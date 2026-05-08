# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/data/ops/chain.py

Prompts

```
['chain multiple datasets together using the chain operation registered with Dataset.register_op', 'create a ChainPolicy instance to sequentially iterate through a list of datasets', 'select the current dataset index from a ChainPolicy for sequential dataset iteration', 'exhaust the current dataset in a ChainPolicy and advance to the next dataset index', 'save the ChainPolicy state to a dictionary using state_dict for checkpointing and resuming', 'create a FilterMap dataset that filters and transforms items using a callable function', 'filter a Dataset to keep only items that match a boolean predicate function', 'map a Dataset to transform each item using a callable function', 'reset a FilterMap dataset back to the beginning of its underlying dataset', 'serialize and deserialize a FilterMap dataset using dill for pickling state', 'create a Mix dataset that combines multiple datasets using a MixPolicy for selection', 'implement a MixPolicy protocol class with initialize, reset, select_dataset, and exhaust methods', 'reset all underlying datasets and the mix policy when restarting iteration', 'iterate through a Mix dataset using next to get samples from selected sub-datasets', 'save and load the state dict of a Mix dataset including all sub-dataset states']
```

Usage

```
{'chain_datasets': 'chain multiple datasets together using the chain operation registered with Dataset.register_op', 'create_chain_policy': 'create a ChainPolicy instance to sequentially iterate through a list of datasets', 'select_dataset': 'select the current dataset index from a ChainPolicy for sequential dataset iteration', 'exhaust_dataset': 'exhaust the current dataset in a ChainPolicy and advance to the next dataset index', 'save_chain_policy_state': 'save the ChainPolicy state to a dictionary using state_dict for checkpointing and resuming'}
```

## File: facebookresearch_cwm/cwm/data/ops/filter_map.py

Prompts

```
['chain multiple datasets together using the chain operation registered with Dataset.register_op', 'create a ChainPolicy instance to sequentially iterate through a list of datasets', 'select the current dataset index from a ChainPolicy for sequential dataset iteration', 'exhaust the current dataset in a ChainPolicy and advance to the next dataset index', 'save the ChainPolicy state to a dictionary using state_dict for checkpointing and resuming', 'create a FilterMap dataset that filters and transforms items using a callable function', 'filter a Dataset to keep only items that match a boolean predicate function', 'map a Dataset to transform each item using a callable function', 'reset a FilterMap dataset back to the beginning of its underlying dataset', 'serialize and deserialize a FilterMap dataset using dill for pickling state', 'create a Mix dataset that combines multiple datasets using a MixPolicy for selection', 'implement a MixPolicy protocol class with initialize, reset, select_dataset, and exhaust methods', 'reset all underlying datasets and the mix policy when restarting iteration', 'iterate through a Mix dataset using next to get samples from selected sub-datasets', 'save and load the state dict of a Mix dataset including all sub-dataset states']
```

Usage

```
{'create_filtermap_dataset': 'create a FilterMap dataset that filters and transforms items using a callable function', 'filter_dataset_items': 'filter a Dataset to keep only items that match a boolean predicate function', 'map_dataset_items': 'map a Dataset to transform each item using a callable function', 'reset_filtermap_position': 'reset a FilterMap dataset back to the beginning of its underlying dataset', 'serialize_filtermap_state': 'serialize and deserialize a FilterMap dataset using dill for pickling state'}
```

## File: facebookresearch_cwm/cwm/data/ops/mix.py

Prompts

```
['chain multiple datasets together using the chain operation registered with Dataset.register_op', 'create a ChainPolicy instance to sequentially iterate through a list of datasets', 'select the current dataset index from a ChainPolicy for sequential dataset iteration', 'exhaust the current dataset in a ChainPolicy and advance to the next dataset index', 'save the ChainPolicy state to a dictionary using state_dict for checkpointing and resuming', 'create a FilterMap dataset that filters and transforms items using a callable function', 'filter a Dataset to keep only items that match a boolean predicate function', 'map a Dataset to transform each item using a callable function', 'reset a FilterMap dataset back to the beginning of its underlying dataset', 'serialize and deserialize a FilterMap dataset using dill for pickling state', 'create a Mix dataset that combines multiple datasets using a MixPolicy for selection', 'implement a MixPolicy protocol class with initialize, reset, select_dataset, and exhaust methods', 'reset all underlying datasets and the mix policy when restarting iteration', 'iterate through a Mix dataset using next to get samples from selected sub-datasets', 'save and load the state dict of a Mix dataset including all sub-dataset states']
```

Usage

```
{'create_Mix_dataset': 'create a Mix dataset that combines multiple datasets using a MixPolicy for selection', 'implement_MixPolicy_protocol': 'implement a MixPolicy protocol class with initialize, reset, select_dataset, and exhaust methods', 'reset_Mix_datasets': 'reset all underlying datasets and the mix policy when restarting iteration', 'iterate_Mix_next': 'iterate through a Mix dataset using next to get samples from selected sub-datasets', 'save_load_Mix_state': 'save and load the state dict of a Mix dataset including all sub-dataset states'}
```

