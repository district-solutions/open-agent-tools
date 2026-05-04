# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/symbolic_regression/bench/dataclasses.py

Prompts

```
['create an Equation dataclass with symbols, descriptions, properties, and a mathematical expression string', 'create a SearchResult dataclass that wraps an Equation with auxiliary metadata', 'create an SEDTask dataclass with symbols, descriptions, properties, and sample data for symbolic regression', 'create a Problem dataclass with a dataset identifier, ground truth equation, and train test samples', 'call create_task on a Problem instance to produce an SEDTask from the ground truth equation', 'get a data module by name such as bio_pop_growth or matsci for symbolic regression benchmarking', 'setup the TransformedFeynmanDataModule to load and parse the LSR Transform dataset from HuggingFace', 'setup a BaseSynthDataModule subclass to load synthetic benchmark problems from an HDF5 file', 'access train test and OOD test samples from a SynProblem instance for evaluation', 'download the llm-srbench dataset from HuggingFace using the snapshot_download helper function']
```

Usage

```
{'create_equation_dataclass': 'create an Equation dataclass with symbols, descriptions, properties, and a mathematical expression string', 'create_searchresult_dataclass': 'create a SearchResult dataclass that wraps an Equation with auxiliary metadata', 'create_sedtask_dataclass': 'create an SEDTask dataclass with symbols, descriptions, properties, and sample data for symbolic regression', 'create_problem_dataclass': 'create a Problem dataclass with a dataset identifier, ground truth equation, and train test samples', 'create_task_from_problem': 'call create_task on a Problem instance to produce an SEDTask from the ground truth equation'}
```

## File: algorithmicsuperintelligence_openevolve/examples/symbolic_regression/bench/datamodules.py

Prompts

```
['create an Equation dataclass with symbols, descriptions, properties, and a mathematical expression string', 'create a SearchResult dataclass that wraps an Equation with auxiliary metadata', 'create an SEDTask dataclass with symbols, descriptions, properties, and sample data for symbolic regression', 'create a Problem dataclass with a dataset identifier, ground truth equation, and train test samples', 'call create_task on a Problem instance to produce an SEDTask from the ground truth equation', 'get a data module by name such as bio_pop_growth or matsci for symbolic regression benchmarking', 'setup the TransformedFeynmanDataModule to load and parse the LSR Transform dataset from HuggingFace', 'setup a BaseSynthDataModule subclass to load synthetic benchmark problems from an HDF5 file', 'access train test and OOD test samples from a SynProblem instance for evaluation', 'download the llm-srbench dataset from HuggingFace using the snapshot_download helper function']
```

Usage

```
{'get_datamodule': 'get a data module by name such as bio_pop_growth or matsci for symbolic regression benchmarking', 'TransformedFeynmanDataModule_setup': 'setup the TransformedFeynmanDataModule to load and parse the LSR Transform dataset from HuggingFace', 'BaseSynthDataModule_setup': 'setup a BaseSynthDataModule subclass to load synthetic benchmark problems from an HDF5 file', 'SynProblem_train_test_samples': 'access train test and OOD test samples from a SynProblem instance for evaluation', 'download_dataset': 'download the llm-srbench dataset from HuggingFace using the snapshot_download helper function'}
```

