# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/agents/base.py

Prompts

```
['act using an AgentBase subclass by calling act with a latent state and optional exploration noise', 'init a latent state for a new episode by calling init_latent_state on an AgentBase subclass', 'train_reconstruct on an AgentBase subclass to get TrainOutput with transition and reward predictions', 'imagine_ahead_noiseless on an AgentBase subclass to plan ahead in the latent space over a horizon', 'posterior_rsample_one_step on an AgentBase subclass to update the latent state given an action and observation', 'build a DenoisedMDP agent with transition, reward, encoder, observation, and actor model configs for an environment', 'create a TransitionModelConfig with custom belief and state sizes for x, y, z latent parts', 'run the imagine_ahead_noiseless method to generate imaginary trajectories using the dynamics model and actor', 'train the DenoisedMDP agent by reconstructing observations and rewards from experience replay data', 'sample the posterior latent state one step using action, next observation, and reward inputs', 'compute GAE lambda returns from imged rewards, value predictions, and a bootstrap tensor', 'temporarily set multiple PyTorch modules to training or eval mode using a context manager', 'perform an optimizer step with optional gradient clipping using a context manager', 'freeze gradients on a list of PyTorch modules within a context manager block', 'wrap a PyTorch optimizer with gradient clipping and state dict save and load support']
```

Usage

```
{'act_agent_base': 'act using an AgentBase subclass by calling act with a latent state and optional exploration noise', 'init_latent_state_agent_base': 'init a latent state for a new episode by calling init_latent_state on an AgentBase subclass', 'train_reconstruct_agent_base': 'train_reconstruct on an AgentBase subclass to get TrainOutput with transition and reward predictions', 'imagine_ahead_noiseless_agent_base': 'imagine_ahead_noiseless on an AgentBase subclass to plan ahead in the latent space over a horizon', 'posterior_rsample_one_step_agent_base': 'posterior_rsample_one_step on an AgentBase subclass to update the latent state given an action and observation'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/agents/denoised_mdp.py

Prompts

```
['act using an AgentBase subclass by calling act with a latent state and optional exploration noise', 'init a latent state for a new episode by calling init_latent_state on an AgentBase subclass', 'train_reconstruct on an AgentBase subclass to get TrainOutput with transition and reward predictions', 'imagine_ahead_noiseless on an AgentBase subclass to plan ahead in the latent space over a horizon', 'posterior_rsample_one_step on an AgentBase subclass to update the latent state given an action and observation', 'build a DenoisedMDP agent with transition, reward, encoder, observation, and actor model configs for an environment', 'create a TransitionModelConfig with custom belief and state sizes for x, y, z latent parts', 'run the imagine_ahead_noiseless method to generate imaginary trajectories using the dynamics model and actor', 'train the DenoisedMDP agent by reconstructing observations and rewards from experience replay data', 'sample the posterior latent state one step using action, next observation, and reward inputs', 'compute GAE lambda returns from imged rewards, value predictions, and a bootstrap tensor', 'temporarily set multiple PyTorch modules to training or eval mode using a context manager', 'perform an optimizer step with optional gradient clipping using a context manager', 'freeze gradients on a list of PyTorch modules within a context manager block', 'wrap a PyTorch optimizer with gradient clipping and state dict save and load support']
```

Usage

```
{'build_DenoisedMDP_agent': 'build a DenoisedMDP agent with transition, reward, encoder, observation, and actor model configs for an environment', 'create_TransitionModelConfig': 'create a TransitionModelConfig with custom belief and state sizes for x, y, z latent parts', 'run_imagine_ahead_noiseless': 'run the imagine_ahead_noiseless method to generate imaginary trajectories using the dynamics model and actor', 'train_reconstruct': 'train the DenoisedMDP agent by reconstructing observations and rewards from experience replay data', 'posterior_rsample_one_step': 'sample the posterior latent state one step using action, next observation, and reward inputs'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/agents/utils.py

Prompts

```
['act using an AgentBase subclass by calling act with a latent state and optional exploration noise', 'init a latent state for a new episode by calling init_latent_state on an AgentBase subclass', 'train_reconstruct on an AgentBase subclass to get TrainOutput with transition and reward predictions', 'imagine_ahead_noiseless on an AgentBase subclass to plan ahead in the latent space over a horizon', 'posterior_rsample_one_step on an AgentBase subclass to update the latent state given an action and observation', 'build a DenoisedMDP agent with transition, reward, encoder, observation, and actor model configs for an environment', 'create a TransitionModelConfig with custom belief and state sizes for x, y, z latent parts', 'run the imagine_ahead_noiseless method to generate imaginary trajectories using the dynamics model and actor', 'train the DenoisedMDP agent by reconstructing observations and rewards from experience replay data', 'sample the posterior latent state one step using action, next observation, and reward inputs', 'compute GAE lambda returns from imged rewards, value predictions, and a bootstrap tensor', 'temporarily set multiple PyTorch modules to training or eval mode using a context manager', 'perform an optimizer step with optional gradient clipping using a context manager', 'freeze gradients on a list of PyTorch modules within a context manager block', 'wrap a PyTorch optimizer with gradient clipping and state dict save and load support']
```

Usage

```
{'compute_lambda_return': 'compute GAE lambda returns from imged rewards, value predictions, and a bootstrap tensor', 'use_training_mode_context': 'temporarily set multiple PyTorch modules to training or eval mode using a context manager', 'use_optim_step_context': 'perform an optimizer step with optional gradient clipping using a context manager', 'use_freeze_parameters': 'freeze gradients on a list of PyTorch modules within a context manager block', 'use_optim_wrapper': 'wrap a PyTorch optimizer with gradient clipping and state dict save and load support'}
```

