# Rock_paper_Scissors
This game is also known also Stone paper scissors.Rock paper scissors is a hand game originating from China, usually played between two people, in which each player simultaneously forms one of three shapes with anoutstretched hand. 
These shapes are “rock,” “paper,” and “scissors.”
In this project, we are demonstrating Rock Paper and Scissor game in Java Programming Language where one player will be Computer and the other player is User.

#Rules of Rock Paper Scissors Game
1. The Rock beats the Scissors (rock crushes scissors)
2. The Scissors beats the Paper (scissors cut paper)
3. The Paper beats the Rock
4. If both players create the same formation then the game is a tie or draw.
5. There should be at least 2 players required to play this game.
We can create a two-player Rock Paper Scissor game in Java using if else condition and Java.util.Random.nextInt() function.

#Pseudo Code for Rock Paper Scissors Java Program
1. Prompt Player to enter any one of the following entries: ROCK, PAPER, SCISSORS.
2. getPlayerMove() method uses Scanner class to get the move of the player. This method will print and return the move enter by the player.
4. getComputerMove() method uses Random class nextInt(num) method. nextInt(num) method produces the random number between 0 (inclusive) and num (exclusive). getComputerMove() method will print and return the computer move.
6. If playerMove and computerMove are the same, then the game is a tie or draw.
7. Else if playerMove and computerMove are different, then 3 cases are possible.
  a. If playerMove is ROCK and computerMove is PAPER then computer wins. If playerMove is ROCK and computerMove is SCISSORS then the player wins.
  b. If playerMove is PAPER and computerMove is SCISSORS then computer wins. If playerMove is PAPER and computerMove is ROCK then the player wins.
  c. If playerMove is SCISSORS andcomputerMove is ROCK then computer wins.If playerMove is SCISSORS and computerMove is PAPER then the player wins.
