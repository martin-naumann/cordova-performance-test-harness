cordova-performance-test-harness
================================

Basic app to demo Javascript load&amp;parse performance in Cordova.

## Setup

You need node.js and the Android SDK on your system to run the code.
Go to a terminal and run

    $ npm install
and then

    $ node_modules/cordova/bin/cordova build android
to create a new build.

To install on your Android device, run

    $ adb install platforms/android/bin/PerformanceHarness-debug.apk
