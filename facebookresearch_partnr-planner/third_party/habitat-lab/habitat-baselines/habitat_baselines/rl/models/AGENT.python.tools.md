# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/models/action_embedding.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that handles a dictionary of mixed Box and Discrete action spaces', 'test the BoxActionEmbedding forward pass by passing continuous action tensors and optional masks', 'test the DiscreteActionEmbedding forward pass by passing discrete action indices and optional masks', 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and number of layers', 'build PackedSequence indexing info from a 2D done signals array for variable-length episode batching', 'build a PackedSequence input and masked hidden states for an RNN forward pass from rollout data', 'build the unpacked RNN output tensor and final hidden states from a PackedSequence result', 'run a forward pass through an RNN state encoder with episode boundary masking for single or sequence inputs', 'build a SimpleCNN model from an observation space with a specified output embedding size', 'run a forward pass through SimpleCNN with rgb and depth observation tensors', 'test the _conv_output_dim method to calculate convolution layer output dimensions', 'review the layer_init method that applies Kaiming normal weight initialization to Conv2d and Linear layers', 'summarize the is_blind property that checks if the model has no rgb or depth input channels']
```

Usage

```
{'build_box_action_embedding': 'build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous Box action spaces', 'build_discrete_action_embedding': 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build_action_embedding': 'build an ActionEmbedding module that handles a dictionary of mixed Box and Discrete action spaces', 'test_box_action_embedding_forward': 'test the BoxActionEmbedding forward pass by passing continuous action tensors and optional masks', 'test_discrete_action_embedding_forward': 'test the DiscreteActionEmbedding forward pass by passing discrete action indices and optional masks'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/models/rnn_state_encoder.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that handles a dictionary of mixed Box and Discrete action spaces', 'test the BoxActionEmbedding forward pass by passing continuous action tensors and optional masks', 'test the DiscreteActionEmbedding forward pass by passing discrete action indices and optional masks', 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and number of layers', 'build PackedSequence indexing info from a 2D done signals array for variable-length episode batching', 'build a PackedSequence input and masked hidden states for an RNN forward pass from rollout data', 'build the unpacked RNN output tensor and final hidden states from a PackedSequence result', 'run a forward pass through an RNN state encoder with episode boundary masking for single or sequence inputs', 'build a SimpleCNN model from an observation space with a specified output embedding size', 'run a forward pass through SimpleCNN with rgb and depth observation tensors', 'test the _conv_output_dim method to calculate convolution layer output dimensions', 'review the layer_init method that applies Kaiming normal weight initialization to Conv2d and Linear layers', 'summarize the is_blind property that checks if the model has no rgb or depth input channels']
```

Usage

```
{'build_rnn_state_encoder': 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and number of layers', 'build_pack_info_from_dones': 'build PackedSequence indexing info from a 2D done signals array for variable-length episode batching', 'build_rnn_inputs': 'build a PackedSequence input and masked hidden states for an RNN forward pass from rollout data', 'build_rnn_out_from_seq': 'build the unpacked RNN output tensor and final hidden states from a PackedSequence result', 'RNNStateEncoder_forward': 'run a forward pass through an RNN state encoder with episode boundary masking for single or sequence inputs'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/models/simple_cnn.py

Prompts

```
['build a BoxActionEmbedding module that applies NeRF style sinusoidal embedding to continuous Box action spaces', 'build a DiscreteActionEmbedding module that embeds discrete actions using a lookup table with a start token', 'build an ActionEmbedding module that handles a dictionary of mixed Box and Discrete action spaces', 'test the BoxActionEmbedding forward pass by passing continuous action tensors and optional masks', 'test the DiscreteActionEmbedding forward pass by passing discrete action indices and optional masks', 'build a GRU or LSTM RNN state encoder with specified input size, hidden size, and number of layers', 'build PackedSequence indexing info from a 2D done signals array for variable-length episode batching', 'build a PackedSequence input and masked hidden states for an RNN forward pass from rollout data', 'build the unpacked RNN output tensor and final hidden states from a PackedSequence result', 'run a forward pass through an RNN state encoder with episode boundary masking for single or sequence inputs', 'build a SimpleCNN model from an observation space with a specified output embedding size', 'run a forward pass through SimpleCNN with rgb and depth observation tensors', 'test the _conv_output_dim method to calculate convolution layer output dimensions', 'review the layer_init method that applies Kaiming normal weight initialization to Conv2d and Linear layers', 'summarize the is_blind property that checks if the model has no rgb or depth input channels']
```

Usage

```
{'build_simple_cnn_model': 'build a SimpleCNN model from an observation space with a specified output embedding size', 'run_cnn_forward_pass': 'run a forward pass through SimpleCNN with rgb and depth observation tensors', 'test_conv_output_dim': 'test the _conv_output_dim method to calculate convolution layer output dimensions', 'review_layer_init': 'review the layer_init method that applies Kaiming normal weight initialization to Conv2d and Linear layers', 'summarize_is_blind_property': 'summarize the is_blind property that checks if the model has no rgb or depth input channels'}
```

