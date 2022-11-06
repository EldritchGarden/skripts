# Skripts
Collection of skripts made for my private Minecraft server to implement custom functionality

## Items:
### Iron Hammer
Custom pickaxe which breaks blocks in a 3x3 area. Uses less durability than a pickaxe.
By default breaks a vertical area in front of the player. Sneak to break a horizontal area.

## Recipes:
### Iron Hammer
2 sticks, 2 iron ingots, 1 iron block.

![image](https://user-images.githubusercontent.com/26440900/200186092-2860d3a1-ff67-4ee7-96de-3ec7a6d01f04.png)

### Leather
Cook rotten flesh on a campfire. 30s cook time.

## Skripts:
* 3x3_pickaxe.sk
  * Implements iron hammer functionality
* homes.sk
  * Players can set their home, and teleport back to it. Also integrates with dynmap markers
* recipes.sk
  * Dependencies: SkBee
  * Custom crafting recipes and `/give_custom` command for custom items
* spawn.sk
  * `/spawn` command for teleporting to spawn
