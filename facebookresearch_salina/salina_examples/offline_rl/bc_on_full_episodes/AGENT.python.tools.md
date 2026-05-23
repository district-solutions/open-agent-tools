# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/offline_rl/bc_on_full_episodes/agents.py

Prompts

```
['build a TransitionEncoder agent that transforms state-action-next_state tuples into embedding vectors with positional encoding', 'build an ActionMLPAgentFromTransformer that decodes transformer embeddings into clipped tanh actions for a gym environment', 'build an ActionMLPAgentFromObservation that maps raw environment observations directly to clipped tanh actions via an MLP', 'build a full transformer-based behavior cloning agent by composing TransitionEncoder, TransformerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'build a simple observation-to-action MLP agent using ActionMLPAgentFromObservation with configurable hidden layers and size', 'run behavior cloning training on offline RL buffer with MSE loss and gradient clipping', 'run the main entry point that instantiates logger, env, workspace, agent and starts BC training', 'run state dict transfer between agent and device for evaluation agent synchronization', 'review the run_bc training loop that performs batch sampling, masked MSE loss, and optimizer steps', 'review the NRemoteAgent evaluation setup that creates parallel evaluation processes with TemporalAgent', 'run behavior cloning training on offline RL buffer with torch AMP mixed precision', 'review the run_bc function and its episode length masking logic for MSE loss computation', 'review the evaluation loop that uses NRemoteAgent for async multi-process environment evaluation', 'build a xFormers-based transition transformer agent with encoder, transformer block, and MLP decoder for offline RL', 'create an MLP agent that maps environment observations directly to clipped action outputs', 'review the xformers_transition_transformers function that chains TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'refactor the observation_mlp function to pass custom kwargs into ActionMLPAgentFromObservation for flexible agent config', 'summarize the xFormers agent pipeline that encodes transitions, applies multi-head attention, and decodes actions via MLP']
```

Usage

```
{'build_TransitionEncoder': 'build a TransitionEncoder agent that transforms state-action-next_state tuples into embedding vectors with positional encoding', 'build_ActionMLPAgentFromTransformer': 'build an ActionMLPAgentFromTransformer that decodes transformer embeddings into clipped tanh actions for a gym environment', 'build_ActionMLPAgentFromObservation': 'build an ActionMLPAgentFromObservation that maps raw environment observations directly to clipped tanh actions via an MLP', 'build_transition_transformers': 'build a full transformer-based behavior cloning agent by composing TransitionEncoder, TransformerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'build_observation_mlp': 'build a simple observation-to-action MLP agent using ActionMLPAgentFromObservation with configurable hidden layers and size'}
```

## File: facebookresearch_salina/salina_examples/offline_rl/bc_on_full_episodes/bc.py

Prompts

```
['build a TransitionEncoder agent that transforms state-action-next_state tuples into embedding vectors with positional encoding', 'build an ActionMLPAgentFromTransformer that decodes transformer embeddings into clipped tanh actions for a gym environment', 'build an ActionMLPAgentFromObservation that maps raw environment observations directly to clipped tanh actions via an MLP', 'build a full transformer-based behavior cloning agent by composing TransitionEncoder, TransformerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'build a simple observation-to-action MLP agent using ActionMLPAgentFromObservation with configurable hidden layers and size', 'run behavior cloning training on offline RL buffer with MSE loss and gradient clipping', 'run the main entry point that instantiates logger, env, workspace, agent and starts BC training', 'run state dict transfer between agent and device for evaluation agent synchronization', 'review the run_bc training loop that performs batch sampling, masked MSE loss, and optimizer steps', 'review the NRemoteAgent evaluation setup that creates parallel evaluation processes with TemporalAgent', 'run behavior cloning training on offline RL buffer with torch AMP mixed precision', 'review the run_bc function and its episode length masking logic for MSE loss computation', 'review the evaluation loop that uses NRemoteAgent for async multi-process environment evaluation', 'build a xFormers-based transition transformer agent with encoder, transformer block, and MLP decoder for offline RL', 'create an MLP agent that maps environment observations directly to clipped action outputs', 'review the xformers_transition_transformers function that chains TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'refactor the observation_mlp function to pass custom kwargs into ActionMLPAgentFromObservation for flexible agent config', 'summarize the xFormers agent pipeline that encodes transitions, applies multi-head attention, and decodes actions via MLP']
```

Usage

```
{'run_bc_behavior_cloning': 'run behavior cloning training on offline RL buffer with MSE loss and gradient clipping', 'run_main_entry': 'run the main entry point that instantiates logger, env, workspace, agent and starts BC training', 'run_state_dict_transfer': 'run state dict transfer between agent and device for evaluation agent synchronization', 'review_run_bc_training_loop': 'review the run_bc training loop that performs batch sampling, masked MSE loss, and optimizer steps', 'review_nremoteagent_evaluation': 'review the NRemoteAgent evaluation setup that creates parallel evaluation processes with TemporalAgent'}
```

