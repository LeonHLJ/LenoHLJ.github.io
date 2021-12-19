---
title: "Multi-Modality Self-Distillation for Weakly Supervised Temporal Action Localization"
collection: publications
permalink: /publication/2021/12/12-TIP_MMSD
date: 2021/12/12
venue: 'IEEE Transactions on Image Processing (TIP)'
citation: '<b>Linjiang Huang*</b>, Liang Wang, Hongsheng Li. &amp;quot;Multi-Modality Self-Distillation for Weakly Supervised Temporal Action Localization&amp;quot;.<i>IEEE Transactions on Image Processing</i> <b>TIP 2021</b>.'
---

## Abstract
As a challenging task of high-level video understanding, Weakly-supervised Temporal Action Localization (WTAL) has attracted increasing attention in recent years. However, due to the weak supervisions of whole-video classification labels, it is challenging to accurately determine action instance boundaries. To address this issue, pseudo-label-based methods were proposed to generate snippet-level pseudo labels from classification results. In spite of the promising performance, these methods hardly take full advantages of multiple modalities, i.e., RGB and optical flow sequences, to generate high quality pseudo labels. Most of them ignored how to mitigate the label noise, which hinders the capability of the network on learning discriminative feature representations. To address these challenges, we propose a Multi-Modality Self-Distillation (MMSD) framework, which contains two single-modal streams and a fused-modal stream to perform multi-modality knowledge distillation and multi-modality self-voting. On the one hand, multi-modality knowledge distillation improves snippet-level classification performance by transferring knowledge between single-modal streams and a fused-modal stream. On the other hand, multi-modality self-voting mitigates the label noise in a modality voting manner according to the reliability and complementarity of the streams. Experimental results on THUMOS14 and ActivityNet1.3 datasets demonstrate the effectiveness of our method and superior performance over state-of-the-art approaches. 

### Code
https://github.com/LeonHLJ/MMSD
