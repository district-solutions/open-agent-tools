# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/dataclass/configs.py

Prompts

```
['create a FairseqConfig instance with nested CommonConfig, DatasetConfig, and OptimizationConfig sub-configs', 'inspect all attributes of a FairseqDataclass subclass using the _get_all_attributes method', 'get the help text, choices, or argparse alias for a dataclass field using _get_meta', 'configure beam search, sampling, and length penalty parameters via GenerationConfig dataclass', 'configure DDP backend, pipeline parallelism, and ZeRO sharding via DistributedTrainingConfig dataclass', 'create a StrEnum subclass that compares its members directly to string values', 'use StrEnumMeta as a metaclass to fix submitit pickling and hydra isinstance checks', 'call ChoiceEnum with a list of strings to generate a StrEnum class enforcing those choices', 'use DDP_BACKEND_CHOICES to validate distributed data parallel backend options like pytorch_ddp or fully_sharded', 'use DATASET_IMPL_CHOICES to validate dataset implementation options like cached, mmap, or lazy', 'initialize the Hydra ConfigStore with FairseqConfig and register all dataclass fields as config nodes', "add default values from dataclass registries to a DictConfig that Hydra doesn't know about", "review the hydra_init function to understand how FairseqConfig is registered with Hydra's ConfigStore", 'review the add_defaults function to understand how task, model, and registry dataclasses are merged into config', 'summarize the initialize module which provides Hydra initialization and config default merging for Fairseq', 'build an argparse ArgumentParser from a FairseqDataclass instance with typed arguments and defaults', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq configuration', 'generate Hydra override strings and deletes from an argparse Namespace for fairseq modules', 'recursively overwrite DictConfig values with a dictionary of overrides for fairseq configuration', 'merge a FairseqDataclass with an existing DictConfig and remove keys not in the dataclass']
```

Usage

