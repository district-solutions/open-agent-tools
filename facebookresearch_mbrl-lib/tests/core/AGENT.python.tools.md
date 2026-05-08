# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/tests/core/test_common_utils.py

Prompts

```
['create a 1D transition reward model from an OmegaConf config with observation and action shapes', 'create a replay buffer from an OmegaConf config with specified observation and action shapes and data types', 'roll out a model-based environment with an agent or precomputed plan and collect observations and rewards', 'roll out an agent in a gym environment for a set number of steps or trials and populate a replay buffer', 'get training and validation transition iterators from a replay buffer with a specified batch size and validation ratio', 'test GaussianMLP model with SiLU and Threshold activation function configurations', 'test BasicEnsemble forward pass with expectation propagation method and mock member outputs', 'test GaussianMLP ensemble with random, fixed, and expectation propagation methods', 'test ModelEnv step behavior with expectation, random, and fixed propagation strategies', 'test Conv2dEncoder and Conv2dDecoder layer shapes with ReLU, SiLU, and Tanh activations', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a given dimension', 'test the PIDAgent act method to compute actions from single or batched observations', 'test the PIDAgent reset method to clear previous and cumulative error state', 'test the PIDAgent get_errors method to retrieve previous and cumulative error arrays', 'test the PIDAgent get_parameters method to retrieve all PID coefficients and targets flattened', 'test TransitionBatch indexing and slicing to verify individual and batched transition access', 'test ReplayBuffer batched add to verify transitions are stored correctly with circular overwrite', 'test ReplayBuffer trajectory tracking to verify trajectory indices and close_trajectory behavior', 'test TransitionIterator and BootstrapIterator to verify batching, shuffling, and ensemble sampling', 'test SequenceTransitionIterator and SequenceTransitionSampler to verify sequence sampling from trajectory batches']
```

Usage

```
{'create_one_dim_tr_model': 'create a 1D transition reward model from an OmegaConf config with observation and action shapes', 'create_replay_buffer': 'create a replay buffer from an OmegaConf config with specified observation and action shapes and data types', 'rollout_model_env': 'roll out a model-based environment with an agent or precomputed plan and collect observations and rewards', 'rollout_agent_trajectories': 'roll out an agent in a gym environment for a set number of steps or trials and populate a replay buffer', 'get_basic_buffer_iterators': 'get training and validation transition iterators from a replay buffer with a specified batch size and validation ratio'}
```

## File: facebookresearch_mbrl-lib/tests/core/test_models.py

Prompts

```
['create a 1D transition reward model from an OmegaConf config with observation and action shapes', 'create a replay buffer from an OmegaConf config with specified observation and action shapes and data types', 'roll out a model-based environment with an agent or precomputed plan and collect observations and rewards', 'roll out an agent in a gym environment for a set number of steps or trials and populate a replay buffer', 'get training and validation transition iterators from a replay buffer with a specified batch size and validation ratio', 'test GaussianMLP model with SiLU and Threshold activation function configurations', 'test BasicEnsemble forward pass with expectation propagation method and mock member outputs', 'test GaussianMLP ensemble with random, fixed, and expectation propagation methods', 'test ModelEnv step behavior with expectation, random, and fixed propagation strategies', 'test Conv2dEncoder and Conv2dDecoder layer shapes with ReLU, SiLU, and Tanh activations', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a given dimension', 'test the PIDAgent act method to compute actions from single or batched observations', 'test the PIDAgent reset method to clear previous and cumulative error state', 'test the PIDAgent get_errors method to retrieve previous and cumulative error arrays', 'test the PIDAgent get_parameters method to retrieve all PID coefficients and targets flattened', 'test TransitionBatch indexing and slicing to verify individual and batched transition access', 'test ReplayBuffer batched add to verify transitions are stored correctly with circular overwrite', 'test ReplayBuffer trajectory tracking to verify trajectory indices and close_trajectory behavior', 'test TransitionIterator and BootstrapIterator to verify batching, shuffling, and ensemble sampling', 'test SequenceTransitionIterator and SequenceTransitionSampler to verify sequence sampling from trajectory batches']
```

Usage

```
{'test_gaussian_mlp_activation_functions': 'test GaussianMLP model with SiLU and Threshold activation function configurations', 'test_basic_ensemble_forward': 'test BasicEnsemble forward pass with expectation propagation method and mock member outputs', 'test_ensemble_propagation_methods': 'test GaussianMLP ensemble with random, fixed, and expectation propagation methods', 'test_model_env_propagation': 'test ModelEnv step behavior with expectation, random, and fixed propagation strategies', 'test_conv2d_encoder_decoder': 'test Conv2dEncoder and Conv2dDecoder layer shapes with ReLU, SiLU, and Tanh activations'}
```

