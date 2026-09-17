Zach Baker

I'm an AI safety researcher interested in fundamental mechanistic interpretability currently working on transformer activation space dynamics across layers.

Current work: Geshkovski et al.'s A Mathematical Perspective on Transformers treats attention as an interacting particle system and proves that tokens collapse into clusters. Their results cover the identity-weight case. I test what happens in networks across training via a developmental interpretability structure.

Random weights follow the theory given in 'Mathematical Perspective': energy rises monotonically, the token cloud collapses. Trained weights don't. Energy monotonicity fails in every model, prompt, and inverse temperature I've tested, and effective rank is maintained instead of collapsing. Measured across GPT-2 (small–XL), ALBERT v2, and BERT. 

See initial write-up here: [Transformers Resist Their Own Architecture](https://www.lesswrong.com/posts/2dA7phbYZGPjhTj9q/transformers-resist-their-own-architecture)
[MetastableStateAnalysis repo](https://github.com/ZachData/MetastableStateAnalysis): experiments, clustering, energy functionals, spectral analysis
[research-vm-infra repo](https://github.com/ZachData/research-vm-infra): the AWS pipeline it all runs on

Also. Analysis of Variational Sparse Autoencoders (arXiv, revision in progress). 

Blue team auditor on Redwood Research's Auditing Sabotage Bench.

Background: Physics and astronomy, UT Austin.

Happy to talk about any of it. Email is on my profile.
