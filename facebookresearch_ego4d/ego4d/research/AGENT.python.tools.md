# Agent Python Tools

- repo: facebookresearch/ego4d
- repo_uri: https://github.com/facebookresearch/ego4d

## File: facebookresearch_ego4d/ego4d/research/chunk.py

Prompts

```
['split a video file into fixed-duration chunks yielding VideoChunk objects with video and audio frames', 'split a video into chunks and subsample each chunk to a fixed number of evenly spaced frames', 'save a VideoChunk object as numpy arrays and metadata JSON to a specified output directory', 'create a VideoChunk dataclass instance holding video frames, audio frames, timestamps, and codec metadata', 'iterate over video chunks with a window size in seconds and a maximum number of chunks to yield', 'create a SlurmConfig dataclass with log folder, timeout, partition, and GPU settings', 'create a function that splits a list into evenly sized batches of a given size', 'create a submitit executor using SlurmConfig for local or SLURM job execution', 'review the SlurmConfig dataclass fields and default values for SLURM job configuration', 'refactor the batch_it function to use list comprehension instead of a for loop', 'create a LabelledFeatureDset to load features from an HDF5 file paired with labels', 'save a list of PyTorch feature tensors from a directory into a single HDF5 file', 'create a VideoDataset to index and iterate over video frames from multiple video paths', 'review the VideoDataset __getitem__ method to understand lazy container creation and frame indexing', 'test the LabelledFeatureDset custom aggregation function to verify feature and label pairing', 'get video metadata including frame count, codec, time base, width, and height from a video file path', 'convert a YUV format torch tensor to RGB format using standard color space conversion coefficients', "derive a permutation tuple from a string like 'cthw' or 'thwc' for reordering video tensor axes", 'create a GPU-accelerated video reader using TorchAudio StreamReader with optional hardware resize and normalization transforms', 'create a CPU-based video reader using PyAV that decodes frames into normalized RGB tensors with optional resize and crop']
```

Usage

```
{'split_video_into_chunks': 'split a video file into fixed-duration chunks yielding VideoChunk objects with video and audio frames', 'subsample_video_frames': 'split a video into chunks and subsample each chunk to a fixed number of evenly spaced frames', 'save_video_chunk_to_disk': 'save a VideoChunk object as numpy arrays and metadata JSON to a specified output directory', 'create_video_chunk_dataclass': 'create a VideoChunk dataclass instance holding video frames, audio frames, timestamps, and codec metadata', 'iterate_video_chunks_with_limit': 'iterate over video chunks with a window size in seconds and a maximum number of chunks to yield'}
```

## File: facebookresearch_ego4d/ego4d/research/common.py

Prompts

```
['split a video file into fixed-duration chunks yielding VideoChunk objects with video and audio frames', 'split a video into chunks and subsample each chunk to a fixed number of evenly spaced frames', 'save a VideoChunk object as numpy arrays and metadata JSON to a specified output directory', 'create a VideoChunk dataclass instance holding video frames, audio frames, timestamps, and codec metadata', 'iterate over video chunks with a window size in seconds and a maximum number of chunks to yield', 'create a SlurmConfig dataclass with log folder, timeout, partition, and GPU settings', 'create a function that splits a list into evenly sized batches of a given size', 'create a submitit executor using SlurmConfig for local or SLURM job execution', 'review the SlurmConfig dataclass fields and default values for SLURM job configuration', 'refactor the batch_it function to use list comprehension instead of a for loop', 'create a LabelledFeatureDset to load features from an HDF5 file paired with labels', 'save a list of PyTorch feature tensors from a directory into a single HDF5 file', 'create a VideoDataset to index and iterate over video frames from multiple video paths', 'review the VideoDataset __getitem__ method to understand lazy container creation and frame indexing', 'test the LabelledFeatureDset custom aggregation function to verify feature and label pairing', 'get video metadata including frame count, codec, time base, width, and height from a video file path', 'convert a YUV format torch tensor to RGB format using standard color space conversion coefficients', "derive a permutation tuple from a string like 'cthw' or 'thwc' for reordering video tensor axes", 'create a GPU-accelerated video reader using TorchAudio StreamReader with optional hardware resize and normalization transforms', 'create a CPU-based video reader using PyAV that decodes frames into normalized RGB tensors with optional resize and crop']
```

Usage

```
{'create_slurm_config': 'create a SlurmConfig dataclass with log folder, timeout, partition, and GPU settings', 'batch_it_function': 'create a function that splits a list into evenly sized batches of a given size', 'create_executor_slurm': 'create a submitit executor using SlurmConfig for local or SLURM job execution', 'review_slurm_config_dataclass': 'review the SlurmConfig dataclass fields and default values for SLURM job configuration', 'refactor_batch_it': 'refactor the batch_it function to use list comprehension instead of a for loop'}
```

