---
title: "Teach-DETR: Better Training DETR with Teachers"
collection: publications
permalink: /publication/TPAMI2023
excerpt: ''
venue: 'IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)'
date: 2023-09-23
paperurl: ''
citation: '<b>Linjiang Huang</b>, Kaixin Lu, Guanglu Song, Liang Wang, Si Liu, Yu Liu, Hongsheng Li. &quot;Teach-DETR: Better Training DETR with Teachers&quot;.<i>IEEE Transactions on Pattern Analysis and Machine Intelligence</i> <b>TPAMI 2023</b>.'
---

## Abstract
In this paper, we present a novel training scheme, namely Teach-DETR, to better train DETR-based detectors from versatile types of teacher detectors. We show that the predicted boxes from teacher detectors are effective medium to transfer knowledge of teacher detectors, which could be either RCNN-based or DETR-based detectors, to train a more accurate and robust DETR model. 
This new training scheme can easily incorporate the predicted boxes from multiple teacher detectors, each of which provides parallel supervisions to the student DETR. Our strategy introduces no additional parameters and adds negligible computational cost to the original detector during training. During inference, Teach-DETR brings zero additional overhead and maintains the merit of requiring no non-maximum suppression. Extensive experiments show that our method leads to consistent improvement for various DETR-based detectors. Specifically, we improve the state-of-the-art detector DINO with Swin-Large backbone, 4-scale feature pyramid and 36-epoch training schedule, from 57.8% to 58.9% in terms of mean average precision on COCO 2017 val set.


### Code
[Link](https://github.com/LeonHLJ/Teach-DETR)