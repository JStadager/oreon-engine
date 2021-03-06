![Banner](docs/_images/Banner.png)
# Oreon Engine (Java - OpenGL/Vulkan)
Welcome to the Cross-Platform 3D Engine.
As OpenGL and Vulkan Binding for Java the [LWJGL 3](https://www.lwjgl.org/) API is used.

Documentation: http://oreonengine.github.io/oreon-engine

## Build Manual
* Oreon Engine project uses [lombok](https://projectlombok.org/).
  Please download the latest [release](https://projectlombok.org/download) of lombok and run the .jar to install lombok plugin into Eclipse.

* Getting started guide for Eclipse available [here](http://oreonengine.github.io/oreon-engine/_navigation/Getting_Started.html).

## Running Oreonworlds Open World OpenGL Demo
* [oe-gl-demo](https://github.com/oreonengine/oreon-engine/tree/master/oreonengine/oe-gl-demo)
  [OreonWorlds](https://github.com/oreonengine/oreon-engine/blob/master/oreonengine/oe-gl-demo/src/main/java/org/oreon/gl/demo/oreonworlds/Main.java)

<img src="docs/_images/thumbnail4.png" width="500px">

## WIP Vulkan Demo
* [oe-vk-demo](https://github.com/oreonengine/oreon-engine/tree/master/oreonengine/oe-vk-demo)
  [SimpleVulkanDemo](https://github.com/oreonengine/oreon-engine/blob/master/oreonengine/oe-vk-demo/src/main/java/org/oreon/vk/demo/SimpleVulkanDemo.java)

## Camera Control
* Move: W, A, S, D
* Rotate: Hold the middle mouse button while moving the mouse
* Accelerate Movespeed: Scroll mouse

## Features
### Quadtree Terrain
Generated by precomputed FFT Fractal Maps 

<img src="docs/_images/Terrain.png" width="500px">
 
### FFT Water
height displacement and Choppy displacement

<img src="docs/_images/Water.png" width="500px">

### Skydome/Atmosphere
### Dynamic Sunlight
<img src="docs/_images/sun.png" width="500px">

### Parallel Split Shadow Mapping
<img src="docs/_images/Shadows.png" width="500px">

### Variance Shadows
### Percentage Closer Shadow Mapping
### 2x - 8x Multisample Anti-Aliasing
### Tessellation
### Normal- /Displacement-Mapping
<img src="docs/_images/Normalmapping.png" width="500px">

### Instanced Rendering
### Post-Processing Effects
<img src="docs/_images/Blur.png" width="300px" align="left">
<img src="docs/_images/LightScattering_LensFlare.png" width="300px">

#### Motion Blur
#### Depth of Field Blur
#### Bloom
#### Light Scattering
#### Lens Flare

### GUI
## Credits
* [Nvidia Corporation](https://developer.nvidia.com/)
* [World Creator](https://www.world-creator.com/)