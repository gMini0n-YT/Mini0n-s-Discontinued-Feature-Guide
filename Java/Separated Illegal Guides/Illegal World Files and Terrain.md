_____________________________________________________________________________________________________________________________________

***KEY WORDS***

**Upgrading:** Upgrading from X.XX.XX to Y.YY.YY to obtain a certain illegal
<br>

**Downrading:** Downgrade from X.XX.XX to Y.YY.YY to obtain a certain illegal
<br>

**EDU:** MinecraftEDU is a modified fork of Minecraft Java Edition, and is an educational form of Minecraft
<br>

**Mod:** Requires a Mod from "Mods & Extra Files" that can let you either play the version or obtain certain unobtainables
<br>
_____________________________________________________________________________________________________________________________________


**Infdev 20100316**
> [!Caution]
> This version requires the Infdev 20100316 saving mod to save and quit the game you can find it in the Links folder
> Opening Chests in this version would crash the game
- The Farlands would generate except they are extremely far out, they are a flat wall and they are unreachable by normal means
- Brick Pyramids would spawn throughout the world, making it the only method of obtaining bricks, download the file in the "Mods & Extra Files" folder to help you find brick pyramids

**Infdev 20100611**
- Monoliths would generate in flat terrain and they would spawn without bedrock underneath allowing for illegal terrain generation. You can use the Monolith Finder in the "Links" folder

**Infdev 20100615**
- Caves do not generate in this version allowing for an area with no caves
- In this version no Bedrock will spawn at the bottom of the world. These chunks can be loaded by left unpopulated, if these chunks are then repopulated in later versions then not only will no bedrock generate but the world will generate new stone types and biomes.

**Infdev 20100616-1**
- Holes in the Bedrock can generate when lava pools generate at the bottom of the world

**Infdev 20100617-2**
- The bottom most layer of the world is made of stone and bedrock allowing for holes within the bedrock

**Alpha 1.2.6**
- Lava Lakes are able to cut through bedrock if spawned at the bottom of the world

**Beta 1.3.2 - Infdev 20100624**
> [!Note]
> In order to access this version, the world save folder will have to be named as World[1-5]. During this downgrade, the level.dat and level.dat_old should be removed temporarily. A world without a level.dat can be accessed by selecting the respective slot when going to the singleplayer screen. The level.dat and level.dat_old will have to be restored when updating back to b1.3-2 in order to preserve the Alpha File Format folders of the next version. No chunks, entities, or placed blocks will be affected during this downgrade.	
- This version has a file format that is not used in any other version. A folder named "data" is used, and contains "entities.dat" and "zones.dat" This folder will become completely unused upon updating out of this version and nothing will be converted to a different file format. This creates several file discontinued features. 

**Beta 1.2_02-launcher**
- This is the last version that uses the Alpha file format. Since the Alpha File Format from the original world has already been converted, updating to this version will regenerate an entirely new world with the Alpha File Format. This allows for numerous folders in both the world save folder and the DIM-1 folder, that are titled with numbers and letters, which contain subfolders titled with numbers and letters, that contain .dat files, since this is how the Alpha File Format worked. There are hundreds of discontinued folders possible. 	

**Beta 1.3.2**
- World names can contain the section symbol § and will format the name which will become unobtainable in later versions.

**Beta 1.9 Prerelease 3-1**
> [!Note]
> Certain multiplayer exclusive chunks can be obtained, however it requires file manipulation. Regions from a newly generated multiplayer world can be copied into the pre-existing world. This would work by taking a region file, changing the numbers to not conflict with previously existing region files, and adding them to the preexisting world.
- Currently "Sky Dimension" chunks generate in a new multiplayer world. These are large floating islands that generate in the overworld, with large sections of void and no bedrock. There is no way to obtain these chunks in a pre-existing world, however the region files can be moved from a newly generated multiplayer world to the preexisting world by renumbering the newly generated region files

**Beta 1.9 Prerelease 6**
- The exit portal would generate when the ender dragon is killed but the exit portal would generate where the dragon died and not at 0,0 allowing for the exit end portal in discontinued locations

**1.1**
- The unicode delete character [] can be typed into a world name by pressing ctrl + backspace. This is the only version where a world can be named with both the delete character [] and the section symbol [§], making this the ideal version to name your world.

**12w07a**
- The file format is now Anvil instead of MCRegion. This converts all .mcr files to .mca, however the .mcr files are maintained within the world save folder for all three dimensions. Additionally, a level.dat backup is taken named level.dat_mcr. These are all discontinued files
- The End in this version does not generate with any main end island it is just you and the void. Additionally when you kill the ender dragon the exit portal will spawn where the dragon died instead of at 0.0


**0.982 Classroom (EDU)**
- A file called EduWorldSettings.ini is generated within the world save. A folder called MCEdu is created within the world save, which includes a file named signLocations_en.ini and a file named tips_en.txt. Within the MCEdu folder a file called infoLocations_en.ini is created when an information block is placed and the game is saved. The teleportLocations_en.ini, teleportLocations.ini, and allowedteleports.ini files are created when a station block is placed and the game is saved. These files and folders are exclusive to Edu versions, and will be discontinued in future versions. 
- Player data is saved in the players folder under username.dat. Additionally, server.log and server.log.lck are created within the world folder. The server log contains the entire chat output. These files are multiplayer exclusive, and will become discontinued in future versions.

