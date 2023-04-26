# Battleship

Battleship is a Python terminal game which runs in the Code Institute mock terminal on Heroku.

Users can play against the computer, trying to find all the computer´s battleships before the computer finds the user´s battleships. Each battleship occupies one square on the game board.

Here is the live version of my project.

### How to play

Battleship is based on the classic pen-and-paper game. Here is more info about it in Wikipedia.

In this version, to guess the battleship location, the player first enters the row (number 1-8) of the ship on the game board.

Then the player enters the column (Letters A-H) of the ship on the game board to guess the battleship location.

Misses are indicated by the minus (-) sign.

Hits are indicated by X.

The player wins when all of the computer´s battleships are sunk.

There are 10 turns in this game.

## Features

### Existing Features

+ Ships are randomly placed on the game board
+ The player cannot see where the computer´s ships are
+ Game board size: 8 rows and 8 columns

## Testing

I have manually tested this game by doing the following:

+ Passed the code through a PEP8 linter and made required changes to pass the code with no problems.

+ Given invalid inputs: Letters when numbers are expected and vise versa.

+ Tested in my local terminal and the Code Institute Heroku terminal

## Bugs

+ No bugs

+ No bugs remaining

## Validator Testing

+ No errors were returned from PEP8online.com

## Deployment

This project was deployed using Code Institute´s mock terminal for Heroku.

### Steps for Deployment

+ Fork or clone this repository
+ Create a new Heroku app
+ Set the buildbacks to Python and NodeJS in that order
+ Link the Heroku app to the repository
+ Click on deploy

## Credits

+ Wikipedia for the details of the Battleships game

+ The game is based on the code from Knowledge Mavens on YouTube - How to Code Battleship in Python - Single Player Game:

https://youtu.be/tF1WRCrd_HQ

+ (99.9% of the code is from this video simply because I didn´t have an idea how to build this game, not even how to get started. I don´t want to steal code so I´m fully crediting it here to Knowledge Mavens on YouTube because the code is not mine.)
