NativeActivity Sample
=====================

This repository contains an example how to create NativeActivity-based app using Android NDK and Gradle Build System.

## How to use

Building native code:

`./build.sh`

Building APK:

`./gradlew build`

Installing APK on the connected device (also will perform build if needed):

`./gradlew installDebug` or `./gradlew installRelease`
