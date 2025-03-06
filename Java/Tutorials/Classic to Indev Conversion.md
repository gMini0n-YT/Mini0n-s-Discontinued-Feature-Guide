# Classic to Indev Conversion Process

1. First you need to download MCedit and NBTExplorer which will be linked at the bottom of the page
2. Save your Classic World using BetaCraft or outside Mods
3. Create a world in Indev 20100124 and save the world
4. Locate your classic world folder and rename it to level (dimensions).mine. The dimensions of the world are usually 256 256 64, (width, length, height) if the world size is diffrerent than change the name to the appropriate world size
5. Then open MCEdit, click on "Open a level..." and load your classic world
6. Once world is loaded, select all chunks using "ctrl+a" and then click export and save it as a schematic
7. Once saved, open the newly made schematic file in NBTExplorer
8. Once loaded, click on the level.dat dropdown, and underneath double click the "Blocks" nbt and it will load up showing a bunch of random binary
9. Then Click Export on the binary block nbt and save it under a custom name
10. Then Stay in NbtExplorer, but this time open up the Indev world that you created in Step 3 in NbtExplorer
11. Once opened, double click on the "Blocks" nbt under the "Maps" folder and select import
12. Import the binary file that we exported in Step 9, and once done click the save button
13. You can then open up your world, but if you want to be safe, you can open up the Indev world now and it should look like your classic world

**External Links**
Betacraft: https://betacraft.uk/downloads
MCEdit: https://www.mediafire.com/file/nw9000858y15435/Ultimate_Old_World_Conversion_Guide_V3.0.zip/file
NBTExplorer: https://sourceforge.net/projects/nbtexplorer.mirror/
