# PLLHO — PLL Harmonic Oscillator

A Eurorack VCO module with 8 harmonic ramp outputs  

- Range (fundamental): 0.1Hz to 10kHz  
- Supply current:
  - +12V: 100mA max
  - -12V: 68mA max
- Features: Expo and linear frequency modulation, harmonic phase offset and modulation, sync

Part of the [GHOQ](../) module collection.

## Contents

- `doc/` — theory of operation and build/calibration documents (PDF)
- `schematics/` — schematic PDFs and PNG images, per board
- `gerbers/` — manufacturing gerber files (zipped), per board + panel
- `module_build/` — full module BOM and module build photos
- `board_A_build/` … `board_E_build/` — per-board BOMs, board photos and KiCad PCB captures with annotations
- `panel_build/` — front panel KiCad viewer exports
- `samples/` — audio samples (MP3)

## Boards

| Board | Function |
|---|---|
| A | I/O, control, exponential converter |
| B | H5/H7 harmonic PLL cores |
| C | H6/H8 harmonic PLL cores |
| D | Fundamental oscillator, H2–H4 slave cores, power regulation |
| E | Bus connecting boards A–D |
| Panel | Front panel |

## Credits

Many ModWigglers participated in the GHOQ thread and contributed to PLLHO design and development. I'll single out @guest whose ideas, solutions and advice were crucial in forming the SRPLL circuit topology and many other aspects of the PLLHO implementation.

## License

CC BY-NC-SA 4.0 — non-commercial use only. See [LICENSE](LICENSE).
