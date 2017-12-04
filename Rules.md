### What is Hexstrat?
Hexstrat is a 2-player turn-based strategy combat game. Players start with their Headquarters at opposite ends of the 3x3x3 hexagonal map, and work their way across the hidden midfield--revealing tiles as they go--in order to capture their opponent's Headquarters, or defeat all of their opponent's units.

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
* First, shuffle all of the land tiles.
* Begin by placing the two Headquarters tiles with 3 land tiles, face down, between them, and 1 land tile behind each of them.
* Continue to place land tiles adjacent to one another, with the middle of the tile aligned with the connecting edge of the adjacent tile. The board should form a hexagon shape when complete.
* Squad chits are used to keep track of the number of units in a squad. The unit marker on top of the stack of chits denotes that squad's unit type. Stack the squad chits accoridng to the unit counts below, then place their corresponding unit marker on the top of the stacks. Place these squads on your Headquarters tile.
  * Starting squads
    * Infantry - 6 units
    * Rocketeer - 6 units
    * Mech - 4 units
* Deciding who goes first
  * Play a round of _Rock, Paper, Scissors_. The winning player goes first.

### Tiles

Tiles may only have one squad on them at any time. Some tiles have attack or defense  bonuses. Tiles may also impede or prevent movement for some units.

 | Tile     | Battle Effect                           | Discovery/Movement Effects                                 |
 | :------- | :-------------------------------------- | :----------------                                 |
 |  Plains  |  No Effect                              | No Effect                                         |
 |  Forest  | +1 Defense to squad as a whole          | Mechs are impeded for the next turn |
 | Mountains| +1 Attack +1 Defense to squad as a whole| Mechs can not move onto mountains |
 | Headquarters     |  No squad Limit on turn 1                | If opponent Headquarters, squad is impeded                    |


### Movement/Exploration
* _Tiles_ are placed upside-down across the field, so that the type of tile is hidden (i.e. you cannot see if a tile is mountain, forest, or plains).
* Tile Reveal happens when you move a squad into “unknown terrain” i.e. move them into fog of war
* Tile Reveal consists of flipping a Tile that was previously unknown terrain.
* One must first declare their intent to move a squad in a given direction, at which point the unknown Terrain Tile is flipped at that location. If the squad can move onto the new tile, it does so. If not, the squad does not move onto the tile, and can not move again during this turn.
* Each squad can only move one tile per turn.
 
### Tile Bonuses

Some tiles offer a Tile Bonus to the first player to move on to that tile. Immediately upon moving onto a tile that offers a Tile Bonus, draw a card from the Tile Bonus Card Deck to your hand. Unless otherwise specified, you may play a Tile Bonus Card on any of your turns. You may only use one Tile Bonus Card per turn.

Though the cards themselves specify their effects, another reference is provided here:

| Bonus | Effect |
| :---- | :----- |
| Survivors Found | You discovered some survivors! **+2 Infantry/Rockets OR +1 Mech.** *Apply this effect immediately.* |
| Artillary Strike | You strike from a distance. **Pick any enemy squad to take one health away from.** |
| Extra Ammo | **Once during combat, you may attack twice.** |
| Boost (aka *Haul Ass*) | **Move one squad twice in one turn.** |
| Scout | You deploy a scouting mission. **Reveal two adjacent tiles of your choice.** |

### Turn Actions
* Each squad gets one action
* An action consists of either a move, an attack, or resetting that unit's _impeded_ state.
* Squads can also choose not to perform any action on their turn.
* Players may play one Tile Bonus Card.
* Once all of a player's squads have expended their actions, or chosen not to perform any actions, the turn is over.

### Combat

Combat occurs when a player's unit attempts to move onto a tile owned by another player.

Each unit type has a specific attack value depending on the unit type it is attacking:

| Infantry   | Value  |
| :--------- | :----- |
| vs. Infantry | 1 atk. |
| vs. Rocketeer | 3 atk. |
| vs. Mech   | 2 atk. |

| Rocketeer | Value  |
| :--------- | :----- |
| vs. Rocketeer  | 1 atk. |
| vs. Mech | 3 atk. |
| vs. Infantry | 2 atk. |

|  Mech  | Value  |
| :--------- | :----- |
| vs. Mech | 1 atk. |
| vs. Infantry | 4 atk. |
| vs. Rocketeer  | 2 atk. |


Combat happens in two stages:

1. The attacking unity adds its attack value, to the _tiles_ bonus values.
2. The defending unit adds its attack value to the _tiles_ bonus

For example, if a squad of 4 mechs attack a squad of 4 infantry, and both do not have any tile modifiers:
1. 4 atk. - 1 def = 3 defending infantry lost
2. 2 atk. - 1 def = 1 attacking mech lost

 ### Capturing your opponent's HQ

To capture your opponent's Headquarters, your infantry must occupy their Headquarters tile for 3 consecuative turns (including the turn they move onto the tile). On the third turn, the Headquarters is captured, and you win!
