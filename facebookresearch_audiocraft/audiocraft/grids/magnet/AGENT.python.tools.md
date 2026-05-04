# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/audiocraft/grids/magnet/audio_magnet_16khz.py

Prompts

```
['run the MAGNET 16kHz audio grid explorer to launch SLURM training jobs for small and medium models', 'configure SLURM partitions using AudioCraftEnvironment get_slurm_partitions with team and global partition types', 'bind the magnet audio_magnet_16khz solver and internal sounds dataset to the Dora launcher', 'launch a 300M parameter MAGNET model training job on 32 GPUs using the explorer job array', 'launch a 1.5B parameter MAGNET model training job on 64 GPUs with FSDP enabled via the explorer', 'run objective metric evaluation for pretrained audio-MAGNeT models on the AudioCaps 16kHz dataset', 'run the Dora grid explorer to launch SLURM job arrays for audio-MAGNeT model evaluation', 'evaluate the small 300M audio-MAGNeT pretrained model using objective metrics with batch size 128', 'evaluate the medium 1.5B audio-MAGNeT pretrained model with FSDP enabled and batch size 128', 'regenerate the evaluation grid by setting REGEN=1 and running dora grid magnet.audio_magnet_pretrained_16khz_eval', 'run the MAGNET 32kHz training grid explorer to launch SLURM jobs for small and medium models', 'configure a 300M MAGNET model training job with 32 GPUs and 30 or 10 second segments', 'configure a 1.5B MAGNET model training job with 64 GPUs, FSDP, and AdamW optimizer', 'get SLURM cluster partitions for team and global resources via AudioCraftEnvironment.get_slurm_partitions', 'customize dataset segment duration to 10 seconds with batch size 576 and decoding steps', 'run objective metric evaluation for a pretrained MAGNeT model on the MusicCaps 32kHz dataset', 'run evaluation on the 10-second MAGNeT small or medium pretrained models with segment duration config', 'run evaluation on the 30-second MAGNeT small or medium pretrained models with FSDP enabled', 'review the eval function that binds launcher options for dataset, solver, and FAD metric configuration']
```

Usage

