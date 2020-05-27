# vTuber-Virtual-Production-Studio-Assets

![](https://i.imgur.com/2kgB34a.jpg)

## Summery
This is an asset pack for doing virtual productions. You can apply these assets and workflows to your games, or vr simulations to capture multi-camera realtime footage from within a viedo game running Unity3d. 

## What is Included
Included is a full studio environment setup to make virtual podcast, and video content from inside Unity3d. There are no avatars included, but this package is a great starting point to create a virtual world to produce content in. 

## Examples
Please check out the examples and tutorials on my youtube page to get familiar on the workflow on virtual prodcutions. These asset  can be ported to work in any game engine, and the basic camera control scipts have been written in C#. We have filmed many music videos, podcasts and events in VR using this system. It has sped up production when making rooms or builds for vTubing, vPodcasts, and vFilms, and endless "over the network, real-time collaborative" projects. Please check out some our productions on Youtube "Godfrey Meyer" or #boomboxhead to find videos. If you have any questions please feel free to reach out to me #boomboxhead on discord painterpainting#5603. Have fun and link me to the videos you make, thanks!

## Versions Of This Camera System
There are different versions of this suite. This is the BOILERPLATE version. I have create templated worlds for VRC as well you can obtain. This package would be a good starting point for anyone interested in a do-it-yourself approach to making virtual productions inside Unity. 

Inside Unity, you can import / create your own set and then use this camera system to help you speed up production with access to 9 cameras, and 12 overlay slides.

## Camera Controls
The way the camera system works, is that it that when the keyboard controls are pressed (1-9) the cameras are Set to Active, while the others are tunrned off. The camera previews can be seen on the camera preview panel using Render textures at a lower resolution for optimization. 

## General Workflow
We create and customize the sets, then during runtime, we use the camera control panel to switch between cameras, and captre the window with OBS (Open Broadcast Software) to captre the audio and video of the production. The different versions of this software can be used in different ways depending ont he platform you are planning to work on. It is common to use many platforms to create a virtual production.

## Slides / Overlay
This system was designed with presentations in mind so we have an extra camera that renders planes infront of a camera, and then we swap out different Slides(gameObjects) using the numeric keypad. You can swap out the pictures of the slides inside the materials by importing jpegs, and adding them to the respective materials. 

## Arranging The Cameras
Move the cameras (via the Parent Object) and feel free to animate or extend the cameras to do even more things. I suggest you create a sound stage / set that works for your needs.

## Pro-Tip: 
Because of the way the camera previews work, only move the Master Root of each camera. You can add a Parent object to the cameras, and animate those for animated camera tracks. Also the names of the layers are reset when VRC SDK setups layers for a project, so the Layers that hide things from the camera lose their name (but still work)... if you would like to hide / show things in the camear view, please re-setup layers and use camera culling.



VRC SDK2 VR World Build 1.0 (coming soon)
uDon / uSharp Build 1.0: (coming soon)

## Dependencies
This .unitypackage was built on Unity 2018.4.20f1 (with VRChat in mind)
The cameras use some scritps fromt he Standarad Assets (https://assetstore.unity.com/packages/essentials/asset-packs/standard-assets-for-unity-2017-3-32351)
VRChat (for VR Builds)

The scripts are very basic controllers to get you started with virtual prodcutions. They were designed in a way to make it easier to port to VRChat / uDon / uSharp. To see beta version builds, please vist my github repo. 

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

Special thanks to Jin, the VR Devs, and the Web XR community for helping is varsious way to make this possible. 
Please subscribe to my youtube page http://www.youtube.com/godfreymeyer and check out more goodies on my guthub github.com/gm3 Much love!


## Contact

Please check out some our productions on [Youtube](https://www.youtube.com/results?search_query=godfrey+meyer&page=&utm_source=opensearch) "Godfrey Meyer" or [#boomboxhead](https://www.youtube.com/results?search_query=%23boomboxhead) to find videos. If you have any questions please feel free to reach out to me #boomboxhead on discord `painterpainting#5603`. Have fun and link me to the videos you make, thanks!
