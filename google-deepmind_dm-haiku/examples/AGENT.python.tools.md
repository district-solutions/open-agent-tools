# Agent Python Tools

- repo: google-deepmind/dm-haiku
- repo_uri: https://github.com/google-deepmind/dm-haiku

## File: google-deepmind_dm-haiku/examples/impala_lite.py

Prompts

```
['run the IMPALA reinforcement learning example with Haiku on the bsuite Catch environment', 'build a SimpleNet Haiku module that outputs policy logits and baseline values from observations', 'create an Agent that selects actions via multinomial sampling from network logits', 'compute the V-trace policy gradient loss with baseline and entropy regularization for trajectories', 'run an actor thread that collects trajectories by interacting with the Catch environment', 'test the impala_lite module by running an integration test with 2 actors and 20 unroll length', 'test the ImpalaLiteTest class using absltest to verify impala_lite integration behavior', 'review the ImpalaLiteTest class and its test_impala_integration method for correctness', 'summarize the impala_lite_test module which contains integration tests for the impala_lite example', 'run the MNIST classifier example to train a LeNet-300-100 MLP on handwritten digit images', 'build a LeNet-300-100 MLP network using Haiku Sequential with Flatten and Linear layers', 'load the MNIST dataset using TensorFlow Datasets with shuffling and batching support', 'train a Haiku network using the Adam optimizer with L2 regularization and exponential moving average', 'evaluate classification accuracy on train and test splits using JIT-compiled evaluation', 'run the MNIST classifier with iterative magnitude-based pruning using Haiku and JAX', 'create a top-k mask keeping the top fraction of values in a JAX array', 'apply existing sparsity masks to Haiku model parameters based on module sparsity predicates', 'generate new sparsity masks for model parameters using a target sparsity fraction and module predicates', 'get total parameter count, non-zero count, and per-tensor sparsity of Haiku model parameters', 'build a Haiku VariationalAutoEncoder with an Encoder and Decoder for binarized MNIST image reconstruction', 'create an Encoder module that encodes images into isotropic Gaussian latent codes with mean and stddev', 'create a Decoder module that decodes latent codes into Bernoulli log-odds over output images', 'run a VAE training loop on binarized MNIST using ELBO loss with Adam optimizer and JAX JIT', 'load and batch the binarized MNIST dataset using TensorFlow Datasets with shuffling and prefetching']
```

Usage

```
{'run_impala_lite': 'run the IMPALA reinforcement learning example with Haiku on the bsuite Catch environment', 'build_simple_net': 'build a SimpleNet Haiku module that outputs policy logits and baseline values from observations', 'create_agent_step': 'create an Agent that selects actions via multinomial sampling from network logits', 'compute_agent_loss': 'compute the V-trace policy gradient loss with baseline and entropy regularization for trajectories', 'run_actor_loop': 'run an actor thread that collects trajectories by interacting with the Catch environment'}
```

## File: google-deepmind_dm-haiku/examples/impala_lite_test.py

Prompts

```
['run the IMPALA reinforcement learning example with Haiku on the bsuite Catch environment', 'build a SimpleNet Haiku module that outputs policy logits and baseline values from observations', 'create an Agent that selects actions via multinomial sampling from network logits', 'compute the V-trace policy gradient loss with baseline and entropy regularization for trajectories', 'run an actor thread that collects trajectories by interacting with the Catch environment', 'test the impala_lite module by running an integration test with 2 actors and 20 unroll length', 'test the ImpalaLiteTest class using absltest to verify impala_lite integration behavior', 'review the ImpalaLiteTest class and its test_impala_integration method for correctness', 'summarize the impala_lite_test module which contains integration tests for the impala_lite example', 'run the MNIST classifier example to train a LeNet-300-100 MLP on handwritten digit images', 'build a LeNet-300-100 MLP network using Haiku Sequential with Flatten and Linear layers', 'load the MNIST dataset using TensorFlow Datasets with shuffling and batching support', 'train a Haiku network using the Adam optimizer with L2 regularization and exponential moving average', 'evaluate classification accuracy on train and test splits using JIT-compiled evaluation', 'run the MNIST classifier with iterative magnitude-based pruning using Haiku and JAX', 'create a top-k mask keeping the top fraction of values in a JAX array', 'apply existing sparsity masks to Haiku model parameters based on module sparsity predicates', 'generate new sparsity masks for model parameters using a target sparsity fraction and module predicates', 'get total parameter count, non-zero count, and per-tensor sparsity of Haiku model parameters', 'build a Haiku VariationalAutoEncoder with an Encoder and Decoder for binarized MNIST image reconstruction', 'create an Encoder module that encodes images into isotropic Gaussian latent codes with mean and stddev', 'create a Decoder module that decodes latent codes into Bernoulli log-odds over output images', 'run a VAE training loop on binarized MNIST using ELBO loss with Adam optimizer and JAX JIT', 'load and batch the binarized MNIST dataset using TensorFlow Datasets with shuffling and prefetching']
```

