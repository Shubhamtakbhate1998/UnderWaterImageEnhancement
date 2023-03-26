TensorFlow and PyTorch implementations of the paper *[Fast Underwater Image Enhancement for Improved Visual Perception (RA-L 2020)](https://ieeexplore.ieee.org/document/9001231)* and other GAN-based models.

![funie-fig](/data/funie.jpg)

### Resources
- Training pipelines for **[FUnIE-GAN](https://ieeexplore.ieee.org/document/9001231)** and **[UGAN](https://ieeexplore.ieee.org/document/8460552) ([original repo](https://github.com/cameronfabbri/Underwater-Color-Correction))**  on [TensorFlow (Keras)](/TF-Keras/) and [PyTorch](/PyTorch/) 
- Modules for image quality analysis based on **UIQM**, **SSIM**, and **PSNR** ([see Evaluation](/Evaluation/))

| Enhanced underwater imagery | Improved detection and pose estimation  | 
|:--------------------|:--------------------|
| ![det-enh](/data/gif1.gif) | ![det-gif](/data/gif2.gif)     |


### FUnIE-GAN Features
- Provides competitive performance for underwater image enhancement
- Offers real-time inference on single-board computers
	- 48+ FPS on Jetson AGX Xavier, 25+ FPS on Jetson TX2
	- 148+ FPS on Nvidia GTX 1080 
- Suitable for underwater robotic deployments for enhanced vision 


	}
	```

