---
title: "A Contrastive Teacher-Student Framework for Novelty Detection under Style Shifts"
collection: "publications"
permalink: /publication/causal
excerpt: 'There have been several efforts to improve Novelty Detection (ND) performance. However, ND methods often suffer significant performance drops under minor distribution shifts caused by changes in the environment, known as style shifts. This challenge arises from the ND setup, where the absence of out-of-distribution (OOD) samples during training causes the detector to be biased toward the dominant style features in the in-distribution (ID) data. As a result, the model mistakenly learns to correlate style with core features, using this shortcut for detection. Robust ND is crucial for real-world applications like autonomous driving and medical imaging, where test samples may have different styles than the training data. Motivated by this, we propose a robust ND method that crafts an auxiliary OOD set with style features similar to the ID set but with different core features. Then, a task-based knowledge distillation strategy is utilized to distinguish core features from style features and help our model rely on core features for discriminating crafted OOD and ID sets. We verified the effectiveness of our method through extensive experimental evaluations on several datasets, including synthetic and real-world benchmarks, against nine different ND methods.'

date: 2025/10/13
venue: 'Submitted to ICLR'
paperurl: #'https://openreview.net/pdf?id=UVSKuh9eK5'
---

![Main figure of the paper](../images/causal.png)
<!-- [Download paper here]([http://academicpages.github.io/files/paper1.pdf](https://openreview.net/pdf?id=UVSKuh9eK5)) -->