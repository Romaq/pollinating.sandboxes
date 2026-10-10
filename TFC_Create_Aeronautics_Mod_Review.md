# TFC + Create + Aeronautics — Recommended Mod Review

**Date:** 2026-10-09  
**Target:** Minecraft 1.21.1 / NeoForge  
**Status:** Proposed for review; **not** a verified compatible installation list.

## Design goals

- TerraFirmaCraft (TFC) is the survival, geology, agriculture, and metallurgy foundation.
- Create is the primary automation and mechanical engineering system.
- Create Aeronautics is essential, with aircraft achievable through meaningful engineering rather than a GregTech-style grind.
- **Quest-guided sandbox:** tutorials, milestones, and optional specializations; quests do not arbitrarily lock unrelated crafting.
- Convenient inventory management, without unintentionally bypassing TFC food spoilage or metalworking.
- No mandatory GregTech.

## A. Essential core — first compatibility test

| Mod | Why consider it | Review status / link |
|---|---|---|
| **TerraFirmaCraft** | Overhauls survival, geology, metallurgy, farming, and food. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/terrafirmacraft) — confirm exact 1.21.1 build |
| **Create** | Mechanical power, belts, presses, processing, trains, and logistics. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create) — confirm version pairing |
| **Create Aeronautics** | Essential physics-based aircraft and mobile contraptions. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-aeronautics) — 1.21.1 NeoForge listing verified |
| **TFC Aeronautics** | Compatibility between TFC, Create, and Aeronautics. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/tfc-aeronautics) — 1.21.1 beta; test carefully |
| **TFCreate Compat** | Aligns Create recipes/materials with TFC's progression. | [GitHub](https://github.com/Ayaibu/TFCreate-Compat) — inspect supported builds and overlap with Sky Arc scripts |
| **Create Aeronautics: Compatibility** | Addresses compatibility with other mods on moving contraptions. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-aeronautics-compatability) — confirm actual need and interaction with TFC Aeronautics |

**Important:** These are candidates, not a claim that all six work together without conflicts. Check dependencies, release versions, and duplicate recipe modifications before installation.

## B. TFC survival expansion

| Mod | Why consider it | Link |
|---|---|---|
| **FirmaLife** | More farming, cooking, food preservation, and homestead infrastructure. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/firmalife) |
| **Farmer's Delight** (conditional) | Expanded cooking; only if a tested TFC recipe/food integration prevents bypasses. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/farmers-delight) |

**Review:** Verify food decay, nutrition, crop climate requirements, and whether extra cooking recipes trivialize TFC.

## C. Storage and exploration convenience

| Mod | Why consider it | Link |
|---|---|---|
| **Sophisticated Storage** | Upgradeable physical chests/barrels and bulk material storage. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/sophisticated-storage) |
| **Tom's Simple Storage** | Searchable central access and crafting across connected inventories. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/toms-storage) |
| **Sophisticated Backpacks** | Portable inventory for mining, prospecting, and construction. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/sophisticated-backpacks) |

**Review:** Test nested inventory behavior, food decay, TFC item size restrictions, storage-controller interoperability, and aircraft-mounted storage. Prefer physical Create logistics for factories even if central search is available.

## D. Create engineering and transport

| Mod | Why consider it | Link |
|---|---|---|
| **Create: Steam 'n' Rails** | More rail infrastructure and train logistics. | [Main project](https://www.curseforge.com/minecraft/mc-mods/create-steam-n-rails) — **main listing does not establish a 1.21.1 release**; find/verify a legitimate compatible port before selection |
| **Create Crafts & Additions** | Adds electrical/rotational-power integration for optional engineering. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/createaddition) |
| **Create: The Factory Must Grow** | Optional oil, heavy industry, and manufacturing; may increase complexity. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-industry) |
| **Create: Connected** | Extra mechanical connectivity and building components. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-connected) |
| **Create: Enchantment Industry** | Optional Create-powered enchanting automation. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/create-enchantment-industry) |

