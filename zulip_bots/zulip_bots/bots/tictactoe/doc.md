# About Tic-Tac-Toe Bot

This bot allows you to play tic-tac-toe in a private message with the bot.
Multiple games can simultaneously be played by different users, each playing
against the computer.

The bot only responds to messages starting with @mention of the bot(botname).

### Commands
**@mention-botname new** will start a new game (but not if you are
already playing a game.) You must type this first to start playing!

**@mention-botname help** will return a help function with valid
commands and coordinates.

**@mention-botname quit** will quit from the current game.

**@mention-botname <coordinate>** will make a move at the
entered coordinate. For example, **@mention-botname 1,1** . After this, the bot will make
its move, or declare the game over if the user or bot has won.

Coordinates are entered in a (row, column) format. Numbering is from top to
bottom and left to right.
Here are the coordinates of each position. When entering coordinates, parentheses
and spaces are optional.

(1, 1)  | (1, 2) | (1, 3)

(2, 1)  | (2, 2) | (2, 3)

(3, 1)  | (3, 2) | (3, 3)

Invalid commands will result in an "I don't understand" response from the bot,
with a suggestion to type **@mention-botname help** .
