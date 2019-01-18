# ros_tts
Sophia Text-to-Speech+Animation ROS Node

This ROS node provides lip-synced, gesture-appropriate animation for 
text-to-speech for the Sophia robot, including blinking gestures and 
an appropriately-timed viseme stream to match.

## Dependencies
To use this, you need:
* [ttsserver](https://github.com/hansonrobotics/ttsserver), a multi-TTS
  audio server
* [blender_api_msgs](https://github.com/hansonrobotics/bender_api_msgs),
  the ROS message set for controlling the robot Blender animation.
* [blender_api](https://github.com/hansonrobotics/bender_api), the
  actual robot rig blender animation.
  
## Status
As of 2019, this code is in active use.

#### Copyright (c) 2017-2019 Hanson Robotics, Ltd.
