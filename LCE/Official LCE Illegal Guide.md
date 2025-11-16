_____________________________________________________________________________________________________________________________________

***KEY WORDS***

**Upgrading:** Upgrading from X.XX.XX to Y.YY.YY to obtain a certain illegal
<br>

**Downgrading:** Downgrade from X.XX.XX to Y.YY.YY to obtain a certain illegal
<br>
_____________________________________________________________________________________________________________________________________

**Pre-TU 1.66.0033.0**
- Currently crafting wooden slabs in this version will convert them to be Petrified Oak Slabs
- Any item can be placed in a furnace slot allowing for multiple discontinued features
- Any block that requires support can be placed on a chest by placing it against a block that cannot hold support blocks such as glass and do this adjacent to the chest
- Currently a player_{xuid}.dat file is made which will not be made in future versions

**TU1**
- Blowing up a chest while spam clicking an item in and out of the chest has a chance for it to become a 0 stack item allowing for overstacked and under stacked items

**TU3**
- Block transmutation can work by updating a budded piston at the same time another piston pushes a block, merging the blocks. This allows for many variations of invalid data value blocks. 

**TU5**
- Block transmutation can work by building a piston and water based contraption. This allows for many variations of invalid data value blocks. This will be further utilized in later versions. 
- Currently Enderpearls stack to 64, which is unobtainable because later the stack size will change to 16
- By updating the previous world, a tag will be added to the world folder signifying the sea level is from an old world, the "newSeaLevel:0" tag 
- Mining Stone brick stairs in different orientations drop stone bricks with various data values, allowing for Invalid Data Value Stone Bricks

**TU7**
- Using Silk Touch on leaves in different orientations allows for Invalid Data Value Leaves

**TU14**
- Every trade that a villager has will become discontinued in some way in future versions
- Silk Touch can be applied to shears in an anvil
- Anvils drop the correct damage value of anvil when mined, meaning a slightly damaged anvil drops a data value 1 anvil and a very damaged anvil drops a data value 2 anvil. In future versions, crafting an anvil will create a data value 2 anvil, and mining any anvil will drop a data value 0 anvil, making data value 1 anvils discontinued in future versions. 
- Currently renaming an item in an anvil only adds 2 tags: the display name and the repair cost 

**TU17**
- By aligning against the side of a vine and placing a ladder inside the vine, the ladder will either become a data value 0 ladder or floating ladder, depending on direction, both of which will be unobtainable in future versions 

**TU19**
- Mobs can now equip armor, including helmets. Skeletons and zombies in the sun will cause the helmet to lose durability, which has a chance of reducing the helmet below 0 into negative durability. These negative durability helmets are not obtainable normally, and are technically unobservable fromr regular helmets. Negative durability helmets can be further combined in a crafting table to go further negative down to -32767 
- Currently firework rockets are crafted without any flight duration, which will not be obtainable in future versions. 
- Updating any mobs from earlier versions will cause them to lose the item they are holding, resulting in weaponless skeletons and weaponless zombie pigmen 
- A pig struck by lightning will create a weaponless zombie pigmen
- Killing a mob attached to a fence with a lead will leave the lead attached to the fence. A lead on a fence without a mob is not obtainable in future versions. 

**TU25**
- Picking up stacks of doors in the inventory will behave oddly, leaving 1 door left in the inventory slot, and combining the rest of the stack with whatever the stack size is of the currently held item. Using this combining method, the item stack size can be overflowed past 64, allowing for overstacked and understacked items, which can be preserved in the inventory by dropping the stack on the ground and picking it up. The stack can only be stored in the inventory, it cannot be moved to a chest. 

**TU31**
- Villagers that spawn in this version will have certain trades with a rewardExp value set to 0, meaning these trades do not provide xp. These no xp trades will be discontinued in future versions. 

**TU43**
- Mining frosted ice with silk touch drops the frosted ice item, which is not obtainable in future versions

**TU46**
- Loading a spawner from earlier versions in this version and allowing it to spawn mobs once creates a mob spawner without any block entity data, which will not be obtainable in future versions. This mob spawner will render as a pig spawner. 
- Currently naming items in an anvil adds only 3 tags, the display name, the repair cost, and a "createdOnHost" tag. This differs from named items in earlier versions, which are missing the "createdOnHost" tag, and from named items in future versions, which also contain the tag "createdByRestricted". 
- Crafting bone blocks currently creates bone blocks with a data value of 4, which is an invalid data value variant of bone blocks 
- Entites updated to this version have the drop chance of their left hand set to 0, even though it is normally 0.85.

**TU54**
- Woodland Mansions can generate with spider rooms, which currently contain a spawner without entity data. The spawner will look like a pig spawner and not spawn anything, and will not be obtainable in future versions. 
- Currently armor stands can be named with a nametag. The name does not render, however it does have a custom name. An armor stand with a custom name is normally not obtainable. 

**TU60**
- Ender dragons can ride boats, which will not be obtainable in future versions
- Cauldrons now emit a signal strength of 6 instead of 3, which is an invalid block configuration 

**TU69**
- By filling up the snow golem spawn cap and then building a snow golem sideways around a piece of bedrock, the snow golem will attempt to spawn, fail, and then drop the bedrock as an item, making it obtainable