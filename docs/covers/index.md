---
title: Covers
nav: thermal-dynamics
image:
  - alt: Stone cover
    file: thermal-dynamics/cover-stone.png
  - alt: Cobblestone cover
    file: thermal-dynamics/cover-cobblestone.png
  - alt: Oak wood cover
    file: thermal-dynamics/cover-wood-log-oak.png
  - alt: Oak wood planks cover
    file: thermal-dynamics/cover-wood-planks-oak.png
  - alt: Sandstone cover
    file: thermal-dynamics/cover-sandstone.png
  - alt: Nether brick cover
    file: thermal-dynamics/cover-nether-brick.png
  - alt: Obsidian cover
    file: thermal-dynamics/cover-obsidian.png
  - alt: Moss stone cover
    file: thermal-dynamics/cover-moss-stone.png
  - alt: Bricks cover
    file: thermal-dynamics/cover-bricks.png
  - alt: Polished granite cover
    file: thermal-dynamics/cover-granite-polished.png
  - alt: Polished diorite cover
    file: thermal-dynamics/cover-diorite-polished.png
  - alt: Polished andesite cover
    file: thermal-dynamics/cover-andesite-polished.png
  - alt: End stone bricks cover
    file: thermal-dynamics/cover-end-stone-bricks.png
redirect_from:
  - /docs/thermal-dynamics/attachments/covers/
recipes:
  crafting:
    - duct-covers
---

**Covers** are items that can be installed on ducts to hide them, making them
look like blocks.


Obtaining
---------

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}


Usage
-----

A cover can be installed on any side of a duct by using it on the duct. It can
be removed by using a [wrench](/docs/wrenches/) on it.

Installed covers do not affect how ducts work in any way. When a duct goes
through a cover, a hole is made in the cover.


Trivia
------

* [Thermal Dynamics](/docs/thermal-dynamics/) uses a configurable blacklist of
  blocks that players should not be able to make covers with. The command
  `/td_blacklist_cover` can be useful when configuring this blacklist; it
  returns the line to add to the list to disable a held cover.
