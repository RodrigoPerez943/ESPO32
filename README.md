# ESPO32 OLED

This repository contains the code for controlling two OLED displays and a rotary encoder using an ESP32. The project utilizes various libraries to interface with the hardware and includes functionality for WiFi connectivity, NTP time synchronization, and integration with the Spotify API.

[![Ver Video](https://i.ibb.co/rfSJVcV/github-ESPO32.png)](https://drive.google.com/file/d/1mFgUo-aFKgUav3_NED-ebNgKQcrPmU-6/view?usp=sharing)

## Features

- **OLED Display Control:** Uses the Adafruit SSD1306 library to control two 128x64 OLED displays.
- **Rotary Encoder Control:** Uses the AiEsp32RotaryEncoder library to handle input from a rotary encoder.
- **WiFi Connectivity:** Connects to WiFi using the WiFi library.
- **NTP Time Synchronization:** Syncs time using the NTPClient library.
- **HTTP Client:** Fetches data from web services using the HTTPClient library.
- **Spotify Integration:** Integrates with the Spotify API using the SpotifyArduino library.

## Hardware Requirements

- ESP32 Development Board
- Two OLED Displays (128x64)
- Rotary Encoder
- Connecting wires

## Software Requirements

- Arduino IDE
- ESP32 Board Manager
- Libraries:
  - Wire
  - Adafruit GFX
  - Adafruit SSD1306
  - WiFi
  - NTPClient
  - WiFiUdp
  - HTTPClient
  - ArduinoJson
  - StateMachine
  - SpotifyArduinoCert
  - SpotifyArduino
  - WiFiClientSecure
  - AiEsp32RotaryEncoder

## Usage

- Once the code is uploaded, the ESP32 will connect to the specified WiFi network.
- The OLED displays will show the current status and time synchronized via NTP.
- Use the rotary encoder to interact with the displays and control the connected components.

## Contributing

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

