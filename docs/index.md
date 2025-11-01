# Procedural Celestial Body Materials

This asset contains a set of procedural materials and scripts you can use to generate gas giants, asteroid rings and stars, and stylize them with post-processing glow effects.

![Celestial Bodies](./assets/images/procedural-celestial-bodies/planets-grid.png)

## Asset Contents

1. Shader Graph Procedural Shaders and Materials, MonoBehaviour scripts for quick setup of:

    - [Procedural Asteroid Ring](procedural-asteroid-rings.md)
    - [Procedural Gas Giant + Lit Atmospheric Glow Effect](./procedural-gas-giants.md)
    - [Procedural Star + Star Corona Glow](./procedural-stars.md)

2. Premade Celestial Body Prefabs - 3 Stars and 6 Gas Giants

    - Seen in the example image above, these are ready to drop into your scenes.

3. Utility Editor Scripts

    - [Editor Menu Items](./custom-menu-commands.md) to create procedural celestial bodies with all materials, textures, and components assigned and ready to edit.

4. Custom 3D Meshes for celestial bodies

    - icosphere_high - high-poly sphere for rendering smooth stars and gas giants. High triangle and vertex count allow for smoother looking dynamic procedural visuals.
    - double_sided_plane - double-sided plane mesh allow for Asteroid Rings to be viewed from both sides.

## Samples
There are two sample scenes in this asset:

- Space Objects Sample Scene - shows the 9 sample celestial bodies, with glow effects and URP settings.
- 3D Skybox Sample Scene - shows a more complex 3D Skybox set up using some of the celestial body prefabs.

## URP Settings

![URP Settings Project](./assets/images/3d-skybox/3d-skybox-renderer-asset.png)

The Sample URP Asset and Renderer have the shadows and anti-aliasing settings used to get the look of the asset presented in the store page.

The 3D Skybox Renderer is needed for [3D Skybox](./3d-skybox-background.md) setup.

## VSync

To avoid screen tearing with the glowing corona post-processing effect, make sure to enable VSync in the Scene View:

![Scene VSync Settings](./assets/images/procedural-celestial-bodies/scene-vsync.png)

And in Builds, from the Project Settings:
![Build VSync Settings](./assets/images/procedural-celestial-bodies/build-vsync.png)

