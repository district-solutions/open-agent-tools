# Agent Python Tools

- repo: facebookresearch/hiera
- repo_uri: https://github.com/facebookresearch/hiera

## File: facebookresearch_hiera/hiera/benchmarking.py

Prompts

```
['run a benchmark on a PyTorch model to measure throughput in images per second', 'test the benchmark function with float16 autocast enabled for faster inference', 'benchmark a model with a custom input size like 384x384 images', 'benchmark a model using a large batch size to measure throughput at scale', 'review the benchmark function that measures model throughput with warmup runs discarded', 'check if huggingface_hub is installed and meets the minimum version requirement of 0.21.0', 'apply the has_config decorator to a class method to capture init args into self.config', 'load a pretrained PyTorch model from the Hugging Face Hub using from_pretrained', 'save a PyTorch model to a local directory using save_pretrained', 'push a PyTorch model to the Hugging Face Hub using push_to_hub', 'build a Hiera tiny vision transformer model for 224x224 image classification with pretrained weights', 'build a Hiera large vision transformer model for 16x224x224 video classification on Kinetics-400', 'create a MaskUnitAttention module that computes masked or global attention with optional q pooling', 'create a HieraBlock transformer block with attention, q pooling, and MLP with stochastic depth', 'run a forward pass through a Hiera model with optional masking and intermediate feature extraction', 'build a MaskedAutoencoderHiera tiny model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera large model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera base model for 16x224x224 video masked autoencoding on Kinetics-400', 'run the forward_encoder method to encode masked input and get latent representations with multi-scale fusion', 'run the forward_decoder method to reconstruct pixel values from latent representations and mask tokens', 'build a Hiera model with pretrained weights loaded from a specified checkpoint URL', 'create an N-dimensional convolution layer by passing the dimension count to conv_nd', 'test the do_pool function to perform max pooling on unrolled tensor data', 'review the do_masked_conv function to zero out masked regions before convolution', 'refactor the Unroll and Reroll classes to reorder patch embeddings for efficient spatial operations']
```

Usage

```
{'run_benchmark_model': 'run a benchmark on a PyTorch model to measure throughput in images per second', 'test_benchmark_with_fp16': 'test the benchmark function with float16 autocast enabled for faster inference', 'benchmark_custom_input_size': 'benchmark a model with a custom input size like 384x384 images', 'benchmark_with_large_batch': 'benchmark a model using a large batch size to measure throughput at scale', 'review_benchmark_function': 'review the benchmark function that measures model throughput with warmup runs discarded'}
```

## File: facebookresearch_hiera/hiera/hfhub.py

Prompts

```
['run a benchmark on a PyTorch model to measure throughput in images per second', 'test the benchmark function with float16 autocast enabled for faster inference', 'benchmark a model with a custom input size like 384x384 images', 'benchmark a model using a large batch size to measure throughput at scale', 'review the benchmark function that measures model throughput with warmup runs discarded', 'check if huggingface_hub is installed and meets the minimum version requirement of 0.21.0', 'apply the has_config decorator to a class method to capture init args into self.config', 'load a pretrained PyTorch model from the Hugging Face Hub using from_pretrained', 'save a PyTorch model to a local directory using save_pretrained', 'push a PyTorch model to the Hugging Face Hub using push_to_hub', 'build a Hiera tiny vision transformer model for 224x224 image classification with pretrained weights', 'build a Hiera large vision transformer model for 16x224x224 video classification on Kinetics-400', 'create a MaskUnitAttention module that computes masked or global attention with optional q pooling', 'create a HieraBlock transformer block with attention, q pooling, and MLP with stochastic depth', 'run a forward pass through a Hiera model with optional masking and intermediate feature extraction', 'build a MaskedAutoencoderHiera tiny model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera large model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera base model for 16x224x224 video masked autoencoding on Kinetics-400', 'run the forward_encoder method to encode masked input and get latent representations with multi-scale fusion', 'run the forward_decoder method to reconstruct pixel values from latent representations and mask tokens', 'build a Hiera model with pretrained weights loaded from a specified checkpoint URL', 'create an N-dimensional convolution layer by passing the dimension count to conv_nd', 'test the do_pool function to perform max pooling on unrolled tensor data', 'review the do_masked_conv function to zero out masked regions before convolution', 'refactor the Unroll and Reroll classes to reorder patch embeddings for efficient spatial operations']
```

