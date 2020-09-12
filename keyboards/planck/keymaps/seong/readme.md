# A Custom Planck Layout

```
 ,-----------------------------------------------------------------------------------.
 | Tab  |   Q  |   W  |   E  |   R  |   T  |   Y  |   U  |   I  |   O  |   P  | Bksp |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 | Esc  |   A  |   S  |   D  |   F  |   G  |   H  |   J  |   K  |   L  |   ;  |   "  |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 | Shift|   Z  |   X  |   C  |   V  |   B  |   N  |   M  |   ,  |   .  |   /  |Enter |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 | Fn   | Ctrl |  GUI | Alt  | Lower|    Space    |Raise | Left | Down |  Up  |Right |
 `-----------------------------------------------------------------------------------'
```
## Compile
 - Execute `qmk compile -kb planck/rev6 -km seong`

## Flash
 - Put planck into RESET mode with `LOWER+RAISE+q`
 - Execute `qmk flash -kb planck/rev6 -km seong`
 - ~Execute `CFLAGS="-Wno-error=deprecated" make planck/rev6:seong:dfu-util` on the cmd line~
