<!-- 
layout: page
title: "abstract"
permalink: /abstract/
-->

# Abstract

We propose ChordGAN, a generative adversarial network that transfers the style elements of music genres. ChordGAN seeks to learn the rendering of harmonic structures into notes by embedding chroma feature extraction within the training process. In notated music, the chroma representation approximates chord notation as it only takes into account the pitch class of musical notes, representing multiple notes collectively as a density of pitches over a short time period. Chroma is used in this work to distinguish critical style features from content features and improve the consistency of transfer. ChordGAN uses conditional GAN architecture and appropriate loss functions, paralleling image-to-image translation algorithms. In the paper, pop, jazz, and classical datasets were used for training and transfer purposes. To evaluate the success of the transfer, two metrics were used: Tonnetz distance, to measure harmonic similarity, and a separate genre classifier, to measure the transfer style fidelity. Given its success under these metrics, ChordGAN can be utilized as a tool for musicians to study compositional techniques for different styles using same chords and automatically generate music from lead sheets.
