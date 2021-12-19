---
title: "Modeling Sub-Actions for Weakly Supervised Temporal Action Localization"
collection: publications
permalink: /publication/2021/05/13-TIP_SUB
date: 2021/05/13
venue: 'IEEE Transactions on Image Processing (TIP)'
citation: '<b>Linjiang Huang*</b>, Yan Huang, Wanli Ouyang, Liang Wang. &quot;Modeling Sub-Actions for Weakly Supervised Temporal Action Localization&quot;.<i>IEEE Transactions on Image Processing</i> <b>TIP 2021</b>.'
---

## Abstract
As a challenging task of high-level video understanding, weakly supervised temporal action localization has attracted more attention recently. Due to the usage of video-level category labels, this task is usually formulated as the task of classification, which always suffers from the contradiction between classification and detection. In this paper, we describe a novel approach to alleviate the contradiction for detecting more complete action instances by explicitly modeling sub-actions. Our method makes use of three innovations to model the latent sub-actions. First, our framework uses prototypes to represent sub-actions, which can be automatically learned in an end-to-end way. Second, we regard the relations among sub-actions as a graph, and construct the correspondences between sub-actions and actions by the graph pooling operation. Doing so not only makes the sub-actions inter-dependent to facilitate the multi-label setting, but also naturally use the video-level labels as weak supervision. Third, we devise three complementary loss functions, namely, representation loss, balance loss and relation loss to ensure the learned sub-actions are diverse and have clear semantic meanings. Experimental results on THUMOS14 and ActivityNet1.3 datasets demonstrate the effectiveness of our method and superior performance over state-of-the-art approaches.
