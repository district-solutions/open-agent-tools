# Agent Python Tools

- repo: facebookresearch/dvsr
- repo_uri: https://github.com/facebookresearch/dvsr

## File: facebookresearch_dvsr/datasets/builder.py

Prompts

```
['build a dataset from a config dict using build_dataset with type and default_args', 'build a PyTorch DataLoader with distributed sampling and configurable batch size and workers', 'create a DistributedSampler that shuffles dataset indices across GPU replicas with seed synchronization', 'review the DistributedSampler class __init__ to understand num_samples_per_replica calculation and seed sync', 'test the worker_init_fn to verify each DataLoader worker gets a unique random seed', 'create a CustomRGBDMultiFrameDataset instance with pipeline, guide_folder, gt_folder, split_file, and frame config', 'review the get_cont_sub_sequence method to extract sliding window sub-sequences from a sequence list', 'review the get_cont_sub_sequence_from_lists method to extract sub-sequences from a list of sequences', 'test the load_annotations method to parse split files and build gt_path and guide_path lists', 'summarize the evaluate method to compute averaged evaluation metrics from model test results', 'build a DToFSimulator in peak mode to generate synthetic dToF depth maps from ground truth depth and guide images', 'build a DToFSimulator in mpeak mode to generate compressed multi-peak dToF histograms from depth and guide images', 'build a DToFSimulator in rebin mode to compress precomputed histograms into multi-peak representations', 'create a full dToF histogram from depth and guide image using weighted bincount per spatial block', 'create a compressed histogram by rebinning based on uniform intervals and local peak detection', 'create a function that converts numpy arrays, ints, floats, or sequences to torch.Tensor objects', 'build a ToTensor pipeline class that converts specified dict keys to torch tensors in a data loader', 'create an ImageToTensor pipeline that converts numpy images to float32 tensors with channel-first layout', 'build a FramesToTensor pipeline that stacks a list of frame images into a single tensor along dim 0', 'create a Collect pipeline that gathers specified keys and metadata into a DataContainer for model input']
```

Usage

```
{'build_dataset_from_cfg': 'build a dataset from a config dict using build_dataset with type and default_args', 'build_dataloader_for_training': 'build a PyTorch DataLoader with distributed sampling and configurable batch size and workers', 'create_distributed_sampler': 'create a DistributedSampler that shuffles dataset indices across GPU replicas with seed synchronization', 'review_distributed_sampler_init': 'review the DistributedSampler class __init__ to understand num_samples_per_replica calculation and seed sync', 'test_worker_init_fn': 'test the worker_init_fn to verify each DataLoader worker gets a unique random seed'}
```

## File: facebookresearch_dvsr/datasets/custom_rgbd_mf.py

Prompts

```
['build a dataset from a config dict using build_dataset with type and default_args', 'build a PyTorch DataLoader with distributed sampling and configurable batch size and workers', 'create a DistributedSampler that shuffles dataset indices across GPU replicas with seed synchronization', 'review the DistributedSampler class __init__ to understand num_samples_per_replica calculation and seed sync', 'test the worker_init_fn to verify each DataLoader worker gets a unique random seed', 'create a CustomRGBDMultiFrameDataset instance with pipeline, guide_folder, gt_folder, split_file, and frame config', 'review the get_cont_sub_sequence method to extract sliding window sub-sequences from a sequence list', 'review the get_cont_sub_sequence_from_lists method to extract sub-sequences from a list of sequences', 'test the load_annotations method to parse split files and build gt_path and guide_path lists', 'summarize the evaluate method to compute averaged evaluation metrics from model test results', 'build a DToFSimulator in peak mode to generate synthetic dToF depth maps from ground truth depth and guide images', 'build a DToFSimulator in mpeak mode to generate compressed multi-peak dToF histograms from depth and guide images', 'build a DToFSimulator in rebin mode to compress precomputed histograms into multi-peak representations', 'create a full dToF histogram from depth and guide image using weighted bincount per spatial block', 'create a compressed histogram by rebinning based on uniform intervals and local peak detection', 'create a function that converts numpy arrays, ints, floats, or sequences to torch.Tensor objects', 'build a ToTensor pipeline class that converts specified dict keys to torch tensors in a data loader', 'create an ImageToTensor pipeline that converts numpy images to float32 tensors with channel-first layout', 'build a FramesToTensor pipeline that stacks a list of frame images into a single tensor along dim 0', 'create a Collect pipeline that gathers specified keys and metadata into a DataContainer for model input']
```

Usage

```
{'create_CustomRGBDMultiFrameDataset': 'create a CustomRGBDMultiFrameDataset instance with pipeline, guide_folder, gt_folder, split_file, and frame config', 'review_get_cont_sub_sequence': 'review the get_cont_sub_sequence method to extract sliding window sub-sequences from a sequence list', 'review_get_cont_sub_sequence_from_lists': 'review the get_cont_sub_sequence_from_lists method to extract sub-sequences from a list of sequences', 'test_load_annotations': 'test the load_annotations method to parse split files and build gt_path and guide_path lists', 'summarize_evaluate': 'summarize the evaluate method to compute averaged evaluation metrics from model test results'}
```

