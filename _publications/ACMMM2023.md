---
title: "Semi-supervised multimodal emotion recognition with expression mae"
collection: publications
category: conferences
permalink: /publication/ACMMM2023
excerpt: 'The Multimodal Emotion Recognition (MER 2023) challenge aims to recognize emotion with audio, language, and visual signals, facilitating innovative technologies of affective computing. This paper presents our submission approach on the Semi-Supervised Learning Sub-Challenge (MER-SEMI).'
date: 2023-10-26
venue: 'ACMMM'
paperurl: 'https://dl.acm.org/doi/10.1145/3581783.3612840'
citation: 'Zebang Cheng, Yuxiang Lin, Zhaoru Chen, Xiang Li, Shuyi Mao, Fan Zhang, Daijun Ding, Bowen Zhang, Xiaojiang Peng. (2023). &quot;Semi-supervised multimodal emotion recognition with expression mae.&quot; <i>Proceedings of the 31st ACM International Conference on Multimedia</i>.'
---

The Multimodal Emotion Recognition (MER 2023) challenge aims to recognize emotion with audio, language, and visual signals, facilitating innovative technologies of affective computing. This paper presents our submission approach on the Semi-Supervised Learning Sub-Challenge (MER-SEMI). First, with large-scale unlabeled emotional videos, we train both image-based and video-based Masked Autoencoders to extract visual features, which termed as expression MAE (expMAE) for simplicity. The expMAE features are found to be largely complementary with other official baseline features. Second, since there is only a few labeled data, we use a classifier to generate pseudo labels for unlabeled videos which have high confidence for a certain category. In addition, we also explore several advanced large models for cross-feature extraction like CLIP, and apply factorized bilinear pooling (FBP) for multimodal feature fusion. Our methods finally achieved 88.55% in F1 score on MER-SEMI, ranking second place among all participating teams.

Please refer to the [paper](https://dl.acm.org/doi/10.1145/3581783.3612840) for more details. We have made our code publicly available at [Emotion-LLaMA](https://github.com/ZebangCheng/Emotion-LLaMA). If citation is needed, please use the following BibTeX entry:

```bibtex
@inproceedings{cheng2023semi,
  title={Semi-supervised multimodal emotion recognition with expression mae},
  author={Cheng, Zebang and Lin, Yuxiang and Chen, Zhaoru and Li, Xiang and Mao, Shuyi and Zhang, Fan and Ding, Daijun and Zhang, Bowen and Peng, Xiaojiang},
  booktitle={Proceedings of the 31st ACM International Conference on Multimedia},
  pages={9436--9440},
  year={2023}
}
```
