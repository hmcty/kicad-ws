# Deloop Lite

System board for a simple, 2-track loop pedal.

Components:
- [Daisy Seed](https://electro-smith.com/products/daisy-seed)
  - Module carrying STM32H7 microcontroller, PCM3060 audio codec, and external
    SDRAM IC
- Barrel jack port assuming center-negative 9V DC power input
- +/-7V Power Supply
  - Imported design from a previous project, see [Pedal Split Supply](/#/project/pedal_split_supply)
- 2x 1/4" mono jacks (1 line-in, 1 line-out)
- 1x 3.5mm TRS MIDI input
- 2x audio input buffer (OPA2134)
- 2x audio output buffer (TL072)
- 1x output mix stage (TL072)
- 40-pin IDC header for UI and digital control connections
- 8x JST XH socket for auxiliary audio connections
- MicroSD card slot

The board is intended can be paired with different UI boards. Default signaling
assumes:
- 16x2 character LCD display
- Individually addressable RGB chain
- 3x footswitches
- 3x potentiometers (for track mixing)
- 1x rotary encoder (for menu navigation)
- 3x SPST switches

The board was designed to fit within a 1590DD enclosure.

