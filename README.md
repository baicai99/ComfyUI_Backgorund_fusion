# ComfyUI_Backgorund_fusion

### Introduction

My computer configuration:
- GPU: RTX4080
- CPU: i9-13900k
If there are issues with video memory overload, please reduce the image resolution or upgrade to a better-performing computer.

Frequently Asked Questions:

Q: What is the purpose of this workflow?
A: This workflow is mainly used for further image blending with Stable Diffusion webui after integrating people into background images using Photoshop, if the blending is insufficient. This workflow can replace the manual image blending process. However, the prerequisite is that the person has already been integrated into the background, rather than generating the background from a white background image. The logic of these two workflows is different.

Q: How do I use this workflow?
A: Step 1: You need to find the corresponding model pose on the material website and blend it into the image using Photoshop. Step 2: Simply import the image into the workflow to obtain a copyright-friendly and exquisite model image.

Q: What should I do if there is an error?
A: Please directly post it in the comment section, and I will respond at 10 AM, 3 PM, and 9 PM (GMT+8) every day.

Q: I feel that the blending is not good. 
A: There are many factors that determine whether the blending is good or not, such as the selection of the original image and the background image. The higher the quality of the original image, theoretically, the better the blending effect, and vice versa.

If you are unable to download through the provided links, it is likely because your location is not in China. Please use a VPN or other methods to access.

- Recommended large model: [majic V7](https://www.liblib.art/modelinfo/bced6d7ec1460ac7b923fc5bc95c4540)

- Recommended VAE: [Realistic difConsistency Negative (Pack)](https://www.liblib.art/modelinfo/232ff495f7c14381910dc6f4df78a7ab)

### v1.0.5_20240531
- Optimization: Improved parameters.
- New: Updated interface, now more visually appealing.

### v1.0.4_20240529
- Enhancement: Addressed image generation issues to ensure perfect image quality.
- Fix: Corrected the issue with facial realism, which was due to using an anime-style VAE.

### v1.0.3_20240528
- Added: Edge blur node for better blending of the model with the surroundings, eliminating any gray edges.
- Added: Discovered that the shadow may not appear when sitting, so I used the double mask. If there is insufficient recognition, you can directly edit the mask in the loading area.
- Fixed: Changed many parameters to make the images appear more natural.

### v1.0.2_20240527
- Added: Added a node for high-resolution images with a large computational load, to directly reduce the resolution. Default is not connected.
- Fixed: Changed many parameters to make the images appear more natural.

### v1.0.1_20240527
- Changed: Replaced openpose full with dw openpose.
- Changed: Replaced canny with anyline.
- Optimized: Improved denoising, feathering, semantic segmentation, hint word inference, and parameters.
- Optimized: More natural smiles.

### v1.0.0_20240526
- Added: Initial version.
- Added: Character blending
- Added: Facial redrawing
- Added: Hand redrawing