---
title: "16. State of health estimation of lithium-ion batteries based on Mixers-bidirectional temporal convolutional neural network"
collection: publications
permalink: /publication/23-batteries-wangkai
excerpt: ''
date: 2023-10-12
venue: 'Journal of Energy Storage (IF: 9.4)'
citation: 'Jingyi Gao, Dongfang Yang, Shi Wang, Zhaoting Li, Licheng Wang, Kai Wang. State of health estimation of lithium-ion batteries based on Mixers-bidirectional temporal convolutional neural network. In Journal of Energy Storage, 2023.'
---
Abstract
--
Accurate state of health (SOH) estimation is essential for designing a safe and reliable battery management systems (BMS). Although data-driven methods have achieved great accuracy and satisfied robustness in SOH estimation, for most neural networks, it is a challenge for SOH estimation to learn long dependencies in the training process due to the lack of the scalability for modeling long sequences. In this study, a novel SOH estimation framework combing Mixers and bidirectional temporal convolutional neural network (BTCN) is proposed, which not only takes the greatest advantage of local and global properties of input features to estimate SOH of lithium-ion batterie (LIBs), but also eases the redundancy of temporal and channel information. In the data pre-processing, the voltage change in the equal time interval is extracted from the measured data of the constant current (CC) charging stage, which is easily obtained in the real-world charging scenario. Then, the features that are highly correlated with SOH are selected by Pearson correlation coefficient (PCC), and all the features are normalized by minimum-maximum scaling method to speed up the convergence process and reduce the initialization requirement of learning-rate. After pre-processing, all features are input into the Mixers-BTCN model. We carry out experiments on aging data from two public datasets, NASA and CALCE. The simulations results indicate that the R2 for each dataset is above 0.768. The mean absolute error (MAE) and root mean square error (RMSE) that are both held within 2.34 %, which proves the accuracy and stability of the proposed SOH
estimation. In addition, the introduction of transfer learning technology verifies the robustness of the proposed model to different ambient temperatures.

[Download](https://www.sciencedirect.com/science/article/abs/pii/S2352152X23026464)
[Download local](../files/23-batteries-wangkai.pdf)
