# CHANGELOG FOR V1.0
## Added
Added a comprehensive Riverwood overhaul setup.
Added Riverwood Has Walls - A Full Overhaul.
Added Riverwood Has Walls - Optimization.
Added Riverwood Has Walls - PBR - Grey.
Added Riverwood Has Walls - Patches Collection for compatibility with the surrounding Riverwood setup.
Added Ivy - Gates of Riverwood.
Added Ivy - Faendal Home Overhaul.
Added Ivy - Riverwood Small Bridge Replacer.
Added Ivy - Riverwood Windmill Apothecary.
Added Ivy - Riverwood Small Addon.
Added Ivy - Riverwood Well Addon.
Added Ivy - Cozy Corner Patch Hub to provide compatibility patches for the expanded Riverwood
## Removed

## Bugfixes and compatibility

### Fixes and Compatibility
* Fixed the **Dwemer Armor SE** setup by removing the incompatible Italian `.esp` translation used alongside the current `.esl` version, which could cause duplicated armor entries.
* Fixed the **Mythic Dawn Armor SE** HDT-SMP setup by removing the redundant `1NDArmor.esp` plugin and keeping `1NDArmor.esl` as the main plugin.
* Completely revised the **Infantry Armor SE** setup to ensure proper HDT-SMP compatibility.
* Replaced the `1FS.esl` version of **Infantry Armor SE** with the `1FS.esp` variant required by the HDT-SMP configuration.
* Replaced the Xtudo patch intended for the ESL version of **Infantry Armor SE** with the corresponding **ESP** version.
* Manually updated **SPID Infantry Armor SE to Bandits** for compatibility with `1FS.esp`.
* Modified `InfanArBandit.esp` to use `1FS.esp` as its master instead of `1FS.esl`.
* Verified the local FormID correspondence of the four Infantry Armor pieces used by the SPID outfit distribution, preserving the correct helmet, cuirass, gauntlets, and boots references.
* Removed the previous simultaneous `1FS.esl` + `1FS.esp` setup, preventing potential duplicated armor and crafting recipes.
* Corrected the HDT-SMP variant used for **Ysmir Armor SE**, switching from the CBBE 3BA conversion to the variant appropriate for the current body setup.
* Removed the obsolete/redundant Navigator patch for **Children of the North Wind**, keeping only the patch compatible with the current **Navigator - Navmesh Fixes** setup.
* Verified and preserved the correct base ordering for **Cities of the North - Falkreath** and its associated fixes package.
* Cleaned up several `.esl` / `.esp` overlaps and dependencies across armor mods, reducing the risk of duplicated records and incompatibilities between base mods, fixes, translations, and HDT-SMP patches.


## Weapon/Armor Changes/Bugfixes

## Alchemy and Food Changes

## Magic Changes

## Economy Changes

## Visual, Performance and World Changes

## Creation Club Content Changes





