# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/arch/builder/fbnet_fpn.py

Prompts

```
['build a feature pyramid network model using FBNetFPNBuilder with an architecture definition and input channels', 'create an FBNetFPNBuilder instance with a MetaBuilder to construct feature pyramid networks', 'run the FBNetFPN forward pass with a list of input tensors to get multi-resolution feature outputs', 'review the get_prev_stages method to understand how previous stage IDs are resolved in the FPN graph', 'refactor the build_stage_combiners method to support additional combiner operations beyond add and choose_right', 'unify an architecture definition dict by parsing block configs, expanding repeats, and flattening stages into a normalized list', 'build a PyTorch nn.Sequential module from a list of unified block configuration dicts with specified input channels', 'build a single neural network block from a block operation name and configuration dict using registered primitives', 'expand repeated block configurations into individual blocks with stride 1 for all repeats after the first', 'calculate the cumulative stride product across all blocks in a unified architecture definition', 'build a multi-input multi-output network backbone from an FBNet architecture definition name', 'create an FBNetBuilder and architecture definition from a given architecture name string', 'run forward pass through MultiIONetBackbone with optional vertical stage0 connection and classification header', 'get the number of paths and stages from an architecture definition dictionary', 'review the MultiIONetBackbone class forward pass logic for multi-path feature fusion and header output']
```

Usage

```
{'build_fbnet_fpn_model': 'build a feature pyramid network model using FBNetFPNBuilder with an architecture definition and input channels', 'create_fbnet_fpn_builder': 'create an FBNetFPNBuilder instance with a MetaBuilder to construct feature pyramid networks', 'run_fbnet_fpn_forward': 'run the FBNetFPN forward pass with a list of input tensors to get multi-resolution feature outputs', 'review_fbnet_fpn_get_prev_stages': 'review the get_prev_stages method to understand how previous stage IDs are resolved in the FPN graph', 'refactor_stage_combiners': 'refactor the build_stage_combiners method to support additional combiner operations beyond add and choose_right'}
```

## File: facebookresearch_mobile-vision/mobile_cv/arch/builder/meta_builder.py

Prompts

```
['build a feature pyramid network model using FBNetFPNBuilder with an architecture definition and input channels', 'create an FBNetFPNBuilder instance with a MetaBuilder to construct feature pyramid networks', 'run the FBNetFPN forward pass with a list of input tensors to get multi-resolution feature outputs', 'review the get_prev_stages method to understand how previous stage IDs are resolved in the FPN graph', 'refactor the build_stage_combiners method to support additional combiner operations beyond add and choose_right', 'unify an architecture definition dict by parsing block configs, expanding repeats, and flattening stages into a normalized list', 'build a PyTorch nn.Sequential module from a list of unified block configuration dicts with specified input channels', 'build a single neural network block from a block operation name and configuration dict using registered primitives', 'expand repeated block configurations into individual blocks with stride 1 for all repeats after the first', 'calculate the cumulative stride product across all blocks in a unified architecture definition', 'build a multi-input multi-output network backbone from an FBNet architecture definition name', 'create an FBNetBuilder and architecture definition from a given architecture name string', 'run forward pass through MultiIONetBackbone with optional vertical stage0 connection and classification header', 'get the number of paths and stages from an architecture definition dictionary', 'review the MultiIONetBackbone class forward pass logic for multi-path feature fusion and header output']
```

Usage

```
{'unify_arch_def': 'unify an architecture definition dict by parsing block configs, expanding repeats, and flattening stages into a normalized list', 'build_blocks': 'build a PyTorch nn.Sequential module from a list of unified block configuration dicts with specified input channels', 'build_block': 'build a single neural network block from a block operation name and configuration dict using registered primitives', 'expand_repeats': 'expand repeated block configurations into individual blocks with stride 1 for all repeats after the first', 'count_strides': 'calculate the cumulative stride product across all blocks in a unified architecture definition'}
```

## File: facebookresearch_mobile-vision/mobile_cv/arch/builder/multi_io.py

Prompts

```
['build a feature pyramid network model using FBNetFPNBuilder with an architecture definition and input channels', 'create an FBNetFPNBuilder instance with a MetaBuilder to construct feature pyramid networks', 'run the FBNetFPN forward pass with a list of input tensors to get multi-resolution feature outputs', 'review the get_prev_stages method to understand how previous stage IDs are resolved in the FPN graph', 'refactor the build_stage_combiners method to support additional combiner operations beyond add and choose_right', 'unify an architecture definition dict by parsing block configs, expanding repeats, and flattening stages into a normalized list', 'build a PyTorch nn.Sequential module from a list of unified block configuration dicts with specified input channels', 'build a single neural network block from a block operation name and configuration dict using registered primitives', 'expand repeated block configurations into individual blocks with stride 1 for all repeats after the first', 'calculate the cumulative stride product across all blocks in a unified architecture definition', 'build a multi-input multi-output network backbone from an FBNet architecture definition name', 'create an FBNetBuilder and architecture definition from a given architecture name string', 'run forward pass through MultiIONetBackbone with optional vertical stage0 connection and classification header', 'get the number of paths and stages from an architecture definition dictionary', 'review the MultiIONetBackbone class forward pass logic for multi-path feature fusion and header output']
```

Usage

```
{'build_multi_io_backbone': 'build a multi-input multi-output network backbone from an FBNet architecture definition name', 'create_fbnet_builder': 'create an FBNetBuilder and architecture definition from a given architecture name string', 'forward_multi_io_backbone': 'run forward pass through MultiIONetBackbone with optional vertical stage0 connection and classification header', 'get_architecture_paths_stages': 'get the number of paths and stages from an architecture definition dictionary', 'review_multi_io_net_backbone': 'review the MultiIONetBackbone class forward pass logic for multi-path feature fusion and header output'}
```

