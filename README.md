[![logo](https://cdn.lunareclipse.studio/img/projects/from-the-fog/banner-text.webp)](https://lunareclipse.studio/creations/from-the-fog)

## Mod/Datapack for Minecraft: Java Edition — Port Minecraft 26.2

# You can't see him, but I promise he can see you...

This repository contains an **unofficial community port** of
[**From The Fog**](https://github.com/LunarEclipseStudios/From-The-Fog) by
**Lunar Eclipse Studios**, updated to run on **Minecraft 26.2**.

From The Fog is a combined datapack + resourcepack that brings the legendary
Herobrine to life in a spooky and immersive way, adding shrines, sightings,
jumpscares, and a whole atmosphere of dread to survival worlds.

All credit for the original concept, design, textures and datapack logic goes
to Lunar Eclipse Studios. This repository only exists to keep the pack working
on newer Minecraft versions; it is **not** an official release and is **not**
affiliated with Lunar Eclipse Studios.

---

### Gallery (from the original project)

[![banner](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/banner.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![forest-encounter](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/forest-encounter.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![window-watcher](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/window-watcher.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![new-grove](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/new-grove.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![shrine-surprise](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/shrine-suprise.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![unknown-entity-err](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/unknown-entity-err.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![more-skins](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/more-skins!.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![ocean-sand-pyramid](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/ocean-sand-pyramid.webp)](https://lunareclipse.studio/creations/from-the-fog)
[![2x2-tunnel](https://cdn.lunareclipse.studio/img/projects/from-the-fog/gallery/2x2-tunnel.webp)](https://lunareclipse.studio/creations/from-the-fog)

*(Images © Lunar Eclipse Studios, hosted on their CDN, linked here with credit — see their [gallery page](https://lunareclipse.studio/creations/from-the-fog) for more.)*

---

## About this port

The original pack is built for older Minecraft versions. This port:

- Updates the datapack to load correctly on **Minecraft 26.2** (function/tag
  paths, gamerule references, and other version-specific fixes)
- Fixes a resourcepack panorama texture size conflict that could cause a
  crash/reset on load when combined with other high-resolution packs
- Folds in some additional community content (extra language files, roadmap
  icons, sounds) from other community ports of the same pack, where it didn't
  conflict with the base pack
- Also provides a repackaged `.jar` build (see Installation below) so it can
  be dropped straight into the `mods` folder instead of manually splitting it
  between `resourcepacks` and `datapacks`

## Installation

Two ways to install this pack — pick whichever is more convenient for you.

### Option A — as a Fabric mod jar (recommended, easiest)

A repackaged `.jar` build is also provided in this repository's releases. It
contains the exact same `assets/` and `data/` content as the datapack/
resourcepack below, just wrapped with a minimal `fabric.mod.json` so Fabric
Loader mounts it automatically as a built-in resource pack + data pack.
**There is no custom Java code in this jar** — it behaves identically to the
datapack/resourcepack version.

1. Download the latest `from-the-fog-*.jar` from this repository's releases.
2. Drop it in your `mods` folder — **client and server**.
3. That's it, no need to touch the `resourcepacks`/`datapacks` folders.

### Option B — as a datapack + resourcepack

1. Download the latest release (the `.zip`) from this repository.
2. Put the pack **in both** your `resourcepacks` **and** `datapacks` folders
   (it's a combined pack, like the original).
3. Make sure it is loaded **below** (i.e. lower priority than) any other
   high-resolution texture packs you use, to avoid texture conflicts.

### After installing (either option)

Join a world. By default it takes a few in-game days before the main events
start — you can speed this up by building a Herobrine shrine (mossy
cobblestone or gold block center).

## Links to the original project

- Original GitHub repository: <https://github.com/LunarEclipseStudios/From-The-Fog>
- Official website: <https://lunareclipse.studio/creations/from-the-fog>
- Official Discord: <https://discord.lunareclipse.studio>

## License

The original **From The Fog** is licensed under
[**CC BY-NC-SA 4.0**](https://github.com/LunarEclipseStudios/From-The-Fog/blob/main/LICENSE.md)
(Attribution-NonCommercial-ShareAlike). In line with that license, this port:

- credits Lunar Eclipse Studios as the original authors,
- is shared non-commercially,
- and is released under the same CC BY-NC-SA 4.0 license.

Please support the original creators — check out their
[website](https://lunareclipse.studio) and consider joining their
[Discord](https://discord.lunareclipse.studio) or supporting them on
[Ko-fi](https://lunareclipse.studio/ko-fi).
