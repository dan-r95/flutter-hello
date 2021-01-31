# flutter-hello

A sample drawing app for testing pen-input with flutter.

![screenshot](https://raw.githubusercontent.com/inkandswitch/flutter-hello/master/screenshot.png)

## Installation

See the full instructions [here][flutter-install].

- Make sure Xcode is installed. Personally, I had to open it and accept some agreements.
- [Download the latest flutter beta][flutter-sdk]
- Unzip it to your home directory or someplace
- Add the bin folder to your path: `export PATH=<some-dir>/flutter/bin:$PATH`
- `brew install --HEAD libimobiledevice`
- `brew install ideviceinstaller ios-deploy cocoapods`
- `pod setup`

## Running the app (debug)

- `flutter run`

## Running the app (release)

- `flutter run --release`

## Running the app on macOS

- `open macos/MacRunner.xcodeproj`
- Click the play button

[flutter-sdk]: https://flutter.io/sdk-archive/#macos
[flutter-install]: https://flutter.io/setup-macos/




## web
sudo docker run -dit --name tecmint-web -p 8080:80 -v /home/rossy/flutter_hello/build/web/:/usr/local/apache2/htdocs/ httpd:2.4