## File: facebookresearch_mbrl-lib/tests/core/test_planning.py

Prompts

```
['create a 1D transition reward model from an OmegaConf config with observation and action shapes', 'create a replay buffer from an OmegaConf config with specified observation and action shapes and data types', 'roll out a model-based environment with an agent or precomputed plan and collect observations and rewards', 'roll out an agent in a gym environment for a set number of steps or trials and populate a replay buffer', 'get training and validation transition iterators from a replay buffer with a specified batch size and validation ratio', 'test GaussianMLP model with SiLU and Threshold activation function configurations', 'test BasicEnsemble forward pass with expectation propagation method and mock member outputs', 'test GaussianMLP ensemble with random, fixed, and expectation propagation methods', 'test ModelEnv step behavior with expectation, random, and fixed propagation strategies', 'test Conv2dEncoder and Conv2dDecoder layer shapes with ReLU, SiLU, and Tanh activations', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a given dimension', 'test the PIDAgent act method to compute actions from single or batched observations', 'test the PIDAgent reset method to clear previous and cumulative error state', 'test the PIDAgent get_errors method to retrieve previous and cumulative error arrays', 'test the PIDAgent get_parameters method to retrieve all PID coefficients and targets flattened', 'test TransitionBatch indexing and slicing to verify individual and batched transition access', 'test ReplayBuffer batched add to verify transitions are stored correctly with circular overwrite', 'test ReplayBuffer trajectory tracking to verify trajectory indices and close_trajectory behavior', 'test TransitionIterator and BootstrapIterator to verify batching, shuffling, and ensemble sampling', 'test SequenceTransitionIterator and SequenceTransitionSampler to verify sequence sampling from trajectory batches']
```

Usage

```
{'create_pid_agent': 'create a PIDAgent with proportional, integral, and derivative control coefficients for a given dimension', 'test_pid_agent_act': 'test the PIDAgent act method to compute actions from single or batched observations', 'test_pid_agent_reset': 'test the PIDAgent reset method to clear previous and cumulative error state', 'test_pid_agent_get_errors': 'test the PIDAgent get_errors method to retrieve previous and cumulative error arrays', 'test_pid_agent_get_parameters': 'test the PIDAgent get_parameters method to retrieve all PID coefficients and targets flattened'}
```

## File: facebookresearch_mbrl-lib/tests/core/test_replay_buffer.py

Prompts

```
['create a 1D transition reward model from an OmegaConf config with observation and action shapes', 'create a replay buffer from an OmegaConf config with specified observation and action shapes and data types', 'roll out a model-based environment with an agent or precomputed plan and collect observations and rewards', 'roll out an agent in a gym environment for a set number of steps or trials and populate a replay buffer', 'get training and validation transition iterators from a replay buffer with a specified batch size and validation ratio', 'test GaussianMLP model with SiLU and Threshold activation function configurations', 'test BasicEnsemble forward pass with expectation propagation method and mock member outputs', 'test GaussianMLP ensemble with random, fixed, and expectation propagation methods', 'test ModelEnv step behavior with expectation, random, and fixed propagation strategies', 'test Conv2dEncoder and Conv2dDecoder layer shapes with ReLU, SiLU, and Tanh activations', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a given dimension', 'test the PIDAgent act method to compute actions from single or batched observations', 'test the PIDAgent reset method to clear previous and cumulative error state', 'test the PIDAgent get_errors method to retrieve previous and cumulative error arrays', 'test the PIDAgent get_parameters method to retrieve all PID coefficients and targets flattened', 'test TransitionBatch indexing and slicing to verify individual and batched transition access', 'test ReplayBuffer batched add to verify transitions are stored correctly with circular overwrite', 'test ReplayBuffer trajectory tracking to verify trajectory indices and close_trajectory behavior', 'test TransitionIterator and BootstrapIterator to verify batching, shuffling, and ensemble sampling', 'test SequenceTransitionIterator and SequenceTransitionSampler to verify sequence sampling from trajectory batches']
```

Usage

```
{'test_TransitionBatch_getitem': 'test TransitionBatch indexing and slicing to verify individual and batched transition access', 'test_ReplayBuffer_add_batch': 'test ReplayBuffer batched add to verify transitions are stored correctly with circular overwrite', 'test_ReplayBuffer_trajectory': 'test ReplayBuffer trajectory tracking to verify trajectory indices and close_trajectory behavior', 'test_TransitionIterator_shuffle': 'test TransitionIterator and BootstrapIterator to verify batching, shuffling, and ensemble sampling', 'test_SequenceTransitionIterator': 'test SequenceTransitionIterator and SequenceTransitionSampler to verify sequence sampling from trajectory batches'}
```

