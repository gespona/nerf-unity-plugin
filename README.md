# nerf-unity-plugin

![nerf poc](nerf_plugin_poc.gif)

NeRF Unity Plugin is native Unity plugin for NeRFRenderCore. NeRFRenderCore is NeRF rendering and training libray by James Perlman (https://github.com/JamesPerlman/NeRFRenderCore)

Initial PoC it's very basic integration showing NeRF training and NeRF composition inside Unity 3D scene, syncing Unity and NeRF camera.

Following work will focus on:

- Save/Load nerf checkpoints
- Improve training and rendering performance
- Offline volumetric rendering
- Realtime rendering inside Unity
- NeRF compositing
- Apply VFX
- Experiments with NeRF training

-> Combine Stable Diffusion with NeRF, for example, using ControlNet for Depth guide to modify NeRF inputs 
