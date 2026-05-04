# Agent Python Tools

- repo: facebookresearch/flowdec
- repo_uri: https://github.com/facebookresearch/flowdec

## File: facebookresearch_flowdec/enhance.py

Prompts

```
['run the enhancement model on WAV files in a directory using a checkpoint and flow solver', 'run the enhancement model on a single WAV file with specified NFE and midpoint solver', 'run the enhancement model on audio files and calculate real-time factor for each file', 'run the enhancement model using a file list with clean-to-noisy pairs and output triples', 'run the enhancement model using reverse diffusion predictor and ALD corrector with custom SNR', 'review how EnhancementModel is loaded from checkpoint and used for audio enhancement with flow or score solvers', 'review the read_list function that parses file lists supporting pairs separated by arrows or commas', 'refactor the enhance_kwargs dictionary to support additional solver or predictor parameters for the model', "test the read_list function with a file containing pairs separated by ' ---> ' or commas", 'summarize the CLI arguments for running audio enhancement including checkpoint, files, solver, and discretization options', 'run a PyTorch Lightning training loop with Hydra config and SLURM support', 'find the latest checkpoint file for a SLURM job to auto-resume training', 'set up SLURM auto-requeue and checkpoint symlinks for preemptible training jobs', 'instantiate a WandbLogger or TensorBoardLogger from a Hydra config for experiment tracking', 'instantiate PyTorch Lightning callbacks from config and update checkpoint dirpaths with run ID']
```

Usage

```
{'run_enhance_audio_files': 'run the enhancement model on WAV files in a directory using a checkpoint and flow solver', 'run_enhance_single_audio': 'run the enhancement model on a single WAV file with specified NFE and midpoint solver', 'run_enhance_with_rtf': 'run the enhancement model on audio files and calculate real-time factor for each file', 'run_enhance_with_pairs_list': 'run the enhancement model using a file list with clean-to-noisy pairs and output triples', 'run_enhance_score_model': 'run the enhancement model using reverse diffusion predictor and ALD corrector with custom SNR', 'review_enhancementmodel_usage': 'review how EnhancementModel is loaded from checkpoint and used for audio enhancement with flow or score solvers', 'review_read_list_function': 'review the read_list function that parses file lists supporting pairs separated by arrows or commas', 'refactor_enhance_kwargs': 'refactor the enhance_kwargs dictionary to support additional solver or predictor parameters for the model', 'test_read_list_pairs': "test the read_list function with a file containing pairs separated by ' ---> ' or commas", 'summarize_enhance_cli': 'summarize the CLI arguments for running audio enhancement including checkpoint, files, solver, and discretization options'}
```

## File: facebookresearch_flowdec/train.py

Prompts

```
['run the enhancement model on WAV files in a directory using a checkpoint and flow solver', 'run the enhancement model on a single WAV file with specified NFE and midpoint solver', 'run the enhancement model on audio files and calculate real-time factor for each file', 'run the enhancement model using a file list with clean-to-noisy pairs and output triples', 'run the enhancement model using reverse diffusion predictor and ALD corrector with custom SNR', 'review how EnhancementModel is loaded from checkpoint and used for audio enhancement with flow or score solvers', 'review the read_list function that parses file lists supporting pairs separated by arrows or commas', 'refactor the enhance_kwargs dictionary to support additional solver or predictor parameters for the model', "test the read_list function with a file containing pairs separated by ' ---> ' or commas", 'summarize the CLI arguments for running audio enhancement including checkpoint, files, solver, and discretization options', 'run a PyTorch Lightning training loop with Hydra config and SLURM support', 'find the latest checkpoint file for a SLURM job to auto-resume training', 'set up SLURM auto-requeue and checkpoint symlinks for preemptible training jobs', 'instantiate a WandbLogger or TensorBoardLogger from a Hydra config for experiment tracking', 'instantiate PyTorch Lightning callbacks from config and update checkpoint dirpaths with run ID']
```

Usage

```
{'run_training': 'run a PyTorch Lightning training loop with Hydra config and SLURM support', 'find_latest_slurm_ckpt': 'find the latest checkpoint file for a SLURM job to auto-resume training', 'set_up_slurm': 'set up SLURM auto-requeue and checkpoint symlinks for preemptible training jobs', 'instantiate_run_logger': 'instantiate a WandbLogger or TensorBoardLogger from a Hydra config for experiment tracking', 'instantiate_callbacks': 'instantiate PyTorch Lightning callbacks from config and update checkpoint dirpaths with run ID'}
```

