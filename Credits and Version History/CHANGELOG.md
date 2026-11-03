# Changelog

The version history of Endless Labyrinth for Windows. To get the latest version, download **Endless Labyrinth.zip** from the [Releases page](https://github.com/DevHinderman2026/Endless-Labyrinth/releases/latest). When you update, copy your `players` folder from your old copy of the game into the new one, so your high scores, Event High Scores and settings come with you.

Events are not listed here: new events reach your game through this repository, without a new version.

## 1.0.1 (2 November 2026)

A bug-fix release. Every mode plays as it did, with the problems below put right.

### New

- **Update notice.** When a newer version of the game is out, the main menu tells you once each time the game starts, with the version number. Nothing is downloaded by itself.

### Changed

- **High scores start at zero.** A new or reset board says "No score yet", and any score of one or more is a record. Your saved scores are kept.
- **Chaos time credits.** The 40-second chaos credit has its own beacon, between its neighbours in pitch and spin. It used to sound exactly like battle mode's 20-second credit. The Chaos Credits help demo is updated to match.
- **The Morse exit** now spells EXIT in full. A letter was missing.
- **Battle's emergency cartridge** appears only when you run dry by firing during a wave, not when you start a wave already empty.
- **Shots from behind.** The help now says plainly that in battle mode and on islands you can hit an enemy straight behind you as well as in front, on purpose, because the later waves come too fast to turn.
- **Walking through an enemy.** In battle mode and on islands, a step that passes straight through an enemy counts as reaching it, except in the moment of grace when you arrive on an island.
- **The island guardian** that hunts you when you are out of shots now moves faster than a steady walk.
- **Built-in background drones** (used only when the recorded ones are missing) now loop without a seam.

### Fixed in the modes

- Battle mode: dying during a break no longer counts the next wave as reached.
- Battle and island enemies now appear at the same pace on every computer, however fast or slow it runs.
- Tower mode: beyond the eleventh tower, the rival's throwing never slows down.
- Driving mode: a shot can no longer destroy a car too far ahead to be heard yet.
- Driving mode: an overpass's echo now reaches its full level.

### Fixed in events

- **Lives:** a touch that costs a life now costs only the life, never points as well.
- **Defuse:** the bonus for finding every bomb, which the game announced, is now really added.
- **Sneak:** walking into a sleeping guard no longer hurts you; it wakes the guard at once, and it hunts you. A quiet snore now plays softly, as intended.
- **Fishing:** a cast catches only fish in front of you, as the help says.
- **Defend the Treasure:** creatures ignore you; only reaching the treasure costs one of its lives.
- **Real and False:** with more than one real bell, every real bell now has false look-alikes.
- **In Order:** a round never asks for more notes than fit, which could stop the game. **Pairs** always gives as many pairs as the event asks for.
- **Whack-a-mole:** no miss is counted at the very start of a run.
- **Lamplighter:** relighting a lamp no longer earns endless points late in a run.
- **Rhythm:** a press just before a beat no longer counts that beat as a miss too.
- Events that do not use items no longer place silent ones.

### Fixed in help and menus

- Standard mode's credit demos give the right values (15, 20 and 30 seconds).
- The Help Menu topic mentions the Events section.
- The Events menu no longer says "live" when the game is offline, and offline it still lists the events it can show.

## 1.0.0 (1 November 2026)

The first release of Endless Labyrinth: an audio game for Windows, played by ear with headphones, for blind and sighted players alike.

### Modes

- **Standard mode:** find the way out of labyrinth after labyrinth before the clock runs out. Each level adds time, and time credits turn up along the way.
- **Battle mode:** hold off endless waves of enemies in an open arena, gathering ammo and time credits in the breaks between waves.
- **Driving mode:** drive a three-lane road by ear, dodging or shooting oncoming cars, with two high scores: cars destroyed and distance.
- **Tower mode:** climb towers floor by floor, racing a rival for the items on each floor and throwing them at it.
- **Island mode:** clear a chain of islands, diving by elevator to the seabed for each island's key while your air lasts.
- **Chaos mode:** every kind of level mixed at random, against one five-minute clock, scored in points.
- **Events:** special challenges that are open only for a while, from half an hour to a few weeks, each with its own Event High Score. New events reach the game from this repository, with no new download.

### Sound

- Everything is placed by sound: left and right, near and far, and a duller sound for anything behind you.
- A slight room echo in the labyrinth, the battle arena, the tower and the road's tunnels, shaped by the walls around you.
- Real recorded backgrounds, footsteps, pickups and hits from Pixabay, all credited, alongside the game's own generated beacons and enemies.

### Help and accessibility

- Help (H) explains every mode, every key and every sound, with demo sections that play each sound.
- The game speaks for itself and works with screen readers. With a Braille notetaker such as the BrailleNote Evolve, or a Braille display with NVDA, it shows everything in Braille too.

### Saves and sounds

- High scores, Event High Scores and settings are saved only on your own computer, in the `players` folder, sealed so a changed save is refused.
- The game plays offline. Online, it checks for events and puts back any of its sounds that are missing or damaged, from the latest release.
