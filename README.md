# vTuber-Virtual-Production-Studio-Assets

![](https://i.imgur.com/2kgB34a.jpg)

## Summery
This is an asset pack for doing virtual productions. You can apply these assets and workflows to your games, or vr simulations to capture multi-camera realtime footage from within a video game running Unity3d. This package would be a good starting point for anyone interested in a do-it-yourself approach to making virtual productions inside Unity. 

Inside Unity, you can import / create your own set and then use this camera system to help you speed up production with access to 9 cameras, and 12 overlay slides.

## What is Included
Included is the this package are the assets to make a full studio environment setup for virtual productions. 

There are no avatars included, but this package is a great starting point to create a virtual world to produce content in. 

If you are looking for open source avatars I reccomend: Link

## Instructions 
(C# control system included in packm this version runs in the Editor when you push Play)
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

## Camera Controls
When the keyboard controls are pressed (1-9) the camera seleted will be Set to Active, while the others are set to Inactive. The camera previews can be seen on the camera preview panel using Render textures at a lower resolution for optimization. 

## General Workflow
To make a custom production, we create and customize a set, configure the locations of the cameras, animate the cameras, then during runtime, we use the camera control panel to switch between these cameras with a camera operator in real time with VRChat as our network and avatar layer. We are capturing the output with OBS (Open Broadcast Software) to captre the audio and video of the production from the game engine. 

The different versions of this software can be used in different ways depending on the platform you are planning to work on.

It is common to use many platforms to create a virtual production.

## Slides / Overlay
This system was designed with presentations in mind so we have an extra camera that renders planes in front of a camera to create the illusion of an Overlay by pushing 0.

We swap out 12 different Slides(show/hide gameObjects) using the numeric keypad and also the (.) key and the (+) key. 

You can swap out the pictures of the slides before building the production, by editing the materials. We import jpegs, and add them to the respective materials before we do the production. A possible extention to this would be to use a URLLoader to have dynamic materials and slides. 

## Arranging The Cameras
Move the cameras (via the Parent Object) and feel free to animate or extend the cameras to do even more things like add more scripts and functionality as needed. If the camera are designed to be moved as rigid body, make sure to put the rigid body, and pickup scripts on the parent object to maintain the camera heirchy. Arrange the cameras around your set by translating the cameras manually, and checking the camera preview object to see how it looks in frame.

## Pro-Tip: 
Because of the way the camera previews work, you should only move the Master Root of each camera. You can add an additional Parent object to the cameras if you like, and animate those for animated camera tracks. 

## Camera Culling / Hiding Objects From Cameras
If you would like to hide / show things in the camera output, you would setup layers and use camera culling with a "SeenByCamera" layer and "GreenScreen" culling layers for teh reflection probe not to reflect the greenscreens.

## Dependencies
This .unitypackage was built on Unity 2018.4.20f1 (with VRChat in mind)
The cameras use some "movement" scritps from the Standarad Assets (https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-for-unity-2017-3-32351)
VRChat SDK will be needed to use the Template packages (for Multiplayer VR Builds)

The camera control script is very basic to get you started with virtual prodcutions. They were coded in a way to make it easier to port to VRChat / uDon / uSharp. (certain functions and classes are not available inside VRChat SDK3)

To see beta version builds, please vist my github repo. 

## Versions Of This Camera System
There are different versions of this suite. This is the BOILERPLATE version that will run in the Editor and in Play Mode to demonstrate the controls of the camera system and workflow of a virtual studio and designed to be extended. 

**vTuberStudioAssets_v1.unitypackage**
This package

**vTuberStudioTemplateSDK2_v1.unitypackageVRC** 
VRC SDK2 Template World Build v1

**vTuberStudioTemplateUDON_v1.unitypackage**
VRC SDK3 uDon / uSharp Template v1 

**Custom vTuber Studio Template**
Please contact me with project details.

## Template VRChat MultiplayerStudio 
We have a template vTuber Studio availible as a drag and drop prefab, that works with VRC SDK2. With this prefab you can make your own production studio inside VRChat by customizing the enviroment and uploading to VRChat Servers.

## Custom VRChat Multiplayer Studio
Our crew is available for comission to create CUSTOM VR Production studios for podcasts, music videos, films, concerts, events, and other productions. We will curate models based on the budget and deisgn, light, and customize your production studio to meet your needs. If you have any custom productions in mind, please feel free to reach out! @godfreymeyer

## Examples
Please check out the examples and tutorials on my youtube page to get familiar on the workflow on virtual prodcutions. These asset can be ported to work in any game engine, and the basic camera control scipts have been written in C# and would have to be ported to work on other platforms tah Unity. Using platforms like VRChat, we have filmed many music videos, podcasts and events in VR using this system as a base. It has sped up production when making rooms or builds for vTubing, vPodcasts, and vFilms, and endless "over the network, real-time collaborative" projects. 

## Web Resources:
http://Unity3d.com/
http://vrchat.com/
https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-for-unity-2017-3-32351

Special thanks to Jin, the VR Devs, and the Web XR community for helping in various way to make this possible.

Please subscribe to my youtube page http://www.youtube.com/godfreymeyer and check out more v on my guthub github.com/gm3 Much love!


## Contact

Please check out some our productions on [Youtube](https://www.youtube.com/results?search_query=godfrey+meyer&page=&utm_source=opensearch) "Godfrey Meyer" or [#boomboxhead](https://www.youtube.com/results?search_query=%23boomboxhead) to find videos. If you have any questions please feel free to reach out to me #boomboxhead on discord `painterpainting#5603`. Have fun and link me to the videos you make, thanks!
