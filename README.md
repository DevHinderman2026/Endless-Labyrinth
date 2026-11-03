# Endless Labyrinth

Endless Labyrinth is an audio game for Windows, made to be played by ear, by blind and sighted players alike. Everything you need to know is in what you hear: where the exit is, where an enemy is coming from, how close a time credit is, and how much time is left. Play with headphones: left, right, near, far and even behind you are all told by sound.

## What's in the game

- **Standard Mode:** find the way out of labyrinth after labyrinth before the clock runs out.
- **Battle Mode:** hold off wave after wave of enemies in an open arena.
- **Driving Mode:** drive an open road by ear, dodging and shooting oncoming cars.
- **Tower Mode:** climb a tower floor by floor against a rival.
- **Island Mode:** fight across a chain of islands joined by the seabed.
- **Chaos Mode:** every kind of level, mixed together.
- **Events:** special challenges that are only open for a while, with their own Event High Scores.

Press H at any time for help, which explains every mode, every key and every sound, with demos you can listen to.

**Credits and version history:** see the [Credits and Version History](Credits%20and%20Version%20History) folder: [CHANGELOG.md](Credits%20and%20Version%20History/CHANGELOG.md) lists what each version of the game brought, and [CREDITS.md](Credits%20and%20Version%20History/CREDITS.md) credits every recorded sound.

The game speaks through its own speech, and works with screen readers. With a Braille notetaker such as the BrailleNote Evolve, or a Braille display and NVDA, it shows everything in Braille too.

## Download and play

1. Open the [latest release](https://github.com/DevHinderman2026/Endless-Labyrinth/releases/latest).
2. Download **Endless Labyrinth.zip**. It holds everything: the game and all of its sounds.
3. Unzip it anywhere you like, for example your Documents folder.
4. Open the **Endless Labyrinth** folder and run **Endless Labyrinth.exe**.

Nothing needs to be installed. The game runs on Windows.

## Online and offline

The game plays offline. When it starts with an internet connection, it also:

- checks this repository for events, so new events appear in your Events menu without a new download;
- checks its sounds, and puts back any that are missing or damaged from the game's latest release, so a sounds folder you delete by accident comes back by itself.

## Your saves

High scores, Event High Scores and settings are saved only on your own computer, in the game's `players` folder. They are never uploaded. They are scrambled and sealed, so a save changed outside the game is refused.

## Credits

Endless Labyrinth is designed and directed by Russell Hinderman (DevHinderman2026). Every recorded sound is credited, with its author and a link to the original, in [CREDITS.md](Credits%20and%20Version%20History/CREDITS.md); a copy is in the download too.

## What's in this repository

- `Credits and Version History`: the game's changelog, and a copy of the credits for every recorded sound. The sounds themselves come only inside the game download.
- `Dev Builds/sounds/CREDITS.md`: the original credits, which the game's own files are kept with.
- `Dev Builds/event_key.pub`: the public half of the developer's event key, which the game uses to check that an event is genuine.
- `events`: the event files the game reads. Every event is signed, and the game plays only events signed by the developer.
- `LICENSE.md`: how the game may be used. All rights reserved; the sounds are used under Pixabay's license.

The game itself is downloaded from [Releases](https://github.com/DevHinderman2026/Endless-Labyrinth/releases); this repository is where its events come from.
