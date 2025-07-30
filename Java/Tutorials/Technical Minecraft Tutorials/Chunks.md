# Chunks

# Chunk Basics

Minecraft dimensions are all made up of chunks. A chunk is 16 blocks long in the x and z dimensions and is infinitely long in the y dimension. Chunks are made upof sub-chunks, sub chunks are 16 blocks in lemgth in all dimensions: x, y, and z. Stacking these sub-chunks infinitely on each other makes up a chunk. All four corners of the chunk can be determined without external tools because they will always be divisible 16.

The corner with the least x and z value is called the *block coordinates*. The block coordinates divided by 16 is called the *chunk coordinates*. Chunk coordinates are used to differentiate different chunks from each other.

In minecraft there is a class called `Chunk` in MCP and `WorldChunk` in Ornithe. Instances of these classes will be called "Chunk instances".

In each minecraft dimension, `Chunk` instances are stored on a chunk hashmap and they are associated with the x and z coordinates of the minecraft dimensions. The chunk with chunk coordinates x and z is considered *loaded* if there is a `Chunk` instance in the hashmap with the same x and z coordinates as the chunk. Otherwise the chunk is considered *unloaded*

# Chunks Loaded By Player

In Minecraft's code there is a class called `PlayerChunkMap` in MCP or `ChunkMap` in Orinthe feather mappings. These classes keep track of the chunks loaded by the player's view distance.

The `PlayerChunkMap` keeps track of where the player is on the world. So when the player logs off and back on, it will read the information from the `PlayerChunkMap` and place the player at the coordinates given. The `PlayerChunkMap` updates every time the player moves 8 blocks away from the position previously logged in the class. Whenever the position of a player in the PlayerChunkMap is updated, it also immediately updates what chunks are within view distance of the player.

If a already generated chunk comes into render distance of the player the chunk becomes loaded. If a chunk moves outside of the player's render distance it is set to become unloaded

# Spawn Chunks

Spawn Chunks are 17 by 17 chunk areas that are always loaded when the server starts. The player does not need to be in render distance of the spawn chunks, they will always be loaded until the player logs out. These Spawn Chunks have been removed as of 25w31a
