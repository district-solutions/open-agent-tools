# Agent Python Tools

- repo: facebookresearch/interhand2.6m
- repo_uri: https://github.com/facebookresearch/interhand2.6m

## File: facebookresearch_interhand2.6m/main/config.py

Prompts

```
['set GPU IDs and continue training flag on the Config instance via set_args', 'configure the InterHand2.6M dataset settings including input shape, heatmap shape, and sigma', 'set learning rate, decay epochs, decay factor, and batch size for training', 'configure output directories for model dumps, visualization, logs, and results', 'set test batch size and transformation mode for evaluation', 'create a Model instance with BackboneNet and PoseNet initialized for training mode with a given joint number', 'create a Model instance with BackboneNet and PoseNet for inference mode with a given joint number', 'run the Model forward pass in train mode to compute joint heatmap, depth, and hand type losses', 'run the Model forward pass in test mode to extract predicted joint coordinates from the heatmap output', 'render a 3D Gaussian heatmap from joint coordinates using configurable sigma and output shape parameters', 'run the InterHand2.6M test module with --gpu, --test_epoch, and --test_set arguments to evaluate a trained model', 'run parse_args to parse GPU IDs supporting range syntax like 0-3 for multi-GPU testing', 'run the Tester evaluation pipeline that collects joint coordinates, root depth, hand type, and inverse transforms across batches', 'test the InterHand2.6M model predictions by running inference on test or validation sets with a specific epoch checkpoint', 'run batch inference through the Tester model collecting joint_coord, rel_root_depth, hand_type, and inv_trans outputs', 'run the InterHand2.6M training loop with GPU ids via --gpu argument', 'run the training loop resuming from a checkpoint using the --continue flag', 'parse command line arguments for GPU ids and continue training options', 'review the main training loop that performs forward pass, backward pass, and model saving per epoch', 'review the parse_args function that handles GPU id range expansion and validation']
```

Usage

```
{'set_gpu_and_resume_training': 'set GPU IDs and continue training flag on the Config instance via set_args', 'configure_interhand_dataset': 'configure the InterHand2.6M dataset settings including input shape, heatmap shape, and sigma', 'set_training_hyperparameters': 'set learning rate, decay epochs, decay factor, and batch size for training', 'configure_output_directories': 'configure output directories for model dumps, visualization, logs, and results', 'set_testing_parameters': 'set test batch size and transformation mode for evaluation'}
```

## File: facebookresearch_interhand2.6m/main/model.py

Prompts

```
['set GPU IDs and continue training flag on the Config instance via set_args', 'configure the InterHand2.6M dataset settings including input shape, heatmap shape, and sigma', 'set learning rate, decay epochs, decay factor, and batch size for training', 'configure output directories for model dumps, visualization, logs, and results', 'set test batch size and transformation mode for evaluation', 'create a Model instance with BackboneNet and PoseNet initialized for training mode with a given joint number', 'create a Model instance with BackboneNet and PoseNet for inference mode with a given joint number', 'run the Model forward pass in train mode to compute joint heatmap, depth, and hand type losses', 'run the Model forward pass in test mode to extract predicted joint coordinates from the heatmap output', 'render a 3D Gaussian heatmap from joint coordinates using configurable sigma and output shape parameters', 'run the InterHand2.6M test module with --gpu, --test_epoch, and --test_set arguments to evaluate a trained model', 'run parse_args to parse GPU IDs supporting range syntax like 0-3 for multi-GPU testing', 'run the Tester evaluation pipeline that collects joint coordinates, root depth, hand type, and inverse transforms across batches', 'test the InterHand2.6M model predictions by running inference on test or validation sets with a specific epoch checkpoint', 'run batch inference through the Tester model collecting joint_coord, rel_root_depth, hand_type, and inv_trans outputs', 'run the InterHand2.6M training loop with GPU ids via --gpu argument', 'run the training loop resuming from a checkpoint using the --continue flag', 'parse command line arguments for GPU ids and continue training options', 'review the main training loop that performs forward pass, backward pass, and model saving per epoch', 'review the parse_args function that handles GPU id range expansion and validation']
```

Usage

```
{'get_model_train': 'create a Model instance with BackboneNet and PoseNet initialized for training mode with a given joint number', 'get_model_test': 'create a Model instance with BackboneNet and PoseNet for inference mode with a given joint number', 'forward_train': 'run the Model forward pass in train mode to compute joint heatmap, depth, and hand type losses', 'forward_test': 'run the Model forward pass in test mode to extract predicted joint coordinates from the heatmap output', 'render_gaussian_heatmap': 'render a 3D Gaussian heatmap from joint coordinates using configurable sigma and output shape parameters'}
```

