# lowenergybluetoothservicebroadcasting
# BLE Temperature and Humidity Broadcast

This project demonstrates how to broadcast temperature and humidity services using an ESP32 development board over Bluetooth Low Energy (BLE). The temperature and humidity values are simulated and can be read using the nRF-Connect app.

## Prerequisites

- ESP32 development board
- Arduino IDE with ESP32 core installed
- nRF-Connect app

## Installation

1. Install the `ESP32 BLE Arduino` library via the Arduino Library Manager.
2. Clone this repository or download the source code.
3. Open `src/main.cpp` in Arduino IDE.
4. Upload the code to your ESP32 board.

## Usage

1. Power on the ESP32 board.
2. Open the nRF-Connect app and scan for nearby Bluetooth devices.
3. Connect to the device named `ESP32_BLE`.
4. Browse the services and characteristics to view the temperature and humidity values.

## Code Overview

- **main.cpp**: Contains the code to broadcast temperature and humidity services.
- **Service UUID**: `00000002-0000-0000-FDFD-FDFDFDFDFDFD`
- **Characteristics**:
  - Temperature Measurement: `2A6E`
  - Humidity: `2A6F`

## License

This project is licensed under the MIT License.
