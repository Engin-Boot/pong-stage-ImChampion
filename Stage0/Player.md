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

## Acceptance Criteria

### Scenario: Player starts new game

Given the player has a device that supports pong game on it
and the player clicks "Start Game"

When the player clicks on "Begin" button

Then the ball(which is at center) is fired
towards player 1 in random direction.

### Scenario: Player hits the Ball

Given the player has launched the game and playing it

When the player hits the ball with paddle

Then the ball reflects from the paddle and
its speed increases by 15%.

### Scenario: When player 1 presses "Up Arrow" key

Given the player has launched the game and playing it

When the player 1 presses "Up Arrow" key

Then the paddle moves in upward direction with constant speed.

### Scenario: When player 1 presses "Down Arrow" key

Given the player has launched the game and playing it

When the player 1 presses "Down Arrow" key

Then the paddle moves in downward direction with constant speed.

### Scenario: When player 2 presses "s" key

Given the player has launched the game and playing it

When the player 2 presses "s" key

Then the paddle moves in upward direction with constant speed.

### Scenario: When player 2 presses "d" key

Given the player has launched the game and playing it

When the player 2 presses "d" key

Then the paddle moves in downward direction with some constant speed.
