# OctoPix Expansion PCB for BTT Octopus Board

![Octo-Neo Front View](images/octopix_front.png)
![Octo-Neo Rear View](images/octopix_rear.png)

This PCB expansion board adds additional Neopixel outputs to your BTT Octopus board, allowing for custom RGB lighting configurations. It plugs into the Octopus's SPI3 header (J47) and provides four JST-XH 3-pin connectors to support up to four separate Neopixel connections.

## Features

- **4x JST-XH 3-pin connectors** for Neopixel data connections
- Compatible with the **BTT Octopus** control board for 3D printers
- Designed to plug directly into the **SPI3 (J47)** header on the Octopus
- Compact design fits neatly without obstructing other ports or components on the Octopus board
- **Buffered data signals** using a **CD4050B** (DIP 16 package) for reliable Neopixel communication

## Bill of Materials (BOM)

| Quantity | Part Description                                      | Example Sourcing Links                                                                                                          |
|----------|-------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| 4        | JST-XH 3-pin connectors                               |   [DigiKey](https://www.digikey.com/en/products/detail/jst-sales-america-inc/B3B-XH-A/1651046)                                                                                                                    |
| 1        | 2x5 header, 2.54mm pitch (Sullins SFH11-PBPC-D05-RA-BK) | [DigiKey SFH11-PBPC-D05-RA-BK](https://www.digikey.com/en/products/detail/sullins-connector-solutions/SFH11-PBPC-D05-RA-BK/1990095) |
| 1        | CD4050B (DIP 16 package)                              |   [DigiKey](https://www.digikey.com/en/products/detail/texas-instruments/CD4050BE/67303)                                                                                                                    |

## Installation

1. Align the Octo-Neo PCB with the **J47 SPI3 header** on the Octopus board.
2. Gently press the Octo-Neo PCB into the J47 header until fully seated.
3. Connect your Neopixel strips to the 3-pin JST-XH connectors on the Octo-Neo PCB.
4. Power on your Octopus board and configure your Neopixel effects using your preferred firmware (e.g., Klipper, Marlin).

**Octo-Neo PCB Installed on BTT Octopus Board** (front and rear views):
![Installed Front View](images/octopus_front.png)
![Installed Rear View](images/octopus_rear.png)

## Credits

This project was created by **knight_rad.iant** on Discord. Join the discussion and follow updates on the design.

---

Contributions, suggestions, and improvements are welcome. Please open an issue or submit a pull request if you have ideas to enhance this project.
