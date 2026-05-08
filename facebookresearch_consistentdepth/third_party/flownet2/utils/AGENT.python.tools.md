# Agent Python Tools

- repo: facebookresearch/consistentdepth
- repo_uri: https://github.com/facebookresearch/consistent_depth

## File: facebookresearch_consistentdepth/third_party/flownet2/utils/flow_utils.py

Prompts

```
['read a Middlebury .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury .flo format file', 'read a .flo file and extract u and v flow channels separately', 'write a combined (H, W, 2) numpy array as optical flow to a .flo file', 'write separate u and v channel arrays as optical flow to a .flo file', 'read a PNG, JPEG, PPM, or JPG image file and return the RGB numpy array', 'read a .bin or .raw numpy file and return the loaded numpy array', 'read a .flo optical flow file and return the flow data as a float32 numpy array', 'load image, numpy binary, or optical flow files by extension using a single function', 'read an image file and automatically strip the alpha channel if present', 'load FlowNetC model weights and biases into PyTorch Conv2d and ConvTranspose2d modules from numpy arrays', 'load FlowNetS model weights and biases into PyTorch modules with configurable parameter prefix for multi-network models', 'load FlowNetS-only model weights and biases into PyTorch modules with optional parameter prefix support', 'load FlowNetSD model weights and biases into PyTorch modules including interconv layers and netsd prefix', 'load FlowNet Fusion model weights and biases into PyTorch modules for fusing multiple flow predictions', 'use TimerBlock as a context manager to time and log code block execution duration', 'use add_arguments_for_module to auto-generate argparse arguments from a class constructor signature', 'use kwargs_from_args to extract prefixed argument values from parsed argparse namespace into a dict', 'use save_checkpoint to save a PyTorch model state dict and optionally copy the best model', 'use format_dictionary_of_losses to format a list of loss labels and values into a readable string']
```

Usage

```
{'read_flow_file': 'read a Middlebury .flo optical flow file and return a numpy array', 'write_flow_file': 'write optical flow data to a Middlebury .flo format file', 'read_flow_separate_channels': 'read a .flo file and extract u and v flow channels separately', 'write_flow_combined_array': 'write a combined (H, W, 2) numpy array as optical flow to a .flo file', 'write_flow_separate_channels': 'write separate u and v channel arrays as optical flow to a .flo file'}
```

## File: facebookresearch_consistentdepth/third_party/flownet2/utils/frame_utils.py

Prompts

```
['read a Middlebury .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury .flo format file', 'read a .flo file and extract u and v flow channels separately', 'write a combined (H, W, 2) numpy array as optical flow to a .flo file', 'write separate u and v channel arrays as optical flow to a .flo file', 'read a PNG, JPEG, PPM, or JPG image file and return the RGB numpy array', 'read a .bin or .raw numpy file and return the loaded numpy array', 'read a .flo optical flow file and return the flow data as a float32 numpy array', 'load image, numpy binary, or optical flow files by extension using a single function', 'read an image file and automatically strip the alpha channel if present', 'load FlowNetC model weights and biases into PyTorch Conv2d and ConvTranspose2d modules from numpy arrays', 'load FlowNetS model weights and biases into PyTorch modules with configurable parameter prefix for multi-network models', 'load FlowNetS-only model weights and biases into PyTorch modules with optional parameter prefix support', 'load FlowNetSD model weights and biases into PyTorch modules including interconv layers and netsd prefix', 'load FlowNet Fusion model weights and biases into PyTorch modules for fusing multiple flow predictions', 'use TimerBlock as a context manager to time and log code block execution duration', 'use add_arguments_for_module to auto-generate argparse arguments from a class constructor signature', 'use kwargs_from_args to extract prefixed argument values from parsed argparse namespace into a dict', 'use save_checkpoint to save a PyTorch model state dict and optionally copy the best model', 'use format_dictionary_of_losses to format a list of loss labels and values into a readable string']
```

Usage

```
{'read_image_with_read_gen': 'read a PNG, JPEG, PPM, or JPG image file and return the RGB numpy array', 'read_numpy_binary_with_read_gen': 'read a .bin or .raw numpy file and return the loaded numpy array', 'read_flow_with_read_gen': 'read a .flo optical flow file and return the flow data as a float32 numpy array', 'load_multiformat_data_with_read_gen': 'load image, numpy binary, or optical flow files by extension using a single function', 'strip_alpha_from_image_with_read_gen': 'read an image file and automatically strip the alpha channel if present'}
```

