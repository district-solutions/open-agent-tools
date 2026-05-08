# Agent Python Tools

- repo: facebookresearch/imagenet-adversarial-training
- repo_uri: https://github.com/facebookresearch/imagenet-adversarial-training

## File: facebookresearch_imagenet-adversarial-training/adv_model.py

Prompts

```
['create a PGDAttacker with num_iter, epsilon, step_size, and prob_start_from_clean parameters', 'run the PGDAttacker attack method on clean images with labels and a model function', 'build an AdvImageNetModel graph that generates adversarial images and computes loss with label smoothing', 'get an inference tower function from AdvImageNetModel that generates adversarial images and classifies them', 'compute the attack success rate by comparing model predictions against target labels', 'train a ResNet model on ImageNet with PGD adversarial training using Horovod distributed training', 'evaluate a trained model on ImageNet validation set with classification error and attack success rate', 'run inference on a directory of images and save predictions to a text file', 'create a distributed evaluation callback with a tower function and epoch-based condition', 'evaluate model robustness using PGD attacker with configurable iterations, epsilon, and step size', 'build a ResNetModel with a specified depth to get logits from an image tensor', 'build a ResNetDenoiseModel that adds denoising blocks after each residual group for adversarial robustness', 'build a ResNeXtDenoiseAllModel that applies non-local denoising after every residual block', 'review the ResNetModel get_logits method to understand how the ResNet backbone processes images', 'review the ResNeXtDenoiseAllModel block_func to see how denoising is applied after each bottleneck', 'build a ResNet backbone model with configurable blocks and group functions for ImageNet classification', 'create a ResNet bottleneck block with grouped convolutions and zero-initialized batch normalization', 'create a feature denoising module using non-local operations with optional embedding and softmax', 'build a non-local attention operation with configurable embedding and dot-product or softmax modes', 'create a ResNet group that stacks multiple bottleneck blocks with configurable stride and features']
```

Usage

```
{'create_PGDAttacker': 'create a PGDAttacker with num_iter, epsilon, step_size, and prob_start_from_clean parameters', 'run_PGDAttacker_attack': 'run the PGDAttacker attack method on clean images with labels and a model function', 'build_AdvImageNetModel_graph': 'build an AdvImageNetModel graph that generates adversarial images and computes loss with label smoothing', 'get_AdvImageNetModel_inference_func': 'get an inference tower function from AdvImageNetModel that generates adversarial images and classifies them', 'compute_AdvImageNetModel_attack_success': 'compute the attack success rate by comparing model predictions against target labels'}
```

## File: facebookresearch_imagenet-adversarial-training/main.py

Prompts

```
['create a PGDAttacker with num_iter, epsilon, step_size, and prob_start_from_clean parameters', 'run the PGDAttacker attack method on clean images with labels and a model function', 'build an AdvImageNetModel graph that generates adversarial images and computes loss with label smoothing', 'get an inference tower function from AdvImageNetModel that generates adversarial images and classifies them', 'compute the attack success rate by comparing model predictions against target labels', 'train a ResNet model on ImageNet with PGD adversarial training using Horovod distributed training', 'evaluate a trained model on ImageNet validation set with classification error and attack success rate', 'run inference on a directory of images and save predictions to a text file', 'create a distributed evaluation callback with a tower function and epoch-based condition', 'evaluate model robustness using PGD attacker with configurable iterations, epsilon, and step size', 'build a ResNetModel with a specified depth to get logits from an image tensor', 'build a ResNetDenoiseModel that adds denoising blocks after each residual group for adversarial robustness', 'build a ResNeXtDenoiseAllModel that applies non-local denoising after every residual block', 'review the ResNetModel get_logits method to understand how the ResNet backbone processes images', 'review the ResNeXtDenoiseAllModel block_func to see how denoising is applied after each bottleneck', 'build a ResNet backbone model with configurable blocks and group functions for ImageNet classification', 'create a ResNet bottleneck block with grouped convolutions and zero-initialized batch normalization', 'create a feature denoising module using non-local operations with optional embedding and softmax', 'build a non-local attention operation with configurable embedding and dot-product or softmax modes', 'create a ResNet group that stacks multiple bottleneck blocks with configurable stride and features']
```

Usage

```
{'train_adversarial_model': 'train a ResNet model on ImageNet with PGD adversarial training using Horovod distributed training', 'evaluate_model_on_imagenet': 'evaluate a trained model on ImageNet validation set with classification error and attack success rate', 'run_inference_on_images': 'run inference on a directory of images and save predictions to a text file', 'create_eval_callback': 'create a distributed evaluation callback with a tower function and epoch-based condition', 'run_pgd_attack_evaluation': 'evaluate model robustness using PGD attacker with configurable iterations, epsilon, and step size'}
```

