## Welcome to Github Pages of InfoGainBNN

Reproduce our results: [Github](https://github.com/InfoGainBNN/InfoGainBNN.github.io)

Check out our main paper: [Bayesian Learning with Information Gain Provably Bounds Risk for a Robust Adversarial Defense](https://proceedings.mlr.press/v162/doan22a/doan22a.pdf)


### Abstract

We present a new algorithm to learn a deep neural network model robust against adversarial attacks. Previous algorithms demonstrate an adversarially trained Bayesian Neural Network (BNN) provides improved robustness. We recognize the learning approach for approximating the multi-modal posterior distribution of an adversarially trained Bayesian model can lead to mode collapse; consequently, the model's achievements in robustness and performance are sub-optimal. Instead, we first propose preventing mode collapse to better approximate the multi-modal posterior distribution. Second, based on the intuition that a robust model should ignore perturbations and only consider the informative content of the input, we conceptualize and formulate an information gain objective to measure and force the information learned from both benign and adversarial training instances to be similar. Importantly. we prove and demonstrate that minimizing the information gain objective allows the adversarial risk to approach the conventional empirical risk. We believe our efforts provide a step towards a basis for a principled method of adversarially training BNNs. Our extensive experimental results demonstrate significantly improved robustness up to 20% compared with adversarial training and Adv-BNN under PGD attacks with 0.035 distortion on both CIFAR-10 and STL-10 dataset.
