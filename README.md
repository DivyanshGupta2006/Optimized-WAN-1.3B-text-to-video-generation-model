# Optimized WAN-1.3B: Enhanced Text to Video Generation

This repository contains the source code for a highly optimized version of the Wan2.1-1.3B text to video generation model developed by Wan AI. Several optimization techniques such as LoRA, 4-bit quantization, operator fusion, cpu offloading and CFG parallelism were applied to improve inference speed without compromising on output quality. A gradio interface seamlessly integrates the pipeline, allowing the user to control individual hyperparameters and view metrics to assess resource usage and model performance. An example output can be viewed below.

https://github.com/user-attachments/assets/0252dca3-42ce-4b45-a598-9b426997d51c

To run optimised Wan 1.3B locally, first clone the repository and install requirements.
``` git clone https://github.com/DivyanshGupta2006/Optimized-WAN-1.3B-text-to-video-generation-model.git ```\
``` cd Optimized-WAN-1.3B-text-to-video-generation-model```\
``` pip install -r requirements.txt ```\

Then, proceed to run ```Optimized_WAN_1_3B.ipynb```. Previous versions of the project can be viewed in the ```Older_Versions``` folder.
