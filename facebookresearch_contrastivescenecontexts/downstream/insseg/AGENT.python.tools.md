# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/ddp_main.py

Prompts

```
['run the segmentation training pipeline using Hydra config and DDP across multiple GPUs', 'run the segmentation testing pipeline using Hydra config on a single GPU', 'run the SegmentationTrainer on a single GPU process with the given config', 'run the SegmentationTrainer across multiple GPUs using multi_proc_run with DDP', 'run the main entry point that fixes random seeds and dispatches training or testing']
```

Usage

```
{'run_segmentation_training': 'run the segmentation training pipeline using Hydra config and DDP across multiple GPUs', 'run_segmentation_testing': 'run the segmentation testing pipeline using Hydra config on a single GPU', 'run_single_proc_training': 'run the SegmentationTrainer on a single GPU process with the given config', 'run_multi_gpu_training': 'run the SegmentationTrainer across multiple GPUs using multi_proc_run with DDP', 'run_main_entry': 'run the main entry point that fixes random seeds and dispatches training or testing'}
```

