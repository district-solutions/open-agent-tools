# Agent Python Tools

- repo: facebookresearch/interwild
- repo_uri: https://github.com/facebookresearch/interwild

## File: facebookresearch_interwild/main/config.py

Prompts

```
['set GPU device IDs and CUDA_VISIBLE_DEVICES via Config.set_args', 'configure training hyperparameters like lr, batch size, and epochs in Config', 'configure 3D and 2D training datasets and test set in Config', 'configure ResNet types for body, hand, and transformer modules in Config', 'configure output directories for models, logs, results, and visualization in Config', 'build a python module to create an InterWild hand pose estimation model using get_model with train or test mode', 'run the Model forward pass with inputs, targets, meta_info, and mode to get hand pose predictions or losses', 'review the Model get_coord method that computes 2D projected and 3D camera-centered joint coordinates from MANO parameters', 'test the init_weights function that initializes Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights', 'refactor the Model forward method to modify the hand bounding box detection or MANO pose estimation pipeline', 'run the test module with --gpu and --test_epoch args to evaluate model predictions', 'parse command line arguments for gpu ids and test epoch using argparse', 'test the Tester class _make_batch_generator method to create a data batch generator', 'test the Tester class _make_model method to initialize the model for evaluation', 'test the Tester class _evaluate method to compute evaluation metrics on model outputs', 'run the pytorch training loop with GPU ids and continue training flag via argparse', 'parse command line arguments for GPU ids range and continue training boolean flag', 'run the Trainer class to create a batch generator and build the model for training', 'run a forward pass through the model then compute loss and perform backward pass with optimizer step', 'save the trainer model state dict along with optimizer state and epoch number to disk']
```

Usage

```
{'set_gpu_ids': 'set GPU device IDs and CUDA_VISIBLE_DEVICES via Config.set_args', 'configure_training': 'configure training hyperparameters like lr, batch size, and epochs in Config', 'configure_datasets': 'configure 3D and 2D training datasets and test set in Config', 'configure_model_architecture': 'configure ResNet types for body, hand, and transformer modules in Config', 'configure_output_dirs': 'configure output directories for models, logs, results, and visualization in Config'}
```

## File: facebookresearch_interwild/main/model.py

Prompts

```
['set GPU device IDs and CUDA_VISIBLE_DEVICES via Config.set_args', 'configure training hyperparameters like lr, batch size, and epochs in Config', 'configure 3D and 2D training datasets and test set in Config', 'configure ResNet types for body, hand, and transformer modules in Config', 'configure output directories for models, logs, results, and visualization in Config', 'build a python module to create an InterWild hand pose estimation model using get_model with train or test mode', 'run the Model forward pass with inputs, targets, meta_info, and mode to get hand pose predictions or losses', 'review the Model get_coord method that computes 2D projected and 3D camera-centered joint coordinates from MANO parameters', 'test the init_weights function that initializes Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights', 'refactor the Model forward method to modify the hand bounding box detection or MANO pose estimation pipeline', 'run the test module with --gpu and --test_epoch args to evaluate model predictions', 'parse command line arguments for gpu ids and test epoch using argparse', 'test the Tester class _make_batch_generator method to create a data batch generator', 'test the Tester class _make_model method to initialize the model for evaluation', 'test the Tester class _evaluate method to compute evaluation metrics on model outputs', 'run the pytorch training loop with GPU ids and continue training flag via argparse', 'parse command line arguments for GPU ids range and continue training boolean flag', 'run the Trainer class to create a batch generator and build the model for training', 'run a forward pass through the model then compute loss and perform backward pass with optimizer step', 'save the trainer model state dict along with optimizer state and epoch number to disk']
```

Usage

```
{'build_interwild_model': 'build a python module to create an InterWild hand pose estimation model using get_model with train or test mode', 'run_model_forward': 'run the Model forward pass with inputs, targets, meta_info, and mode to get hand pose predictions or losses', 'review_model_get_coord': 'review the Model get_coord method that computes 2D projected and 3D camera-centered joint coordinates from MANO parameters', 'test_init_weights': 'test the init_weights function that initializes Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights', 'refactor_model_forward': 'refactor the Model forward method to modify the hand bounding box detection or MANO pose estimation pipeline'}
```

