# ZMK config for beekeeb Toucan Keyboard

[The beekeeb Toucan Keyboard](https://beekeeb.com/toucan-keyboard/) is a wireless split 42-key column‑stagger keyboard that a display and a trackpad, with an aggressive stagger on the pinky columns.

# Keymap

Layer access:

- `NAV`: hold left thumb `&mo 1`
- `SYM`: hold right thumb `&mo 2`
- `ADJ`: hold both `NAV` and `SYM`

`BASE`

```text
+------+------+------+------+------+------+  +------+------+------+------+------+------+ 
| Tab  |  Q   |  W   |  E   |  R   |  T   |  |  Y   |  U   |  I   |  O   |  P   | Bspc |
| Esc  |Sft/A |Alt/S |Ctl/D |Gui/F |  G   |  |  H   |Gui/J |Ctl/K |Alt/L |Sft/; |  '   |
| Lsft |  Z   |  X   |  C   |  V   |  B   |  |  N   |  M   |  ,   |  .   |  /   | Esc  |
               | Gui  | NAV  |Space |  | Enter| SYM  | RAlt |
               +------+------+------+  +------+------+------+
```

`NAV`

```text
+------+------+------+------+------+------+  +------+------+------+------+------+------+ 
| Tab  |  1   |  2   |  3   |  4   |  5   |  |  6   |  7   |  8   |  9   |  0   | Bspc |
|      | BT0  | BT1  | BT2  | BT3  | BT4  |  | Left | Down |  Up  | Right|      |      |
| Lsft |Studio|      |      |      |      |  |      |      |      |      |      |      |
               | Gui  |      |Space |  | Enter|      | RAlt |
               +------+------+------+  +------+------+------+
```

`SYM`

```text
+------+------+------+------+------+------+  +------+------+------+------+------+------+ 
| Tab  |  !   |  @   |  #   |  $   |  %   |  |  ^   |  &   |  *   |  (   |  )   | Bspc |
| Lctl |      |      |      |      |      |  |  -   |  =   |  [   |  ]   |  \   |  `   |
| Lsft |      |      |      |      |      |  |  _   |  +   |  {   |  }   |  |   |  ~   |
               | Gui  |      |Space |  | Enter|      | RAlt |
               +------+------+------+  +------+------+------+
```

`ADJ`

```text
+------+------+------+------+------+------+  +------+------+------+------+------+------+ 
| Tab  |BT CLR|  F7  |  F8  |  F9  | F12  |  | Vol- | Mute | Vol+ |      |      | Bspc |
| Lctl |      |  F4  |  F5  |  F6  | F11  |  |      |      |      |      |      |      |
|BOOT L|      |  F1  |  F2  |  F3  | F10  |  |      |      |      |      |      |BOOT R|
               | Gui  | NAV  |Space |  | Enter| SYM  | RAlt |
               +------+------+------+  +------+------+------+
```

Notes:

- `BOOT L` is the left-half bootloader key.
- `BOOT R` is the right-half bootloader key.
- `BT CLR` is intentionally on `ADJ` only.
- `Studio` is `&studio_unlock`.

# License

The code in this repo is available under the MIT license.

The included shield nice_view_gem is modified from https://github.com/M165437/nice-view-gem licensed under the MIT License.

ZMK code snippets are taken from the ZMK documentation under the MIT license.

The embedded font QuinqueFive is designed by GGBotNet, licensed under under the SIL Open Font License, Version 1.1.
