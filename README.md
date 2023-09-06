# Liar's Dice 
This repository will implement the game Liar's Dice using PyGame and create various AI agents for the game.

## Game Overview
Liar's Dice is a bluffing game in which players compete to be the last player with dice remaining in the game. 

## Rules of the Game
- Each player has begins the game with a cup containing 5 dice.
- At the start of each round every player rolls their dice, and conceals them with their cup.
- Then first player begins by placing a bid which is the minimum number of dice of a particular face value they believe are showing under all the cups in the game.
- The following player must then take one of two actions:
  - Call *liar*.
  - Make a higher bid (a bid naming a higher number of dice of any face value).
- If the player calls *liar*, all players in the game reveal their dice.
  - If the last player to make a bid was a liar, meaning that there was a smaller number of dice of the face value predicted than claimed, they lose a die and a new round commences beginning with the player to their left.
  - If the last player to make a bid was not a liar, then the player calling liar loses a die.
- Otherwise, the round continues with play passing clockwise until liar is called.
- When a player loses all their dice they are out of the game.
- The last player remaining with dice wins the game.

  ## Key project steps
 - [ ] Research poker AI projects as the game space is similar and determine what are the most popular libraries.
 - [ ] Construct the game logic.
 - [ ] Implement a GUI so that humans can visualise the game space. 
 - [ ] Implement agents to play the game and train them.
 - [ ] Examine the performance of the most successful agents relative to human players. 
