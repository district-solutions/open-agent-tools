# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/dataclass/configs.py

Prompts

```
['create a FairseqConfig dataclass instance with all sub-configs for fairseq training', 'build a CommonConfig dataclass to set logging, FP16, seed, and device options', 'configure a DistributedTrainingConfig dataclass for DDP backend, pipeline parallelism, and ZeRO sharding', 'setup a DatasetConfig dataclass to control batch size, max tokens, and validation subsets', 'customize a GenerationConfig dataclass to set beam size, sampling, length penalty, and constraints', 'create a StrEnum subclass that compares equal to its string value', 'create a ChoiceEnum from a list of string choices for validation', 'review the StrEnumMeta metaclass workaround for submitit pickling and hydra instance checks', 'use LOG_FORMAT_CHOICES to validate log format options like json or tqdm', 'use DDP_BACKEND_CHOICES to select a distributed data parallel backend like pytorch_ddp', 'initialize the Hydra ConfigStore with FairseqConfig and all its dataclass field defaults', 'add default dataclass values to a DictConfig for task, model, and registry fields', 'review the hydra_init function that stores FairseqConfig and field defaults in Hydra ConfigStore', 'review the add_defaults function that merges task, model, and registry dataclass defaults into a config', 'refactor add_defaults to support additional registry types beyond task, model, and REGISTRIES', 'build an argparse parser from a FairseqDataclass with optional prefix and default deletion', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq', 'parse a comma-separated string into a typed list of ints, floats, or strings', 'overwrite values in a DictConfig using a nested dictionary of overrides', 'merge a FairseqDataclass with an existing DictConfig and preserve the parent reference']
```

Usage

```
{'create_FairseqConfig': 'create a FairseqConfig dataclass instance with all sub-configs for fairseq training', 'build_CommonConfig': 'build a CommonConfig dataclass to set logging, FP16, seed, and device options', 'configure_DistributedTrainingConfig': 'configure a DistributedTrainingConfig dataclass for DDP backend, pipeline parallelism, and ZeRO sharding', 'setup_DatasetConfig': 'setup a DatasetConfig dataclass to control batch size, max tokens, and validation subsets', 'customize_GenerationConfig': 'customize a GenerationConfig dataclass to set beam size, sampling, length penalty, and constraints'}
```

## File: facebookresearch_fairseq/fairseq/dataclass/constants.py

Prompts

```
['create a FairseqConfig dataclass instance with all sub-configs for fairseq training', 'build a CommonConfig dataclass to set logging, FP16, seed, and device options', 'configure a DistributedTrainingConfig dataclass for DDP backend, pipeline parallelism, and ZeRO sharding', 'setup a DatasetConfig dataclass to control batch size, max tokens, and validation subsets', 'customize a GenerationConfig dataclass to set beam size, sampling, length penalty, and constraints', 'create a StrEnum subclass that compares equal to its string value', 'create a ChoiceEnum from a list of string choices for validation', 'review the StrEnumMeta metaclass workaround for submitit pickling and hydra instance checks', 'use LOG_FORMAT_CHOICES to validate log format options like json or tqdm', 'use DDP_BACKEND_CHOICES to select a distributed data parallel backend like pytorch_ddp', 'initialize the Hydra ConfigStore with FairseqConfig and all its dataclass field defaults', 'add default dataclass values to a DictConfig for task, model, and registry fields', 'review the hydra_init function that stores FairseqConfig and field defaults in Hydra ConfigStore', 'review the add_defaults function that merges task, model, and registry dataclass defaults into a config', 'refactor add_defaults to support additional registry types beyond task, model, and REGISTRIES', 'build an argparse parser from a FairseqDataclass with optional prefix and default deletion', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq', 'parse a comma-separated string into a typed list of ints, floats, or strings', 'overwrite values in a DictConfig using a nested dictionary of overrides', 'merge a FairseqDataclass with an existing DictConfig and preserve the parent reference']
```

Usage

```
{'create_StrEnum_subclass': 'create a StrEnum subclass that compares equal to its string value', 'create_choice_enum_from_list': 'create a ChoiceEnum from a list of string choices for validation', 'review_StrEnumMeta_workaround': 'review the StrEnumMeta metaclass workaround for submitit pickling and hydra instance checks', 'use_LOG_FORMAT_CHOICES': 'use LOG_FORMAT_CHOICES to validate log format options like json or tqdm', 'use_DDP_BACKEND_CHOICES': 'use DDP_BACKEND_CHOICES to select a distributed data parallel backend like pytorch_ddp'}
```

