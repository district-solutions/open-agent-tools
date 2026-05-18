# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/metaseq/benchmark/dummy_lm.py

Prompts

```
['create a DummyLMConfig dataclass to configure dictionary size, dataset size, and tokens per sample for a dummy language model task', 'build a DummyLMTask that generates synthetic source and target token sequences using a configurable dictionary and sequence length', 'run the load_dataset method on DummyLMTask to create a DummyDataset for a given split like train or valid', 'create a DummyDataset that returns a fixed batch of dummy tokens and supports standard dataset interface methods', 'review the DummyLMTask source and target dictionary properties that return the shared synthetic word dictionary', 'run the metaseq generator benchmark CLI to measure latency and peak memory for a loaded model', 'run the main function to instantiate a generator interface, warm up, and benchmark generation performance', 'run the benchmark function to measure generation latency and peak GPU memory across multiple repeats', 'run the profile function to collect CPU and CUDA traces with tensorboard output for generation', 'review the benchmark function that uses CUDA events to time generator.generate calls and report latency']
```

Usage

```
{'create_DummyLMConfig': 'create a DummyLMConfig dataclass to configure dictionary size, dataset size, and tokens per sample for a dummy language model task', 'build_DummyLMTask': 'build a DummyLMTask that generates synthetic source and target token sequences using a configurable dictionary and sequence length', 'run_DummyLMTask_load_dataset': 'run the load_dataset method on DummyLMTask to create a DummyDataset for a given split like train or valid', 'create_DummyDataset': 'create a DummyDataset that returns a fixed batch of dummy tokens and supports standard dataset interface methods', 'review_DummyLMTask_dictionary': 'review the DummyLMTask source and target dictionary properties that return the shared synthetic word dictionary'}
```

## File: facebookresearch_metaseq/metaseq/benchmark/generator.py

Prompts

```
['create a DummyLMConfig dataclass to configure dictionary size, dataset size, and tokens per sample for a dummy language model task', 'build a DummyLMTask that generates synthetic source and target token sequences using a configurable dictionary and sequence length', 'run the load_dataset method on DummyLMTask to create a DummyDataset for a given split like train or valid', 'create a DummyDataset that returns a fixed batch of dummy tokens and supports standard dataset interface methods', 'review the DummyLMTask source and target dictionary properties that return the shared synthetic word dictionary', 'run the metaseq generator benchmark CLI to measure latency and peak memory for a loaded model', 'run the main function to instantiate a generator interface, warm up, and benchmark generation performance', 'run the benchmark function to measure generation latency and peak GPU memory across multiple repeats', 'run the profile function to collect CPU and CUDA traces with tensorboard output for generation', 'review the benchmark function that uses CUDA events to time generator.generate calls and report latency']
```

Usage

```
{'run_generator_benchmark': 'run the metaseq generator benchmark CLI to measure latency and peak memory for a loaded model', 'run_main': 'run the main function to instantiate a generator interface, warm up, and benchmark generation performance', 'run_benchmark': 'run the benchmark function to measure generation latency and peak GPU memory across multiple repeats', 'run_profile': 'run the profile function to collect CPU and CUDA traces with tensorboard output for generation', 'review_benchmark': 'review the benchmark function that uses CUDA events to time generator.generate calls and report latency'}
```

