---
title: Investigating Transfer Learning Capabilities of Vision Transformers and
  CNNs by Fine-Tuning a Single Trainable Block
publication_types:
  - "3"
authors:
  - Durvesh Malpure
  - Onkar Litake
  - Rajesh Ingle
author_notes:
  - Equal Contribution
  - Equal Contribution
doi: October 2021
publication: In arXiv
publication_short: In arXiv
abstract: >
  In recent developments in the field of Computer Vision, a rise is seen in the
  use of transformer-based architectures. They are surpassing the
  state-of-the-art set by CNN architectures in accuracy but on the other hand,
  they are computationally very expensive to train from scratch. As these models
  are quite recent in the Computer Vision field, there is a need to study it’s
  transfer learning capabilities and compare it with CNNs so that we can
  understand which architecture is better when applied to real world problems
  with small data. In this work, we follow a simple yet restrictive method for
  fine-tuning both CNN and Transformer models pretrained on ImageNet1K on
  CIFAR-10 and compare them with each other. We only unfreeze the last
  transformer/encoder or last convolutional block of a model and freeze all the
  layers before it while adding a simple MLP at the end for classification. This
  simple modification lets us use the raw learned weights of both these neural
  networks. From our experiments, we find out that transformers-based
  architectures not only achieve higher accuracy than CNNs

  but some transformers even achieve this feat with around 4 times lesser number of parameters.
draft: false
url_pdf: https://arxiv.org/ftp/arxiv/papers/2110/2110.05270.pdf
featured: false
tags: []
date: 2021-11-26T17:04:02.769Z
links: null
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
---
