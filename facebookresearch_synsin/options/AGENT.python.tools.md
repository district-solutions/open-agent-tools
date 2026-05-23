# Agent Python Tools

- repo: facebookresearch/synsin
- repo_uri: https://github.com/facebookresearch/synsin

## File: facebookresearch_synsin/options/options.py

Prompts

```
['create a python module that loads a ZbufferModelPts model using get_model with opt.model_type set to zbuffer_pts', 'create a python module that loads a ViewAppearanceFlow model using get_model with opt.model_type set to viewappearance', 'create a python module that loads a Tatarchenko model using get_model with opt.model_type set to tatarchenko', 'create a python module that loads the MP3D dataset using get_dataset with opt.dataset set to mp3d', 'create a python module that loads the KITTIDataLoader using get_dataset with opt.dataset set to kitti', 'create an ArgumentParser instance that sets up eval parameters for model evaluation', 'parse command line arguments for evaluation including batch size and GPU IDs', 'add evaluation parameters like test folder, ground truth folder, and dataset to the parser', 'parse a string of arguments and return args and grouped argument dictionaries', 'configure eval options including num views, render IDs, and auto regressive mode', 'build an ArgumentParser instance to configure self-supervised view synthesis training arguments', 'parse command line arguments for model, data, and training parameters using ArgumentParser', 'add model configuration arguments like model_type, accumulation, and depth predictor to the parser', 'get the log directory path for a training run using get_log_path with timestamp and opts', 'get the model checkpoint save path and create directories using get_model_path with opts']
```

Usage

```
{'get_model_zbuffer': 'create a python module that loads a ZbufferModelPts model using get_model with opt.model_type set to zbuffer_pts', 'get_model_viewappearance': 'create a python module that loads a ViewAppearanceFlow model using get_model with opt.model_type set to viewappearance', 'get_model_tatarchenko': 'create a python module that loads a Tatarchenko model using get_model with opt.model_type set to tatarchenko', 'get_dataset_mp3d': 'create a python module that loads the MP3D dataset using get_dataset with opt.dataset set to mp3d', 'get_dataset_kitti': 'create a python module that loads the KITTIDataLoader using get_dataset with opt.dataset set to kitti'}
```

## File: facebookresearch_synsin/options/test_options.py

Prompts

```
['create a python module that loads a ZbufferModelPts model using get_model with opt.model_type set to zbuffer_pts', 'create a python module that loads a ViewAppearanceFlow model using get_model with opt.model_type set to viewappearance', 'create a python module that loads a Tatarchenko model using get_model with opt.model_type set to tatarchenko', 'create a python module that loads the MP3D dataset using get_dataset with opt.dataset set to mp3d', 'create a python module that loads the KITTIDataLoader using get_dataset with opt.dataset set to kitti', 'create an ArgumentParser instance that sets up eval parameters for model evaluation', 'parse command line arguments for evaluation including batch size and GPU IDs', 'add evaluation parameters like test folder, ground truth folder, and dataset to the parser', 'parse a string of arguments and return args and grouped argument dictionaries', 'configure eval options including num views, render IDs, and auto regressive mode', 'build an ArgumentParser instance to configure self-supervised view synthesis training arguments', 'parse command line arguments for model, data, and training parameters using ArgumentParser', 'add model configuration arguments like model_type, accumulation, and depth predictor to the parser', 'get the log directory path for a training run using get_log_path with timestamp and opts', 'get the model checkpoint save path and create directories using get_model_path with opts']
```

Usage

```
{'create_argument_parser': 'create an ArgumentParser instance that sets up eval parameters for model evaluation', 'parse_eval_args': 'parse command line arguments for evaluation including batch size and GPU IDs', 'add_eval_parameters': 'add evaluation parameters like test folder, ground truth folder, and dataset to the parser', 'parse_arg_string': 'parse a string of arguments and return args and grouped argument dictionaries', 'configure_eval_options': 'configure eval options including num views, render IDs, and auto regressive mode'}
```

## File: facebookresearch_synsin/options/train_options.py

Prompts

```
['create a python module that loads a ZbufferModelPts model using get_model with opt.model_type set to zbuffer_pts', 'create a python module that loads a ViewAppearanceFlow model using get_model with opt.model_type set to viewappearance', 'create a python module that loads a Tatarchenko model using get_model with opt.model_type set to tatarchenko', 'create a python module that loads the MP3D dataset using get_dataset with opt.dataset set to mp3d', 'create a python module that loads the KITTIDataLoader using get_dataset with opt.dataset set to kitti', 'create an ArgumentParser instance that sets up eval parameters for model evaluation', 'parse command line arguments for evaluation including batch size and GPU IDs', 'add evaluation parameters like test folder, ground truth folder, and dataset to the parser', 'parse a string of arguments and return args and grouped argument dictionaries', 'configure eval options including num views, render IDs, and auto regressive mode', 'build an ArgumentParser instance to configure self-supervised view synthesis training arguments', 'parse command line arguments for model, data, and training parameters using ArgumentParser', 'add model configuration arguments like model_type, accumulation, and depth predictor to the parser', 'get the log directory path for a training run using get_log_path with timestamp and opts', 'get the model checkpoint save path and create directories using get_model_path with opts']
```

Usage

```
{'build_argument_parser': 'build an ArgumentParser instance to configure self-supervised view synthesis training arguments', 'parse_arguments': 'parse command line arguments for model, data, and training parameters using ArgumentParser', 'add_model_parameters': 'add model configuration arguments like model_type, accumulation, and depth predictor to the parser', 'get_log_path': 'get the log directory path for a training run using get_log_path with timestamp and opts', 'get_model_path': 'get the model checkpoint save path and create directories using get_model_path with opts'}
```

