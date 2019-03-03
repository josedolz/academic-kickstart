---
title: HyperDense-Net A hyper-densely connected CNN for multi-modal image segmentation 
date: '2018-10-09T16:39:14+02:00'
authors:
#  - Jose Dolz
  - Jose Dolz, Karthik Gopinath, Jing Yuan, Herve Lombaert, Christian Desrosiers, Ismail Ben Ayed
publication_types:
  - '2'
header:
  caption: caption
  image: https://github.com/josedolz/academic-kickstart/tree/master/static/img/HyperDenseNet.png
publication: IEEE Transactions on Medical Imaging
abstract: Recently, dense connections have attracted substantial attention in computer vision because they facilitate gradient flow and implicit deep supervision during training. Particularly, DenseNet, which connects each layer to every other layer in a feed-forward fashion, has shown impressive performances in natural image classification tasks. We propose HyperDenseNet, a 3D fully convolutional neural network that extends the definition of dense connectivity to multi-modal segmentation problems. Each imaging modality has a path, and dense connections occur not only between the pairs of layers within the same path, but also between those across different paths. This contrasts with the existing multi-modal CNN approaches, in which modeling several modalities relies entirely on a single joint layer (or level of abstraction) for fusion, typically either at the input or at the output of the network. Therefore, the proposed network has total freedom to learn more complex combinations between the modalities, within and in-between all the levels of abstraction, which increases significantly the learning representation. We report extensive evaluations over two different and highly competitive multi-modal brain tissue segmentation challenges, iSEG 2017 and MRBrainS 2013, with the former focusing on 6-month infant data and the latter on adult images. HyperDenseNet yielded significant improvements over many state-of-the-art segmentation networks, ranking at the top on both benchmarks. We further provide a comprehensive experimental analysis of features re-use, which confirms the importance of hyper-dense connections in multi-modal representation learning. Our code is publicly available.
#image_preview: /img/sample-815141_640.jpg
selected: false
url_pdf: 'https://arxiv.org/pdf/1804.02967.pdf'
#url_code: 'https://github.com/josedolz/HyperDenseNet'
#math: true
---

