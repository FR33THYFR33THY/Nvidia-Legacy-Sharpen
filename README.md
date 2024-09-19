# Nvidia-Legacy-Sharpen

## Description
A superior alternative for sharpening your game.

## Requirements
- Nvidia GPU

## Alternative For AMD GPU'S
Radeon Image Sharpening in driver settings. <br>
This is the same as FidelityFX CAS Sharpening, which is built into some game settings options.

![Radeon Image Sharpening FidelityFX](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/9dc543a9-dc2e-4298-a096-d67c060d7e9c)


## Why
- GeForce Experience "Game Filters" significantly reduces framerate.
- Nvidia Image Scaling "NIS" sharpening significantly ruins image quality, forcing a lower resolution.
 <br> NIS also forces GPU scaling, which increases latency.

Legacy sharpen enables you to enhance the game's sharpness through display scaling, resulting in minimal impact on framerate and latency, and without any loss in image quality. Use Legacy Sharpen if FidelityFX CAS Sharpening is unavailable in the game.

## Note
Display Stream Compression "DSC" monitors should already have this option unlocked.

Some DX12 games may require the shader cache files to be deleted before legacy sharpening optimization is applied.
Another way to force game shaders to reload, you can update your graphics driver. Ensure you apply the sharpen optimization before launching the game.
Legacy sharpening is baked into the DX12 shaders, so if the game shaders have already been loaded before the optimization is applied, you may see artifacts.

![Artifacts Comparison](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/ce734f29-b4bd-4b19-9d7f-d64d70eaed89)


## Comparisons

- 1 Default

![1 Default](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/f45442f4-180f-4c0d-a4f2-ddbd5eab6ed9)

- 2 FidelityFX CAS (In Game, 50%)

![2 FidelityFX CAS (In Game, 50%)](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/7bb625f7-4831-4667-9f56-bb2ef574300c)

- 3 Geforce Filters (Sharpen +, 50%)

![3 Geforce Filters (Sharpen +, 50%)](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/4c2a5f9f-14e5-4eb0-8e3f-83ff69af7c46)

- 4 Nvidia Image Scaling (1632x918, 50%)

![4 Nvidia Image Scaling (1632x918, 50%)](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/1498695d-d533-430c-af0c-ee81313c1050)

- 5 Legacy Sharpen (Ignore Film Grain 0, 50%)

![5 Legacy Sharpen (Ignore Film Grain 0, 50%)](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/aedd052b-7fd7-475e-a904-44011cddae93)


## Benchmark
7800x3d 4090 1080p<br>
OBS NDI game capture<br>
All tests used 360Hz with DSC off

![Picture1](https://github.com/fr33thytweaks/Nvidia-Legacy-Sharpen/assets/168888348/a703040f-8717-4082-9915-697dbe466e9e)

## Video
[Video](<https://youtu.be/KzVQL117-E0>)

[![Video](https://img.youtube.com/vi/KzVQL117-E0/maxresdefault.jpg)]([https://www.youtube.com/watch?v=KzVQL117-E0](https://youtu.be/KzVQL117-E0))