**0.984 Classroom (EDU)**
- A file called EduWorldSettings.ini is generated within the world save. A folder called MCEdu is created within the world save, which includes several files that are gnenerated when the server is launched. These files and folders are exclusive to Edu versions, and will be discontinued in future versions.

**12w21a**
- When creating a new world, if the name picked matches a current world folder name, additional characters will be added to the new folder name. The actual world name will only be the original picked name, which must be within the 32 character limit. However, if the game closes out while generating the world, the folder name will be applied to the world name, regardless of the folder name length. From 12w18a through 19w11b, world names would uses dashes after the name, and from 19w12a+ a number in parentheses is added to the end. The longest possible name is a bit complicated to figure out, since it is limited to the longest possible folder name, and the maximum length of the folder name is determined by the length of the file path, which is limited to 248 characters. Due to the version range,

**12w32a-2**
- Within the data folder, the villages.dat file now generates. This file tracks player made villages, and will become discontinued in future versions

**1.6.3-1**
- Bounding boxes now save with the world. In order for current structures (witch huts, nether fortresses, etc.) to be saved to the world file, the player must load the appropriate chunks within the game manually. After this is completed, structures will be compatible in all snapshots starting with snapshot. All these bounding boxes will not be obtainable in their current locations in future versions.
- These bounding boxes are stored in structure files, which are generated when the respective structure is loaded. These files are Village.dat, Fortress.dat, Temple.dat, Mineshaft.dat, and Stronghold.dat. All of these files will be discontinued in a future version.

**1.6.4 Build 1 Classroom-1 (EDU)**
- A file called forcedchunks.dat generates within the world save folder, which will become unobtainable in non edu versions

**13w37b**
- Bounding boxes now save with the world. In order for current structures (witch huts, nether fortresses, etc.) to be saved to the world file, the player must load the appropriate chunks within the game manually. After this is completed, structures will be compatible in all snapshots starting with snapshot. All these bounding boxes will not be obtainable in their current locations in future versions.
- These bounding boxes are stored in structure files, which are generated when the respective structure is loaded. These files are Village.dat, Fortress.dat, Temple.dat, Mineshaft.dat, and Stronghold.dat. All of these files will be discontinued in a future version.

**1.7.10 Build 1 Classroom-1 (EDU)**
- Player data is saved in the playerdata folder under username.dat. This will become unobtainable in future versions as it is stored as a UUID instead of a username. Additionally, since you are logging in in offline mode, the UUID for the statistics is different, allowing for multiple statistic files in a singleplayer world.

**1.7.10 Build 20 Classroom-1 (EDU)**
- The computer process allows for the writing of external files, meaning essentially any file can be created within the world save, all of which would be discontinued. Upon world save the computer folder is generated, which is a discontinued folder.

**14w02a**
- Currently the files village_nether.dat and villages_end.dat generate in the data folder. These are discontinued files.
- Data is again stored by username instead of UUID. This allows for a statistic file with the players username that will not convert to a UUID. This also means that statistics will not be accurately tracked during this version. This occurs because the change to UUID was based on real world time instead of version ordering. 

**1.8.9 Build 3 Classroom (EDU)**
- Player data is saved in the playerdata folder under username.dat. This will become unobtainable in future versions as it is stored as a UUID instead of a username. Additionally, since you are logging in in offline mode, the UUID for the statistics is different, allowing for multiple statistic files in a singleplayer world.
- Files called EduWorldSettings.ini, EduMapSettings.ini, and forcedchunks.dat generate within the world save. A folder called MCEdu is created within the world save, which includes several files that are gnenerated when the server is launched. Another folder called region_eduf1_backup is created upon world save, and contains a copy of the region files. These files and folders are exclusive to Edu versions, and will be discontinued in future versions.
- The computer process allows for the writing of external files, meaning essentially any file can be created within the world save, all of which would be discontinued. Upon world save the computer folder is generated, which is a discontinued folder.

**16w39a**
- The file Mansion.dat now generates in the data folder, which will be unobtainable in future versions

**1.11.2 (MOD)**
> [!Note]
> This version uses Forge 1.13.20.2235 for version 1.11.2. This version can be downloaded from the forge link in "Links", and added to the official minecraft launcher, or it can be added directly from multimc. Adding to multimc requires creating a 1.11.2 instance, then going to edit instance, then install forge, then scrolling down to the correct version of forge and selecting it.
- Shulkers can be put into other shulkers by using a hopper. This only works due to the forge version that is being used. Nested shulkers are normally unobtainable.
- The capabilites.dat file generates in the data folder, and the forcedchunks.dat file generates in the world save folder and the two DIM folders. These are all discontinued files exclusive to the mod used.

**17w13a-1**
- Added Advancements to replace Acheivements. Support for custom advancements was added, meaning an empty folder called Advancements is generated in the data folder. This folder is unobtainable in future versions.

