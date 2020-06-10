---
title: "Unsupervised Intra-domain Adaptation for Semantic Segmentation through Self-Supervision"
collection: publications
permalink: /publications/2020-intrada
date: 2020-06-16
venue: "IEEE Conference on Computer Vision and Pattern Recognition 2020 (CVPR 2020)"
citation: "<b>Fei Pan</b>, Inkyu Shin, Francois Rameau, Seokju Lee, In So Kweon. <i>IEEE Conference on Computer Vision and Pattern Recognition 2020</i>. <b>CVPR 2020</b>."
---

[[Project page]](https://feipan664.github.io/IntraDA/) [[Paper]](https://arxiv.org/pdf/2004.07703.pdf)  [[Code]](https://github.com/feipan664/IntraDA.git) [[Presentation]](https://youtu.be/x1KLka4iQlo) [[DemoVideo]](https://youtu.be/Cy71aWeHQe4)

## Abstract
Convolutional neural network-based approaches have achieved remarkable progress in semantic segmentation. However, these approaches heavily rely on annotated data which are labor intensive. To cope with this limitation, automatically annotated data generated from graphic engines are used to train segmentation models. However, the models trained from synthetic data are difficult to transfer to real images. To tackle this issue, previous works have considered directly adapting models from the source data to the unlabeled target data (to reduce the inter-domain gap). Nonetheless, these techniques do not consider the large distribution gap among the target data itself (intra-domain gap). In this work, we propose a two-step self-supervised domain adaptation approach to minimize the inter-domain and intra-domain gap together. First, we conduct the inter-domain adaptation of the model; from this adaptation, we separate the target domain into an easy and hard split using an entropy-based ranking function. Finally, to decrease the intra-domain gap, we propose to employ a self-supervised adaptation technique from the easy to the hard split. Experimental results on numerous benchmark datasets highlight the effectiveness of our method against existing state-of-the-art approaches.