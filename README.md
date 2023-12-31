
# Synchronized Clock

Synchronized Clock is a simple Android app designed to provide precise time synchronization for your Android device. It retrieves the current time from either the device's system clock or a network time server using the NTP protocol.


## Features
- Displays the current time from either the system clock or an NTP server.
- Updates the time every second if the network is available.
- Uses Apache Commons Net to fetch time from an NTP server.
- Checks network connectivity to select the time source.

## Usage
- Install the app on your Android device.
- Launch the app.
- If the network is available, the app will retrieve the time from an NTP server (in this case, "time.google.com").
- If the network is unavailable, the app will use the device's system clock.
- The time updates every second if the network is available.

## Installation
- Clone or download this repository to your computer.
- Open the project in Android Studio or your preferred Android development IDE.
- Build and run the app on your Android device.

## Technologies
- Android Studio
- Apache Commons Net for NTP time retrieval.
