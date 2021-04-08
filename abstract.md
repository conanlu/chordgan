---
layout: page
title: "abstract"
permalink: /abstract/
---

We propose ComposeGAN as a generative adversarial network that learns and transfers the style elements of tonal music genres. Early attempts of symbolic music style transfer have faced the challenge of maintaining content while changing style. ChordGAN presents a novel method to differentiate between style and content by embedding chroma feature extraction within the training process. A chroma is a visual representation of music that only records note density, distinguishing style from content and improving the consistency of transfer. ComposeGAN uses conditional GAN architecture and loss functions, paralleling Pix2Pix image-to-image translation algorithms. Pop, jazz, and classical datasets were used for training purposes. To evaluate the success of the transfer, two metrics were used: Tonnetz distance, to measure harmonic similarity, and a separate genre classifier, to measure transfer realism. The success of the transfer is evidenced by the high independent genre classifier accuracy rate and low Tonnetz distance, demonstrating a convincing style change and a conservation of content, respectively. ChordGAN can be utilized as a tool for musicians to study compositional techniques and automatically generate music from lead sheets.
