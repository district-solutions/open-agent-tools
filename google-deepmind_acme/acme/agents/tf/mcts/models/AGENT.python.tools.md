# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/mcts/models/base.py

Prompts

```
['build a python class that subclasses Model and implements load_checkpoint, save_checkpoint, update, reset, and needs_reset', 'implement the update method to process a timestep, action, and next_timestep for MCTS planning', 'create a model subclass that saves and loads checkpoints to reset state after rollouts', 'build a model subclass that resets to an optional initial observation state for MCTS', 'implement the needs_reset property to signal when the MCTS model requires a reset', 'build an MLPTransitionModel that predicts next state, reward, and discount from state and action inputs', 'create an MLPModel with replay buffer, transition model, and Adam optimizer for environment modeling', 'run a model step to predict the next state, reward, and termination given an action', 'update the model by adding a transition to replay and performing SGD on a sampled batch', 'save and load the model checkpoint to persist and restore the internal model state', 'create a Simulator instance by passing a dm_env.Environment to wrap it for MCTS rollouts', 'step the Simulator with an action to get the next dm_env.TimeStep from the wrapped environment', 'reset the Simulator environment to start a new episode and clear the needs_reset flag', 'get the observation_spec and action_spec from the Simulator to understand the environment interface', 'test that the Simulator model matches the ground truth environment across multiple episodes', 'test that save_checkpoint and load_checkpoint correctly restore the Simulator state', 'run the absltest test suite for the MCTS Simulator model fidelity and checkpointing', 'compare two dm_env TimeStep objects for matching reward, discount, step_type, and observation', 'review the Simulator class that wraps a dm_env environment as an MCTS-compatible model']
```

Usage

```
{'build_mcts_model_subclass': 'build a python class that subclasses Model and implements load_checkpoint, save_checkpoint, update, reset, and needs_reset', 'implement_model_update': 'implement the update method to process a timestep, action, and next_timestep for MCTS planning', 'create_model_checkpoint_system': 'create a model subclass that saves and loads checkpoints to reset state after rollouts', 'build_model_reset_logic': 'build a model subclass that resets to an optional initial observation state for MCTS', 'implement_needs_reset_property': 'implement the needs_reset property to signal when the MCTS model requires a reset'}
```

## File: google-deepmind_acme/acme/agents/tf/mcts/models/mlp.py

Prompts

```
['build a python class that subclasses Model and implements load_checkpoint, save_checkpoint, update, reset, and needs_reset', 'implement the update method to process a timestep, action, and next_timestep for MCTS planning', 'create a model subclass that saves and loads checkpoints to reset state after rollouts', 'build a model subclass that resets to an optional initial observation state for MCTS', 'implement the needs_reset property to signal when the MCTS model requires a reset', 'build an MLPTransitionModel that predicts next state, reward, and discount from state and action inputs', 'create an MLPModel with replay buffer, transition model, and Adam optimizer for environment modeling', 'run a model step to predict the next state, reward, and termination given an action', 'update the model by adding a transition to replay and performing SGD on a sampled batch', 'save and load the model checkpoint to persist and restore the internal model state', 'create a Simulator instance by passing a dm_env.Environment to wrap it for MCTS rollouts', 'step the Simulator with an action to get the next dm_env.TimeStep from the wrapped environment', 'reset the Simulator environment to start a new episode and clear the needs_reset flag', 'get the observation_spec and action_spec from the Simulator to understand the environment interface', 'test that the Simulator model matches the ground truth environment across multiple episodes', 'test that save_checkpoint and load_checkpoint correctly restore the Simulator state', 'run the absltest test suite for the MCTS Simulator model fidelity and checkpointing', 'compare two dm_env TimeStep objects for matching reward, discount, step_type, and observation', 'review the Simulator class that wraps a dm_env environment as an MCTS-compatible model']
```

Usage

```
{'build_mlp_transition_model': 'build an MLPTransitionModel that predicts next state, reward, and discount from state and action inputs', 'create_mlp_model': 'create an MLPModel with replay buffer, transition model, and Adam optimizer for environment modeling', 'run_model_step': 'run a model step to predict the next state, reward, and termination given an action', 'train_model_with_update': 'update the model by adding a transition to replay and performing SGD on a sampled batch', 'save_and_load_checkpoint': 'save and load the model checkpoint to persist and restore the internal model state'}
```

