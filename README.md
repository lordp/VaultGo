# VaultGo
Fields of Mistria save file utility, for Linux users.

```
A tool for unpacking Fields of Mistria `.sav` files. You can pack and unpack saves as needed.

Made by Darryl Hamilton, using the Go Language. No affilation with NPC Studio and no warranty is given,
use at your own risk!

Copy the `.sav` you wish to use from your Fields of Mistria save location to the current directory first.

Usage: ./vaultgo <COMMAND>

Commands:
  pack    <DIRECTORY> Packs a directory of JSON + Farm Buffer data into single .sav file
  unpack  <SAVE FILE> Unpacks a .sav file into a directory of JSON + Farm Buffer data
  help    Print this message or the help of the given subcommand(s)
```

## Save file location
The save files for me are located in the following directory - this may not be where they are for you though.

`~/.local/share/Steam/steamapps/compatdata/2142790/pfx/drive_c/users/steamuser/AppData/Local/FieldsOfMistria/saves/`

If this is not where they are for you, typing the following may help you find them.

`find ~ -name "game-*.sav"`

The `-autosave.sav` file is what the game saves to when changing from one day to the next.

Copy the save file you want to edit to the same directory as `vaultgo`. Once you have unpacked the file, changed what you wanted and packed it again, copy the save file back to the save file location above and run the game.

## Why?

I wrote this because I couldn't get the [vaultc](https://github.com/NPC-Studio/vaultc) app to work and thought using this as a way to extend my Go
knowledge would be fun (it was).

## Source code

I'm going to keep the source code to myself, for two reasons
 - the source code for the official vaultc app is not available
 - what I've written is probably horrific, and I don't want to cause harm to those that may read it

If anyone from NPC Studios wants to have a look, I will send you a copy.
