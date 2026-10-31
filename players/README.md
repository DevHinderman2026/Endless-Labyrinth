# The players folder

This folder holds each player's save data. The game makes these files itself, and they are saved only on the player's own computer: Git never uploads them.

| File | What it holds |
| --- | --- |
| `highscores.dat` | The high score of every mode, scrambled and sealed. |
| `events.dat` | Event High Scores: the best run in every event played, scrambled and sealed. |
| `settings.json` | The player's settings (Braille speech on or off). |

A save changed outside the game is refused, set aside as a `.rejected` copy, and started fresh. A save that cannot be read for a moment is left untouched, and nothing is saved that session. Event High Scores can never be reset.
