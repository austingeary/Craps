<<<<<<< HEAD
# Craps
A Casino Game

This was an exercise completed in the context of the Dunder Data Courses.

<span style="color:green">Here is a simplified game of craps using a single Python class. The basic game of craps is as follows:</span> 

There are two stages to the game. 

1. You make a wager
    If you roll a 2, 3 or 12 you lose and the game ends. If you roll a 7 or 11 you win and the game ends.
    If you roll anything else (4,5,6,8,9,10) then the game continues to the second stage.
2. You continue rolling until you roll your original number from the first stage or a 7.
    If you roll your original number you win and the game ends. If your roll a 7 you lose and the game ends.

How to Play:

1. Create a new game using the Craps class, indicating the player's name and their starting balance as attributes:
```
game = Craps(player_name='Austin', starting_money=1000)
```
2. Place a wager using the play() method. The argument is how much you want to bet on this game.
```
game.play(25)
```
3. Rinse and repeat step 2 until you're broke or happy with your balance.