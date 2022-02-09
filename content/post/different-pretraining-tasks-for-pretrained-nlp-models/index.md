---
title: Different pretraining tasks for pretrained NLP models.
date: 2022-02-09T03:16:12.421Z
draft: false
featured: false
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
In recent years, there are a huge number of pretrained NLP models created by researchers. In pretraining the model, a huge amount of data is taken and passed through a model with specific task. These tasks are called as pre-training task. In this article we gonna look at different pre-training tasks:

Depending on whether the pretrained model is encoder only or encoder-decoder framework, there are various pretraining tasks:

1. Masked Language modeling

2. Span Correction

Cross-lingual text-to-text pretraining tasks:

3. Translation Pair Span correction

4. Translation Span Correction

5. Machine Translation





### 5. Machine Translation

Machine Translation is used as a text-to-text pretraining task for Seq-to-Seq learning. It was used in paper ['Cross-Lingual Natural Language Generation via Pre-training'](https://arxiv.org/abs/1909.10481).  Let e and f denote a sentence and its corresponding translation. We directly use e and f as the input and output sequences, respectively. The loss function of MT is    
Lmt(e,f) = L(e -> f)




