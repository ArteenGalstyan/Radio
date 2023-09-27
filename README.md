# Radio

> Note: this is a work in progress project that is a part of a larger project for building a fully operational cube satellite.

The radio is designed is to operate in the 432-438 MHz US amateur radio UHF band provided by the FCC. A valid FCC license is required to transmit on this bandwidth.

### Specifications

| Parameter         | Value     | Notes                            |
| ----------------- | --------- | -------------------------------- |
| Power Consumption | TX: 8.0 W | 5V @ 1.6A                        |
|                   | RX: 0.8 W | 5V @ 160mA                       |
| Frequency         | 435 MHz   | 405 - 455 MHz range of operation |
| RF Transmit Power | 1W +30dBm |                                  |
| Baud Rate         | 3.5 kbps  | Configurable                     |
| Range             | 1 km      |                                  |
| Flash memory      | 32kBytes  |                                  |

### Block Diagram

![Radio Block Diagram](Assets/PNG/Circuit%20Block%20Diagram%20-%20Radio.png)

### Circuit Diagram

![Radio Circuit Diagram](Assets/PNG/Radio-Schematic-13-02.png)

### TODO

- [x] Block Diagram
- [x] Circuit Schematic
- [ ] 4-layer pcb layout
- [ ] Firmware
- [ ] Testing
