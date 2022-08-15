# The Witcher Game

The aim of this task is to implement an turn combat game based on the Witcher universe. The player plays for the witcher Geralt of Rivia against a computer that randomly chooses from a set of famous enemies the witcher faced either in the books or in the games.

The game mechanic is fairly simple: both Geralt and the monster have their own health and vigor (stamina). The witcher has the following abilities:
- **Fast attack**, regular attack that has 85 % chance of hitting the opponent and 20 % chance of a critical strike. Does not consume much vigor.
- **Strong attack** has an 60 % hit chance but does significantly more damage than the fast attack. Moreover, has a 40 % critical strike chance. Consumes twice as much vigor as the fast attack.
- **Aard** consumes significant amount of stamina and has a 20 % of stunning the opponent, making him skip his next turn and lose all his vigor.

You are free to add any abilities/signs/potions you want :)

Geralt's opponents will also have their own abilities with their names, effects and costs.

Before both Geralt's and his opponents turn, you need to print out status of the game (health, vigor of both characters). When the character uses any ability, you need to print out which ability it is and what was it's effect.

To illustrate the flow of the game, see this example:
1. The game opens in the menu and allows you to either start a new game or exit.
2. When the game starts, the computer randomly chooses Geralt's opponent and also randomly chooses who starts.
3. The game starts with the first round where the first character plays it's ability. Then his opponent plays his ability.
4. The round ends and both characters replenish their vigor by an amount you will set.
5. The second round starts. The flow is the same as steps 3 and 4.
6. The game ends when one of the characters is killed.

The assignment is intentionally left vague in some areas like cost of the attacks. You are free to choose your own values, hit chance percentages, crit changes and so on. Let's make it fun :)
