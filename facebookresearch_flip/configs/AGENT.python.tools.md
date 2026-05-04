# Agent Python Tools

- repo: facebookresearch/flip
- repo_uri: https://github.com/facebookresearch/flip

## File: facebookresearch_flip/configs/cfg_flip_base.py

Prompts

```
['get the default FLIP base model config for ViT-B on LAION-400M with 10000 ImageNet epochs', 'customize the FLIP base config to change the image model mask ratio from the default 0.5', 'modify the FLIP base config to adjust the image model hidden size from 768', 'adjust the FLIP base config to change the text transformer hidden size from 512 or num_heads from 8', 'override the FLIP base config to set a different number of training epochs from 10000', 'get the FLIP ViT-H/14 model configuration with 10000 epochs and 1280 hidden size for image encoder', 'customize the FLIP huge 14 config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 config', 'get the FLIP ViT-H/14 model configuration for LAION-2B with 20000 epochs and 2e-6 learning rate', 'customize the FLIP huge 14 LAION-2B config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'get the default config for ViT-L on LAION-400M with 10000 ImageNet epochs and 0.5 mask ratio', 'review the get_config function that sets num_epochs, mask_ratio, and partition_states for ViT-L training', 'summarize the get_config function which returns a config object with 10000 epochs and memory partitioning enabled', 'refactor the get_config function to support a different mask ratio or epoch count for ViT-L', 'test the get_config function to verify it returns a config with num_epochs set to 10000.0', 'get the default config for ViT-L on LAION-2B with 20000 ImageNet epochs', 'get the default image encoder configuration with a 24-layer ViT transformer', 'get the default text encoder configuration with a 12-layer BERT-style transformer', 'customize the adamw optimizer settings like learning rate, weight decay, and beta values', 'customize image and text augmentation settings including crop, flip, and tokenizer options']
```

Usage

```
{'get_config_FLIP_base': 'get the default FLIP base model config for ViT-B on LAION-400M with 10000 ImageNet epochs', 'customize_config_mask_ratio': 'customize the FLIP base config to change the image model mask ratio from the default 0.5', 'modify_config_hidden_size': 'modify the FLIP base config to adjust the image model hidden size from 768', 'adjust_config_text_transformer': 'adjust the FLIP base config to change the text transformer hidden size from 512 or num_heads from 8', 'override_config_num_epochs': 'override the FLIP base config to set a different number of training epochs from 10000'}
```

## File: facebookresearch_flip/configs/cfg_flip_huge14.py

Prompts

```
['get the default FLIP base model config for ViT-B on LAION-400M with 10000 ImageNet epochs', 'customize the FLIP base config to change the image model mask ratio from the default 0.5', 'modify the FLIP base config to adjust the image model hidden size from 768', 'adjust the FLIP base config to change the text transformer hidden size from 512 or num_heads from 8', 'override the FLIP base config to set a different number of training epochs from 10000', 'get the FLIP ViT-H/14 model configuration with 10000 epochs and 1280 hidden size for image encoder', 'customize the FLIP huge 14 config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 config', 'get the FLIP ViT-H/14 model configuration for LAION-2B with 20000 epochs and 2e-6 learning rate', 'customize the FLIP huge 14 LAION-2B config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'get the default config for ViT-L on LAION-400M with 10000 ImageNet epochs and 0.5 mask ratio', 'review the get_config function that sets num_epochs, mask_ratio, and partition_states for ViT-L training', 'summarize the get_config function which returns a config object with 10000 epochs and memory partitioning enabled', 'refactor the get_config function to support a different mask ratio or epoch count for ViT-L', 'test the get_config function to verify it returns a config with num_epochs set to 10000.0', 'get the default config for ViT-L on LAION-2B with 20000 ImageNet epochs', 'get the default image encoder configuration with a 24-layer ViT transformer', 'get the default text encoder configuration with a 12-layer BERT-style transformer', 'customize the adamw optimizer settings like learning rate, weight decay, and beta values', 'customize image and text augmentation settings including crop, flip, and tokenizer options']
```

Usage

```
{'get_config_FLIP_H14': 'get the FLIP ViT-H/14 model configuration with 10000 epochs and 1280 hidden size for image encoder', 'customize_FLIP_H14_config': 'customize the FLIP huge 14 config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect_image_encoder_config': 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect_text_encoder_config': 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure_memory_optimization': 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 config'}
```

## File: facebookresearch_flip/configs/cfg_flip_huge14_L2B_2x.py

