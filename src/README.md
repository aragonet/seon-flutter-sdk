# seon_plugin

[![pub package](https://img.shields.io/pub/v/seon_plugin.svg)](https://pub.dartlang.org/packages/seon_plugin)

[SEON Fraud Prevention](https://seon.io/) - Device Fingerprinting SDK for Flutter.

Learn about SEON Device Fingerprinting SDK at [SEON DOCS](https://docs.seon.io/getting-started/device-fingerprinting?_ga=2.234703388.388222201.1661599912-60975941.1661413923)

## Getting Started

First of all you need to add seon_plugin in your project. In order to do that, follow [this guide](https://pub.dev/packages/seon_plugin/install).

We suggest you to check [example](https://github.com/Shahin-Sefidgaran/seon-flutter-sdk/tree/main/src/example) source code.

## Use Flutter Plugin

```dart
    var fingerprintBase64 = await SeonPlugin().getFingerPrintBase64(
        sessionId: '<Your Session id>', // Any id for identifying your session with seon.
        isLoggingEnabled: true // True if you want the fingerprint response to be logged.
        );
```

## Version 2.0.0 Breaking Changes on Android

The newly computed device hash won't be compatible with previous versions.
