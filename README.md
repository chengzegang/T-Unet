

# T-Unet (experimental)
## Overview
 A Temporal-Unet designed to extract vocal from songs
## Dependencies

## Datasets
[MUSDB18](https://sigsep.github.io/datasets/musdb.html)
## Model
architecture of T-Net is shown as below, it contains 3 down sampling blocks one tranform block and 3 upsampling blocks. Each Downsampling block shrink input to 1/10 on temporal-wise, and vise versa.
![T-Net architecture](tunet.png "T-Net is basically 1D version of original Unet")
## Statics

## References