Usage

```
{'test_impala_integration': 'test the impala_lite module by running an integration test with 2 actors and 20 unroll length', 'run_impala_lite': 'run the impala_lite example with configurable trajectories per actor, number of actors, and unroll length', 'test_ImpalaLiteTest': 'test the ImpalaLiteTest class using absltest to verify impala_lite integration behavior', 'review_ImpalaLiteTest': 'review the ImpalaLiteTest class and its test_impala_integration method for correctness', 'summarize_impala_lite_test': 'summarize the impala_lite_test module which contains integration tests for the impala_lite example'}
```

## File: google-deepmind_dm-haiku/examples/mnist.py

Prompts

```
['run the IMPALA reinforcement learning example with Haiku on the bsuite Catch environment', 'build a SimpleNet Haiku module that outputs policy logits and baseline values from observations', 'create an Agent that selects actions via multinomial sampling from network logits', 'compute the V-trace policy gradient loss with baseline and entropy regularization for trajectories', 'run an actor thread that collects trajectories by interacting with the Catch environment', 'test the impala_lite module by running an integration test with 2 actors and 20 unroll length', 'test the ImpalaLiteTest class using absltest to verify impala_lite integration behavior', 'review the ImpalaLiteTest class and its test_impala_integration method for correctness', 'summarize the impala_lite_test module which contains integration tests for the impala_lite example', 'run the MNIST classifier example to train a LeNet-300-100 MLP on handwritten digit images', 'build a LeNet-300-100 MLP network using Haiku Sequential with Flatten and Linear layers', 'load the MNIST dataset using TensorFlow Datasets with shuffling and batching support', 'train a Haiku network using the Adam optimizer with L2 regularization and exponential moving average', 'evaluate classification accuracy on train and test splits using JIT-compiled evaluation', 'run the MNIST classifier with iterative magnitude-based pruning using Haiku and JAX', 'create a top-k mask keeping the top fraction of values in a JAX array', 'apply existing sparsity masks to Haiku model parameters based on module sparsity predicates', 'generate new sparsity masks for model parameters using a target sparsity fraction and module predicates', 'get total parameter count, non-zero count, and per-tensor sparsity of Haiku model parameters', 'build a Haiku VariationalAutoEncoder with an Encoder and Decoder for binarized MNIST image reconstruction', 'create an Encoder module that encodes images into isotropic Gaussian latent codes with mean and stddev', 'create a Decoder module that decodes latent codes into Bernoulli log-odds over output images', 'run a VAE training loop on binarized MNIST using ELBO loss with Adam optimizer and JAX JIT', 'load and batch the binarized MNIST dataset using TensorFlow Datasets with shuffling and prefetching']
```

Usage

```
{'run_mnist_classifier': 'run the MNIST classifier example to train a LeNet-300-100 MLP on handwritten digit images', 'build_mlp_network': 'build a LeNet-300-100 MLP network using Haiku Sequential with Flatten and Linear layers', 'load_mnist_dataset': 'load the MNIST dataset using TensorFlow Datasets with shuffling and batching support', 'train_network_with_adam': 'train a Haiku network using the Adam optimizer with L2 regularization and exponential moving average', 'evaluate_classification_accuracy': 'evaluate classification accuracy on train and test splits using JIT-compiled evaluation'}
```

## File: google-deepmind_dm-haiku/examples/mnist_pruning.py

Prompts

