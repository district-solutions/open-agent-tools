# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/pwil/adder.py

Prompts

```
['create a PWILAdder instance wrapping a direct RL adder with a WassersteinDistanceRewarder', 'add the first timestep to the PWILAdder which resets the rewarder and stores the observation', 'add an action and next timestep transition with PWIL-substituted rewards to the underlying adder', 'reset the PWILAdder clearing the latest observation and resetting the underlying adder', 'review the PWILAdder class and its reward-substituting wrapper pattern for experience replay', 'build a PWIL agent builder wrapping an RL agent with demonstration-based imitation learning configuration', 'create a function that prefills a replay buffer adder with expert demonstration transitions', 'create a PWIL adder that substitutes imitation reward using Wasserstein distance rewarder', 'build a dataset iterator from a Reverb replay client with optional demonstration prefilling in a background thread', 'build a PWIL learner by delegating to the underlying RL agent builder with shared networks and dataset', 'build a WassersteinDistanceRewarder with expert demonstrations iterator and episode length parameters', 'create a WassersteinDistanceRewarder that uses actions for distance computation with custom alpha and beta', 'reset the WassersteinDistanceRewarder to make all expert transitions available and reinitialize weights', 'compute PWIL reward for an observation and action pair using append_and_compute_reward method', 'vectorize expert demonstrations into a numpy array for Wasserstein distance reward computation']
```

Usage

```
{'create_pwil_adder': 'create a PWILAdder instance wrapping a direct RL adder with a WassersteinDistanceRewarder', 'add_first_timestep': 'add the first timestep to the PWILAdder which resets the rewarder and stores the observation', 'add_transition': 'add an action and next timestep transition with PWIL-substituted rewards to the underlying adder', 'reset_adder': 'reset the PWILAdder clearing the latest observation and resetting the underlying adder', 'review_pwil_adder_class': 'review the PWILAdder class and its reward-substituting wrapper pattern for experience replay'}
```

## File: google-deepmind_acme/acme/agents/jax/pwil/builder.py

Prompts

```
['create a PWILAdder instance wrapping a direct RL adder with a WassersteinDistanceRewarder', 'add the first timestep to the PWILAdder which resets the rewarder and stores the observation', 'add an action and next timestep transition with PWIL-substituted rewards to the underlying adder', 'reset the PWILAdder clearing the latest observation and resetting the underlying adder', 'review the PWILAdder class and its reward-substituting wrapper pattern for experience replay', 'build a PWIL agent builder wrapping an RL agent with demonstration-based imitation learning configuration', 'create a function that prefills a replay buffer adder with expert demonstration transitions', 'create a PWIL adder that substitutes imitation reward using Wasserstein distance rewarder', 'build a dataset iterator from a Reverb replay client with optional demonstration prefilling in a background thread', 'build a PWIL learner by delegating to the underlying RL agent builder with shared networks and dataset', 'build a WassersteinDistanceRewarder with expert demonstrations iterator and episode length parameters', 'create a WassersteinDistanceRewarder that uses actions for distance computation with custom alpha and beta', 'reset the WassersteinDistanceRewarder to make all expert transitions available and reinitialize weights', 'compute PWIL reward for an observation and action pair using append_and_compute_reward method', 'vectorize expert demonstrations into a numpy array for Wasserstein distance reward computation']
```

Usage

```
{'build_PWILBuilder': 'build a PWIL agent builder wrapping an RL agent with demonstration-based imitation learning configuration', 'create_prefill_demonstrations': 'create a function that prefills a replay buffer adder with expert demonstration transitions', 'make_PWIL_adder': 'create a PWIL adder that substitutes imitation reward using Wasserstein distance rewarder', 'make_dataset_iterator': 'build a dataset iterator from a Reverb replay client with optional demonstration prefilling in a background thread', 'make_PWIL_learner': 'build a PWIL learner by delegating to the underlying RL agent builder with shared networks and dataset'}
```

## File: google-deepmind_acme/acme/agents/jax/pwil/rewarder.py

Prompts

```
['create a PWILAdder instance wrapping a direct RL adder with a WassersteinDistanceRewarder', 'add the first timestep to the PWILAdder which resets the rewarder and stores the observation', 'add an action and next timestep transition with PWIL-substituted rewards to the underlying adder', 'reset the PWILAdder clearing the latest observation and resetting the underlying adder', 'review the PWILAdder class and its reward-substituting wrapper pattern for experience replay', 'build a PWIL agent builder wrapping an RL agent with demonstration-based imitation learning configuration', 'create a function that prefills a replay buffer adder with expert demonstration transitions', 'create a PWIL adder that substitutes imitation reward using Wasserstein distance rewarder', 'build a dataset iterator from a Reverb replay client with optional demonstration prefilling in a background thread', 'build a PWIL learner by delegating to the underlying RL agent builder with shared networks and dataset', 'build a WassersteinDistanceRewarder with expert demonstrations iterator and episode length parameters', 'create a WassersteinDistanceRewarder that uses actions for distance computation with custom alpha and beta', 'reset the WassersteinDistanceRewarder to make all expert transitions available and reinitialize weights', 'compute PWIL reward for an observation and action pair using append_and_compute_reward method', 'vectorize expert demonstrations into a numpy array for Wasserstein distance reward computation']
```

Usage

```
{'build_wasserstein_rewarder': 'build a WassersteinDistanceRewarder with expert demonstrations iterator and episode length parameters', 'create_rewarder_with_actions': 'create a WassersteinDistanceRewarder that uses actions for distance computation with custom alpha and beta', 'reset_rewarder_weights': 'reset the WassersteinDistanceRewarder to make all expert transitions available and reinitialize weights', 'compute_trajectory_reward': 'compute PWIL reward for an observation and action pair using append_and_compute_reward method', 'vectorize_demonstrations': 'vectorize expert demonstrations into a numpy array for Wasserstein distance reward computation'}
```

