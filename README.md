# Self Supervised Learning for Graph Classification

## Motivation

* Social networks, Molecular sciences, Transportation, E-commerce
* Reliance on labeled data causes poor generalization and less robustness

## SSL

* Designing the pretext task (contrast based, auxilary etc.)
* From pretext to downstream task
* Comparisons of SSL methods' performance among different domains (text, image and graphs)
* OOD Generalization and SSL

## Related Works

* Test Time Adaptation strategy

## Graph Adversarial Pseudo Group Contrast

* Graph Pseudo-Positive Samples
* Adversarial Learnable Augmenter

## Performance Evaluation and Problems

* Contrastive learning as self supervised task during testing improves test performance
* ALA contributes more than GPPS but when combined performs the best on average
* Experiments on molecular scaffold OOD dataset demonstrated state-of-the-art performance on GNNs
* Access to test distribution in real datasets?
* Can the parametrized augmenter generalize to other learnable graph generators?
* GCL projector and MLP in augmenter initialization?

## References
[GraphTTA](https://arxiv.org/abs/2208.09126 "Test Time Adaptation on Graph Neural Networks")
