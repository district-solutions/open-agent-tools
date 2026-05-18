# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/examples/run_fbnet_v2.py

Prompts

```
['run the fbnet v2 model on a downloaded image and print softmax output', 'run the _get_input function to download and open an example image from a URL', 'run the fbnet factory function to load a pretrained model by name', 'run the get_preprocess function to get an image preprocessing pipeline for a given input size', 'run softmax on the model output tensor and print the maximum class probability', 'run the fbnet v2 jit int8 quantized model on a downloaded dog image and print softmax output', 'run model_jit to load a pretrained fbnet_c_i8f_int8_jit quantized model in jit format', 'run torch backends quantized engine set to qnnpack for int8 quantized model inference', 'run the flops estimation script to compute per module FLOPs and parameters for an FBNet model', 'create an FBNet model by name using the fbnet constructor with pretrained set to False', 'print the FLOPs and parameter count for each module of a PyTorch model using flops_utils', 'build a dummy input batch tensor with torch.zeros matching the model input size from arch_def', 'review the run_flops_estimation function to understand how FBNet models are profiled for FLOPs and parameters']
```

Usage

```
{'run_fbnet_v2_inference': 'run the fbnet v2 model on a downloaded image and print softmax output', 'run_get_input': 'run the _get_input function to download and open an example image from a URL', 'run_fbnet_model': 'run the fbnet factory function to load a pretrained model by name', 'run_get_preprocess': 'run the get_preprocess function to get an image preprocessing pipeline for a given input size', 'run_softmax_output': 'run softmax on the model output tensor and print the maximum class probability'}
```

## File: facebookresearch_mobile-vision/examples/run_fbnet_v2_jit_int8.py

Prompts

```
['run the fbnet v2 model on a downloaded image and print softmax output', 'run the _get_input function to download and open an example image from a URL', 'run the fbnet factory function to load a pretrained model by name', 'run the get_preprocess function to get an image preprocessing pipeline for a given input size', 'run softmax on the model output tensor and print the maximum class probability', 'run the fbnet v2 jit int8 quantized model on a downloaded dog image and print softmax output', 'run model_jit to load a pretrained fbnet_c_i8f_int8_jit quantized model in jit format', 'run torch backends quantized engine set to qnnpack for int8 quantized model inference', 'run the flops estimation script to compute per module FLOPs and parameters for an FBNet model', 'create an FBNet model by name using the fbnet constructor with pretrained set to False', 'print the FLOPs and parameter count for each module of a PyTorch model using flops_utils', 'build a dummy input batch tensor with torch.zeros matching the model input size from arch_def', 'review the run_flops_estimation function to understand how FBNet models are profiled for FLOPs and parameters']
```

Usage

```
{'run_fbnet_v2_jit_int8': 'run the fbnet v2 jit int8 quantized model on a downloaded dog image and print softmax output', 'run_get_input': 'run the _get_input function to download and open an example dog image from the pytorch website', 'run_model_jit': 'run model_jit to load a pretrained fbnet_c_i8f_int8_jit quantized model in jit format', 'run_get_preprocess': 'run get_preprocess to create an image preprocessing function for 224x224 input size', 'run_quantized_engine': 'run torch backends quantized engine set to qnnpack for int8 quantized model inference'}
```

## File: facebookresearch_mobile-vision/examples/run_flops_estimation.py

Prompts

```
['run the fbnet v2 model on a downloaded image and print softmax output', 'run the _get_input function to download and open an example image from a URL', 'run the fbnet factory function to load a pretrained model by name', 'run the get_preprocess function to get an image preprocessing pipeline for a given input size', 'run softmax on the model output tensor and print the maximum class probability', 'run the fbnet v2 jit int8 quantized model on a downloaded dog image and print softmax output', 'run model_jit to load a pretrained fbnet_c_i8f_int8_jit quantized model in jit format', 'run torch backends quantized engine set to qnnpack for int8 quantized model inference', 'run the flops estimation script to compute per module FLOPs and parameters for an FBNet model', 'create an FBNet model by name using the fbnet constructor with pretrained set to False', 'print the FLOPs and parameter count for each module of a PyTorch model using flops_utils', 'build a dummy input batch tensor with torch.zeros matching the model input size from arch_def', 'review the run_flops_estimation function to understand how FBNet models are profiled for FLOPs and parameters']
```

Usage

```
{'run_flops_estimation': 'run the flops estimation script to compute per module FLOPs and parameters for an FBNet model', 'create_fbnet_model': 'create an FBNet model by name using the fbnet constructor with pretrained set to False', 'print_model_flops': 'print the FLOPs and parameter count for each module of a PyTorch model using flops_utils', 'build_dummy_input_batch': 'build a dummy input batch tensor with torch.zeros matching the model input size from arch_def', 'review_run_flops_estimation': 'review the run_flops_estimation function to understand how FBNet models are profiled for FLOPs and parameters'}
```

