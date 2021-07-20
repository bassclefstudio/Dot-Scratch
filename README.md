# Dot-Scratch
This is the Git repository for the Scratch project Dot: Return ([link](https://scratch.mit.edu/projects/412149960)), a simplistic vector-based platformer engine designed in Scratch. It is hosted on Git thanks to [RokCoder's sb3-commit project](https://github.com/rokcoder-scratch/sb3-commit), which converts the Scratch `.sb3` file to a text file that can be published to source control.

## Scratch Credits

 - Pen text engine for UI elements: "Pen Text Engine++" provided by [@-Rex-](https://scratch.mit.edu/users/-Rex-/)
 - Triangle filler (for UI elements) by [@TheLogFather](https://scratch.mit.edu/users/TheLogFather/)
 - All other coding and art by me, [@bassclefstudio](https://scratch.mit.edu/users/bassclefstudio/)

## Changelog

|Date|Version|Notes|
|---|---|---|
|20 Jul 2021    |`v0.14-beta`            |New physics engine supports better collision detection (using adjusted normal vector approach) and multiple simeltaneous physics objects! (to be used in a future update).|
|27 Feb 2021    |`v0.13-beta`            |Automation! This is a new feature that will allow for the manipulation (movement, destruction/creation, etc.) of parts of the game level.|
|13 Dec 2020    |`v0.12.1`               |Sound! Currently in beta, MIDI music plays during gameplay (not while paused or in the editor). Repeats on loop. `\[M\]` to mute. Silly sound effects are always on.|
|13 Dec 2020    |`v0.11`                 |Language support improved by allowing two classes of language support - native pen languages (translated naturally), and tooltip languages (a warning dialog displays on launch, and all text is accompanied by a dialog in the translated language).|
|13 Dec 2020    |`v0.10.1`               |Dialog bugs fixed (allows for stacked dialogs!) and dialog loading added for opening legacy .dot3 files.|
|12 Dec 2020    |`v0.10`                 |Updated JSON libraries (v5) with a new backwards-compatibility system, added loading dialogs for long-running operations, and fixed bug involving camera zoom glitches.|
|3 Dec 2020     |`v0.9`                  |Minor bug fixes, added full set of levels (for now) with main menu, improved and included text subsystem in release.|
|9 Nov 2020     |`v0.8.2`                |Minor bug fixes, and a slightly new level design (playing around with the possibilities for actual puzzle-based levels, rather than your traditional platformer levels). One or two more features to add, and then I think I'll be ready to put some serious work into level design!|
|1 Nov 2020     |`v0.8.1`                |Added additional reset code that prevents player from restarting level with incorrect settings if they died near an antigravity surface or portal.|
|12 Oct 2020    |`v0.8b`                 |Edits to the antigravity surface ("flip" in the code) mean that the gravity is only flipped when the player successfully *crosses* the surface, instead of the first moment that they touch it. Also some slight color changes.|
|30 Sep 2020    |`v0.7b`                 |This is a side-by-side revision of the project (alongside v0.6 changes) that discards the gravity wells and the myriad of problems they caused (for now) in favor of moving platforms, switches, and a revised level format (JSON format revision 4 supports opening files from previous versions pre v0.6).|
|30 Sep 2020    |`v0.6.3`                |Changes to the way gravity functions in-game.|
|20 Sep 2020    |`v0.6.2`                |German alphabet characters added to PTE.|
|20 Sep 2020    |`v0.6.1`                |Added beta version of locale understanding - translations simply provided by the Translate blocks and cached for performance. Unfortunately the PTE I'm using for text only really supports basic Latin characters.|
|19 Sep 2020    |`v0.6`                  |Added beta version of FPS counter and adjustments. The project can now fully support variable frame rate (up to 60fps in something like Turbowarp) and adjustable resolution and display scaling.|
|13 Sep 2020    |`v0.5.2`                |Fixed issue with text sizing and camera, added new sample level and font size option in editor.|
|7 Sep 2020     |`v0.5`                  |Line and point portals can interact with each other. Full editor support. New sample level demonstrates new features.|
|30 Aug 2020    |`v0.4`                  |Added point portals and custom endpoints. Editor fully supports all features.|
|14 Aug 2020    |`v0.3.1`                |Beta version of portals and gravity reversal (NOTE: no editor support).|
|14 Aug 2020    |`v0.3`                  |Supporting camera transitions and boundaries in levels and the editor. New levels in progress.|
|20 Jul 2020    |`v0.2`                  |Full drag and drop support, ordering segments in the editor, various bug fixes and improvements. Added touch inputs.|
|19 Jul 2020    |`v0.1.1`                |Some bug fixes, dragging of segments enabled, updated to v2 JSON schema. Updated legacy levels (but no new puzzles... yet!)|
|19 July 2020   |`v0.1`                  |Initial beta version, many features missing. Bugs are imminent.|
