# Purrse

A tracking app meant to help you "purrrsue ^..^" your financial goals!

> [!IMPORTANT]
> This is a new [**React Native**](https://reactnative.dev) project,
> bootstrapped using [`@react-native-community/cli`](https://github.com/react-native-community/cli).

## Getting Started

> [!IMPORTANT]
> Make sure you have completed the [Set Up Your Environment](https://reactnative.dev/docs/set-up-your-environment) guide before proceeding.

### Debug using Metro

```sh
npm start
npm run android
```

### Build a release APK

Make sure to create a `release.keystore` file within the root directory of the project:

```sh
keytool -genkeypair -v -keystore release.keystore -alias purrse-release-key -keyalg RSA -keysize 2048 -validity 10000
```

For Google Play releases, use this command:

```sh
npm run android-release-bundle
```
