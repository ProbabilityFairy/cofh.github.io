---
title: Commands (CoFH World)
nav: cofh-world
---

[CoFH World](/docs/cofh-world/) adds a couple of
**[commands](https://minecraft.gamepedia.com/Commands)** to the game.


Summary
-------

All of CoFH World's commands must be prefixed with `/cofhworld` and a space.

{::options parse_block_html="true" /}
<div class="uk-overflow-container">
| Command | Description | Permission level |
|---
| [list](#list) | Displays a list of all registered features. | 4 |
| [reload](#reload) | Reloads the [world generator configuration](/docs/world-generator-configuration/). | 4 |
{:.uk-table .uk-table-striped .cofh-table-semi-compress}
</div>
{::options parse_block_html="false" /}


Details
-------

### list
Displays a list of the names of all registered [generation
entries](/docs/world-generator-configuration/#generation-entry-format).

    /cofhworld list

### reload
Reloads the [world generator
configuration](/docs/world-generator-configuration/).

    /cofhworld reload