```
['run the IMPALA reinforcement learning example with Haiku on the bsuite Catch environment', 'build a SimpleNet Haiku module that outputs policy logits and baseline values from observations', 'create an Agent that selects actions via multinomial sampling from network logits', 'compute the V-trace policy gradient loss with baseline and entropy regularization for trajectories', 'run an actor thread that collects trajectories by interacting with the Catch environment', 'test the impala_lite module by running an integration test with 2 actors and 20 unroll length', 'test the ImpalaLiteTest class using absltest to verify impala_lite integration behavior', 'review the ImpalaLiteTest class and its test_impala_integration method for correctness', 'summarize the impala_lite_test module which contains integration tests for the impala_lite example', 'run the MNIST classifier example to train a LeNet-300-100 MLP on handwritten digit images', 'build a LeNet-300-100 MLP network using Haiku Sequential with Flatten and Linear layers', 'load the MNIST dataset using TensorFlow Datasets with shuffling and batching support', 'train a Haiku network using the Adam optimizer with L2 regularization and exponential moving average', 'evaluate classification accuracy on train and test splits using JIT-compiled evaluation', 'run the MNIST classifier with iterative magnitude-based pruning using Haiku and JAX', 'create a top-k mask keeping the top fraction of values in a JAX array', 'apply existing sparsity masks to Haiku model parameters based on module sparsity predicates', 'generate new sparsity masks for model parameters using a target sparsity fraction and module predicates', 'get total parameter count, non-zero count, and per-tensor sparsity of Haiku model parameters', 'build a Haiku VariationalAutoEncoder with an Encoder and Decoder for binarized MNIST image reconstruction', 'create an Encoder module that encodes images into isotropic Gaussian latent codes with mean and stddev', 'create a Decoder module that decodes latent codes into Bernoulli log-odds over output images', 'run a VAE training loop on binarized MNIST using ELBO loss with Adam optimizer and JAX JIT', 'load and batch the binarized MNIST dataset using TensorFlow Datasets with shuffling and prefetching']
```

Usage

```
{'run_mnist_pruning': 'run the MNIST classifier with iterative magnitude-based pruning using Haiku and JAX', 'create_topk_mask': 'create a top-k mask keeping the top fraction of values in a JAX array', 'apply_mask_params': 'apply existing sparsity masks to Haiku model parameters based on module sparsity predicates', 'update_mask_sparsity': 'generate new sparsity masks for model parameters using a target sparsity fraction and module predicates', 'get_sparsity_metrics': 'get total parameter count, non-zero count, and per-tensor sparsity of Haiku model parameters'}
```

## File: google-deepmind_dm-haiku/examples/vae.py

Prompts

```
['run the IMPALA reinforcement learning example with Haiku on the bsuite Catch environment', 'build a SimpleNet Haiku module that outputs policy logits and baseline values from observations', 'create an Agent that selects actions via multinomial sampling from network logits', 'compute the V-trace policy gradient loss with baseline and entropy regularization for trajectories', 'run an actor thread that collects trajectories by interacting with the Catch environment', 'test the impala_lite module by running an integration test with 2 actors and 20 unroll length', 'test the ImpalaLiteTest class using absltest to verify impala_lite integration behavior', 'review the ImpalaLiteTest class and its test_impala_integration method for correctness', 'summarize the impala_lite_test module which contains integration tests for the impala_lite example', 'run the MNIST classifier example to train a LeNet-300-100 MLP on handwritten digit images', 'build a LeNet-300-100 MLP network using Haiku Sequential with Flatten and Linear layers', 'load the MNIST dataset using TensorFlow Datasets with shuffling and batching support', 'train a Haiku network using the Adam optimizer with L2 regularization and exponential moving average', 'evaluate classification accuracy on train and test splits using JIT-compiled evaluation', 'run the MNIST classifier with iterative magnitude-based pruning using Haiku and JAX', 'create a top-k mask keeping the top fraction of values in a JAX array', 'apply existing sparsity masks to Haiku model parameters based on module sparsity predicates', 'generate new sparsity masks for model parameters using a target sparsity fraction and module predicates', 'get total parameter count, non-zero count, and per-tensor sparsity of Haiku model parameters', 'build a Haiku VariationalAutoEncoder with an Encoder and Decoder for binarized MNIST image reconstruction', 'create an Encoder module that encodes images into isotropic Gaussian latent codes with mean and stddev', 'create a Decoder module that decodes latent codes into Bernoulli log-odds over output images', 'run a VAE training loop on binarized MNIST using ELBO loss with Adam optimizer and JAX JIT', 'load and batch the binarized MNIST dataset using TensorFlow Datasets with shuffling and prefetching']
```

Usage

```
{'build_vae_model': 'build a Haiku VariationalAutoEncoder with an Encoder and Decoder for binarized MNIST image reconstruction', 'create_encoder': 'create an Encoder module that encodes images into isotropic Gaussian latent codes with mean and stddev', 'create_decoder': 'create a Decoder module that decodes latent codes into Bernoulli log-odds over output images', 'run_vae_training': 'run a VAE training loop on binarized MNIST using ELBO loss with Adam optimizer and JAX JIT', 'load_dataset': 'load and batch the binarized MNIST dataset using TensorFlow Datasets with shuffling and prefetching'}
```

