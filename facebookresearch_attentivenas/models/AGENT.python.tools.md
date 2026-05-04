# Agent Python Tools

- repo: facebookresearch/attentivenas
- repo_uri: https://github.com/facebookresearch/attentivenas

## File: facebookresearch_attentivenas/models/attentive_nas_dynamic_model.py

Prompts

```
['build a python module to create an AttentiveNasDynamicModel from a supernet config with 1000 classes', 'run set_active_subnet on the dynamic model to configure resolution width depth kernel size and expand ratio', 'sample a random active subnet configuration from the dynamic model and optionally compute its FLOPs', 'get a pruned static AttentiveNasStaticModel subnet from the dynamic model with preserved weights', 'compute the FLOPs in millions for the currently active subnet configuration of the dynamic model', 'build an AttentiveNasStaticModel with first_conv, blocks, last_conv, classifier, and resolution parameters', 'run a forward pass through the AttentiveNasStaticModel with input tensor x and bicubic interpolation', 'get the module_str property to retrieve a string representation of all model modules', 'get the config property to retrieve a dictionary with the model architecture configuration', 'initialize model weights using Kaiming normal for conv layers and normal for linear layers', 'create an AttentiveNasDynamicModel using create_model with arch set to attentive_nas_dynamic_model', 'create a static AttentiveNas model subsampled from a pretrained supernet using create_model', 'create a neural network model by calling create_model with args and an architecture string', 'review the create_model function that supports dynamic and static AttentiveNAS model creation', 'summarize the model factory module that creates AttentiveNAS dynamic or static models from args']
```

Usage

```
{'build_AttentiveNasDynamicModel': 'build a python module to create an AttentiveNasDynamicModel from a supernet config with 1000 classes', 'run_set_active_subnet': 'run set_active_subnet on the dynamic model to configure resolution width depth kernel size and expand ratio', 'sample_sample_active_subnet': 'sample a random active subnet configuration from the dynamic model and optionally compute its FLOPs', 'get_get_active_subnet': 'get a pruned static AttentiveNasStaticModel subnet from the dynamic model with preserved weights', 'compute_compute_active_subnet_flops': 'compute the FLOPs in millions for the currently active subnet configuration of the dynamic model'}
```

## File: facebookresearch_attentivenas/models/attentive_nas_static_model.py

Prompts

```
['build a python module to create an AttentiveNasDynamicModel from a supernet config with 1000 classes', 'run set_active_subnet on the dynamic model to configure resolution width depth kernel size and expand ratio', 'sample a random active subnet configuration from the dynamic model and optionally compute its FLOPs', 'get a pruned static AttentiveNasStaticModel subnet from the dynamic model with preserved weights', 'compute the FLOPs in millions for the currently active subnet configuration of the dynamic model', 'build an AttentiveNasStaticModel with first_conv, blocks, last_conv, classifier, and resolution parameters', 'run a forward pass through the AttentiveNasStaticModel with input tensor x and bicubic interpolation', 'get the module_str property to retrieve a string representation of all model modules', 'get the config property to retrieve a dictionary with the model architecture configuration', 'initialize model weights using Kaiming normal for conv layers and normal for linear layers', 'create an AttentiveNasDynamicModel using create_model with arch set to attentive_nas_dynamic_model', 'create a static AttentiveNas model subsampled from a pretrained supernet using create_model', 'create a neural network model by calling create_model with args and an architecture string', 'review the create_model function that supports dynamic and static AttentiveNAS model creation', 'summarize the model factory module that creates AttentiveNAS dynamic or static models from args']
```

Usage

```
{'build_AttentiveNasStaticModel': 'build an AttentiveNasStaticModel with first_conv, blocks, last_conv, classifier, and resolution parameters', 'run_forward_pass': 'run a forward pass through the AttentiveNasStaticModel with input tensor x and bicubic interpolation', 'get_module_str': 'get the module_str property to retrieve a string representation of all model modules', 'get_config': 'get the config property to retrieve a dictionary with the model architecture configuration', 'initialize_weights': 'initialize model weights using Kaiming normal for conv layers and normal for linear layers'}
```

## File: facebookresearch_attentivenas/models/model_factory.py

Prompts

```
['build a python module to create an AttentiveNasDynamicModel from a supernet config with 1000 classes', 'run set_active_subnet on the dynamic model to configure resolution width depth kernel size and expand ratio', 'sample a random active subnet configuration from the dynamic model and optionally compute its FLOPs', 'get a pruned static AttentiveNasStaticModel subnet from the dynamic model with preserved weights', 'compute the FLOPs in millions for the currently active subnet configuration of the dynamic model', 'build an AttentiveNasStaticModel with first_conv, blocks, last_conv, classifier, and resolution parameters', 'run a forward pass through the AttentiveNasStaticModel with input tensor x and bicubic interpolation', 'get the module_str property to retrieve a string representation of all model modules', 'get the config property to retrieve a dictionary with the model architecture configuration', 'initialize model weights using Kaiming normal for conv layers and normal for linear layers', 'create an AttentiveNasDynamicModel using create_model with arch set to attentive_nas_dynamic_model', 'create a static AttentiveNas model subsampled from a pretrained supernet using create_model', 'create a neural network model by calling create_model with args and an architecture string', 'review the create_model function that supports dynamic and static AttentiveNAS model creation', 'summarize the model factory module that creates AttentiveNAS dynamic or static models from args']
```

Usage

```
{'create_attentive_nas_dynamic_model': 'create an AttentiveNasDynamicModel using create_model with arch set to attentive_nas_dynamic_model', 'create_attentive_nas_static_model': 'create a static AttentiveNas model subsampled from a pretrained supernet using create_model', 'create_model_with_arch': 'create a neural network model by calling create_model with args and an architecture string', 'review_create_model_function': 'review the create_model function that supports dynamic and static AttentiveNAS model creation', 'summarize_model_factory': 'summarize the model factory module that creates AttentiveNAS dynamic or static models from args'}
```

