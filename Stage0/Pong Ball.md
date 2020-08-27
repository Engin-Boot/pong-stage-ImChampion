# Pong Ball

## Feature

This module provides the functionality of
the ball when it collides with wall.

## Assumptions

- Pong ball placed at the center of Pong Board
at the start of game, and whenever any player
gets a point.
- When a player gets point then for the
next round the ball will be fired in its direction.

## Acceptance Criteria

### Scenario: Ball hits the left wall

Given the player has launched the game and playing it

When the ball hits the left wall

Then player 2 score is incremented by 1. And the final
score of player 2 is checked if it equals 10 the call
the "Declare Winner" module.

### Scenario: Ball hits the right wall

Given the player has launched the game and playing it

When the ball hits the right wall

Then player 1 score is incremented by 1. And the final
score of player 1 is checked if it equals 10 the call
the "Declare Winner" module.

### Scenario: Ball hits the top or bottom wall

Given the player has launched the game and playing it

When the ball hits the top or bottom wall.
Then depending on the velocity of the ball,
The ball will be reflected from the wall.
