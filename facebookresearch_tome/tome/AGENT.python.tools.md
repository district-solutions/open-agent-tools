# Agent Python Tools

- repo: facebookresearch/tome
- repo_uri: https://github.com/facebookresearch/tome

## File: facebookresearch_tome/tome/merge.py

Prompts

```
['build a token merger using bipartite_soft_matching to reduce tokens by cosine similarity with protected class tokens', 'build a token merger using kth_bipartite_soft_matching to merge every kth element with the rest', 'build a token merger using random_bipartite_soft_matching to randomly select and merge r tokens', 'run merge_wavg to apply a merge function with weighted average based on token size', 'run merge_source to track token adjacency between initial tokens and final merged groups', 'benchmark a PyTorch model to measure images per second throughput on a given device', 'benchmark a PyTorch model with float16 autocast enabled for faster inference measurement', 'benchmark a PyTorch model with a custom batch size and input resolution', 'parse a constant integer r value into a per-layer token reduction schedule list', 'parse an r and inflection tuple into a per-layer token reduction schedule with upward or downward trend', 'generate a list of N random RGB color tuples using a fixed random seed', 'generate a colormap with N equidistant colors by setting a custom seed value', 'create a visualization image from a PIL image and torch tensor showing ToMe patch groups', 'create a visualization with a custom patch size for ToMe attention merging groups', 'create a visualization image without skipping the class token in the source tensor']
```

Usage

```
{'build_bipartite_soft_matching': 'build a token merger using bipartite_soft_matching to reduce tokens by cosine similarity with protected class tokens', 'build_kth_bipartite_soft_matching': 'build a token merger using kth_bipartite_soft_matching to merge every kth element with the rest', 'build_random_bipartite_soft_matching': 'build a token merger using random_bipartite_soft_matching to randomly select and merge r tokens', 'run_merge_wavg': 'run merge_wavg to apply a merge function with weighted average based on token size', 'run_merge_source': 'run merge_source to track token adjacency between initial tokens and final merged groups'}
```

## File: facebookresearch_tome/tome/utils.py

Prompts

```
['build a token merger using bipartite_soft_matching to reduce tokens by cosine similarity with protected class tokens', 'build a token merger using kth_bipartite_soft_matching to merge every kth element with the rest', 'build a token merger using random_bipartite_soft_matching to randomly select and merge r tokens', 'run merge_wavg to apply a merge function with weighted average based on token size', 'run merge_source to track token adjacency between initial tokens and final merged groups', 'benchmark a PyTorch model to measure images per second throughput on a given device', 'benchmark a PyTorch model with float16 autocast enabled for faster inference measurement', 'benchmark a PyTorch model with a custom batch size and input resolution', 'parse a constant integer r value into a per-layer token reduction schedule list', 'parse an r and inflection tuple into a per-layer token reduction schedule with upward or downward trend', 'generate a list of N random RGB color tuples using a fixed random seed', 'generate a colormap with N equidistant colors by setting a custom seed value', 'create a visualization image from a PIL image and torch tensor showing ToMe patch groups', 'create a visualization with a custom patch size for ToMe attention merging groups', 'create a visualization image without skipping the class token in the source tensor']
```

Usage

```
{'benchmark_model_throughput': 'benchmark a PyTorch model to measure images per second throughput on a given device', 'benchmark_model_fp16': 'benchmark a PyTorch model with float16 autocast enabled for faster inference measurement', 'benchmark_model_custom_batch': 'benchmark a PyTorch model with a custom batch size and input resolution', 'parse_r_constant': 'parse a constant integer r value into a per-layer token reduction schedule list', 'parse_r_schedule': 'parse an r and inflection tuple into a per-layer token reduction schedule with upward or downward trend'}
```

## File: facebookresearch_tome/tome/vis.py

Prompts

```
['build a token merger using bipartite_soft_matching to reduce tokens by cosine similarity with protected class tokens', 'build a token merger using kth_bipartite_soft_matching to merge every kth element with the rest', 'build a token merger using random_bipartite_soft_matching to randomly select and merge r tokens', 'run merge_wavg to apply a merge function with weighted average based on token size', 'run merge_source to track token adjacency between initial tokens and final merged groups', 'benchmark a PyTorch model to measure images per second throughput on a given device', 'benchmark a PyTorch model with float16 autocast enabled for faster inference measurement', 'benchmark a PyTorch model with a custom batch size and input resolution', 'parse a constant integer r value into a per-layer token reduction schedule list', 'parse an r and inflection tuple into a per-layer token reduction schedule with upward or downward trend', 'generate a list of N random RGB color tuples using a fixed random seed', 'generate a colormap with N equidistant colors by setting a custom seed value', 'create a visualization image from a PIL image and torch tensor showing ToMe patch groups', 'create a visualization with a custom patch size for ToMe attention merging groups', 'create a visualization image without skipping the class token in the source tensor']
```

Usage

```
{'generate_colormap_random_colors': 'generate a list of N random RGB color tuples using a fixed random seed', 'generate_colormap_custom_seed': 'generate a colormap with N equidistant colors by setting a custom seed value', 'make_visualization_tome_groups': 'create a visualization image from a PIL image and torch tensor showing ToMe patch groups', 'make_visualization_custom_patch_size': 'create a visualization with a custom patch size for ToMe attention merging groups', 'make_visualization_no_class_token': 'create a visualization image without skipping the class token in the source tensor'}
```

