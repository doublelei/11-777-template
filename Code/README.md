
## Image Encoder —— VQVAE2

### CUB dataset
1. Download the dataset images from [CUB](http://www.vision.caltech.edu/visipedia/CUB-200.html)

2. Train VQVAE2 with CUB images by 
```
cd vq-vae-2pytorch & python train_vqvae.py [DATASET PATH]
```

### Sample Result
The reconstructed results:
![Sample from Stage 1 (VQ-VAE)](vq-vae-2-pytorch/sample/00560_00000.png)

The checkpoint is [here](vq-vae-2-pytorch/checkpoint/vqvae2_cub_560.pt)

