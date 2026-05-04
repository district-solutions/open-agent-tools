# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/audiocraft/grids/watermarking/_explorers.py

Prompts

```
['create a WatermarkingMbExplorer instance to configure grid metrics for multi-bit watermarking experiments', 'create a WatermarkingExplorer instance to configure grid metrics for standard watermarking experiments', 'review the WatermarkingMbExplorer stages method to see train, valid, and evaluate stages', 'review the WatermarkingExplorer get_grid_metrics method to see train, valid, and evaluate metric groups', 'summarize the eval_metrics class attribute to understand which metrics are tracked for watermarking experiments', 'run the dora grid watermarking.audioseal explorer to launch AudioSeal watermarking robustness experiments on SLURM', 'run the explorer function to launch an 8 GPU SLURM job array for watermark robustness solver', 'review the explorer function that configures SLURM partitions and binds watermark robustness solver settings', 'review the WatermarkingExplorer decorator that defines train, valid, and evaluate stages for watermarking experiments', 'review the AudioCraftEnvironment get_slurm_partitions method to retrieve team and global SLURM partition names', 'run the dora grid watermarking.kbits explorer to launch 16-bit multi-bit watermarking robustness experiments on SLURM', 'review the WatermarkingMbExplorer decorator that defines train, valid, and evaluate stages for multi-bit watermarking experiments', 'review the augmentation weights configuration that sets updownresample, speed, echo, noise, filter, and compression augmentation probabilities']
```

Usage

```
{'create_watermarking_mb_explorer': 'create a WatermarkingMbExplorer instance to configure grid metrics for multi-bit watermarking experiments', 'create_watermarking_explorer': 'create a WatermarkingExplorer instance to configure grid metrics for standard watermarking experiments', 'review_watermarkingmbexplorer_stages': 'review the WatermarkingMbExplorer stages method to see train, valid, and evaluate stages', 'review_watermarkingexplorer_get_grid_metrics': 'review the WatermarkingExplorer get_grid_metrics method to see train, valid, and evaluate metric groups', 'summarize_watermarking_eval_metrics': 'summarize the eval_metrics class attribute to understand which metrics are tracked for watermarking experiments'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/watermarking/audioseal.py

Prompts

```
['create a WatermarkingMbExplorer instance to configure grid metrics for multi-bit watermarking experiments', 'create a WatermarkingExplorer instance to configure grid metrics for standard watermarking experiments', 'review the WatermarkingMbExplorer stages method to see train, valid, and evaluate stages', 'review the WatermarkingExplorer get_grid_metrics method to see train, valid, and evaluate metric groups', 'summarize the eval_metrics class attribute to understand which metrics are tracked for watermarking experiments', 'run the dora grid watermarking.audioseal explorer to launch AudioSeal watermarking robustness experiments on SLURM', 'run the explorer function to launch an 8 GPU SLURM job array for watermark robustness solver', 'review the explorer function that configures SLURM partitions and binds watermark robustness solver settings', 'review the WatermarkingExplorer decorator that defines train, valid, and evaluate stages for watermarking experiments', 'review the AudioCraftEnvironment get_slurm_partitions method to retrieve team and global SLURM partition names', 'run the dora grid watermarking.kbits explorer to launch 16-bit multi-bit watermarking robustness experiments on SLURM', 'review the WatermarkingMbExplorer decorator that defines train, valid, and evaluate stages for multi-bit watermarking experiments', 'review the augmentation weights configuration that sets updownresample, speed, echo, noise, filter, and compression augmentation probabilities']
```

Usage

```
{'run_audioseal_grid': 'run the dora grid watermarking.audioseal explorer to launch AudioSeal watermarking robustness experiments on SLURM', 'run_explorer_function': 'run the explorer function to launch an 8 GPU SLURM job array for watermark robustness solver', 'review_explorer_function': 'review the explorer function that configures SLURM partitions and binds watermark robustness solver settings', 'review_watermarkingexplorer_decorator': 'review the WatermarkingExplorer decorator that defines train, valid, and evaluate stages for watermarking experiments', 'review_get_slurm_partitions': 'review the AudioCraftEnvironment get_slurm_partitions method to retrieve team and global SLURM partition names'}
```

## File: facebookresearch_audiocraft/audiocraft/grids/watermarking/kbits.py

Prompts

```
['create a WatermarkingMbExplorer instance to configure grid metrics for multi-bit watermarking experiments', 'create a WatermarkingExplorer instance to configure grid metrics for standard watermarking experiments', 'review the WatermarkingMbExplorer stages method to see train, valid, and evaluate stages', 'review the WatermarkingExplorer get_grid_metrics method to see train, valid, and evaluate metric groups', 'summarize the eval_metrics class attribute to understand which metrics are tracked for watermarking experiments', 'run the dora grid watermarking.audioseal explorer to launch AudioSeal watermarking robustness experiments on SLURM', 'run the explorer function to launch an 8 GPU SLURM job array for watermark robustness solver', 'review the explorer function that configures SLURM partitions and binds watermark robustness solver settings', 'review the WatermarkingExplorer decorator that defines train, valid, and evaluate stages for watermarking experiments', 'review the AudioCraftEnvironment get_slurm_partitions method to retrieve team and global SLURM partition names', 'run the dora grid watermarking.kbits explorer to launch 16-bit multi-bit watermarking robustness experiments on SLURM', 'review the WatermarkingMbExplorer decorator that defines train, valid, and evaluate stages for multi-bit watermarking experiments', 'review the augmentation weights configuration that sets updownresample, speed, echo, noise, filter, and compression augmentation probabilities']
```

Usage

```
{'run_kbits_grid': 'run the dora grid watermarking.kbits explorer to launch 16-bit multi-bit watermarking robustness experiments on SLURM', 'run_explorer_function': 'run the explorer function to launch an 8 GPU SLURM job array for 16-bit multi-bit watermarking solver', 'review_explorer_function': 'review the explorer function that configures SLURM partitions and binds 16-bit multi-bit watermark robustness solver settings', 'review_watermarkingmbexplorer_decorator': 'review the WatermarkingMbExplorer decorator that defines train, valid, and evaluate stages for multi-bit watermarking experiments', 'review_augmentation_weights': 'review the augmentation weights configuration that sets updownresample, speed, echo, noise, filter, and compression augmentation probabilities'}
```

