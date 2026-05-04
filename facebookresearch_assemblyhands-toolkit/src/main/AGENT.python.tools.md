# Agent Python Tools

- repo: facebookresearch/assemblyhands-toolkit
- repo_uri: https://github.com/facebookresearch/assemblyhands-toolkit

## File: facebookresearch_assemblyhands-toolkit/src/main/config.py

Prompts

```
['create a BaseConfig instance with default input image shape, heatmap shape, sigma, and resnet type settings', 'print all configuration key-value pairs from a BaseConfig instance to the console', 'create a Config instance for a dataset like InterHand2.6M or AssemblyHands-Ego with training and testing settings', 'set GPU device IDs and continue training flag on a Config instance and update CUDA_VISIBLE_DEVICES', 'review the Config class directory path setup for data, output, model, visualization, log, and result directories', 'build a Model instance with BackboneNet and PoseNet for 3D hand pose estimation', 'run render_gaussian_heatmap to generate 3D Gaussian heatmaps from joint coordinates', 'run the Model forward pass in train or test mode with inputs and targets', 'init Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights using init_weights', 'get a configured Model with BackboneNet and PoseNet for training or testing mode', 'run the test evaluation pipeline for InterHand2.6M or AssemblyHands datasets with GPU inference', 'run parse_args to configure GPU IDs, test epoch, test set, and dataset via CLI arguments', 'run the main inference loop that predicts joint coordinates, root depth, hand type, and inverse transforms', 'test parse_args GPU range parsing that converts hyphenated ranges like 0-3 into comma-separated IDs', 'test the main function to evaluate model predictions on a specified test or validation set', 'run the AssemblyHands training loop on the InterHand2.6M dataset with GPU support', 'run the training loop with evaluation enabled to collect joint coordinates and predictions', 'resume training from a specific checkpoint epoch using the resume_epoch argument', 'parse command-line arguments for GPU IDs, dataset, resume epoch, and evaluation flags', 'configure multi-GPU training by specifying a GPU range like 0-3 for parallel training']
```

Usage

```
{'create_BaseConfig': 'create a BaseConfig instance with default input image shape, heatmap shape, sigma, and resnet type settings', 'print_BaseConfig_print_config': 'print all configuration key-value pairs from a BaseConfig instance to the console', 'create_Config': 'create a Config instance for a dataset like InterHand2.6M or AssemblyHands-Ego with training and testing settings', 'run_Config_set_args': 'set GPU device IDs and continue training flag on a Config instance and update CUDA_VISIBLE_DEVICES', 'review_Config_dataset_paths': 'review the Config class directory path setup for data, output, model, visualization, log, and result directories'}
```

## File: facebookresearch_assemblyhands-toolkit/src/main/model.py

Prompts

```
['create a BaseConfig instance with default input image shape, heatmap shape, sigma, and resnet type settings', 'print all configuration key-value pairs from a BaseConfig instance to the console', 'create a Config instance for a dataset like InterHand2.6M or AssemblyHands-Ego with training and testing settings', 'set GPU device IDs and continue training flag on a Config instance and update CUDA_VISIBLE_DEVICES', 'review the Config class directory path setup for data, output, model, visualization, log, and result directories', 'build a Model instance with BackboneNet and PoseNet for 3D hand pose estimation', 'run render_gaussian_heatmap to generate 3D Gaussian heatmaps from joint coordinates', 'run the Model forward pass in train or test mode with inputs and targets', 'init Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights using init_weights', 'get a configured Model with BackboneNet and PoseNet for training or testing mode', 'run the test evaluation pipeline for InterHand2.6M or AssemblyHands datasets with GPU inference', 'run parse_args to configure GPU IDs, test epoch, test set, and dataset via CLI arguments', 'run the main inference loop that predicts joint coordinates, root depth, hand type, and inverse transforms', 'test parse_args GPU range parsing that converts hyphenated ranges like 0-3 into comma-separated IDs', 'test the main function to evaluate model predictions on a specified test or validation set', 'run the AssemblyHands training loop on the InterHand2.6M dataset with GPU support', 'run the training loop with evaluation enabled to collect joint coordinates and predictions', 'resume training from a specific checkpoint epoch using the resume_epoch argument', 'parse command-line arguments for GPU IDs, dataset, resume epoch, and evaluation flags', 'configure multi-GPU training by specifying a GPU range like 0-3 for parallel training']
```

Usage

```
{'build_model_for_hand_pose_estimation': 'build a Model instance with BackboneNet and PoseNet for 3D hand pose estimation', 'run_gaussian_heatmap_rendering': 'run render_gaussian_heatmap to generate 3D Gaussian heatmaps from joint coordinates', 'run_model_forward_pass': 'run the Model forward pass in train or test mode with inputs and targets', 'init_network_weights': 'init Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights using init_weights', 'get_model_for_training_or_testing': 'get a configured Model with BackboneNet and PoseNet for training or testing mode'}
```

