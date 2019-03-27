# TerrainTools
New Terrain Tools and Brush Assets for the Unity Terrain system.

## Installation
1. Clone this repository somewhere to disk or download the .zip by clicking the "Clone or Download" button
2. Open your Unity project (2018.3 or later)
3. Drag and drop the Editor and Shaders folder into your project
4. After the project recompiles, you should be able to use the tools and brushes with Terrain

## Included Tools
- Utility
  - Bridge
  - Clone Stamp
  - Mesh Stamp
  - Slope Flatten Height
- Erosion
  - Erode Height
  - Ridging Erosion
  - Terrace Erosion
- Transform
  - Pinch Height
  - Sharpen Height
  - Smudge Height
  - Twist Height

## RunSwimFly Tool Additions

1. Setup

The drop down menu under paint tools will now contain a folder called “RunSwimFly Tools”. Ensure that you have ticked the “Draw Instanced” checkbox in you terrain options. 


2. Overview

The package adds automation to the process of texture and height painting. It does this by filtering according to terrain slope, height and texture and through simulating hydraulic erosion.

You can view a usage demonstration at https://youtu.be/2H84nHdi_JM


3. Masked Paint Texture

The masked texture tool allows you to paint textures using slope and height filters and by using the pre existing textures as masks or stencils. As with all of the tools mouse over a label to get a description of what the control does. Using the various sliders you can set a control value at which a texture is maximally applied. You can also set the breadth of values over which the texture is applied and how sharp the boundary is.

Slope and height slider values can be set directly or by shift clicking or shift dragging to sample the terrain in the scene view. You can preview current settings by clicking the “Fill” button and then undoing. Then paint as you would with any other tool or hit “Fill” to paint the entire terrain.

Each texture has its own set of control values so you can move between them without losing your settings.


4. Hydraulic Erosion

This tool uses a simulated water flow to erode terrains. Left mouse to add water to the terrain. The brush opacity setting determines the rate of water addition. 

When you first start adding water a simulation area is set up around the brush. You can wait for the water to evaporate or you can stop the simulation by pressing the shift key. Left clicking outside the simulation zone will restart the simulation with a new zone. You can expand the simulation area using the “Extent” slider until it covers the entire terrain. However large simulation areas require faster graphics hardware to run at a reasonable frame rate.

There are numerous controls to affect water behaviour and appearance, erosion characteristics and simulation speed and area. Mouse over the labels to get tool tips. As always you can undo if you are not satisfied with the results.

You can mask or stencil the operation according to the underlying texture.


4. Other tools

The other tools operate as their standard analogues but with the ability to mask or stencil the operation according to the underlying texture.


5. Contact

Please contact business@runswimfly.com if you have any comments or queries.
