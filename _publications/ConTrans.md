---
title: "ConTrans: Improving Transformer with Convolutional Attention for Medical Image Segmentation"
collection: publications
permalink: /publications/ConTrans
venue: "The 25<sup>th</sup> International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI 2022)"
date: 2022-9-16
citation: '<b>Ailiang Lin</b>, Jiayu Xu, Jinxing Li and Guangming Lu.'
---

[[PDF]](https://conferences.miccai.org/2022/papers/107-Paper1211.html)[[Code]](https://github.com/TianBaoGe/ConTrans)

## Abstract
Over the past few years, convolution neural networks (CNNs) and vision transformers (ViTs) have been two dominant architectures in medical image segmentation. Although CNNs can efficiently capture local representations, they experience difficulty establishing long-distance dependencies. Comparably, ViTs achieve impressive success owing to their powerful global contexts modeling capabilities, but they may not generalize well on insufficient datasets due to the lack of inductive biases inherent to CNNs. To inherit the merits of these two different design paradigms while avoiding their respective limitations, we propose a concurrent structure termed ConTrans, which can couple detailed localization information with global contexts to the maximum extent. ConTrans consists of two parallel encoders, i.e., a Swin Transformer encoder and a CNN encoder. Specifically, the CNN encoder is progressively stacked by the novel Depthwise Attention Block (DAB), with the aim to provide the precise local features we need. Furthermore, a well-designed Spatial-Reduction-Cross-Attention (SRCA) module is embedded in the decoder to form a comprehensive fusion of these two distinct feature representations and eliminate the semantic divergence between them. This allows to obtain accurate semantic information and ensure the up-sampling features with semantic consistency in a hierarchical manner. Extensive experiments across four typical tasks show that ConTrans significantly outperforms state-of-the-art methods on ten famous benchmarks.