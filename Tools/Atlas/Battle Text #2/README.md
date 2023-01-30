# Battle Text (#2)

*This is a translated or to-be-translated script and its associated files for Atlas.*


## Overview:

It contains the text you'll see during battles and in some training events.

See more: [Battle Text #1](../Battle%20Text%20%231)


## How to Use:

1. Place these files in the directory:
    - `Atlas.exe`
    - `db3_eng.nes` *(Dragon Ball 3 - Gokuuden file that ideally has an English character set represented in the tiles and the table)*
2. Run [`db3_eng_battle_2.bat`](./db3_eng_battle_2.bat)
3. Check the command prompt/terminal and ensure there were no failures.
    - Alternatively, check the `debug.log`
4. Use a hex editor that supports tables (FCEUX, WindHex, etc.) and ensure that the text didn't write past where it was supposed to.
   - For instance:
     - open the original Japanese game in WindHex with the jpn table
     - open the WIP English game in WindHex with the eng table
     - check what address the last string ends at in the Japanese game
     - ensure the last string in the English game ends at or before that address.
5. Play the game to the point where the text should show up and ensure that it does correctly.
