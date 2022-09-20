---
description: Learn how to configure the plugin
---

# Configuration

## Setting materials

Minecraft has different ids for placeable and placed material, you'll have to tell to the plugin the mutation schema of your items.

For example the id of the placeable carrot is "CARRPT", the id of the palced is "CARROTS".

If you need help you can join our [discord](https://discord.io/RocketPlugins) server and our moderators will help you setting up the schema.

If you don't put an item in the `items` list it won't work.

## Editing levels

You can edit levels with the levels configuration.

```yaml
# Percent for each level of how many blocks should it break
# You can't add or remove levels
# Example: There are 7 blocks to mine, it will mine only the 15% of them at level 1
levels:
  1: 15.0
  2: 20.0
  3: 35.0
  4: 40.0
  5: 50.0
```

## Editing tasks

Tasks are the main function of the plugin, they are used to make the minions work.\
Default values are very good but you can increase/decrease them.\


**Remember:** Decreasing tasks duration may cause lag.

```yaml
tasks:
  grow: 5
  collect: 10
```

### Grow Task

The grow task is used to increase crops growing speed, if you use it for blocks it won't be used.

### Collect Task

The collect task is used to break and collect items.
