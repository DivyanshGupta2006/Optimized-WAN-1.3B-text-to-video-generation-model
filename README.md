# Optimized WAN-1.3B: Enhanced Text to Video Generation

This repository contains the source code for a highly optimized version of the Wan2.1-1.3B text to video generation model developed by Wan AI. Several optimization techniques were applied to improve inference speed without compromising on output quality. A gradio interface seamlessly integrates the pipeline, allowing the user to control individual hyperparameters and view metrics to assess resource usage and model performance. An example output can be viewed below.\

https://github.com/user-attachments/assets/babe4c1e-9479-460e-b2c8-c79d5ad540d3

Prompt: A golden retriever puppy runs joyfully through a field of blooming sunflowers under a bright blue sky, with petals floating in the air and butterfiles fluttering aorund. The camera slowly follows the puppy from a low angle.\\

Features:
- LoRA
- 4-bit quantization
- Operator fusion
- CPU offloading
- CFG parallelism
- Precise control over number of inference steps and guidance scale


To run optimised Wan 1.3B locally, first clone the repository and install requirements.\
```git clone https://github.com/DivyanshGupta2006/Optimized-WAN-1.3B-text-to-video-generation-model.git```\
```cd Optimized-WAN-1.3B-text-to-video-generation-model```\
```pip install -r requirements.txt```\

Then, proceed to run ```Optimized_WAN_1_3B.ipynb```. The generated video is saved under the path ```output_video.mp4```, and an additional mp4 ```output_frames.mp4``` contains the generated frames played back at 1 fps.
Previous versions of the project can be viewed in the ```Older_Versions``` folder.
