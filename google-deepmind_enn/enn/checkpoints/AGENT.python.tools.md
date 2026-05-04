# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/checkpoints/cifar10.py

Prompts

```
['create a ResNet18 checkpoint for CIFAR-10 classification using the resnet_18 function', 'create a ResNet110 checkpoint for CIFAR-10 classification using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR-10 using resnet_18_final_epinet', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR-10 using resnet_110_final_epinet', 'create a ResNet constructor for a given config using the _make_resnet_ctor helper function', 'create a ResNet18 EnnCheckpoint for CIFAR100 using the resnet_18 function', 'create a ResNet110 EnnCheckpoint for CIFAR100 using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR100', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR100', 'review the _make_resnet_ctor helper that builds an EnsembleResNetENN constructor from a config', 'create an EnnCheckpoint for a ResNet50 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet101 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet152 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet200 model trained on ImageNet with temperature 0.8', 'create an EpinetCheckpoint with a ResNet50 base model and final-layer episodic network on ImageNet', 'create a load function that downloads ENN checkpoint params and state from a remote URL file', 'download and deserialize ENN checkpoint params and state from a remote npzs file into JAX arrays', 'compute the average logits across ENN samples by converting to probabilities then back to logits', 'build a JIT-compiled sampler that produces multiple ENN logit samples from a checkpoint given inputs and a key', 'create a forward function that averages EpiNet predictions over multiple ENN index samples from a checkpoint']
```

Usage

```
{'create_resnet_18_checkpoint': 'create a ResNet18 checkpoint for CIFAR-10 classification using the resnet_18 function', 'create_resnet_110_checkpoint': 'create a ResNet110 checkpoint for CIFAR-10 classification using the resnet_110 function', 'create_resnet_18_epinet_checkpoint': 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR-10 using resnet_18_final_epinet', 'create_resnet_110_epinet_checkpoint': 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR-10 using resnet_110_final_epinet', 'create_resnet_constructor': 'create a ResNet constructor for a given config using the _make_resnet_ctor helper function'}
```

## File: google-deepmind_enn/enn/checkpoints/cifar100.py

Prompts

```
['create a ResNet18 checkpoint for CIFAR-10 classification using the resnet_18 function', 'create a ResNet110 checkpoint for CIFAR-10 classification using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR-10 using resnet_18_final_epinet', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR-10 using resnet_110_final_epinet', 'create a ResNet constructor for a given config using the _make_resnet_ctor helper function', 'create a ResNet18 EnnCheckpoint for CIFAR100 using the resnet_18 function', 'create a ResNet110 EnnCheckpoint for CIFAR100 using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR100', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR100', 'review the _make_resnet_ctor helper that builds an EnsembleResNetENN constructor from a config', 'create an EnnCheckpoint for a ResNet50 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet101 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet152 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet200 model trained on ImageNet with temperature 0.8', 'create an EpinetCheckpoint with a ResNet50 base model and final-layer episodic network on ImageNet', 'create a load function that downloads ENN checkpoint params and state from a remote URL file', 'download and deserialize ENN checkpoint params and state from a remote npzs file into JAX arrays', 'compute the average logits across ENN samples by converting to probabilities then back to logits', 'build a JIT-compiled sampler that produces multiple ENN logit samples from a checkpoint given inputs and a key', 'create a forward function that averages EpiNet predictions over multiple ENN index samples from a checkpoint']
```

Usage

```
{'create_resnet18_checkpoint': 'create a ResNet18 EnnCheckpoint for CIFAR100 using the resnet_18 function', 'create_resnet110_checkpoint': 'create a ResNet110 EnnCheckpoint for CIFAR100 using the resnet_110 function', 'create_resnet18_epinet_checkpoint': 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR100', 'create_resnet110_epinet_checkpoint': 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR100', 'review_make_resnet_ctor': 'review the _make_resnet_ctor helper that builds an EnsembleResNetENN constructor from a config'}
```

## File: google-deepmind_enn/enn/checkpoints/imagenet.py

Prompts

