# Scorpion2022-RPU

Dick Hamill's [Scorpion2022](https://github.com/RetroPinUpgrade/Scorpion2022) for Williams' Scorpion (1980), using
RPU (Retro Pin Upgrade), with PinNode added: scores, achievements and settings reported to the PinNode network card.
The game is Dick's; every line PinNode added is marked `// PinNode`.

GPL-3.0, as the original is.

## Build

Install the **PinNode** Arduino library (0.3.21 or later). Then build this folder for the Arduino Mega 2560:

```
arduino-cli compile -b arduino:avr:mega Scorpion2022-RPU
```

Each release has the `.hex` and the `pinnode.game.json` it was built with.
