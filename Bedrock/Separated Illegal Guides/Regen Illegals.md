______________________________________________________________________________________________________________________________________
***KEY WORDS***

**(Android)**: Android Exclusive Version
<br>
**(UBC)**: The process of downgrading a block to another version converting it to an Unknown Block, mining it up, and then upgrading to 1.21.30 to obtain the block
<br>
**(Experimental)**: Turning on the Experimental Toggle
<br>
**(X.XX.XX.X - Y.YY.YY.Y)**: Version Upgrading or Downgrading from and to 
<br>
**(0.12.1 Downgrade**): Downgrading client to 0.12.1 and renaming world you would like to downgrade will cause the world to downgrade to 0.12 without any corruption. This allows to easily downgrade to any version above 0.12.1. 
**VCR**: Valid Chunk Regeneration, the process of regenerating blocks without removing it's block states and entities: (e.g. floating support items, duplication)
<br>

**ICR**: Invalid Chunk Regeneration, the process of regenerating blocks and removing it's block states and entities, this only works on Block Entities (e.g. chests, enderchests), everything else that is not a block entity will be regenerated like in VCR
<br>
**USR**: Update Suppression Regen, using an Update Suppressor https://www.youtube.com/watch?v=FswCxCU3lzc to create an illegal formation and then saving & quitting and breaking the formation and save & quitting again to regen the blocks after all the pending ticks have disappeared. Full Tutorial in "UpdateSuppressedRegenGuide" in the "Links" Folder
______________________________________________________________________________________________________________________________________
**To Help you Find the Lowest Subchunk and the Chunk Boundaries, download the "Bedrock-Chunk-Boarders-Pack" in the "Texture Pack" folder**

****VCR****
<br>
Note: Formations ending in ^ have their obtaining method listed at the bottom of the VCR section of the Document
<br>
**Floating Side Support Block (including Side Support Blocks on Invalid Blocks)**
- Torches, Soul Torches, Redstone Torches
- Signs (All Types)
- Item Frames, Glow Item Frames
- Bells
- Levers
- Buttons (All Types)
- Tripwire
- Banners
- Glow Lichen
- Amethyst Clusters
- Amethyst Buds (Large, Medium, Small)
- Skulk Veins
- Ladders
- Vines
- Grindstones

**Floating Top Support Block (Including Top Support Blocks on Invalid Blocks)**
- Amethyst Cluster
- Amethyst Buds (Small, Medium, Large)
- Spore Blossom
- Pointed Dripstone
- Grindstones
- Weeping Vines
- Hanging Roots
- Hanging Pale Roots
- Lanterns/Soul Lanterns
- Hanging Signs/Attached Hanging Signs (all wood types)
- Bells
- Glow Berries (all growth stages)
- Item Frames/Glow Item Frames
- Bells
- Levers
- Buttons (all types)
- Glow Lichens
- Sculk Veins

Glitched Pistons/Sticky Pistons:
- Unextendable Pistons/Sticky Pistons (having the head regenerated in the way)
- Pistons/Stick Pistons Without Piston/Sticky Piston Heads
- Piston/Sticky Piston Heads Without Pistons/Stick Pistons

Flowing Liquids^:
 - Flowing Water (all liquid depths)
 - Flowing Lava (all liquid depths)

Waterless Alive Coral Blocks^:
 - Tube Coral
 - Brain Coral
 - Bubble Coral
 - Fire Coral
 - Horn Coral

Invalid Liquid Placements:
 - Water & Lava Flowing Into Each Other
 - Lava Next To Waterlogged Block
 - Water and Lava Next to Each other

Invalid Portal Formations:
 - Half/Quarter Nether Portal
 - Half/Quarter End Portal
 - 1 to 3 Sides Of Nether Portal Removed
 - 1 to 3 Sides Of Nether Portal Replaced (any tile)
 - 1 to 2 Sides Of End Portal Removed
 - 1 to 2 Sides Of End Portal Replaced (any tile)

Incomplete Block Transformations^:
 - Water Touching Dry Sponge
 - Water Touching Concrete Powder
 - Lava On Soul Soil Touching Blue Ice (all liquid depths)

Permanent Frosted Ice (any age)

Pressed Buttons (Any Type)

Pressed Pressure Plates (Any Type)

Bottom Half of Blocks (Place the bottom half 1 block below the 2nd to bottom subchunk)
- Pointed Dripstone (2+ Tall)
- Big Dripleaf (2+ Tall)
- Small Dripleaf (2+ Tall)
- Pitcher Plant (Fully Grown)

Invalid Placement Cactus (all tiles)

Floating Scaffolding (all stabilities)

Invalid Placement Chorus Plant

Permanently Activated Rails
- Permanently Activated Powered Rail
- Permanently Activated Detector Rail
- Permanently Activated Activator Rail

Permanently Pressed Buttons

Permanently Pressed Pressure Plates

Permanent Suspicious Sand/Gravel (All Dusted Levels)

Walls Connected to Nothing

Beds inside Blocks (Placing only Half of the Bed in the VCR Chunk and breaking it and placing a block where the other half of the bed was, when regening it, it will show the bed inside the block)

Waterless Alive Coral Blocks:
 + Set up a long water stream ending on the border of an empty chunk (DO NOT LET THE WATER FLOW INTO THE CHUNK),
 + Place coral blocks into the empty chunk next to the think layer of flowing water so it stays alive,
 + Save & Quit then rejoin,
 + Break the coral blocks to empty the chunk again and remove the water source,
 + Save & Quit then rejoin and the coral blocks should stay alive without water.

