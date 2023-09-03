# Drone Inspection Action(s)

## What is This?

This repository contains a copy of a [demo application developed by DJI](https://github.com/dji-sdk/Mobile-UXSDK-Android) with our own custom implementation of some drone actions for the DJI Mini 2 drone. These actions consist of:

- taking off,
- gimbal movement of -70 degrees on the pitch axis, with completion time of 1.5 seconds, and a delay of 3 seconds after the action is completed,
- rotating drone body 30 degrees along the yaw axis relative to North,
- one photo capture **_OR_** recording a video for 4 seconds (for some reason both cannot be executed in one mission execution, since the camera mode is not switched to the required mode, and then the mission gets stuck),
- resetting gimbal position to 0 degrees on the pitch axis, with completion time of 1.5 seconds,
- landing.

To view a complete list of missions and actions, refer to [Official DJI Documentation](https://developer.dji.com/api-reference/android-api/Components/Missions/DJIMissionAction.html). Note that not all of the actions are functional for the DJI Mini 2 drone.

## How to use the application?

Make sure to create an API Key via the official [DJI Developer platform](https://developer.dji.com/), and paste the key in the AndroidManifest.xml file.

If you want to execute these elements on the drone, you must:

- Install the application on your Android phone;
- Connect the phone to the drone remote controller;
- Turn on the drone and the remote controller;
- Launch the application;
- Click on "Complete Demo of Default UI Widgets" button;
- Click on "START".

**_ATTENTION_** - The element actions will execute immediately! Watch out for your surroundings!
