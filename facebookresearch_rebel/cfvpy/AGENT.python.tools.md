# Agent Python Tools

- repo: facebookresearch/rebel
- repo_uri: https://github.com/facebookresearch/rebel

## File: facebookresearch_rebel/cfvpy/models.py

Prompts

```
['build a multi-layer perceptron with configurable hidden size, layers, activation, layer norm, and dropout', 'create a Net2 neural network module for counterfactual value iteration with dice and faces parameters', 'compute the input tensor size given a number of dice faces and dice count', 'compute the output tensor size as num_faces raised to the power of num_dice', 'review the Net2 forward pass that runs packed input through the MLP body then output layer', 'run the CFVExp selfplay training loop with a config to train a CFR value network', 'build a CFR value model from config with optional JIT compilation and half precision', 'create a RecursiveSolvingParams MDP config from a YAML-style dictionary for CFR solving', 'clip gradient norms of model parameters to a max norm value during training', 'get the last action index from a query tensor using one-hot action encoding', 'run the selfplay training loop by calling selfplay(cfg) to instantiate CFVExp and execute training', 'review the CFVExp class run method which orchestrates selfplay training with data loading and optimization', 'summarize the selfplay function that wraps CFVExp initialization and run for a given config', 'test the selfplay function by passing a config object with env, model, and optimizer settings', 'refactor the selfplay entry point to support additional training modes beyond CFVExp', 'create a StopWatchTimer instance to track elapsed time with start and pause methods', 'create a MultiStopWatchTimer to track cumulative timings across multiple named operations', 'run compute_exploitability to evaluate a CFR model by invoking the cfr binary subprocess', 'instantiate a class from a config object using cfg_instantiate with dynamic import', 'create a FractionCounter to accumulate numerator and denominator values and compute their ratio']
```

Usage

```
{'build_mlp_network': 'build a multi-layer perceptron with configurable hidden size, layers, activation, layer norm, and dropout', 'create_net2_model': 'create a Net2 neural network module for counterfactual value iteration with dice and faces parameters', 'compute_input_size': 'compute the input tensor size given a number of dice faces and dice count', 'compute_output_size': 'compute the output tensor size as num_faces raised to the power of num_dice', 'review_net2_forward': 'review the Net2 forward pass that runs packed input through the MLP body then output layer'}
```

## File: facebookresearch_rebel/cfvpy/selfplay.py

Prompts

```
['build a multi-layer perceptron with configurable hidden size, layers, activation, layer norm, and dropout', 'create a Net2 neural network module for counterfactual value iteration with dice and faces parameters', 'compute the input tensor size given a number of dice faces and dice count', 'compute the output tensor size as num_faces raised to the power of num_dice', 'review the Net2 forward pass that runs packed input through the MLP body then output layer', 'run the CFVExp selfplay training loop with a config to train a CFR value network', 'build a CFR value model from config with optional JIT compilation and half precision', 'create a RecursiveSolvingParams MDP config from a YAML-style dictionary for CFR solving', 'clip gradient norms of model parameters to a max norm value during training', 'get the last action index from a query tensor using one-hot action encoding', 'run the selfplay training loop by calling selfplay(cfg) to instantiate CFVExp and execute training', 'review the CFVExp class run method which orchestrates selfplay training with data loading and optimization', 'summarize the selfplay function that wraps CFVExp initialization and run for a given config', 'test the selfplay function by passing a config object with env, model, and optimizer settings', 'refactor the selfplay entry point to support additional training modes beyond CFVExp', 'create a StopWatchTimer instance to track elapsed time with start and pause methods', 'create a MultiStopWatchTimer to track cumulative timings across multiple named operations', 'run compute_exploitability to evaluate a CFR model by invoking the cfr binary subprocess', 'instantiate a class from a config object using cfg_instantiate with dynamic import', 'create a FractionCounter to accumulate numerator and denominator values and compute their ratio']
```

Usage

```
{'run_CfvExp_selfplay_training': 'run the CFVExp selfplay training loop with a config to train a CFR value network', 'build_model_with_build_model': 'build a CFR value model from config with optional JIT compilation and half precision', 'create_mdp_config_from_yaml': 'create a RecursiveSolvingParams MDP config from a YAML-style dictionary for CFR solving', 'clip_gradient_norms': 'clip gradient norms of model parameters to a max norm value during training', 'get_last_action_index_from_query': 'get the last action index from a query tensor using one-hot action encoding'}
```

