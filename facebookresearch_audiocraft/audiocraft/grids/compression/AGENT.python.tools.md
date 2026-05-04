# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/audiocraft/grids/compression/_explorers.py

Prompts

```
['create a CompressionExplorer instance to configure audio compression experiment tracking grids', 'get the grid meta columns like index, name, state, and sig for each XP job', 'get the train, valid, and evaluate metric groups with sisnr and visqol evaluation metrics', 'configure the eval_metrics list with sisnr and visqol for compression quality evaluation', 'define the train, valid, and evaluate stages for the compression experiment pipeline', 'run the compression debug grid search explorer to schedule SLURM experiments', 'configure SLURM job partitions using AudioCraftEnvironment get_slurm_partitions with team and global', 'bind the compression debug solver config using launcher bind_ with solver parameter', 'launch a job array with base debug task and parameter overrides via launcher', 'override RVQ bins and quantizer count parameters when launching compression debug experiments', 'run the explorer function to launch an AudioGen EnCodec training experiment at 16 kHz on SLURM', 'bind the internal sounds 16khz dataset configuration to the experiment launcher', 'launch a compression experiment with 8 GPUs using the CompressionExplorer decorator and launcher', 'run the base causal EnCodec 24kHz grid search experiment on SLURM with 8 GPUs', 'launch the EnCodec base 24kHz training experiment by calling the launcher', 'run the EnCodec MusicGen 32kHz grid search experiment on SLURM with 8 GPUs', 'run the EnCodec MusicGen 32kHz experiment with VISQOL quality metrics enabled']
```

Usage

