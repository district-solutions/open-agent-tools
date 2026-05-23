# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/cv/mmcv/cnn/rfsearch/operator.py

Prompts

```
['build a Conv2dRFSearchOp with a Conv2d layer and global config to enable receptive field searching', 'create a BaseConvRFSearchOp wrapping a PyTorch module with a global config dictionary', 'test the Conv2dRFSearchOp forward pass by passing a tensor and receiving a weighted multi-dilation output', 'review the estimate_rates method to see how branch weights are used to compute new dilation rates', 'refactor the expand_rates method to re-expand dilation rates and reinitialize branch weights', 'initialize a PyTorch model with RFSearchHook to enable receptive field search via dilation rates', "wrap a PyTorch model's Conv2d layers with Conv2dRFSearchOp for searchable receptive field operations", "set fixed dilation rates on a model's Conv2d layers from a pre-searched receptive field structure config", 'perform a dilation searching step on the model and save the updated search config to JSON', 'estimate and expand dilation rates for all BaseConvRFSearchOp modules in the model during search', 'create a python module that saves a config dictionary to a JSON file using mmengine dump', 'build a python module that expands dilation rates into large and small branches based on a config dict', 'create a function that calculates the padding value for a convolutional layer given kernel size, stride, and dilation', 'review the expand_rates function to understand how it generates unique dilation rate tuples from a config', 'refactor the get_single_padding function to support tuple kernel sizes and dilation values']
```

Usage

```
{'build_conv2d_rf_search_op': 'build a Conv2dRFSearchOp with a Conv2d layer and global config to enable receptive field searching', 'create_base_conv_rf_search_op': 'create a BaseConvRFSearchOp wrapping a PyTorch module with a global config dictionary', 'test_forward_pass': 'test the Conv2dRFSearchOp forward pass by passing a tensor and receiving a weighted multi-dilation output', 'review_estimate_rates': 'review the estimate_rates method to see how branch weights are used to compute new dilation rates', 'refactor_expand_rates': 'refactor the expand_rates method to re-expand dilation rates and reinitialize branch weights'}
```

## File: facebookresearch_sapiens/cv/mmcv/cnn/rfsearch/search.py

Prompts

```
['build a Conv2dRFSearchOp with a Conv2d layer and global config to enable receptive field searching', 'create a BaseConvRFSearchOp wrapping a PyTorch module with a global config dictionary', 'test the Conv2dRFSearchOp forward pass by passing a tensor and receiving a weighted multi-dilation output', 'review the estimate_rates method to see how branch weights are used to compute new dilation rates', 'refactor the expand_rates method to re-expand dilation rates and reinitialize branch weights', 'initialize a PyTorch model with RFSearchHook to enable receptive field search via dilation rates', "wrap a PyTorch model's Conv2d layers with Conv2dRFSearchOp for searchable receptive field operations", "set fixed dilation rates on a model's Conv2d layers from a pre-searched receptive field structure config", 'perform a dilation searching step on the model and save the updated search config to JSON', 'estimate and expand dilation rates for all BaseConvRFSearchOp modules in the model during search', 'create a python module that saves a config dictionary to a JSON file using mmengine dump', 'build a python module that expands dilation rates into large and small branches based on a config dict', 'create a function that calculates the padding value for a convolutional layer given kernel size, stride, and dilation', 'review the expand_rates function to understand how it generates unique dilation rate tuples from a config', 'refactor the get_single_padding function to support tuple kernel sizes and dilation values']
```

Usage

```
{'init_model_rfsearch': 'initialize a PyTorch model with RFSearchHook to enable receptive field search via dilation rates', 'wrap_model_conv2d': "wrap a PyTorch model's Conv2d layers with Conv2dRFSearchOp for searchable receptive field operations", 'set_model_dilation': "set fixed dilation rates on a model's Conv2d layers from a pre-searched receptive field structure config", 'step_dilation_search': 'perform a dilation searching step on the model and save the updated search config to JSON', 'estimate_and_expand_rates': 'estimate and expand dilation rates for all BaseConvRFSearchOp modules in the model during search'}
```

## File: facebookresearch_sapiens/cv/mmcv/cnn/rfsearch/utils.py

Prompts

```
['build a Conv2dRFSearchOp with a Conv2d layer and global config to enable receptive field searching', 'create a BaseConvRFSearchOp wrapping a PyTorch module with a global config dictionary', 'test the Conv2dRFSearchOp forward pass by passing a tensor and receiving a weighted multi-dilation output', 'review the estimate_rates method to see how branch weights are used to compute new dilation rates', 'refactor the expand_rates method to re-expand dilation rates and reinitialize branch weights', 'initialize a PyTorch model with RFSearchHook to enable receptive field search via dilation rates', "wrap a PyTorch model's Conv2d layers with Conv2dRFSearchOp for searchable receptive field operations", "set fixed dilation rates on a model's Conv2d layers from a pre-searched receptive field structure config", 'perform a dilation searching step on the model and save the updated search config to JSON', 'estimate and expand dilation rates for all BaseConvRFSearchOp modules in the model during search', 'create a python module that saves a config dictionary to a JSON file using mmengine dump', 'build a python module that expands dilation rates into large and small branches based on a config dict', 'create a function that calculates the padding value for a convolutional layer given kernel size, stride, and dilation', 'review the expand_rates function to understand how it generates unique dilation rate tuples from a config', 'refactor the get_single_padding function to support tuple kernel sizes and dilation values']
```

Usage

```
{'write_config_to_json': 'create a python module that saves a config dictionary to a JSON file using mmengine dump', 'expand_dilation_rates': 'build a python module that expands dilation rates into large and small branches based on a config dict', 'calculate_conv_padding': 'create a function that calculates the padding value for a convolutional layer given kernel size, stride, and dilation', 'review_expand_rates': 'review the expand_rates function to understand how it generates unique dilation rate tuples from a config', 'refactor_get_single_padding': 'refactor the get_single_padding function to support tuple kernel sizes and dilation values'}
```

