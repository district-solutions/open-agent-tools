# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/models/action_embedding.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review the ActionEmbedding output_size property to verify total embedding dimensions across all sub modules', 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and layer count', 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build a PackedSequence and masked hidden states from flattened input tensors and sequence info', 'build the original output tensors and hidden states from an RNN packed sequence result', 'review the RNNStateEncoder forward method that handles single timestep and sequence forward passes with masking', 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run the SimpleCNN forward pass on a dict of rgb and depth observation tensors', 'test the _conv_output_dim method to calculate output dimensions after convolution layers', 'review the layer_init method that applies Kaiming normal weight initialization to conv and linear layers', 'summarize the is_blind property that checks if the model has no rgb or depth input channels']
```

Usage

```
{'build_box_action_embedding': 'build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build_discrete_action_embedding': 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build_action_embedding': 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test_box_action_embedding_forward': 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review_action_embedding_output_size': 'review the ActionEmbedding output_size property to verify total embedding dimensions across all sub modules'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/models/rnn_state_encoder.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review the ActionEmbedding output_size property to verify total embedding dimensions across all sub modules', 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and layer count', 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build a PackedSequence and masked hidden states from flattened input tensors and sequence info', 'build the original output tensors and hidden states from an RNN packed sequence result', 'review the RNNStateEncoder forward method that handles single timestep and sequence forward passes with masking', 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run the SimpleCNN forward pass on a dict of rgb and depth observation tensors', 'test the _conv_output_dim method to calculate output dimensions after convolution layers', 'review the layer_init method that applies Kaiming normal weight initialization to conv and linear layers', 'summarize the is_blind property that checks if the model has no rgb or depth input channels']
```

Usage

```
{'build_rnn_state_encoder': 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and layer count', 'build_pack_info_from_dones': 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build_rnn_inputs': 'build a PackedSequence and masked hidden states from flattened input tensors and sequence info', 'build_rnn_out_from_seq': 'build the original output tensors and hidden states from an RNN packed sequence result', 'review_RNNStateEncoder_forward': 'review the RNNStateEncoder forward method that handles single timestep and sequence forward passes with masking'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/models/simple_cnn.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous gym Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that combines Box and Discrete embeddings for a dictionary of action spaces', 'test the BoxActionEmbedding forward pass with a torch tensor action and optional mask tensor', 'review the ActionEmbedding output_size property to verify total embedding dimensions across all sub modules', 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and layer count', 'build PackedSequence indexing info from a 2D done signals array for RNN batching', 'build a PackedSequence and masked hidden states from flattened input tensors and sequence info', 'build the original output tensors and hidden states from an RNN packed sequence result', 'review the RNNStateEncoder forward method that handles single timestep and sequence forward passes with masking', 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run the SimpleCNN forward pass on a dict of rgb and depth observation tensors', 'test the _conv_output_dim method to calculate output dimensions after convolution layers', 'review the layer_init method that applies Kaiming normal weight initialization to conv and linear layers', 'summarize the is_blind property that checks if the model has no rgb or depth input channels']
```

Usage

```
{'build_SimpleCNN': 'build a SimpleCNN model from an observation space and output size for habitat RL agents', 'run_SimpleCNN_forward': 'run the SimpleCNN forward pass on a dict of rgb and depth observation tensors', 'test_conv_output_dim': 'test the _conv_output_dim method to calculate output dimensions after convolution layers', 'review_layer_init': 'review the layer_init method that applies Kaiming normal weight initialization to conv and linear layers', 'summarize_is_blind': 'summarize the is_blind property that checks if the model has no rgb or depth input channels'}
```