## File: facebookresearch_rebel/cfvpy/tasks.py

Prompts

```
['build a multi-layer perceptron with configurable hidden size, layers, activation, layer norm, and dropout', 'create a Net2 neural network module for counterfactual value iteration with dice and faces parameters', 'compute the input tensor size given a number of dice faces and dice count', 'compute the output tensor size as num_faces raised to the power of num_dice', 'review the Net2 forward pass that runs packed input through the MLP body then output layer', 'run the CFVExp selfplay training loop with a config to train a CFR value network', 'build a CFR value model from config with optional JIT compilation and half precision', 'create a RecursiveSolvingParams MDP config from a YAML-style dictionary for CFR solving', 'clip gradient norms of model parameters to a max norm value during training', 'get the last action index from a query tensor using one-hot action encoding', 'run the selfplay training loop by calling selfplay(cfg) to instantiate CFVExp and execute training', 'review the CFVExp class run method which orchestrates selfplay training with data loading and optimization', 'summarize the selfplay function that wraps CFVExp initialization and run for a given config', 'test the selfplay function by passing a config object with env, model, and optimizer settings', 'refactor the selfplay entry point to support additional training modes beyond CFVExp', 'create a StopWatchTimer instance to track elapsed time with start and pause methods', 'create a MultiStopWatchTimer to track cumulative timings across multiple named operations', 'run compute_exploitability to evaluate a CFR model by invoking the cfr binary subprocess', 'instantiate a class from a config object using cfg_instantiate with dynamic import', 'create a FractionCounter to accumulate numerator and denominator values and compute their ratio']
```

Usage

```
{'run_selfplay': 'run the selfplay training loop by calling selfplay(cfg) to instantiate CFVExp and execute training', 'review_CFVExp_run': 'review the CFVExp class run method which orchestrates selfplay training with data loading and optimization', 'summarize_selfplay_function': 'summarize the selfplay function that wraps CFVExp initialization and run for a given config', 'test_selfplay_cfg': 'test the selfplay function by passing a config object with env, model, and optimizer settings', 'refactor_selfplay_entry': 'refactor the selfplay entry point to support additional training modes beyond CFVExp'}
```

## File: facebookresearch_rebel/cfvpy/utils.py

Prompts

```
['build a multi-layer perceptron with configurable hidden size, layers, activation, layer norm, and dropout', 'create a Net2 neural network module for counterfactual value iteration with dice and faces parameters', 'compute the input tensor size given a number of dice faces and dice count', 'compute the output tensor size as num_faces raised to the power of num_dice', 'review the Net2 forward pass that runs packed input through the MLP body then output layer', 'run the CFVExp selfplay training loop with a config to train a CFR value network', 'build a CFR value model from config with optional JIT compilation and half precision', 'create a RecursiveSolvingParams MDP config from a YAML-style dictionary for CFR solving', 'clip gradient norms of model parameters to a max norm value during training', 'get the last action index from a query tensor using one-hot action encoding', 'run the selfplay training loop by calling selfplay(cfg) to instantiate CFVExp and execute training', 'review the CFVExp class run method which orchestrates selfplay training with data loading and optimization', 'summarize the selfplay function that wraps CFVExp initialization and run for a given config', 'test the selfplay function by passing a config object with env, model, and optimizer settings', 'refactor the selfplay entry point to support additional training modes beyond CFVExp', 'create a StopWatchTimer instance to track elapsed time with start and pause methods', 'create a MultiStopWatchTimer to track cumulative timings across multiple named operations', 'run compute_exploitability to evaluate a CFR model by invoking the cfr binary subprocess', 'instantiate a class from a config object using cfg_instantiate with dynamic import', 'create a FractionCounter to accumulate numerator and denominator values and compute their ratio']
```

Usage

```
{'create_stopwatch_timer': 'create a StopWatchTimer instance to track elapsed time with start and pause methods', 'create_multistopwatch_timer': 'create a MultiStopWatchTimer to track cumulative timings across multiple named operations', 'run_compute_exploitability': 'run compute_exploitability to evaluate a CFR model by invoking the cfr binary subprocess', 'instantiate_cfg_class': 'instantiate a class from a config object using cfg_instantiate with dynamic import', 'create_fraction_counter': 'create a FractionCounter to accumulate numerator and denominator values and compute their ratio'}
```

