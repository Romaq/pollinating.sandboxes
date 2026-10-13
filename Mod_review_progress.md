# TFC + Create + Aeronautics — Mod Review Progress

**Date:** 2026-10-10  
**Target:** Minecraft 1.21.1[^1] / NeoForge [^2]  
**Status:** Proposed for review; **not** a verified compatible installation list.

## Design goals

- **TerraFirmaCraft (TFC)** is the survival, geology, agriculture, and metallurgy foundation.
- **Create** is the primary automation and mechanical engineering system.
- **Create Aeronautics** is essential, with aircraft achievable through meaningful engineering rather than a **GregTech**-style grind.
- Quest-guided sandbox: tutorials, milestones, and optional specializations; quests do not arbitrarily lock unrelated crafting.
- Convenient inventory management, without unintentionally bypassing **TFC** food spoilage or metalworking.
- No mandatory **GregTech**[^3].

## A. Essential core — first compatibility test

| Mod | Why consider it | Review status / link | Modrinth? |
|---|---|---|---|
| **TerraFirmaCraft** | Overhauls survival, geology, metallurgy, farming, and food. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/terrafirmacraft) — confirm exact 1.21.1 build | [x] |  
| **Patchouli** | Dependency for TFC, required for in-game books. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/patchouli) — dependency for TFC | [x] |  
| **Create** | Mechanical power, belts, presses, processing, trains, and logistics. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create) — confirm version pairing | [x] |  
| **Create Aeronautics** | Essential physics-based aircraft and mobile contraptions. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-aeronautics) — 1.21.1 NeoForge listing verified | [x] |  
| **TFC Aeronautics** | Compatibility between TFC, Create, and Aeronautics. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/tfc-aeronautics) — 1.21.1 beta; test carefully | [_] |  
| **TFCreate Compat** | Aligns Create recipes/materials with TFC's progression. | [GitHub](https://github.com/Ayaibu/TFCreate-Compat) — inspect supported builds and overlap with Sky Arc scripts | [x] |  
| **Create Aeronautics: Compatibility** | Addresses compatibility with other mods on moving contraptions. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-aeronautics-compatability) — confirm actual need and interaction with TFC Aeronautics | [x] |  

**Important:** These are candidates, not a claim that all six work together without conflicts. Check dependencies, release versions, and duplicate recipe modifications before installation.

**Notes:**
1. I can use the CurseForge client to combine all the elements. At the moment, **TFC Aeronautics** is unavailable on **Modrinth**. After adding **Patchouli** as a **TFC** dependency, I was able to run the modpack up to creating a world with the "*pollinating sandboxes* seed.  
2. To preserve a sense of continuation for testing, I plan to use that "seed zero" moving forward.  
3. I note the mod claims **Modrinth** has a more updated version of **Create**, but both sites offer the same **Create** v. 6.0.10 for 1.21.1.

## B. World Topology, Topography, and environmental dangers

| Mod | Why consider it | Link |  Modrinth? |  
|---|---|---|---|  
| **TerraFirmaEarth** | Expanding and smoothing biome transition, cleaner terrain, and better hydrology. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/terrafirmaearth) | [_]  
| **Dynamic Trees** | Trees have an obvious growth cycle, and harvesting has tradeoffs. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/dynamictrees) | [x]  
| **Dynamic Trees - TFC** | TFC Compatibility Layer | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/dynamictreestfc) | [x]
| **Dynamic Trees TFC - Seeds** | TFC Compatibility Layer | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/dynamic-trees-tfc-seeds) | [x]
| **TFC Weather Systems** | More realistic weather for TFC | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/tfc-weather-systems-realistic-weather-for) | [_]
| **** | More realistic weather for TFC | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/tfc-weather-systems-realistic-weather-for) | [_]

