# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/jax/losses/impala.py

Prompts

```
['build an entropy-regularized IMPALA loss function with V-trace for actor-critic reinforcement learning', 'create a critic loss using V-trace TD error with importance sampling ratios', 'compute the policy gradient loss using categorical logits and V-trace advantages', 'calculate entropy regularization loss for policy exploration in reinforcement learning', 'configure IMPALA loss with discount rate, reward clipping, baseline cost, and entropy cost', 'test the IMPALA loss function returns scalar loss and metrics using a recurrent actor-critic network', 'test the IMPALA loss function with a Reverb replay sample containing batched step data', 'test a Haiku LSTM-based recurrent actor-critic network using dynamic unroll for sequence processing', 'test tree_map utility to tile observations, actions, and rewards across batch and sequence dimensions', 'test IMPALA loss function initialization with Haiku parameters and a discount factor of 0.99', 'build a python module to compute the decoupled MPO loss for reinforcement learning policy optimization', 'create initial MPO parameters with temperature and dual variables for a given action dimension', 'compute normalized importance weights and temperature loss from Q-values for policy optimization', 'compute cross-entropy loss between online policy and reweighted target policy using normalized weights', 'clip MPO parameters to enforce minimum log temperature and log alpha constraints', 'build a WPO loss instance with decoupled KL constraints for mean and stddev of a Gaussian policy', 'compute the Wasserstein policy gradient loss using sampled actions and Q-value gradients', 'compute the alpha-weighted KL penalty and dual loss for Lagrange multiplier adaptation', 'adapt a normal distribution to scale gradients by variance for natural gradient optimization', 'clip WPO dual variable parameters to prevent log alpha values from going below the minimum threshold']
```

Usage

```
{'build_impala_loss_function': 'build an entropy-regularized IMPALA loss function with V-trace for actor-critic reinforcement learning', 'create_vtrace_critic_loss': 'create a critic loss using V-trace TD error with importance sampling ratios', 'compute_policy_gradient_loss': 'compute the policy gradient loss using categorical logits and V-trace advantages', 'calculate_entropy_regularization': 'calculate entropy regularization loss for policy exploration in reinforcement learning', 'configure_impala_loss_parameters': 'configure IMPALA loss with discount rate, reward clipping, baseline cost, and entropy cost'}
```

## File: google-deepmind_acme/acme/jax/losses/impala_test.py

Prompts

```
['build an entropy-regularized IMPALA loss function with V-trace for actor-critic reinforcement learning', 'create a critic loss using V-trace TD error with importance sampling ratios', 'compute the policy gradient loss using categorical logits and V-trace advantages', 'calculate entropy regularization loss for policy exploration in reinforcement learning', 'configure IMPALA loss with discount rate, reward clipping, baseline cost, and entropy cost', 'test the IMPALA loss function returns scalar loss and metrics using a recurrent actor-critic network', 'test the IMPALA loss function with a Reverb replay sample containing batched step data', 'test a Haiku LSTM-based recurrent actor-critic network using dynamic unroll for sequence processing', 'test tree_map utility to tile observations, actions, and rewards across batch and sequence dimensions', 'test IMPALA loss function initialization with Haiku parameters and a discount factor of 0.99', 'build a python module to compute the decoupled MPO loss for reinforcement learning policy optimization', 'create initial MPO parameters with temperature and dual variables for a given action dimension', 'compute normalized importance weights and temperature loss from Q-values for policy optimization', 'compute cross-entropy loss between online policy and reweighted target policy using normalized weights', 'clip MPO parameters to enforce minimum log temperature and log alpha constraints', 'build a WPO loss instance with decoupled KL constraints for mean and stddev of a Gaussian policy', 'compute the Wasserstein policy gradient loss using sampled actions and Q-value gradients', 'compute the alpha-weighted KL penalty and dual loss for Lagrange multiplier adaptation', 'adapt a normal distribution to scale gradients by variance for natural gradient optimization', 'clip WPO dual variable parameters to prevent log alpha values from going below the minimum threshold']
```

Usage

```
{'test_impala_loss_shapes': 'test the IMPALA loss function returns scalar loss and metrics using a recurrent actor-critic network', 'test_impala_with_reverb_sample': 'test the IMPALA loss function with a Reverb replay sample containing batched step data', 'test_haiku_lstm_unroll': 'test a Haiku LSTM-based recurrent actor-critic network using dynamic unroll for sequence processing', 'test_tree_map_batching': 'test tree_map utility to tile observations, actions, and rewards across batch and sequence dimensions', 'test_impala_loss_initialization': 'test IMPALA loss function initialization with Haiku parameters and a discount factor of 0.99'}
```