## File: facebookresearch_interwild/main/test.py

Prompts

```
['set GPU device IDs and CUDA_VISIBLE_DEVICES via Config.set_args', 'configure training hyperparameters like lr, batch size, and epochs in Config', 'configure 3D and 2D training datasets and test set in Config', 'configure ResNet types for body, hand, and transformer modules in Config', 'configure output directories for models, logs, results, and visualization in Config', 'build a python module to create an InterWild hand pose estimation model using get_model with train or test mode', 'run the Model forward pass with inputs, targets, meta_info, and mode to get hand pose predictions or losses', 'review the Model get_coord method that computes 2D projected and 3D camera-centered joint coordinates from MANO parameters', 'test the init_weights function that initializes Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights', 'refactor the Model forward method to modify the hand bounding box detection or MANO pose estimation pipeline', 'run the test module with --gpu and --test_epoch args to evaluate model predictions', 'parse command line arguments for gpu ids and test epoch using argparse', 'test the Tester class _make_batch_generator method to create a data batch generator', 'test the Tester class _make_model method to initialize the model for evaluation', 'test the Tester class _evaluate method to compute evaluation metrics on model outputs', 'run the pytorch training loop with GPU ids and continue training flag via argparse', 'parse command line arguments for GPU ids range and continue training boolean flag', 'run the Trainer class to create a batch generator and build the model for training', 'run a forward pass through the model then compute loss and perform backward pass with optimizer step', 'save the trainer model state dict along with optimizer state and epoch number to disk']
```

Usage

```
{'run_test_evaluation': 'run the test module with --gpu and --test_epoch args to evaluate model predictions', 'parse_args_gpu_test_epoch': 'parse command line arguments for gpu ids and test epoch using argparse', 'test_Tester_make_batch_generator': 'test the Tester class _make_batch_generator method to create a data batch generator', 'test_Tester_make_model': 'test the Tester class _make_model method to initialize the model for evaluation', 'test_Tester_evaluate': 'test the Tester class _evaluate method to compute evaluation metrics on model outputs'}
```

## File: facebookresearch_interwild/main/train.py

Prompts

```
['set GPU device IDs and CUDA_VISIBLE_DEVICES via Config.set_args', 'configure training hyperparameters like lr, batch size, and epochs in Config', 'configure 3D and 2D training datasets and test set in Config', 'configure ResNet types for body, hand, and transformer modules in Config', 'configure output directories for models, logs, results, and visualization in Config', 'build a python module to create an InterWild hand pose estimation model using get_model with train or test mode', 'run the Model forward pass with inputs, targets, meta_info, and mode to get hand pose predictions or losses', 'review the Model get_coord method that computes 2D projected and 3D camera-centered joint coordinates from MANO parameters', 'test the init_weights function that initializes Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights', 'refactor the Model forward method to modify the hand bounding box detection or MANO pose estimation pipeline', 'run the test module with --gpu and --test_epoch args to evaluate model predictions', 'parse command line arguments for gpu ids and test epoch using argparse', 'test the Tester class _make_batch_generator method to create a data batch generator', 'test the Tester class _make_model method to initialize the model for evaluation', 'test the Tester class _evaluate method to compute evaluation metrics on model outputs', 'run the pytorch training loop with GPU ids and continue training flag via argparse', 'parse command line arguments for GPU ids range and continue training boolean flag', 'run the Trainer class to create a batch generator and build the model for training', 'run a forward pass through the model then compute loss and perform backward pass with optimizer step', 'save the trainer model state dict along with optimizer state and epoch number to disk']
```

Usage

```
{'run_training_loop': 'run the pytorch training loop with GPU ids and continue training flag via argparse', 'parse_gpu_args': 'parse command line arguments for GPU ids range and continue training boolean flag', 'run_trainer_make_model': 'run the Trainer class to create a batch generator and build the model for training', 'run_forward_backward_pass': 'run a forward pass through the model then compute loss and perform backward pass with optimizer step', 'save_trainer_model': 'save the trainer model state dict along with optimizer state and epoch number to disk'}
```

