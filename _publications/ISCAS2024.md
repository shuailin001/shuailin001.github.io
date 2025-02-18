---
title: "Squeeze‑Excite Fusion Based Multimodal Neural Network for Sleep Stage Classification with Flexible EEG/ECG Signal Acquisition Circuit"
collection: publications
category: conferences
permalink: /publication/Squeeze‑Excite-Fusion-Based-Multimodal-Neural-Network-for-Sleep-Stage-Classification-with-Flexible-EEG/ECG-Signal-Acquisition-Circuit
excerpt: 'Shuailin Tao, Jinhai Hu, Wang Ling Goh, Yuan Gao'
#date: 2009-10-01
venue: '2024 IEEE International Symposium on Circuits and Systems (ISCAS 2024)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/10557984/'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This paper presents a multimodal fusion strategy for sleep stage classification using polysomnography (PSG) with electroencephalogram (EEG) and Electrocardiogram (ECG) data. The Squeeze-Excite (SE) Fusion mechanism is implemented to enhance the collaborative impact of EEG and ECG signals on neural network classification. To address the challenges of imbalance in the dataset, a balanced sampler is used. Improved feature extraction is achieved through Linear-frequency cepstral coefficients (LFCC) applied to the EEG signal. A recurrent convolutional neural network (RCNN) reduces model parameters and optimizes architecture, while quantizing the network weight down to INT4 ensures hardware compatibility, especially for edge devices. Applying these methodologies to signals, this optimized approach achieves a significant validation accuracy of 77.6% with a compact 23.5KB weight memory size on the MIT-BIH dataset, covering six distinct classification categories.