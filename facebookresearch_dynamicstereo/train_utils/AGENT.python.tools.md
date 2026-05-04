# Agent Python Tools

- repo: facebookresearch/dynamicstereo
- repo_uri: https://github.com/facebookresearch/dynamic_stereo

## File: facebookresearch_dynamicstereo/train_utils/logger.py

Prompts

```
['create a Logger instance with a model, scheduler, and checkpoint path for training logging', 'push a dictionary of training metrics to the Logger for a specific task', 'update the Logger step counter and print training status at the configured summary frequency', 'write a dictionary of results directly to TensorBoard as scalar values at the current step', 'close the Logger TensorBoard SummaryWriter to flush and release resources', 'compute the sequence loss over a list of flow predictions against ground truth flow with validity mask', 'calculate end-point error metrics including 1px, 3px, and 5px thresholds from the final flow prediction', 'weight iterative flow predictions using an adjusted loss gamma for consistent multi-iteration training', 'filter out invalid pixels and extremely large displacements from flow ground truth using magnitude threshold', 'validate that flow prediction tensors match ground truth shapes and contain no NaN or Inf values', 'count the number of trainable parameters in a PyTorch model', 'run test evaluation on a model across multiple dataloaders and save results to JSON', 'convert a Matplotlib figure to a numpy array of RGB pixel values', 'save training images, disparity maps, and flow predictions to a TensorBoard writer', 'review the utility functions for parameter counting, evaluation, figure conversion, and TensorBoard logging']
```

Usage

```
{'create_logger_instance': 'create a Logger instance with a model, scheduler, and checkpoint path for training logging', 'push_metrics_to_logger': 'push a dictionary of training metrics to the Logger for a specific task', 'update_logger_step': 'update the Logger step counter and print training status at the configured summary frequency', 'write_dict_to_tensorboard': 'write a dictionary of results directly to TensorBoard as scalar values at the current step', 'close_logger_writer': 'close the Logger TensorBoard SummaryWriter to flush and release resources'}
```

## File: facebookresearch_dynamicstereo/train_utils/losses.py

Prompts

```
['create a Logger instance with a model, scheduler, and checkpoint path for training logging', 'push a dictionary of training metrics to the Logger for a specific task', 'update the Logger step counter and print training status at the configured summary frequency', 'write a dictionary of results directly to TensorBoard as scalar values at the current step', 'close the Logger TensorBoard SummaryWriter to flush and release resources', 'compute the sequence loss over a list of flow predictions against ground truth flow with validity mask', 'calculate end-point error metrics including 1px, 3px, and 5px thresholds from the final flow prediction', 'weight iterative flow predictions using an adjusted loss gamma for consistent multi-iteration training', 'filter out invalid pixels and extremely large displacements from flow ground truth using magnitude threshold', 'validate that flow prediction tensors match ground truth shapes and contain no NaN or Inf values', 'count the number of trainable parameters in a PyTorch model', 'run test evaluation on a model across multiple dataloaders and save results to JSON', 'convert a Matplotlib figure to a numpy array of RGB pixel values', 'save training images, disparity maps, and flow predictions to a TensorBoard writer', 'review the utility functions for parameter counting, evaluation, figure conversion, and TensorBoard logging']
```

Usage

```
{'compute_sequence_loss': 'compute the sequence loss over a list of flow predictions against ground truth flow with validity mask', 'calculate_epe_metrics': 'calculate end-point error metrics including 1px, 3px, and 5px thresholds from the final flow prediction', 'weight_iterative_predictions': 'weight iterative flow predictions using an adjusted loss gamma for consistent multi-iteration training', 'filter_invalid_flow_pixels': 'filter out invalid pixels and extremely large displacements from flow ground truth using magnitude threshold', 'validate_flow_tensor_shapes': 'validate that flow prediction tensors match ground truth shapes and contain no NaN or Inf values'}
```

## File: facebookresearch_dynamicstereo/train_utils/utils.py

Prompts

```
['create a Logger instance with a model, scheduler, and checkpoint path for training logging', 'push a dictionary of training metrics to the Logger for a specific task', 'update the Logger step counter and print training status at the configured summary frequency', 'write a dictionary of results directly to TensorBoard as scalar values at the current step', 'close the Logger TensorBoard SummaryWriter to flush and release resources', 'compute the sequence loss over a list of flow predictions against ground truth flow with validity mask', 'calculate end-point error metrics including 1px, 3px, and 5px thresholds from the final flow prediction', 'weight iterative flow predictions using an adjusted loss gamma for consistent multi-iteration training', 'filter out invalid pixels and extremely large displacements from flow ground truth using magnitude threshold', 'validate that flow prediction tensors match ground truth shapes and contain no NaN or Inf values', 'count the number of trainable parameters in a PyTorch model', 'run test evaluation on a model across multiple dataloaders and save results to JSON', 'convert a Matplotlib figure to a numpy array of RGB pixel values', 'save training images, disparity maps, and flow predictions to a TensorBoard writer', 'review the utility functions for parameter counting, evaluation, figure conversion, and TensorBoard logging']
```

Usage

```
{'count_parameters_model': 'count the number of trainable parameters in a PyTorch model', 'run_test_eval_model': 'run test evaluation on a model across multiple dataloaders and save results to JSON', 'fig2data_matplotlib': 'convert a Matplotlib figure to a numpy array of RGB pixel values', 'save_ims_to_tb_tensorboard': 'save training images, disparity maps, and flow predictions to a TensorBoard writer', 'review_utils_functions': 'review the utility functions for parameter counting, evaluation, figure conversion, and TensorBoard logging'}
```