```
{'create_compression_explorer': 'create a CompressionExplorer instance to configure audio compression experiment tracking grids', 'get_grid_meta_columns': 'get the grid meta columns like index, name, state, and sig for each XP job', 'get_grid_metrics_groups': 'get the train, valid, and evaluate metric groups with sisnr and visqol evaluation metrics', 'configure_eval_metrics': 'configure the eval_metrics list with sisnr and visqol for compression quality evaluation', 'define_explorer_stages': 'define the train, valid, and evaluate stages for the compression experiment pipeline'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/compression/debug.py

Prompts

```
['create a CompressionExplorer instance to configure audio compression experiment tracking grids', 'get the grid meta columns like index, name, state, and sig for each XP job', 'get the train, valid, and evaluate metric groups with sisnr and visqol evaluation metrics', 'configure the eval_metrics list with sisnr and visqol for compression quality evaluation', 'define the train, valid, and evaluate stages for the compression experiment pipeline', 'run the compression debug grid search explorer to schedule SLURM experiments', 'configure SLURM job partitions using AudioCraftEnvironment get_slurm_partitions with team and global', 'bind the compression debug solver config using launcher bind_ with solver parameter', 'launch a job array with base debug task and parameter overrides via launcher', 'override RVQ bins and quantizer count parameters when launching compression debug experiments', 'run the explorer function to launch an AudioGen EnCodec training experiment at 16 kHz on SLURM', 'bind the internal sounds 16khz dataset configuration to the experiment launcher', 'launch a compression experiment with 8 GPUs using the CompressionExplorer decorator and launcher', 'run the base causal EnCodec 24kHz grid search experiment on SLURM with 8 GPUs', 'launch the EnCodec base 24kHz training experiment by calling the launcher', 'run the EnCodec MusicGen 32kHz grid search experiment on SLURM with 8 GPUs', 'run the EnCodec MusicGen 32kHz experiment with VISQOL quality metrics enabled']
```

Usage

```
{'run_explorer_grid': 'run the compression debug grid search explorer to schedule SLURM experiments', 'configure_slurm_partitions': 'configure SLURM job partitions using AudioCraftEnvironment get_slurm_partitions with team and global', 'bind_solver_config': 'bind the compression debug solver config using launcher bind_ with solver parameter', 'launch_job_array': 'launch a job array with base debug task and parameter overrides via launcher', 'override_rvq_params': 'override RVQ bins and quantizer count parameters when launching compression debug experiments'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/compression/encodec_audiogen_16khz.py

Prompts

```
['create a CompressionExplorer instance to configure audio compression experiment tracking grids', 'get the grid meta columns like index, name, state, and sig for each XP job', 'get the train, valid, and evaluate metric groups with sisnr and visqol evaluation metrics', 'configure the eval_metrics list with sisnr and visqol for compression quality evaluation', 'define the train, valid, and evaluate stages for the compression experiment pipeline', 'run the compression debug grid search explorer to schedule SLURM experiments', 'configure SLURM job partitions using AudioCraftEnvironment get_slurm_partitions with team and global', 'bind the compression debug solver config using launcher bind_ with solver parameter', 'launch a job array with base debug task and parameter overrides via launcher', 'override RVQ bins and quantizer count parameters when launching compression debug experiments', 'run the explorer function to launch an AudioGen EnCodec training experiment at 16 kHz on SLURM', 'bind the internal sounds 16khz dataset configuration to the experiment launcher', 'launch a compression experiment with 8 GPUs using the CompressionExplorer decorator and launcher', 'run the base causal EnCodec 24kHz grid search experiment on SLURM with 8 GPUs', 'launch the EnCodec base 24kHz training experiment by calling the launcher', 'run the EnCodec MusicGen 32kHz grid search experiment on SLURM with 8 GPUs', 'run the EnCodec MusicGen 32kHz experiment with VISQOL quality metrics enabled']
```

Usage

```
{'run_encodec_audiogen_16khz_explorer': 'run the explorer function to launch an AudioGen EnCodec training experiment at 16 kHz on SLURM', 'configure_slurm_partitions': 'configure SLURM job partitions using AudioCraftEnvironment get_slurm_partitions with team and global scopes', 'bind_solver_config': 'bind the compression encodec audiogen 16khz solver configuration to the experiment launcher', 'bind_dataset_config': 'bind the internal sounds 16khz dataset configuration to the experiment launcher', 'launch_compression_experiment': 'launch a compression experiment with 8 GPUs using the CompressionExplorer decorator and launcher'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/compression/encodec_base_24khz.py

Prompts

```
['create a CompressionExplorer instance to configure audio compression experiment tracking grids', 'get the grid meta columns like index, name, state, and sig for each XP job', 'get the train, valid, and evaluate metric groups with sisnr and visqol evaluation metrics', 'configure the eval_metrics list with sisnr and visqol for compression quality evaluation', 'define the train, valid, and evaluate stages for the compression experiment pipeline', 'run the compression debug grid search explorer to schedule SLURM experiments', 'configure SLURM job partitions using AudioCraftEnvironment get_slurm_partitions with team and global', 'bind the compression debug solver config using launcher bind_ with solver parameter', 'launch a job array with base debug task and parameter overrides via launcher', 'override RVQ bins and quantizer count parameters when launching compression debug experiments', 'run the explorer function to launch an AudioGen EnCodec training experiment at 16 kHz on SLURM', 'bind the internal sounds 16khz dataset configuration to the experiment launcher', 'launch a compression experiment with 8 GPUs using the CompressionExplorer decorator and launcher', 'run the base causal EnCodec 24kHz grid search experiment on SLURM with 8 GPUs', 'launch the EnCodec base 24kHz training experiment by calling the launcher', 'run the EnCodec MusicGen 32kHz grid search experiment on SLURM with 8 GPUs', 'run the EnCodec MusicGen 32kHz experiment with VISQOL quality metrics enabled']
```

Usage

```
{'run_encodec_base_24khz_grid': 'run the base causal EnCodec 24kHz grid search experiment on SLURM with 8 GPUs', 'configure_slurm_partitions': 'configure SLURM partitions using AudioCraftEnvironment get_slurm_partitions for team and global access', 'bind_solver_config': 'bind the compression encodec_base_24khz solver configuration to the experiment launcher', 'bind_dataset_config': 'bind the audio example dataset to the experiment launcher via launcher bind_', 'launch_experiment': 'launch the EnCodec base 24kHz training experiment by calling the launcher'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/compression/encodec_musicgen_32khz.py

Prompts

```
['create a CompressionExplorer instance to configure audio compression experiment tracking grids', 'get the grid meta columns like index, name, state, and sig for each XP job', 'get the train, valid, and evaluate metric groups with sisnr and visqol evaluation metrics', 'configure the eval_metrics list with sisnr and visqol for compression quality evaluation', 'define the train, valid, and evaluate stages for the compression experiment pipeline', 'run the compression debug grid search explorer to schedule SLURM experiments', 'configure SLURM job partitions using AudioCraftEnvironment get_slurm_partitions with team and global', 'bind the compression debug solver config using launcher bind_ with solver parameter', 'launch a job array with base debug task and parameter overrides via launcher', 'override RVQ bins and quantizer count parameters when launching compression debug experiments', 'run the explorer function to launch an AudioGen EnCodec training experiment at 16 kHz on SLURM', 'bind the internal sounds 16khz dataset configuration to the experiment launcher', 'launch a compression experiment with 8 GPUs using the CompressionExplorer decorator and launcher', 'run the base causal EnCodec 24kHz grid search experiment on SLURM with 8 GPUs', 'launch the EnCodec base 24kHz training experiment by calling the launcher', 'run the EnCodec MusicGen 32kHz grid search experiment on SLURM with 8 GPUs', 'run the EnCodec MusicGen 32kHz experiment with VISQOL quality metrics enabled']
```

Usage

```
{'run_encodec_musicgen_32khz_grid': 'run the EnCodec MusicGen 32kHz grid search experiment on SLURM with 8 GPUs', 'run_visqol_evaluation': 'run the EnCodec MusicGen 32kHz experiment with VISQOL quality metrics enabled', 'configure_slurm_partitions': 'configure SLURM partitions using AudioCraftEnvironment get_slurm_partitions for team and global access', 'bind_solver_config': 'bind the compression encodec_musicgen_32khz solver configuration to the experiment launcher', 'bind_dataset_config': 'bind the internal music 400k 32kHz dataset to the experiment launcher'}
```