## File: facebookresearch_consistentdepth/third_party/flownet2/utils/param_utils.py

Prompts

```
['read a Middlebury .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury .flo format file', 'read a .flo file and extract u and v flow channels separately', 'write a combined (H, W, 2) numpy array as optical flow to a .flo file', 'write separate u and v channel arrays as optical flow to a .flo file', 'read a PNG, JPEG, PPM, or JPG image file and return the RGB numpy array', 'read a .bin or .raw numpy file and return the loaded numpy array', 'read a .flo optical flow file and return the flow data as a float32 numpy array', 'load image, numpy binary, or optical flow files by extension using a single function', 'read an image file and automatically strip the alpha channel if present', 'load FlowNetC model weights and biases into PyTorch Conv2d and ConvTranspose2d modules from numpy arrays', 'load FlowNetS model weights and biases into PyTorch modules with configurable parameter prefix for multi-network models', 'load FlowNetS-only model weights and biases into PyTorch modules with optional parameter prefix support', 'load FlowNetSD model weights and biases into PyTorch modules including interconv layers and netsd prefix', 'load FlowNet Fusion model weights and biases into PyTorch modules for fusing multiple flow predictions', 'use TimerBlock as a context manager to time and log code block execution duration', 'use add_arguments_for_module to auto-generate argparse arguments from a class constructor signature', 'use kwargs_from_args to extract prefixed argument values from parsed argparse namespace into a dict', 'use save_checkpoint to save a PyTorch model state dict and optionally copy the best model', 'use format_dictionary_of_losses to format a list of loss labels and values into a readable string']
```

Usage

```
{'parse_flownetc_weights': 'load FlowNetC model weights and biases into PyTorch Conv2d and ConvTranspose2d modules from numpy arrays', 'parse_flownets_weights': 'load FlowNetS model weights and biases into PyTorch modules with configurable parameter prefix for multi-network models', 'parse_flownetsonly_weights': 'load FlowNetS-only model weights and biases into PyTorch modules with optional parameter prefix support', 'parse_flownetsd_weights': 'load FlowNetSD model weights and biases into PyTorch modules including interconv layers and netsd prefix', 'parse_flownetfusion_weights': 'load FlowNet Fusion model weights and biases into PyTorch modules for fusing multiple flow predictions'}
```

## File: facebookresearch_consistentdepth/third_party/flownet2/utils/tools.py

Prompts

```
['read a Middlebury .flo optical flow file and return a numpy array', 'write optical flow data to a Middlebury .flo format file', 'read a .flo file and extract u and v flow channels separately', 'write a combined (H, W, 2) numpy array as optical flow to a .flo file', 'write separate u and v channel arrays as optical flow to a .flo file', 'read a PNG, JPEG, PPM, or JPG image file and return the RGB numpy array', 'read a .bin or .raw numpy file and return the loaded numpy array', 'read a .flo optical flow file and return the flow data as a float32 numpy array', 'load image, numpy binary, or optical flow files by extension using a single function', 'read an image file and automatically strip the alpha channel if present', 'load FlowNetC model weights and biases into PyTorch Conv2d and ConvTranspose2d modules from numpy arrays', 'load FlowNetS model weights and biases into PyTorch modules with configurable parameter prefix for multi-network models', 'load FlowNetS-only model weights and biases into PyTorch modules with optional parameter prefix support', 'load FlowNetSD model weights and biases into PyTorch modules including interconv layers and netsd prefix', 'load FlowNet Fusion model weights and biases into PyTorch modules for fusing multiple flow predictions', 'use TimerBlock as a context manager to time and log code block execution duration', 'use add_arguments_for_module to auto-generate argparse arguments from a class constructor signature', 'use kwargs_from_args to extract prefixed argument values from parsed argparse namespace into a dict', 'use save_checkpoint to save a PyTorch model state dict and optionally copy the best model', 'use format_dictionary_of_losses to format a list of loss labels and values into a readable string']
```

Usage

```
{'create_timer_context': 'use TimerBlock as a context manager to time and log code block execution duration', 'add_argparse_args_from_class': 'use add_arguments_for_module to auto-generate argparse arguments from a class constructor signature', 'extract_kwargs_from_args': 'use kwargs_from_args to extract prefixed argument values from parsed argparse namespace into a dict', 'save_torch_checkpoint': 'use save_checkpoint to save a PyTorch model state dict and optionally copy the best model', 'format_loss_values': 'use format_dictionary_of_losses to format a list of loss labels and values into a readable string'}
```

