# Unity-Noises

Collection of GPU HLSL noises functions for Unity with :

- 3D Perlin Noise
- 3D Periodic Perlin Noise
- 3D Simplex Noise
- 3D Voronoi Noise

## How to use

The noise functions are all in the .hlsl files in the /Includes/ directory.

Examples of wrapping of these functions for CustomRenderTextures are in the /Examples/ directory for each type of noise. The parameters of each noises are accessible through the corresponding material.

You can use these textures as maps for your material, or write your own material shader using the noise functions directly (recommended for better performance). 


## Acknowledgments 

Simplex and Perlin noise functions are based on Keijiro Takahashi [NoiseShader](https://github.com/keijiro/NoiseShader/).
Voronoi noise functions are based on Scrawk [GPU-Voronoi-Noise](https://github.com/Scrawk/GPU-Voronoi-Noise).
