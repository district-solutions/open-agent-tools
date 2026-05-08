# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/units/mlip_unit/api/inference.py

Prompts

```
['create an InferenceSettings dataclass with tf32, activation checkpointing, merge mole, and compile flags for MLIP inference', 'create an MLIPInferenceCheckpoint dataclass to hold model config, state dict, ema state dict, and tasks config', 'use the inference_settings_default function to get general-purpose InferenceSettings for most systems and models', 'use the inference_settings_turbo function to get optimized InferenceSettings for long simulations with constant composition', 'use guess_inference_settings to resolve a string name or InferenceSettings object into the correct settings instance']
```

Usage

```
{'create_InferenceSettings': 'create an InferenceSettings dataclass with tf32, activation checkpointing, merge mole, and compile flags for MLIP inference', 'create_MLIPInferenceCheckpoint': 'create an MLIPInferenceCheckpoint dataclass to hold model config, state dict, ema state dict, and tasks config', 'use_inference_settings_default': 'use the inference_settings_default function to get general-purpose InferenceSettings for most systems and models', 'use_inference_settings_turbo': 'use the inference_settings_turbo function to get optimized InferenceSettings for long simulations with constant composition', 'use_guess_inference_settings': 'use guess_inference_settings to resolve a string name or InferenceSettings object into the correct settings instance'}
```

