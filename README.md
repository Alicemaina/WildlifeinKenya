# earthquake-tracker
![Earthquake Tracker]()
# [Earthquake Tracker![Build Status](https://github.com/Alicemaina/earthquake-tracker.git?branch=master)](https://github.com/Alicemaina/earthquake-tracker.git)
This App mark areas that are aftered by eathquake to help the construction develop manager the risk as they develop and also of the poeple living in the eare affected.
## Getting Started

These instructions will get you a copy of the project up and running on your local machine ready for development. If you want to help developing the app take a look to the contributing section, at the end.

### Development environment setup

We use [Android Studio](https://developer.android.com/studio/index.html) (the official Android IDE) for development, so we recommend it as the IDE to use in your development environment. Once you install Android Studio, you can use the Android SDK Manager to obtain the SDK tools, platforms, and other components you will need to start developing. The most important are:

 * Android SDK Tools and Android SDK Platform-tools (upgrade to their last versions is usually a good idea).
 * Android SDK Build-Tools 24.0.1.
 * Android 7.0 (API Level 24) SDK Platform.
 * Android Support Repository

You can also install other packages like emulators for running the app, if you don't have or don't want to use a real device. The minimum supported Android version is *4.0.1, Ice Cream Sandwich (API level 14).*

### Building and installing the app

First of all you need to get the source code, so clone this repository  on your local machine. If you want to contribute it is better to **fork the repository** by clicking on the *Fork* option on the top right corner and
 [keep it synced](https://help.github.com/articles/syncing-a-fork) by adding the original repository as a remote.

```
git clonehttps://github.com/Alicemaina/earthquake-tracker.git
git remote add upstream https://github.com/Alicemaina/earthquake-tracker.git
```

Android Studio uses Gradle as the foundation of the build system, but It is not necessary that you install it in your pc. You can use the [Gradle Wrapper](https://docs.gradle.org/current/userguide/gradle_wrapper.html) included in the project, as recommended by Google. Building the app with
Gradle is very easy: in a terminal, go to the directory that contains the repository, and run the `clean` and `build` tasks using the gradle wrapper (you may need to run `chmod +x gradlew` before):
```
./gradlew clean build
```

Then, for running the app on a device or emulator:
```
adb [-d] install path/to/calendula.apk
```
*The -d flag specifies that you want to use the attached device (in case you also have an emulator running.*

This tasks can also be done from Android Studio with a few clicks.

## App versions
earthquake-tracker 
*minSdkVersion 19
*targetSdkVersion 25
*versionCode 1
*versionName "1.0"

 


## Contributing ##
Feel free to fork and send a pull request if you want to contribute to this project! Notice that Wildlife in Kenya is licensed under the terms of the [MIT license](LICENSE.md), so by submitting content to the Wildlife in K repository, you release your work to the public domain.

Before starting, take a look at our [contribution guidelines](CONTRIBUTING.md). 

### I would like to contribute, but I'm not a developer...
If you're not a developer but you want to help, don't worry! You can help [with app translations](CONTRIBUTING.md#help-with-app-translations), by [joining the BETA group](#app-versions), and [much more](CONTRIBUTING.md#i-would-like-to-contribute-but-im-not-a-developer)!. Everyone is welcome!

## License

MIT License

Copyright (c) 2017 Alicemaina

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
