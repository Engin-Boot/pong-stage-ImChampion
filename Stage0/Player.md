# Player

## Feature

The player would be able to move the paddle
and hit the ball.

## Acceptance Criteria

### Scenario: Player hits the ball

Given the player is on pong game.
And the size of paddle is fixed for both players.
When a player hits the ball.
Then the ball goes to the opponent player and
the player has to wait for the response from opponent.

### Scenario: Player misses the ball

Given the player is on pong game.
And the size of paddle is fixed for both players.
When a player misses the ball.
Then a point should be incremented in scorecard
of the opponent player.
