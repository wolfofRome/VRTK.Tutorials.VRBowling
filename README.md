[![VRTK logo][VRTK-Image]](#)

# VR Bowling Game Tutorial

> _This has been tested on version 2019.4.28f1 of the Unity software_

[![License][License-Badge]][License]
[![Backlog][Backlog-Badge]][Backlog]
[![Discord][Discord-Badge]][Discord]
[![Videos][Videos-Badge]][Videos]
[![Twitter][Twitter-Badge]][Twitter]

## Introduction

A tutorial on how to make a VR Bowling game using the components from the VRTK suite within the [Unity] software.

This tutorial covers the basics of getting a VR camera working within Unity and being able to interact with objects within the scene.

> If you're using Unity 2020.1 or above then please refer to the [Converting To Unity 2020] tutorial.

![VR Bowling Scene](https://user-images.githubusercontent.com/36199993/74746663-af050780-525d-11ea-8eb0-6ba279fed0f7.gif)

## Getting Started

Follow the [Making A VR Bowling Game] tutorial to build this project yourself in an empty Unity project or follow the instructions below to download the completed project.

### Downloading the project

* Download this project repository to your local machine using *one* of the following methods:
  * Git clone the repository with `git clone https://github.com/ExtendRealityLtd/VRTK.Tutortials.VRBowling.git`
  * Download the zip file at `https://github.com/ExtendRealityLtd/VRTK.Tutortials.VRBowling/archive/master.zip` and extract it.

### Opening the downloaded project in the Unity software

> **Do not** drag and drop this downloaded tutorial project into an existing Unity project. The downloaded tutorial project **is a Unity project** already and you should not nest a Unity project inside another Unity project. Follow the instructions below for opening this tutorial project within the Unity software.

#### Using the Unity Hub

* Open the [Unity Hub] panel.
* Click the `Add` Button.
* Browse to the local directory where the repository was cloned/downloaded to and click `Select Folder`.
* The tutorial project will now show up in the Unity Hub project window, so select `VRTK.Tutortials.VRBowling` to open the project in the Unity software.
* The `VRTK.Tutortials.VRBowling` project will now open within the Unity software.

#### Opening from within the Unity software

* Select `Main Menu -> File -> Open Project` within the Unity software.
* Browse to the local directory where the repository was cloned/downloaded to and click `Select Folder`.
* The `VRTK.Tutortials.VRBowling` project will now open within the Unity software.

### Running the game scene

* Open the `Assets/Scenes/BowlingAlley` scene.
* Enable `Maximize On Play` in the Unity Game view control bar to ensure no performance issues are caused by the Unity Editor overhead.
* Play the scene in the Unity Editor (`CTRL` + `P`).
* The scene should automatically play within any Unity supported XR hardware.

## Contributing

We're not currently in a place where accepting contributions would be helpful. But as soon as we're ready we'll let you know!

## License

Code released under the [MIT License][License].

## Disclaimer

These materials are not sponsored by or affiliated with Unity Technologies or its affiliates. "Unity" is a trademark or registered trademark of Unity Technologies or its affiliates in the U.S. and elsewhere.

[VRTK-Image]: https://raw.githubusercontent.com/ExtendRealityLtd/related-media/main/github/readme/vrtk.png
[Unity]: https://unity3d.com/
[Converting To Unity 2020]: Documentation/Tutorials/03.ConvertingToUnity2020/README.md
[Making A VR Bowling Game]: Documentation/Tutorials/01.MakingAVRBowlingGame/README.md

[License-Badge]: https://img.shields.io/github/license/ExtendRealityLtd/VRTK.svg
[Backlog-Badge]: https://img.shields.io/badge/project-backlog-78bdf2.svg

[Discord-Badge]: https://img.shields.io/badge/discord--7289DA.svg?style=social&logo=discord
[Videos-Badge]: https://img.shields.io/badge/youtube--e52d27.svg?style=social&logo=youtube
[Twitter-Badge]: https://img.shields.io/badge/twitter--219eeb.svg?style=social&logo=twitter

[License]: LICENSE.md
[Backlog]: http://tracker.vrtk.io

[Discord]: https://discord.com/invite/bRNS6hr
[Videos]: http://videos.vrtk.io
[Twitter]: https://twitter.com/VR_Toolkit

[Unity Hub]: https://docs.unity3d.com/Manual/GettingStartedUnityHub.html
