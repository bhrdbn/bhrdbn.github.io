---
title: "Scanning Trojaned Models Using Out-of-Distribution Samples"
collection: publications
permalink: /publication/trodo
excerpt: 'In this work, we’ve introduced TRODO, a new method for detecting backdoor attacks in deep neural networks. TRODO identifies trojans by adversarially shifting out-of-distribution (OOD) samples toward in-distribution (ID) and detecting when classifiers mistakenly classify them as ID. This approach is effective even without training data and works against adversarially trained trojaned classifiers, making it adaptable across different scenarios and datasets.'

date: 2024/10/13
venue: 'Published in NeurIPS'
paperurl: #'https://openreview.net/pdf?id=UVSKuh9eK5'
---
Scanning for trojan (backdoor) in deep neural networks is crucial due to their significant real-world applications. There has been an increasing focus on developing effective general trojan scanning methods across various trojan attacks. Despite advancements, there remains a shortage of methods that perform effectively without preconceived assumptions about the backdoor attack method. Additionally, we have observed that current methods struggle to identify classifiers trojaned using adversarial training. Motivated by these challenges, our study introduces a novel scanning method named TRODO (TROjan scanning by Detection of adversarial shifts in Out-of-distribution samples). TRODO leverages the concept of "blind spots" regions where trojaned classifiers erroneously identify out-of-distribution
(OOD) samples as in-distribution (ID). We scan for these blind spots by adversarially shifting OOD samples towards in-distribution. The increased likelihood
of perturbed OOD samples being classified as ID serves as a signature for trojan detection. TRODO is both trojan and label mapping agnostic, effective even
against adversarially trained trojaned classifiers. It is applicable even in scenarios where training data is absent, demonstrating high accuracy and adaptability across various scenarios and datasets, highlighting its potential as a robust trojan scanning strategy.

![Main figure of the paper](../images/trodo.png)
<!-- [Download paper here]([http://academicpages.github.io/files/paper1.pdf](https://openreview.net/pdf?id=UVSKuh9eK5)) -->