```
{'run_audio_magnet_16khz_explorer': 'run the MAGNET 16kHz audio grid explorer to launch SLURM training jobs for small and medium models', 'configure_slurm_partitions': 'configure SLURM partitions using AudioCraftEnvironment get_slurm_partitions with team and global partition types', 'bind_magnet_solver': 'bind the magnet audio_magnet_16khz solver and internal sounds dataset to the Dora launcher', 'launch_small_model_training': 'launch a 300M parameter MAGNET model training job on 32 GPUs using the explorer job array', 'launch_medium_model_training': 'launch a 1.5B parameter MAGNET model training job on 64 GPUs with FSDP enabled via the explorer'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/magnet/audio_magnet_pretrained_16khz_eval.py

Prompts

```
['run the MAGNET 16kHz audio grid explorer to launch SLURM training jobs for small and medium models', 'configure SLURM partitions using AudioCraftEnvironment get_slurm_partitions with team and global partition types', 'bind the magnet audio_magnet_16khz solver and internal sounds dataset to the Dora launcher', 'launch a 300M parameter MAGNET model training job on 32 GPUs using the explorer job array', 'launch a 1.5B parameter MAGNET model training job on 64 GPUs with FSDP enabled via the explorer', 'run objective metric evaluation for pretrained audio-MAGNeT models on the AudioCaps 16kHz dataset', 'run the Dora grid explorer to launch SLURM job arrays for audio-MAGNeT model evaluation', 'evaluate the small 300M audio-MAGNeT pretrained model using objective metrics with batch size 128', 'evaluate the medium 1.5B audio-MAGNeT pretrained model with FSDP enabled and batch size 128', 'regenerate the evaluation grid by setting REGEN=1 and running dora grid magnet.audio_magnet_pretrained_16khz_eval', 'run the MAGNET 32kHz training grid explorer to launch SLURM jobs for small and medium models', 'configure a 300M MAGNET model training job with 32 GPUs and 30 or 10 second segments', 'configure a 1.5B MAGNET model training job with 64 GPUs, FSDP, and AdamW optimizer', 'get SLURM cluster partitions for team and global resources via AudioCraftEnvironment.get_slurm_partitions', 'customize dataset segment duration to 10 seconds with batch size 576 and decoding steps', 'run objective metric evaluation for a pretrained MAGNeT model on the MusicCaps 32kHz dataset', 'run evaluation on the 10-second MAGNeT small or medium pretrained models with segment duration config', 'run evaluation on the 30-second MAGNeT small or medium pretrained models with FSDP enabled', 'review the eval function that binds launcher options for dataset, solver, and FAD metric configuration']
```

Usage

```
{'run_audio_magnet_eval': 'run objective metric evaluation for pretrained audio-MAGNeT models on the AudioCaps 16kHz dataset', 'run_explorer_grid': 'run the Dora grid explorer to launch SLURM job arrays for audio-MAGNeT model evaluation', 'eval_small_model': 'evaluate the small 300M audio-MAGNeT pretrained model using objective metrics with batch size 128', 'eval_medium_model': 'evaluate the medium 1.5B audio-MAGNeT pretrained model with FSDP enabled and batch size 128', 'regen_eval_grid': 'regenerate the evaluation grid by setting REGEN=1 and running dora grid magnet.audio_magnet_pretrained_16khz_eval'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/magnet/magnet_32khz.py

Prompts

```
['run the MAGNET 16kHz audio grid explorer to launch SLURM training jobs for small and medium models', 'configure SLURM partitions using AudioCraftEnvironment get_slurm_partitions with team and global partition types', 'bind the magnet audio_magnet_16khz solver and internal sounds dataset to the Dora launcher', 'launch a 300M parameter MAGNET model training job on 32 GPUs using the explorer job array', 'launch a 1.5B parameter MAGNET model training job on 64 GPUs with FSDP enabled via the explorer', 'run objective metric evaluation for pretrained audio-MAGNeT models on the AudioCaps 16kHz dataset', 'run the Dora grid explorer to launch SLURM job arrays for audio-MAGNeT model evaluation', 'evaluate the small 300M audio-MAGNeT pretrained model using objective metrics with batch size 128', 'evaluate the medium 1.5B audio-MAGNeT pretrained model with FSDP enabled and batch size 128', 'regenerate the evaluation grid by setting REGEN=1 and running dora grid magnet.audio_magnet_pretrained_16khz_eval', 'run the MAGNET 32kHz training grid explorer to launch SLURM jobs for small and medium models', 'configure a 300M MAGNET model training job with 32 GPUs and 30 or 10 second segments', 'configure a 1.5B MAGNET model training job with 64 GPUs, FSDP, and AdamW optimizer', 'get SLURM cluster partitions for team and global resources via AudioCraftEnvironment.get_slurm_partitions', 'customize dataset segment duration to 10 seconds with batch size 576 and decoding steps', 'run objective metric evaluation for a pretrained MAGNeT model on the MusicCaps 32kHz dataset', 'run evaluation on the 10-second MAGNeT small or medium pretrained models with segment duration config', 'run evaluation on the 30-second MAGNeT small or medium pretrained models with FSDP enabled', 'review the eval function that binds launcher options for dataset, solver, and FAD metric configuration']
```

Usage

```
{'run_magnet_32khz_explorer': 'run the MAGNET 32kHz training grid explorer to launch SLURM jobs for small and medium models', 'configure_magnet_small_model': 'configure a 300M MAGNET model training job with 32 GPUs and 30 or 10 second segments', 'configure_magnet_medium_model': 'configure a 1.5B MAGNET model training job with 64 GPUs, FSDP, and AdamW optimizer', 'get_slurm_partitions': 'get SLURM cluster partitions for team and global resources via AudioCraftEnvironment.get_slurm_partitions', 'customize_segment_duration': 'customize dataset segment duration to 10 seconds with batch size 576 and decoding steps'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/magnet/magnet_pretrained_32khz_eval.py

Prompts

```
['run the MAGNET 16kHz audio grid explorer to launch SLURM training jobs for small and medium models', 'configure SLURM partitions using AudioCraftEnvironment get_slurm_partitions with team and global partition types', 'bind the magnet audio_magnet_16khz solver and internal sounds dataset to the Dora launcher', 'launch a 300M parameter MAGNET model training job on 32 GPUs using the explorer job array', 'launch a 1.5B parameter MAGNET model training job on 64 GPUs with FSDP enabled via the explorer', 'run objective metric evaluation for pretrained audio-MAGNeT models on the AudioCaps 16kHz dataset', 'run the Dora grid explorer to launch SLURM job arrays for audio-MAGNeT model evaluation', 'evaluate the small 300M audio-MAGNeT pretrained model using objective metrics with batch size 128', 'evaluate the medium 1.5B audio-MAGNeT pretrained model with FSDP enabled and batch size 128', 'regenerate the evaluation grid by setting REGEN=1 and running dora grid magnet.audio_magnet_pretrained_16khz_eval', 'run the MAGNET 32kHz training grid explorer to launch SLURM jobs for small and medium models', 'configure a 300M MAGNET model training job with 32 GPUs and 30 or 10 second segments', 'configure a 1.5B MAGNET model training job with 64 GPUs, FSDP, and AdamW optimizer', 'get SLURM cluster partitions for team and global resources via AudioCraftEnvironment.get_slurm_partitions', 'customize dataset segment duration to 10 seconds with batch size 576 and decoding steps', 'run objective metric evaluation for a pretrained MAGNeT model on the MusicCaps 32kHz dataset', 'run evaluation on the 10-second MAGNeT small or medium pretrained models with segment duration config', 'run evaluation on the 30-second MAGNeT small or medium pretrained models with FSDP enabled', 'review the eval function that binds launcher options for dataset, solver, and FAD metric configuration']
```

Usage

```
{'run_MAGNeT_evaluation': 'run objective metric evaluation for a pretrained MAGNeT model on the MusicCaps 32kHz dataset', 'run_explorer_grid': 'run the Dora grid explorer to launch SLURM jobs evaluating multiple MAGNeT pretrained models', 'run_10sec_model_eval': 'run evaluation on the 10-second MAGNeT small or medium pretrained models with segment duration config', 'run_30sec_model_eval': 'run evaluation on the 30-second MAGNeT small or medium pretrained models with FSDP enabled', 'review_eval_function': 'review the eval function that binds launcher options for dataset, solver, and FAD metric configuration'}
```

