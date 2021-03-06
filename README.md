# 🔐 Ti.Identity [![Build Status](https://travis-ci.org/appcelerator-modules/titanium-identity.svg?branch=master)](https://travis-ci.org/appcelerator-modules/titanium-identity)

> ⚠️ **Important**: This module is still under development and will be released with Titanium SDK 6.3.0 and
the release of the iPhone X. Feel free to try it out early, but please do not consider using it in production, yet!

# Summary
The Ti.Identity module allows you to use Fingerprint authentication, Keychain Access and Face authentication (iOS) with Axway Titanium.

## Requirements
- Titanium Mobile SDK 6.2.0 or later
- iOS 8.0 or later
- Xcode 8 or later

## Features
- [x] Use the Fingerprint sensor of your device to authenticate
- [x] Use the Face detection API's of your device to authenticate (iOS 11+)
- [x] Store, read, update and delete items with the native keychain

## Example
Please see the full-featured example in `ios/example/app.js` and `ios/example/app.js`.

## Build from Source
- iOS: `appc ti build -p ios --build-only` from the `ios` directory
- Android: `appc ti build -p android --build-only` from the `android` directory

> Note: Please do not use the (deprecated) `build.py` for iOS and `ant` for Android anymore.
> Those are unified in the above appc-cli these days.

## Author
Hans Knöchel, Axway

## License
Apache 2.0

## Contributing
Code contributions are greatly appreciated, please submit a new [pull request](https://github.com/appcelerator-modules/ti.identity/pull/new/master)!