**Notes:**
1. The definition of [Topography vs. Topology](https://thisvsthat.io/topography-vs-topology) may be useful in this discussion. 
2. **Minecraft** at its core presumes a flat and *practically* infinite topology: 7 times the size of planet Earth surface area with a storage requirement simply beyond most enduser budget and access.
3. "Curving" the topology can be accomplished in **Minecraft** by teleporting the player from one boundary to another. I dislike forced teleportation for this purpose. **Minecraft**'s world is flat.
4. **Minecraft** Topography *suxx0rs*. Biomes are blotches dropped into the world based upon noise generation. There is no guiding principle for warm vs. cold biomes. There is also no hydrology. Surface water is set at a baseline of 63, rivers are gouged below that surface level and lakes are "smaller seas." Part of the appeal of **TFC** is that biomes are guided by the principle "atmospheric hydrology is driven east to west up to a count of blocks distant from origin (0x, 0z) and climate warmth is driven north to south by a similar count of blocks from origin.
5. Surface erosion, streams, lakes are not a factor in **TFC** world generation. I would like erosion over time to be a factor. I would also prefer lakes and streams to form more naturally.
6. In many aspects of **Minecraft** and modpacks in general, environmental dangers are due to supernatural monsters or other players. **TFC** brings more of the environment to the forefront as a hazard. Technology is the solution that brings its own problems.

## C. TFC Magic?

| Mod | Why consider it | Link |
|---|---|---|
| **theorematurgy** | A magic system for adding a pinch of buff to mundane tools and weapons | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/theorematurgy) | [x] |
| **TOM x TFC** | A TFC connetor | [Curseforge](https://www.curseforge.com/minecraft/mc-mods/tom-x-tfc) | [x] |


**Notes:** Minecraft Vanilla has hints of the supernatural (mods) and arcane (basic enchantments). A well designed magic system would be fitting and allow for an extra spice to the modpack.

## D. TFC survival expansion

| Mod | Why consider it | Link |
|---|---|---|
| **FirmaLife** | More farming, cooking, food preservation, and homestead infrastructure. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/firmalife) |
| **Farmer's Delight** (conditional) | Expanded cooking; only if a tested TFC recipe/food integration prevents bypasses. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/farmers-delight) |

**Review:** Verify food decay, nutrition, crop climate requirements, and whether extra cooking recipes trivialize TFC.

## E. Storage and exploration convenience

| Mod | Why consider it | Link |
|---|---|---|
| **Sophisticated Storage** | Upgradeable physical chests/barrels and bulk material storage. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/sophisticated-storage) |
| **Tom's Simple Storage** | Searchable central access and crafting across connected inventories. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/toms-storage) |
| **Sophisticated Backpacks** | Portable inventory for mining, prospecting, and construction. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/sophisticated-backpacks) |

**Review:** Test nested inventory behavior, food decay, TFC item size restrictions, storage-controller interoperability, and aircraft-mounted storage. Prefer physical Create logistics for factories even if central search is available.

## F. Create engineering and transport

| Mod | Why consider it | Link |
|---|---|---|
| **Create: Steam 'n' Rails** | More rail infrastructure and train logistics. | [Main project](https://www.curseforge.com/minecraft/mc-mods/create-steam-n-rails) — **main listing does not establish a 1.21.1 release**; find/verify a legitimate compatible port before selection |
| **Create Crafts & Additions** | Adds electrical/rotational-power integration for optional engineering. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/createaddition) |
| **Create: The Factory Must Grow** | Optional oil, heavy industry, and manufacturing; may increase complexity. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-industry) |
| **Create: Connected** | Extra mechanical connectivity and building components. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-connected) |
| **Create: Enchantment Industry** | Optional Create-powered enchanting automation. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-enchantment-industry) |

**Recommendation:** Defer Factory Must Grow and Enchantment Industry until core progression is playable. Avoid adding industrial systems simply to increase mod count.

## G. Quests and interface