Prompts

```
['get the default FLIP base model config for ViT-B on LAION-400M with 10000 ImageNet epochs', 'customize the FLIP base config to change the image model mask ratio from the default 0.5', 'modify the FLIP base config to adjust the image model hidden size from 768', 'adjust the FLIP base config to change the text transformer hidden size from 512 or num_heads from 8', 'override the FLIP base config to set a different number of training epochs from 10000', 'get the FLIP ViT-H/14 model configuration with 10000 epochs and 1280 hidden size for image encoder', 'customize the FLIP huge 14 config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 config', 'get the FLIP ViT-H/14 model configuration for LAION-2B with 20000 epochs and 2e-6 learning rate', 'customize the FLIP huge 14 LAION-2B config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'get the default config for ViT-L on LAION-400M with 10000 ImageNet epochs and 0.5 mask ratio', 'review the get_config function that sets num_epochs, mask_ratio, and partition_states for ViT-L training', 'summarize the get_config function which returns a config object with 10000 epochs and memory partitioning enabled', 'refactor the get_config function to support a different mask ratio or epoch count for ViT-L', 'test the get_config function to verify it returns a config with num_epochs set to 10000.0', 'get the default config for ViT-L on LAION-2B with 20000 ImageNet epochs', 'get the default image encoder configuration with a 24-layer ViT transformer', 'get the default text encoder configuration with a 12-layer BERT-style transformer', 'customize the adamw optimizer settings like learning rate, weight decay, and beta values', 'customize image and text augmentation settings including crop, flip, and tokenizer options']
```

Usage

```
{'get_config_FLIP_H14_L2B_2x': 'get the FLIP ViT-H/14 model configuration for LAION-2B with 20000 epochs and 2e-6 learning rate', 'customize_FLIP_H14_L2B_2x_config': 'customize the FLIP huge 14 LAION-2B config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect_image_encoder_config': 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect_text_encoder_config': 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure_memory_optimization': 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 LAION-2B config'}
```

## File: facebookresearch_flip/configs/cfg_flip_large.py

Prompts

```
['get the default FLIP base model config for ViT-B on LAION-400M with 10000 ImageNet epochs', 'customize the FLIP base config to change the image model mask ratio from the default 0.5', 'modify the FLIP base config to adjust the image model hidden size from 768', 'adjust the FLIP base config to change the text transformer hidden size from 512 or num_heads from 8', 'override the FLIP base config to set a different number of training epochs from 10000', 'get the FLIP ViT-H/14 model configuration with 10000 epochs and 1280 hidden size for image encoder', 'customize the FLIP huge 14 config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 config', 'get the FLIP ViT-H/14 model configuration for LAION-2B with 20000 epochs and 2e-6 learning rate', 'customize the FLIP huge 14 LAION-2B config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'get the default config for ViT-L on LAION-400M with 10000 ImageNet epochs and 0.5 mask ratio', 'review the get_config function that sets num_epochs, mask_ratio, and partition_states for ViT-L training', 'summarize the get_config function which returns a config object with 10000 epochs and memory partitioning enabled', 'refactor the get_config function to support a different mask ratio or epoch count for ViT-L', 'test the get_config function to verify it returns a config with num_epochs set to 10000.0', 'get the default config for ViT-L on LAION-2B with 20000 ImageNet epochs', 'get the default image encoder configuration with a 24-layer ViT transformer', 'get the default text encoder configuration with a 12-layer BERT-style transformer', 'customize the adamw optimizer settings like learning rate, weight decay, and beta values', 'customize image and text augmentation settings including crop, flip, and tokenizer options']
```

Usage

```
{'get_config': 'get the default config for ViT-L on LAION-400M with 10000 ImageNet epochs and 0.5 mask ratio', 'review_get_config': 'review the get_config function that sets num_epochs, mask_ratio, and partition_states for ViT-L training', 'summarize_get_config': 'summarize the get_config function which returns a config object with 10000 epochs and memory partitioning enabled', 'refactor_get_config': 'refactor the get_config function to support a different mask ratio or epoch count for ViT-L', 'test_get_config': 'test the get_config function to verify it returns a config with num_epochs set to 10000.0'}
```

## File: facebookresearch_flip/configs/cfg_flip_large_L2B_2x.py

Prompts

