# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/examples/video_classification/video_classification.py

Prompts

```
['run the video classification training module with torchrun on a kinetics-400 dataset using R3D-18 model', 'train an R3D-18 video classification model using distributed data parallel with AdamW optimizer and gradient clipping', 'parse command line arguments for video classification training including batch size, learning rate, and frame dimensions', 'initialize logging with rank-aware formatting for distributed training processes', 'build an SPDL data pipeline with GPU NVDEC hardware decoding for concurrent video frame sampling and decoding']
```

Usage

```
{'run_video_classification': 'run the video classification training module with torchrun on a kinetics-400 dataset using R3D-18 model', 'train_R3D18_model': 'train an R3D-18 video classification model using distributed data parallel with AdamW optimizer and gradient clipping', 'parse_training_args': 'parse command line arguments for video classification training including batch size, learning rate, and frame dimensions', 'init_distributed_logging': 'initialize logging with rank-aware formatting for distributed training processes', 'build_video_pipeline': 'build an SPDL data pipeline with GPU NVDEC hardware decoding for concurrent video frame sampling and decoding'}
```

