# Changelog

The version history of Endless Labyrinth for Windows. From version 2.0.0 the game updates itself when you ask it to: choose **Check for Updates** on the main menu, and your high scores, Event High Scores and settings are kept. If you have 1.0.1 or older, download **Endless Labyrinth.zip** from the [Releases page](https://github.com/DevHinderman2026/Endless-Labyrinth/releases/latest) once more, and copy your `players` folder from your old copy of the game into the new one, so your scores and settings come with you; every update after that is one key press.

Events are not listed here: new events reach your game through this repository, without a new version.

## 2.0.0 (6 November 2026)

A difficulty overhaul, and the game now updates itself when you ask. Tuned by ear.

### New

- **Check for Updates.** A new entry on the main menu, after Key Test. The game says the newest version number and what is new, and asks you to press Y to update or N to stay. Press Y and it downloads the new version, says how far it has got, checks the download, closes, installs the update over itself and starts again on its own. Your `players` folder, with every score and setting, is never touched. Nothing is ever downloaded without your Y, and there are no automatic updates. The start-up notice about a new version now points you to Check for Updates. The help explains it all under General, Updates.
- The Terms of Use and Privacy Policy (`TERMS.md` and `PRIVACY.md`) now ship inside the game, next to the license.

### Changed: battle mode

- **The emergency cartridge** (the one that appears when you run dry by firing mid-wave) now holds enough shots to finish the wave, and never fewer than three. It used to hold only enough for the enemies in the room at that moment, which was often one or two shots: not enough to finish the wave, which made it no rescue at all.
- **Wave breaks** start at 45 seconds and get a second shorter every wave, down to 30 seconds from wave sixteen on. They used to start at 24 seconds and fall to 10, which left no time to find credits and ammo by ear once the waves grew. The 60-second clock and the credit values are unchanged.

### Changed: tower mode (and chaos tower floors)

- **Each tower is one and a half times as hard as the one below it**, instead of twice. By tower four that is about three and a half times tower one instead of eight times.
- **On tower one, floors one, two and three need one, two and three hits** to bring the rival down.
- **A thrown item never takes more than 25 health**, in tower mode and on chaos tower floors alike: four clean hits from full at the hardest. It used to reach 40 by tower three (three hits) and 55 deep in a climb (two hits).

### Changed: standard mode labyrinths (and chaos labyrinths)

- **Levels past 10 grow gently.** Every labyrinth has always had a way out, but from about level 15 the walls were so dense and the room so large that the way out could not be found by ear in the time: at level 20 the shortest route averaged 36 steps and could pass 80. Levels 1 to 10 are unchanged; after that the room grows half as fast and the walls thicken half as fast, never past a quarter of the cells, so level 20 averages 22 steps and level 40 about 33. Every level is still a little bigger than the last.

### Changed: events

- **Follow the guide: the guide speeds up.** In The Music Box and Whale Song the guide walks a little faster as the run goes on, so a run with no clock ends in the end: the longer you keep up, the higher your score. Event makers get three settings for it: how often, by how much, and the top speed. Events made before 2.0.0 get the defaults (every 15 seconds, 0.1 steps a second faster, up to 3) without any change to their files.

### Unchanged

- Island mode, driving mode, and everything else in chaos mode.

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
