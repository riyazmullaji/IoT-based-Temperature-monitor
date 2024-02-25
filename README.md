# Bolt IoT Temperature Monitor with SMS Alerts (LM35 sensor, Twilio integration)

## Overview

This project uses a Bolt IoT Wi-Fi module and an LM35 sensor to monitor temperature and send SMS notifications via Twilio if it exceeds a certain threshold.

## Hardware Setup

* Bolt IoT Wi-Fi module
* LM35 temperature sensor
* Breadboard
* Jumper wires
* [Optional: Enclosure]

## Software Setup

1. Install required libraries:
   - `bolt`
   - `twilio`
2. Set up your Bolt account and API key.
3. Create a Twilio account and obtain your API credentials.

## Code Usage

1. Clone this repository.
2. Install dependencies (`pip install -r requirements.txt`).
3. Edit `config.py` with your Bolt and Twilio credentials.
4. Run `main.py`.
5. The script will monitor temperature and send SMS alerts if needed.

## Troubleshooting

* Check your internet connection and Bolt/Twilio API keys.
* Refer to the library documentation for error messages.

## Contributing

We welcome contributions! Please follow these guidelines:
1. Fork this repository.
2. Make changes in a separate branch.
3. Submit a pull request with clear descriptions.

## License

This project is licensed under the MIT License.

## Contact

riyazmullaji02@gmail.com
