# Agent Python Tools

- repo: facebookresearch/collaq
- repo_uri: https://github.com/facebookresearch/collaq

## File: facebookresearch_collaq/third_party/pymarl/src/modules/mixers/qmix.py

Prompts

```
['create a QMixer with 1 hypernet layer by passing args with n_agents, state_shape, and mixing_embed_dim', 'create a QMixer with 2 hypernet layers by setting hypernet_layers to 2 and hypernet_embed in args', 'run the QMixer forward pass with agent_qs and states tensors to compute the total joint Q-value', 'review the QMixer hyper_w_1 network which produces state-conditioned weights for the first mixing layer', 'review the QMixer V network which computes V(s) as a state-dependent bias for the final output', 'create a QTranBase mixer network instance with coma_critic or qtran_paper architecture and small or big network size', 'run the QTranBase forward pass with a batch, hidden states, and optional actions to get Q and V outputs', 'build the Q network for joint action-value estimation using state and action inputs through a multi-layer MLP', 'build the V network for state-value estimation using state inputs through a multi-layer MLP', 'review the action_encoding network that encodes agent hidden states and actions for the qtran_paper architecture', 'create a VDNMixer instance that extends nn.Module for value decomposition networks', 'run the VDNMixer forward pass to sum agent Q-values across the agent dimension', 'test the VDNMixer forward method with agent Q-values tensor and batch input', 'review the VDNMixer class implementation for summing agent Q-values along dimension 2', 'refactor the VDNMixer forward method to support configurable summation dimensions']
```

Usage

```
{'create_qmixer_with_hypernet_1': 'create a QMixer with 1 hypernet layer by passing args with n_agents, state_shape, and mixing_embed_dim', 'create_qmixer_with_hypernet_2': 'create a QMixer with 2 hypernet layers by setting hypernet_layers to 2 and hypernet_embed in args', 'forward_qmixer_agent_qs': 'run the QMixer forward pass with agent_qs and states tensors to compute the total joint Q-value', 'review_qmixer_hyper_w1': 'review the QMixer hyper_w_1 network which produces state-conditioned weights for the first mixing layer', 'review_qmixer_V_network': 'review the QMixer V network which computes V(s) as a state-dependent bias for the final output'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/modules/mixers/qtran.py

Prompts

```
['create a QMixer with 1 hypernet layer by passing args with n_agents, state_shape, and mixing_embed_dim', 'create a QMixer with 2 hypernet layers by setting hypernet_layers to 2 and hypernet_embed in args', 'run the QMixer forward pass with agent_qs and states tensors to compute the total joint Q-value', 'review the QMixer hyper_w_1 network which produces state-conditioned weights for the first mixing layer', 'review the QMixer V network which computes V(s) as a state-dependent bias for the final output', 'create a QTranBase mixer network instance with coma_critic or qtran_paper architecture and small or big network size', 'run the QTranBase forward pass with a batch, hidden states, and optional actions to get Q and V outputs', 'build the Q network for joint action-value estimation using state and action inputs through a multi-layer MLP', 'build the V network for state-value estimation using state inputs through a multi-layer MLP', 'review the action_encoding network that encodes agent hidden states and actions for the qtran_paper architecture', 'create a VDNMixer instance that extends nn.Module for value decomposition networks', 'run the VDNMixer forward pass to sum agent Q-values across the agent dimension', 'test the VDNMixer forward method with agent Q-values tensor and batch input', 'review the VDNMixer class implementation for summing agent Q-values along dimension 2', 'refactor the VDNMixer forward method to support configurable summation dimensions']
```

Usage

```
{'create_QTranBase': 'create a QTranBase mixer network instance with coma_critic or qtran_paper architecture and small or big network size', 'run_QTranBase_forward': 'run the QTranBase forward pass with a batch, hidden states, and optional actions to get Q and V outputs', 'build_Q_network': 'build the Q network for joint action-value estimation using state and action inputs through a multi-layer MLP', 'build_V_network': 'build the V network for state-value estimation using state inputs through a multi-layer MLP', 'review_action_encoding': 'review the action_encoding network that encodes agent hidden states and actions for the qtran_paper architecture'}
```

## File: facebookresearch_collaq/third_party/pymarl/src/modules/mixers/vdn.py

Prompts

```
['create a QMixer with 1 hypernet layer by passing args with n_agents, state_shape, and mixing_embed_dim', 'create a QMixer with 2 hypernet layers by setting hypernet_layers to 2 and hypernet_embed in args', 'run the QMixer forward pass with agent_qs and states tensors to compute the total joint Q-value', 'review the QMixer hyper_w_1 network which produces state-conditioned weights for the first mixing layer', 'review the QMixer V network which computes V(s) as a state-dependent bias for the final output', 'create a QTranBase mixer network instance with coma_critic or qtran_paper architecture and small or big network size', 'run the QTranBase forward pass with a batch, hidden states, and optional actions to get Q and V outputs', 'build the Q network for joint action-value estimation using state and action inputs through a multi-layer MLP', 'build the V network for state-value estimation using state inputs through a multi-layer MLP', 'review the action_encoding network that encodes agent hidden states and actions for the qtran_paper architecture', 'create a VDNMixer instance that extends nn.Module for value decomposition networks', 'run the VDNMixer forward pass to sum agent Q-values across the agent dimension', 'test the VDNMixer forward method with agent Q-values tensor and batch input', 'review the VDNMixer class implementation for summing agent Q-values along dimension 2', 'refactor the VDNMixer forward method to support configurable summation dimensions']
```

Usage

```
{'create_VDNMixer': 'create a VDNMixer instance that extends nn.Module for value decomposition networks', 'run_VDNMixer_forward': 'run the VDNMixer forward pass to sum agent Q-values across the agent dimension', 'test_VDNMixer_forward': 'test the VDNMixer forward method with agent Q-values tensor and batch input', 'review_VDNMixer': 'review the VDNMixer class implementation for summing agent Q-values along dimension 2', 'refactor_VDNMixer_forward': 'refactor the VDNMixer forward method to support configurable summation dimensions'}
```

