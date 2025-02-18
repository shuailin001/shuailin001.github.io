---
title: "Supervised Contrastive Learning Framework and Hardware Implementation of Learned ResNet for Real-time Respiratory Sound Classification"
collection: publications
category: manuscripts
permalink: /publication/Supervised-Contrastive-Learning-Framework-and-Hardware-Implementation-of-Learned-ResNet-for-Real-time-Respiratory-Sound-Classification
excerpt: 'Jinhai Hu, Cong Sheng Leow, Shuailin Tao, Wang Ling Goh, Yuan Gao'
date: 2024-10-01
order: 6
venue: 'IEEE Transactions on Biomedical Circuits and Systems (TBioCAS)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/10550005/'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This paper presents a supervised contrastive learning (SCL) framework for respiratory sound classification and the hardware implementation of learned ResNet on field programmable gate array (FPGA) for real-time monitoring. At the algorithmic level, multiple techniques such as features augmentation and MixUp are combined holistically to mitigate the impact of data scarcity and imbalanced classes in the training dataset. Bayesian optimization further enhances the classification accuracy through parameter tuning in pre-processing and SCL. The proposed framework achieves 0.8725 total score (including runtime score) on a ResNet-18 model in both event and record multi-class classification tasks using the SJTU Paediatric Respiratory Sound Database (SPRSound). In addition, algorithmhardware co-optimizations including Quantization-Aware Training (QAT), merge of network layers, optimization of memory size and number of parallel threads are performed for hardware implementation on FPGA. This approach reduces 40% model size and 70% computation latency. The learned ResNet is implemented on a Xilinx Zynq ZCU102 FPGA with 16ms latency and less than 2% inference score degradation compared to the software model.