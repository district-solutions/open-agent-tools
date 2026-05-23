# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/ldm/modules/distributions/distributions.py

Prompts

```
['create a DiagonalGaussianDistribution from parameters tensor with mean and logvar split along dim 1', 'sample from a DiagonalGaussianDistribution using mean plus standard deviation times random noise', 'compute the KL divergence between two DiagonalGaussianDistribution objects or against a standard normal prior', 'compute the KL divergence between two gaussians given mean and logvar tensors with automatic broadcasting', 'compute the negative log likelihood of a sample under a DiagonalGaussianDistribution']
```

Usage

```
{'create_diagonal_gaussian_distribution': 'create a DiagonalGaussianDistribution from parameters tensor with mean and logvar split along dim 1', 'sample_from_gaussian_distribution': 'sample from a DiagonalGaussianDistribution using mean plus standard deviation times random noise', 'compute_kl_divergence': 'compute the KL divergence between two DiagonalGaussianDistribution objects or against a standard normal prior', 'compute_normal_kl_divergence': 'compute the KL divergence between two gaussians given mean and logvar tensors with automatic broadcasting', 'compute_negative_log_likelihood': 'compute the negative log likelihood of a sample under a DiagonalGaussianDistribution'}
```

