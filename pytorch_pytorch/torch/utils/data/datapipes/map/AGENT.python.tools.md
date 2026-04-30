# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/utils/data/datapipes/map/callable.py

Prompts

```
['create a MapperMapDataPipe that applies a function to each item from a source MapDataPipe', 'create a default_fn that returns each input data item directly without transformation', 'build a datapipe chain that maps a function over each element using the map functional decorator', 'test MapperMapDataPipe __getitem__ applies the function to items by index', 'test MapperMapDataPipe __len__ delegates to the source datapipe length', 'create a ShufflerIterDataPipe to shuffle a MapDataPipe using random indices', 'test the set_seed method to set a reproducible random seed for shuffling', 'test the set_shuffle method to enable or disable shuffling on a datapipe', 'test the reset method to re-shuffle a datapipe with a deterministic or random seed', 'build a datapipe shuffle pipeline by chaining shuffle and set_seed on a MapDataPipe']
```

Usage

```
{'create_MapperMapDataPipe': 'create a MapperMapDataPipe that applies a function to each item from a source MapDataPipe', 'create_default_fn': 'create a default_fn that returns each input data item directly without transformation', 'build_datapipe_map': 'build a datapipe chain that maps a function over each element using the map functional decorator', 'test_MapperMapDataPipe': 'test MapperMapDataPipe __getitem__ applies the function to items by index', 'test_MapperMapDataPipe_len': 'test MapperMapDataPipe __len__ delegates to the source datapipe length'}
```

## File: pytorch_pytorch/torch/utils/data/datapipes/map/combinatorics.py

Prompts

```
['create a MapperMapDataPipe that applies a function to each item from a source MapDataPipe', 'create a default_fn that returns each input data item directly without transformation', 'build a datapipe chain that maps a function over each element using the map functional decorator', 'test MapperMapDataPipe __getitem__ applies the function to items by index', 'test MapperMapDataPipe __len__ delegates to the source datapipe length', 'create a ShufflerIterDataPipe to shuffle a MapDataPipe using random indices', 'test the set_seed method to set a reproducible random seed for shuffling', 'test the set_shuffle method to enable or disable shuffling on a datapipe', 'test the reset method to re-shuffle a datapipe with a deterministic or random seed', 'build a datapipe shuffle pipeline by chaining shuffle and set_seed on a MapDataPipe']
```

Usage

```
{'create_ShubberIterDataPipe': 'create a ShufflerIterDataPipe to shuffle a MapDataPipe using random indices', 'test_set_seed': 'test the set_seed method to set a reproducible random seed for shuffling', 'test_set_shuffle': 'test the set_shuffle method to enable or disable shuffling on a datapipe', 'test_reset': 'test the reset method to re-shuffle a datapipe with a deterministic or random seed', 'build_shuffle_pipeline': 'build a datapipe shuffle pipeline by chaining shuffle and set_seed on a MapDataPipe'}
```

