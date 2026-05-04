# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/kfac_ferminet_alpha/tests/common.py

Prompts

```
['build a fully connected layer that multiplies input by weights and adds bias', 'initialize a standard autoencoder with Glorot uniform weights for a given data shape', 'test the autoencoder forward pass by evaluating losses and intermediate layer values', 'refactor the autoencoder to swap tanh activation for a different nonlinearity', 'review how the autoencoder registers normal predictive distributions and computes squared losses', 'test the autoencoder model by comparing JAXPR graphs between auto-registered and manually tagged versions', 'run a tagged autoencoder model with fully connected layers and normal predictive distribution loss', 'compare JAXPR equation graphs to verify variable counts and primitives match between two models', 'register a dense layer with input, output, weight, and bias parameters for KFAC tagging', 'auto-register tags on a model function using tag_graph_matcher for JAXPR analysis', 'test the tracer module JVP computation against jax.jvp for autoencoder loss functions', 'test the tracer module VJP computation against jax.vjp for autoencoder loss functions', 'test the tracer module HVP computation against jax.grad for autoencoder loss functions', 'test the tracer estimator VJP against tag graph matcher for layer-wise tangent info', 'test the generate_data static method to produce params data and tangents for tracer tests']
```

Usage

```
{'build_fully_connected_layer': 'build a fully connected layer that multiplies input by weights and adds bias', 'init_autoencoder': 'initialize a standard autoencoder with Glorot uniform weights for a given data shape', 'test_autoencoder_forward_pass': 'test the autoencoder forward pass by evaluating losses and intermediate layer values', 'refactor_autoencoder_nonlinearity': 'refactor the autoencoder to swap tanh activation for a different nonlinearity', 'review_loss_registration': 'review how the autoencoder registers normal predictive distributions and computes squared losses'}
```

## File: google-deepmind_deepmind-research/kfac_ferminet_alpha/tests/graph_matcher_test.py

Prompts

```
['build a fully connected layer that multiplies input by weights and adds bias', 'initialize a standard autoencoder with Glorot uniform weights for a given data shape', 'test the autoencoder forward pass by evaluating losses and intermediate layer values', 'refactor the autoencoder to swap tanh activation for a different nonlinearity', 'review how the autoencoder registers normal predictive distributions and computes squared losses', 'test the autoencoder model by comparing JAXPR graphs between auto-registered and manually tagged versions', 'run a tagged autoencoder model with fully connected layers and normal predictive distribution loss', 'compare JAXPR equation graphs to verify variable counts and primitives match between two models', 'register a dense layer with input, output, weight, and bias parameters for KFAC tagging', 'auto-register tags on a model function using tag_graph_matcher for JAXPR analysis', 'test the tracer module JVP computation against jax.jvp for autoencoder loss functions', 'test the tracer module VJP computation against jax.vjp for autoencoder loss functions', 'test the tracer module HVP computation against jax.grad for autoencoder loss functions', 'test the tracer estimator VJP against tag graph matcher for layer-wise tangent info', 'test the generate_data static method to produce params data and tangents for tracer tests']
```

Usage

```
{'test_graph_matcher_autoencoder': 'test the autoencoder model by comparing JAXPR graphs between auto-registered and manually tagged versions', 'run_tagged_autoencoder': 'run a tagged autoencoder model with fully connected layers and normal predictive distribution loss', 'compare_jaxpr_graphs': 'compare JAXPR equation graphs to verify variable counts and primitives match between two models', 'register_dense_layer_tags': 'register a dense layer with input, output, weight, and bias parameters for KFAC tagging', 'auto_register_tags': 'auto-register tags on a model function using tag_graph_matcher for JAXPR analysis'}
```

## File: google-deepmind_deepmind-research/kfac_ferminet_alpha/tests/tracer_test.py

Prompts

```
['build a fully connected layer that multiplies input by weights and adds bias', 'initialize a standard autoencoder with Glorot uniform weights for a given data shape', 'test the autoencoder forward pass by evaluating losses and intermediate layer values', 'refactor the autoencoder to swap tanh activation for a different nonlinearity', 'review how the autoencoder registers normal predictive distributions and computes squared losses', 'test the autoencoder model by comparing JAXPR graphs between auto-registered and manually tagged versions', 'run a tagged autoencoder model with fully connected layers and normal predictive distribution loss', 'compare JAXPR equation graphs to verify variable counts and primitives match between two models', 'register a dense layer with input, output, weight, and bias parameters for KFAC tagging', 'auto-register tags on a model function using tag_graph_matcher for JAXPR analysis', 'test the tracer module JVP computation against jax.jvp for autoencoder loss functions', 'test the tracer module VJP computation against jax.vjp for autoencoder loss functions', 'test the tracer module HVP computation against jax.grad for autoencoder loss functions', 'test the tracer estimator VJP against tag graph matcher for layer-wise tangent info', 'test the generate_data static method to produce params data and tangents for tracer tests']
```

Usage

```
{'test_tracer_jvp': 'test the tracer module JVP computation against jax.jvp for autoencoder loss functions', 'test_tracer_vjp': 'test the tracer module VJP computation against jax.vjp for autoencoder loss functions', 'test_tracer_hvp': 'test the tracer module HVP computation against jax.grad for autoencoder loss functions', 'test_trace_estimator': 'test the tracer estimator VJP against tag graph matcher for layer-wise tangent info', 'test_generate_data': 'test the generate_data static method to produce params data and tangents for tracer tests'}
```

