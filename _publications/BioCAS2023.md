---
title: "Supervised contrastive pretrained ResNet with MixUp to enhance respiratory sound classification on imbalanced and limited dataset"
collection: publications
category: conferences
permalink: /publication/Supervised-contrastive-pretrained-ResNet-with-MixUp-to-enhance-respiratory-sound-classification-on-imbalanced-and-limited-dataset
excerpt: 'Jinhai Hu, Cong Sheng Leow, Shuailin Tao, Wang Ling Goh, Yuan Gao'
date: 2023-10-01
order: 5
venue: '2023 IEEE Biomedical Circuits and Systems Conference (BioCAS 2023)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/document/10389029/'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This paper proposes a strategy of combining multiple techniques to classify paediatric respiratory sound (PRS) from the Open-Source SJTU Paediatric Respiratory Sound Database. Inspired by recent successes in image classification, this work focuses on improving audio classification with limited and imbalanced datasets through Residual Networks (ResNet). These techniques include augmentations applied to audio features, supervised contrastive (SupCon) pretraining, and MixUp. These three techniques helped reduced overfitting due to imbalanced dataset. To further enhance accuracy, pre-processing, and training hyperparameters were optimized through Bayesian Optimization. The proposed strategy achieved over 95% training accuracies for the four tasks in the IEEE BioCAS 2023 grand challenge. Through this strategy, the four tasks achieved calculated scores of 0.769, 0.632, 0.662 and 0.512 respectively using the test dataset. The total score is 0.729 including 0.1 obtained from the runtime bonus.