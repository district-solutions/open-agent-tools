# Agent Python Tools

- repo: facebookresearch/dynamicstereo
- repo_uri: https://github.com/facebookresearch/dynamic_stereo

## File: facebookresearch_dynamicstereo/models/dynamic_stereo_model.py

Prompts

```
['build a DynamicStereoModel that loads pretrained weights and runs inference on a batch dictionary', 'run the DynamicStereoModel forward pass on a batch_dict with configurable iterations and kernel size', 'review the DynamicStereoModel class that wraps DynamicStereo with pretrained checkpoint loading and CUDA setup', 'summarize the DynamicStereoModel forward method that calls forward_batch_test with kernel_size and iters parameters', 'test the DynamicStereoModel __post_init__ method that loads state_dict weights and initializes the internal DynamicStereo model', 'build a RAFTStereoModel to estimate disparity maps from left-right stereo image pairs', 'run the RAFTStereoModel forward pass on a batch_dict with stereo_video pairs to get disparity', 'create a RAFTStereoModel with custom model_weights path and default hidden_dims and corr_levels config', 'review the RAFTStereoModel forward method that pads inputs, runs inference with autocast, and returns disparity', 'test the RAFTStereoModel post_init that loads pretrained weights and sets the model to eval mode on CUDA']
```

Usage

```
{'build_dynamic_stereo_model': 'build a DynamicStereoModel that loads pretrained weights and runs inference on a batch dictionary', 'run_dynamic_stereo_inference': 'run the DynamicStereoModel forward pass on a batch_dict with configurable iterations and kernel size', 'review_DynamicStereoModel': 'review the DynamicStereoModel class that wraps DynamicStereo with pretrained checkpoint loading and CUDA setup', 'summarize_DynamicStereoModel_forward': 'summarize the DynamicStereoModel forward method that calls forward_batch_test with kernel_size and iters parameters', 'test_DynamicStereoModel_post_init': 'test the DynamicStereoModel __post_init__ method that loads state_dict weights and initializes the internal DynamicStereo model'}
```

## File: facebookresearch_dynamicstereo/models/raft_stereo_model.py

Prompts

```
['build a DynamicStereoModel that loads pretrained weights and runs inference on a batch dictionary', 'run the DynamicStereoModel forward pass on a batch_dict with configurable iterations and kernel size', 'review the DynamicStereoModel class that wraps DynamicStereo with pretrained checkpoint loading and CUDA setup', 'summarize the DynamicStereoModel forward method that calls forward_batch_test with kernel_size and iters parameters', 'test the DynamicStereoModel __post_init__ method that loads state_dict weights and initializes the internal DynamicStereo model', 'build a RAFTStereoModel to estimate disparity maps from left-right stereo image pairs', 'run the RAFTStereoModel forward pass on a batch_dict with stereo_video pairs to get disparity', 'create a RAFTStereoModel with custom model_weights path and default hidden_dims and corr_levels config', 'review the RAFTStereoModel forward method that pads inputs, runs inference with autocast, and returns disparity', 'test the RAFTStereoModel post_init that loads pretrained weights and sets the model to eval mode on CUDA']
```

Usage

```
{'build_stereo_disparity_model': 'build a RAFTStereoModel to estimate disparity maps from left-right stereo image pairs', 'run_disparity_inference': 'run the RAFTStereoModel forward pass on a batch_dict with stereo_video pairs to get disparity', 'create_stereo_model_config': 'create a RAFTStereoModel with custom model_weights path and default hidden_dims and corr_levels config', 'review_RAFTStereoModel_forward': 'review the RAFTStereoModel forward method that pads inputs, runs inference with autocast, and returns disparity', 'test_RAFTStereoModel_initialization': 'test the RAFTStereoModel post_init that loads pretrained weights and sets the model to eval mode on CUDA'}
```

