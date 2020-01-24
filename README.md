# Emacs Configuration

## Installation

### Windows
On Windows, simply put this `.emacs` file in your HOME directory specified by emacs. This is usually 
```sh
C:\Users\<username>\AppData
```

### Linux
Place the `.emacs` file in your HOME (`~/`) directory. That's it!

### Installing Dependencies
There will also be somethings that you need to do. They are:
```sh
<M+x> package-refresh-contents>
<M+x> package-install RET
gruvbox-theme
<M+x> package-install RET
auto-complete
<M+x> package-install RET
airline-themes
<M+x> package-install RET
powerline
<M+x> package-install RET
doom-themes
```

This completes it! Enjoy!

## Key Bindings

```
ALT-F               Load file in the current window.
ALT-SHIFT-F         Load file in the other window.

ALT-S               Save the file in the current window.

ALT-W               Switch to the other buffer.
ALT-M               Looks for and executes a build.bat.

ALT-C               Switches between H file and CPP file in the current window.
ALT-SHIFT-C         Switches between H file and CPP file in the other window.

ALT-K               Kills the buffer.
ALT-R               Revert the buffer.

ALT-U               Undo last change.

CTRL-SPACE          Sets mark.
CTRL-Q              Copies the block.
CTRL-W              Cuts the block.
CTRL-F              Pastes the block.

ALT-SHIFT-:         Jumps back to the old mark.

ALT-J               Jumps to function by name.

CTRL-S              Forward Search.
CTRL-R              Backward Search.

ALT-O               Query Replace then y or n.
ALT-L               Replace inside block only.

ALT-M               Build project.

ATL+[               Begin keyboard macro.
ALT+]               End keyboard macro.
ALT-'               Replat keyboard macro.
```
