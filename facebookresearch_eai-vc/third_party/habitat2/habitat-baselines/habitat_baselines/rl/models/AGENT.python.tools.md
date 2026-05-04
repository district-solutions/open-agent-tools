# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/models/action_embedding.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review the ActionEmbedding class output_size property that sums all embedding module output sizes', 'build a GRU or LSTM RNN state encoder with specified input and hidden sizes', 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build a PackedSequence and masked hidden states from flattened rollout tensors for RNN forward pass', 'build the unflattened RNN output and final hidden states from a PackedSequence result', 'review the RNNStateEncoder forward method that handles single step and sequence RNN encoding with masks', 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run the SimpleCNN forward pass on a dictionary of rgb and depth observation tensors', 'test the SimpleCNN is_blind property to check if the model has no visual input channels', 'refactor the SimpleCNN layer_init method to use a different weight initialization strategy', 'review the SimpleCNN _conv_output_dim method to verify convolution output dimension calculations']
```

Usage

```
{'build_box_action_embedding': 'build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build_discrete_action_embedding': 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build_action_embedding': 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test_box_action_embedding_forward': 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review_action_embedding_output_size': 'review the ActionEmbedding class output_size property that sums all embedding module output sizes'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/models/rnn_state_encoder.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review the ActionEmbedding class output_size property that sums all embedding module output sizes', 'build a GRU or LSTM RNN state encoder with specified input and hidden sizes', 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build a PackedSequence and masked hidden states from flattened rollout tensors for RNN forward pass', 'build the unflattened RNN output and final hidden states from a PackedSequence result', 'review the RNNStateEncoder forward method that handles single step and sequence RNN encoding with masks', 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run the SimpleCNN forward pass on a dictionary of rgb and depth observation tensors', 'test the SimpleCNN is_blind property to check if the model has no visual input channels', 'refactor the SimpleCNN layer_init method to use a different weight initialization strategy', 'review the SimpleCNN _conv_output_dim method to verify convolution output dimension calculations']
```

Usage

```
{'build_rnn_state_encoder': 'build a GRU or LSTM RNN state encoder with specified input and hidden sizes', 'build_pack_info_from_dones': 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build_rnn_inputs': 'build a PackedSequence and masked hidden states from flattened rollout tensors for RNN forward pass', 'build_rnn_out_from_seq': 'build the unflattened RNN output and final hidden states from a PackedSequence result', 'review_RNNStateEncoder_forward': 'review the RNNStateEncoder forward method that handles single step and sequence RNN encoding with masks'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/models/simple_cnn.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review the ActionEmbedding class output_size property that sums all embedding module output sizes', 'build a GRU or LSTM RNN state encoder with specified input and hidden sizes', 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build a PackedSequence and masked hidden states from flattened rollout tensors for RNN forward pass', 'build the unflattened RNN output and final hidden states from a PackedSequence result', 'review the RNNStateEncoder forward method that handles single step and sequence RNN encoding with masks', 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run the SimpleCNN forward pass on a dictionary of rgb and depth observation tensors', 'test the SimpleCNN is_blind property to check if the model has no visual input channels', 'refactor the SimpleCNN layer_init method to use a different weight initialization strategy', 'review the SimpleCNN _conv_output_dim method to verify convolution output dimension calculations']
```

Usage

```
{'build_SimpleCNN': 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run_SimpleCNN_forward': 'run the SimpleCNN forward pass on a dictionary of rgb and depth observation tensors', 'test_SimpleCNN_is_blind': 'test the SimpleCNN is_blind property to check if the model has no visual input channels', 'refactor_SimpleCNN_layer_init': 'refactor the SimpleCNN layer_init method to use a different weight initialization strategy', 'review_SimpleCNN_conv_output_dim': 'review the SimpleCNN _conv_output_dim method to verify convolution output dimension calculations'}
```

