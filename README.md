<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/tools/pub/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/to/develop-packages).
-->
A Flutter package that allows you to stream live camera feeds from compatible devices, with easy-to-use controls for starting, stopping, and refreshing the feed. Designed to be intuitive, flexible, and suitable for a wide variety of applications, including remote monitoring, security, and creative photo/video apps

## Features

1.TO Start live view feed with customizable size and display options.
2.Stream live camera data directly into your Flutter apps.
3.Stop and refresh the live view seamlessly.
4.A widget to render live view feed in real-time.
5.Optimized for low latency with configurable frame rate limits.

## Getting started

Installation

Add the package to your pubspec.yaml:

dependencies:
  camera_live_view: latest

Run the following command:
flutter pub get

## Usage

 final CameraController controller = CameraController();
 
 LiveViewWidget(controller: controller)

 controller.startLiveView(
           liveViewSize: "medium", // Configurable parameter
          cameraDisplay: "on",    // Configurable parameter
                );

## Additional information

📝 Documentation
For more detailed usage instructions and API reference, visit the https://github.com/gautamshaileshk/camera_live_view
