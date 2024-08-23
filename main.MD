- `0x805B7F00`
  - Something to do with velocity

- `0x806ACC11`
  - Shadow offset

- `0x806AD752`
  - Smear effect if set to 2

- `0x806AD754`
  - Shadow scale and HUD scale

- `0x806AD731`
  - Messing with lights. You can see the square texture before the actual post-processing is done, similar to Luigi's Mansion

- `0x806AD734`
  - Slants camera

- `0x806AD732`
  - Shifts ground textures around

- `0x806AD738`
  - Turns Rosalina into a sleep paralysis demon

- `0x806AD750`
  - A weird smear. Not a true smear, and seems to swap some textures? I'm not sure

- `0x80B7DDC9`
  - Flat head when jumping

- `0x806AD766`
  - Weird Lakitu zoom-in effect when set to a value like 3, then game crashes

- `0x806AD768`
  - Weird Lakitu zoom-out, no crash

- `0x805B7F20`
  - Set to negative one to watch Mario peel off the screen

- `0x805B7F90`
  - Tip-Toe Animation Controller, high values = slower animation

- `0x805B7F98`
  - Mario Walk Animation Speed

- `0x810833D3`
  - Lives display

- `0x809EC044`
  - Possibly the cursor Y

- `0x806BCA44`
  - Something fishy

- `0x805B7F24`
  - Mario's walk animation controller 1?

- `0x805B7F28`
  - Mario's walk animation controller 2?

- `0x806AD734 -> 0x3e800000`
  - Flat Textures then game crash

- `0x80B7DDC4 -> 16`
  - Mario loses head when jumping

- `0x806AD654 -> Any #`
  - Sound Effect Multiplier (Default 1)

- `0x805B7F1C -> Any #`
  - Speed Multiplier (Default 1)

- `0x806BCA40`
  - Likely x or y velocity

- `0x806BCAFC`
  - Likely x or y velocity

- `0x810C04B4`
  - Camera Y, cannot change for some reason

- `0x810C053C WORD`
  - Life

- `0x806AD738`
  - Rosalina head modifier

- `0x80F63CF6`
  - Starbit count

- `0x8107FF0A`
  - Starbit display

- `0x806BD97C`
  - Locking this value causes weird stuff. A GPU desync happened, Mario fell through the floor, then the game crashed

- `0x805B7FEC`
  - Set it to 24, and crouch. Then crouch again for the Mario RPG animation. Mario's movement will be limited to 8 directions, similar to Mario RPG, and a loud noise will play

- `0x806AD730`
  - Overall gamescale, maybe quality? Messes nearly every game object and HUD/GUI. Negative values seem to make all objects disappear

- `0x806AD75C`
  - Toggles Mario's Shadow

- `0x806AD754`
  - HUD Scale, Negative values cause it to go backwards. Also affects pointer

- `0x806AD768`
  - Something to do with camera

- `0x806AD76C`
  - Messes with a lot of stuff. Values lower than 3 shrink Mario, put him in freefall right above the ground, and mess with the camera. Values higher than 3 also mess with the camera and likely crash the game. Also affects Mario's air acceleration

- `0x806AD774`
  - Changing this value at all removes Mario's head. No way to fix it

- `0x806AD7A8`
  - Squishes the screen upward, leaving a smear below

- `0x806AD870`
  - Entire Screen Scale, leaves smear (Like resizing a window)

- `0x806AD874`
  - Screen Position, leaves smear

- `0x810C01C8`
  - Mario's X Position

- `0x810C01CC`
  - Mario's Y Position

- `0x810C01D0`
  - Mario's Z Position

- `0x810780C4`
  - Some camera movement option. Tied to X Position somehow, either affects Camera Rotation or X Position

- `0x810C0420`
  - Mario's X Velocity

- `0x810C01F0`
  - Mario's Y Velocity

- 0x810C0428`
  - Mario's Z Velocity

- `0x810C01E0`
  - Mario's X Width.  Also slightly glitches out Mario's shadow.  Does not affect Mario's hitbox

- `0x810C01E4`
  - Mario's Y Height.  Interestingly, Mario will continue looking at entities if for height change.  For example, position Mario near a Luma.  He will look up at it.  Change Mario's height, and his view will adjust to keep looking at said Luma. Does not affect Mario's hitbox

- `0x810C01E8`
  - Mario's Z Width. Does not affect Mario's hitbox

- `0x0810C0530`
  - Mario's Gravity


813921DB  - Star chip controllers
8135CA9F - Star chip controllers
