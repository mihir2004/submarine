# Submarine Project

This project is part of the Tinkering Lab and involves building and programming a submarine using the ESP-32 microcontroller.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Submarine project aims to create a functional submarine prototype controlled by the ESP-32 microcontroller. The project includes hardware setup, firmware programming, and testing.

## Features

- Remote control of the submarine
- Sensors for depth and orientation
- Real-time data transmission

## Technologies Used

- ESP-32
- C/C++
- Arduino IDE
- Various sensors (pressure, gyroscope, etc.)

## Folder Structure

- **Tinkering/**: Contains all the project files and resources

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/mihir2004/submarine.git
    cd submarine
    ```

2. Set up the ESP-32 development environment:
    - Install the Arduino IDE
    - Add the ESP-32 board to the Arduino IDE (follow [this guide](https://github.com/espressif/arduino-esp32#installation-instructions))

3. Open the project in Arduino IDE:
    - Open `Tinkering/Tinkering.ino` in the Arduino IDE
    - Connect your ESP-32 to your computer

4. Install necessary libraries:
    - Install required libraries mentioned in the code (e.g., `WiFi.h`, `Wire.h`)

5. Upload the code to the ESP-32:
    - Select the correct board and port in the Arduino IDE
    - Click on the upload button

## Usage

1. Power on the ESP-32.
2. Use the remote control interface (defined in the code) to control the submarine.
3. Monitor sensor data through the serial monitor or any connected display.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
