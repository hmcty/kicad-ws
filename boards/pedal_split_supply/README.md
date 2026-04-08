## Pedal Split Supply

A breadboard-compatible, split power supply for prototyping audio circuits.

Provides low-noise, stable +/- 7V rails. Requires 9V DC input. 

Parts:
- [TPS7A49](https://www.ti.com/product/TPS7A49)
  - LDO for +7V rail
  - Vin range: 2.5V to 20V
  - Maximum output current: 150mA
- [TPS7A30](https://www.ti.com/product/TPS7A30)
  - LDO for -7V rail
  - Vin range: -3V to -36V
  - Maximum output current: 200mA
- [LT1931](https://www.analog.com/media/en/technical-documentation/data-sheets/1931fa.pdf)
  - DC/DC converter for -9V rail
  - Vin range: 2.45V to 16V

### LT1931 Layout

Analog Devices recommends the following layout for the LT1931:
![LT1931 Layout](boards/pedal_split_supply/assets/lt1931-layout.png)

### Errata

v1.0.0
------

- Positive and negative rails are reversed

