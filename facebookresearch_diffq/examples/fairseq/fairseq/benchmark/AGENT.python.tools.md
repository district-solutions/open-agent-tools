# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/benchmark/dummy_lm.py

Prompts

```
['create a DummyLMConfig dataclass with dict_size, dataset_size, and tokens_per_sample settings for benchmarking', 'build a DummyLMTask that generates synthetic language model data with a configurable dictionary and sequence length', 'run the DummyLMTask load_dataset method to create a DummyDataset for a given split like train or valid', 'create a DummyDataset that returns identical batches for benchmarking fairseq language model inference performance', 'review the DummyLMTask source_dictionary and target_dictionary properties that return the shared synthetic dictionary', 'build a dummy masked language model task with configurable dictionary size and tokens per sample', 'run the setup_task class method to initialize a DummyMaskedLMTask with a generated dictionary', 'test loading a dummy dataset split with stacked source tokens and masked targets', 'review the add_args method to configure dict-size, dataset-size, and tokens-per-sample arguments', 'build a DummyModel language model with configurable num_layers and embed_dim arguments', 'build a DummyEncoder with embedding layers and transformer-style layer stacks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'test the DummyModel build_model class method to construct a model from args and task', 'review the DummyEncoder get_normalized_probs method that returns softmax or log_softmax logits', 'build a dummy machine translation task with configurable dictionary size, dataset size, and source/target sequence lengths', 'run the setup_task class method to initialize a DummyMTTask with a generated dictionary and padding', 'test the load_dataset method to generate synthetic source and target token batches for a given split', 'review the DummyDataset collater method that returns a pre-built batch dict with src_tokens, src_lengths, and target tensors']
```

Usage

