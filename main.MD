0x805B7F00 - Something to do with velocity
0x806ACC11 - Shadow offset
0x806AD752 - Smear effect if set to 2 
0x806AD754 - Shadow scale and HUD scale
0x806AD731 - Messing with lights.  You can see the square texture before the actual post-processing is done or something.  Similar to Luigi's mansion
0x806AD734 - Slants camera
0x806AD732 - Shifts ground textures around
0x806AD738 - Turns Rosalina into a sleep paralysis demon
0x806AD750 - A wierd smear.  Not a true smear, and seems to swap some textures? I'm not sure
0x80B7DDC9 - Flat head when jumping
0x806AD766 - Wierd Lakitu zoom in effect when setting to a value like 3, then game crash
0x806AD768 - Wierd Lakitu zoom out, no crash
0x805B7F20 - Set to negative one to watch Mario peel off the screen
0x805B7F90 - Tip-Toe Animation Controller, high values = slower animation
0x805B7F98 - Mario Walk Animation Speed
810833D3 - Lives ?Display
809EC044 - Possibably the cursor Y
806BCA44 - Smth fishy

805B7F24 - Mario's walk animation controller 1?
805B7F28 - Mario's walk animation controller 2?

806AD734 -> 0x3e800000   - Flat Textures then game crash
80B7DDC4 -> 16   - Mario loses head when jumping
806AD654 -> Any #   - Sound Effect Multiplier (Default 1)
805B7F1C -> Any #   - Speed Multiplier (Default 1)

806BCA40 - Likely x or y velocity
806BCAFC - Likely x or y velocity
810C04B4 - Camera Y, cannot change for some reason
810C053C   WORD  - Life
806AD738 - Rosalina head modifer
80F63CF6 - Starbit count
8107FF0A - Starbit display
806BD97C - Locking this value causes wierd stuff.  A GPU desync happened to me, then mario fell through the floor, then the game crashed
805B7FEC - Ok, this one is good.  Set it to 24, and crouch, then crouch again for the Mario RPG animation. Mario's movement will be limited to 8 directions, similar to Mario RPG, and a loud noise will play
806AD730 - Overall gamescale, maybe quality? Messes nearly every game object and HUD/GUI.  Negative values seem to make all objects disappear
806AD75C - Toggles Mario's Shadow
806AD754 - HUD Scale, Negative values cause it to go backwards.  Also affects pointer
806AD768 - Something to do with camera.
806AD76C - Messes with a lot of stuff.  Values lower than 3 shrink mario, put him in freefall right above the ground, and mess with the camera.  Values higher than 3 also mess with the camera, take it easy because it scales very quickly and likely crashes the game.  Also seems to affect Mario's Air Acceleration.
806AD774 - Changing this value at all removes Mario's head.  No way to fix it.
806AD7A8 - Squishes the screen upward, leaving a smear below
806AD870 - Entire Screen Scale, leaves smear (Like resizing a window kinda)
806AD874 - Screen Position, leaves smear
810C01C8 - MARIO'S X POSITION!!!!!!!!
810C01CC - MARIO'S Y POSITION!!!!!!!!
810C01D0 - MARIO'S Z POSITION!!!!!!!!
810780C4 - Some camera movement option.  Tied to X Position somehow, either effects Camera Rotation or X Position
