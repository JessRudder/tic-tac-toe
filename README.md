Want to build a tic tac toe app that allows a user to select from multiple versions of the game tic-tac-toe

The game should keep an overall score (W/L/D for each game type played)

The game should have a funny name generator
 - It should allow the user to enter their name but always change it to a funny name built on that name

There should be a menu that allows you to select which type of tic-tac-toe you're going to play:

Current varieties under consideration
1) Tic-Tac-Toooooooooh No!
    - A combo of tic-tac-toe and hot potato which forces users to make quick decisions as they don't want it to be their turn when the random timer ends and the game explodes
    - Lose by traditional loss (e.g. other player gets a line) OR lose by being the player whose turn it is when the time is up)
    - You don't know how much time you have but a beeping tone gets faster and faster as you near the explosion
2) 8Bit-Tac-Toe
    - Traditional tic-tac-toe with 8-bit game styling and music!
3) Tic-Tac-WeGo
    - Players must select their square at the same time.  Only after the selection has been made will the choices be revealed.
    - Same choices will cancel out (3 same choices in a row = a draw)

Need:
1) Standard tic-tac-toe class (handles normal game logic)
2) Special tic-tac-toe classes that inherit base tic-tac-toe and contain logic unique to that class
3) Overall game controller?
  - I'm thinking this is what would contain the score and the flow for selecting various games, etc
4) Class for the name generator