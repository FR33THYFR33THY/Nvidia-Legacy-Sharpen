# Nvidia-Legacy-Sharpen

## Description
A superior alternative for sharpening your game.

## Requirements
- Nvidia GPU

## Alternative For AMD GPU'S
Radeon Image Sharpening in driver settings. <br>
This is the same as FidelityFX CAS Sharpening, which is built into some game settings options.

![Radeon Image Sharpening FidelityFX](https://github.com/user-attachments/assets/bac312ad-e80a-419b-a5ec-31225937ca58)

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

![Artifacts Comparison](https://github.com/user-attachments/assets/73ec9b8f-e747-4d1f-8025-ff80e06fac5d)

## Comparisons

- 1 Default

![3](https://github.com/user-attachments/assets/5e2aa7d6-827a-4c8f-82be-77d07f8bd126)

- 2 FidelityFX CAS (In Game, 50%)

![4](https://github.com/user-attachments/assets/afcbd040-5eef-4e93-a64b-2d12338b976f)

- 3 Geforce Filters (Sharpen +, 50%)

![5](https://github.com/user-attachments/assets/983815d4-538a-4d0c-b1fd-5b3d8fc96c16)

- 4 Nvidia Image Scaling (1632x918, 50%)

![6](https://github.com/user-attachments/assets/61c7c28f-27cc-4fbd-becd-44080cef981c)

- 5 Legacy Sharpen (Ignore Film Grain 0, 50%)

![7](https://github.com/user-attachments/assets/0b72702f-c2fd-420a-855a-f40803efb77c)

## Benchmark
7800x3d 4090 1080p<br>
OBS NDI game capture<br>
All tests used 360Hz with DSC off

![8](https://github.com/user-attachments/assets/56befe6a-08ad-4e29-bc3f-c6fcda33170f)

## Video
[Video](<https://youtu.be/KzVQL117-E0>)

[![Video](https://img.youtube.com/vi/KzVQL117-E0/maxresdefault.jpg)]([https://www.youtube.com/watch?v=KzVQL117-E0](https://youtu.be/KzVQL117-E0))