## File: google-deepmind_acme/acme/agents/tf/mcts/models/simulator.py

Prompts

```
['build a python class that subclasses Model and implements load_checkpoint, save_checkpoint, update, reset, and needs_reset', 'implement the update method to process a timestep, action, and next_timestep for MCTS planning', 'create a model subclass that saves and loads checkpoints to reset state after rollouts', 'build a model subclass that resets to an optional initial observation state for MCTS', 'implement the needs_reset property to signal when the MCTS model requires a reset', 'build an MLPTransitionModel that predicts next state, reward, and discount from state and action inputs', 'create an MLPModel with replay buffer, transition model, and Adam optimizer for environment modeling', 'run a model step to predict the next state, reward, and termination given an action', 'update the model by adding a transition to replay and performing SGD on a sampled batch', 'save and load the model checkpoint to persist and restore the internal model state', 'create a Simulator instance by passing a dm_env.Environment to wrap it for MCTS rollouts', 'step the Simulator with an action to get the next dm_env.TimeStep from the wrapped environment', 'reset the Simulator environment to start a new episode and clear the needs_reset flag', 'get the observation_spec and action_spec from the Simulator to understand the environment interface', 'test that the Simulator model matches the ground truth environment across multiple episodes', 'test that save_checkpoint and load_checkpoint correctly restore the Simulator state', 'run the absltest test suite for the MCTS Simulator model fidelity and checkpointing', 'compare two dm_env TimeStep objects for matching reward, discount, step_type, and observation', 'review the Simulator class that wraps a dm_env environment as an MCTS-compatible model']
```

Usage

```
{'create_simulator_from_env': 'create a Simulator instance by passing a dm_env.Environment to wrap it for MCTS rollouts', 'step_simulator_action': 'step the Simulator with an action to get the next dm_env.TimeStep from the wrapped environment', 'reset_simulator_environment': 'reset the Simulator environment to start a new episode and clear the needs_reset flag', 'save_and_load_checkpoint': 'save a checkpoint of the Simulator state and load it later to restore the environment for rollouts', 'get_observation_and_action_specs': 'get the observation_spec and action_spec from the Simulator to understand the environment interface'}
```

## File: google-deepmind_acme/acme/agents/tf/mcts/models/simulator_test.py

Prompts

```
['build a python class that subclasses Model and implements load_checkpoint, save_checkpoint, update, reset, and needs_reset', 'implement the update method to process a timestep, action, and next_timestep for MCTS planning', 'create a model subclass that saves and loads checkpoints to reset state after rollouts', 'build a model subclass that resets to an optional initial observation state for MCTS', 'implement the needs_reset property to signal when the MCTS model requires a reset', 'build an MLPTransitionModel that predicts next state, reward, and discount from state and action inputs', 'create an MLPModel with replay buffer, transition model, and Adam optimizer for environment modeling', 'run a model step to predict the next state, reward, and termination given an action', 'update the model by adding a transition to replay and performing SGD on a sampled batch', 'save and load the model checkpoint to persist and restore the internal model state', 'create a Simulator instance by passing a dm_env.Environment to wrap it for MCTS rollouts', 'step the Simulator with an action to get the next dm_env.TimeStep from the wrapped environment', 'reset the Simulator environment to start a new episode and clear the needs_reset flag', 'get the observation_spec and action_spec from the Simulator to understand the environment interface', 'test that the Simulator model matches the ground truth environment across multiple episodes', 'test that save_checkpoint and load_checkpoint correctly restore the Simulator state', 'run the absltest test suite for the MCTS Simulator model fidelity and checkpointing', 'compare two dm_env TimeStep objects for matching reward, discount, step_type, and observation', 'review the Simulator class that wraps a dm_env environment as an MCTS-compatible model']
```

Usage

```
{'test_simulator_fidelity': 'test that the Simulator model matches the ground truth environment across multiple episodes', 'test_checkpointing': 'test that save_checkpoint and load_checkpoint correctly restore the Simulator state', 'run_simulator_test': 'run the absltest test suite for the MCTS Simulator model fidelity and checkpointing', 'check_equal_timesteps': 'compare two dm_env TimeStep objects for matching reward, discount, step_type, and observation', 'review_simulator_class': 'review the Simulator class that wraps a dm_env environment as an MCTS-compatible model'}
```

