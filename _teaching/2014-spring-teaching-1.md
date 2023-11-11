---
title: "Poison Dart Frog: A Clean-Label Attack with Low Poisoning Rate and High Attack Success Rate in the Absence of Training Data"
collection: 
permalink: /teaching/2014-spring-teaching-1
date: 2023-10-14
paperurl: 'https://arxiv.org/pdf/2308.09487.pdf'
---

Abstract

To successfully launch backdoor attacks, injected data needs to be correctly labeled; otherwise, they can be easily detected by even basic data filters. Hence, the concept of clean-label attacks was introduced, which is more dangerous as it doesn’t require changing the labels of injected data. To the best of our knowledge, the existing clean-label backdoor attacks largely rely on an understanding of the entire training set or a portion of it. However, in practice, it is very difficult for attackers to have it because training datasets are often collected from multiple independent sources.

Unlike all current clean-label attacks, we propose a novel clean label method called 'Poison Dart Frog'. Poison Dart Frog does not require access to any training data; it only necessitates knowledge of the target class for the attack, such as 'frog'. On CIFAR10, Tiny-ImageNet, and TSRD, with a mere 0.1%, 0.025%, and 0.4% poisoning rate of the training set size, respectively, Poison Dart Frog achieves a high Attack Success Rate compared to LC, HTBA, BadNets, and Blend. Furthermore, compared to the state-of-the-art attack, NARCISSUS, Poison Dart Frog achieves similar attack success rates without any training data. Finally, we demonstrate that four typical backdoor defense algorithms struggle to counter Poison Dart Frog.

Recommended citation: **Ma B**, Wang J, Wang D, et al. Poison Dart Frog: A Clean-Label Attack with Low Poisoning Rate and High Attack Success Rate in the Absence of Training Data[J]. *arXiv preprint* arXiv:2308.09487, 2023.

