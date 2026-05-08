# Agent Python Tools

- repo: facebookresearch/mega
- repo_uri: https://github.com/facebookresearch/mega

## File: facebookresearch_mega/fairseq/benchmark/dummy_lm.py

Prompts

```
['run the dummy_lm task to benchmark fairseq language model throughput with synthetic data', 'create a DummyLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'setup the dummy_lm task by calling setup_task to build a synthetic dictionary and task instance', 'load a dummy dataset split for train, valid, or test using DummyLMTask load_dataset method', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model inference speed', 'run the fairseq dummy_masked_lm task to benchmark masked language model performance with synthetic data', 'setup a DummyMaskedLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model throughput', 'load a dummy dataset split with stacked source tokens and target masks for benchmarking', 'review the DummyMaskedLMTask add_args method to configure dict-size, dataset-size, and tokens-per-sample', 'build a FairseqLanguageModel using DummyModel with a configurable number of layers and embedding dimension', 'build a DummyEncoder with embedding layers and transformer-like residual blocks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'review the DummyModel build_model classmethod that constructs a DummyEncoder from task dictionary and args', 'summarize the DummyEncoder get_normalized_probs method that returns softmax or log-softmax over logits', 'setup a DummyMTTask with a synthetic dictionary and dummy source-target token sequences for benchmarking', 'add task-specific CLI arguments for dict size, dataset size, and tokens per sample to an argparse parser', 'get the source and target dictionaries from a DummyMTTask instance for token indexing']
```

Usage

```
{'run_dummy_lm_benchmark': 'run the dummy_lm task to benchmark fairseq language model throughput with synthetic data', 'create_dummy_lm_task': 'create a DummyLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'setup_dummy_lm_task': 'setup the dummy_lm task by calling setup_task to build a synthetic dictionary and task instance', 'load_dummy_dataset': 'load a dummy dataset split for train, valid, or test using DummyLMTask load_dataset method', 'create_dummy_dataset': 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model inference speed'}
```

## File: facebookresearch_mega/fairseq/benchmark/dummy_masked_lm.py

Prompts

```
['run the dummy_lm task to benchmark fairseq language model throughput with synthetic data', 'create a DummyLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'setup the dummy_lm task by calling setup_task to build a synthetic dictionary and task instance', 'load a dummy dataset split for train, valid, or test using DummyLMTask load_dataset method', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model inference speed', 'run the fairseq dummy_masked_lm task to benchmark masked language model performance with synthetic data', 'setup a DummyMaskedLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model throughput', 'load a dummy dataset split with stacked source tokens and target masks for benchmarking', 'review the DummyMaskedLMTask add_args method to configure dict-size, dataset-size, and tokens-per-sample', 'build a FairseqLanguageModel using DummyModel with a configurable number of layers and embedding dimension', 'build a DummyEncoder with embedding layers and transformer-like residual blocks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'review the DummyModel build_model classmethod that constructs a DummyEncoder from task dictionary and args', 'summarize the DummyEncoder get_normalized_probs method that returns softmax or log-softmax over logits', 'setup a DummyMTTask with a synthetic dictionary and dummy source-target token sequences for benchmarking', 'add task-specific CLI arguments for dict size, dataset size, and tokens per sample to an argparse parser', 'get the source and target dictionaries from a DummyMTTask instance for token indexing']
```

Usage

```
{'run_dummy_masked_lm_task': 'run the fairseq dummy_masked_lm task to benchmark masked language model performance with synthetic data', 'setup_DummyMaskedLMTask': 'setup a DummyMaskedLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'create_DummyDataset': 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model throughput', 'load_dataset_DummyMaskedLMTask': 'load a dummy dataset split with stacked source tokens and target masks for benchmarking', 'review_DummyMaskedLMTask_add_args': 'review the DummyMaskedLMTask add_args method to configure dict-size, dataset-size, and tokens-per-sample'}
```

## File: facebookresearch_mega/fairseq/benchmark/dummy_model.py

Prompts

