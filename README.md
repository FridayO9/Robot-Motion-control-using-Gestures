# Robot-Motion-control-using-Gestures
This project implements a gesture-controlled robot using Raspberry Pi as the microcontroller. The robot is capable of moving based on different hand gestures, which are recognized by a hand recognition model running on a computer. The recognized gestures are sent to the Raspberry Pi via TCP, where they are processed to control the robot's chassis. A queue system is also implemented to remember previous gestures, allowing the robot to repeat a sequence of gestures.

Gesture Detection: A camera connected to the computer captures hand movements. A hand gesture recognition model processes these gestures.
Sending Gestures via TCP: The recognized gestures are sent to the Raspberry Pi via TCP protocol.
Controlling the Robot: The Raspberry Pi receives the gestures and translates them into motion commands to control the robot's chassis.
Gesture Queue: The system stores recognized gestures in a queue, allowing the robot to replay the last set of gestures in sequence.

The respective codes are uploded 
