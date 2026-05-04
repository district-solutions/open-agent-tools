# Agent Python Tools

- repo: google-deepmind/emergentincontextlearning
- repo_uri: https://github.com/google-deepmind/emergent_in_context_learning

## File: google-deepmind_emergentincontextlearning/experiment/configs/images_all_exemplars.py

Prompts

```
['get a jaxline config object for training a transformer on omniglot data with bursty sequences', 'get a reduced transformer config with 2 layers and 2 heads by calling get_config with debug set to true', 'configure the omniglot dataset to use all exemplars across all 1623 classes via the omniglot config dict', 'configure the transformer model architecture with 12 layers and 8 attention heads using the transformer config dict', 'configure evaluation modes for fewshot and holdout tasks based on the zipf exponent setting', 'configure the omniglot dataset with image augmentation that multiplies total classes by 8', 'set evaluation modes for uniform distribution when zipf_exponent is zero', 'customize transformer hyperparameters like num_layers, num_heads, and dropout_prob via the config', 'get the default transformer experiment config for Omniglot image classification training', 'get a reduced transformer experiment config with fewer layers and heads for debugging', 'set the ZIPF_EXPONENT constant to control Zipf distribution for data generation', 'configure evaluation modes based on whether ZIPF_EXPONENT is zero or non-zero', 'configure the transformer or RNN model architecture with layers, heads, and hidden size']
```

Usage

```
{'get_config_for_training': 'get a jaxline config object for training a transformer on omniglot data with bursty sequences', 'get_config_in_debug_mode': 'get a reduced transformer config with 2 layers and 2 heads by calling get_config with debug set to true', 'configure_omniglot_exemplars': 'configure the omniglot dataset to use all exemplars across all 1623 classes via the omniglot config dict', 'configure_transformer_architecture': 'configure the transformer model architecture with 12 layers and 8 attention heads using the transformer config dict', 'configure_evaluation_modes': 'configure evaluation modes for fewshot and holdout tasks based on the zipf exponent setting'}
```

## File: google-deepmind_emergentincontextlearning/experiment/configs/images_augmented.py

Prompts

```
['get a jaxline config object for training a transformer on omniglot data with bursty sequences', 'get a reduced transformer config with 2 layers and 2 heads by calling get_config with debug set to true', 'configure the omniglot dataset to use all exemplars across all 1623 classes via the omniglot config dict', 'configure the transformer model architecture with 12 layers and 8 attention heads using the transformer config dict', 'configure evaluation modes for fewshot and holdout tasks based on the zipf exponent setting', 'configure the omniglot dataset with image augmentation that multiplies total classes by 8', 'set evaluation modes for uniform distribution when zipf_exponent is zero', 'customize transformer hyperparameters like num_layers, num_heads, and dropout_prob via the config', 'get the default transformer experiment config for Omniglot image classification training', 'get a reduced transformer experiment config with fewer layers and heads for debugging', 'set the ZIPF_EXPONENT constant to control Zipf distribution for data generation', 'configure evaluation modes based on whether ZIPF_EXPONENT is zero or non-zero', 'configure the transformer or RNN model architecture with layers, heads, and hidden size']
```

Usage

```
{'get_config_for_training': 'get a jaxline config object for training a transformer on augmented omniglot image data', 'get_config_in_debug_mode': 'get a reduced transformer config with fewer layers and heads by passing debug=True', 'configure_omniglot_augmentation': 'configure the omniglot dataset with image augmentation that multiplies total classes by 8', 'set_eval_modes_for_uniform': 'set evaluation modes for uniform distribution when zipf_exponent is zero', 'customize_transformer_hyperparameters': 'customize transformer hyperparameters like num_layers, num_heads, and dropout_prob via the config'}
```

## File: google-deepmind_emergentincontextlearning/experiment/configs/images_identical.py

Prompts

```
['get a jaxline config object for training a transformer on omniglot data with bursty sequences', 'get a reduced transformer config with 2 layers and 2 heads by calling get_config with debug set to true', 'configure the omniglot dataset to use all exemplars across all 1623 classes via the omniglot config dict', 'configure the transformer model architecture with 12 layers and 8 attention heads using the transformer config dict', 'configure evaluation modes for fewshot and holdout tasks based on the zipf exponent setting', 'configure the omniglot dataset with image augmentation that multiplies total classes by 8', 'set evaluation modes for uniform distribution when zipf_exponent is zero', 'customize transformer hyperparameters like num_layers, num_heads, and dropout_prob via the config', 'get the default transformer experiment config for Omniglot image classification training', 'get a reduced transformer experiment config with fewer layers and heads for debugging', 'set the ZIPF_EXPONENT constant to control Zipf distribution for data generation', 'configure evaluation modes based on whether ZIPF_EXPONENT is zero or non-zero', 'configure the transformer or RNN model architecture with layers, heads, and hidden size']
```

Usage

```
{'get_config_default': 'get the default transformer experiment config for Omniglot image classification training', 'get_config_debug': 'get a reduced transformer experiment config with fewer layers and heads for debugging', 'configure_zipf_exponent': 'set the ZIPF_EXPONENT constant to control Zipf distribution for data generation', 'configure_eval_modes': 'configure evaluation modes based on whether ZIPF_EXPONENT is zero or non-zero', 'configure_model_architecture': 'configure the transformer or RNN model architecture with layers, heads, and hidden size'}
```

