# Optimized WAN-1.3B: Enhanced Text to Video Generation

This repository contains the source code for a highly optimized version of the Wan2.1-1.3B text to video generation model developed by Wan AI. Several optimization techniques were applied to improve inference speed without compromising on output quality. A gradio interface seamlessly integrates the pipeline, allowing the user to control individual hyperparameters and view metrics to assess resource usage and model performance. An example output can be viewed below.

https://github.com/user-attachments/assets/951a3e5d-e53e-4f26-a983-668988aed40e

Features:
- LoRA
- 4-bit quantization
- Operator fusion
- CPU offloading
- DPM scheduler
- Attention slicing
- Precise control over number of inference steps, guidance scale and generation seed


To run optimised Wan 1.3B locally, first clone the repository and install requirements.\
```git clone https://github.com/DivyanshGupta2006/Optimized-WAN-1.3B-text-to-video-generation-model.git```\
```cd Optimized-WAN-1.3B-text-to-video-generation-model```\
```pip install -r requirements.txt```

Then, proceed to run ```Optimized_WAN_1_3B.ipynb```. The generated video is saved under the path ```output_video.mp4```, and an additional mp4 ```output_frames.mp4``` contains the generated frames played back at 1 fps.
Previous versions of the project can be viewed in the ```Older_Versions``` folder.
A profiling report can be viewed showing the improvements that each individual optimization techniques provide over the baseline model.
A technical writeup showing a detailed description of the entire implementation can also be found.
A demo video folder showing various demonstration clips can additionally be viewed. 
