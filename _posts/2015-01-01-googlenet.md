---
title: GoogLeNet
author: Marie-Neige Chapel
date: 2015-01-01
category: CNN
layout: post
---

This network [1], also called Inception-v1, is a particular incarnation of the Inception architecture.

## Architecture

{% include model_architecture.html img_detailed='assets/img/googlenet_detailed.svg' %}

{% include_relative conv_relu.md %}

{% include_relative inception_module.md %}

{% include_relative depth_concatenation.md %}

{% include_relative global_average_pooling.md %}

## Bibliography

- [1] [[Paper] Going deeper with convolutions](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Szegedy_Going_Deeper_With_2015_CVPR_paper.pdf)
- [2] [[Medium] Going deeper with convolutions: the inception paper, explained](https://medium.com/aiguys/going-deeper-with-convolutions-the-inception-paper-explained-841a0c661fd3)
- [3] [[Blog] Understanding the inception module in deep learning](https://deepai.org/machine-learning-glossary-and-terms/inception-module)
- [4] [[Medium] Review GoogLeNet (Inception v1) - Winner of ILSVRC 2014 (Image Classification)](https://medium.com/coinmonks/paper-review-of-googlenet-inception-v1-winner-of-ilsvlc-2014-image-classification-c2b3565a64e7)
- [5] [[Dockship] GoogLeNet pretrained model](https://dockship.io/articles/606726b2c4b39328660fcd9e/googlenet:-cnn-architecture)
