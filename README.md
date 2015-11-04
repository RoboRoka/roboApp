# roboApp

iOS app for controlling the RoboRoka device over bluetooth


## Basic Idea

The app uses BLE to connect to a (BLE enabled) RoboRoka device and it's commands to control the robot arm.

To control the arm, the app will use the following data:

* Accelerometer / gyroscope - movement of the device (tilt, pan, spin, ...) can be used for one or more axis of movement
* Swipe gestures
* Tap gesture - Open / Close the jaw


## Proposed UI

The app will display a blank screen (graphics may be added, but shouldn't alter the apps behaviour) and recognise 2 gestures, a tap and swipe over the screen. Swiping up/down moves the arm forward/back, swiping left/right rotates the arm left/right.

Tilting the device from/towards the user lifts the arm down/up.

A simple tap on the screen opens or closes the arms gripper.


## Possible changes

It might be better to allocate a portion of the screen for swiping up and down, which cause the arm to rise / drop.

This would mean the app would only have a touch interface (might be better for demo purposes)
