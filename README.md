## ***Morphe***: High-Fidelity Generative Video Streaming with Vision Foundation Model

[![python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)](https://www.python.org/downloads/release/python-3100/) 
[![pytorch](https://img.shields.io/badge/PyTorch-2.5-ee4c2c?logo=pytorch&logoColor=white)](https://pytorch.org/get-started/locally/) [![cuda](https://img.shields.io/badge/CUDA-12.1-0a27b5?logo=cuda&logoColor=white)](https://developer.nvidia.com/cuda-12.1.0-download-archive)

⭐ If ***Morphe*** is helpful to you, please star this repo. Thanks! 🤗
 
## ✅ TODO
- [ ] Update paper link
- [ ] Pretrained models
- [ ] Code release
- [x] ~~Repo release~~
- [x] ~~Demo~~


## 📝 Abstract
![Model System](images/model_system.png)

Video streaming is a fundamental Internet service, while the quality still cannot be guaranteed especially in poor network conditions such as bandwidth-constrained and remote areas. Existing works mainly work towards two directions: traditional pixel-codec streaming nearly approaches its limit and is hard to step further in compression; the emerging neural-enhanced or generative streaming usually fall short in latency and visual fidelity, hindering their practical deployment. 

Inspired by the recent success of vision foundation model (VFM), we strive to ***harness the powerful video understanding and processing capacities of VFM to achieve generalization, high fidelity and loss resilience for real-time video streaming with even higher compression rate.*** We present , the first revolutionized paradigm that enables VFM-based end-to-end generative video streaming towards this goal. Specifically, ***Morphe*** employs joint training of visual tokenizers and variable-resolution spatiotemporal optimization under simulated network constraints. Additionally, a robust streaming system is constructed that leverages intelligent packet dropping to resist real-world network perturbations. Extensive evaluation demonstrates that ***Morphe*** achieves comparable visual quality while saving 62.5% bandwidth compared to H.265, and accomplishes real-time, loss-resilient video delivery in challenging network environments, representing a milestone in VFM-enabled multimedia streaming solutions.

## 😍 Visual Demo

Visual comparison between ***Morphe*** and H.265 when compressing 1080P HD video at 395kbps with 20% packet loss:

<div align="center">  
  <img src="https://img.shields.io/badge/You_can_click_the_videos_folder_in_the_left_file_tree_to_download_hd_comparison_videos-red?style=for-the-badge" alt="Download Notice">  
</div>

<div align="center">
    <img src="videos/capybara.gif" width="auto" height="600px" />
</div>
<br>
<div align="center">
    <img src="videos/lake.gif" width="auto" height="600px"/>
</div>

## 📌Frame Demo

![Frame Demo](images/compare.png)

