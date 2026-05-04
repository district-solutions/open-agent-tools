# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/cortexbench/mujoco_vc/src/mujoco_vc/gym_wrapper.py

Prompts

```
['build a MuJoCo gym environment with pixel observations and frozen embedding wrapper for a given env name', 'create a gym observation wrapper that renders RGB images from a MuJoCo environment using a specified camera', 'create a gym observation wrapper that extracts frozen vision embeddings from image observations with history buffering', 'test the get_proprioception function to extract proprioceptive state from a metaworld or adroit gym environment', 'review the FrozenEmbeddingWrapper observation method that fuses image embeddings into a flattened state vector', 'load a pretrained vision model by embedding name and return the model, embedding dimension, transforms, and metadata', 'fuse a list of numpy array embeddings into a single flattened array by concatenating and raveling', 'fuse a list of embeddings using FLARE by computing consecutive deltas and appending the last embedding', 'review the load_pretrained_model function to understand how it loads configs via OmegaConf and instantiates models via Hydra', 'refactor fuse_embeddings_flare to add support for additional tensor formats beyond numpy arrays and PyTorch tensors', 'run policy rollouts from initial states in a MuJoCo or DMC environment and return trajectory paths', 'test the rollout_from_init_states function with a GymEnv and policy to verify trajectory collection', 'refactor the toggle_tqdm function to support additional progress bar libraries beyond tqdm', 'review the rollout_from_init_states function for correct handling of DMC and MuJoCo physics backends', 'summarize the rollout_utils module functions for MuJoCo environment policy evaluation and trajectory collection']
```

Usage

```
{'build_env_constructor': 'build a MuJoCo gym environment with pixel observations and frozen embedding wrapper for a given env name', 'create_MuJoCoPixelObsWrapper': 'create a gym observation wrapper that renders RGB images from a MuJoCo environment using a specified camera', 'create_FrozenEmbeddingWrapper': 'create a gym observation wrapper that extracts frozen vision embeddings from image observations with history buffering', 'test_get_proprioception': 'test the get_proprioception function to extract proprioceptive state from a metaworld or adroit gym environment', 'review_FrozenEmbeddingWrapper_observation': 'review the FrozenEmbeddingWrapper observation method that fuses image embeddings into a flattened state vector'}
```

## File: facebookresearch_eai-vc/cortexbench/mujoco_vc/src/mujoco_vc/model_loading.py

Prompts

```
['build a MuJoCo gym environment with pixel observations and frozen embedding wrapper for a given env name', 'create a gym observation wrapper that renders RGB images from a MuJoCo environment using a specified camera', 'create a gym observation wrapper that extracts frozen vision embeddings from image observations with history buffering', 'test the get_proprioception function to extract proprioceptive state from a metaworld or adroit gym environment', 'review the FrozenEmbeddingWrapper observation method that fuses image embeddings into a flattened state vector', 'load a pretrained vision model by embedding name and return the model, embedding dimension, transforms, and metadata', 'fuse a list of numpy array embeddings into a single flattened array by concatenating and raveling', 'fuse a list of embeddings using FLARE by computing consecutive deltas and appending the last embedding', 'review the load_pretrained_model function to understand how it loads configs via OmegaConf and instantiates models via Hydra', 'refactor fuse_embeddings_flare to add support for additional tensor formats beyond numpy arrays and PyTorch tensors', 'run policy rollouts from initial states in a MuJoCo or DMC environment and return trajectory paths', 'test the rollout_from_init_states function with a GymEnv and policy to verify trajectory collection', 'refactor the toggle_tqdm function to support additional progress bar libraries beyond tqdm', 'review the rollout_from_init_states function for correct handling of DMC and MuJoCo physics backends', 'summarize the rollout_utils module functions for MuJoCo environment policy evaluation and trajectory collection']
```

Usage

```
{'load_pretrained_model': 'load a pretrained vision model by embedding name and return the model, embedding dimension, transforms, and metadata', 'fuse_embeddings_concat': 'fuse a list of numpy array embeddings into a single flattened array by concatenating and raveling', 'fuse_embeddings_flare': 'fuse a list of embeddings using FLARE by computing consecutive deltas and appending the last embedding', 'review_load_pretrained_model': 'review the load_pretrained_model function to understand how it loads configs via OmegaConf and instantiates models via Hydra', 'refactor_fuse_embeddings_flare': 'refactor fuse_embeddings_flare to add support for additional tensor formats beyond numpy arrays and PyTorch tensors'}
```

## File: facebookresearch_eai-vc/cortexbench/mujoco_vc/src/mujoco_vc/rollout_utils.py

Prompts

```
['build a MuJoCo gym environment with pixel observations and frozen embedding wrapper for a given env name', 'create a gym observation wrapper that renders RGB images from a MuJoCo environment using a specified camera', 'create a gym observation wrapper that extracts frozen vision embeddings from image observations with history buffering', 'test the get_proprioception function to extract proprioceptive state from a metaworld or adroit gym environment', 'review the FrozenEmbeddingWrapper observation method that fuses image embeddings into a flattened state vector', 'load a pretrained vision model by embedding name and return the model, embedding dimension, transforms, and metadata', 'fuse a list of numpy array embeddings into a single flattened array by concatenating and raveling', 'fuse a list of embeddings using FLARE by computing consecutive deltas and appending the last embedding', 'review the load_pretrained_model function to understand how it loads configs via OmegaConf and instantiates models via Hydra', 'refactor fuse_embeddings_flare to add support for additional tensor formats beyond numpy arrays and PyTorch tensors', 'run policy rollouts from initial states in a MuJoCo or DMC environment and return trajectory paths', 'test the rollout_from_init_states function with a GymEnv and policy to verify trajectory collection', 'refactor the toggle_tqdm function to support additional progress bar libraries beyond tqdm', 'review the rollout_from_init_states function for correct handling of DMC and MuJoCo physics backends', 'summarize the rollout_utils module functions for MuJoCo environment policy evaluation and trajectory collection']
```

Usage

```
{'run_rollout_from_init_states': 'run policy rollouts from initial states in a MuJoCo or DMC environment and return trajectory paths', 'test_rollout_from_init_states': 'test the rollout_from_init_states function with a GymEnv and policy to verify trajectory collection', 'refactor_toggle_tqdm': 'refactor the toggle_tqdm function to support additional progress bar libraries beyond tqdm', 'review_rollout_from_init_states': 'review the rollout_from_init_states function for correct handling of DMC and MuJoCo physics backends', 'summarize_rollout_utils': 'summarize the rollout_utils module functions for MuJoCo environment policy evaluation and trajectory collection'}
```

