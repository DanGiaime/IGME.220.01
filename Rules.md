### What is Hexstrat?
Hexstrat is a 2-player turn-based strategy combat game. Players start with their Headquarters at opposite ends of the 44-tile hexagonal map, and work their way across the hidden midfield--revealing tiles as they go--in order to capture their opponent's Headquarters, or defeat all of their opponent's units.

### Win Conditions
* Rout - Defeat all of your opponent's units in combat.
* Demolition - Destroy your opponent's Headquarters.

### Setup
* Begin by selecting the two Headquarters tiles(bright green), and placing them 6 tiles-length apart.
* Place all world tiles onto the field randomly upside-down, so that the terrain icon is not visible.
  * Begin by placing the 6 upside-down tiles between the two Headquarters. Then, build outwards equally on both sides until all tiles have been placed, and a stretched hexagon shape is achieved. The Headquarters should be at opposing corners of the hexagonal map.
* Place all squads onto the Headquarters tile.
  * Starting squads
    * Infantry - 6 units
    * Rocketeer - 4 units
    * Mech - 8 units
* Deciding who goes first
  * Play a round of _Rock, Paper, Scissors_. The winning player goes first.

### Movement/Exploration
* _Tiles_ are placed upside-down across the field, so that the type of tile is hidden (i.e. you cannot see if a tile is mountain, forest, or plains).
* During your turn, your units can move or "Scout" by flipping a nearby Tile that was previously unknown terrain
* Tiles are flipped by either moving into them or scouting them.
* Scouting does not count as an action if only done once, therefore allowing you to scout a tile and move into it or move into a tile and then scout a tile farther way from your original position.
* Each squad can only move one tile per turn, with the exception of infantry, which can move up to three tiles per turn.

### Turn Actions
* Squads can use actions depending on the number tiles they can move.
* An action consists of either a move, an attack, or extra scouting.
* Squads can also choose not to perform any action on their turn.
* Once all of a player's squads have expended their actions, or chosen not to perform any actions, the turn is over.

### Combat

Combat occurs when a player's unit declares an attack on an enemy tile within their attack range.

Each unit type has different attack damages and ranges:

| Unit 		| Damage | Range 	|
| :-------- | :----- | :------- |
| Infantry 	| 2 	 | 0 tiles 	|
| Rocketeer | 4 	 | 1-2 tiles|
| Mech   	| 3 	 | 0-1 tiles|

When the attack is declared:

1. The attacking unit adds values corresponding to the _tiles_ bonuses.
2. The resulting attack value is substracted from the defending unit's count.
3. If the defending units are infantry and still have units in their squad, they may counter-attack.
4a. If both units are on the same tile, the squad that deals more damage in said combat stays in the tile while the other gets kicked out.
4b. If a tie happens in this scenario, both squads are pushed away from the tile to a desired tile in the opposite direction from where the enemy attacked.

Example. Mechs in a Plain tile attack Infantry in the same tile:
1. Mechs have 3 damage, so infantry loses 3 units from their squad.
2. Infantry decides to counter-attack, so the Mechs lose 2 units.
3. Since Mechs dealt more damage and moved from the direction of their base, enemy infantry retreats to a nearby tile in the opposite direction.

### Tiles

Tiles may have two squads on them at any time. Some tiles have attack or range bonuses.

 | Tile     | Battle Effect                           | 
 | :------- | :-------------------------------------- | 
 |  Plains  |  No Effect                              | 
 |  Forest  | +1 Damage to Squad                      | 
 | Mountains| +1 Range to Squad						  | 
 | Headquarters     |  No Effect                      |

### Demolition

To destroy your opponent's Headquarters, your units must attack the Headquarters tile for 5 damage. The player who destroys the Enemy Headquarters wins!

### Playtesting Notes
* For reference, the map layout consisted of:
	* 24 Plains
	* 12 Forests
	* 6 Mountains
* Balance Notes:
	* Rocketeers are extremely powerful when in mountains.
	* Infantry are exceptional at scouting the map and dealing with Rocketeers, even when in mountains.
	* Infantry are also good at nullifying enemy infantry if you were to get an advantageous position for your Rocketeer.
	* Tanks are good at zoning Infantry, chunking down units from reckless Infantry, and preventing movement of more cautious ones.
	* Because you can damage the Headquarters at a distance, Rocketeers in mountains are less likely to prevent enemy rocketeers from hitting the HQ, which prevents rocketeers from only sitting in mountains.
	* The game feels very tense, as infantry can you
* Fun Notes:
	* Reactive effects like increased damage on counter-attacks need other mechanics to work, for their activation relies on the enemy, and a strategically-sound enemy will only trigger such abilities when the value they will provide to their player becomes meaningless.
	* For example, if you were to have Infantry have an ability that allowed them to counter-attack, with extra damage for each tile they're away from their enemies, it would create a situation were rocketeers cannot deal with infantry until they can kill them before the counter-attack, rendering the ability meaningless.
* Ideas:
	* For each unit you lose you gain a coin, which allows you to buy an upgrade for your unit.
	* This may allow for the decreased damage per missing unit to return.