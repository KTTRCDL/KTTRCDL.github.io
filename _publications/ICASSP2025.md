---
title: "UMETTS: A Unified Framework for Emotional Text-to-Speech Synthesis with Multimodal Prompts"
collection: publications
category: conferences
permalink: /publication/ICASSP2025
excerpt: 'The paper introduces UMETTS, a multimodal emotional text-to-speech (E-TTS) framework that leverages emotional cues from text, audio, and visual inputs. The proposed system incorporates an Emotion Prompt Alignment Module (EP-Align) and an Emotion Embedding-Induced TTS Module (EMI-TTS) to generate expressive and emotionally resonant speech.'
date: 2025-04-06
venue: 'ICASSP'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10889012/'
citation: 'Xiang Li, Zhi-Qi Cheng, Jun-Yan He, Junyao Chen, Xiaomao Fan, Xiaojiang Peng, Alexander G Hauptmann (2025). &quot;UMETTS: A Unified Framework for Emotional Text-to-Speech Synthesis with Multimodal Prompts; <i>2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)</i>.'
---

Emotional Text-to-Speech (E-TTS) synthesis has garnered significant attention in recent years due to its potential to revolutionize human-computer interaction. However, current E-TTS approaches often struggle to capture the intricacies of human emotions, primarily relying on oversimplified emotional labels or single-modality input. In this paper, we introduce the Unified Multimodal Prompt-Induced Emotional Text-to-Speech System (UMETTS), a novel framework that leverages emotional cues from multiple modalities to generate highly expressive and emotionally resonant speech. The core of UMETTS consists of two key components:(1)the Emotion Prompt Alignment Module (EP-Align) and the Emotion Embedding-Induced TTS (EMI-TTS). EP-Align employs contrastive learning to align emotional features across text, audio, and visual modalities, ensuring a coherent fusion of multimodal information.(2)Subsequently, EMI-TTS integrates the aligned emotional embeddings with state-of-the-art TTS models to synthesize speech that accurately reflects the intended emotions. Extensive evaluations show that UMETTS achieves significant improvements in emotion accuracy and speech naturalness, outperforming traditional E-TTS methods on both objective and subjective metrics.

Please refer to the [paper](https://ieeexplore.ieee.org/abstract/document/10889012/) for more details. We have made our code publicly available at [UMETTS](https://github.com/KTTRCDL/UMETTS). If citation is needed, please use the following BibTeX entry:

```bibtex
@INPROCEEDINGS{10889012,
  author={Li, Xiang and Cheng, Zhi-Qi and He, Jun-Yan and Chen, Junyao and Fan, Xiaomao and Peng, Xiaojiang and Hauptmann, Alexander G.},
  booktitle={ICASSP 2025 - 2025 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={UMETTS: A Unified Framework for Emotional Text-to-Speech Synthesis with Multimodal Prompts}, 
  year={2025},
  volume={},
  number={},
  pages={1-5},
  keywords={Human computer interaction;Visualization;Codes;Accuracy;Contrastive learning;Signal processing;Reproducibility of results;Acoustics;Text to speech;Speech processing;Emotional Text-to-Speech;Multimodal Synthesis;Contrastive Learning;Expressive Speech Synthesis;Human-Computer Interaction},
  doi={10.1109/ICASSP49660.2025.10889012}}
```
