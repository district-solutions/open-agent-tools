# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/audiocraft/grids/audiogen/audiogen_base_16khz.py

Prompts

```
['run the audiogen_base_16khz explorer to launch a 64 GPU SLURM training job for AudioGen', 'configure the LMExplorer decorator to set train and valid stages with perplexity tracking metrics', 'bind the audiogen_base_16khz solver and internal sounds dataset to the launcher', 'setup FSDP distributed training with autocast disabled for the medium scale AudioGen model', 'get SLURM partitions for team and global clusters using AudioCraftEnvironment', 'run objective metric evaluation for a pretrained AudioGen model on the AudioCaps 16kHz dataset', 'run the AudioGen evaluation explorer grid to launch SLURM jobs for the audiogen-medium model', 'run the dora grid with REGEN=1 to regenerate and evaluate the audiogen pretrained model', 'review the eval function to understand how FAD metrics and top-k sampling options are configured', 'review the explorer function to understand how SLURM partitions and cached grid signatures are handled']
```

Usage

```
{'run_audiogen_explorer': 'run the audiogen_base_16khz explorer to launch a 64 GPU SLURM training job for AudioGen', 'configure_lm_explorer': 'configure the LMExplorer decorator to set train and valid stages with perplexity tracking metrics', 'bind_solver_and_dataset': 'bind the audiogen_base_16khz solver and internal sounds dataset to the launcher', 'setup_fsdp_training': 'setup FSDP distributed training with autocast disabled for the medium scale AudioGen model', 'get_slurm_partitions': 'get SLURM partitions for team and global clusters using AudioCraftEnvironment'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/audiogen/audiogen_pretrained_16khz_eval.py

Prompts

```
['run the audiogen_base_16khz explorer to launch a 64 GPU SLURM training job for AudioGen', 'configure the LMExplorer decorator to set train and valid stages with perplexity tracking metrics', 'bind the audiogen_base_16khz solver and internal sounds dataset to the launcher', 'setup FSDP distributed training with autocast disabled for the medium scale AudioGen model', 'get SLURM partitions for team and global clusters using AudioCraftEnvironment', 'run objective metric evaluation for a pretrained AudioGen model on the AudioCaps 16kHz dataset', 'run the AudioGen evaluation explorer grid to launch SLURM jobs for the audiogen-medium model', 'run the dora grid with REGEN=1 to regenerate and evaluate the audiogen pretrained model', 'review the eval function to understand how FAD metrics and top-k sampling options are configured', 'review the explorer function to understand how SLURM partitions and cached grid signatures are handled']
```

Usage

```
{'run_eval': 'run objective metric evaluation for a pretrained AudioGen model on the AudioCaps 16kHz dataset', 'run_explorer': 'run the AudioGen evaluation explorer grid to launch SLURM jobs for the audiogen-medium model', 'run_grid_with_regen': 'run the dora grid with REGEN=1 to regenerate and evaluate the audiogen pretrained model', 'review_eval': 'review the eval function to understand how FAD metrics and top-k sampling options are configured', 'review_explorer': 'review the explorer function to understand how SLURM partitions and cached grid signatures are handled'}
```

