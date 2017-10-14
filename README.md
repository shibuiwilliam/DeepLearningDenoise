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
![0](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/0.PNG)

##### black lines denoising
![ae1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/ae1.PNG)
![ae2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/ae2.PNG)

##### colorful lines denoising
![aeColor1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/aeColor1.PNG)
![aeColor2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/aeColor2.PNG)

## Cifar_Denoise_CAE
Another convolutional autoencoder.
![1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/1.PNG)

##### black lines denoising
![cae1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/cae1.PNG)
![cae2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/cae2.PNG)

##### colorful lines denoising
![caeColor1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/caeColor1.PNG)
![caeColor2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/caeColor2.PNG)

## Cifar_Denoise_DNCNN
Denoising convolutional neural network.
https://arxiv.org/pdf/1608.03981v1.pdf
![2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/2.PNG)

##### black lines denoising
![dncnn1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/dncnn1.PNG)
![dncnn2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/dncnn2.PNG)

##### colorful lines denoising
![dncnnColor1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/dncnnColor1.PNG)
![dncnnColor2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/dncnnColor2.PNG)

## Cifar_Denoise_Win5RB
Wide Inference Network with 5 layers of Resnet including Batchnormalization.
https://arxiv.org/pdf/1707.05414.pdf
![3](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/3.PNG)

##### black lines denoising
![win1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/win1.PNG)
![win2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/win2.PNG)

##### colorful lines denoising
![winColor1](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/winColor1.PNG)
![winColor2](https://github.com/shibuiwilliam/DeepLearningDenoise/blob/master/imgs/winColor2.PNG)


