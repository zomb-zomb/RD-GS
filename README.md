# RD-GS

## Code is comming soon.

## Abstract

![image](https://github.com/zomb-zomb/RD-GS/assets/60563359/ba47e63c-c609-44f2-bcdc-bdde2bee6ac8)

In recent years, Neural Radiance Fields (NeRF) has revolutionized 3D reconstruction with its implicit representation. Building upon NeRF, 3D Gaussian Splatting (3D-GS) has departed from the implicit representation of neural networks and instead directly represents scenes as point clouds with Gaussian-shaped distributions. While this shift has notably elevated the rendering quality and speed of radiance fields but inevitably led to a significant increase in memory usage. Additionally, effectively rendering dynamic scenes in 3D-GS has emerged as a pressing challenge. To address these concerns, this paper purposes a dynamic scene rendering framework with a hybrid representation of explicit and implicit features. We use a deformable MLP to capture the dynamic offset of Gaussian points and express the color features of points through hash encoding and a tiny MLP to reduce storage requirements. Moreover, we introduce a learnable denoising mask coupled with denoising loss to eliminate noise points from the scene, thereby further compressing 3D-GS. Finally, motion noise of points is mitigated through static constraints and motion consistency constraints. Experimental results demonstrate that our method surpasses existing approaches in rendering quality and speed, while significantly reducing the memory usage associated with 3D-GS, making it highly suitable for various tasks such as novel view synthesis, and dynamic mapping.


## Method
![image](https://github.com/zomb-zomb/RD-GS/assets/60563359/a08fdc43-4c14-4d9c-978b-fd5932c02d55)

## Experiment

![image](https://github.com/zomb-zomb/RD-GS/assets/60563359/b01701a8-3c3e-4b24-b418-0bc715ffd0e0)


