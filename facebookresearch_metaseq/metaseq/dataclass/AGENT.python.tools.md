# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/dataclass/configs.py

Prompts

```
['create a MetaseqConfig dataclass with nested CommonConfig, DatasetConfig, and OptimizationConfig fields', 'build a DistributedTrainingConfig dataclass to set distributed_world_size, ddp_backend, and device_id', 'configure a CheckpointConfig dataclass to set save_dir, save_interval_updates, and keep_last_epochs', 'setup a GenerationConfig dataclass to configure beam size, max_len_b, and sampling temperature', 'customize a DatasetConfig dataclass to set max_tokens, batch_size, and train_subset', 'create a StrEnum from a list of string choices using the ChoiceEnum factory function', 'use the StrEnum class to define string-based enums with custom str eq repr and hash methods', 'use the AttentionVariants enum to select between default and xformers attention backends', 'configure the distributed data parallel backend using DDP_BACKEND_CHOICES with c10d fully_sharded or pytorch_ddp', 'configure the dataset implementation using DATASET_IMPL_CHOICES with raw lazy cached mmap or fasta options', 'run hydra_init to register MetaseqConfig and all its dataclass field defaults into Hydra ConfigStore', 'review hydra_init to understand how MetaseqConfig is registered with Hydra ConfigStore', 'test hydra_init to verify MetaseqConfig and its fields are stored in ConfigStore correctly', 'refactor hydra_init to use a custom config name instead of the default base_config', 'summarize hydra_init which registers MetaseqConfig and its dataclass fields into Hydra ConfigStore', 'convert a flat argparse Namespace to a structured OmegaConf DictConfig with Hydra overrides', 'generate argparse arguments from a MetaseqDataclass instance for CLI configuration parsing', 'generate Hydra override strings and delete lists from an argparse Namespace for config migration', 'overwrite config values in a DictConfig by matching keys from a dictionary of overrides', 'merge two MetaseqDataclass configs using OmegaConf while preserving parent references and struct mode']
```

Usage

```
{'create_metaseq_config': 'create a MetaseqConfig dataclass with nested CommonConfig, DatasetConfig, and OptimizationConfig fields', 'build_distributed_training_config': 'build a DistributedTrainingConfig dataclass to set distributed_world_size, ddp_backend, and device_id', 'configure_checkpoint_saving': 'configure a CheckpointConfig dataclass to set save_dir, save_interval_updates, and keep_last_epochs', 'setup_generation_config': 'setup a GenerationConfig dataclass to configure beam size, max_len_b, and sampling temperature', 'customize_dataset_config': 'customize a DatasetConfig dataclass to set max_tokens, batch_size, and train_subset'}
```

## File: facebookresearch_metaseq/metaseq/dataclass/constants.py

Prompts

```
['create a MetaseqConfig dataclass with nested CommonConfig, DatasetConfig, and OptimizationConfig fields', 'build a DistributedTrainingConfig dataclass to set distributed_world_size, ddp_backend, and device_id', 'configure a CheckpointConfig dataclass to set save_dir, save_interval_updates, and keep_last_epochs', 'setup a GenerationConfig dataclass to configure beam size, max_len_b, and sampling temperature', 'customize a DatasetConfig dataclass to set max_tokens, batch_size, and train_subset', 'create a StrEnum from a list of string choices using the ChoiceEnum factory function', 'use the StrEnum class to define string-based enums with custom str eq repr and hash methods', 'use the AttentionVariants enum to select between default and xformers attention backends', 'configure the distributed data parallel backend using DDP_BACKEND_CHOICES with c10d fully_sharded or pytorch_ddp', 'configure the dataset implementation using DATASET_IMPL_CHOICES with raw lazy cached mmap or fasta options', 'run hydra_init to register MetaseqConfig and all its dataclass field defaults into Hydra ConfigStore', 'review hydra_init to understand how MetaseqConfig is registered with Hydra ConfigStore', 'test hydra_init to verify MetaseqConfig and its fields are stored in ConfigStore correctly', 'refactor hydra_init to use a custom config name instead of the default base_config', 'summarize hydra_init which registers MetaseqConfig and its dataclass fields into Hydra ConfigStore', 'convert a flat argparse Namespace to a structured OmegaConf DictConfig with Hydra overrides', 'generate argparse arguments from a MetaseqDataclass instance for CLI configuration parsing', 'generate Hydra override strings and delete lists from an argparse Namespace for config migration', 'overwrite config values in a DictConfig by matching keys from a dictionary of overrides', 'merge two MetaseqDataclass configs using OmegaConf while preserving parent references and struct mode']
```

Usage

```
{'create_choice_enum': 'create a StrEnum from a list of string choices using the ChoiceEnum factory function', 'use_strenum_class': 'use the StrEnum class to define string-based enums with custom str eq repr and hash methods', 'use_attention_variants': 'use the AttentionVariants enum to select between default and xformers attention backends', 'configure_ddp_backend': 'configure the distributed data parallel backend using DDP_BACKEND_CHOICES with c10d fully_sharded or pytorch_ddp', 'configure_dataset_impl': 'configure the dataset implementation using DATASET_IMPL_CHOICES with raw lazy cached mmap or fasta options'}
```