## File: facebookresearch_interhand2.6m/main/test.py

Prompts

```
['set GPU IDs and continue training flag on the Config instance via set_args', 'configure the InterHand2.6M dataset settings including input shape, heatmap shape, and sigma', 'set learning rate, decay epochs, decay factor, and batch size for training', 'configure output directories for model dumps, visualization, logs, and results', 'set test batch size and transformation mode for evaluation', 'create a Model instance with BackboneNet and PoseNet initialized for training mode with a given joint number', 'create a Model instance with BackboneNet and PoseNet for inference mode with a given joint number', 'run the Model forward pass in train mode to compute joint heatmap, depth, and hand type losses', 'run the Model forward pass in test mode to extract predicted joint coordinates from the heatmap output', 'render a 3D Gaussian heatmap from joint coordinates using configurable sigma and output shape parameters', 'run the InterHand2.6M test module with --gpu, --test_epoch, and --test_set arguments to evaluate a trained model', 'run parse_args to parse GPU IDs supporting range syntax like 0-3 for multi-GPU testing', 'run the Tester evaluation pipeline that collects joint coordinates, root depth, hand type, and inverse transforms across batches', 'test the InterHand2.6M model predictions by running inference on test or validation sets with a specific epoch checkpoint', 'run batch inference through the Tester model collecting joint_coord, rel_root_depth, hand_type, and inv_trans outputs', 'run the InterHand2.6M training loop with GPU ids via --gpu argument', 'run the training loop resuming from a checkpoint using the --continue flag', 'parse command line arguments for GPU ids and continue training options', 'review the main training loop that performs forward pass, backward pass, and model saving per epoch', 'review the parse_args function that handles GPU id range expansion and validation']
```

Usage

```
{'run_test_interhand_model': 'run the InterHand2.6M test module with --gpu, --test_epoch, and --test_set arguments to evaluate a trained model', 'run_parse_args_gpu_range': 'run parse_args to parse GPU IDs supporting range syntax like 0-3 for multi-GPU testing', 'run_tester_evaluation_pipeline': 'run the Tester evaluation pipeline that collects joint coordinates, root depth, hand type, and inverse transforms across batches', 'test_interhand_model_predictions': 'test the InterHand2.6M model predictions by running inference on test or validation sets with a specific epoch checkpoint', 'run_tester_batch_inference': 'run batch inference through the Tester model collecting joint_coord, rel_root_depth, hand_type, and inv_trans outputs'}
```

## File: facebookresearch_interhand2.6m/main/train.py

Prompts

```
['set GPU IDs and continue training flag on the Config instance via set_args', 'configure the InterHand2.6M dataset settings including input shape, heatmap shape, and sigma', 'set learning rate, decay epochs, decay factor, and batch size for training', 'configure output directories for model dumps, visualization, logs, and results', 'set test batch size and transformation mode for evaluation', 'create a Model instance with BackboneNet and PoseNet initialized for training mode with a given joint number', 'create a Model instance with BackboneNet and PoseNet for inference mode with a given joint number', 'run the Model forward pass in train mode to compute joint heatmap, depth, and hand type losses', 'run the Model forward pass in test mode to extract predicted joint coordinates from the heatmap output', 'render a 3D Gaussian heatmap from joint coordinates using configurable sigma and output shape parameters', 'run the InterHand2.6M test module with --gpu, --test_epoch, and --test_set arguments to evaluate a trained model', 'run parse_args to parse GPU IDs supporting range syntax like 0-3 for multi-GPU testing', 'run the Tester evaluation pipeline that collects joint coordinates, root depth, hand type, and inverse transforms across batches', 'test the InterHand2.6M model predictions by running inference on test or validation sets with a specific epoch checkpoint', 'run batch inference through the Tester model collecting joint_coord, rel_root_depth, hand_type, and inv_trans outputs', 'run the InterHand2.6M training loop with GPU ids via --gpu argument', 'run the training loop resuming from a checkpoint using the --continue flag', 'parse command line arguments for GPU ids and continue training options', 'review the main training loop that performs forward pass, backward pass, and model saving per epoch', 'review the parse_args function that handles GPU id range expansion and validation']
```

Usage

```
{'run_training': 'run the InterHand2.6M training loop with GPU ids via --gpu argument', 'run_continue_training': 'run the training loop resuming from a checkpoint using the --continue flag', 'parse_gpu_args': 'parse command line arguments for GPU ids and continue training options', 'review_main_training_loop': 'review the main training loop that performs forward pass, backward pass, and model saving per epoch', 'review_parse_args': 'review the parse_args function that handles GPU id range expansion and validation'}
```

