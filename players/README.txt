The players folder holds each player's save data:

  highscores.dat  - the high score of every mode, scrambled and sealed.
  events.dat      - the permanent Event High Score and each event's best run, scrambled and sealed.
  settings.json   - the player's settings (Braille speech on or off).

The game makes these files itself. A save changed outside the game is refused, set aside as a
.rejected copy, and started fresh. The Event High Score can never be reset.