```
{'create_fairseq_config': 'create a FairseqConfig instance with nested CommonConfig, DatasetConfig, and OptimizationConfig sub-configs', 'inspect_fairseqdataclass_attributes': 'inspect all attributes of a FairseqDataclass subclass using the _get_all_attributes method', 'get_field_metadata': 'get the help text, choices, or argparse alias for a dataclass field using _get_meta', 'configure_generation_params': 'configure beam search, sampling, and length penalty parameters via GenerationConfig dataclass', 'configure_distributed_training': 'configure DDP backend, pipeline parallelism, and ZeRO sharding via DistributedTrainingConfig dataclass'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/dataclass/constants.py

Prompts

```
['create a FairseqConfig instance with nested CommonConfig, DatasetConfig, and OptimizationConfig sub-configs', 'inspect all attributes of a FairseqDataclass subclass using the _get_all_attributes method', 'get the help text, choices, or argparse alias for a dataclass field using _get_meta', 'configure beam search, sampling, and length penalty parameters via GenerationConfig dataclass', 'configure DDP backend, pipeline parallelism, and ZeRO sharding via DistributedTrainingConfig dataclass', 'create a StrEnum subclass that compares its members directly to string values', 'use StrEnumMeta as a metaclass to fix submitit pickling and hydra isinstance checks', 'call ChoiceEnum with a list of strings to generate a StrEnum class enforcing those choices', 'use DDP_BACKEND_CHOICES to validate distributed data parallel backend options like pytorch_ddp or fully_sharded', 'use DATASET_IMPL_CHOICES to validate dataset implementation options like cached, mmap, or lazy', 'initialize the Hydra ConfigStore with FairseqConfig and register all dataclass fields as config nodes', "add default values from dataclass registries to a DictConfig that Hydra doesn't know about", "review the hydra_init function to understand how FairseqConfig is registered with Hydra's ConfigStore", 'review the add_defaults function to understand how task, model, and registry dataclasses are merged into config', 'summarize the initialize module which provides Hydra initialization and config default merging for Fairseq', 'build an argparse ArgumentParser from a FairseqDataclass instance with typed arguments and defaults', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq configuration', 'generate Hydra override strings and deletes from an argparse Namespace for fairseq modules', 'recursively overwrite DictConfig values with a dictionary of overrides for fairseq configuration', 'merge a FairseqDataclass with an existing DictConfig and remove keys not in the dataclass']
```

Usage

```
{'create_StrEnum_subclass': 'create a StrEnum subclass that compares its members directly to string values', 'use_StrEnumMeta_workaround': 'use StrEnumMeta as a metaclass to fix submitit pickling and hydra isinstance checks', 'call_ChoiceEnum_factory': 'call ChoiceEnum with a list of strings to generate a StrEnum class enforcing those choices', 'use_DDP_BACKEND_CHOICES': 'use DDP_BACKEND_CHOICES to validate distributed data parallel backend options like pytorch_ddp or fully_sharded', 'use_DATASET_IMPL_CHOICES': 'use DATASET_IMPL_CHOICES to validate dataset implementation options like cached, mmap, or lazy'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/dataclass/initialize.py

Prompts

```
['create a FairseqConfig instance with nested CommonConfig, DatasetConfig, and OptimizationConfig sub-configs', 'inspect all attributes of a FairseqDataclass subclass using the _get_all_attributes method', 'get the help text, choices, or argparse alias for a dataclass field using _get_meta', 'configure beam search, sampling, and length penalty parameters via GenerationConfig dataclass', 'configure DDP backend, pipeline parallelism, and ZeRO sharding via DistributedTrainingConfig dataclass', 'create a StrEnum subclass that compares its members directly to string values', 'use StrEnumMeta as a metaclass to fix submitit pickling and hydra isinstance checks', 'call ChoiceEnum with a list of strings to generate a StrEnum class enforcing those choices', 'use DDP_BACKEND_CHOICES to validate distributed data parallel backend options like pytorch_ddp or fully_sharded', 'use DATASET_IMPL_CHOICES to validate dataset implementation options like cached, mmap, or lazy', 'initialize the Hydra ConfigStore with FairseqConfig and register all dataclass fields as config nodes', "add default values from dataclass registries to a DictConfig that Hydra doesn't know about", "review the hydra_init function to understand how FairseqConfig is registered with Hydra's ConfigStore", 'review the add_defaults function to understand how task, model, and registry dataclasses are merged into config', 'summarize the initialize module which provides Hydra initialization and config default merging for Fairseq', 'build an argparse ArgumentParser from a FairseqDataclass instance with typed arguments and defaults', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq configuration', 'generate Hydra override strings and deletes from an argparse Namespace for fairseq modules', 'recursively overwrite DictConfig values with a dictionary of overrides for fairseq configuration', 'merge a FairseqDataclass with an existing DictConfig and remove keys not in the dataclass']
```

Usage

```
{'init_hydra_config_store': 'initialize the Hydra ConfigStore with FairseqConfig and register all dataclass fields as config nodes', 'add_defaults_to_cfg': "add default values from dataclass registries to a DictConfig that Hydra doesn't know about", 'review_hydra_init': "review the hydra_init function to understand how FairseqConfig is registered with Hydra's ConfigStore", 'review_add_defaults': 'review the add_defaults function to understand how task, model, and registry dataclasses are merged into config', 'summarize_initialize_module': 'summarize the initialize module which provides Hydra initialization and config default merging for Fairseq'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/dataclass/utils.py

Prompts

```
['create a FairseqConfig instance with nested CommonConfig, DatasetConfig, and OptimizationConfig sub-configs', 'inspect all attributes of a FairseqDataclass subclass using the _get_all_attributes method', 'get the help text, choices, or argparse alias for a dataclass field using _get_meta', 'configure beam search, sampling, and length penalty parameters via GenerationConfig dataclass', 'configure DDP backend, pipeline parallelism, and ZeRO sharding via DistributedTrainingConfig dataclass', 'create a StrEnum subclass that compares its members directly to string values', 'use StrEnumMeta as a metaclass to fix submitit pickling and hydra isinstance checks', 'call ChoiceEnum with a list of strings to generate a StrEnum class enforcing those choices', 'use DDP_BACKEND_CHOICES to validate distributed data parallel backend options like pytorch_ddp or fully_sharded', 'use DATASET_IMPL_CHOICES to validate dataset implementation options like cached, mmap, or lazy', 'initialize the Hydra ConfigStore with FairseqConfig and register all dataclass fields as config nodes', "add default values from dataclass registries to a DictConfig that Hydra doesn't know about", "review the hydra_init function to understand how FairseqConfig is registered with Hydra's ConfigStore", 'review the add_defaults function to understand how task, model, and registry dataclasses are merged into config', 'summarize the initialize module which provides Hydra initialization and config default merging for Fairseq', 'build an argparse ArgumentParser from a FairseqDataclass instance with typed arguments and defaults', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq configuration', 'generate Hydra override strings and deletes from an argparse Namespace for fairseq modules', 'recursively overwrite DictConfig values with a dictionary of overrides for fairseq configuration', 'merge a FairseqDataclass with an existing DictConfig and remove keys not in the dataclass']
```

Usage

```
{'gen_parser_from_dataclass': 'build an argparse ArgumentParser from a FairseqDataclass instance with typed arguments and defaults', 'convert_namespace_to_omegaconf': 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq configuration', 'override_module_args': 'generate Hydra override strings and deletes from an argparse Namespace for fairseq modules', 'overwrite_args_by_name': 'recursively overwrite DictConfig values with a dictionary of overrides for fairseq configuration', 'merge_with_parent': 'merge a FairseqDataclass with an existing DictConfig and remove keys not in the dataclass'}
```

