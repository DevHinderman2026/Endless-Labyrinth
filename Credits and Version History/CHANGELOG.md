# Changelog

The version history of Endless Labyrinth for Windows. From version 2.0.0 the game updates itself when you ask it to: choose **Check for Updates** on the main menu, and your high scores, Event High Scores and settings are kept. If you have 1.0.1 or older, download **Endless Labyrinth.zip** from the [Releases page](https://github.com/DevHinderman2026/Endless-Labyrinth/releases/latest) once more, and copy your `players` folder from your old copy of the game into the new one, so your scores and settings come with you; every update after that is one key press.

Events are not listed here: new events reach your game through this repository, without a new version.

## 4.0.0 (November 2026)

True 3D sound for headphones, turning in the walking modes, a new mode, Find the Voice, an arena crowd in every battle, the modes brought in line with the website, new things for events, and many fixes. It comes out alongside web version 6.0.0, so the two play alike and events stay the same in both. Version 3.1.0 was never released: everything it was to bring is part of 4.0.0, and is listed here. Every event made before 4.0.0 plays as it always did.

### New: true 3D sound for headphones

- Every sound that has a place is now heard in 3D, worked out for an average head: the same medium head model as Escape the Cave, 17.5 centimetres across, calculated, with no recording of anyone's ears. A sound from one side reaches your far ear a fraction of a millisecond later and duller, and a sound behind you is duller in both ears.
- It is always on. **Headphones are needed**: speakers mix left and right together, and the game cannot be played without them.
- Every sound that has a place is played from one exact point: a recording made in stereo is made into a single point in memory when the game loads it, so it sits precisely where its thing is. The sound files themselves are unchanged.
- Speech, the background drones and shores, your own footsteps and the menus are not placed.

### New: the walking modes turn with you

- **Which modes:** Standard, Battle, Tower, Island, Find the Voice and the walking levels of Chaos. You turn where you stand, the whole world turns round you, the backgrounds included, and you walk the way you face.
- **Left and Right turn you:** a press is a quick turn of 30 degrees, so three presses are a quarter turn and six turn you right round; hold one to keep turning, slowly at first and then faster, and let go to stop exactly there.
- **Up walks the way you face**, and held down it runs. **Down takes one step straight back**, and held down it walks backwards.
- **Ticks:** as you turn, a soft tick marks east, south and west, a higher tick marks north, and a quick turn that lands between two of them gives a softer click.
- **Walls and edges:** walked straight into, a wall or the edge of the room stops you with its sound. Met at a slant, you slide along it in silence.
- **Aiming:** in Battle, on a tower floor and on an island, a shot or a throw takes what is centred straight ahead of you or directly behind you. Enemies in Battle and on islands now come from any side.
- **The report:** Enter's report ends with the way you are facing, such as Facing north-east.
- **Which do not turn:** Driving, the roads in Chaos, the events and an elevator ride. There the four arrows work exactly as they always have, with north ahead.
- **If you played before 4.0.0:** in the modes that turn, Left and Right no longer step you west and east, and there is no sidestep any more. To step to the side, turn a quarter, three presses of Left or Right, then press Up. If you never turn, Up and Down still go north and south as before. The help has a topic on this: General Turning, If You Played Before 4.0.0.

### New: Find the Voice

- **A new mode,** on the main menu between Island Mode and Chaos Mode. A woman's voice, the guide, calls to you from somewhere in a dark room: over here, this way, follow me, and hundreds more. Turn until her voice is centred, walk to her, and when you are within two steps of her a chime sounds; after half a second of quiet she calls again from somewhere new. Five finds complete a level, and on each level she stands farther away.
- **A creature that listens.** A blind creature shares the room and hunts by sound. The floor is concrete with patches of broken glass: step on glass and it charges, growling, with a footstep for every step it runs, for as long as you are on glass and 3 seconds after you are back on concrete; every charge lasts at least 5 seconds, even after a single step on glass. It runs a little slower than you can run. If it catches you, you lose a life.
- **Three lives and no clock.** Your score is the number of levels you complete, on a high score board of its own. The first level is always the witch's, and every level after it has a different event background.
- **Her voice is Heart,** a natural American voice made by Kokoro, an open speech model, and recorded for the game: every one of her calls comes with the game's sounds, the same recordings as the website's, so there is nothing to download and nothing to wait for, and her first call comes as soon as the level has been said. With Speech turned off for Braille, no voice is heard for her: a soft shimmering sound plays where she stands in place of her voice. Heart is used for the guide alone: the Windows voice still says everything else.
- **In Chaos Mode,** Find the Voice levels come about as often as islands. The guide must be found three or four times the first time in a run, and one more time each time after, at most eight. Then everything else goes silent and only an exit is heard, the battle exit's Morse signal, and the clock waits until you walk through it. Being caught costs 25 of the run's health (see below).

### New: the arena crowd in Battle Mode and Chaos's battles

- Every battle now has an arena crowd: its murmur under the drums, heard all through the fight everywhere in the arena, and a roar a moment after the explosion when you shoot an enemy down. When an enemy reaches you the battle is over, and the crowd says nothing.
- **When a wave begins, the crowd goes wild.** With the war horn after the five, four, three, two, one, a great roar comes from all round the arena, as loud as a kill's, and the crowd's murmur swells for a few seconds and settles back.
- **The cartridge and credit beacons are twice as loud** in Battle Mode and in Chaos's battles, held to full loudness up close, so you hear them over the crowd.

### New: one health bar for all of Chaos Mode

- **A Chaos run now has one health bar,** as on the website. It starts at 100, and every finished level gives 10 more, with no cap. Every Chaos report states your health.
- **What costs health:** an enemy reaching you in a battle or on an island costs 25; the enemy is gone and counted, and in battles the crowd reacts. An island's guardian costs 25 while you have shots, but takes all your health if you are out of them. Out of air on the seabed, you lose 10 a second. A crash on a Chaos road costs 20 health and its 30 seconds. Being caught in Find the Voice costs 25.
- **Getting it back:** a tower's potion brings you back to 100 if you are below it, and leaves you alone above it.
- **The voice still warns you:** at 35 or below it says "Health low", and how much is left. When health runs out, the run ends.

### Changed: corners in the labyrinths

- **In Standard Mode and Chaos Mode's labyrinths,** where two pieces of wall touch only at their corners, with floor beyond, you now fit through the gap between them when you face it at a slant. An opening you hear straight ahead is one you can walk through. The same on the website, from version 6.3.0.

### Changed: running carries on

- While you run you can press other keys, Space to shoot or throw, Enter for the report, T for the clock, and the run carries on; only another step, or letting go, ends it. In the modes that turn you can turn while you run: hold Left or Right as well and the run curves.

### Changed: the modes, now as on the website

The website's version of the game has rebalanced its modes over the last weeks; 4.0.0 brings those rules to Windows, along with the turning they were made for.

- **Battle.** You start with eighty seconds (was sixty). During a wave the clock waits whenever nothing is after you, and runs again the moment the next enemy appears; during a break it runs as before. Enemies come in turns, never all at once: one at a time in waves 1 to 3, the next appearing only after you shoot the one before, two at once in waves 4 to 6, three in 7 to 9, and four, the most there will ever be, from wave 10. The first wave has six. Breaks start at fifty-two seconds and shrink a second a wave to twenty-five (were forty-five and thirty). Credits are worth fifteen, twenty-five or thirty-five seconds (were ten, fifteen and twenty), and each break holds only three to six of them.
- **Standard.** You start with sixty seconds (was forty-five), and credits are worth twenty, thirty or forty seconds (were fifteen, twenty and thirty).
- **Tower.** The rival is rebalanced to start gentle and still grow every tower with no limit. In tower one it races for an item just faster than you walk, so running wins most races, and it gets five percent faster every tower. Every new item gives you a head start before the rival races for it, a second and a half in tower one. A new item lies four to ten steps from you, never at the rival's feet. Each item you take makes the rival three percent faster, at most five times. In tower one its throws fly slower than you walk, come about every seven seconds and warn you for a second and a half; each tower after, they come faster and more often, with no limit.
- **Island.** A dive now gives twenty seconds of air (was thirty). From ten seconds left you hear Low air, then high beeps that come faster and faster as the air runs out (they were once a second over the last fifteen). Every dive has an air vent (until now about half did), and ten seconds after you take one, another appears somewhere else on the seabed. Every step along the seabed is now a swimming stroke.
- **Chaos.** Its battles, tower floors and islands follow the same rules. In its battles enemies come in turns too, counted by the battles you have played in the run: one at a time in the first three, then two, up to four. Its five minutes and its credits are unchanged.

### New: in events

- **Smash and grab with an exit.** An event can have an exit that you hear from the start, but that stays locked, and quieter, until every glass case in the room is smashed. Walk out through it to the next room, with a new number of cases.
- **Chasers of their own.** The creatures a smashed case brings can have their own sound, such as a ghost, and their own cost when they reach you. One that reaches you then vanishes.
- **Rewards that vary.** A glass case or a treasure chest can give some rewards more often than others, such as shots from most cases and extra time from a few, and a different amount each time, such as 15 to 45 seconds.
- **Swimming.** An event can now be deep water that you swim through: every step is a swimming stroke, as quiet as shallow water. Sonar Dive, Whale Song and The Sonar Maze swim.
- Events that use any of these play in 4.0.0 and later. Older versions list them as playable on the website only.

### Changed: events

- **Pumpkin Hunt, Second Addition:** about half of the pumpkins are locked in glass cases and the rest lie on the floor; a smashed case brings three ghosts and holds shots for the laser, and a ghost's touch now costs ten seconds instead of ending the run.
- **Turkey Hunt and The Angry Papa** are corrected: their descriptions read properly, a turkey no longer adds time, and Papa's cookies appear nearer to you.
- **Dungeon Keys** plays the door unlocking when you take a key.
- **Call of Fate:** "Ring three times" and the like are now said just before the climb up to the next level ends, and the level begins right then, instead of as the climb begins.
- **Count the Chimes:** after a miscount, the next count waits until you have heard what the number was, so its chimes no longer ring over the voice.
- **Medals** are set afresh for The Expedition, Trapped in Darkness, Frozen Memories, Flooded Cellar, Wolf Woods and Lure, and The Expedition, Trapped in Darkness and Frozen Memories now give a bonus for finishing.
- **Christmas Presents** runs through New Year's Day.
- A Lure event never gives you the laser.
- An event that has one of the newer settings but does not use it is no longer kept from versions 3.0.0 and 3.0.1.

### New: running

- **Hold Up to run** the way you face, about 280 steps a minute, and **hold Down to walk back**, about 200 a minute, in Standard, Battle, Tower, Island, Find the Voice, Chaos and the events. In the events, where nothing turns, Up runs north and Down walks back south. Letting go stops you, and so does a wall, the edge of the room, a new level and pausing. A quick press is still one step. Driving is unchanged, and a Braille notetaker's held key still counts as one press.

### Changed: the climb up the stairs

- When you climb to the next floor, level, room or round, the next one now begins once the climb has finished, and half a second more, instead of on top of it. The background keeps playing, the clock waits, and you cannot move until it begins.
- In Chaos, the climb is now heard every time you take the stairs. Until now it was heard only when the stairs led to another tower floor.

### Fixed: sounds that would not sit in the middle

- Some event recordings drift from one side to the other by themselves, such as the fairy dust in Trapped in Darkness, so they could never be centred. Every looping sound you find by ear in an event, such as an item, a way out or a creature, is now played from one point, and only its place in the room says where it is.

### Fixed: lives missing from the report

- In an event whose creatures all come from smashed glass cases, such as The Jewel Heist, Enter did not say how many lives you had left, though a guard's touch still cost one. Enter now says your lives whenever a creature's touch can cost one, from the start of the run.

### Fixed: found in a full review of the game

- **Quitting a mode no longer closes the game.** Pressing Escape and then Y to leave Standard, Battle, Driving, Tower, Island or Chaos closed the game with an error if you had not played an event since starting it. This was also in 3.0.0 and 3.0.1.
- **The laser can always hit.** In an event that gives you the laser, every creature and every chaser can now be shot. Some could not, such as the ghosts of the first Pumpkin Hunt, Second Addition.
- **Smash and grab with items on the floor.** An event can now lock only some of its items in glass cases; the rest lie on the floor, and you take them by stepping onto them.
- **Events in stages.** A stage after the first now lays out its own items. When two stages each had a set number of items, the second could have none, and the run could not go on.
- **Dance steps.** Holding an arrow a moment too long no longer gives a second answer that costs a life.
- **Minefield and Mirror twin can always be finished.** The safe way through a minefield now ends just below the goal, so a step forward reaches it, and the twin in Mirror twin can now reach every calling spot.
- **The end of a run names what you brought down.** It counts each kind of creature under its own name and points, such as 6 ghosts, and names the creature that caught you.
- **The wait after a climb is quiet.** Nothing in the next room is heard, moves or can hurt you until it begins.
- **The clock is announced correctly** after a trap or a thrown stone takes seconds off it.
- **Enter says your lives** whenever you can lose one, a trap included, and your shots in the events where Space fires the laser. It says 1 second, not 1 seconds.
- **Nothing is walled in.** When a new level brings new walls, anything lying where a wall now stands is moved somewhere you can reach.
- **Chaos.** A tower floor's background keeps playing through the climb, as in Tower Mode.

### If you have 2.0.0 or newer

- Choose **Check for Updates** on the main menu.

## 3.0.1 (November 2026)

Fixes for the new kinds of event. Only events change: Standard, Battle, Tower, Island, Driving and Chaos are exactly as they were.

- **Less broken glass, and it stays.** A smashed glass case now leaves broken glass only on its own square and the eight around it, three steps across, and that glass stays where it fell on every level after. Before, it spread five steps across, so it was hard to get past without a creature hearing you.
- **Nothing out of reach behind a creature.** A creature that listens is never placed on an item or right beside one, and a new item is never placed beside one. Before, an item could lie where it could only be reached by walking into the creature.
- **Items you can tell apart.** In the new kinds of event, when an event gives its items several sounds, each item now takes a different one, so several items out at once can be told apart by ear.
- **An extra life calls with a bell.** The heartbeat it used was too low to be heard from far away.
- **A charge you can hear coming.** A creature that charges now makes footsteps as it runs, heard from where it is, on whatever floor it is crossing.
- **Creatures can grow level by level, up to a limit.** An event played in levels can now set the most creatures a level ever has, so it can begin with one and build up.

## 3.0.0 (November 2026)

The biggest update to events since they began. Only events change: Standard, Battle, Tower, Island, Driving and Chaos are exactly as they were in 2.0.0. Every event made before 3.0.0 plays as it always did.

### New: seven kinds of event

- **Memories.** Memories lie about each level, each with a few notes of music of its own. Find them all to reach the next level. Made for Trapped in Darkness.
- **Smash and Grab.** Every item is in a glass case: find it by its knocking and smash it with Space.
- **Silent Escape.** Reach the way out of each room without waking the creatures that listen.
- **Echo Hunt.** Hidden things call only now and then, each with a few notes of music.
- **Lure.** Pick up stones and throw them with Space to draw listening creatures away.
- **Rebuild the Song.** Find every piece of a tune, and the whole melody plays.
- **Storm Chase.** Reach each shelter before the thunder arrives.

### New: twenty-five more kinds of event

- **Red Light, Green Light.** Walk to the goal only while the music plays; a step in the silence costs a life.
- **Minefield.** Cross the field: after every step, one click for each mine beside you.
- **Stepping Stones.** Hear a path of notes across the water, then walk it from memory.
- **Bat and Ball.** Get into the line of a bouncing ball and hit it back.
- **Race a Rival.** A rival you can hear is after the same items as you.
- **Catch the Thief.** Catch the thief before it gets out with a treasure.
- **Boss.** One great creature that stalks, roars and charges; your shots hurt it only while it is tired.
- **Escort.** Lead a friend home and shoot the raiders that come for it.
- **Shooting Gallery.** Line up the targets and shoot them, but spare the friends.
- **Odd One Out.** Several things sound the same note; step onto the one that is a little off.
- **Cover the Ground.** Every square you step on for the first time scores.
- **Sonar Maze.** A maze of silent walls and a silent way out, heard only by pinging with Space.
- **Courier.** Hear what each customer wants, fetch it from the right shelf and bring it back.
- **Dance Steps.** Repeat the caller's row of steps with the arrow keys.
- **Tag.** Keep away from the one that is it; when you are it, tag one back.
- **Crossing the Road.** Cross lanes of traffic that you hear sweeping past.
- **Mirror Twin.** Steer a twin that steps the opposite way to you onto a calling spot.
- **March in Time.** Take one step on every drum beat while you collect things.
- **Count the Chimes.** Walk as many steps as the bell rang, then press Space.
- **Rising Tide.** Reach high ground before the water behind you reaches you.
- **Snake.** Every item makes your tail longer, and you must not step on it.
- **Push the Crate.** Push a humming crate onto the spot that calls for it.
- **Crack the Code.** Find the secret order of a ring of pads by trial and memory.
- **Turn the Tables.** Take the power item and the creatures run from you.
- **Treasure Map.** Follow spoken directions, counting your own steps, and dig with Space.

That makes 63 kinds of event in all, and any of them can be a stage of a longer event.

### New: what any event can now have

- **Glass display cases.** A case hums, knocks from within fifteen steps, and rings a bell when you are beside it; Space smashes it. Whatever was inside is yours at once, and the voice says only an extra reward. Broken glass is left on the floor.
- **Creatures that listen.** They wait, breathing, facing one way. A few steps in front of one wakes it; beside or behind it is safe. Loud sounds wake it from farther off. It growls, charges for a while, then stops where it is.
- **Runners, statues and throwers,** and up to three kinds of creature in one event.
- **Floors** you hear in your footsteps: stone, sand, snow, water, glass, ice and mud. Glass is loud, water is quiet, ice slides you a step, mud holds you a moment.
- **Walls.** An event room can be a labyrinth, new on every level. Creatures find their way round the walls.
- **Levels and endings.** Collecting events can be played in levels, always announced by number. A run can end after a set number of levels, or a number chosen afresh each run.
- **Stages.** One event can be up to five stages in a row, each a different mission, with one score.
- **A meter** that runs down and must be refilled, such as air or warmth.
- **Traps, safe spots, teleports and treasure chests.**
- **Supplies** in any event: ammo boxes, extra lives and bonus points.
- **Unlimited shots.** An event can give you a laser that never runs out. Enter then says "unlimited shots" in place of a number, no ammo boxes appear, and a reward that would have been shots is points instead.
- **Story lines:** an event can have the voice speak a line as a level begins, when so many items are found, or when a creature first wakes.
- **Music played by the game.** Twelve well-known tunes and six instruments, for the items of the musical events.

### New: events from newer versions

- The web version of the game keeps growing. If an event ever uses something this version does not have, it is still listed in the Events menu, with the words "on the website only", so you know it is on.

### Help

- The Events section of the help describes all of the above, every new kind of event included, with the knock of a glass case to listen to.

### If you have 2.0.0

- Choose **Check for Updates** on the main menu. Events that use the new features appear only in 3.0.0 and later.

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
