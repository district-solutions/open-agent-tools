# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/utils/merges/strategies.py

Prompts

```
['merge multiple LoRA adapters using the linear merge strategy with custom weights', 'merge multiple LoRA adapters using the TIES merge strategy with magnitude-based sparsification', 'merge multiple LoRA adapters using the DoReFa random pruning linear merge strategy', 'merge multiple LoRA adapters using the DoReFa random pruning TIES merge strategy', 'create a custom MergeStrategy subclass that implements the merge method for task tensors', 'prune a pytorch tensor using magnitude-based pruning to retain the top-k largest values by density', 'prune a pytorch tensor using random bernoulli masking with an optional rescale to preserve expected value', 'prune a pytorch tensor by specifying magnitude or random method with a given density fraction', 'calculate a majority sign mask across stacked task tensors using total magnitude or frequency method', 'merge multiple task tensors using a majority sign mask and normalize by the number of preserved parameters']
```

Usage

```
{'merge_adapters_linear': 'merge multiple LoRA adapters using the linear merge strategy with custom weights', 'merge_adapters_ties': 'merge multiple LoRA adapters using the TIES merge strategy with magnitude-based sparsification', 'merge_adapters_dare_linear': 'merge multiple LoRA adapters using the DoReFa random pruning linear merge strategy', 'merge_adapters_dare_ties': 'merge multiple LoRA adapters using the DoReFa random pruning TIES merge strategy', 'create_merge_strategy': 'create a custom MergeStrategy subclass that implements the merge method for task tensors'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/utils/merges/utils.py

Prompts

```
['merge multiple LoRA adapters using the linear merge strategy with custom weights', 'merge multiple LoRA adapters using the TIES merge strategy with magnitude-based sparsification', 'merge multiple LoRA adapters using the DoReFa random pruning linear merge strategy', 'merge multiple LoRA adapters using the DoReFa random pruning TIES merge strategy', 'create a custom MergeStrategy subclass that implements the merge method for task tensors', 'prune a pytorch tensor using magnitude-based pruning to retain the top-k largest values by density', 'prune a pytorch tensor using random bernoulli masking with an optional rescale to preserve expected value', 'prune a pytorch tensor by specifying magnitude or random method with a given density fraction', 'calculate a majority sign mask across stacked task tensors using total magnitude or frequency method', 'merge multiple task tensors using a majority sign mask and normalize by the number of preserved parameters']
```

Usage

```
{'prune_tensor_magnitude': 'prune a pytorch tensor using magnitude-based pruning to retain the top-k largest values by density', 'prune_tensor_random': 'prune a pytorch tensor using random bernoulli masking with an optional rescale to preserve expected value', 'prune_tensor_method': 'prune a pytorch tensor by specifying magnitude or random method with a given density fraction', 'calculate_majority_sign_mask': 'calculate a majority sign mask across stacked task tensors using total magnitude or frequency method', 'disjoint_merge_tensors': 'merge multiple task tensors using a majority sign mask and normalize by the number of preserved parameters'}
```

