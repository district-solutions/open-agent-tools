# Agent Python Tools

- repo: facebookresearch/c3dponrsfm
- repo_uri: https://github.com/facebookresearch/c3dpo_nrsfm

## File: facebookresearch_c3dponrsfm/config.py

Prompts

```
["build an argparse parser from a config constructor's default arguments", 'load and apply configuration values from a YAML file into a config object', 'flatten a nested config dictionary into dot-separated key-value pairs', 'apply dot-separated key-value pairs to update a nested config dictionary', 'write a config object to a YAML file in the experiment directory', 'run the demo to predict 3D human pose from 2D keypoints and save visualizations', 'get a sample Human3.6M 2D keypoint tensor for testing the model', 'download the pretrained Human3.6M model weights and return the model directory path', 'initialize a 3D pose estimation model from a downloaded model directory', 'show and save 2D keypoint projections as an image with colored sticks', 'run eval_model to evaluate a 3D pose model on a dataset like h36m or pascal3d', 'run the evaluate script to benchmark 3D pose models across h36m, pascal3d, and up3d datasets', 'test the eval_model function by passing a dataset name and checking returned MPJPE and Stress metrics', 'refactor eval_model to support custom dataset names or configurable batch size and worker count', 'review the eval_model function to understand how it downloads models, caches predictions, and computes evaluation metrics', 'run the C3DPO model training loop with a config object that specifies dataset, solver, and model parameters', 'create an SGD, Adagrad, or Adam optimizer with a multistep learning rate scheduler for the model', 'run a full training experiment by loading an experiment config from a YAML file path', 'run evaluation on a test dataset loader using the trained model and return results as a dictionary', 'build a C3DPO model instance with configurable keypoints, projection type, and camera parameters for 3D pose estimation', 'run the C3DPO forward pass with 2D keypoints and visibility masks to predict 3D shape and camera parameters', 'create a 1x1 convolution layer with configurable input/output planes and weight initialization standard deviation', 'test the ResLayer residual block with configurable expansion factor and batch normalization for feature extraction', 'review the C3DPO canonicalization loss method that enforces rotation-invariant 3D shape predictions via random rotations']
```

Usage

```
{'get_arg_parser': "build an argparse parser from a config constructor's default arguments", 'set_config_from_file': 'load and apply configuration values from a YAML file into a config object', 'convert_to_stringval': 'flatten a nested config dictionary into dot-separated key-value pairs', 'set_config': 'apply dot-separated key-value pairs to update a nested config dictionary', 'dump_config': 'write a config object to a YAML file in the experiment directory'}
```

## File: facebookresearch_c3dponrsfm/demo.py

Prompts

```
["build an argparse parser from a config constructor's default arguments", 'load and apply configuration values from a YAML file into a config object', 'flatten a nested config dictionary into dot-separated key-value pairs', 'apply dot-separated key-value pairs to update a nested config dictionary', 'write a config object to a YAML file in the experiment directory', 'run the demo to predict 3D human pose from 2D keypoints and save visualizations', 'get a sample Human3.6M 2D keypoint tensor for testing the model', 'download the pretrained Human3.6M model weights and return the model directory path', 'initialize a 3D pose estimation model from a downloaded model directory', 'show and save 2D keypoint projections as an image with colored sticks', 'run eval_model to evaluate a 3D pose model on a dataset like h36m or pascal3d', 'run the evaluate script to benchmark 3D pose models across h36m, pascal3d, and up3d datasets', 'test the eval_model function by passing a dataset name and checking returned MPJPE and Stress metrics', 'refactor eval_model to support custom dataset names or configurable batch size and worker count', 'review the eval_model function to understand how it downloads models, caches predictions, and computes evaluation metrics', 'run the C3DPO model training loop with a config object that specifies dataset, solver, and model parameters', 'create an SGD, Adagrad, or Adam optimizer with a multistep learning rate scheduler for the model', 'run a full training experiment by loading an experiment config from a YAML file path', 'run evaluation on a test dataset loader using the trained model and return results as a dictionary', 'build a C3DPO model instance with configurable keypoints, projection type, and camera parameters for 3D pose estimation', 'run the C3DPO forward pass with 2D keypoints and visibility masks to predict 3D shape and camera parameters', 'create a 1x1 convolution layer with configurable input/output planes and weight initialization standard deviation', 'test the ResLayer residual block with configurable expansion factor and batch normalization for feature extraction', 'review the C3DPO canonicalization loss method that enforces rotation-invariant 3D shape predictions via random rotations']
```

