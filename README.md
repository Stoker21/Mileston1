# Risk
# v0.0.1

Risk is a strategy board game where the goal is to conquer every territory on
the map.

The map consists of 16 territories. The territories are divided into six
continents:

Asia            (4 territories)
North America   (4 territories)
Africa          (3 territories)
Europe          (3 territories)
Australia       (2 territories)
South America   (2 territories)

Each territory is represented by a node on the map. Each continent is
represented by a color. Adjacent territories are connected by a line (edge).

The game starts with four players. Before the game begins, each player is
randomly assigned four territories. Each of these territories will start out
with one army. The order of the players is randomly determined.

Player Turn: Drafting
--------------------------------------------------------------------------------
At the beginning of a player's turn, the player gains a number of armies equal
to the number of territories in the player's control. Furthermore, a bonus
number of armies is granted for every entire continent under control:

Asia            3
North America   3
Africa          2
Europe          2
Australia       1
South America   1

The player then chooses where to place the new armies, as long as they are in
controlled territories.

--------------------------------------------------------------------------------

Player Turn: Attacking
--------------------------------------------------------------------------------
After drafting the new armies, the player can choose to attack adjacent enemy
territories.

The attacker gets one, two, or three dice to attack during a round of battle.
The number of dice is equal to the number of armies used to attack (minimum of
one, maximum of three). However, the attacking territory must have at least two
armies in order to attack, and at least one army cannot participate in the
attack at all.

Armies		Can use for attack
  2                 1
  3                 2
  4+                3

The defender gets one or two dice to defend during a round of battle. The
number of dice is equal to the number of armies used to defend (minimum of one,
maximum of two).

The top dice rolls of the attacker and defender are compared in each round of
battle (highest to highest, second-highest to second-highest). Each lower roll
loses an army. For each draw, the attacker loses an army.

For example, if an attacker rolls 4, 3, 3, and the defender rolls 3, 2, then
the defender loses two armies. If an attacker rolls 5, 2, 1, and the defender
rolls 3, 2, the defender loses one army, and the attacker loses one army.

If an enemy territory's armies are completely wiped out, the attacking
territory must move at least a number of armies equal to that used in the most
round of battle. However, at least one army must remain behind.

For example, an attacking territory has five armies. It uses three armies (the
maximum) in a round of battle against an enemy territory. The enemy territory
is cleared out. The attacking territory must move at least three armies into
the conquered territory, leaving at least one behind, since every territory
must be occupied by at least one army.

--------------------------------------------------------------------------------

Player Turn: Fortifying
--------------------------------------------------------------------------------
At the end of the turn, the player may choose to move any armies to any
adjacent controlled territories. However, each territory must keep at least one
army.

--------------------------------------------------------------------------------

Victory
--------------------------------------------------------------------------------
Winning is achieved by eliminating all other players and controlling every
territory on the map.

The rules for this game were adapted from
https://en.wikipedia.org/wiki/Risk_(game)