Usage

```
{'check_huggingface_hub_availability': 'check if huggingface_hub is installed and meets the minimum version requirement of 0.21.0', 'use_has_config_decorator': 'apply the has_config decorator to a class method to capture init args into self.config', 'load_pretrained_model_from_hub': 'load a pretrained PyTorch model from the Hugging Face Hub using from_pretrained', 'save_model_to_directory': 'save a PyTorch model to a local directory using save_pretrained', 'push_model_to_hub': 'push a PyTorch model to the Hugging Face Hub using push_to_hub'}
```

## File: facebookresearch_hiera/hiera/hiera.py

Prompts

```
['run a benchmark on a PyTorch model to measure throughput in images per second', 'test the benchmark function with float16 autocast enabled for faster inference', 'benchmark a model with a custom input size like 384x384 images', 'benchmark a model using a large batch size to measure throughput at scale', 'review the benchmark function that measures model throughput with warmup runs discarded', 'check if huggingface_hub is installed and meets the minimum version requirement of 0.21.0', 'apply the has_config decorator to a class method to capture init args into self.config', 'load a pretrained PyTorch model from the Hugging Face Hub using from_pretrained', 'save a PyTorch model to a local directory using save_pretrained', 'push a PyTorch model to the Hugging Face Hub using push_to_hub', 'build a Hiera tiny vision transformer model for 224x224 image classification with pretrained weights', 'build a Hiera large vision transformer model for 16x224x224 video classification on Kinetics-400', 'create a MaskUnitAttention module that computes masked or global attention with optional q pooling', 'create a HieraBlock transformer block with attention, q pooling, and MLP with stochastic depth', 'run a forward pass through a Hiera model with optional masking and intermediate feature extraction', 'build a MaskedAutoencoderHiera tiny model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera large model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera base model for 16x224x224 video masked autoencoding on Kinetics-400', 'run the forward_encoder method to encode masked input and get latent representations with multi-scale fusion', 'run the forward_decoder method to reconstruct pixel values from latent representations and mask tokens', 'build a Hiera model with pretrained weights loaded from a specified checkpoint URL', 'create an N-dimensional convolution layer by passing the dimension count to conv_nd', 'test the do_pool function to perform max pooling on unrolled tensor data', 'review the do_masked_conv function to zero out masked regions before convolution', 'refactor the Unroll and Reroll classes to reorder patch embeddings for efficient spatial operations']
```

Usage

```
{'build_hiera_tiny_image_model': 'build a Hiera tiny vision transformer model for 224x224 image classification with pretrained weights', 'build_hiera_large_video_model': 'build a Hiera large vision transformer model for 16x224x224 video classification on Kinetics-400', 'create_mask_unit_attention': 'create a MaskUnitAttention module that computes masked or global attention with optional q pooling', 'create_hiera_block': 'create a HieraBlock transformer block with attention, q pooling, and MLP with stochastic depth', 'run_hiera_forward_pass': 'run a forward pass through a Hiera model with optional masking and intermediate feature extraction'}
```

## File: facebookresearch_hiera/hiera/hiera_mae.py

Prompts

