---
title: "Feature Learning and Signal Propagation in Deep Neural Networks"
collection: publications
permalink: /publications/2022-FeatureSignal
excerpt: 'Recent work by Baratin et al. (2021) sheds light on an intriguing pattern that occurs during the training of deep neural networks: some layers align much more with data compared to other layers'
date: 2022-07-17
venue: 'ICML 2022'
citation: 'Lou, Yizhang, Chris E. Mingard, and Soufiane Hayou. "Feature Learning and Signal Propagation in Deep Neural Networks." International Conference on Machine Learning. PMLR, 2022.'
---

Recent work by Baratin et al. (2021) sheds light on an intriguing pattern that occurs during the training of deep neural
networks: some layers align much more with data compared to other layers (where the alignment is defined as the 
normalized euclidean product of the tangent features matrix and the data labels matrix). The curve of the alignment as a 
function of layer index (generally) exhibits a ascent-descent pattern where the maximum is reached for some hidden 
layer. In this work, we provide the first explanation for this phenomenon. We introduce the Equilibrium Hypothesis 
which connects this alignment pattern to signal propagation in deep neural networks. Our experiments demonstrate an 
excellent match with the theoretical predictions.


[Download paper here](http://c1510.github.io/files/FeatureSignal.pdf)