## File: facebookresearch_assemblyhands-toolkit/src/main/test.py

Prompts

```
['create a BaseConfig instance with default input image shape, heatmap shape, sigma, and resnet type settings', 'print all configuration key-value pairs from a BaseConfig instance to the console', 'create a Config instance for a dataset like InterHand2.6M or AssemblyHands-Ego with training and testing settings', 'set GPU device IDs and continue training flag on a Config instance and update CUDA_VISIBLE_DEVICES', 'review the Config class directory path setup for data, output, model, visualization, log, and result directories', 'build a Model instance with BackboneNet and PoseNet for 3D hand pose estimation', 'run render_gaussian_heatmap to generate 3D Gaussian heatmaps from joint coordinates', 'run the Model forward pass in train or test mode with inputs and targets', 'init Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights using init_weights', 'get a configured Model with BackboneNet and PoseNet for training or testing mode', 'run the test evaluation pipeline for InterHand2.6M or AssemblyHands datasets with GPU inference', 'run parse_args to configure GPU IDs, test epoch, test set, and dataset via CLI arguments', 'run the main inference loop that predicts joint coordinates, root depth, hand type, and inverse transforms', 'test parse_args GPU range parsing that converts hyphenated ranges like 0-3 into comma-separated IDs', 'test the main function to evaluate model predictions on a specified test or validation set', 'run the AssemblyHands training loop on the InterHand2.6M dataset with GPU support', 'run the training loop with evaluation enabled to collect joint coordinates and predictions', 'resume training from a specific checkpoint epoch using the resume_epoch argument', 'parse command-line arguments for GPU IDs, dataset, resume epoch, and evaluation flags', 'configure multi-GPU training by specifying a GPU range like 0-3 for parallel training']
```

Usage

```
{'run_test_evaluation': 'run the test evaluation pipeline for InterHand2.6M or AssemblyHands datasets with GPU inference', 'run_parse_args': 'run parse_args to configure GPU IDs, test epoch, test set, and dataset via CLI arguments', 'run_main_pipeline': 'run the main inference loop that predicts joint coordinates, root depth, hand type, and inverse transforms', 'test_parse_args_gpu_range': 'test parse_args GPU range parsing that converts hyphenated ranges like 0-3 into comma-separated IDs', 'test_main_evaluation': 'test the main function to evaluate model predictions on a specified test or validation set'}
```

## File: facebookresearch_assemblyhands-toolkit/src/main/train.py

Prompts

```
['create a BaseConfig instance with default input image shape, heatmap shape, sigma, and resnet type settings', 'print all configuration key-value pairs from a BaseConfig instance to the console', 'create a Config instance for a dataset like InterHand2.6M or AssemblyHands-Ego with training and testing settings', 'set GPU device IDs and continue training flag on a Config instance and update CUDA_VISIBLE_DEVICES', 'review the Config class directory path setup for data, output, model, visualization, log, and result directories', 'build a Model instance with BackboneNet and PoseNet for 3D hand pose estimation', 'run render_gaussian_heatmap to generate 3D Gaussian heatmaps from joint coordinates', 'run the Model forward pass in train or test mode with inputs and targets', 'init Conv2d, ConvTranspose2d, BatchNorm2d, and Linear layer weights using init_weights', 'get a configured Model with BackboneNet and PoseNet for training or testing mode', 'run the test evaluation pipeline for InterHand2.6M or AssemblyHands datasets with GPU inference', 'run parse_args to configure GPU IDs, test epoch, test set, and dataset via CLI arguments', 'run the main inference loop that predicts joint coordinates, root depth, hand type, and inverse transforms', 'test parse_args GPU range parsing that converts hyphenated ranges like 0-3 into comma-separated IDs', 'test the main function to evaluate model predictions on a specified test or validation set', 'run the AssemblyHands training loop on the InterHand2.6M dataset with GPU support', 'run the training loop with evaluation enabled to collect joint coordinates and predictions', 'resume training from a specific checkpoint epoch using the resume_epoch argument', 'parse command-line arguments for GPU IDs, dataset, resume epoch, and evaluation flags', 'configure multi-GPU training by specifying a GPU range like 0-3 for parallel training']
```

Usage

```
{'run_training_interhand26m': 'run the AssemblyHands training loop on the InterHand2.6M dataset with GPU support', 'run_training_with_evaluation': 'run the training loop with evaluation enabled to collect joint coordinates and predictions', 'resume_training_from_epoch': 'resume training from a specific checkpoint epoch using the resume_epoch argument', 'parse_training_args': 'parse command-line arguments for GPU IDs, dataset, resume epoch, and evaluation flags', 'configure_multi_gpu_training': 'configure multi-GPU training by specifying a GPU range like 0-3 for parallel training'}
```