## File: facebookresearch_metaseq/metaseq/dataclass/initialize.py

Prompts

```
['create a MetaseqConfig dataclass with nested CommonConfig, DatasetConfig, and OptimizationConfig fields', 'build a DistributedTrainingConfig dataclass to set distributed_world_size, ddp_backend, and device_id', 'configure a CheckpointConfig dataclass to set save_dir, save_interval_updates, and keep_last_epochs', 'setup a GenerationConfig dataclass to configure beam size, max_len_b, and sampling temperature', 'customize a DatasetConfig dataclass to set max_tokens, batch_size, and train_subset', 'create a StrEnum from a list of string choices using the ChoiceEnum factory function', 'use the StrEnum class to define string-based enums with custom str eq repr and hash methods', 'use the AttentionVariants enum to select between default and xformers attention backends', 'configure the distributed data parallel backend using DDP_BACKEND_CHOICES with c10d fully_sharded or pytorch_ddp', 'configure the dataset implementation using DATASET_IMPL_CHOICES with raw lazy cached mmap or fasta options', 'run hydra_init to register MetaseqConfig and all its dataclass field defaults into Hydra ConfigStore', 'review hydra_init to understand how MetaseqConfig is registered with Hydra ConfigStore', 'test hydra_init to verify MetaseqConfig and its fields are stored in ConfigStore correctly', 'refactor hydra_init to use a custom config name instead of the default base_config', 'summarize hydra_init which registers MetaseqConfig and its dataclass fields into Hydra ConfigStore', 'convert a flat argparse Namespace to a structured OmegaConf DictConfig with Hydra overrides', 'generate argparse arguments from a MetaseqDataclass instance for CLI configuration parsing', 'generate Hydra override strings and delete lists from an argparse Namespace for config migration', 'overwrite config values in a DictConfig by matching keys from a dictionary of overrides', 'merge two MetaseqDataclass configs using OmegaConf while preserving parent references and struct mode']
```

Usage

```
{'run_hydra_init': 'run hydra_init to register MetaseqConfig and all its dataclass field defaults into Hydra ConfigStore', 'review_hydra_init': 'review hydra_init to understand how MetaseqConfig is registered with Hydra ConfigStore', 'test_hydra_init': 'test hydra_init to verify MetaseqConfig and its fields are stored in ConfigStore correctly', 'refactor_hydra_init': 'refactor hydra_init to use a custom config name instead of the default base_config', 'summarize_hydra_init': 'summarize hydra_init which registers MetaseqConfig and its dataclass fields into Hydra ConfigStore'}
```

## File: facebookresearch_metaseq/metaseq/dataclass/utils.py

Prompts

```
['create a MetaseqConfig dataclass with nested CommonConfig, DatasetConfig, and OptimizationConfig fields', 'build a DistributedTrainingConfig dataclass to set distributed_world_size, ddp_backend, and device_id', 'configure a CheckpointConfig dataclass to set save_dir, save_interval_updates, and keep_last_epochs', 'setup a GenerationConfig dataclass to configure beam size, max_len_b, and sampling temperature', 'customize a DatasetConfig dataclass to set max_tokens, batch_size, and train_subset', 'create a StrEnum from a list of string choices using the ChoiceEnum factory function', 'use the StrEnum class to define string-based enums with custom str eq repr and hash methods', 'use the AttentionVariants enum to select between default and xformers attention backends', 'configure the distributed data parallel backend using DDP_BACKEND_CHOICES with c10d fully_sharded or pytorch_ddp', 'configure the dataset implementation using DATASET_IMPL_CHOICES with raw lazy cached mmap or fasta options', 'run hydra_init to register MetaseqConfig and all its dataclass field defaults into Hydra ConfigStore', 'review hydra_init to understand how MetaseqConfig is registered with Hydra ConfigStore', 'test hydra_init to verify MetaseqConfig and its fields are stored in ConfigStore correctly', 'refactor hydra_init to use a custom config name instead of the default base_config', 'summarize hydra_init which registers MetaseqConfig and its dataclass fields into Hydra ConfigStore', 'convert a flat argparse Namespace to a structured OmegaConf DictConfig with Hydra overrides', 'generate argparse arguments from a MetaseqDataclass instance for CLI configuration parsing', 'generate Hydra override strings and delete lists from an argparse Namespace for config migration', 'overwrite config values in a DictConfig by matching keys from a dictionary of overrides', 'merge two MetaseqDataclass configs using OmegaConf while preserving parent references and struct mode']
```

Usage

```
{'convert_namespace_to_omegaconf': 'convert a flat argparse Namespace to a structured OmegaConf DictConfig with Hydra overrides', 'gen_parser_from_dataclass': 'generate argparse arguments from a MetaseqDataclass instance for CLI configuration parsing', 'override_module_args': 'generate Hydra override strings and delete lists from an argparse Namespace for config migration', 'overwrite_args_by_name': 'overwrite config values in a DictConfig by matching keys from a dictionary of overrides', 'merge_with_parent': 'merge two MetaseqDataclass configs using OmegaConf while preserving parent references and struct mode'}
```