```
['get the default FLIP base model config for ViT-B on LAION-400M with 10000 ImageNet epochs', 'customize the FLIP base config to change the image model mask ratio from the default 0.5', 'modify the FLIP base config to adjust the image model hidden size from 768', 'adjust the FLIP base config to change the text transformer hidden size from 512 or num_heads from 8', 'override the FLIP base config to set a different number of training epochs from 10000', 'get the FLIP ViT-H/14 model configuration with 10000 epochs and 1280 hidden size for image encoder', 'customize the FLIP huge 14 config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 config', 'get the FLIP ViT-H/14 model configuration for LAION-2B with 20000 epochs and 2e-6 learning rate', 'customize the FLIP huge 14 LAION-2B config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'get the default config for ViT-L on LAION-400M with 10000 ImageNet epochs and 0.5 mask ratio', 'review the get_config function that sets num_epochs, mask_ratio, and partition_states for ViT-L training', 'summarize the get_config function which returns a config object with 10000 epochs and memory partitioning enabled', 'refactor the get_config function to support a different mask ratio or epoch count for ViT-L', 'test the get_config function to verify it returns a config with num_epochs set to 10000.0', 'get the default config for ViT-L on LAION-2B with 20000 ImageNet epochs', 'get the default image encoder configuration with a 24-layer ViT transformer', 'get the default text encoder configuration with a 12-layer BERT-style transformer', 'customize the adamw optimizer settings like learning rate, weight decay, and beta values', 'customize image and text augmentation settings including crop, flip, and tokenizer options']
```

Usage

```
{'get_config_ViT_L_LAION2B': 'get the default config for ViT-L on LAION-2B with 20000 ImageNet epochs', 'review_get_config': 'review the get_config function that sets mask ratio, learning rate, and partitioning for ViT-L training', 'summarize_get_config': 'summarize the get_config function which returns a config object with 20000 epochs and 2e-6 learning rate', 'refactor_get_config': 'refactor the get_config function to support a different number of epochs or learning rate', 'test_get_config': 'test the get_config function to verify it returns a config with correct mask ratio and partitioning settings'}
```

## File: facebookresearch_flip/configs/default.py

Prompts

```
['get the default FLIP base model config for ViT-B on LAION-400M with 10000 ImageNet epochs', 'customize the FLIP base config to change the image model mask ratio from the default 0.5', 'modify the FLIP base config to adjust the image model hidden size from 768', 'adjust the FLIP base config to change the text transformer hidden size from 512 or num_heads from 8', 'override the FLIP base config to set a different number of training epochs from 10000', 'get the FLIP ViT-H/14 model configuration with 10000 epochs and 1280 hidden size for image encoder', 'customize the FLIP huge 14 config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'inspect the image encoder transformer config with 32 layers, 16 heads, and 1280 hidden size from get_config', 'inspect the text encoder transformer config with 24 layers, 16 heads, and 1024 hidden size from get_config', 'configure memory optimization by enabling partition_states and flatten_params in the FLIP huge 14 config', 'get the FLIP ViT-H/14 model configuration for LAION-2B with 20000 epochs and 2e-6 learning rate', 'customize the FLIP huge 14 LAION-2B config by modifying num_epochs, mask_ratio, or warmup_epochs after calling get_config', 'get the default config for ViT-L on LAION-400M with 10000 ImageNet epochs and 0.5 mask ratio', 'review the get_config function that sets num_epochs, mask_ratio, and partition_states for ViT-L training', 'summarize the get_config function which returns a config object with 10000 epochs and memory partitioning enabled', 'refactor the get_config function to support a different mask ratio or epoch count for ViT-L', 'test the get_config function to verify it returns a config with num_epochs set to 10000.0', 'get the default config for ViT-L on LAION-2B with 20000 ImageNet epochs', 'get the default image encoder configuration with a 24-layer ViT transformer', 'get the default text encoder configuration with a 12-layer BERT-style transformer', 'customize the adamw optimizer settings like learning rate, weight decay, and beta values', 'customize image and text augmentation settings including crop, flip, and tokenizer options']
```

Usage

```
{'get_config': 'get the default hyperparameter configuration for training a FLIP model on TPUs', 'get_config_img': 'get the default image encoder configuration with a 24-layer ViT transformer', 'get_config_txt': 'get the default text encoder configuration with a 12-layer BERT-style transformer', 'customize_optimizer': 'customize the adamw optimizer settings like learning rate, weight decay, and beta values', 'customize_augmentation': 'customize image and text augmentation settings including crop, flip, and tokenizer options'}
```

