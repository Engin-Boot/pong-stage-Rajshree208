# Interaction Sequences

## Startup Sequence

User will launch the game
User choose the option to play
User selects a level
The Game starts after a countdown of 3 seconds.

## Movement Initiation

launch-game ->
start-game ->
paddle-movement ->
collision-count ->
calculate-score ->
exit-game

## One score

Collision-Count will keep the record of the counter for the missed and
hit ball.
If the player hits the ball, the counter for player's score increments by 1,
or else the opponent player's score counter increments by 1.
Thereafter, Calculate-Score gets the counter values for both the players,
compares them and declare the winner.