```
{'create_DummyLMConfig': 'create a DummyLMConfig dataclass with dict_size, dataset_size, and tokens_per_sample settings for benchmarking', 'build_DummyLMTask': 'build a DummyLMTask that generates synthetic language model data with a configurable dictionary and sequence length', 'run_DummyLMTask_load_dataset': 'run the DummyLMTask load_dataset method to create a DummyDataset for a given split like train or valid', 'create_DummyDataset': 'create a DummyDataset that returns identical batches for benchmarking fairseq language model inference performance', 'review_DummyLMTask_properties': 'review the DummyLMTask source_dictionary and target_dictionary properties that return the shared synthetic dictionary'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/benchmark/dummy_masked_lm.py

Prompts

```
['create a DummyLMConfig dataclass with dict_size, dataset_size, and tokens_per_sample settings for benchmarking', 'build a DummyLMTask that generates synthetic language model data with a configurable dictionary and sequence length', 'run the DummyLMTask load_dataset method to create a DummyDataset for a given split like train or valid', 'create a DummyDataset that returns identical batches for benchmarking fairseq language model inference performance', 'review the DummyLMTask source_dictionary and target_dictionary properties that return the shared synthetic dictionary', 'build a dummy masked language model task with configurable dictionary size and tokens per sample', 'run the setup_task class method to initialize a DummyMaskedLMTask with a generated dictionary', 'test loading a dummy dataset split with stacked source tokens and masked targets', 'review the add_args method to configure dict-size, dataset-size, and tokens-per-sample arguments', 'build a DummyModel language model with configurable num_layers and embed_dim arguments', 'build a DummyEncoder with embedding layers and transformer-style layer stacks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'test the DummyModel build_model class method to construct a model from args and task', 'review the DummyEncoder get_normalized_probs method that returns softmax or log_softmax logits', 'build a dummy machine translation task with configurable dictionary size, dataset size, and source/target sequence lengths', 'run the setup_task class method to initialize a DummyMTTask with a generated dictionary and padding', 'test the load_dataset method to generate synthetic source and target token batches for a given split', 'review the DummyDataset collater method that returns a pre-built batch dict with src_tokens, src_lengths, and target tensors']
```

Usage

```
{'build_DummyMaskedLMTask': 'build a dummy masked language model task with configurable dictionary size and tokens per sample', 'create_DummyDataset': 'create a dummy FairseqDataset that returns a fixed batch for benchmarking masked LM training', 'run_setup_task': 'run the setup_task class method to initialize a DummyMaskedLMTask with a generated dictionary', 'test_load_dataset': 'test loading a dummy dataset split with stacked source tokens and masked targets', 'review_DummyMaskedLMTask_add_args': 'review the add_args method to configure dict-size, dataset-size, and tokens-per-sample arguments'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/benchmark/dummy_model.py

Prompts

```
['create a DummyLMConfig dataclass with dict_size, dataset_size, and tokens_per_sample settings for benchmarking', 'build a DummyLMTask that generates synthetic language model data with a configurable dictionary and sequence length', 'run the DummyLMTask load_dataset method to create a DummyDataset for a given split like train or valid', 'create a DummyDataset that returns identical batches for benchmarking fairseq language model inference performance', 'review the DummyLMTask source_dictionary and target_dictionary properties that return the shared synthetic dictionary', 'build a dummy masked language model task with configurable dictionary size and tokens per sample', 'run the setup_task class method to initialize a DummyMaskedLMTask with a generated dictionary', 'test loading a dummy dataset split with stacked source tokens and masked targets', 'review the add_args method to configure dict-size, dataset-size, and tokens-per-sample arguments', 'build a DummyModel language model with configurable num_layers and embed_dim arguments', 'build a DummyEncoder with embedding layers and transformer-style layer stacks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'test the DummyModel build_model class method to construct a model from args and task', 'review the DummyEncoder get_normalized_probs method that returns softmax or log_softmax logits', 'build a dummy machine translation task with configurable dictionary size, dataset size, and source/target sequence lengths', 'run the setup_task class method to initialize a DummyMTTask with a generated dictionary and padding', 'test the load_dataset method to generate synthetic source and target token batches for a given split', 'review the DummyDataset collater method that returns a pre-built batch dict with src_tokens, src_lengths, and target tensors']
```

Usage

```
{'build_DummyModel': 'build a DummyModel language model with configurable num_layers and embed_dim arguments', 'build_DummyEncoder': 'build a DummyEncoder with embedding layers and transformer-style layer stacks for benchmarking', 'run_DummyEncoder_forward': 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'test_DummyModel_build_model': 'test the DummyModel build_model class method to construct a model from args and task', 'review_DummyEncoder_get_normalized_probs': 'review the DummyEncoder get_normalized_probs method that returns softmax or log_softmax logits'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/benchmark/dummy_mt.py

Prompts

```
['create a DummyLMConfig dataclass with dict_size, dataset_size, and tokens_per_sample settings for benchmarking', 'build a DummyLMTask that generates synthetic language model data with a configurable dictionary and sequence length', 'run the DummyLMTask load_dataset method to create a DummyDataset for a given split like train or valid', 'create a DummyDataset that returns identical batches for benchmarking fairseq language model inference performance', 'review the DummyLMTask source_dictionary and target_dictionary properties that return the shared synthetic dictionary', 'build a dummy masked language model task with configurable dictionary size and tokens per sample', 'run the setup_task class method to initialize a DummyMaskedLMTask with a generated dictionary', 'test loading a dummy dataset split with stacked source tokens and masked targets', 'review the add_args method to configure dict-size, dataset-size, and tokens-per-sample arguments', 'build a DummyModel language model with configurable num_layers and embed_dim arguments', 'build a DummyEncoder with embedding layers and transformer-style layer stacks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'test the DummyModel build_model class method to construct a model from args and task', 'review the DummyEncoder get_normalized_probs method that returns softmax or log_softmax logits', 'build a dummy machine translation task with configurable dictionary size, dataset size, and source/target sequence lengths', 'run the setup_task class method to initialize a DummyMTTask with a generated dictionary and padding', 'test the load_dataset method to generate synthetic source and target token batches for a given split', 'review the DummyDataset collater method that returns a pre-built batch dict with src_tokens, src_lengths, and target tensors']
```

Usage

```
{'build_DummyMTTask': 'build a dummy machine translation task with configurable dictionary size, dataset size, and source/target sequence lengths', 'create_DummyDataset': 'create a FairseqDataset subclass that returns a fixed batch for benchmarking machine translation models', 'run_DummyMTTask_setup_task': 'run the setup_task class method to initialize a DummyMTTask with a generated dictionary and padding', 'test_DummyMTTask_load_dataset': 'test the load_dataset method to generate synthetic source and target token batches for a given split', 'review_DummyDataset_collater': 'review the DummyDataset collater method that returns a pre-built batch dict with src_tokens, src_lengths, and target tensors'}
```

