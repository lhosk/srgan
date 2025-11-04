# SRGAN - LH

### Data Structures

**data**  
├── **train_32/**  
├── **train_128/**  
├── **train_128_from_32/**  
├── **test_32/**  
├── **test_128/**  
└── *data_preparation.py*  

**notebooks**  
└── *GAN2.ipynb*  

**models**  
├── *modelA.keras*  
├── *modelB.keras*  
└── **modelSRGAN/**  
&emsp;├── *srgan_generator_epoch150.keras*  
&emsp;├── *srgan_discriminator_epoch150.keras*  
&emsp;├── *srgan_losses.csv*  
&emsp;└── ...  

##### Tiny info
Data Files on GitHub hold limited image files to due size restrictions.   
The number represents the resolutions (32 is 32x32 res, 128 is 128x128, and 128_from_32 is the 128x128 made from the 32x32 using the SRGAN).   




### References

1. **OpenAI.** *ChatGPT.*  
   https://chat.openai.com  

2. **TensorLayer.** *SRGAN Implementation.*  
   GitHub Repository: [https://github.com/tensorlayer/SRGAN/tree/master](https://github.com/tensorlayer/SRGAN/tree/master)

3. **Balraj98.** *Single Image Super-Resolution GAN (SRGAN) – PyTorch.*  
   Kaggle Notebook: [https://www.kaggle.com/code/balraj98/single-image-super-resolution-gan-srgan-pytorch](https://www.kaggle.com/code/balraj98/single-image-super-resolution-gan-srgan-pytorch)

4. **Lornatang.** *SRGAN-PyTorch.*  
   GitHub Repository: [https://github.com/Lornatang/SRGAN-PyTorch/tree/main](https://github.com/Lornatang/SRGAN-PyTorch/tree/main)

5. **Ledig, C., Theis, L., Huszár, F., Caballero, J., Aitken, A., Tejani, A., Totz, J., Wang, Z., & Shi, W.**  
   *Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network.*  
   arXiv: [https://arxiv.org/pdf/1609.04802](https://arxiv.org/pdf/1609.04802)