Incomplete Block Transformations:
 - Dry Sponge & Concrete Powder Next To Water:
   + Set up a path for a long water stream ending on the border of an empty chunk,
   + Place dry sponge/concrete powder blocks into the empty chunk next to where the think layer of flowing water will be,
   + Save & Quit then rejoin,
   + Break the dry sponge/concrete powder blocks to empty the chunk again and add the water source so it flows ALMOST into the empty chunk,
   + Save & Quit then rejoin and the dry sponge/concrete powder blocks should stay the same whilst next to water.
 - Lava On Soul Soil Touching Blue Ice:
   + Set up lava that flows NEARLY into the empty chunk,
   + Place soul soil underneath the lava closest to the chunk border,
   + Place blue ice into the empty chunk so it touches the flowing lava,
   + The lava should turn into basalt (this is intentional),
   + Save & Quit then rejoin,
   + Break the blue ice then mine the basalt wait for the lava to flow back into where the basalt was,
   + Save & Quit then rejoin and the blue ice should've regenerated next to the lava without turning it into basalt.
  
****ICR****
<br>
**Placing any of these Block in an ICR Chunk (you can tell by looking at the "ChunkRegenerationGraph.webp" in the "Files" Folder) will remove their Block Entities and make them completely unusable, invisible, or stuck in their current state**
- Unusable Beehives
- Unusable Beenests
- Invisible Signs
- Invisible Hanging Signs
- Permanently Unactivated Skulk Sensor
- Permanently Activated Skulk Sensor
- Permanently Unactivated Calibrated Skulk Sensor
- Permanently Activated Calibrated Skulk Sensor
- Permanently Unactivated Skulk Catalyst
- Permanently Activated Skulk Catalyst
- Permanently Unactivated Skulk Shrieker
- Invisible Banner
- Invisible Chest
- Invisible Trapped Chest
- Invisible Shulker Box
- Unusable Dispenser
- Unusable Dropper
- Unusable Barrel
- Unusable Chiseled Bookshelf
- Invisible Decorated Pot
- Unusable Furnace
- Unusable Smoker
- Unusable Blast Furnace
- Unusable Lit Furnace
- Unusable Lit Smoker
- Unusable Lit Blast Furnace
- Unusable Brewing Stand
- Unusable Campfire
- Unusable Soul Campfire
- Unusable Extinguished Campfire
- Unusable Extinguished Soul Campfire
- Unusable Hopper
- Unusable Lectern
- Unusable Crafter
- Unusable Activated Crafter
- Unusable Beacon
- Unusable Spawner
- Unusable Trial Spawner
- Unusable Activated Trial Spawner
- Unusable Activated Trial Vault
- Unusable Trial Vault
- Unusable Note Block
- Unusable Item Frame
- Unusable Glow Item Frame
- Invisible Extended Piston Head
- Invisible Extended Sticky Piston Head
- Invisible Unextended Piston Head
- Invisible Unextended Sticky Piston Head
- Unusable Juke Box
- Unusable Enchanting Table
- Invisible Player Head
- Invisible Zombie Head
- Invisible Creeper Head
- Invisible Skeleton Skull
- Invisible Wither Skeleton Skull
- Invisible Piglin Head
- Invisible Ender Dragon Head
- Unusable Command Block
- Unusable Chain Command Block
- Unusable Repeating Command Block
- Unusable Structure Block Variants
- Unusable Jigsaw Block
- Unusable Daylight Sensor
- Unusable Flower Pot
- Unusable Redstone Comparator
- Unusable Powered Redstone Comparator
- Invisible Bed
- Unusable Cauldron
- Invisible Conduit
- Invisible Bell
- Unusable Lodestone
- Unusable Suspicious Sand
- Unusable Suspicious Gravel
- Activated Tripwire
- Activated Observer
- Activated Dripleaf
- Permanently Activated Observer

****USR****

Things on Every Block
- Cactus on Every Block
- Every Plant-Based Foliage on Every Block (including itself)
- Soul Fire on non-soul Blocks
- Fire on Soul Sand Blocks
- Torches on Any Block (including itself)
- Sea Pickles on Glowstone and Sealanterns, and itself
- Azaleas on Every Block (including itself)
- Ladders Connected to nothing or any block (including itself)
- Buttons on Fence Gates and Walls
- Redstone Repeaters on any Block (including itself)
- Redstone Comparator on any Block (including itself)
- Redstone Dust on any Block (including itself)
- Bubble Column without Water
- Bubble Columns without Soulsand/Magma Block
- Chrous Plant on any Block
- Chrous Flower on Any Block
- Rails on Any Block (including itself)
- Bells on Any Block (including itself)
- Levers and Buttons on any Block (including itself)
- Hanging Signs on Any Block
- Dripstone on Any Block (including itself)
- Flowerpots on any Block (including itself)
- Amethyst Clusters/Buds on Any Block
- Lit Creaking Heart without Pale Oak Logs
- Unlit Creaking Heart with Pale Oak Logs

Waterlogged Anything
- Waterlesss Seagrass
- Waterless Kelp
- Waterless Tall Seagrass
- Waterlogged Foliage
- Waterlogged Redstone
- Waterlogged Torches
