implement a single-player multi-level version of a dungeons and dragons board
game.

The game starts with a collection of boards which represent the desired game-levels, running as follows:
• The user chooses a player character.

• The game starts with the first level. Each level consists of several rounds. A round, also called Game

  Tick, is defined as follows:
  – The player performs a single action.
  – Each enemy performs a single action.
• The level ends once the enemies are all dead. In this case, the next level will be loaded up.
• The game ends once the player finished all levels, or if the player dies
