## v1.1.0

### Bug fixes

* Fixes visual bug when hewn rock was mined.
* Vanilla meteorites are replaced by minerals from this mod.
* Fixes flickering textures in the finder tool.
* Fixed a few minor texture issues.
* Fixed bug where mobile mineral sonar does not find ores from Minerals mod.
* Made rubble and other resources not spawn when a rock is damage by a non-pawn source, like meteorites.
* Solid rock is always thin roof or cave wall and weathered rock is always unroofed.

### Gameplay changes

* Added new rock type: Claystone. Yeilds clay chunks or soft clay when mined.
* Added giant versions of quartz, glowstone, and coldstone that can drop something special when mined.
* Increased chunk drop rate for boulders. 
* Reduced slate block drop rate for walls by 70%.
* Reduced rubble drop rate by ~50% for all rocks. 
* Mining output now depends on miner skill.

### Visual changes 

* New textures for quartz, glowstone, and coldstone.
* Added mod config setting to change the visual spread of textures.
* Moved weathered and soild rock textures up to avoid gaps and reduce overlaps with nearby walls. 
* Removed damage graphics from small minerals/rocks.

### Other

* Added Russian translations by skyarkangle.
* Added mod config settings to change resource drop rate and drop amount.
* Dynamic minerals like salt can now spawn in groups instead of one at a time. 


## v1.0.7

* Major update that replaces rock walls, ores, chunks, and adds other rock-related content. Replacement of rocks and chunks can be disabled in the mod's settings menu.
* Compatible with Rimworld 1.0
* Lots of minor and major adjustments
* Some content has been removed in put into optional mods, such as the cut gems and weapons. See [MineralsCraft mod](https://github.com/zachary-foster/MineralsCraft_SK)).
* The mod now has a setting menu where the frequency of each type of mineral or rock and be changed.
* Dravite and Goshenite moved from this mod to MineralsExtra. See [MineralsExtra mod](https://github.com/zachary-foster/MineralsExtra_SK)).
* Starting rock chunks are now removed at map generation. This can be changed in the settings.
* Some minerals now appear to grow up adjacent walls.
* Fixed various graphical bugs when textures overlaped.
* Fixed most of lag assocaited with cold and NPS and improved performance overall.
* Snow appears on rocks.

## v0.6.0

### Bug fixes:

* Various treaders now buy/sell rough gems and cut gems.


## v0.5.0

This version splits the mod into a few different mods:

* Minerals Core: Minerals with unique appearance and unique uses and all the C# code.
* Minerals Extra: Lots of other minerals to add variety, but usually similar in use/appearance to some other mineral. Many are rare minerals that drop lots of gemstones.
* Minerals Frozen: Did you know ice is a mineral? This mod adds snow and ice formations, which can be "mined" for blocks that can be used to build things. However, anything built with snow or ice will take damage when it is above freezing. 

** It might be save-game compatible if you update and use all three mods on the old save, otherwise it will not be save-game compatible. **
 
* Less mineral abundance overall
* Generally increased drop amounts
* Lots of other adjustments

## v0.4.3

### Bug fixes:

* Save/load no longer makes all minerals go to 100%


## v0.4.2 

### Aditions:

* 7 new static minerals: Tourmaline group
* 2 new minerals: growning sulfur and larger static sulfur
* 4 new static minerals: Corundum group
* 6 new static minerals: Beryl group
* 2 new static minerals: Magnetite and lodestone
* 1 new static minerals: Diamonds
* 2 new static minerals: Malachite and Azurite
* 1 new static minerals: Uraninite
* 1 new static minerals: Cassiterite

### Improvements:

* New print method now uses normal distributions, so clusters look more natural
* "neededNearbyTerrains" now can be used with "things" like buildingd and steam geysers.
* Minerals can now stack on eachother

### Changes

* Increased gem drop rate a bit
* increased rough gem and gem value 
* Made flint less pretty
* Increased sharp stone stack count to 150
* Quartz is now outside of caves as well
* increased yield of flint nodules and obsidian
* Lots of other small adjustments 

### Bug fixes:

* Ice stalagmites dont drop sand anymore

## v0.3.1

### Bug fixes:

* Large minerals no longer block pawns

## v0.3.0

### Bug fixes:

* Minerals falling as meteorites are now full grown and not stacked.
* A few bugs with sharp stone arrows are fixed
* Now dynamic minerals only reproduce when growing
* Missing stuff icon added for sharp stones

### Changes

* Flint is more common
* Tribal tools take less work to make
* Coldstone melts faster and it a bit more common

### Improvements

* New mineral: ice stalagmites
* New mineral: pyrite
* New weapon: Macuahuitl
* Minerals are more likely to spawn near associated ores
