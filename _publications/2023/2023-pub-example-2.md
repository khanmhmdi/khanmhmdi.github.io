---
title:          "Improving spleen segmentation in ultrasound images using a hybrid deep learning framework"
date:           2024-01-21 00:01:00 +0800
selected:       false
pub:            "Nature Publishing Group UK - Scientific Reports"
pub_date:       "2024"
abstract: >-
 This paper introduces a novel method for spleen segmentation in ultrasound images, using a two-phase training approach. In the first phase, the SegFormerB0 network is trained to provide an initial segmentation. In the second phase, the network is further refined using the Pix2Pix structure, which enhances attention to details and corrects any erroneous or additional segments in the output. This hybrid method effectively combines the strengths of both SegFormer and Pix2Pix to produce highly accurate segmentation results. We have assembled the Spleenex dataset, consisting of 450 ultrasound images of the spleen, which is the first dataset of its kind in this field. Our method has been validated on this dataset, and the experimental results show that it outperforms existing state-of-the-art models. Specifically, our approach achieved a mean Intersection over Union (mIoU) of 94.17% and a mean Dice (mDice) score of 96.82%, surpassing models such as Splenomegaly Segmentation Network (SSNet), U-Net, and Variational autoencoder based methods. The proposed method also achieved a Mean Percentage Length Error (MPLE) of 3.64%, further demonstrating its accuracy. Furthermore, the proposed method has demonstrated strong performance even in the presence of noise in ultrasound images, highlighting its practical applicability in clinical environments.
cover:          /assets/images/covers/cover2.jpg
authors:
  - Ali Karimi*
  - Javad Seraj*
  - Fatemeh Mirzadeh Sarcheshmeh
  - Kasra Fazli
  - Amirali Seraj
  - Parisa Eslami
  - Mohamadreza Khanmohamadi*
  - Helia Sajjadian Moosavi
  - Hadi Ghattan Kashani
  - Abdoulreza Sajjadian Moosavi
  - Masoud Shariat Panahi
links:
  Paper: https://www.nature.com/articles/s41598-025-85632-9
  Unsplash: https://unsplash.com/photos/orange-fruit-on-white-table-cloth-ISX_imp8t1o
---
