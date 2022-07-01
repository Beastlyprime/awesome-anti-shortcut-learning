# Awesome: anti-Shortcut Learning
A curated list of 'anti-shortcut learning', 'combating spurious correlations/features/attributes', and 'debiasing' related papers. In progress.

## Analysis
- [Which shortcut cues will dnns choose? a study from the parameter-space perspective, arXiv 2021](https://arxiv.org/pdf/2110.03095)
- [Deep Learning Through the Lens of Example Difficulty, NeurIPS 2021](https://arxiv.org/abs/2106.09647).  computational difficulty of making a prediction for a given input. Early layers generalize while later layers memorize; early layers converge faster and networks learn easy data and simple functions first.

## Methods
- [Last Layer Re-Training is Sufficient for Robustness to Spurious Correlations, arXiv 2022](https://arxiv.org/pdf/2204.02937). Just last layer retraining on large ImageNet-trained models can significantly improve robustness. This potentially reduces the issue of spurious correlations to a linear problem.
- [Domain-Adjusted Regression or: ERM May Already Learn Features Sufficient for Out-of-Distribution Generalization, arXiv 2022](https://arxiv.org/abs/2202.06856v1). It is argured that the current bottleneck is not feature learning, but robust regression. ERM produces features which are informative enough that a linear classifier on top of these frozen features is—in principle—capable of generalizing almost as well as if we had access to the test domain when training the entire network.
