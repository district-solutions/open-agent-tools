# Agent Python Tools

- repo: facebookresearch/neuralstpp
- repo_uri: https://github.com/facebookresearch/neural_stpp

## File: facebookresearch_neuralstpp/flow_layers/container.py

Prompts

```
['build a python module to run SequentialFlow forward pass on input tensor x through chained flow layers', 'create a SequentialFlow container by passing multiple normalizing flow layer modules as arguments', 'run the SequentialFlow forward method with reverse=True to invert the flow transformation through all layers', 'test the SequentialFlow forward method with logpx argument to track log probability density changes', 'review the SequentialFlow forward method inds parameter to selectively apply a subset of chained layers', 'build a PlanarFlow normalizing flow layer for invertible transformations on nd-dimensional data', 'build a RadialFlow normalizing flow layer for radial invertible transformations on nd-dimensional data', 'build a HypernetworkRadialFlow that uses a hypernetwork to generate radial flow parameters from conditioning inputs', 'review the PlanarFlow forward method to understand how it computes transformations and log-determinant gradients', 'create a learnable Swish activation function module with a trainable beta parameter']
```

Usage

```
{'build_sequentialflow_forward': 'build a python module to run SequentialFlow forward pass on input tensor x through chained flow layers', 'create_sequentialflow_with_layers': 'create a SequentialFlow container by passing multiple normalizing flow layer modules as arguments', 'run_sequentialflow_reverse': 'run the SequentialFlow forward method with reverse=True to invert the flow transformation through all layers', 'test_sequentialflow_logpx': 'test the SequentialFlow forward method with logpx argument to track log probability density changes', 'review_sequentialflow_inds': 'review the SequentialFlow forward method inds parameter to selectively apply a subset of chained layers'}
```

## File: facebookresearch_neuralstpp/flow_layers/planar.py

Prompts

```
['build a python module to run SequentialFlow forward pass on input tensor x through chained flow layers', 'create a SequentialFlow container by passing multiple normalizing flow layer modules as arguments', 'run the SequentialFlow forward method with reverse=True to invert the flow transformation through all layers', 'test the SequentialFlow forward method with logpx argument to track log probability density changes', 'review the SequentialFlow forward method inds parameter to selectively apply a subset of chained layers', 'build a PlanarFlow normalizing flow layer for invertible transformations on nd-dimensional data', 'build a RadialFlow normalizing flow layer for radial invertible transformations on nd-dimensional data', 'build a HypernetworkRadialFlow that uses a hypernetwork to generate radial flow parameters from conditioning inputs', 'review the PlanarFlow forward method to understand how it computes transformations and log-determinant gradients', 'create a learnable Swish activation function module with a trainable beta parameter']
```

Usage

```
{'build_planar_flow': 'build a PlanarFlow normalizing flow layer for invertible transformations on nd-dimensional data', 'build_radial_flow': 'build a RadialFlow normalizing flow layer for radial invertible transformations on nd-dimensional data', 'build_hypernetwork_radial_flow': 'build a HypernetworkRadialFlow that uses a hypernetwork to generate radial flow parameters from conditioning inputs', 'review_planar_flow_forward': 'review the PlanarFlow forward method to understand how it computes transformations and log-determinant gradients', 'create_swish_activation': 'create a learnable Swish activation function module with a trainable beta parameter'}
```

