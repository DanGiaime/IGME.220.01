### What is Hexstrat?
Hexstrat is a 2-player turn-based strategy combat game. Players start with their Headquarters at opposite ends of a 5x5x5 hexagonal map, and work their way across the hidden midfield--revealing tiles as they go--in order to capture their opponent's Headquarters, or defeat all of their opponent's units.

### Game Pieces

#### Unit Markers

 * **2** Mech markers, one per player
 * **2** Infantry markers, one per player
 * **2** Rocketeer markers, one per player
 * **50** Squad chits

#### Tiles

The game has 37 total tiles:
* **2** Headquarters tiles, one per player
* **35** Land tiles
  * **15** Plains tiles
  * **10** Mountain tiles
  * **10** Forest tiles

### Win Conditions

* Rout - Defeat all of your opponent's units in combat.
* Seize - Capture your opponent's Headquarters.

### Setup

1. First, shuffle all of the land tiles.
2. Begin by placing the two Headquarters tiles with 3 land tiles, face down, between them, and 1 land tile behind each of them.
3. Continue to place land tiles adjacent to one another, with the middle of the tile aligned with the connecting edge of the adjacent tile. The board should form a hexagon shape when complete.
4. Squad chits are used to keep track of the number of units in a squad. The unit marker on top of the stack of chits denotes that squad's unit type. Stack the squad chits according to the unit counts below, then place their corresponding unit marker on the top of the stacks. Place these squads on your Headquarters tile.

#### Starting squads

* Infantry - 6 units
* Rocketeer - 6 units
* Mech - 4 units

### Deciding who goes first

Play a round of _Rock, Paper, Scissors_. The winning player goes first.

### Turn Actions

On their turn, players may perform one action for each of their _unimpeded_ squads:

* **Move** - Your squad attempts to move to an adjacent tile. If the tile has not been revealed yet, reveal the tile, then move the squad. If the squad may not move to the tile (i.e. Mech moving to a Mountain tile), the squad remains on the current tile, and may not perform another action. (See "Movement/Exploration")
* **Attack** - If one of your opponent's squads is on an adjacent tile, you may enter into combat by attacking that tile. (See "Combat")
* **Deimpede** - If your squad is in the _impeded_ state, they must perform the deimpede action before they may perform any other actions.
* **Wait** - Do nothing this turn.

On their turn, players may also play one Tile Bonus Card, unless stated otherwise.

Once all of a player's squads have expended their actions, or chosen not to perform any actions, the turn is over.

### Movement/Exploration

* _Tiles_ are placed upside-down across the field, so that the type of tile is hidden (i.e. you cannot see if a tile is mountain, forest, or plains).
* Tile Reveal happens when you move a squad into “unknown terrain” i.e. move them into fog of war
* Tile Reveal consists of flipping a Tile that was previously unknown terrain.
* One must first declare their intent to move a squad in a given direction, at which point the unknown Terrain Tile is flipped at that location. If the squad can move onto the new tile, it does so. If not, the squad does not move onto the tile, and can not move again during this turn.
* Each squad can only move one tile per turn.
* __Impeded__ - Some actions may cause a squad to become impeded. After becoming impeded, the only action that squad may take is to resolve its impeded state. While impeded, the squad still retaliates if attacked.


### Tiles

Tiles may only have one squad on them at any time. Some tiles provide attack and/or defense bonues to the occupying squad. Tiles may also impede or prevent movement for some unit types.

 | Tile     | Battle Effect                           | Discovery/Movement Effects                                 |
 | :------- | :-------------------------------------- | :---------------- |
 |  Plains  |  No Effect                              | No Effect |
 |  Forest  | +1 Defense         | Mechs are impeded for the next turn |
 | Mountains| +1 Attack +1 Defense | Mechs can not move onto mountains |
 | Headquarters | | If opponent Headquarters, squad is impeded for the next turn |

### Tile Bonuses

Some tiles offer a Tile Bonus to the first player to move on to that tile. Immediately upon moving onto a tile that offers a Tile Bonus, draw a card from the Tile Bonus Card Deck to your hand. You do not have to show the card to the opponent until you play it. Unless otherwise specified, you may play a Tile Bonus Card on any of your turns. You may only use one Tile Bonus Card per turn.

Though the cards themselves specify their effects, another reference is provided here:

| Bonus | Effect |
| :---- | :----- |
| Survivors Found | You discovered some survivors! **+2 Infantry/Rockets OR +1 Mech.** *Apply this effect immediately.* |
| Artillery Strike | You strike from a distance. **Pick any enemy squad to take one health away from.** |
| Extra Ammo | **Once during combat, you may attack twice.** |
| Boost (aka *Haul Ass*) | **Move one squad twice in one turn.** |
| Scout | You deploy a scouting mission. **Reveal two adjacent tiles of your choice.** |

### Combat

Combat occurs when a player's unit attempts to move onto a tile owned by another player, or a player declares an attack on an adjacent enemy unit. Combat can be declared regardless of movement capability.

Squads have 3 stats used in battle - __HP__, __DEF__, and __ATK__.

###### HP

A squad's HP is equal to the number of units in the squad. During battle, a squad can only attack if it has at least one HP. If a squad is killed before it can attack, it will deal no damage. When a squad loses HP, units are removed from that squad equal to the amount of damage taken.

###### DEF

All squads default to 0 DEF, and can only gain DEF via Tile/Card Bonuses. When a squad would take any amount of damage, it will first subtract its DEF from this damage before taking it. For example, if a squad were to take 3 damage, but the squad has 1 DEF, the squad will take 3 - 1 = 2 damage instead.

###### ATK

ATK is determined based on which unit-type attacks which unit type. The number of units in a squad has no effect on damage dealt.
Each unit type has a specific ATK value depending on the unit type it is attacking:


| Infantry   | Value  |
| :--------- | :----- |
| vs. Infantry | 1 ATK |
| vs. Rocketeer | 3 ATK |
| vs. Mech   | 2 ATK |


| Rocketeer | Value  |
| :--------- | :----- |
| vs. Rocketeer  | 1 ATK |
| vs. Mech | 3 ATK |
| vs. Infantry | 2 ATK |


|  Mech  | Value  |
| :--------- | :----- |
| vs. Mech | 1 ATK |
| vs. Infantry | 4 ATK |
| vs. Rocketeer  | 2 ATK |


Combat happens in two stages:

1. The attacking squad adds its attack value to the _tiles_ bonus values and deals that much damage to the defending squad.
2. The defending squad, __if still alive__, adds its attack value to the _tiles_ bonus and deals that much damage to the attacking squad.

For example, if a squad of 4 mechs attack a squad of 2 infantry, and both do not have any tile modifiers:

1. 4 ATK = 4 defending infantry lost
2. 2 ATK = 2 attacking mech lost

If a squad of 2 mechs attack a squad of 4 infantry, and the infantry are on the mountains:

1. 4 ATK - 1 DEF = 3 defending infantry lost
2. 2 ATK + 1 ATK = 3 attacking mech lost

### Capturing your opponent's HQ

To capture your opponent's Headquarters, your __infantry__ must occupy their Headquarters tile for 3 consecutive turns (including the turn they move onto the tile). On the third turn, the Headquarters is captured, and you win!


The attacking player starts the counter on the turn they enter the enemy's HQ. On the attacking player's next turn, if the attacking player's infantry remain on the HQ, the count goes to 2. On the attacking player's next turn after that, if the attacking player's infantry remain on the HQ, the counter goes to 3 and the attacking player wins.
