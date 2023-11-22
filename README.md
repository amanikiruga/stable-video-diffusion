---
title: Stable Video Diffusion
code taken from: [multimodalart/stable-video-diffusion](https://huggingface.co/spaces/multimodalart/stable-video-diffusion)
All rights belong to respective owners

## Instructions to use

1. Clone the repo with `git clone https://github.com/amanikiruga/stable-video-diffusion` 
2. Install the packages using `pip install -r requirements.txt`
3. In an interactive python terminal inside the directory run the following to download the model: 

```python
from huggingface_hub import hf_hub_download
hf_hub_download(repo_id="stabilityai/stable-video-diffusion-img2vid-xt", filename="svd_xt.safetensors", local_dir="checkpoints") 
```
4. Run the `simple_video_sample.ipynb` file or mess around as needed
