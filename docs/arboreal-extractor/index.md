---
title: Arboreal Extractor
nav: thermal-expansion
recipes:
  crafting:
    - device-tapper
---

![Arboreal extractor](/assets/images/thermal-expansion/arboreal-extractor.png){:style="height: 128px"}

> Put down the axe.


An **arboreal extractor** (also known as a **tapper**) is a
[device](/docs/devices/) that extracts a fluid from an adjacent
[tree](https://minecraft.gamepedia.com/Tree).


Obtaining
---------

A placed arboreal extractor can be instantly picked up by dismantling it with a
[wrench](/docs/wrenches/). Its configuration is preserved in the item. It can
also be mined using a [pickaxe](https://minecraft.gamepedia.com/Pickaxe).

### Crafting
{% include recipe-table.html type='crafting' recipes=page.recipes.crafting no-result=true %}


Usage
-----

### Placement
When placed, an arboreal extractor faces the player. It can face any of the four
cardinal directions, and can be rotated using a [wrench](/docs/wrenches/).

### Operation
When placed next to the bottom of a [tree](https://minecraft.gamepedia.com/Tree)
(or [huge mushroom](https://minecraft.gamepedia.com/Huge_mushroom)), an arboreal
extractor will start extracting a fluid. An active arboreal extractor produces a
certain amount of fluid every 600 ticks (30 seconds).

The amount of fluid an arboreal extractor produces per cycle can be increased by
placing fertilizer items in its fertilizer slot. Fertilizer will boost the
device's production for 16 cycles per item.

| Fertilizer type | Production multiplier |
|---
| [Phyto-Gro](/docs/phyto-gro/) | × 2 |
| [Rich Phyto-Gro](/docs/rich-phyto-gro/) | × 3 |
| [Fluxed Phyto-Gro](/docs/fluxed-phyto-gro/) | × 4 |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}

### Input and output
Items and fluids can enter and exit an arboreal extractor through its sides.
Every side of an arboreal extractor may correspond to its fertilizer slot, its
output tank, or both at the same time.

An arboreal extractor can automatically transfer fluids out of any sides that
directly correspond to its output tank. This is called auto-output. The device
can automatically transfer up to 1,000 mB of fluid at a time. It can also
transfer items from adjacent inventories into any sides that directly correspond
to its fertilizer slot. This is called auto-input. Auto-output and auto-input
occur every 600 ticks (30 seconds). Auto-output occurs after fluid is produced,
and auto-input occurs right before fluid is produced.

Which sides correspond to which slots/tanks and whether auto-output and
auto-input are enabled can be configured using the Configuration tab in the
device's GUI.

### Redstone control
An arboreal extractor may be configured to respond to
[redstone](https://minecraft.gamepedia.com/Redstone) signals. It can be in one
of three modes:

Ignored
: Redstone control is disabled. The arboreal extractor works whenever possible.
This is the default mode.

Low
: The arboreal extractor works when *not* powered. When powered, it stops
working.

High
: The arboreal extractor only works when powered.

The current mode can be set using the Redstone Control tab in the device's GUI.

### Security
An arboreal extractor can have a [signalum security
lock](/docs/signalum-security-lock/) installed to restrict who can access it.

### Redprints
An arboreal extractor's configuration can be saved on a
[redprint](/docs/redprint/) to be copied to other arboreal extractors.


Products
--------

The fluid that an arboreal extractor produces and the amount of fluid that is
produced per cycle depends on the type of tree.

| Tree type | Extracted fluid | Fluid per cycle |
|---
| Oak | [Sap](/docs/sap/) | 50 mB |
| Spruce | [Resin](/docs/resin/) | 100 mB |
| Birch | [Resin](/docs/resin/) | 50 mB |
| Jungle | [Resin](/docs/resin/) | 50 mB |
| Acacia | [Resin](/docs/resin/) | 50 mB |
| Dark Oak | [Sap](/docs/sap/) | 50 mB |
| Huge brown mushroom | [Mushroom Stew](/docs/mushroom-stew/) | 50 mB |
| Huge red mushroom | [Mushroom Stew](/docs/mushroom-stew/) | 50 mB |
{:.uk-table .uk-table-striped .uk-table-condensed .uk-text-small .cofh-table-compress}
