# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/inference/proposer/nmc/single_site_half_space_nmc_proposer.py

Prompts

```
['build a SingleSiteHalfSpaceNMCProposer instance for a given RVIdentifier node to propose new values', 'compute the Gamma distribution alpha and beta parameters from a World using Hessian-based gradients', 'get the Gamma proposal distribution for a node in a World with cached gradient optimization', 'review the compute_alpha_beta method to understand how Hessian diagonal and first gradient derive Gamma parameters', 'refactor the get_proposal_distribution method to customize fallback behavior when alpha or beta are invalid', 'build a SingleSiteRealSpaceNMCProposer instance with a node, alpha, and beta parameters for MCMC inference', 'sample a fractional distance from a Beta distribution using alpha and beta parameters for the proposer learning rate', 'compute alpha and beta priors from accepted learning rates using the method of moments for adaptive MCMC', 'adapt the proposer alpha and beta parameters based on whether a proposed sample was accepted or rejected', 'compute the Dirichlet alpha parameters for a node using the Hessian of log probability in a world', 'review the compute_alpha method to understand how Hessian diagonal minus max values predict Dirichlet alpha', 'review the get_proposal_distribution method to understand caching logic and fallback to ancestral proposer']
```

Usage

```
{'build_proposer': 'build a SingleSiteHalfSpaceNMCProposer instance for a given RVIdentifier node to propose new values', 'compute_alpha_beta': 'compute the Gamma distribution alpha and beta parameters from a World using Hessian-based gradients', 'get_proposal_distribution': 'get the Gamma proposal distribution for a node in a World with cached gradient optimization', 'review_compute_alpha_beta': 'review the compute_alpha_beta method to understand how Hessian diagonal and first gradient derive Gamma parameters', 'refactor_get_proposal_distribution': 'refactor the get_proposal_distribution method to customize fallback behavior when alpha or beta are invalid'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/inference/proposer/nmc/single_site_real_space_nmc_proposer.py

Prompts

```
['build a SingleSiteHalfSpaceNMCProposer instance for a given RVIdentifier node to propose new values', 'compute the Gamma distribution alpha and beta parameters from a World using Hessian-based gradients', 'get the Gamma proposal distribution for a node in a World with cached gradient optimization', 'review the compute_alpha_beta method to understand how Hessian diagonal and first gradient derive Gamma parameters', 'refactor the get_proposal_distribution method to customize fallback behavior when alpha or beta are invalid', 'build a SingleSiteRealSpaceNMCProposer instance with a node, alpha, and beta parameters for MCMC inference', 'sample a fractional distance from a Beta distribution using alpha and beta parameters for the proposer learning rate', 'compute alpha and beta priors from accepted learning rates using the method of moments for adaptive MCMC', 'adapt the proposer alpha and beta parameters based on whether a proposed sample was accepted or rejected', 'compute the Dirichlet alpha parameters for a node using the Hessian of log probability in a world', 'review the compute_alpha method to understand how Hessian diagonal minus max values predict Dirichlet alpha', 'review the get_proposal_distribution method to understand caching logic and fallback to ancestral proposer']
```

Usage

```
{'build_NMC_proposer': 'build a SingleSiteRealSpaceNMCProposer instance with a node, alpha, and beta parameters for MCMC inference', 'get_proposal_distribution': 'get the proposal distribution for a node in a world using Newtonian Monte Carlo with Hessian-based second-order gradients', 'sample_frac_dist': 'sample a fractional distance from a Beta distribution using alpha and beta parameters for the proposer learning rate', 'compute_beta_priors': 'compute alpha and beta priors from accepted learning rates using the method of moments for adaptive MCMC', 'do_adaptation': 'adapt the proposer alpha and beta parameters based on whether a proposed sample was accepted or rejected'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/inference/proposer/nmc/single_site_simplex_space_nmc_proposer.py

Prompts

```
['build a SingleSiteHalfSpaceNMCProposer instance for a given RVIdentifier node to propose new values', 'compute the Gamma distribution alpha and beta parameters from a World using Hessian-based gradients', 'get the Gamma proposal distribution for a node in a World with cached gradient optimization', 'review the compute_alpha_beta method to understand how Hessian diagonal and first gradient derive Gamma parameters', 'refactor the get_proposal_distribution method to customize fallback behavior when alpha or beta are invalid', 'build a SingleSiteRealSpaceNMCProposer instance with a node, alpha, and beta parameters for MCMC inference', 'sample a fractional distance from a Beta distribution using alpha and beta parameters for the proposer learning rate', 'compute alpha and beta priors from accepted learning rates using the method of moments for adaptive MCMC', 'adapt the proposer alpha and beta parameters based on whether a proposed sample was accepted or rejected', 'compute the Dirichlet alpha parameters for a node using the Hessian of log probability in a world', 'review the compute_alpha method to understand how Hessian diagonal minus max values predict Dirichlet alpha', 'review the get_proposal_distribution method to understand caching logic and fallback to ancestral proposer']
```

Usage

```
{'build_proposer': 'build a SingleSiteSimplexSpaceNMCProposer instance for a given RVIdentifier node with an optional transform', 'compute_alpha': 'compute the Dirichlet alpha parameters for a node using the Hessian of log probability in a world', 'get_proposal_distribution': 'get the Transformed Dirichlet proposal distribution for a node in a given world', 'review_compute_alpha': 'review the compute_alpha method to understand how Hessian diagonal minus max values predict Dirichlet alpha', 'review_get_proposal_distribution': 'review the get_proposal_distribution method to understand caching logic and fallback to ancestral proposer'}
```

