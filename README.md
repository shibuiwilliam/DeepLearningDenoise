# DeepLearningDenoise
This repository shows various ways to use deep learning to denoise images, using Cifar10 as dataset and Keras as library.

## Noisy Images
I made two kinds of noisy images:
1. images with random black lines
2. images with random colorful lines

![4](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/4.PNG)

![5](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/5.PNG)

## Cifar_DeLine_AutoEncoder
Convolutional autoencoder to denoise images.

##### black lines denoising
![ae1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/ae1.PNG)
![ae2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/ae2.PNG)

##### colorful lines denoising
![aeColor1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/aeColor1.PNG)
![aeColor2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/aeColor2.PNG)

## Cifar_Denoise_CAE
Another convolutional autoencoder.

##### black lines denoising

##### colorful lines denoising


## Cifar_Denoise_DNCNN
Denoising convolutional neural network.
https://arxiv.org/pdf/1608.03981v1.pdf

##### black lines denoising

##### colorful lines denoising


## Cifar_Denoise_Win5RB
Wide Inference Network with 5 layers of Resnet including Batchnormalization.
https://arxiv.org/pdf/1707.05414.pdf

##### black lines denoising

##### colorful lines denoising


