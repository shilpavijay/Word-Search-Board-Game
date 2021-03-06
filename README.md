Board-Game-in-Python
====================

Game Description:

For A3, you will implement a word search game. The game involves an rectangular board of uppercase letters that is read from a file. For example, here are the file contents representing a (tiny) 2 row by 4 column board:

ANTT
XSOB
The game also involves a non-empty words list read from a file. For example, here are example file contents for a words list:

ANT
BOX
SOB
TO
To make it a bit more challenging, there may be words in the words list that do not appear in the board, and the word list is not shown to the players.

The object of the game is for the players to view the board and find words (remember that the words list is unknown to the players). Words may be contained in rows (from left to right) or columns (from top to bottom), but not backwards. When a player correctly guesses a word that occurs in the words list, that player is awarded points according to a scoring system described in the starter code. The game ends when all words on the board that appear in the words list have been guessed.

The player with the highest score wins.

The words from the words list and the letters of the board are made up of alphabetic, uppercase characters.