## File: facebookresearch_ego4d/ego4d/research/dataset.py

Prompts

```
['split a video file into fixed-duration chunks yielding VideoChunk objects with video and audio frames', 'split a video into chunks and subsample each chunk to a fixed number of evenly spaced frames', 'save a VideoChunk object as numpy arrays and metadata JSON to a specified output directory', 'create a VideoChunk dataclass instance holding video frames, audio frames, timestamps, and codec metadata', 'iterate over video chunks with a window size in seconds and a maximum number of chunks to yield', 'create a SlurmConfig dataclass with log folder, timeout, partition, and GPU settings', 'create a function that splits a list into evenly sized batches of a given size', 'create a submitit executor using SlurmConfig for local or SLURM job execution', 'review the SlurmConfig dataclass fields and default values for SLURM job configuration', 'refactor the batch_it function to use list comprehension instead of a for loop', 'create a LabelledFeatureDset to load features from an HDF5 file paired with labels', 'save a list of PyTorch feature tensors from a directory into a single HDF5 file', 'create a VideoDataset to index and iterate over video frames from multiple video paths', 'review the VideoDataset __getitem__ method to understand lazy container creation and frame indexing', 'test the LabelledFeatureDset custom aggregation function to verify feature and label pairing', 'get video metadata including frame count, codec, time base, width, and height from a video file path', 'convert a YUV format torch tensor to RGB format using standard color space conversion coefficients', "derive a permutation tuple from a string like 'cthw' or 'thwc' for reordering video tensor axes", 'create a GPU-accelerated video reader using TorchAudio StreamReader with optional hardware resize and normalization transforms', 'create a CPU-based video reader using PyAV that decodes frames into normalized RGB tensors with optional resize and crop']
```

Usage

```
{'create_LabelledFeatureDset': 'create a LabelledFeatureDset to load features from an HDF5 file paired with labels', 'save_features_to_hdf5': 'save a list of PyTorch feature tensors from a directory into a single HDF5 file', 'create_VideoDataset': 'create a VideoDataset to index and iterate over video frames from multiple video paths', 'review_VideoDataset_getitem': 'review the VideoDataset __getitem__ method to understand lazy container creation and frame indexing', 'test_LabelledFeatureDset_aggr_function': 'test the LabelledFeatureDset custom aggregation function to verify feature and label pairing'}
```

## File: facebookresearch_ego4d/ego4d/research/readers.py

Prompts

```
['split a video file into fixed-duration chunks yielding VideoChunk objects with video and audio frames', 'split a video into chunks and subsample each chunk to a fixed number of evenly spaced frames', 'save a VideoChunk object as numpy arrays and metadata JSON to a specified output directory', 'create a VideoChunk dataclass instance holding video frames, audio frames, timestamps, and codec metadata', 'iterate over video chunks with a window size in seconds and a maximum number of chunks to yield', 'create a SlurmConfig dataclass with log folder, timeout, partition, and GPU settings', 'create a function that splits a list into evenly sized batches of a given size', 'create a submitit executor using SlurmConfig for local or SLURM job execution', 'review the SlurmConfig dataclass fields and default values for SLURM job configuration', 'refactor the batch_it function to use list comprehension instead of a for loop', 'create a LabelledFeatureDset to load features from an HDF5 file paired with labels', 'save a list of PyTorch feature tensors from a directory into a single HDF5 file', 'create a VideoDataset to index and iterate over video frames from multiple video paths', 'review the VideoDataset __getitem__ method to understand lazy container creation and frame indexing', 'test the LabelledFeatureDset custom aggregation function to verify feature and label pairing', 'get video metadata including frame count, codec, time base, width, and height from a video file path', 'convert a YUV format torch tensor to RGB format using standard color space conversion coefficients', "derive a permutation tuple from a string like 'cthw' or 'thwc' for reordering video tensor axes", 'create a GPU-accelerated video reader using TorchAudio StreamReader with optional hardware resize and normalization transforms', 'create a CPU-based video reader using PyAV that decodes frames into normalized RGB tensors with optional resize and crop']
```

Usage

```
{'get_video_meta': 'get video metadata including frame count, codec, time base, width, and height from a video file path', 'yuv_to_rgb': 'convert a YUV format torch tensor to RGB format using standard color space conversion coefficients', 'derive_cthw_axis_order': "derive a permutation tuple from a string like 'cthw' or 'thwc' for reordering video tensor axes", 'create_TorchAudioStreamReader': 'create a GPU-accelerated video reader using TorchAudio StreamReader with optional hardware resize and normalization transforms', 'create_PyAvReader': 'create a CPU-based video reader using PyAV that decodes frames into normalized RGB tensors with optional resize and crop'}
```

