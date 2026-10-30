# Mr. Duck Goes to College — public beta

**Play:** https://dustooned.github.io/MDGTCdev/

A browser demo for the development team, students, and other playtesters. No Godot installation or GitHub account is needed to play. A recent desktop browser with WebGL 2 is recommended. Keyboard and controller controls are supported.

Current release: **2026-10-30-web-32**, choice-time tags and immediate clock feedback. Validated time costs sit beside choices; committed actions roll the clock and briefly show their actual time cost. 2,824 assertions across 34 current game suites pass. An older standalone dialogue harness retains unchanged baseline failures and is excluded from that count.

Previous release: **2026-10-30-web-31**, the complete outdoor seed outing. Physical seeds/planter progress, short landmark direction questions, a post-conversation object reveal and quiet thoughts/notifications. 2,773 assertions across 33 suites pass, including the real on-foot outing and next-day return.

Previous release: **2026-10-30-web-30**, short intentions and contextual replies. Conversation choices use brief phrases and twelve semantic symbols; NPCs respond to the selected topic and actual favor progress. Shopkeepers finish speaking before the purchase screen opens. 2,715 assertions pass across 32 suites.

Previous release: **2026-10-30-web-29**, the comic UI pass. Pockets have stable item selection, a facing action panel and pinned Close; story lines wait for separate reveal/advance presses. Pause is a compact notebook, and shared vector frames/type/tokens form an editable artist kit. 2,642 automated assertions pass across 31 suites. Human controller, listening, pacing and final art review remain open.

Previous release: **2026-10-29-web-28**, Fall days and scheduled nights. Duck now gets tired, chooses actual sleep hours, and can borrow energy with a later crash. NPCs keep different work/home/sleep hours, and Bea and Tavi meet at the terrace on Friday nights. The neighborhood has new home and service-room blockouts, seasonal foliage and hillside rivals. Dialogue keeps its camera through choices and replies; inner thoughts have their own brief bubbles and deep sounds. The flip phone has an inbox and individual messages. **2,585 automated checks pass across 30 suites**; final sleep face art and human balance/controller/tablet review are still pending.

Previous release: **2026-10-28-web-27**, Illustrated Ink throughout the game and restored browser sound.

Previous release: **2026-10-28-web-25**, "City Day" with Mom's voice, a phone and calmer sound. Cutscene lines now babble as they type, and Mom nags down an old phone line: high and quick, every other line climbing, through a narrow, crackly filter. After her call Mr. Duck can't leave his room until he picks up his phone (placeholder: **M** or the **PHONE** button opens her angry texts). His inner thoughts replace the old parenthetical asides in dialogue and soften as he's looked after. Room 2 has its own song, doors switch the music at once without the old song swelling back in the hall, and the trash's burning flower goes dark the moment the roommate hauls it away. Existing saves keep their progress; choose “Start a new test day” to see the opening.

Previous release: **2026-10-26-web-24**, "City Day" for iPads with a keyboard or controller, with smoother music. The page keeps keyboard focus on the game after taps and app switches (iPad Safari dropped it), and the pause menu has a “Check keyboard / controller” screen listing connected controllers and every key or button the game receives. On the web the game renders at CSS resolution with smaller shadow maps to save memory, and after an unexpected reload the page offers crash details for a bug report. Music crossfades between areas at a steady level; cutscenes and doors lower it instead of cutting it; the pause menu fades it out; rooms keep the music of the street outside; dungeons sit it low under the drone. Everything from web-23 is included.

Previous release: **2026-10-25-web-23**, "City Day" with gentler halftone. Floors and the ground keep a finer, lighter dot screen over a soft shadow; walls and the sides of things are nearly plain shadow; and lights too dim to notice (the sun inside the dungeons, low lamps) no longer paint dots, so the Forge floor is smooth in firelight. Overall brightness is unchanged. Everything from web-22 (the new opening, Room 2, Mr. Duck’s thoughts) is included; choose “Start a new test day” to see the opening with an existing save.

Previous release: **2026-10-25-web-22**, "City Day" with a new opening. A new game starts in Mr. Duck’s bare room (a mattress on the floor) with a cold phone call from his mother, told in dramatic speech bubbles: her voice comes through a little phone screen in retro text. Mr. Duck never speaks; his placeholder inner thoughts appear in a dark thought cloud. Trash with an ever-burning flower blocks the stairs and the board stays locked until the roommate’s gift: in Room 2, the kettle’s last drops wake the plants and vines, the last one goes on the roommate’s burning hair, and they hand over the board and haul the trash away. His room can be revisited, with hints that decorating comes later. The travel HUD drops the mission panel and keeps the illustrated clock. Existing saves skip the opening and keep their board; choose “Start a new test day” to see it.

