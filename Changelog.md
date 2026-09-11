# CHANGELOG FOR V1.0
## Added
- Added a comprehensive **Riverwood overhaul** setup.
- Added **Riverwood Has Walls - A Full Overhaul**.
- Added **Riverwood Has Walls - Optimization**.
- Added **Riverwood Has Walls - PBR - Grey**.
- Added **Riverwood Has Walls - Patches Collection** for compatibility with the surrounding Riverwood setup.
- Added **Ivy - Gates of Riverwood**.
- Added **Ivy - Faendal Home Overhaul**.
- Added **Ivy - Riverwood Small Bridge Replacer**.
- Added **Ivy - Riverwood Windmill Apothecary**.
- Added **Ivy - Riverwood Small Addon**.
- Added **Ivy - Riverwood Well Addon**.
- Added **Ivy - Cozy Corner Patch Hub** to provide compatibility patches for the expanded Riverwood setup.
- Added FYX - Water Mesh Optimization for improved water mesh performance and compatibility with Water for ENB + Community Shaders.
- Added SunHelm Survival and Needs as the main survival framework for the modlist.
- Added SunHelm Magical Heat Sources to integrate magical heat sources with SunHelm’s temperature system.
- Added More Wells for SunHelm - Vanilla to expand the number of vanilla wells that can be used as water sources.
- Added SunHelm Survival and Needs - Italian Translation for full Italian localization of the survival system.
- Added ethqnm’s Ice.
- Added ethqnm’s Blowing Snow.
- Added Glacier LOD Meshes.
- Added TMD Epic Waterfalls.
- Othavein UI.
- City Trees.
- Kept Markarth Extra Mountains Edit - City of Stone
- Confirmed the Markarth Fixed AF + Stony AF stack
- Added/verified the City Trees patch for ALT Markarth's Forge
- Added Capital Windhelm expanded.
- Added Icy Windhelm.
- Added Windgelm Bridge Revived.
- Added Jk's Windhelm Outskirt.

## Removed
- Removed JK's Whiterun Exterior from the Whiterun setup.
- Removed Vel'dun UI
- Removed Witcherun
- Removed Pleasantrees
- Removed Jk's Castle Dour
- Removed Jk's Bards College
- Removed Gonzeh - Left Hand Mine Mini due to incompatibility with JK's Markarth Outskirts

## Bugfixes and compatibility
* Reorganized several **modlist sections** to improve clarity, navigation, maintenance, and overall quality of life.
* Added additional **compatibility patches for city outskirts** to improve integration between exterior overhauls and nearby worldspace modifications.
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
- Consolidated the stack around Grand Solitude - The Walls of High King Erling
* Removed/disabled standalone overhauls that had become integrated or redundant
* Consolidated the Riften Expansion + JK's Riften Outskirts + Riften Docks Overhaul stack
* Cleaned up the JK's Thieves Guild + GG's Thieves Guild Headquarters branch
* Removed redundant old JK-only patches
* Added Snazzy Interiors - Riften AIO - JKsGGs Thieves Guild HQ Patch
* Added Snazzy Interiors - Riften AIO - RYFTEN Consistency of Windows Patch
* Added Riften Expansion - RYFTEN Windows Patch
* Added the FYX Temple of Mara + Better Optimized Riften Meshes patch
* Disabled Riften Temple Sconce Fix
* Kept Riften Temple Sconce Base Fix - Plugin Alternative BOS
* Disabled HS Player Homes - Honeyside
* Added Riften Docks Overhaul - SMIM
* Added Dynamic Boats patches for Riften Docks Overhaul and Riften Expansion
* Verified overall compatibility with City Trees, RYFTEN, and Snazzy
* Restored proper compatibility with Riften Docks Overhaul - SMIM
* Consolidated the Capital Windhelm Expansion + JK's Windhelm Outskirts + Windhelm Bridge Revived + Icy Windhelm stack
* Added Rob's Bug Fixes - Capital Windhelm Expansion
* Added Nature of the Wild Lands - Capital Windhelm Patch
* Added City Trees - Capital Windhelm Expansion Patch
* Added JK's New Gnisis Cornerclub - Capital Windhelm Expansion Patch
* Added JK's Candlehearth Hall - Capital Windhelm Expansion Patch
* Added JK's Temple of Talos - Capital Windhelm Expansion Patch
* Added JK's Palace of the Kings - Capital Windhelm Expansion Patch
* Added Jonado's Random Patches
* Removed the old Windhelm - CWE Braziers Patch
* Kept the Windhelm Brazier Replacer BOS setup
* Verified compatibility with Dynamic Boats at Docks and DK's Realistic Nord Ships 

## Alchemy and Food Changes

## Magic Changes

## Economy Changes

## Visual, Performance and World Changes
- Reworked the Whiterun overhaul stack to improve overall compatibility and reduce unnecessary overlap between city modifications.
- Reconfigured the Capital Whiterun / Restored Whiterun Defences compatibility stack.
- Reviewed and corrected the Whiterun plugin load order.
- Reviewed modlist, plugins, loadorder, lockedorder and archive configuration after the Whiterun overhaul changes.
- Improved overall plugin consistency and dependency handling within the current load order.
- Resolved the previously reproducible crash occurring when leaving the Riverwood Trader.
- Performed additional runtime stability testing after the SMP reinstall, with no recurrence of the crash.
- Reviewed the current HUD/UI stack, including SkyHUD, TrueHUD, STB Widgets / Active Effects and Othavein UI.
- Reduced several redundancies between city overhauls and obsolete patches
- Improved patch coverage for AI Overhaul, USSEP, NotWL, City Trees, and JK Interiors

## Creation Club Content Changes

## Planned / Future Implementations
- Began a new performance and memory optimization pass, with particular attention to RAM and GPU VRAM usage.
- Identified high VRAM utilization on 12 GB GPUs as a possible source of short frametime spikes and intermittent stuttering.
- Core Impact Framework
- Dynamic Wind Framework
- Animated Ice Floes and Icebergs