| Mod | Why consider it | Link |
|---|---|---|
| **FTB Quests** | Tutorials, optional quest branches, milestones, and rewards. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ftb-quests-forge) |
| **FTB Library / FTB Teams** | Add only the versions required by FTB Quests. | [FTB Library](https://www.curseforge.com/minecraft/mc-mods/ftb-library-forge) · [FTB Teams](https://www.curseforge.com/minecraft/mc-mods/ftb-teams-forge) |
| **EMI** or &rarr;**JEI** | Recipe discovery and crafting paths; choose a primary recipe viewer. | [EMI](https://www.curseforge.com/minecraft/mc-mods/emi) · [JEI](https://www.curseforge.com/minecraft/mc-mods/jei) |
| &rarr;**Jade** | Inspect blocks, inventories, and machinery in the world. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/jade) |
| &rarr;**Xaero's Minimap** | Navigation and waypoints while prospecting. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap) |
| &rarr;**Xaero's World Map** | World-scale mapping for exploration and travel routes. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map) |
| &rarr;**Mouse Tweaks** | Less repetitive inventory movement. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks) |
| &rarr;**Controlling** | Find and resolve keybind conflicts in a large modpack. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/controlling) |
| &rarr;**AppleSkin** (conditional) | Hunger/saturation information; test against TFC nutrition interface. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/appleskin) |
| **FTB Chunks** (conditional) | Chunk claiming/loading for multiplayer factories. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ftb-chunks-forge) |

## H. Performance candidates — add only after baseline tests

| Mod | Why consider it | Link |
|---|---|---|
| **ModernFix** | General performance and memory optimizations. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/modernfix) |
| **FerriteCore** | Memory-use reductions. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ferritecore) |
| **Embeddium** | Client rendering optimization, **only if the exact NeoForge build is compatible with Aeronautics**. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/embeddium) |

## I. Reference modpacks (study, not automatic dependencies)

- [TerraFirmaCraft: Sky Arc](https://www.curseforge.com/minecraft/search?class=modpacks&search=TerraFirmaCraft%20Sky%20Arc) — reference for TFC/Create/Aeronautics recipe integration; inspect license before copying scripts.
- [All the Mods: Gravitas²](https://www.curseforge.com/minecraft/modpacks/all-the-mods-gravitas2) — reference for quests and instructional progression, **not** for GregTech gating.
- [Terraero](https://www.curseforge.com/minecraft/search?class=modpacks&search=Terraero) — optional industrial and aircraft ideas.

## J. Suggested review order

1. **Core compatibility:** TFC + Create + Aeronautics, then integration addons.
2. **Recipe economy:** Check TFC metal requirements and early Create access; test first-aircraft recipes.
3. **Storage:** Add one system at a time; test food decay and item metadata.
4. **Quest framework:** Write original tutorial, milestone, and optional engineering branches.
5. **Expansion mods:** Evaluate transport, farming, and optional power systems individually.
6. **Performance:** Establish a clean benchmark and test optimizers individually.

## J. Review decisions to make

- [x] Approve core three mods as the pack's required identity.
- [ ] Choose the TFC/Create recipe integration strategy; avoid conflicting script packs.
- [ ] Decide whether FirmaLife is part of the default survival experience.
- [ ] Select a storage approach after testing food and item behavior.
- [ ] Choose a quest mod after confirming 1.21.1 NeoForge support.
- [ ] Determine whether optional electrical power or oil refining fits the intended progression.
- [ ] Approve exact mod versions **only after** a dependency and launch test.

**Verification caveat:** Links point to project pages for review, not preselected compatible download files. Individual mods may lack 1.21.1 NeoForge builds or require specific dependency versions. No mod installation or configuration change has been made.

[^1] **Minecraft 1.21.1** is the latest **Minecraft** version supported by **TFC**, and so anchors this particular version.  
[^2] **Forge** has made itself odious because of the behavior by the mod leader, *LexManos*. [**Neoforge** explained the reason for the fork.](https://neoforged.net/news/theproject/) I also note the most simple way to explain the difference between **NeoForge** and **Fabric**. You can carry a bicycle on a car, but you can't carry a car on a bicycle. **NeoForge** is much more complex, hence slower to update and debug, but it supplies code pipelines that more complex mods (such as **TFC**) will need to hook into without elaborate mods that duplicate just using **NeoForge**. Note: It is my intention to add [**Sinytra Connector**](https://connector.sinytra.org/) with a few functional **Fabric** mods to leave open that possibility for adding **Fabric** mods should one wish to do sos.  
[^3] Experience with **GregTech* has been unfavorable due to being overly "grindy" without appropriate reward, and unnecessarily complicates progression.