Usage

```
{'run_demo_3d_pose': 'run the demo to predict 3D human pose from 2D keypoints and save visualizations', 'get_test_h36m_sample': 'get a sample Human3.6M 2D keypoint tensor for testing the model', 'download_model_h36m': 'download the pretrained Human3.6M model weights and return the model directory path', 'init_model_from_dir': 'initialize a 3D pose estimation model from a downloaded model directory', 'show_projections_keypoints': 'show and save 2D keypoint projections as an image with colored sticks'}
```

## File: facebookresearch_c3dponrsfm/evaluate.py

Prompts

```
["build an argparse parser from a config constructor's default arguments", 'load and apply configuration values from a YAML file into a config object', 'flatten a nested config dictionary into dot-separated key-value pairs', 'apply dot-separated key-value pairs to update a nested config dictionary', 'write a config object to a YAML file in the experiment directory', 'run the demo to predict 3D human pose from 2D keypoints and save visualizations', 'get a sample Human3.6M 2D keypoint tensor for testing the model', 'download the pretrained Human3.6M model weights and return the model directory path', 'initialize a 3D pose estimation model from a downloaded model directory', 'show and save 2D keypoint projections as an image with colored sticks', 'run eval_model to evaluate a 3D pose model on a dataset like h36m or pascal3d', 'run the evaluate script to benchmark 3D pose models across h36m, pascal3d, and up3d datasets', 'test the eval_model function by passing a dataset name and checking returned MPJPE and Stress metrics', 'refactor eval_model to support custom dataset names or configurable batch size and worker count', 'review the eval_model function to understand how it downloads models, caches predictions, and computes evaluation metrics', 'run the C3DPO model training loop with a config object that specifies dataset, solver, and model parameters', 'create an SGD, Adagrad, or Adam optimizer with a multistep learning rate scheduler for the model', 'run a full training experiment by loading an experiment config from a YAML file path', 'run evaluation on a test dataset loader using the trained model and return results as a dictionary', 'build a C3DPO model instance with configurable keypoints, projection type, and camera parameters for 3D pose estimation', 'run the C3DPO forward pass with 2D keypoints and visibility masks to predict 3D shape and camera parameters', 'create a 1x1 convolution layer with configurable input/output planes and weight initialization standard deviation', 'test the ResLayer residual block with configurable expansion factor and batch normalization for feature extraction', 'review the C3DPO canonicalization loss method that enforces rotation-invariant 3D shape predictions via random rotations']
```

Usage

```
{'run_eval_model': 'run eval_model to evaluate a 3D pose model on a dataset like h36m or pascal3d', 'run_evaluate_cli': 'run the evaluate script to benchmark 3D pose models across h36m, pascal3d, and up3d datasets', 'test_eval_model': 'test the eval_model function by passing a dataset name and checking returned MPJPE and Stress metrics', 'refactor_eval_model': 'refactor eval_model to support custom dataset names or configurable batch size and worker count', 'review_eval_model': 'review the eval_model function to understand how it downloads models, caches predictions, and computes evaluation metrics'}
```

## File: facebookresearch_c3dponrsfm/experiment.py

Prompts

