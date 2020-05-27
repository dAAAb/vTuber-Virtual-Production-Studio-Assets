# vTuber-Virtual-Production-Studio-Assets

![](https://i.imgur.com/2kgB34a.jpg)

## Summery
This is an asset pack for doing virtual productions. You can apply these assets and workflows to your games, or vr simulations to capture multi-camera realtime footage from within a video game running Unity3d. 

## What is Included
Included is a full studio environment setup to make virtual podcast, and video content from inside Unity3d. There are no avatars included, but this package is a great starting point to create a virtual world to produce content in. If you are looking for open source avatars I reccomend: Link

## Examples
Please check out the examples and tutorials on my youtube page to get familiar on the workflow on virtual prodcutions. These asset can be ported to work in any game engine, and the basic camera control scipts have been written in C# and would have to be ported to work on other platforms tah Unity. Using platforms like VRChat, we have filmed many music videos, podcasts and events in VR using this system as a base. It has sped up production when making rooms or builds for vTubing, vPodcasts, and vFilms, and endless "over the network, real-time collaborative" projects. 

## Versions Of This Camera System
There are different versions of this suite. This is the BOILERPLATE version that will run in the Editor and in Play Mode to demonstrate the concept of Virtual Productions. 

I have create template worlds for VRC as well you can obtain. Links

This package would be a good starting point for anyone interested in a do-it-yourself approach to making virtual productions inside Unity. 

Inside Unity, you can import / create your own set and then use this camera system to help you speed up production with access to 9 cameras, and 12 overlay slides.

## Camera Controls
When the keyboard controls are pressed (1-9) the camera seleted will be Set to Active, while the others are set to Inactive. The camera previews can be seen on the camera preview panel using Render textures at a lower resolution for optimization. 

## General Workflow
We create and customize the sets, configure the locations of the cameras, animate the cameras, then during runtime, we use the camera control panel to switch between these cameras, capturing the output window with OBS (Open Broadcast Software) to captre the audio and video of the production. 

The different versions of this software can be used in different ways depending on the platform you are planning to work on. It is common to use many platforms to create a virtual production.

## Slides / Overlay
This system was designed with presentations in mind so we have an extra camera that renders planes in front of a camera to create the illusion of an Overlay.

We swap out different Slides(show/hide gameObjects) using the numeric keypad. 

You can swap out the pictures of the slides before the production, inside the materials by importing jpegs, and adding them to the respective materials. 

## Arranging The Cameras
Move the cameras (via the Parent Object) and feel free to animate or extend the cameras to do even more things like add more scripts and functionality as needed. I suggest you create a sound stage / set that works for your needs.

## Pro-Tip: 
Because of the way the camera previews work, you should only move the Master Root of each camera. You can add a Parent object to the cameras, and animate those for animated camera tracks. 

If you would like to hide / show things in the camera view, please setup layers and use camera culling with a "SeenByCamera" layer and "GreenScreen" culling layers for teh reflection probe not to reflect the greenscreens.



VRC SDK2 VR World Build 1.0 (coming soon)
uDon / uSharp Build 1.0: (coming soon)

## Dependencies
This .unitypackage was built on Unity 2018.4.20f1 (with VRChat in mind)
The cameras use some "movement" scritps from the Standarad Assets (https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-for-unity-2017-3-32351)
VRChat (for VR Builds)

The camera control script is very basic to get you started with virtual prodcutions. They were coded in a way to make it easier to port to VRChat / uDon / uSharp. (certain functions and classes are not available inside VRChat SDK3)

To see beta version builds, please vist my github repo. 

## Instructions 
(C# control system included in pack)
* 1-9 keys will swap between cameras
* 0 goes to Overlay mode to display 

Slides (Use Numeric Keypad)
* 0-9, (.), (+) to change slides
* F - Map Cam To Screen
* R - Realtime Reflection Probe
* L - Camera Light
* U - Toggle All Cameras
* K - Color Screen Toggle
* P - Camera Previews Toggle
* T - Studio Lights Toggle

## Web Resources:
http://Unity3d.com/
http://vrchat.com/
https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-for-unity-2017-3-32351

Special thanks to Jin, the VR Devs, and the Web XR community for helping in various way to make this possible.

Please subscribe to my youtube page http://www.youtube.com/godfreymeyer and check out more virtual production on my guthub github.com/gm3 Much love!


## Contact

Please check out some our productions on [Youtube](https://www.youtube.com/results?search_query=godfrey+meyer&page=&utm_source=opensearch) "Godfrey Meyer" or [#boomboxhead](https://www.youtube.com/results?search_query=%23boomboxhead) to find videos. If you have any questions please feel free to reach out to me #boomboxhead on discord `painterpainting#5603`. Have fun and link me to the videos you make, thanks!
