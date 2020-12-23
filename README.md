# GAN

Generative Adversarial network（生成对抗网络)

概述：GAN（生成对抗网络），顾名思义，这个网络第一部分是生成网络，第二部分对抗模型严格来讲是一个判别器；简单来说，就是让两个网络相互竞争，生成网络来生成假的数据，对抗网络通过判别器去判别真伪，最后希望生成器生成的数据能够以假乱真。

核心思想：判断器的任务是尽力将假的判断为假的，将真的判断为真的；生成器的任务是使生成的越真越好。两者交替迭代训练。

Discriminator Network(对抗网络)

Generative Network（生成网络）

环境：

CUDA10.1 ; Pytorch1.5.1 ; python 3.7 ......

## 0、前置

理解GAN: 博客

1、简单的多层神经网络（Multilayer neural network）

训练速度快：10轮：CPU——14mins, GPU——6mins ；50轮之后才有效果

2、简单的卷积神经网络（Convolutional Neural Network）

GPU, 10轮左右效果就能展现出来了。

## 1、Auxiliary Classifier GAN









