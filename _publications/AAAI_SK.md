---
title: "Part-Level Graph Convolutional Network for Skeleton-Based Action Recognition"
collection: publications
permalink: /publication/2020/04/03-AAAI_SK
date: 2020/04/03
venue: 'Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)'
citation: '<b>Linjiang Huang*</b>, Yan Huang, Wanli Ouyang, Liang Wang. &quot;Part-Level Graph Convolutional Network for Skeleton-Based Action Recognition&quot;.<i>Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)</i> <b>AAAI 2020</b>.'
---

## Abstract
Recently, graph convolutional networks have achieved remarkable performance for skeleton-based action recognition. In this work, we identify a problem posed by the GCNs for skeleton-based action recognition, namely part-level action modeling. To address this problem, a novel Part-Level Graph Convolutional Network (PL-GCN) is proposed to capture part-level information of skeletons. Different from previous methods, the partition of body parts is learnable rather than manually defined. We propose two part-level blocks, namely Part Relation block (PR block) and Part Attention block (PA block), which are achieved by two differentiable operations, namely graph pooling operation and graph unpooling operation. The PR block aims at learning high-level relations between body parts while the PA block aims at highlighting the important body parts in the action. Integrating the original GCN with the two blocks, the PL-GCN can learn both part-level and joint-level information of the action. Extensive experiments on two benchmark datasets show the state-of-the-art performance on skeleton-based action recognition and demonstrate the effectiveness of the proposed method.
