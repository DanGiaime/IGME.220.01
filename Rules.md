### What is Hexstrat?
Hexstrat is a 2-player turn-based strategy combat game. Players start with their Headquarters at opposite ends of the 3x3x3 hexagonal map, and work their way across the hidden midfield--revealing tiles as they go--in order to capture their opponent's Headquarters, or defeat all of their opponent's units.

### Game Pieces
#### Units
* **12** Infantry units, 6 per player
* **12** Rocketeer units, 6 per player
* **8** Mech units, 4 per player
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
* Begin by selecting the two Headquarters tiles(bright green), and placing them exactly 3 tiles-length apart.
* Place all world tiles onto the field randomly upside-down, so that the logo is not visible.
  * Begin by placing the 3 upside-down tiles between the two Headquarters. Then, build outwards equally on both sides until all tiles have been placed, and a hexagon shape is achieved. The Headquarters should be at opposing corners of the hexagonal map.
* Place all squads onto the Headquarters tile.
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
 
#### Tile Bonuses

Some tiles offer a Tile Bonus to the first player to move on to that tile. Immediately upon moving onto a tile that offers a Tile Bonus, draw a card from the Tile Bonus Card Deck to your hand. Unless otherwise specified, you may play a Tile Bonus Card on any of your turns. You may only use one Tile Bonus Card per turn.

Though the cards themselves specify their effects, another reference is provided here:

| Bonus | Effect |
| :---- | :----- |
| Survivors Found | You discovered some survivors! **+2 Infantry/Rockets OR +1 Mech.** *Apply this effect immediately.* |
| Artillary Strike | You strike from a distance. **Pick any enemy squad to take one health away from.** |
| Extra Ammo | **Once during combat, you may attack twice.** |
| Boost (aka H A U L   A S S) | **Move one squad twice in one turn.** |
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
