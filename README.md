# ISS Overhead Notifier

## Description
ISS Overhead Notifier is a simple Python script that notifies you when the International Space Station (ISS) is passing overhead your location. It utilizes the Open Notify API to fetch the ISS's current position and the Geopy library to determine your location based on your IP address or provided coordinates. When the ISS is within a certain distance from your location and it is nighttime, the script sends an email to alert you of its presence.

## Requirements
- Python 3.x
- requests library
- smtplib library (built-in with Python)
- time library (built-in with Python)

## Setup
1. Update the following variables in the script with your information:
   - `MY_EMAIL`: Your email address.
   - `MY_PASSWORD`: Your email password or app password if you're using Gmail.
   - `MY_LAT`: Your latitude.
   - `MY_LONG`: Your longitude.
   - `__YOUR_SMTP_ADDRESS_HERE___`: Your SMTP server address for sending emails.

## Usage
1. Run the script using Python:
2. Keep the script running in the background. It will check every 60 seconds if the ISS is overhead and if it's nighttime at your location.

## Disclaimer
This script relies on third-party APIs and services for ISS position data, sunrise/sunset times, and email notification. Use it responsibly and at your own discretion.

## Credits
ISS Overhead Notifier was created by me. Special thanks to the creators of the Open Notify API and the Sunrise-Sunset API for providing the necessary data.
