# DnCNN-keras

1.Model Architecture
------------------

> Implementation of "Beyond a Gaussian Denoiser: Residual Learning of Deep CNN for Image Denoising"

### 1.1 Model 1
>  in -> conv(3x3x3x64) -> relu -> conv(64x3x3x64) -> relu -> conv(64x3x3x64) -> relu -> conv(64x3x3x64) -> relu -> conv(64x3x3x3) -> out

### 1.2 Model 2
>  in -> conv(3x3x3x64) -> relu -> conv(64x3x3x64) -> relu -> conv(64x3x3x64) -> relu -> conv(64x3x3x64) -> relu -> conv(64x3x3x3) + in -> out

### 1.3 Model 3
>  in -> conv(3x3x3x64) -> bn -> relu -> conv(64x3x3x64) -> bn -> relu -> conv(64x3x3x64) -> bn -> relu -> conv(64x3x3x64) -> bn -> relu -> conv(64x3x3x3) + in -> out

2.Result
--------
