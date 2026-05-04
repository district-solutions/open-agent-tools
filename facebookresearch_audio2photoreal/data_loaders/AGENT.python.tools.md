# Agent Python Tools

- repo: facebookresearch/audio2photoreal
- repo_uri: https://github.com/facebookresearch/audio2photoreal

## File: facebookresearch_audio2photoreal/data_loaders/data.py

Prompts

```
['create a Social PyTorch dataset for audio-driven motion generation with train val and test splits', 'review the Social class inv_transform method that denormalizes pose face or audio data using loaded stats', 'build a data loader using Social __getitem__ to sample normalized motion audio and keyframes per item', 'test the Social _chunk_data method that splits long sequences into fixed-length chunks for test splits', 'summarize the Social _get_random_subsection method that randomly samples variable-length subsequences with padding for training', 'load pose, face, and audio data from a local directory into a structured dictionary', 'create a PyTorch DataLoader from a data dictionary with configurable batch size and split', 'load body pose, face expression, and audio data from a list of file paths', 'review the load_local_data function to understand how it handles person flipping and data loading', 'refactor the get_dataset_loader function to support custom collate functions and worker counts', 'create a boolean mask tensor from sequence lengths and a maximum length value', 'collate a batch of variable-sized tensors into a single padded tensor canvas', 'collate a pre-adapted batch of motion, audio, and keyframe tensors into a conditioned output', 'collate a raw social motion batch with audio and keyframes into padded tensors and conditions', 'review the collate_tensors and social_collate functions for PyTorch DataLoader integration']
```

Usage

```
{'create_social_dataset': 'create a Social PyTorch dataset for audio-driven motion generation with train val and test splits', 'review_Social_inv_transform': 'review the Social class inv_transform method that denormalizes pose face or audio data using loaded stats', 'build_Social_getitem': 'build a data loader using Social __getitem__ to sample normalized motion audio and keyframes per item', 'test_Social_chunk_data': 'test the Social _chunk_data method that splits long sequences into fixed-length chunks for test splits', 'summarize_Social_get_random_subsection': 'summarize the Social _get_random_subsection method that randomly samples variable-length subsequences with padding for training'}
```

## File: facebookresearch_audio2photoreal/data_loaders/get_data.py

Prompts

```
['create a Social PyTorch dataset for audio-driven motion generation with train val and test splits', 'review the Social class inv_transform method that denormalizes pose face or audio data using loaded stats', 'build a data loader using Social __getitem__ to sample normalized motion audio and keyframes per item', 'test the Social _chunk_data method that splits long sequences into fixed-length chunks for test splits', 'summarize the Social _get_random_subsection method that randomly samples variable-length subsequences with padding for training', 'load pose, face, and audio data from a local directory into a structured dictionary', 'create a PyTorch DataLoader from a data dictionary with configurable batch size and split', 'load body pose, face expression, and audio data from a list of file paths', 'review the load_local_data function to understand how it handles person flipping and data loading', 'refactor the get_dataset_loader function to support custom collate functions and worker counts', 'create a boolean mask tensor from sequence lengths and a maximum length value', 'collate a batch of variable-sized tensors into a single padded tensor canvas', 'collate a pre-adapted batch of motion, audio, and keyframe tensors into a conditioned output', 'collate a raw social motion batch with audio and keyframes into padded tensors and conditions', 'review the collate_tensors and social_collate functions for PyTorch DataLoader integration']
```

Usage

```
{'load_local_data': 'load pose, face, and audio data from a local directory into a structured dictionary', 'get_dataset_loader': 'create a PyTorch DataLoader from a data dictionary with configurable batch size and split', 'load_pose_data': 'load body pose, face expression, and audio data from a list of file paths', 'review_load_local_data': 'review the load_local_data function to understand how it handles person flipping and data loading', 'refactor_get_dataset_loader': 'refactor the get_dataset_loader function to support custom collate functions and worker counts'}
```

## File: facebookresearch_audio2photoreal/data_loaders/tensors.py

Prompts

```
['create a Social PyTorch dataset for audio-driven motion generation with train val and test splits', 'review the Social class inv_transform method that denormalizes pose face or audio data using loaded stats', 'build a data loader using Social __getitem__ to sample normalized motion audio and keyframes per item', 'test the Social _chunk_data method that splits long sequences into fixed-length chunks for test splits', 'summarize the Social _get_random_subsection method that randomly samples variable-length subsequences with padding for training', 'load pose, face, and audio data from a local directory into a structured dictionary', 'create a PyTorch DataLoader from a data dictionary with configurable batch size and split', 'load body pose, face expression, and audio data from a list of file paths', 'review the load_local_data function to understand how it handles person flipping and data loading', 'refactor the get_dataset_loader function to support custom collate functions and worker counts', 'create a boolean mask tensor from sequence lengths and a maximum length value', 'collate a batch of variable-sized tensors into a single padded tensor canvas', 'collate a pre-adapted batch of motion, audio, and keyframe tensors into a conditioned output', 'collate a raw social motion batch with audio and keyframes into padded tensors and conditions', 'review the collate_tensors and social_collate functions for PyTorch DataLoader integration']
```

Usage

```
{'create_length_mask': 'create a boolean mask tensor from sequence lengths and a maximum length value', 'collate_variable_tensors': 'collate a batch of variable-sized tensors into a single padded tensor canvas', 'collate_social_batch_v2': 'collate a pre-adapted batch of motion, audio, and keyframe tensors into a conditioned output', 'collate_social_batch': 'collate a raw social motion batch with audio and keyframes into padded tensors and conditions', 'review_collate_functions': 'review the collate_tensors and social_collate functions for PyTorch DataLoader integration'}
```

