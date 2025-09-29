---
title: "Efficient neutral-IGM inference from noisy 21-cm forest spectra with latent-space U-Net encoding and XGBoost"
collection: publications
permalink: /publication/Soltinsky_2025_file
excerpt: 'Coauthor, [ads](https://ui.adsabs.harvard.edu/abs/2025arXiv250711611P/abstract){:target="_blank" rel="noopener"}'
date: 2025-7-15
venue: 'arXiv'
paperurl: 'http://tomassoltinsky.github.io/files/Patil_2025.pdf'
citation:
---

The 21-cm forest, comprising narrow absorption features imprinted on the radio spectra of high-redshift radio-loud quasars by intervening neutral hydrogen, offers a uniquely sensitive probe of the thermal state of the neutral intergalactic medium (IGM) during the epoch of reionization. Although over 30 such quasars are now known at $$z>5.5$$, the signal remains elusive in practice, owing to instrumental noise, the intrinsic weakness of the absorption features, and the limited brightness of available background sources. Recent studies have focused on the one-dimensional transmission power spectrum as a statistical observable, but this approach also demands high signal-to-noise ratios. Here, we present a systematic comparison of five inference pipelines for recovering IGM parameters from mock 21-cm forest spectra at $$z=6$$, incorporating realistic instrumental noise and telescope characteristics. We show that likelihood-free inference based on machine learning substantially outperforms traditional Bayesian methods. In particular, our most effective method dispenses with the power spectrum entirely: we use a convolutional U-Net to extract a latent-space encoding of the input spectrum and perform parameter regression using XGBoost. This approach yields accurate constraints on the IGM neutral fraction and X-ray heating efficiency even with a single 50-hour uGMRT sightline, which is an orders-of-magnitude improvement in integration time relative to existing techniques. We publicly release our code, training data, and models. Beyond the 21-cm forest, these results underscore the promise of hybrid deep learning and gradient-boosted inference techniques for extracting physical information from low-SNR data across astrophysics.
