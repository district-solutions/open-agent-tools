# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/rl/subspace_of_policies/agents.py

Prompts

```
['create a Normalizer agent to normalize Brax environment observations using pre-trained mean and std', 'create an AlphaAgent to sample alpha coefficients using Dirichlet or Categorical distributions for policy interpolation', 'create a LoPAgent to interpolate between multiple policy models using alpha weights and output actions', 'create a CriticAgent to evaluate state-alpha pairs and output scalar Q-value estimates', 'review the LoPAgent cosine_similarity method to compute similarity between two policy model anchors', 'run the RL policy evaluation across multiple HalfCheetah environments using a loaded policy and normalizer model', 'generate k-shot interpolation points using categorical, bezier, or Dirichlet distribution geometry for policy mixing', 'create a boolean mask from a done tensor to exclude timesteps after episode termination for reward aggregation', 'run the Hydra-configured main entry point that initializes CUDA and executes the full evaluation pipeline', 'review the run_eval function that loads policy models, generates alpha weights, and evaluates agents across environments', 'create a Linear layer with N anchor networks for subspace policy interpolation', 'build a Linear layer where all anchors share the same initial weights via same_init', 'run forward pass on Linear layer by passing input tensor and alpha mixing weights', 'create a Sequential model that chains Linear and standard modules with time-aware forwarding', 'run forward pass on Sequential model passing input and time parameter t through all modules', 'run the LINE PPO training loop with action agent, critic agent, logger, and config', 'clip gradient norms on model parameters to a specified maximum value', 'review the LINE PPO training loop for policy update, critic update, and trajectory acquisition logic', 'refactor the clip_grad function to support different gradient clipping strategies']
```

Usage

```
{'create_normalizer_agent': 'create a Normalizer agent to normalize Brax environment observations using pre-trained mean and std', 'create_alpha_agent': 'create an AlphaAgent to sample alpha coefficients using Dirichlet or Categorical distributions for policy interpolation', 'create_lop_agent': 'create a LoPAgent to interpolate between multiple policy models using alpha weights and output actions', 'create_critic_agent': 'create a CriticAgent to evaluate state-alpha pairs and output scalar Q-value estimates', 'review_cosine_similarity': 'review the LoPAgent cosine_similarity method to compute similarity between two policy model anchors'}
```

## File: facebookresearch_salina/salina_examples/rl/subspace_of_policies/evaluation.py

Prompts

```
['create a Normalizer agent to normalize Brax environment observations using pre-trained mean and std', 'create an AlphaAgent to sample alpha coefficients using Dirichlet or Categorical distributions for policy interpolation', 'create a LoPAgent to interpolate between multiple policy models using alpha weights and output actions', 'create a CriticAgent to evaluate state-alpha pairs and output scalar Q-value estimates', 'review the LoPAgent cosine_similarity method to compute similarity between two policy model anchors', 'run the RL policy evaluation across multiple HalfCheetah environments using a loaded policy and normalizer model', 'generate k-shot interpolation points using categorical, bezier, or Dirichlet distribution geometry for policy mixing', 'create a boolean mask from a done tensor to exclude timesteps after episode termination for reward aggregation', 'run the Hydra-configured main entry point that initializes CUDA and executes the full evaluation pipeline', 'review the run_eval function that loads policy models, generates alpha weights, and evaluates agents across environments', 'create a Linear layer with N anchor networks for subspace policy interpolation', 'build a Linear layer where all anchors share the same initial weights via same_init', 'run forward pass on Linear layer by passing input tensor and alpha mixing weights', 'create a Sequential model that chains Linear and standard modules with time-aware forwarding', 'run forward pass on Sequential model passing input and time parameter t through all modules', 'run the LINE PPO training loop with action agent, critic agent, logger, and config', 'clip gradient norms on model parameters to a specified maximum value', 'review the LINE PPO training loop for policy update, critic update, and trajectory acquisition logic', 'refactor the clip_grad function to support different gradient clipping strategies']
```

Usage

```
{'run_evaluation': 'run the RL policy evaluation across multiple HalfCheetah environments using a loaded policy and normalizer model', 'generate_k_shot_points': 'generate k-shot interpolation points using categorical, bezier, or Dirichlet distribution geometry for policy mixing', 'generate_mask': 'create a boolean mask from a done tensor to exclude timesteps after episode termination for reward aggregation', 'run_main': 'run the Hydra-configured main entry point that initializes CUDA and executes the full evaluation pipeline', 'review_run_eval': 'review the run_eval function that loads policy models, generates alpha weights, and evaluates agents across environments'}
```

