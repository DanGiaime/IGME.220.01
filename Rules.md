### Win Conditions
* Rout
* Seize

### Units
* __Infantry__
  * Attack - 2
  * Defense - 2
  * Description
    * A mobile Unit capable of moving on any Tile. Can Seize an enemy's base.
* __Mech__
  * Attack - 3
  * Defense - 2
  * Description
    * A strong Unit capable of moving onto Plains and Forest Tiles. Cannot Seize an enemy's base.
    
### Tiles
* Tile Effects
 * When this Unit is on a given tile, it experiences the following effect
 | Tile     | Effect            |
 | :------- | :---------------- |
 |  Plains  |  No Effect        |
 |  Forest  | +1 Defense        |
 | Mountains| +1 Attack/Defense |


### Tile Placement
* _Tiles_ are stored in a stack, upside-down so that the type of tile is hidden (i.e. you cannot see if a tile is mountain, forest, or plains).
* Tile Placement happens when you move a unit into “unknown terrain” i.e. move them into fog of war
* Tile placement consists of grabbing a Tile from the Tile Stack
* Tile stack, and placing it where one intends to move. One must first declare their intent to move in a given direction, at which point a Terrain Tile is drawn and placed at that location. If the moving Unit can move onto the new tile, it does so. If not, the Unit goes into a Stunned state for a turn, and does not move.
* A given Unit can reveal at most one tile per turn.

### Turn Order
1. Move Unit(s) (if not impeded)
2. Reveal Tile (If Unit in fog)
3. Attack (if there is another Unit on the Tile being moved to)

### Battle
* Battle occurs when one Unit declares an attack on an adjacent Unit owned by the other player.

|    Roll     | Modifier |
| :---------- | :------- |
| 10 or below |    +1    |
| 11 or higher|    +2    |
1. Each player rolls a d20. Each player gets a modifier according to the result of their roll. See the table above for modifiers.
2.

The attacking player rolls for an attack boost, whilst the defending player rolls for a defense boost.
