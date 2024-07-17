# QR Code Scanner App

## Overview
The QR Code Scanner App is an Android application built with Jetpack Compose that allows users to scan QR codes using their device's camera. The app utilizes modern Android libraries and components to provide a seamless and user-friendly experience. If a QR code contains a URL, the app will automatically open the link in the default browser.

## Features
- Camera access to scan QR codes
- Real-time QR code scanning and decoding
- Automatic detection and opening of URLs in the browser
- Clean and modern user interface built with Jetpack Compose
- Requesting camera permissions dynamically

## Screenshots


## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/Ashking1956/QR-Code-Scanner.git
    ```
2. Open the project in Android Studio.
3. Build and run the app on an emulator or a physical device.

## Usage
1. Launch the app.
2. Grant camera permission when prompted.
3. Align the QR code within the camera frame.
4. If the QR code contains a URL, it will automatically open in the browser.

## Code Structure
- `MainActivity.kt`: The main activity that sets up the UI and handles camera permissions.
- `MainScreen.kt`: The composable functions that define the main screen and camera preview UI.
- `BarCodeAnalyser.kt`: The class responsible for analyzing camera frames and decoding QR codes.

## Main Dependencies
- [Jetpack Compose](https://developer.android.com/jetpack/compose) - For building the UI
- [CameraX](https://developer.android.com/training/camerax) - For camera functionality
- [Accompanist Permissions](https://github.com/google/accompanist) - For handling runtime permissions
- [ML Kit Barcode Scanning](https://developers.google.com/ml-kit/vision/barcode-scanning) - For barcode scanning and decoding

## Permissions
The app requires the following permissions:
- `CAMERA`: To access the device's camera for scanning QR codes

## Contribution
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