```
['create a ResNet18 checkpoint for CIFAR-10 classification using the resnet_18 function', 'create a ResNet110 checkpoint for CIFAR-10 classification using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR-10 using resnet_18_final_epinet', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR-10 using resnet_110_final_epinet', 'create a ResNet constructor for a given config using the _make_resnet_ctor helper function', 'create a ResNet18 EnnCheckpoint for CIFAR100 using the resnet_18 function', 'create a ResNet110 EnnCheckpoint for CIFAR100 using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR100', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR100', 'review the _make_resnet_ctor helper that builds an EnsembleResNetENN constructor from a config', 'create an EnnCheckpoint for a ResNet50 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet101 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet152 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet200 model trained on ImageNet with temperature 0.8', 'create an EpinetCheckpoint with a ResNet50 base model and final-layer episodic network on ImageNet', 'create a load function that downloads ENN checkpoint params and state from a remote URL file', 'download and deserialize ENN checkpoint params and state from a remote npzs file into JAX arrays', 'compute the average logits across ENN samples by converting to probabilities then back to logits', 'build a JIT-compiled sampler that produces multiple ENN logit samples from a checkpoint given inputs and a key', 'create a forward function that averages EpiNet predictions over multiple ENN index samples from a checkpoint']
```

Usage

```
{'create_resnet50_checkpoint': 'create an EnnCheckpoint for a ResNet50 model trained on ImageNet with temperature 0.8', 'create_resnet101_checkpoint': 'create an EnnCheckpoint for a ResNet101 model trained on ImageNet with temperature 0.8', 'create_resnet152_checkpoint': 'create an EnnCheckpoint for a ResNet152 model trained on ImageNet with temperature 0.8', 'create_resnet200_checkpoint': 'create an EnnCheckpoint for a ResNet200 model trained on ImageNet with temperature 0.8', 'create_resnet50_epinet_checkpoint': 'create an EpinetCheckpoint with a ResNet50 base model and final-layer episodic network on ImageNet'}
```

## File: google-deepmind_enn/enn/checkpoints/utils.py

Prompts

```
['create a ResNet18 checkpoint for CIFAR-10 classification using the resnet_18 function', 'create a ResNet110 checkpoint for CIFAR-10 classification using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR-10 using resnet_18_final_epinet', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR-10 using resnet_110_final_epinet', 'create a ResNet constructor for a given config using the _make_resnet_ctor helper function', 'create a ResNet18 EnnCheckpoint for CIFAR100 using the resnet_18 function', 'create a ResNet110 EnnCheckpoint for CIFAR100 using the resnet_110 function', 'create a final-layer EpiNet checkpoint with ResNet18 base on CIFAR100', 'create a final-layer EpiNet checkpoint with ResNet110 base on CIFAR100', 'review the _make_resnet_ctor helper that builds an EnsembleResNetENN constructor from a config', 'create an EnnCheckpoint for a ResNet50 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet101 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet152 model trained on ImageNet with temperature 0.8', 'create an EnnCheckpoint for a ResNet200 model trained on ImageNet with temperature 0.8', 'create an EpinetCheckpoint with a ResNet50 base model and final-layer episodic network on ImageNet', 'create a load function that downloads ENN checkpoint params and state from a remote URL file', 'download and deserialize ENN checkpoint params and state from a remote npzs file into JAX arrays', 'compute the average logits across ENN samples by converting to probabilities then back to logits', 'build a JIT-compiled sampler that produces multiple ENN logit samples from a checkpoint given inputs and a key', 'create a forward function that averages EpiNet predictions over multiple ENN index samples from a checkpoint']
```

Usage

```
{'load_enn_params_from_file': 'create a load function that downloads ENN checkpoint params and state from a remote URL file', 'init_enn_from_file': 'download and deserialize ENN checkpoint params and state from a remote npzs file into JAX arrays', 'average_logits_over_samples': 'compute the average logits across ENN samples by converting to probabilities then back to logits', 'make_enn_sampler_from_checkpoint': 'build a JIT-compiled sampler that produces multiple ENN logit samples from a checkpoint given inputs and a key', 'make_epinet_forward_fn': 'create a forward function that averages EpiNet predictions over multiple ENN index samples from a checkpoint'}
```

