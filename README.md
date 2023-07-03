# Live Mission Recording - Inspection Requirement 2

## What is This?

This repository contains a base implementation of the UX SDK [by DJI](https://github.com/dji-sdk/Mobile-UXSDK-Android), and a custom implementation of the MissionControl object, which executes the element actions of:
- Taking off;
- Gimbal pitch action of -70 degrees, with completion time of 1.5 seconds, and a delay of 3 seconds after the action completion;
- Rotating drone body 30 degrees along the yaw axis relative to true north;
- One photo capture ***OR*** Recording a video for 4 seconds;
- Resetting gimbal pitch to 0 degrees, with completion time of 1.5 seconds;
- Landing.

## How to use the application?
Make sure to create an API Key via the official [DJI Developer platform](https://developer.dji.com/), and paste the key in the AndroidManifest.xml file.

If you want to execute these elements on the drone, you must:
- Install the application on your Android phone;
- Connect the phone to the drone remote controller;
- Turn on the drone and the remote controller;
- Launch the application;
- Click on "Complete Demo of Default UI Widgets" button;
- Click on "START".

***ATTENTION*** - The element actions will execute immediately! Watch out for your surroundings!