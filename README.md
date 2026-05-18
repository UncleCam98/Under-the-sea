# Under the Sea

## Overview

**Under the Sea** is an embedded intelligent systems project developed as part of the course **Design of Embedded and Intelligent Systems** at Halmstad University.

The project combines computer vision, path planning, robot communication, and embedded control in a shared multi-robot environment. The system uses an overhead camera to detect hand gestures and robot positions. These inputs are then used to control two robot platforms:

- A helium-balloon fish robot
- A ground-based crab robot

The detected hand gestures are interpreted as high-level commands:

- `PALM` means food or attraction
- `FIST` means threat or avoidance
- `NONE` means no active command

The crab robot uses grid-based navigation and A-star pathfinding, while the fish robot reacts through gesture-driven movement states.

## Modules
- [Hand recognition](hand-recognition/README.md)
- [A-star](a-star/README.md)
- [Fish robot](fish/README.md)
- [ROS2 communication](ros2-communication/README.md)


## Documentations
Gesture recognition model: 
https://ai.google.dev/edge/mediapipe/solutions/vision/gesture_recognizer/index#models

Gesture recognition code:
https://stackoverflow.com/questions/76320300/nameerror-name-mp-image-is-not-defined-with-mediapipe-gesture-recognition/76340423#76340423