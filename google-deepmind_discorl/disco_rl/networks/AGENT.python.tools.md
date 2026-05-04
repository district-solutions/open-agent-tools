# Agent Python Tools

- repo: google-deepmind/discorl
- repo_uri: https://github.com/google-deepmind/disco_rl

## File: google-deepmind_discorl/disco_rl/networks/action_models.py

Prompts

```
['build an LSTM-based action-conditional model using LSTMModel with action_spec, out_spec, head_mlp_hiddens, and lstm_size parameters', "create an action model instance by calling get_action_model with name 'lstm' and required constructor arguments", 'run a model step on an LSTMState embedding to get transition outputs and head predictions for all actions', "build a root node LSTMState from the agent's flattened state using a linear layer and tanh activation", 'review the LSTMModel _model_transition_all_actions method that performs one-hot action conditioning through an LSTM layer', 'build an LSTM meta network with configurable hidden size and embedding dimensions for update rules', 'create a MetaLSTM module that processes trajectories and meta targets throughout the agent lifetime', 'construct input vectors from update rule inputs using y_net, z_net, and policy_net transforms', 'review the multiplicative interaction function that conditions RNN state output via learned linear projection', 'summarize the conv1d network builder that creates sequential 1D convolution blocks with average pooling', "build a policy network using get_network with name 'mlp' and dense layer specs", 'create an MLPHeadNet subclass that implements _embedding_pass for custom input processing', 'test the MLP class by instantiating it with out_spec, dense layers, and action_spec', 'review the MLPHeadNet _head_pass method that computes outputs as linear functions of the embedding', "refactor get_network to support additional network types beyond 'mlp'"]
```

Usage

```
{'build_lstm_action_model': 'build an LSTM-based action-conditional model using LSTMModel with action_spec, out_spec, head_mlp_hiddens, and lstm_size parameters', 'create_action_model_factory': "create an action model instance by calling get_action_model with name 'lstm' and required constructor arguments", 'run_model_step': 'run a model step on an LSTMState embedding to get transition outputs and head predictions for all actions', 'build_root_embedding': "build a root node LSTMState from the agent's flattened state using a linear layer and tanh activation", 'review_model_transition_all_actions': 'review the LSTMModel _model_transition_all_actions method that performs one-hot action conditioning through an LSTM layer'}
```

## File: google-deepmind_discorl/disco_rl/networks/meta_nets.py

Prompts

```
['build an LSTM-based action-conditional model using LSTMModel with action_spec, out_spec, head_mlp_hiddens, and lstm_size parameters', "create an action model instance by calling get_action_model with name 'lstm' and required constructor arguments", 'run a model step on an LSTMState embedding to get transition outputs and head predictions for all actions', "build a root node LSTMState from the agent's flattened state using a linear layer and tanh activation", 'review the LSTMModel _model_transition_all_actions method that performs one-hot action conditioning through an LSTM layer', 'build an LSTM meta network with configurable hidden size and embedding dimensions for update rules', 'create a MetaLSTM module that processes trajectories and meta targets throughout the agent lifetime', 'construct input vectors from update rule inputs using y_net, z_net, and policy_net transforms', 'review the multiplicative interaction function that conditions RNN state output via learned linear projection', 'summarize the conv1d network builder that creates sequential 1D convolution blocks with average pooling', "build a policy network using get_network with name 'mlp' and dense layer specs", 'create an MLPHeadNet subclass that implements _embedding_pass for custom input processing', 'test the MLP class by instantiating it with out_spec, dense layers, and action_spec', 'review the MLPHeadNet _head_pass method that computes outputs as linear functions of the embedding', "refactor get_network to support additional network types beyond 'mlp'"]
```

Usage

```
{'build_lstm_meta_network': 'build an LSTM meta network with configurable hidden size and embedding dimensions for update rules', 'create_met_lstm_module': 'create a MetaLSTM module that processes trajectories and meta targets throughout the agent lifetime', 'construct_meta_net_input': 'construct input vectors from update rule inputs using y_net, z_net, and policy_net transforms', 'review_multiplicative_interaction': 'review the multiplicative interaction function that conditions RNN state output via learned linear projection', 'summarize_conv1d_net': 'summarize the conv1d network builder that creates sequential 1D convolution blocks with average pooling'}
```

## File: google-deepmind_discorl/disco_rl/networks/nets.py

Prompts

```
['build an LSTM-based action-conditional model using LSTMModel with action_spec, out_spec, head_mlp_hiddens, and lstm_size parameters', "create an action model instance by calling get_action_model with name 'lstm' and required constructor arguments", 'run a model step on an LSTMState embedding to get transition outputs and head predictions for all actions', "build a root node LSTMState from the agent's flattened state using a linear layer and tanh activation", 'review the LSTMModel _model_transition_all_actions method that performs one-hot action conditioning through an LSTM layer', 'build an LSTM meta network with configurable hidden size and embedding dimensions for update rules', 'create a MetaLSTM module that processes trajectories and meta targets throughout the agent lifetime', 'construct input vectors from update rule inputs using y_net, z_net, and policy_net transforms', 'review the multiplicative interaction function that conditions RNN state output via learned linear projection', 'summarize the conv1d network builder that creates sequential 1D convolution blocks with average pooling', "build a policy network using get_network with name 'mlp' and dense layer specs", 'create an MLPHeadNet subclass that implements _embedding_pass for custom input processing', 'test the MLP class by instantiating it with out_spec, dense layers, and action_spec', 'review the MLPHeadNet _head_pass method that computes outputs as linear functions of the embedding', "refactor get_network to support additional network types beyond 'mlp'"]
```

Usage

```
{'build_mlp_network': "build a policy network using get_network with name 'mlp' and dense layer specs", 'create_mlp_head_net': 'create an MLPHeadNet subclass that implements _embedding_pass for custom input processing', 'test_MLP_class': 'test the MLP class by instantiating it with out_spec, dense layers, and action_spec', 'review_MLPHeadNet_head_pass': 'review the MLPHeadNet _head_pass method that computes outputs as linear functions of the embedding', 'refactor_get_network': "refactor get_network to support additional network types beyond 'mlp'"}
```