## File: facebookresearch_salina/salina_examples/rl/subspace_of_policies/subspace.py

Prompts

```
['create a Normalizer agent to normalize Brax environment observations using pre-trained mean and std', 'create an AlphaAgent to sample alpha coefficients using Dirichlet or Categorical distributions for policy interpolation', 'create a LoPAgent to interpolate between multiple policy models using alpha weights and output actions', 'create a CriticAgent to evaluate state-alpha pairs and output scalar Q-value estimates', 'review the LoPAgent cosine_similarity method to compute similarity between two policy model anchors', 'run the RL policy evaluation across multiple HalfCheetah environments using a loaded policy and normalizer model', 'generate k-shot interpolation points using categorical, bezier, or Dirichlet distribution geometry for policy mixing', 'create a boolean mask from a done tensor to exclude timesteps after episode termination for reward aggregation', 'run the Hydra-configured main entry point that initializes CUDA and executes the full evaluation pipeline', 'review the run_eval function that loads policy models, generates alpha weights, and evaluates agents across environments', 'create a Linear layer with N anchor networks for subspace policy interpolation', 'build a Linear layer where all anchors share the same initial weights via same_init', 'run forward pass on Linear layer by passing input tensor and alpha mixing weights', 'create a Sequential model that chains Linear and standard modules with time-aware forwarding', 'run forward pass on Sequential model passing input and time parameter t through all modules', 'run the LINE PPO training loop with action agent, critic agent, logger, and config', 'clip gradient norms on model parameters to a specified maximum value', 'review the LINE PPO training loop for policy update, critic update, and trajectory acquisition logic', 'refactor the clip_grad function to support different gradient clipping strategies']
```

Usage

```
{'create_Linear_layer': 'create a Linear layer with N anchor networks for subspace policy interpolation', 'build_Linear_same_init': 'build a Linear layer where all anchors share the same initial weights via same_init', 'run_Linear_forward': 'run forward pass on Linear layer by passing input tensor and alpha mixing weights', 'create_Sequential_model': 'create a Sequential model that chains Linear and standard modules with time-aware forwarding', 'run_Sequential_forward': 'run forward pass on Sequential model passing input and time parameter t through all modules'}
```

## File: facebookresearch_salina/salina_examples/rl/subspace_of_policies/train.py

Prompts

```
['create a Normalizer agent to normalize Brax environment observations using pre-trained mean and std', 'create an AlphaAgent to sample alpha coefficients using Dirichlet or Categorical distributions for policy interpolation', 'create a LoPAgent to interpolate between multiple policy models using alpha weights and output actions', 'create a CriticAgent to evaluate state-alpha pairs and output scalar Q-value estimates', 'review the LoPAgent cosine_similarity method to compute similarity between two policy model anchors', 'run the RL policy evaluation across multiple HalfCheetah environments using a loaded policy and normalizer model', 'generate k-shot interpolation points using categorical, bezier, or Dirichlet distribution geometry for policy mixing', 'create a boolean mask from a done tensor to exclude timesteps after episode termination for reward aggregation', 'run the Hydra-configured main entry point that initializes CUDA and executes the full evaluation pipeline', 'review the run_eval function that loads policy models, generates alpha weights, and evaluates agents across environments', 'create a Linear layer with N anchor networks for subspace policy interpolation', 'build a Linear layer where all anchors share the same initial weights via same_init', 'run forward pass on Linear layer by passing input tensor and alpha mixing weights', 'create a Sequential model that chains Linear and standard modules with time-aware forwarding', 'run forward pass on Sequential model passing input and time parameter t through all modules', 'run the LINE PPO training loop with action agent, critic agent, logger, and config', 'clip gradient norms on model parameters to a specified maximum value', 'review the LINE PPO training loop for policy update, critic update, and trajectory acquisition logic', 'refactor the clip_grad function to support different gradient clipping strategies']
```

Usage

```
{'run_LINE_PPO': 'run the LINE PPO training loop with action agent, critic agent, logger, and config', 'run_main': 'run the main entry point that instantiates agents and starts LINE PPO training via Hydra', 'clip_grad': 'clip gradient norms on model parameters to a specified maximum value', 'review_run_line_ppo': 'review the LINE PPO training loop for policy update, critic update, and trajectory acquisition logic', 'refactor_clip_grad': 'refactor the clip_grad function to support different gradient clipping strategies'}
```

