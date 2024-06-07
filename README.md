### Introduction

My computer specifications:
- Graphics Card: RTX 4080
- CPU: i9-13900k
If you encounter issues such as out-of-memory errors, please reduce the image resolution or use a higher-performance computer.

### Preview Images:
<img src="https://github.com/baicai99/ComfyUI_Backgorund_fusion/assets/101706274/0b5ed5a7-f4c6-4e14-9a04-afa7f02e7753" width="400" alt="Image Description">
<img src="https://github.com/baicai99/ComfyUI_Backgorund_fusion/assets/101706274/587015d2-827e-4e1b-9c5d-91548685e9f6" width="400" alt="Image Description">
<img src="https://github.com/baicai99/ComfyUI_Backgorund_fusion/assets/101706274/56512024-7db2-4c91-a4e9-091c31c61405" width="400" alt="Image Description">
<img src="https://github.com/baicai99/ComfyUI_Backgorund_fusion/assets/101706274/bb139025-c28a-4cd7-8cc1-01fa4645d9fb" width="400" alt="Image Description">

### FAQs:

Q: What is the purpose of this workflow?
A: This workflow is primarily used for further image fusion using Stable Diffusion webui when the fusion of a person into a background image using Photoshop is insufficient. This workflow can replace the manual image fusion process. However, the prerequisite is that the person has already been integrated into the background, not generating the background from a white image. These two workflows have different logics.

Q: How do I use this workflow?
A: Step 1: You need to find the corresponding model pose on a material website and then use Photoshop to blend it into the image. Step 2: Directly import the image into the workflow to produce a refined, copyright-compliant model image.

Q: What should I do if an error occurs?
A: Post it directly in the comment section. I check the comments every day at 10 AM, 3 PM, and 9 PM (GMT+8).

Q: What if the fusion is not good?
A: The quality of the fusion depends on many factors, such as the choice of the original image and the background image. The higher the quality of the original image, the better the theoretical fusion effect, and vice versa.

If you cannot download via the provided link, it is likely because your location is outside of China. Please use a VPN or other means to access it.

- Recommended large model: [majic V7](https://www.liblib.art/modelinfo/bced6d7ec1460ac7b923fc5bc95c4540)

- Recommended Vae: [Realistic difConsistency Negative (Pack)](https://www.liblib.art/modelinfo/232ff495f7c14381910dc6f4df78a7ab)

### v1.0.5_20240531
- Optimization: Parameter optimization.
- New: Updated interface, more aesthetically pleasing.

### v1.0.4_20240529
- Continuous output of images, with perfect results from this workflow.
- Fix: Realized that the lack of realism in facial features was due to using an anime-style vae.

### v1.0.3_20240528
- New: Added an edge blur node to better integrate the model with the surrounding environment, eliminating gray edges.
- New: Implemented a dual-mask system for seated poses to ensure proper shadow rendering; if recognition is insufficient, use mask editing in the load area.
- Fix: Adjusted numerous parameters to produce more natural images.

### v1.0.2_20240527
- New: Added a node for reducing resolution when dealing with extremely high-pixel images, which significantly reduces computation load; not connected by default.
- Fix: Adjusted numerous parameters to produce more natural images.

### v1.0.1_20240527
- Change: Replaced openpose full with dw openpose.
- Change: Replaced canny with anyline.
- Optimization: Improved denoising, feathering, semantic segmentation, prompt inversion, and parameters.
- Optimization: More natural smiles.

### v1.0.0_20240526
- New: Initial version.
- New: Person integration.
- New: Face redraw.
- New: Hand redraw.
