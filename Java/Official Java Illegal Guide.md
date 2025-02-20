**Classic 0.0.14a_08**
- Sand and Gravel do not fall into liquids allowing for sand and gravel floating above water

**Classic 0.0.19a_04**
- Sponges would not update to a Wet Sponge when used, allowing for weird, unobtainable positions and states of water

**Classic 0.0.23a_01**
- By placing gravity blocks (sand or gravel) above a water source, the gravity block and the water will swap places, allowing for non-updated water sources.

**Indev 20100124-3**
- The Indev House will spawn upon loading the world, within the Indev House chests full of 99 count items will spawn which is unobtainable in future versions. Among these items are bedrock, grass, and infinite lava items. The Infinite Water Items, 16 Cloth Colors, Sponges, Coal Ore, Obsidian and leaves can also be obtained and will convert to an unobtainable in future versions.
- Exploding A Chest while keeping it open will cause the items inside the chest to convert to 0 stack items. These items are useful for duplication, overstacked items, and understacked items. A 0 Stack item is a the most well known duplication method and java illegal, once you have it you can right click in your inventory and it will give you and infinite amount of diamonds. Every time you right click the 0 stack item, the item count will start going into the negatives allowing for negative durability stacked items, and once it reaches -129 it will overlap and the item count will become +127. This method of 0 stack items works all the way to Alpha 1.2.6

**Indev 20100128-2**
- Indev Chests would spawn with 100 count items allowing for overstacked items

**Indev 20100201-2**
- Sponges would soak up infinite lava and infinite water allowing for discontinued configurations of the water and lava

**Indev 20100206-2**
- Golden Hoes have a higher durability which is later lowered allowing for negative durability hoes if you lower the durability of the hoe in this current version

**Indev 20100209**
-  Any item can be placed in the furnace fuel and output slot

**Infdev 20100316**
> [!Caution]
> This version requires the Infdev 20100316 saving mod to save and quit the game you can find it in the Links folder
> Opening Chests in this version would crash the game
- The Farlands would generate except they are extremely far out, they are a flat wall and they are unreachable by normal means
- The Player would spawn with 999 stacks of axes, shovels, pickaxes, torches, flint and steel, oak planks, glass blocks, and arrows every time you load the world. These are technically -25 stacks which is obtainable, but because of the Chest crash they can not be moved to chests in this version. 
- Brick Pyramids would spawn throughout the world, making it the only method of obtaining bricks

**Infdev 20100607**
- Top Half Doors can be created by placing two signs and placing a door on top

**Infdev 20100611**
- Monoliths would generate in flat terrain and they would spawn without bedrock underneath allowing for illegal terrain generation

**Infdev 20100615**
- Water and Lava can flow next to each other without forming stone
- Lava will flow 8 blocks in the overworld which will later update to 3 blocks making it an illegal block formations
- Water and Lava do not update correctly, allowing for water and lava in different flow states without a source block

**Infdev 20100616-1**
- Holes in the Bedrock can generate when lava pools generate at the bottom of the world

**Infdev 20100617-2**
- The bottom most layer of the world is made of stone and bedrock allowing for holes within the bedrock

**Infdev 20100625-2**
- Added Spawners which can be mined up by hand and will drop as an item, also Infinite Water Source items would convert to a Spawnere as well
- Spawners currently have the same block id as signs. If a sign is loaded near a spawner, the spawner will receive sign metadata. Reloading a sign-spawner will crash and potentially soft lock the world in this version. This is fixed in the next version, but the spawner maintains the sign data.

**Alpha 1.0.1_01 - Infdev 20100630-2**
- Downgrading Redstone that is placed on against a block will convert it to a gear in Infdev 20100630-2. Breaking the block below the gear and updating back to Alpha 1.0.1_01 will create floating redstone

**Alpha 1.0.1_01**
- Activating a lever and then breaking it's support block will keep the lever floating

**Alpha 1.0.4**
- Snow Layers were added but can only be obtained in the Winter Type Map. Snow Layers would generate on top of all blocks during snowfall which allows for illegal block formations like snow layers on non-full blocks (e.g. stairs and slabs)

**Alpha 1.0.5-2**
- Added Block Replacement Bypass, this is involves placing a support blocks directly into water, lava, fire, or snow. This allows for many illegal block formations such as floating flowers, floating ladders, quintuple chests
- Snowballs in this version would stack to 64 allowing for overstacked snowballs

**Alpha 1.0.6**
- Cactus can be placed on and next to any block allowing for many illegal block formations

**Alpha 1.0.11**
- Placing a door next to a cactus would create a half door

**Alpha 1.1.1**
- Fishing Rods would stack to 64 in this version

**Alpha 1.2.0**
- Zombie Pigmen and skeletons appear to hold their weapons but it is all visual, updating these two mobs past 1.3 will turn them into weaponless weaponless mobs
- Lava only flows 4 blocks in the nether

**Alpha 1.2.2**
- In this version it is possible to get to the Farlands in under an hour. The way to do this is to summon a nether portal and place a boat in it, get into the boat, and once you go through the nether the game will become glitched and you will become stuck in the nether portal animation. Save and Quit the game, and when you load back in you will be at the same coordinates in the nether as you were in the overworld. When you generate another portal and go through your coordinates in the overworld will be multiplied 8 times. Doing this over again will cause your coords to multiply 8 types each time until you are all the way at the farlands
- Nether Portals can be summoned by pressing F4 which can be used to get to the Farlands and to create illegal block formations

**Alpha 1.2.6**
- Lava Lakes are able to cut through bedrock if spawned at the bottom of the world

**Beta 1.3.2 - Infdev 20100624**
> [!Note]
> In order to access this version, the world save folder will have to be named as World[1-5]. During this downgrade, the level.dat and level.dat_old should be removed temporarily. A world without a level.dat can be accessed by selecting the respective slot when going to the singleplayer screen. The level.dat and level.dat_old will have to be restored when updating back to b1.3-2 in order to preserve the Alpha File Format folders of the next version. No chunks, entities, or placed blocks will be affected during this downgrade.	
- This version has a file format that is not used in any other version. A folder named "data" is used, and contains "entities.dat" and "zones.dat" This folder will become completely unused upon updating out of this version and nothing will be converted to a different file format. This creates several file discontinued features. 

**Beta 1.2_02-launcher**
- This is the last version that uses the Alpha file format. Since the Alpha File Format from the original world has already been converted, updating to this version will regenerate an entirely new world with the Alpha File Format. This allows for numerous folders in both the world save folder and the DIM-1 folder, that are titled with numbers and letters, which contain subfolders titled with numbers and letters, that contain .dat files, since this is how the Alpha File Format worked. There are hundreds of discontinued folders possible. 	

