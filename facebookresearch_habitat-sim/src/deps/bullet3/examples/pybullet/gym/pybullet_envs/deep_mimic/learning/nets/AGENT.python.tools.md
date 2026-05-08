# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/deep_mimic/learning/nets/fc_2layers_1024units.py

Prompts

```
['build a 2-layer fully connected network with 1024 and 512 units using ReLU activation', 'build a 2-layer fully connected network with variable reuse enabled for shared weights', 'review the build_net function to understand its layer configuration and activation choices', 'refactor the build_net function to parameterize the layer sizes instead of hardcoding them', 'test the build_net function to verify input tensor concatenation along the last axis', 'build a neural network using the fc_2layers_1024units architecture with input tensors', 'review the build_net factory function that routes to registered network architectures', 'test the build_net function to verify it raises an assertion on unsupported net names', 'summarize the net_builder module that provides a factory interface for building neural networks']
```

Usage

```
{'build_net_fc_2layers': 'build a 2-layer fully connected network with 1024 and 512 units using ReLU activation', 'build_net_with_reuse': 'build a 2-layer fully connected network with variable reuse enabled for shared weights', 'review_build_net': 'review the build_net function to understand its layer configuration and activation choices', 'refactor_build_net_layers': 'refactor the build_net function to parameterize the layer sizes instead of hardcoding them', 'test_build_net_concat': 'test the build_net function to verify input tensor concatenation along the last axis'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/deep_mimic/learning/nets/net_builder.py

Prompts

```
['build a 2-layer fully connected network with 1024 and 512 units using ReLU activation', 'build a 2-layer fully connected network with variable reuse enabled for shared weights', 'review the build_net function to understand its layer configuration and activation choices', 'refactor the build_net function to parameterize the layer sizes instead of hardcoding them', 'test the build_net function to verify input tensor concatenation along the last axis', 'build a neural network using the fc_2layers_1024units architecture with input tensors', 'review the build_net factory function that routes to registered network architectures', 'test the build_net function to verify it raises an assertion on unsupported net names', 'summarize the net_builder module that provides a factory interface for building neural networks']
```

Usage

```
{'build_net_with_fc_2layers': 'build a neural network using the fc_2layers_1024units architecture with input tensors', 'build_net_with_reuse': 'build a neural network with variable reuse enabled for shared graph scopes', 'review_build_net_factory': 'review the build_net factory function that routes to registered network architectures', 'test_build_net_unsupported': 'test the build_net function to verify it raises an assertion on unsupported net names', 'summarize_net_builder': 'summarize the net_builder module that provides a factory interface for building neural networks'}
```

