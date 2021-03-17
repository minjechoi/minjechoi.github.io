---
title: "StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation"
collection: publications
permalink: /publications/2018-StarGAN
excerpt: 'Existing approaches on image-to-image translation, while capable of producing high-quality translation images, were limited to one-on-one translations and also less robust on multiple domains. To address this limitation, we introduced StarGAN, a model that uses a simple yet effective approach, one-hot masking, and show through facial image translation tasks that our model is capable of performing multiple forms of image translations.'
date: 2018-06-18
venue: 'Conference on Computer Vision and Pattern Recognition (CVPR)'
paperurl: 'https://ieeexplore.ieee.org/document/8579014'
citation: 'Y. Choi, M. Choi, M. Kim, J. Ha, S. Kim and J. Choo, "StarGAN: Unified Generative Adversarial Networks for Multi-domain Image-to-Image Translation," 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, Salt Lake City, UT, USA, 2018, pp. 8789-8797, doi: 10.1109/CVPR.2018.00916.'
---

Abstract: Recent studies have shown remarkable success in image-to-image translation for two domains. However, existing approaches have limited scalability and robustness in handling more than two domains, since different models should be built independently for every pair of image domains. To address this limitation, we propose StarGAN, a novel and scalable approach that can perform image-to-image translations for multiple domains using only a single model. Such a unified model architecture of StarGAN allows simultaneous training of multiple datasets with different domains within a single network. This leads to StarGAN's superior quality of translated images compared to existing models as well as the novel capability of flexibly translating an input image to any desired target domain. We empirically demonstrate the effectiveness of our approach on a facial attribute transfer and a facial expression synthesis tasks.

[Alternative download link for paper (arxiv)](https://arxiv.org/abs/1711.09020)

[Code and models used for the paper](https://github.com/yunjey/stargan)