**1.12 Prerelease 1**
- Added a function system. This causes an empty folder named functions to generate in the data folder, which is unobtainable in future versions.

**18w08a**
- The deep warm ocean biome will be temporarily discontinued in future versions. Ocean monuments can currently generate in a deep warm ocean biome, which in future versions will convert to a warm ocean biome. An ocean monument in a warm ocean biome is normally unobtainable, making this a discontinued feature.

**18w46a**
- Void End Rings would generate from this version to the current version. The edge of these rings is always aligned to an 8×8 grid and can cause "cuts" (completely smooth, flat surfaces) when intersecting with outer end islands. Other structures, such as the small circular end islands, chorus plants, gateways and end cities are not cut off when crossing the border, but also do not generate inside the void ring. The first ring that generates starts at 370,728 and ends at 524,288

**19w36a**
- This version introduced new gamerules. These included drowningDamage, fallDamage, fireDamage, and doInsomnia. These rules are normally defaulted to true, however updating your world to this version causes them to be set to false, which allows for 4 discontinued gamestates. These cause the player to take no drowning, fire, or fall damage. This also prevents phantoms from spawning, causing phantoms to become a discontinued feature. Phantom membranes are still obtainable through cats.

**20w14∞**
> [!Note]
> In order to play your world in this version, world save insertion must be used. This requires first removing the world save from the world saves folder. From here, select create world and create a world with the same folder name as the world save. Then, while still in the create world screen, drag the world save into the saves folder, and select create world. This forces the world to load without removing the level.dat or level.dat_old files.
- Each dimension has it's own DIM folder, all of which are normally unobtainable. This allows for theoretically over 2 billion discontinued folders.
- Currently, a level.dat and level.dat_old file generate, however they have the name special_level.dat and special_level.dat_old. These are both normally unobtainable files.
- Added the /debugdim command. This command can be used in survival, and creates debug files for whichever dimension you are in. This allows for a large assortment of discontinued files within the world save.

**21w05b (Datapack)**
> [!Note]
> This version requires the same Caves & Cliffs Datapack from the previous version, meaning no file editing is required if updating from the previous version
- The world height is now increased to 320, and extends below to -64. Any new chunks generated in this version with the datapack will have solid stone generate underneath all chunks extending down from Y0 to Y-64, with no bedrock.

**21w19a**
sed to overfill a chunk and perform both chunk savestating and chunk regeneration, which will be further utilized in later versions.
- Obtaining a large bundle and attempting to save, and crashing the game at a precise time during this save can create a level#############.dat file, which is a file discontinued feature will not be obtainable in future versions. Similarly, by performing this crash while attempting to save a chunk containing more data than allocated ram, a tmp###################.tmp can be created in the region folder, which is another file discontinued feature that will not be obtainable in future versions.

**22w17a**
- The player receives a new uuid in this version, allowing for pets to have an invalid owner id, and for multiple statistic and advancement files

**23w13a_or_b**
- Votes are stored in the world file in a vote.json file, as well as generating a backup file of vote.json_old. Both of these are discontinued world files.
- The moon dimension generates in a dimensions folder. The dimensions folder does not normally generate in the world folder, allowing for several discontinued folders and files.

**24w14potato-1**
> [!Note]
> In order to play your world in this version world save insertion must be used. This requires first removing the world save from the world saves folder. From here, select create world and create a world with the same folder name as the world save. Then select the Datapacks or Experimental option and enable the Update 1.21, Villager Trade Rebalance, and the Bundle datapack. Then, while still in the create world screen, drag the world save into the saves folder, and select create world. This forces the world to load without removing the level.dat or level.dat_old files.
- The potato dimension generates in a dimensions folder. The dimensions folder does not normally generate in the world folder, allowing for several discontinued folders and files.

**25w14craftmine**
- In the dimensions/minecraft folder of your world, new level# (with # replaced by the level number) folders can be created in 25w14craftmine. There is no way to reach these dimensions after 25w14craftmine, making this a file discontinued feature.
- In the data folder of your world, a new mine_data.dat file is created in 25w14craftmine that remains after updating out of the version
- For each level created in 25w14craftmine, a datapack will be created to specify that level's dimension properties. They will remain after WSI, but will not properly register their dimensions due to using minecraft:generated as the type field, which is not a registered type by default
- The memory lane extends all the way past the world border. Downgrading from the April Fools' snapshot results in a hallway of stone and gray stained glass being past the world border around -30000000, 0, 8. Other chunks past the world border will be full of air.
- Many of the player unlocks in 25w14craftmine achieve their effects by giving the player an attribute modifier, which are not removed when updating out of this version (unless their attribute exists only in 25w14craftmine).
-  When inside a mine with the One HP mine ingredient the player is given an attribute modifier that reduces max health by 19. The modifier is cleared upon leaving the mine, but it can be preserved by updating out of 25w14craftmine without leaving the mine.
-  Using a mine revisitor to visit an old mine sets the player's game mode to adventure. Dying in a mine in multiplayer sets the player's game mode to spectator. These game modes can be preserved by logging off and updating out of craftmine.
