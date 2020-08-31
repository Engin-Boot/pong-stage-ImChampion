# Player

## Feature

This module provides the player to hit the ball,
move paddles.

Paddle movement keys for Players are
"Up Arrow","Down Arrow" for Player 1
and "s","d" for Player 2.

## Assumptions

- Player 1 will be on left side and Player 2
will be on right side of the Pong Board.

- Pong Ball is placed at the Center of Pong Board.

- Player 2 Paddle movement keys functional only when
'vs player' option chosen.

## Acceptance Criteria

### Scenario: Choose Opponent

Given the player has a device that supports pong game on it

When the player clicks on Start Game option

Then the player is provided with 2 option:

- vs Computer
- vs Player(2 Player game).

### Scenario: Player vs Computer

Given the player has a device that supports pong game on it
and need to choose opponent.

When the player clicks on "vs Computer" option

Then the game begins and the ball is fired
towards player 1 in random direction.

### Scenario: Player vs Player

Given the player has a device that supports pong game on it
and need to choose opponent.

When the player clicks on "vs Player" option

Then a text box pops up for the player 2 to enter his name.
Once the 2nd player enters name and hits 'Enter Game' option
then the game begins and the ball is fired
towards player 1 in random direction.

### Scenario: Player hits the Ball

Given the player has launched the game and playing it

When the player hits the ball with paddle

Then the ball reflects from the paddle its speed
increases according to difficulty level selected.

### Scenario: When player 1 presses "Up Arrow" key

Given the player has launched the game and playing it

When the player 1 presses "Up Arrow" key

Then the paddle moves in upward direction with constant speed.

### Scenario: When player 1 presses "Down Arrow" key

Given the player has launched the game and playing it

When the player 1 presses "Down Arrow" key

Then the paddle moves in downward direction with constant speed.

### Scenario: When player 2 presses "s" key

Given the player has launched the game and has selected
'vs Player' option

When the player 2 presses "s" key

Then the paddle moves in upward direction with constant speed.

### Scenario: When player 2 presses "d" key

Given the player has launched the game and has selected
'vs Player' option

When the player 2 presses "d" key

Then the paddle moves in downward direction with some constant speed.