Previous release: **2026-10-25-web-21**, "City Day" with ancient dungeons. The Forge and Room 2 are staged as old places now: the first visit opens beneath a watching stone face with the room’s title card and a low boom, the halls are dark and foggy with flickering braziers and stone columns, and when a sealed gate opens the camera cuts to it as the stone sinks into the floor with a rumble and a chime. The text has a mythic voice (the Registrar, the Trial of Prediction, the Overgrown Mind). Progress in both rooms still lasts for the visit only. Builds from web-06 to web-20 keep their saves.

Previous release: **2026-10-25-web-20**, "City Day" in halftone. Cast shadows across the whole city, campus, courtyard and every room are now drawn as a comic-book dot screen. Dot size follows distance: bold dots near Mr. Duck, finer dots far away, so distant shadows do not turn chunky. Characters, glass and glowing screens keep their own look, street lamps stay smooth, and only the room you are in casts lamp shadows. Overall brightness matches the previous build. Builds from web-06 to web-19 keep their saves.

Previous release: **2026-10-25-web-19**, "City Day" with the first two dungeon slices. The Forge on campus opens on ENGR 101, Controlled Motion: register at the desk, pass the initiation by predicting where a cart stops, then ride the stopping bay and brake at the right mark to stop inside the gold bay; a board on the wall says how each run went. Room 2 in the apartment hall is the roommate's garden: listen to the flowers, plant and mist three seeds, the overgrowth gives way, and the AC button cools the room and puts out the roommate's hair. Progress in both rooms lasts for the visit and is not saved yet. The Pixel Parlor also gets halftone shadows: its lamp casts real shadows and the floor draws them as a dot screen. Builds from web-06 to web-18 keep their saves.

Previous release: **2026-10-25-web-18**, "City Day" with a smoother first look. Walking into the Pixel Parlor now eases the letterbox in and out instead of snapping, and the shot dollies the camera in a little before returning it exactly where it was. Builds from web-06 to web-17 keep their saves. A halftone shadow shader is now in the project — cast shadow as a rotated dot screen — but nothing uses it yet.

Previous release: **2026-10-25-web-17**, "City Day" with the downtown skateshop. GOOFY FOOT SKATES opens on the west block with its own sign, awning and door, six decks on the wall, and a placard that says it is hiring for a summer job that is not in yet. The shops now have street windows with a painted hint of what is inside, and the five businesses hiring for the summer tape a HELP WANTED card to the glass — art only. Saves from web-06 to web-16 carry over unchanged.

Previous release: **2026-10-25-web-16**, "City Day" with a cinematic first look. Walking into the Pixel Parlor now plays a short framed shot: letterbox bars close, the view holds for a fixed length, then the bars clear and control returns where it left off. The shot owns its length, so nothing can leave you stuck watching it. Saves from web-06 to web-15 carry over unchanged. Known: the downtown skateshop, shop windows and HELP WANTED signs are in progress and not finished in this build.

Previous release: **2026-10-25-web-15**, "City Day" with skating poses. Mr. Duck rides goofy (right foot forward) and stands on the grip tape instead of through the deck. Pushing has a placeholder kick and new foot-scuff sounds. His eyes change with the move: effort when pushing or grinding, surprise when falling or bailing, delight on flips and grabs. Walking arms swing in time with the footsteps, and after talking to someone he is back on his board if he was riding. Saves from web-06 to web-14 carry over unchanged.

Previous release: **2026-10-25-web-14**, "City Day" with bigger eyes. The eye plate is 1.35 times larger again, so the hand-drawn eyes fill more of his face, and the plate no longer casts a faint shadow on his head. His open eyes, and the blink frames with them, sit lower to match his other expressions. Saves from web-06 to web-13 carry over unchanged.

Previous release: **2026-10-25-web-13**, "City Day" with Mr. Duck's new eyes. The eyes are redrawn by hand, bigger and closer together, on a larger eye plate the game builds from the model's own, so they keep their drawn shape instead of stretching sideways. He blinks with the new open, half and closed frames; happy, sad, angry, surprise and dizzy are drawn for later. Saves from web-06 to web-12 carry over unchanged.

Previous release: **2026-10-24-web-12**, "City Day" with the quest and card cleanup. Eli reacts after the greeting lesson instead of repeating it, Nora thanks you once, and the seed handoff opens your pockets on the seeds with Give ready. Cost cards name the action and answer Yes · N min / Not now. Exits name where you are. Refusals are warned in the prompt and shown on a fading paper note. Cards fit their content, and nearby captions no longer overlap. Saves from web-06 to web-11 carry over unchanged.

Previous release: **2026-10-24-web-11**, "City Day" with the Pixel Parlor. The downtown arcade gets a tenth placeholder interior behind a gold door on the west block: six dark cabinets with lit screens, a token counter and a placard. Nothing is playable yet. Saves from web-06 to web-10 carry over unchanged.

