# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/offline_rl/decision_transformer/agents.py

Prompts

```
['build a TransitionEncoder agent to encode state action and reward to go transitions into embeddings', 'build an ActionMLPAgentFromTransformer agent that predicts actions from transformer output embeddings', 'build an ActionMLPAgentFromObservation agent that predicts actions directly from observations and reward to go', 'build a complete decision transformer pipeline by composing encoder transformer and decoder agents', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'run the decision transformer offline RL training loop using behavior cloning on a d4rl dataset', 'create a ControlAgent to track and update reward-to-go values across timesteps in a Salina workspace', 'run the behavior cloning training loop with MSE loss and gradient clipping on a replay buffer', 'review the ControlAgent forward method to understand how reward-to-go is computed at each timestep', 'summarize the run_bc function that orchestrates async evaluation and supervised BC training', 'build a decision transformer agent by composing TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'create an xFormerMultiBlockAgent with configurable layers, heads, and context length for attention-based RL', 'test the transition_transformers function with encoder, transformer, and decoder config objects', 'review the TransitionEncoder class that transforms state-action-next_state tuples into embedding vectors', 'refactor the ActionMLPAgentFromTransformer to support different MLP architectures for action prediction']
```

Usage

```
{'build_TransitionEncoder': 'build a TransitionEncoder agent to encode state action and reward to go transitions into embeddings', 'build_ActionMLPAgentFromTransformer': 'build an ActionMLPAgentFromTransformer agent that predicts actions from transformer output embeddings', 'build_ActionMLPAgentFromObservation': 'build an ActionMLPAgentFromObservation agent that predicts actions directly from observations and reward to go', 'build_transition_transformers': 'build a complete decision transformer pipeline by composing encoder transformer and decoder agents', 'build_mlp': 'build a multi-layer perceptron with configurable layer sizes and activation functions'}
```

## File: facebookresearch_salina/salina_examples/offline_rl/decision_transformer/dt.py

Prompts

```
['build a TransitionEncoder agent to encode state action and reward to go transitions into embeddings', 'build an ActionMLPAgentFromTransformer agent that predicts actions from transformer output embeddings', 'build an ActionMLPAgentFromObservation agent that predicts actions directly from observations and reward to go', 'build a complete decision transformer pipeline by composing encoder transformer and decoder agents', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'run the decision transformer offline RL training loop using behavior cloning on a d4rl dataset', 'create a ControlAgent to track and update reward-to-go values across timesteps in a Salina workspace', 'run the behavior cloning training loop with MSE loss and gradient clipping on a replay buffer', 'review the ControlAgent forward method to understand how reward-to-go is computed at each timestep', 'summarize the run_bc function that orchestrates async evaluation and supervised BC training', 'build a decision transformer agent by composing TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'create an xFormerMultiBlockAgent with configurable layers, heads, and context length for attention-based RL', 'test the transition_transformers function with encoder, transformer, and decoder config objects', 'review the TransitionEncoder class that transforms state-action-next_state tuples into embedding vectors', 'refactor the ActionMLPAgentFromTransformer to support different MLP architectures for action prediction']
```

Usage

```
{'run_decision_transformer_training': 'run the decision transformer offline RL training loop using behavior cloning on a d4rl dataset', 'create_control_agent': 'create a ControlAgent to track and update reward-to-go values across timesteps in a Salina workspace', 'run_behavior_cloning': 'run the behavior cloning training loop with MSE loss and gradient clipping on a replay buffer', 'review_control_agent_forward': 'review the ControlAgent forward method to understand how reward-to-go is computed at each timestep', 'summarize_run_bc_function': 'summarize the run_bc function that orchestrates async evaluation and supervised BC training'}
```

## File: facebookresearch_salina/salina_examples/offline_rl/decision_transformer/xformers_agents.py

Prompts

```
['build a TransitionEncoder agent to encode state action and reward to go transitions into embeddings', 'build an ActionMLPAgentFromTransformer agent that predicts actions from transformer output embeddings', 'build an ActionMLPAgentFromObservation agent that predicts actions directly from observations and reward to go', 'build a complete decision transformer pipeline by composing encoder transformer and decoder agents', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'run the decision transformer offline RL training loop using behavior cloning on a d4rl dataset', 'create a ControlAgent to track and update reward-to-go values across timesteps in a Salina workspace', 'run the behavior cloning training loop with MSE loss and gradient clipping on a replay buffer', 'review the ControlAgent forward method to understand how reward-to-go is computed at each timestep', 'summarize the run_bc function that orchestrates async evaluation and supervised BC training', 'build a decision transformer agent by composing TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'create an xFormerMultiBlockAgent with configurable layers, heads, and context length for attention-based RL', 'test the transition_transformers function with encoder, transformer, and decoder config objects', 'review the TransitionEncoder class that transforms state-action-next_state tuples into embedding vectors', 'refactor the ActionMLPAgentFromTransformer to support different MLP architectures for action prediction']
```

Usage

```
{'build_decision_transformer_agent': 'build a decision transformer agent by composing TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'create_xformer_multi_block_agent': 'create an xFormerMultiBlockAgent with configurable layers, heads, and context length for attention-based RL', 'test_transition_transformers_function': 'test the transition_transformers function with encoder, transformer, and decoder config objects', 'review_transition_encoder': 'review the TransitionEncoder class that transforms state-action-next_state tuples into embedding vectors', 'refactor_action_mlp_agent': 'refactor the ActionMLPAgentFromTransformer to support different MLP architectures for action prediction'}
```

