### What is Hexstrat?
Hexstrat is a 2-player turn-based strategy combat game. Players start with their Headquarters at opposite ends of the 3x3x3 hexagonal map, and work their way across the hidden midfield--revealing tiles as they go--in order to capture their opponent's Headquarters, or defeat all of their opponent's units.

### Win Conditions
* Rout - Defeat all of your opponent's units in combat.
* Seize - Capture your opponent's Headquarters.

### Setup
* Begin by selecting the two Headquarters tiles(bright green), and placing them exactly 3 tiles-length apart.
* Place all world tiles onto the field randomly upside-down, so that the logo is not visible.
  * Begin by placing the 3 upside-down tiles between the two Headquarters. Then, build outwards equally on both sides until all tiles have been placed, and a hexagon shape is achieved. The Headquarters should be at opposing corners of the hexagonal map.
* Place all units onto the Headquarters tile.
  * Starting Units
    * Infantry - 10
    * Mech - 3
* Deciding who goes first
  * Each player rolls a d20. The player who rolls the highest goes first. The turn order is counterclockwise.

### Movement/Exploration
* _Tiles_ are placed upside-down across the field, so that the type of tile is hidden (i.e. you cannot see if a tile is mountain, forest, or plains).
* Tile Reveal happens when you move a unit into “unknown terrain” i.e. move them into fog of war
* Tile Reveal consists of flipping a Tile that was previously unknown terrain.
* One must first declare their intent to move in a given direction, at which point the unknown Terrain Tile is flipped at that location. If the moving Unit can move onto the new tile, it does so. If not, the Unit goes into a Stunned state for a turn, and does not move.
* A given Squadron of units can reveal at most one tile per turn.

### Turn Actions
* Each Unit gets one Action
* An Action consists of either a move or an attack
* Units can move or attack in groups. No more than one full squad can move/attack at a time.
* Units can also choose not to use their Action this turn.
* Once all Units have expended their actions or chosen not to use them, the turn is over.

### Battle
* Battle occurs when one Unit declares an attack on an adjacent Unit owned by the other player.

| Roll  | Modifier |
| :---- | :------- |
| 1     |    0     |
| 2-9   |    +1    |
| 10-14 |    +2    |
| 15-19 |    +3    |
| 20    |    +4    |
1. Each player rolls a d20. Each player gets a modifier according to the result of their roll. See the table above for modifiers.
  * The attacking player rolls for an attack boost, whilst the defending player rolls for a defense boost.
2. Calculate total unit attack + tile attack modifier (if any) + roll attack modifier for the attacking player
3. Calculate total unit defense + tile defense modifier (if any) + roll defense modifier for the defending player
4. If total attack > total defense, the defending player loses the difference in units
5. If total defense >= total attack, the attacking player remains in their current location and is impeded


### Tiles
* Tile Effects
 * When this Unit is on a given tile, it experiences the following effect


 | Tile     | Battle Effect                           | Discovery/Movement Effects                                 |
 | :------- | :-------------------------------------- | :----------------                                 |
 |  Plains  |  No Effect                              | No Effect                                         |
 |  Forest  | +1 Defense to squad as a whole          | Mechs are impeded |
 | Mountains| +1 Attack +1 Defense to squad as a whole| Mechs return to previous position and are impeded |
 | Headquarters     |  No Unit Limit on turn 1                | If enemy Headquarters, Unit is impeded                    |
* Tiles can hold at most one squad of Infantry, or one squad of Mechs unless otherwise stated.

### Units
* __Infantry__
  * Attack - 1
  * Defense - 1
  * Description
    * A mobile Unit capable of moving on any Tile. Can Seize an enemy's Headquarters.
  * Squad size - 5
* __Mech__
  * Attack - 2
  * Defense - 1
  * Description
    * A strong Unit capable of moving onto Plains and Forest Tiles. Cannot Seize an enemy's Headquarters.
  * Squad size - 3
