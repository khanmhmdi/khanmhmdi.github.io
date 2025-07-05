---
title:          "DETR-SAM: Automated Few-Shot Segmentation with Detection Transformer and Keypoint Matching"
date:           2023-01-05 00:01:00 +0800
selected:       true
pub:            "IEEE-COINS"
pub_date:       "2024"
abstract: >- 
  Few-shot Segmentation (FSS) aims to segment objects in an image using only a few annotated examples. The Segment Anything Model (SAM) has recently gained attention in FSS due to its versatility and capability to handle various segmentation tasks with prompts. However, its potential to autonomously segment predefined visual categories (e.g., cars, faces) within a dataset without explicit human prompting remains underexplored. To address this gap, this work focuses on automating the process, eliminating the need for manual prompts to reduce ambiguity and improve contextual understanding. We propose a novel technique, DETR-SAM, which integrates the DEtection TRansformer (DETR) with a keypoint matching algorithm to generate automatic prompts for SAM to segment the objects within the image. In particular, DETR predicts the object position boundaries. To enhance segmentation accuracy, keypoint matching is employed to detect keypoints between support and query images. Evaluations on the FSS dataset show that our method achieves comparable performance to several state-of-the-art models. Furthermore, due to the utilization of the pretrain vision models, our method is robust to overfitting. DETRSAM stands out by automating prompt generation, showcasing its promising effectiveness in the FSS domain.

cover:          /assets/images/covers/detr-sam.png
authors:
- Mohamadreza Khanmohamadi*
- Bahar Farahani*
links:
  Paper: https://ieeexplore.ieee.org/abstract/document/10622658/
---