**Recommendation:** Defer Factory Must Grow and Enchantment Industry until core progression is playable. Avoid adding industrial systems simply to increase mod count.

## E. Quests and interface

| Mod | Why consider it | Link |
|---|---|---|
| **FTB Quests** | Tutorials, optional quest branches, milestones, and rewards. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ftb-quests-forge) |
| **FTB Library / FTB Teams** | Add only the versions required by FTB Quests. | [FTB Library](https://www.curseforge.com/minecraft/mc-mods/ftb-library-forge) · [FTB Teams](https://www.curseforge.com/minecraft/mc-mods/ftb-teams-forge) |
| **EMI** **or** **JEI** | Recipe discovery and crafting paths; choose a primary recipe viewer. | [EMI](https://www.curseforge.com/minecraft/mc-mods/emi) · [JEI](https://www.curseforge.com/minecraft/mc-mods/jei) |
| **Jade** | Inspect blocks, inventories, and machinery in the world. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/jade) |
| **Xaero's Minimap** | Navigation and waypoints while prospecting. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xaeros-minimap) |
| **Xaero's World Map** | World-scale mapping for exploration and travel routes. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/xaeros-world-map) |
| **Mouse Tweaks** | Less repetitive inventory movement. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/mouse-tweaks) |
| **Controlling** | Find and resolve keybind conflicts in a large modpack. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/controlling) |
| **AppleSkin** (conditional) | Hunger/saturation information; test against TFC nutrition interface. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/appleskin) |
| **FTB Chunks** (conditional) | Chunk claiming/loading for multiplayer factories. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ftb-chunks-forge) |

## F. Performance candidates — add only after baseline tests

| Mod | Why consider it | Link |
|---|---|---|
| **ModernFix** | General performance and memory optimizations. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/modernfix) |
| **FerriteCore** | Memory-use reductions. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/ferritecore) |
| **Embeddium** | Client rendering optimization, **only if the exact NeoForge build is compatible with Aeronautics**. | [CurseForge](https://www.curseforge.com/minecraft/mc-mods/embeddium) |

## G. Reference modpacks (study, not automatic dependencies)

- [TerraFirmaCraft: Sky Arc](https://www.curseforge.com/minecraft/search?class=modpacks&search=TerraFirmaCraft%20Sky%20Arc) — reference for TFC/Create/Aeronautics recipe integration; inspect license before copying scripts.
- [All the Mods: Gravitas²](https://www.curseforge.com/minecraft/modpacks/all-the-mods-gravitas2) — reference for quests and instructional progression, **not** for GregTech gating.
- [Terraero](https://www.curseforge.com/minecraft/search?class=modpacks&search=Terraero) — optional industrial and aircraft ideas.

## H. Suggested review order

1. **Core compatibility:** TFC + Create + Aeronautics, then integration addons.
2. **Recipe economy:** Check TFC metal requirements and early Create access; test first-aircraft recipes.
3. **Storage:** Add one system at a time; test food decay and item metadata.
4. **Quest framework:** Write original tutorial, milestone, and optional engineering branches.
5. **Expansion mods:** Evaluate transport, farming, and optional power systems individually.
6. **Performance:** Establish a clean benchmark and test optimizers individually.

## I. Review decisions to make

- [ ] Approve core three mods as the pack's required identity.
- [ ] Choose the TFC/Create recipe integration strategy; avoid conflicting script packs.
- [ ] Decide whether FirmaLife is part of the default survival experience.
- [ ] Select a storage approach after testing food and item behavior.
- [ ] Choose a quest mod after confirming 1.21.1 NeoForge support.
- [ ] Determine whether optional electrical power or oil refining fits the intended progression.
- [ ] Approve exact mod versions **only after** a dependency and launch test.

**Verification caveat:** Links point to project pages for review, not preselected compatible download files. Individual mods may lack 1.21.1 NeoForge builds or require specific dependency versions. No mod installation or configuration change has been made.
