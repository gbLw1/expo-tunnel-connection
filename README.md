# React native app Expo tutorial

## Description

This is a test project to learn how to create, run and connect your React Native with Expo app on your phone to see the changes in real time.

## Creating the project

Make sure you're have the latest version of Expo CLI installed and you're logged in to Expo. If you're not, you can follow the instructions in the [expo documentation](https://docs.expo.dev/eas-update/getting-started/#login-to-your-expo-account).

```bash
npx create-expo-app@latest
```

## Running the project

To run the project, you can use the following command:

```bash
npx expo start
```

This will show a QR code in the terminal with some options to run the app. You can run the app on your phone by scanning the QR code or by running the app on an emulator.

### Trouble with LAN connection

If you're having trouble connecting to the app using the default start command, you can try to run in tunnel mode.

This tunnel mode requires the `@expo/ngrok` package to be installed. If you don't have it installed, you can install it by running:

```bash
sudo npm install -g @expo/ngrok
```

After installing the package, you can run the following command to start the app in tunnel mode:

```bash
npx expo start --tunnel
```

## Connecting to the app

After running the app, you can connect to it by scanning the QR code with the Expo Go app on your phone. You can download the Expo Go app from the [App Store](https://apps.apple.com/us/app/expo-go/id982107779) or [Google Play](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en&gl=US).
