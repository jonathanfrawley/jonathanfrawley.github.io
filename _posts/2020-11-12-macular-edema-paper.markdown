---
layout: post
title:  "[Paper] Segmentation of Macular Edema Datasets with Small Residual 3D U-Net Architectures"
date:   2020-11-12 11:19:16 +0000
categories: edema AI deep learning
---
[This paper](https://arxiv.org/abs/2005.04697) investigates the application of deep convolutional neural networks with prohibitively small datasets to the problem of macular edema segmentation. In particular, we investigate several different heavily regularized architectures. We find that, contrary to popular belief, neural architectures within this application setting are able to achieve close to human-level performance on unseen test images without requiring large numbers of training examples. Annotating these 3D datasets is difficult, with multiple criteria required. It takes an experienced clinician two days to annotate a single 3D image, whereas our trained model achieves similar performance in less than a second. We found that an approach which uses targeted dataset augmentation, alongside architectural simplification with an emphasis on residual design, has acceptable generalization performance - despite relying on fewer than 15 training examples. 

This work has been accepted to [BIBE 2020](https://www.ieeebibe2020.org/) and is in the process of publication.