## File: facebookresearch_dvsr/datasets/dtof_simulator.py

Prompts

```
['build a dataset from a config dict using build_dataset with type and default_args', 'build a PyTorch DataLoader with distributed sampling and configurable batch size and workers', 'create a DistributedSampler that shuffles dataset indices across GPU replicas with seed synchronization', 'review the DistributedSampler class __init__ to understand num_samples_per_replica calculation and seed sync', 'test the worker_init_fn to verify each DataLoader worker gets a unique random seed', 'create a CustomRGBDMultiFrameDataset instance with pipeline, guide_folder, gt_folder, split_file, and frame config', 'review the get_cont_sub_sequence method to extract sliding window sub-sequences from a sequence list', 'review the get_cont_sub_sequence_from_lists method to extract sub-sequences from a list of sequences', 'test the load_annotations method to parse split files and build gt_path and guide_path lists', 'summarize the evaluate method to compute averaged evaluation metrics from model test results', 'build a DToFSimulator in peak mode to generate synthetic dToF depth maps from ground truth depth and guide images', 'build a DToFSimulator in mpeak mode to generate compressed multi-peak dToF histograms from depth and guide images', 'build a DToFSimulator in rebin mode to compress precomputed histograms into multi-peak representations', 'create a full dToF histogram from depth and guide image using weighted bincount per spatial block', 'create a compressed histogram by rebinning based on uniform intervals and local peak detection', 'create a function that converts numpy arrays, ints, floats, or sequences to torch.Tensor objects', 'build a ToTensor pipeline class that converts specified dict keys to torch tensors in a data loader', 'create an ImageToTensor pipeline that converts numpy images to float32 tensors with channel-first layout', 'build a FramesToTensor pipeline that stacks a list of frame images into a single tensor along dim 0', 'create a Collect pipeline that gathers specified keys and metadata into a DataContainer for model input']
```

Usage

```
{'build_dtofsimulator_peak': 'build a DToFSimulator in peak mode to generate synthetic dToF depth maps from ground truth depth and guide images', 'build_dtofsimulator_mpeak': 'build a DToFSimulator in mpeak mode to generate compressed multi-peak dToF histograms from depth and guide images', 'build_dtofsimulator_rebin': 'build a DToFSimulator in rebin mode to compress precomputed histograms into multi-peak representations', 'create_dtof_hist': 'create a full dToF histogram from depth and guide image using weighted bincount per spatial block', 'create_rebin_hist': 'create a compressed histogram by rebinning based on uniform intervals and local peak detection'}
```

## File: facebookresearch_dvsr/datasets/formating.py

Prompts

```
['build a dataset from a config dict using build_dataset with type and default_args', 'build a PyTorch DataLoader with distributed sampling and configurable batch size and workers', 'create a DistributedSampler that shuffles dataset indices across GPU replicas with seed synchronization', 'review the DistributedSampler class __init__ to understand num_samples_per_replica calculation and seed sync', 'test the worker_init_fn to verify each DataLoader worker gets a unique random seed', 'create a CustomRGBDMultiFrameDataset instance with pipeline, guide_folder, gt_folder, split_file, and frame config', 'review the get_cont_sub_sequence method to extract sliding window sub-sequences from a sequence list', 'review the get_cont_sub_sequence_from_lists method to extract sub-sequences from a list of sequences', 'test the load_annotations method to parse split files and build gt_path and guide_path lists', 'summarize the evaluate method to compute averaged evaluation metrics from model test results', 'build a DToFSimulator in peak mode to generate synthetic dToF depth maps from ground truth depth and guide images', 'build a DToFSimulator in mpeak mode to generate compressed multi-peak dToF histograms from depth and guide images', 'build a DToFSimulator in rebin mode to compress precomputed histograms into multi-peak representations', 'create a full dToF histogram from depth and guide image using weighted bincount per spatial block', 'create a compressed histogram by rebinning based on uniform intervals and local peak detection', 'create a function that converts numpy arrays, ints, floats, or sequences to torch.Tensor objects', 'build a ToTensor pipeline class that converts specified dict keys to torch tensors in a data loader', 'create an ImageToTensor pipeline that converts numpy images to float32 tensors with channel-first layout', 'build a FramesToTensor pipeline that stacks a list of frame images into a single tensor along dim 0', 'create a Collect pipeline that gathers specified keys and metadata into a DataContainer for model input']
```

Usage

```
{'convert_numpy_to_torch_tensor': 'create a function that converts numpy arrays, ints, floats, or sequences to torch.Tensor objects', 'convert_dict_values_to_tensor': 'build a ToTensor pipeline class that converts specified dict keys to torch tensors in a data loader', 'convert_image_to_tensor': 'create an ImageToTensor pipeline that converts numpy images to float32 tensors with channel-first layout', 'convert_frames_to_tensor': 'build a FramesToTensor pipeline that stacks a list of frame images into a single tensor along dim 0', 'collect_pipeline_data': 'create a Collect pipeline that gathers specified keys and metadata into a DataContainer for model input'}
```

