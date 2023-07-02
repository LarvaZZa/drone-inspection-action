# Live Mission Recording - Inspection Requirement 2

## What is This?

This repository contians a base implementation of the UX SDK [by DJI](https://github.com/dji-sdk/Mobile-UXSDK-Android), and a custom implementation of the MissionControl object, which executes the element actions of:
- Taking off;
- Gimbal pitch action of -70 degrees, with completion time of 1.5 seconds, and a delay of 3 seconds after the action completion;
- One photo capture;
- Rotating drone body 30 degrees along the yaw axis relative to true north;
- Recording a video for 4 seconds;
- Reseting gimbal pitch to 0 degrees, with completion time of 1.5 seconds;
- Landing.

## How to use the application?

If you want to execute these elements on the drone, you must:
- Install the application on your Android phone;
- Connect the phone to the drone remote controller;
- Turn on the drone and the remote cotnroller;
- Launch the applicaiton;
- Click on "Complete Demo of Default UI Widgets" button;
- Click on "START".

***ATTENTION*** - The element actions will execute immediatelly! Watch out for your surroundings!