## File: google-deepmind_acme/acme/jax/losses/mpo.py

Prompts

```
['build an entropy-regularized IMPALA loss function with V-trace for actor-critic reinforcement learning', 'create a critic loss using V-trace TD error with importance sampling ratios', 'compute the policy gradient loss using categorical logits and V-trace advantages', 'calculate entropy regularization loss for policy exploration in reinforcement learning', 'configure IMPALA loss with discount rate, reward clipping, baseline cost, and entropy cost', 'test the IMPALA loss function returns scalar loss and metrics using a recurrent actor-critic network', 'test the IMPALA loss function with a Reverb replay sample containing batched step data', 'test a Haiku LSTM-based recurrent actor-critic network using dynamic unroll for sequence processing', 'test tree_map utility to tile observations, actions, and rewards across batch and sequence dimensions', 'test IMPALA loss function initialization with Haiku parameters and a discount factor of 0.99', 'build a python module to compute the decoupled MPO loss for reinforcement learning policy optimization', 'create initial MPO parameters with temperature and dual variables for a given action dimension', 'compute normalized importance weights and temperature loss from Q-values for policy optimization', 'compute cross-entropy loss between online policy and reweighted target policy using normalized weights', 'clip MPO parameters to enforce minimum log temperature and log alpha constraints', 'build a WPO loss instance with decoupled KL constraints for mean and stddev of a Gaussian policy', 'compute the Wasserstein policy gradient loss using sampled actions and Q-value gradients', 'compute the alpha-weighted KL penalty and dual loss for Lagrange multiplier adaptation', 'adapt a normal distribution to scale gradients by variance for natural gradient optimization', 'clip WPO dual variable parameters to prevent log alpha values from going below the minimum threshold']
```

Usage

```
{'build_mpo_loss': 'build a python module to compute the decoupled MPO loss for reinforcement learning policy optimization', 'create_mpo_params': 'create initial MPO parameters with temperature and dual variables for a given action dimension', 'compute_weights_temperature_loss': 'compute normalized importance weights and temperature loss from Q-values for policy optimization', 'compute_cross_entropy_loss': 'compute cross-entropy loss between online policy and reweighted target policy using normalized weights', 'clip_mpo_params': 'clip MPO parameters to enforce minimum log temperature and log alpha constraints'}
```

## File: google-deepmind_acme/acme/jax/losses/wpo.py

Prompts

```
['build an entropy-regularized IMPALA loss function with V-trace for actor-critic reinforcement learning', 'create a critic loss using V-trace TD error with importance sampling ratios', 'compute the policy gradient loss using categorical logits and V-trace advantages', 'calculate entropy regularization loss for policy exploration in reinforcement learning', 'configure IMPALA loss with discount rate, reward clipping, baseline cost, and entropy cost', 'test the IMPALA loss function returns scalar loss and metrics using a recurrent actor-critic network', 'test the IMPALA loss function with a Reverb replay sample containing batched step data', 'test a Haiku LSTM-based recurrent actor-critic network using dynamic unroll for sequence processing', 'test tree_map utility to tile observations, actions, and rewards across batch and sequence dimensions', 'test IMPALA loss function initialization with Haiku parameters and a discount factor of 0.99', 'build a python module to compute the decoupled MPO loss for reinforcement learning policy optimization', 'create initial MPO parameters with temperature and dual variables for a given action dimension', 'compute normalized importance weights and temperature loss from Q-values for policy optimization', 'compute cross-entropy loss between online policy and reweighted target policy using normalized weights', 'clip MPO parameters to enforce minimum log temperature and log alpha constraints', 'build a WPO loss instance with decoupled KL constraints for mean and stddev of a Gaussian policy', 'compute the Wasserstein policy gradient loss using sampled actions and Q-value gradients', 'compute the alpha-weighted KL penalty and dual loss for Lagrange multiplier adaptation', 'adapt a normal distribution to scale gradients by variance for natural gradient optimization', 'clip WPO dual variable parameters to prevent log alpha values from going below the minimum threshold']
```

Usage

```
{'build_wpo_loss': 'build a WPO loss instance with decoupled KL constraints for mean and stddev of a Gaussian policy', 'compute_wpo_loss_function': 'compute the Wasserstein policy gradient loss using sampled actions and Q-value gradients', 'compute_parametric_kl_penalty': 'compute the alpha-weighted KL penalty and dual loss for Lagrange multiplier adaptation', 'natural_gradient_adaptor': 'adapt a normal distribution to scale gradients by variance for natural gradient optimization', 'clip_wpo_params': 'clip WPO dual variable parameters to prevent log alpha values from going below the minimum threshold'}
```