```
["build an argparse parser from a config constructor's default arguments", 'load and apply configuration values from a YAML file into a config object', 'flatten a nested config dictionary into dot-separated key-value pairs', 'apply dot-separated key-value pairs to update a nested config dictionary', 'write a config object to a YAML file in the experiment directory', 'run the demo to predict 3D human pose from 2D keypoints and save visualizations', 'get a sample Human3.6M 2D keypoint tensor for testing the model', 'download the pretrained Human3.6M model weights and return the model directory path', 'initialize a 3D pose estimation model from a downloaded model directory', 'show and save 2D keypoint projections as an image with colored sticks', 'run eval_model to evaluate a 3D pose model on a dataset like h36m or pascal3d', 'run the evaluate script to benchmark 3D pose models across h36m, pascal3d, and up3d datasets', 'test the eval_model function by passing a dataset name and checking returned MPJPE and Stress metrics', 'refactor eval_model to support custom dataset names or configurable batch size and worker count', 'review the eval_model function to understand how it downloads models, caches predictions, and computes evaluation metrics', 'run the C3DPO model training loop with a config object that specifies dataset, solver, and model parameters', 'create an SGD, Adagrad, or Adam optimizer with a multistep learning rate scheduler for the model', 'run a full training experiment by loading an experiment config from a YAML file path', 'run evaluation on a test dataset loader using the trained model and return results as a dictionary', 'build a C3DPO model instance with configurable keypoints, projection type, and camera parameters for 3D pose estimation', 'run the C3DPO forward pass with 2D keypoints and visibility masks to predict 3D shape and camera parameters', 'create a 1x1 convolution layer with configurable input/output planes and weight initialization standard deviation', 'test the ResLayer residual block with configurable expansion factor and batch normalization for feature extraction', 'review the C3DPO canonicalization loss method that enforces rotation-invariant 3D shape predictions via random rotations']
```

Usage

```
{'run_training_C3DPO': 'run the C3DPO model training loop with a config object that specifies dataset, solver, and model parameters', 'init_model_from_dir': 'initialize a C3DPO model from an experiment directory by loading its config file and checkpoint', 'init_optimizer': 'create an SGD, Adagrad, or Adam optimizer with a multistep learning rate scheduler for the model', 'run_experiment_from_cfg_file': 'run a full training experiment by loading an experiment config from a YAML file path', 'run_eval': 'run evaluation on a test dataset loader using the trained model and return results as a dictionary'}
```

## File: facebookresearch_c3dponrsfm/model.py

Prompts

```
["build an argparse parser from a config constructor's default arguments", 'load and apply configuration values from a YAML file into a config object', 'flatten a nested config dictionary into dot-separated key-value pairs', 'apply dot-separated key-value pairs to update a nested config dictionary', 'write a config object to a YAML file in the experiment directory', 'run the demo to predict 3D human pose from 2D keypoints and save visualizations', 'get a sample Human3.6M 2D keypoint tensor for testing the model', 'download the pretrained Human3.6M model weights and return the model directory path', 'initialize a 3D pose estimation model from a downloaded model directory', 'show and save 2D keypoint projections as an image with colored sticks', 'run eval_model to evaluate a 3D pose model on a dataset like h36m or pascal3d', 'run the evaluate script to benchmark 3D pose models across h36m, pascal3d, and up3d datasets', 'test the eval_model function by passing a dataset name and checking returned MPJPE and Stress metrics', 'refactor eval_model to support custom dataset names or configurable batch size and worker count', 'review the eval_model function to understand how it downloads models, caches predictions, and computes evaluation metrics', 'run the C3DPO model training loop with a config object that specifies dataset, solver, and model parameters', 'create an SGD, Adagrad, or Adam optimizer with a multistep learning rate scheduler for the model', 'run a full training experiment by loading an experiment config from a YAML file path', 'run evaluation on a test dataset loader using the trained model and return results as a dictionary', 'build a C3DPO model instance with configurable keypoints, projection type, and camera parameters for 3D pose estimation', 'run the C3DPO forward pass with 2D keypoints and visibility masks to predict 3D shape and camera parameters', 'create a 1x1 convolution layer with configurable input/output planes and weight initialization standard deviation', 'test the ResLayer residual block with configurable expansion factor and batch normalization for feature extraction', 'review the C3DPO canonicalization loss method that enforces rotation-invariant 3D shape predictions via random rotations']
```

Usage

```
{'build_C3DPO_model': 'build a C3DPO model instance with configurable keypoints, projection type, and camera parameters for 3D pose estimation', 'run_C3DPO_forward': 'run the C3DPO forward pass with 2D keypoints and visibility masks to predict 3D shape and camera parameters', 'create_conv1x1_layer': 'create a 1x1 convolution layer with configurable input/output planes and weight initialization standard deviation', 'test_ResLayer': 'test the ResLayer residual block with configurable expansion factor and batch normalization for feature extraction', 'review_C3DPO_canonicalization_loss': 'review the C3DPO canonicalization loss method that enforces rotation-invariant 3D shape predictions via random rotations'}
```