## File: facebookresearch_imagenet-adversarial-training/nets.py

Prompts

```
['create a PGDAttacker with num_iter, epsilon, step_size, and prob_start_from_clean parameters', 'run the PGDAttacker attack method on clean images with labels and a model function', 'build an AdvImageNetModel graph that generates adversarial images and computes loss with label smoothing', 'get an inference tower function from AdvImageNetModel that generates adversarial images and classifies them', 'compute the attack success rate by comparing model predictions against target labels', 'train a ResNet model on ImageNet with PGD adversarial training using Horovod distributed training', 'evaluate a trained model on ImageNet validation set with classification error and attack success rate', 'run inference on a directory of images and save predictions to a text file', 'create a distributed evaluation callback with a tower function and epoch-based condition', 'evaluate model robustness using PGD attacker with configurable iterations, epsilon, and step size', 'build a ResNetModel with a specified depth to get logits from an image tensor', 'build a ResNetDenoiseModel that adds denoising blocks after each residual group for adversarial robustness', 'build a ResNeXtDenoiseAllModel that applies non-local denoising after every residual block', 'review the ResNetModel get_logits method to understand how the ResNet backbone processes images', 'review the ResNeXtDenoiseAllModel block_func to see how denoising is applied after each bottleneck', 'build a ResNet backbone model with configurable blocks and group functions for ImageNet classification', 'create a ResNet bottleneck block with grouped convolutions and zero-initialized batch normalization', 'create a feature denoising module using non-local operations with optional embedding and softmax', 'build a non-local attention operation with configurable embedding and dot-product or softmax modes', 'create a ResNet group that stacks multiple bottleneck blocks with configurable stride and features']
```

Usage

```
{'build_resnet_model': 'build a ResNetModel with a specified depth to get logits from an image tensor', 'build_resnet_denoise_model': 'build a ResNetDenoiseModel that adds denoising blocks after each residual group for adversarial robustness', 'build_resnext_denoise_all_model': 'build a ResNeXtDenoiseAllModel that applies non-local denoising after every residual block', 'review_resnet_model_get_logits': 'review the ResNetModel get_logits method to understand how the ResNet backbone processes images', 'review_resnext_denoise_all_model_block_func': 'review the ResNeXtDenoiseAllModel block_func to see how denoising is applied after each bottleneck'}
```

## File: facebookresearch_imagenet-adversarial-training/resnet_model.py

Prompts

```
['create a PGDAttacker with num_iter, epsilon, step_size, and prob_start_from_clean parameters', 'run the PGDAttacker attack method on clean images with labels and a model function', 'build an AdvImageNetModel graph that generates adversarial images and computes loss with label smoothing', 'get an inference tower function from AdvImageNetModel that generates adversarial images and classifies them', 'compute the attack success rate by comparing model predictions against target labels', 'train a ResNet model on ImageNet with PGD adversarial training using Horovod distributed training', 'evaluate a trained model on ImageNet validation set with classification error and attack success rate', 'run inference on a directory of images and save predictions to a text file', 'create a distributed evaluation callback with a tower function and epoch-based condition', 'evaluate model robustness using PGD attacker with configurable iterations, epsilon, and step size', 'build a ResNetModel with a specified depth to get logits from an image tensor', 'build a ResNetDenoiseModel that adds denoising blocks after each residual group for adversarial robustness', 'build a ResNeXtDenoiseAllModel that applies non-local denoising after every residual block', 'review the ResNetModel get_logits method to understand how the ResNet backbone processes images', 'review the ResNeXtDenoiseAllModel block_func to see how denoising is applied after each bottleneck', 'build a ResNet backbone model with configurable blocks and group functions for ImageNet classification', 'create a ResNet bottleneck block with grouped convolutions and zero-initialized batch normalization', 'create a feature denoising module using non-local operations with optional embedding and softmax', 'build a non-local attention operation with configurable embedding and dot-product or softmax modes', 'create a ResNet group that stacks multiple bottleneck blocks with configurable stride and features']
```

Usage

```
{'build_resnet_backbone': 'build a ResNet backbone model with configurable blocks and group functions for ImageNet classification', 'create_resnet_bottleneck': 'create a ResNet bottleneck block with grouped convolutions and zero-initialized batch normalization', 'create_denoising_module': 'create a feature denoising module using non-local operations with optional embedding and softmax', 'build_non_local_op': 'build a non-local attention operation with configurable embedding and dot-product or softmax modes', 'create_resnet_group': 'create a ResNet group that stacks multiple bottleneck blocks with configurable stride and features'}
```