## File: facebookresearch_fairseq/fairseq/dataclass/initialize.py

Prompts

```
['create a FairseqConfig dataclass instance with all sub-configs for fairseq training', 'build a CommonConfig dataclass to set logging, FP16, seed, and device options', 'configure a DistributedTrainingConfig dataclass for DDP backend, pipeline parallelism, and ZeRO sharding', 'setup a DatasetConfig dataclass to control batch size, max tokens, and validation subsets', 'customize a GenerationConfig dataclass to set beam size, sampling, length penalty, and constraints', 'create a StrEnum subclass that compares equal to its string value', 'create a ChoiceEnum from a list of string choices for validation', 'review the StrEnumMeta metaclass workaround for submitit pickling and hydra instance checks', 'use LOG_FORMAT_CHOICES to validate log format options like json or tqdm', 'use DDP_BACKEND_CHOICES to select a distributed data parallel backend like pytorch_ddp', 'initialize the Hydra ConfigStore with FairseqConfig and all its dataclass field defaults', 'add default dataclass values to a DictConfig for task, model, and registry fields', 'review the hydra_init function that stores FairseqConfig and field defaults in Hydra ConfigStore', 'review the add_defaults function that merges task, model, and registry dataclass defaults into a config', 'refactor add_defaults to support additional registry types beyond task, model, and REGISTRIES', 'build an argparse parser from a FairseqDataclass with optional prefix and default deletion', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq', 'parse a comma-separated string into a typed list of ints, floats, or strings', 'overwrite values in a DictConfig using a nested dictionary of overrides', 'merge a FairseqDataclass with an existing DictConfig and preserve the parent reference']
```

Usage

```
{'init_hydra_config_store': 'initialize the Hydra ConfigStore with FairseqConfig and all its dataclass field defaults', 'add_defaults_to_cfg': 'add default dataclass values to a DictConfig for task, model, and registry fields', 'review_hydra_init': 'review the hydra_init function that stores FairseqConfig and field defaults in Hydra ConfigStore', 'review_add_defaults': 'review the add_defaults function that merges task, model, and registry dataclass defaults into a config', 'refactor_add_defaults': 'refactor add_defaults to support additional registry types beyond task, model, and REGISTRIES'}
```

## File: facebookresearch_fairseq/fairseq/dataclass/utils.py

Prompts

```
['create a FairseqConfig dataclass instance with all sub-configs for fairseq training', 'build a CommonConfig dataclass to set logging, FP16, seed, and device options', 'configure a DistributedTrainingConfig dataclass for DDP backend, pipeline parallelism, and ZeRO sharding', 'setup a DatasetConfig dataclass to control batch size, max tokens, and validation subsets', 'customize a GenerationConfig dataclass to set beam size, sampling, length penalty, and constraints', 'create a StrEnum subclass that compares equal to its string value', 'create a ChoiceEnum from a list of string choices for validation', 'review the StrEnumMeta metaclass workaround for submitit pickling and hydra instance checks', 'use LOG_FORMAT_CHOICES to validate log format options like json or tqdm', 'use DDP_BACKEND_CHOICES to select a distributed data parallel backend like pytorch_ddp', 'initialize the Hydra ConfigStore with FairseqConfig and all its dataclass field defaults', 'add default dataclass values to a DictConfig for task, model, and registry fields', 'review the hydra_init function that stores FairseqConfig and field defaults in Hydra ConfigStore', 'review the add_defaults function that merges task, model, and registry dataclass defaults into a config', 'refactor add_defaults to support additional registry types beyond task, model, and REGISTRIES', 'build an argparse parser from a FairseqDataclass with optional prefix and default deletion', 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq', 'parse a comma-separated string into a typed list of ints, floats, or strings', 'overwrite values in a DictConfig using a nested dictionary of overrides', 'merge a FairseqDataclass with an existing DictConfig and preserve the parent reference']
```

Usage

```
{'gen_parser_from_dataclass': 'build an argparse parser from a FairseqDataclass with optional prefix and default deletion', 'convert_namespace_to_omegaconf': 'convert a flat argparse Namespace into a structured Hydra DictConfig for fairseq', 'eval_str_list': 'parse a comma-separated string into a typed list of ints, floats, or strings', 'overwrite_args_by_name': 'overwrite values in a DictConfig using a nested dictionary of overrides', 'merge_with_parent': 'merge a FairseqDataclass with an existing DictConfig and preserve the parent reference'}
```

