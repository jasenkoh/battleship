**Battleship**



You should write a simple Battleship game.  This game is played on a 6x6 grid, onto which player 1 places 3 ships per square (either horizontally or vertically), which player 2 attempts to find by guessing locations.  Player 2 has 10 guesses in which to hit all 3 squares occupied by the ship.  If he hits all 3 squares before running out of guesses he wins; if he runs out of guesses he loses.

Squares on the grid are referred to by a letter for the row and a number for the column, like the following:

```
 |123456
-+------
A|
B|
C|
D|
E|
F|
```

Thus, players should enter "B3" to refer to the third cell on the second row.

When printing the board, you should use '.' to show squares that have not yet been guessed, 'O' for squares that have been guessed that are misses, and 'X' for squares that have been guessed that are hits.

The start of an example game is the following (you can assume that Player 2 is a good sport and doesn't spy on Player 1's input):


Player 1, please enter the start square for your ship: <player enters "B3" on the console and hits enter>
Player 1, please enter the end square for your ship: <player enters "B5" on the console and hits enter>

```
Board Status:
......
......
......
......
......
......
```

```
Player 2, you have 10 guesses left.  Please enter your guess: <player enters "E2" on the console and hits enter>
That was a miss!

Board Status:
......
......
......
......
.O....
......
```

```
Player 2, you have 9 guesses left.  Please enter your guess: <player enters "B4" on the console and hits enter>
That was a hit!

Board Status:
......
...X..
......
......
.O....
......
```

```
Player 2, you have 8 guesses left.  Please enter your guess: <player enters "B3" on the console and hits enter>
That was a hit!

Board Status:
......
..XX..
......
......
.O....
......

Player 2, you have 7 guesses left.  Please enter your guess: <player enters "B5" on the console and hits enter>
You won!
```

