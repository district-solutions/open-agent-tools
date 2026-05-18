# Agent Python Tools

- repo: facebookresearch/multigrain
- repo_uri: https://github.com/facebookresearch/multigrain

## File: facebookresearch_multigrain/multigrain/backbones/backbone.py

Prompts

```
['build a BackBone module using resnet50 as the base network for feature extraction and classification', 'build a BackBone module using senet154 as the base network with pre-classifier support', 'run the BackBone forward pass on a single tensor to get embedding and classifier output', 'run the BackBone forward pass on a list of unequal-sized tensors for batched feature extraction', 'review the BackBone class to understand how whitening is applied to embeddings before classification', 'build a NASNet-A-Mobile model with monkey-patched cells that support arbitrary image shapes', 'review the CellStem0 forward pass that uses shrink_sum and shrink_cat for arbitrary shapes', 'review the CellStem1 forward pass with dual-path processing and shrink operations', 'review the NormalCell forward pass with conv_prev_1x1 and conv_1x1 input paths', 'review the ReductionCell0 forward pass that reduces spatial dimensions with shrink operations', 'refactor the nasnetamobile function to monkey-patch all six cell forward methods before model creation', 'build a PNASNet-5-Large model with a custom number of classes using pnasnet5large', 'create a function that shrinks tensors to a common size and sums them together', 'create a function that shrinks tensors to a common size and concatenates them along a dimension', 'review the cell_forward monkey-patch that adds cropping operations before additions and concatenations in PNASNet cells', 'test the equal_except function that compares two tuples and returns True if they match except on an optional index']
```

Usage

```
{'build_BackBone_with_resnet': 'build a BackBone module using resnet50 as the base network for feature extraction and classification', 'build_BackBone_with_senet': 'build a BackBone module using senet154 as the base network with pre-classifier support', 'run_BackBone_forward_single': 'run the BackBone forward pass on a single tensor to get embedding and classifier output', 'run_BackBone_forward_list': 'run the BackBone forward pass on a list of unequal-sized tensors for batched feature extraction', 'review_BackBone_whitening': 'review the BackBone class to understand how whitening is applied to embeddings before classification'}
```

## File: facebookresearch_multigrain/multigrain/backbones/nasnet_mobile.py

Prompts

```
['build a BackBone module using resnet50 as the base network for feature extraction and classification', 'build a BackBone module using senet154 as the base network with pre-classifier support', 'run the BackBone forward pass on a single tensor to get embedding and classifier output', 'run the BackBone forward pass on a list of unequal-sized tensors for batched feature extraction', 'review the BackBone class to understand how whitening is applied to embeddings before classification', 'build a NASNet-A-Mobile model with monkey-patched cells that support arbitrary image shapes', 'review the CellStem0 forward pass that uses shrink_sum and shrink_cat for arbitrary shapes', 'review the CellStem1 forward pass with dual-path processing and shrink operations', 'review the NormalCell forward pass with conv_prev_1x1 and conv_1x1 input paths', 'review the ReductionCell0 forward pass that reduces spatial dimensions with shrink operations', 'refactor the nasnetamobile function to monkey-patch all six cell forward methods before model creation', 'build a PNASNet-5-Large model with a custom number of classes using pnasnet5large', 'create a function that shrinks tensors to a common size and sums them together', 'create a function that shrinks tensors to a common size and concatenates them along a dimension', 'review the cell_forward monkey-patch that adds cropping operations before additions and concatenations in PNASNet cells', 'test the equal_except function that compares two tuples and returns True if they match except on an optional index']
```

Usage

```
{'build_nasnet_mobile_model': 'build a NASNet-A-Mobile model with monkey-patched cells that support arbitrary image shapes', 'review_CellStem0_forward': 'review the CellStem0 forward pass that uses shrink_sum and shrink_cat for arbitrary shapes', 'review_CellStem1_forward': 'review the CellStem1 forward pass with dual-path processing and shrink operations', 'review_NormalCell_forward': 'review the NormalCell forward pass with conv_prev_1x1 and conv_1x1 input paths', 'review_ReductionCell0_forward': 'review the ReductionCell0 forward pass that reduces spatial dimensions with shrink operations', 'refactor_nasnetamobile_monkey_patch': 'refactor the nasnetamobile function to monkey-patch all six cell forward methods before model creation'}
```

## File: facebookresearch_multigrain/multigrain/backbones/pnasnet.py

Prompts

```
['build a BackBone module using resnet50 as the base network for feature extraction and classification', 'build a BackBone module using senet154 as the base network with pre-classifier support', 'run the BackBone forward pass on a single tensor to get embedding and classifier output', 'run the BackBone forward pass on a list of unequal-sized tensors for batched feature extraction', 'review the BackBone class to understand how whitening is applied to embeddings before classification', 'build a NASNet-A-Mobile model with monkey-patched cells that support arbitrary image shapes', 'review the CellStem0 forward pass that uses shrink_sum and shrink_cat for arbitrary shapes', 'review the CellStem1 forward pass with dual-path processing and shrink operations', 'review the NormalCell forward pass with conv_prev_1x1 and conv_1x1 input paths', 'review the ReductionCell0 forward pass that reduces spatial dimensions with shrink operations', 'refactor the nasnetamobile function to monkey-patch all six cell forward methods before model creation', 'build a PNASNet-5-Large model with a custom number of classes using pnasnet5large', 'create a function that shrinks tensors to a common size and sums them together', 'create a function that shrinks tensors to a common size and concatenates them along a dimension', 'review the cell_forward monkey-patch that adds cropping operations before additions and concatenations in PNASNet cells', 'test the equal_except function that compares two tuples and returns True if they match except on an optional index']
```

Usage

```
{'build_pnasnet5large_model': 'build a PNASNet-5-Large model with a custom number of classes using pnasnet5large', 'create_shrink_sum': 'create a function that shrinks tensors to a common size and sums them together', 'create_shrink_cat': 'create a function that shrinks tensors to a common size and concatenates them along a dimension', 'review_cell_forward': 'review the cell_forward monkey-patch that adds cropping operations before additions and concatenations in PNASNet cells', 'test_equal_except': 'test the equal_except function that compares two tuples and returns True if they match except on an optional index'}
```