Previous release: **2026-10-24-web-10**, "City Day" with placeholder interiors. Nine doors marked with a gold mat now open into simple lit rooms: Administration, Records / Enrollment and Student Accounts on campus; Corner Market, Fix and Mix, Second Spin and the Community Room downtown; and two courtyard houses. Press E to go in; press E on the exit mat or walk out the doorway to leave. The rooms are placeholders with a readable placard and nobody inside. The learning-court temples have no interiors yet. Being inside is never saved, so saves from web-06 to web-09 carry over unchanged.

Previous release: **2026-10-24-web-09**, "City Day" with the airflow exercise. Take a fan from the campus equipment desk and learn to aim it at the airflow bench (its connector is marked 90°). Then use the same rule on the Common Ground vent (180°): run it on low for no stamina, or boost for less time. You can also ask the neighbors to help, which fixes the vent without the lesson. Nora thanks you once for what you actually did. Saves from web-06 to web-08 carry over.

Previous release: **2026-10-24-web-08**, "City Day" with Nora's favor desk. Nora takes seed-favor visits from 9:00 to 18:00. When she is closed, her speech bubble and the objective say when to come back. Nothing expires: a carried packet or a waiting report keeps for another day. Once you have helped, later visits open with Nora remembering it. Saves from web-06 and web-07 carry over unchanged.

Previous release: **2026-10-24-web-07**, "City Day" with a minimal travel HUD. A Breath of the Wild–style stamina wheel appears beside Mr. Duck only while stamina is spent or refilling, drains by percentage, and shows fitness as gold pips. The clock and objective stay on screen, prompts appear only when there is something to do, and the commute debug readouts and debug pause entries are behind F3 or a pause toggle.

Previous release: **2026-10-24-web-06**, "City Day". The full commute city (apartments, downtown, greenway, campus, bus, skating, residents) now hosts the neighbor favor. People talk in speech bubbles with thought-cloud choices; costs, pockets and menus use paper cards; the original commute HUD is restyled to match. Sidewalk residents complain about city conditions before their tips, and Rosa, at the downtown bus stop, speaks Spanish. What Mr. Duck understands depends on the greeting he learns from Eli.

Previous release: **2026-10-24-web-05**, based on the neighbor preview **2026-10-24-neighbor-01**. Mr. Duck now uses a rigged, animated 3D model (idle, walk and crouch clips with swappable eye and mouth art); skating, jumps and tricks keep their simple placeholder poses. The opening card has a new title treatment (type only; title artwork comes later). Includes the optional "A small favor" errand with Nora and Eli, pockets, the day clock and stamina.

Previous release: **2026-10-21-web-04**, based on native playtest **2026-10-21-skate-polish-06**. Skating now keeps steering consistent after tricks, turns through arcs, and uses a small ground pivot in place of backward stance. Wall jumps and double jumps have original board-crack and rising chip sounds. Includes the stronger NPC clay treatment, adjustable clay strength, controller menu fixes, zone music, and sound effects. Browser audio pause/resume is now sent only when its state changes; steady playback no longer restarts and copies the music buffer every frame.

## Playtest controls

| Action | Keyboard | Controller |
| --- | --- | --- |
| Move | WASD / arrows | Left stick |
| Look | Right mouse drag / IJKL | Right stick |
| Jump | Space | A |
| Ask / inspect | E | X |
| Equip board | Q / Alt | View / Select |
| Board push | B | B |
| Pause / settings | Escape / P | Start |
| Menu select / toggle | Enter / Space | A |
| Menu back | Escape | B |
| Slider adjustment | Left / right | D-pad / left stick |

Click the game once to focus it and enable browser audio. For a controller, press a button after connecting it. Browser saves stay in that browser and can be lost when site data is cleared or private browsing ends.

## Feedback

Open a [playtest issue](https://github.com/dustooned/MDGTCdev/issues/new?template=bug-report.yml) or share the downloadable feedback template with your instructor/team. Include the demo version, browser/device, controls, and steps to reproduce the problem.

## Repository and updates

This repository contains exported browser builds and their public playtest page. Editable Godot/Blender projects, original recording masters, research files, internal documents, and credentials are kept separately.

GitHub Actions publishes `site/` through GitHub Pages when `main` changes. Each game export has its own directory under `site/builds/` so an older browser session can keep loading matching assets. New releases should use a new directory, then update the play button and release information on the landing page. Keep file names generated by Godot together and unchanged.

The single-threaded Godot web export works without special cross-origin-isolation headers. Godot and its third-party notices are available under `site/legal/` and linked from the demo page. Build information and file hashes are recorded in `site/build-info.json`.
