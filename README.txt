====================================================================
PROJECT TITLE: BLACKOUT
DEVELOPER: Shlok Tiwari
COURSE: CS410G - Section 001
====================================================================

------------ OVERVIEW ------------
"Blackout" is a 2D stealth and puzzle-action game built in Unity. The core gameplay loop centers around "hacking" or cracking puzzles to disable security mechanics, and utilizing movement tools in order to infiltrate a corporation called ARGUS. ARGUS is a corrupted 
corporation that conducted experiments on innocent civilians with the intention to "Save the World." The main character's parents were a part of those tests, and ever since he lost them, he's been training to break in and steal ARGUS' data chip,
which holds records, video footage, patient reports, and test results of the whole thing. That is his main goal, to bring justice and take down any other corporations similar to ARGUS.

------------ CONTROLS ------------
Movement: W/Spacebar, A, S, D (or Arrow Keys)
Interact / Start Hacks: 'F' key
Execute Hack (Minigames): Left Mouse Button Click
Use Grapple: Right Mouse Button Click & Hold (3 Second Cooldown)
Skip/Speed Up Dialogue: Left Mouse Button Click
Pause / Exit Terminal: ESC
Hide from Red Scan (Body Scan): Hold 'CTRL' key
Hide from Purple Scan (Thermal Scan): Hold 'E' key

------------ PUZZLE SOLUTIONS ------------
Here are the direct solutions to the hacking minigames:

1. Elevator Hacks (Timing Puzzle):
   - Press 'F' to open the terminal.
   - A blue cursor will move back and forth rapidly across a bar.
   - Wait for the blue cursor to align completely inside the green target zone and Left-Click.
   - You must successfully hit the green zone multiple times in a row (speed increases with each hit). 
   - Missing a click resets the counter to 0. Complete the required hits to open the elevator.

2. Laser Hacks (Routing the Power Puzzle)
   - Press 'F' to open the terminal.
   - A 3x3 square of routing wires will open.
   - Connect the power from the START to END.
   - Routing wires are rotated randomly each time the puzzle is opened and progress is not saved.

3. Floor 3 Final Hack (Multi-Phase Puzzle):
   - Located at the main server on Floor 3. This is a 4-phase sequence.
   - Phase 1 (Elevator Hack): Complete the standard timing bar puzzle.
   - Phase 2 (Dot Puzzle): Click the dots in sequence before the timing rings run out.
   - Phase 3 (Elevator Hack): Complete the timing bar puzzle again (faster).
   - Phase 4 (Dot Puzzle): Complete the dot puzzle again (faster).
   - Note: Failing any phase resets the entire sequence back to Phase 1. Complete all 4 phases to unlock the data chip.

4. TIPs FOR COMPLETION
   - You can hold CTRL or E while in a Laser Hack to avoid scanners while still completing the puzzle.
   - You can click and hold Right-Click to hang in the air.
   - You can hold CTRL or E while falling and you will not be detected (Do not press A or D while falling otherwise you will be caught).


------------ CREDITS & ASSET ATTRIBUTION ------------
As per the academic honesty requirements, all art, music, and sound assets are explicitly identified below. 

I created ALL of the Music, SFX, Code, and Core Mechanics myself. All Music and SFX were created using FL Studio. Some Art Assets were obtained from the Unity Asset store, these assets are detailed below under the fair use policy for non-distributed educational work.

EXTERNAL ASSETS LIST:

1. ASSET TYPE: Background_Pack - 2D Pixel Art CYBERPUNK Backgrounds
   AUTHOR/CREATOR: Mokawyler
   SPECIFIC SOURCE/URL: https://assetstore.unity.com/packages/2d/textures-materials/building/2d-pixel-art-cyberpunk-backgrounds-248725

2. ASSET TYPE: Tile_Pack - Platformer Set
   AUTHOR/CREATOR: Szadi Art.
   SPECIFIC SOURCE/URL: https://assetstore.unity.com/packages/2d/environments/platformer-set-150023

3. ASSET TYPE: Tile_Pack - SciFi-CultistsPack
   AUTHOR/CREATOR: PixelConstructs
   SPECIFIC SOURCE/URL: https://assetstore.unity.com/packages/2d/environments/scifi-cultistspack-211371

4. ASSET TYPE: Sprite - Ninja Sprite Sheet (Free)
   AUTHOR/CREATOR: Kin Ng
   SPECIFIC SOURCE/URL: https://assetstore.unity.com/packages/2d/characters/ninja-sprite-sheet-free-93901

------------ HOW TO PLAY ------------
1. Extract the entire submitted .zip folder to a location on your Windows 10/11 PC.
2. Ensure all files (including Project_Data, MonoBleedingEdge, UnityCrashHandler64.exe, and UnityPlayer.dll) remain together in the exact same folder.
3. Double-click the main executable (.exe) file to launch the game.