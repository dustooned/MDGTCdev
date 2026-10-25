# Mr. Duck Goes to College — public beta

**Play:** https://dustooned.github.io/MDGTCdev/

A browser demo for the development team, students, and other playtesters. No Godot installation or GitHub account is needed to play. A recent desktop browser with WebGL 2 is recommended. Keyboard and controller controls are supported.

Current release: **2026-10-25-web-14**, "City Day" with bigger eyes. The eye plate is 1.35 times larger again, so the hand-drawn eyes fill more of his face, and the plate no longer casts a faint shadow on his head. His open eyes, and the blink frames with them, sit lower to match his other expressions. Saves from web-06 to web-13 carry over unchanged.

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
