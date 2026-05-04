# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/experiments/memory_size/analysis.py

Prompts

```
['run score on a pandas DataFrame grouped by num_bits to get a single memory performance float', 'run plot_learning on a DataFrame to visualize average return over time grouped by num_bits', 'run plot_scale on a DataFrame to visualize regret ratio scaling across num_bits values', 'run plot_seeds on a DataFrame to plot individual run returns colored by num_bits', 'review the NUM_EPISODES and TAGS constants imported from the memory_size sweep module', 'load a MemoryChain environment with a specified number of bits and optional seed for reproducibility', 'run the memory size diagnostic experiment by calling load with varying num_bits values from the sweep settings', 'test an RL agent against the MemoryChain environment by loading it with load(num_bits) and stepping through episodes', 'review the MemoryChain class in memory_chain.py to understand observation structure and reward logic for the memory task', 'summarize the sweep settings in sweep.py showing log-spaced num_bits values from 1 to 50 for the memory experiment']
```

Usage

```
{'run_score': 'run score on a pandas DataFrame grouped by num_bits to get a single memory performance float', 'run_plot_learning': 'run plot_learning on a DataFrame to visualize average return over time grouped by num_bits', 'run_plot_scale': 'run plot_scale on a DataFrame to visualize regret ratio scaling across num_bits values', 'run_plot_seeds': 'run plot_seeds on a DataFrame to plot individual run returns colored by num_bits', 'review_constants': 'review the NUM_EPISODES and TAGS constants imported from the memory_size sweep module'}
```

## File: google-deepmind_bsuite/bsuite/experiments/memory_size/memory_size.py

Prompts

```
['run score on a pandas DataFrame grouped by num_bits to get a single memory performance float', 'run plot_learning on a DataFrame to visualize average return over time grouped by num_bits', 'run plot_scale on a DataFrame to visualize regret ratio scaling across num_bits values', 'run plot_seeds on a DataFrame to plot individual run returns colored by num_bits', 'review the NUM_EPISODES and TAGS constants imported from the memory_size sweep module', 'load a MemoryChain environment with a specified number of bits and optional seed for reproducibility', 'run the memory size diagnostic experiment by calling load with varying num_bits values from the sweep settings', 'test an RL agent against the MemoryChain environment by loading it with load(num_bits) and stepping through episodes', 'review the MemoryChain class in memory_chain.py to understand observation structure and reward logic for the memory task', 'summarize the sweep settings in sweep.py showing log-spaced num_bits values from 1 to 50 for the memory experiment']
```

Usage

```
{'load_memory_chain_env': 'load a MemoryChain environment with a specified number of bits and optional seed for reproducibility', 'run_memory_size_experiment': 'run the memory size diagnostic experiment by calling load with varying num_bits values from the sweep settings', 'test_memory_chain_agent': 'test an RL agent against the MemoryChain environment by loading it with load(num_bits) and stepping through episodes', 'review_memory_chain_implementation': 'review the MemoryChain class in memory_chain.py to understand observation structure and reward logic for the memory task', 'summarize_memory_size_sweep': 'summarize the sweep settings in sweep.py showing log-spaced num_bits values from 1 to 50 for the memory experiment'}
```

