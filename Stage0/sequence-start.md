# Interaction Sequences

## Startup Sequence

User will launch the game
User choose the option to play
User selects a level
The Game starts after a countdown of 3 seconds.

## Movement Initiation

launch_game ->
start_game ->
paddle_movement ->
collision count ->
calculate_score ->
exit_game

## One score

collision_count will keep the record of the counter for the missed and
the hit ball.
If the player hits the ball the counter for player1 score increments by 1,
or else the opponent player's score counter increments by 1.
Thereafter, calculate_score gets the counter values for both the players,
compares them and declare the winner.
