# Chunks

# Chunk Basics

Minecraft dimensions are all made up of chunks. A chunk is 16 blocks long in the x and z dimensions and is infinitely long in the y dimension. Chunks are made upof sub-chunks, sub chunks are 16 blocks in lemgth in all dimensions: x, y, and z. Stacking these sub-chunks infinitely on each other makes up a chunk. All four corners of the chunk can be determined without external tools because they will always be divisible 16.

The corner with the least x and z value is called the *block coordinates*. The block coordinates divided by 16 is called the *chunk coordinates*. Chunk coordinates are used to differentiate different chunks from each other.

In minecraft there is a class called `Chunk` in MCP and `WorldChunk` in Ornithe. Instances of these classes will be called "Chunk instances".

In each minecraft dimension, `Chunk` instances are stored on a chunk hashmap and they are associated with the x and z coordinates of the minecraft dimensions. The chunk is considered *loaded* if the chunk coordinates in the hashmap are the same as the chunk coordinates in the world. Otherwise the chunk is considered *unloaded*