```
['run the dummy_lm task to benchmark fairseq language model throughput with synthetic data', 'create a DummyLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'setup the dummy_lm task by calling setup_task to build a synthetic dictionary and task instance', 'load a dummy dataset split for train, valid, or test using DummyLMTask load_dataset method', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model inference speed', 'run the fairseq dummy_masked_lm task to benchmark masked language model performance with synthetic data', 'setup a DummyMaskedLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model throughput', 'load a dummy dataset split with stacked source tokens and target masks for benchmarking', 'review the DummyMaskedLMTask add_args method to configure dict-size, dataset-size, and tokens-per-sample', 'build a FairseqLanguageModel using DummyModel with a configurable number of layers and embedding dimension', 'build a DummyEncoder with embedding layers and transformer-like residual blocks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'review the DummyModel build_model classmethod that constructs a DummyEncoder from task dictionary and args', 'summarize the DummyEncoder get_normalized_probs method that returns softmax or log-softmax over logits', 'setup a DummyMTTask with a synthetic dictionary and dummy source-target token sequences for benchmarking', 'add task-specific CLI arguments for dict size, dataset size, and tokens per sample to an argparse parser', 'get the source and target dictionaries from a DummyMTTask instance for token indexing']
```

Usage

```
{'build_DummyModel': 'build a FairseqLanguageModel using DummyModel with a configurable number of layers and embedding dimension', 'build_DummyEncoder': 'build a DummyEncoder with embedding layers and transformer-like residual blocks for benchmarking', 'run_DummyEncoder_forward': 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'review_DummyModel_build_model': 'review the DummyModel build_model classmethod that constructs a DummyEncoder from task dictionary and args', 'summarize_DummyEncoder_get_normalized_probs': 'summarize the DummyEncoder get_normalized_probs method that returns softmax or log-softmax over logits'}
```

## File: facebookresearch_mega/fairseq/benchmark/dummy_mt.py

Prompts

```
['run the dummy_lm task to benchmark fairseq language model throughput with synthetic data', 'create a DummyLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'setup the dummy_lm task by calling setup_task to build a synthetic dictionary and task instance', 'load a dummy dataset split for train, valid, or test using DummyLMTask load_dataset method', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model inference speed', 'run the fairseq dummy_masked_lm task to benchmark masked language model performance with synthetic data', 'setup a DummyMaskedLMTask with a configurable dictionary size and tokens per sample for benchmarking', 'create a DummyDataset that returns a fixed batch for benchmarking fairseq model throughput', 'load a dummy dataset split with stacked source tokens and target masks for benchmarking', 'review the DummyMaskedLMTask add_args method to configure dict-size, dataset-size, and tokens-per-sample', 'build a FairseqLanguageModel using DummyModel with a configurable number of layers and embedding dimension', 'build a DummyEncoder with embedding layers and transformer-like residual blocks for benchmarking', 'run the DummyEncoder forward pass on token tensors with optional masked token filtering', 'review the DummyModel build_model classmethod that constructs a DummyEncoder from task dictionary and args', 'summarize the DummyEncoder get_normalized_probs method that returns softmax or log-softmax over logits', 'setup a DummyMTTask with a synthetic dictionary and dummy source-target token sequences for benchmarking', 'add task-specific CLI arguments for dict size, dataset size, and tokens per sample to an argparse parser', 'get the source and target dictionaries from a DummyMTTask instance for token indexing']
```

Usage

```
{'setup_dummy_mt_task': 'setup a DummyMTTask with a synthetic dictionary and dummy source-target token sequences for benchmarking', 'load_dummy_dataset': 'load a DummyDataset split with synthetic batches of source tokens and target tokens for machine translation benchmarking', 'add_dummy_mt_args': 'add task-specific CLI arguments for dict size, dataset size, and tokens per sample to an argparse parser', 'create_dummy_dataset': 'create a DummyDataset that returns a fixed batch on collation for fast machine translation benchmarking', 'get_dummy_mt_dictionaries': 'get the source and target dictionaries from a DummyMTTask instance for token indexing'}
```