## File: facebookresearch_salina/salina_examples/offline_rl/bc_on_full_episodes/bc_with_torch_amp.py

Prompts

```
['build a TransitionEncoder agent that transforms state-action-next_state tuples into embedding vectors with positional encoding', 'build an ActionMLPAgentFromTransformer that decodes transformer embeddings into clipped tanh actions for a gym environment', 'build an ActionMLPAgentFromObservation that maps raw environment observations directly to clipped tanh actions via an MLP', 'build a full transformer-based behavior cloning agent by composing TransitionEncoder, TransformerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'build a simple observation-to-action MLP agent using ActionMLPAgentFromObservation with configurable hidden layers and size', 'run behavior cloning training on offline RL buffer with MSE loss and gradient clipping', 'run the main entry point that instantiates logger, env, workspace, agent and starts BC training', 'run state dict transfer between agent and device for evaluation agent synchronization', 'review the run_bc training loop that performs batch sampling, masked MSE loss, and optimizer steps', 'review the NRemoteAgent evaluation setup that creates parallel evaluation processes with TemporalAgent', 'run behavior cloning training on offline RL buffer with torch AMP mixed precision', 'review the run_bc function and its episode length masking logic for MSE loss computation', 'review the evaluation loop that uses NRemoteAgent for async multi-process environment evaluation', 'build a xFormers-based transition transformer agent with encoder, transformer block, and MLP decoder for offline RL', 'create an MLP agent that maps environment observations directly to clipped action outputs', 'review the xformers_transition_transformers function that chains TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'refactor the observation_mlp function to pass custom kwargs into ActionMLPAgentFromObservation for flexible agent config', 'summarize the xFormers agent pipeline that encodes transitions, applies multi-head attention, and decodes actions via MLP']
```

Usage

```
{'run_bc_training': 'run behavior cloning training on offline RL buffer with torch AMP mixed precision', 'run_main_entry': 'run the main entry point that instantiates logger, env, workspace, agent and starts BC training', 'run_state_dict_transfer': 'run the state dict helper to move agent parameters to a specified device', 'review_run_bc_masking': 'review the run_bc function and its episode length masking logic for MSE loss computation', 'review_evaluation_loop': 'review the evaluation loop that uses NRemoteAgent for async multi-process environment evaluation'}
```

## File: facebookresearch_salina/salina_examples/offline_rl/bc_on_full_episodes/xformers_agents.py

Prompts

```
['build a TransitionEncoder agent that transforms state-action-next_state tuples into embedding vectors with positional encoding', 'build an ActionMLPAgentFromTransformer that decodes transformer embeddings into clipped tanh actions for a gym environment', 'build an ActionMLPAgentFromObservation that maps raw environment observations directly to clipped tanh actions via an MLP', 'build a full transformer-based behavior cloning agent by composing TransitionEncoder, TransformerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'build a simple observation-to-action MLP agent using ActionMLPAgentFromObservation with configurable hidden layers and size', 'run behavior cloning training on offline RL buffer with MSE loss and gradient clipping', 'run the main entry point that instantiates logger, env, workspace, agent and starts BC training', 'run state dict transfer between agent and device for evaluation agent synchronization', 'review the run_bc training loop that performs batch sampling, masked MSE loss, and optimizer steps', 'review the NRemoteAgent evaluation setup that creates parallel evaluation processes with TemporalAgent', 'run behavior cloning training on offline RL buffer with torch AMP mixed precision', 'review the run_bc function and its episode length masking logic for MSE loss computation', 'review the evaluation loop that uses NRemoteAgent for async multi-process environment evaluation', 'build a xFormers-based transition transformer agent with encoder, transformer block, and MLP decoder for offline RL', 'create an MLP agent that maps environment observations directly to clipped action outputs', 'review the xformers_transition_transformers function that chains TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'refactor the observation_mlp function to pass custom kwargs into ActionMLPAgentFromObservation for flexible agent config', 'summarize the xFormers agent pipeline that encodes transitions, applies multi-head attention, and decodes actions via MLP']
```

Usage

```
{'build_xformers_transition_transformer_agent': 'build a xFormers-based transition transformer agent with encoder, transformer block, and MLP decoder for offline RL', 'create_observation_mlp_agent': 'create an MLP agent that maps environment observations directly to clipped action outputs', 'review_xformers_transition_transformers': 'review the xformers_transition_transformers function that chains TransitionEncoder, xFormerMultiBlockAgent, and ActionMLPAgentFromTransformer', 'refactor_observation_mlp_kwargs': 'refactor the observation_mlp function to pass custom kwargs into ActionMLPAgentFromObservation for flexible agent config', 'summarize_xformers_agent_pipeline': 'summarize the xFormers agent pipeline that encodes transitions, applies multi-head attention, and decodes actions via MLP'}
```

