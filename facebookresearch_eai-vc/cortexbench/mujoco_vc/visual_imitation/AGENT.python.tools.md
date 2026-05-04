# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/mujoco_vc/visual_imitation/hydra_launcher.py

Prompts

```
['run the hydra launcher script to start mjrl BC training with DMC_BC_config', 'configure and launch mjrl training jobs using hydra with the DMC_BC_config configuration', 'run the BC PVR training loop by executing the hydra launcher with spawn multiprocessing', 'save the hydra job configuration as job_config.json using OmegaConf structured config', 'set the MUJOCO_GL environment variable to egl for headless MuJoCo rendering', 'compute visual embeddings from trajectory images using a pretrained model and chunked inference', 'precompute fused embedding features with history window and optional proprioceptive concatenation for paths', 'create a PyTorch Dataset that yields feature-action pairs from precomputed frozen embeddings and trajectories', 'compute mean score and success percentage from rollout paths for dmc adroit or metaworld suites']
```

Usage

```
{'run_hydra_launcher': 'run the hydra launcher script to start mjrl BC training with DMC_BC_config', 'configure_jobs_with_hydra': 'configure and launch mjrl training jobs using hydra with the DMC_BC_config configuration', 'run_bc_pvr_train_loop': 'run the BC PVR training loop by executing the hydra launcher with spawn multiprocessing', 'save_job_config': 'save the hydra job configuration as job_config.json using OmegaConf structured config', 'set_mujoco_gl_backend': 'set the MUJOCO_GL environment variable to egl for headless MuJoCo rendering'}
```

## File: facebookresearch_eai-vc/cortexbench/mujoco_vc/visual_imitation/train_loop.py

Prompts

```
['run the hydra launcher script to start mjrl BC training with DMC_BC_config', 'configure and launch mjrl training jobs using hydra with the DMC_BC_config configuration', 'run the BC PVR training loop by executing the hydra launcher with spawn multiprocessing', 'save the hydra job configuration as job_config.json using OmegaConf structured config', 'set the MUJOCO_GL environment variable to egl for headless MuJoCo rendering', 'compute visual embeddings from trajectory images using a pretrained model and chunked inference', 'precompute fused embedding features with history window and optional proprioceptive concatenation for paths', 'create a PyTorch Dataset that yields feature-action pairs from precomputed frozen embeddings and trajectories', 'compute mean score and success percentage from rollout paths for dmc adroit or metaworld suites']
```

Usage

```
{'run_bc_pvr_train_loop': 'run the behavior cloning training loop with a config dict for visual imitation learning', 'compute_embeddings': 'compute visual embeddings from trajectory images using a pretrained model and chunked inference', 'precompute_features': 'precompute fused embedding features with history window and optional proprioceptive concatenation for paths', 'create_FrozenEmbeddingDataset': 'create a PyTorch Dataset that yields feature-action pairs from precomputed frozen embeddings and trajectories', 'compute_metrics_from_paths': 'compute mean score and success percentage from rollout paths for dmc adroit or metaworld suites'}
```