```
['run a benchmark on a PyTorch model to measure throughput in images per second', 'test the benchmark function with float16 autocast enabled for faster inference', 'benchmark a model with a custom input size like 384x384 images', 'benchmark a model using a large batch size to measure throughput at scale', 'review the benchmark function that measures model throughput with warmup runs discarded', 'check if huggingface_hub is installed and meets the minimum version requirement of 0.21.0', 'apply the has_config decorator to a class method to capture init args into self.config', 'load a pretrained PyTorch model from the Hugging Face Hub using from_pretrained', 'save a PyTorch model to a local directory using save_pretrained', 'push a PyTorch model to the Hugging Face Hub using push_to_hub', 'build a Hiera tiny vision transformer model for 224x224 image classification with pretrained weights', 'build a Hiera large vision transformer model for 16x224x224 video classification on Kinetics-400', 'create a MaskUnitAttention module that computes masked or global attention with optional q pooling', 'create a HieraBlock transformer block with attention, q pooling, and MLP with stochastic depth', 'run a forward pass through a Hiera model with optional masking and intermediate feature extraction', 'build a MaskedAutoencoderHiera tiny model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera large model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera base model for 16x224x224 video masked autoencoding on Kinetics-400', 'run the forward_encoder method to encode masked input and get latent representations with multi-scale fusion', 'run the forward_decoder method to reconstruct pixel values from latent representations and mask tokens', 'build a Hiera model with pretrained weights loaded from a specified checkpoint URL', 'create an N-dimensional convolution layer by passing the dimension count to conv_nd', 'test the do_pool function to perform max pooling on unrolled tensor data', 'review the do_masked_conv function to zero out masked regions before convolution', 'refactor the Unroll and Reroll classes to reorder patch embeddings for efficient spatial operations']
```

Usage

```
{'build_mae_hiera_tiny_224': 'build a MaskedAutoencoderHiera tiny model for 224x224 image masked autoencoding with pretrained weights', 'build_mae_hiera_large_224': 'build a MaskedAutoencoderHiera large model for 224x224 image masked autoencoding with pretrained weights', 'build_mae_hiera_base_16x224': 'build a MaskedAutoencoderHiera base model for 16x224x224 video masked autoencoding on Kinetics-400', 'run_forward_encoder': 'run the forward_encoder method to encode masked input and get latent representations with multi-scale fusion', 'run_forward_decoder': 'run the forward_decoder method to reconstruct pixel values from latent representations and mask tokens'}
```

## File: facebookresearch_hiera/hiera/hiera_utils.py

Prompts

```
['run a benchmark on a PyTorch model to measure throughput in images per second', 'test the benchmark function with float16 autocast enabled for faster inference', 'benchmark a model with a custom input size like 384x384 images', 'benchmark a model using a large batch size to measure throughput at scale', 'review the benchmark function that measures model throughput with warmup runs discarded', 'check if huggingface_hub is installed and meets the minimum version requirement of 0.21.0', 'apply the has_config decorator to a class method to capture init args into self.config', 'load a pretrained PyTorch model from the Hugging Face Hub using from_pretrained', 'save a PyTorch model to a local directory using save_pretrained', 'push a PyTorch model to the Hugging Face Hub using push_to_hub', 'build a Hiera tiny vision transformer model for 224x224 image classification with pretrained weights', 'build a Hiera large vision transformer model for 16x224x224 video classification on Kinetics-400', 'create a MaskUnitAttention module that computes masked or global attention with optional q pooling', 'create a HieraBlock transformer block with attention, q pooling, and MLP with stochastic depth', 'run a forward pass through a Hiera model with optional masking and intermediate feature extraction', 'build a MaskedAutoencoderHiera tiny model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera large model for 224x224 image masked autoencoding with pretrained weights', 'build a MaskedAutoencoderHiera base model for 16x224x224 video masked autoencoding on Kinetics-400', 'run the forward_encoder method to encode masked input and get latent representations with multi-scale fusion', 'run the forward_decoder method to reconstruct pixel values from latent representations and mask tokens', 'build a Hiera model with pretrained weights loaded from a specified checkpoint URL', 'create an N-dimensional convolution layer by passing the dimension count to conv_nd', 'test the do_pool function to perform max pooling on unrolled tensor data', 'review the do_masked_conv function to zero out masked regions before convolution', 'refactor the Unroll and Reroll classes to reorder patch embeddings for efficient spatial operations']
```

Usage

```
{'build_pretrained_model': 'build a Hiera model with pretrained weights loaded from a specified checkpoint URL', 'create_conv_nd': 'create an N-dimensional convolution layer by passing the dimension count to conv_nd', 'test_do_pool': 'test the do_pool function to perform max pooling on unrolled tensor data', 'review_do_masked_conv': 'review the do_masked_conv function to zero out masked regions before convolution', 'refactor_unroll_reroll': 'refactor the Unroll and Reroll classes to reorder patch embeddings for efficient spatial operations'}
```

