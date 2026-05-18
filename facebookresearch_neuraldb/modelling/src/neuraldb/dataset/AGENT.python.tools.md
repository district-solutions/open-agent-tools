# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/modelling/src/neuraldb/dataset/neuraldb_file_reader.py

Prompts

```
['create a NeuralDBFileReader with an InstanceGenerator and call read on a JSONL dataset file', 'use the read method to yield generated instances from each database in a JSONL file', 'set the DEBUG environment variable to limit reading to the first four databases', 'review the NeuralDBFileReader class and its read method for reading JSONL database files', 'refactor the NeuralDBFileReader read method to support additional file formats beyond JSONL', 'build a python module that creates a NeuralDBParser instance to parse database facts and queries', 'run the NeuralDBParser load_instances method to parse a database dict with facts and queries', 'test the NeuralDBParser _maybe_sample method to randomly sample queries up to a max limit', 'review the NeuralDBParser _read_query method that processes query answers and answer types', 'refactor the NeuralDBParser _process_answer method to return custom answer types instead of None', 'create a Seq2SeqDataset from a generator that yields feature dictionaries for sequence-to-sequence training', 'create a Seq2SeqDataset from a generator with an auto_pad function applied to each instance', 'get the number of feature instances stored in a Seq2SeqDataset using len()', 'get a single feature dictionary from a Seq2SeqDataset by index using bracket notation', 'convert a Seq2SeqDataset features list into a dictionary mapping each key to a list of values']
```

Usage

```
{'read_instances_from_jsonl': 'create a NeuralDBFileReader with an InstanceGenerator and call read on a JSONL dataset file', 'yield_database_instances': 'use the read method to yield generated instances from each database in a JSONL file', 'debug_early_exit': 'set the DEBUG environment variable to limit reading to the first four databases', 'review_NeuralDBFileReader': 'review the NeuralDBFileReader class and its read method for reading JSONL database files', 'refactor_NeuralDBFileReader': 'refactor the NeuralDBFileReader read method to support additional file formats beyond JSONL'}
```

## File: facebookresearch_neuraldb/modelling/src/neuraldb/dataset/neuraldb_parser.py

Prompts

```
['create a NeuralDBFileReader with an InstanceGenerator and call read on a JSONL dataset file', 'use the read method to yield generated instances from each database in a JSONL file', 'set the DEBUG environment variable to limit reading to the first four databases', 'review the NeuralDBFileReader class and its read method for reading JSONL database files', 'refactor the NeuralDBFileReader read method to support additional file formats beyond JSONL', 'build a python module that creates a NeuralDBParser instance to parse database facts and queries', 'run the NeuralDBParser load_instances method to parse a database dict with facts and queries', 'test the NeuralDBParser _maybe_sample method to randomly sample queries up to a max limit', 'review the NeuralDBParser _read_query method that processes query answers and answer types', 'refactor the NeuralDBParser _process_answer method to return custom answer types instead of None', 'create a Seq2SeqDataset from a generator that yields feature dictionaries for sequence-to-sequence training', 'create a Seq2SeqDataset from a generator with an auto_pad function applied to each instance', 'get the number of feature instances stored in a Seq2SeqDataset using len()', 'get a single feature dictionary from a Seq2SeqDataset by index using bracket notation', 'convert a Seq2SeqDataset features list into a dictionary mapping each key to a list of values']
```

Usage

```
{'build_NeuralDBParser': 'build a python module that creates a NeuralDBParser instance to parse database facts and queries', 'run_load_instances': 'run the NeuralDBParser load_instances method to parse a database dict with facts and queries', 'test_maybe_sample': 'test the NeuralDBParser _maybe_sample method to randomly sample queries up to a max limit', 'review_read_query': 'review the NeuralDBParser _read_query method that processes query answers and answer types', 'refactor_process_answer': 'refactor the NeuralDBParser _process_answer method to return custom answer types instead of None'}
```

## File: facebookresearch_neuraldb/modelling/src/neuraldb/dataset/seq2seq_dataset.py

Prompts

```
['create a NeuralDBFileReader with an InstanceGenerator and call read on a JSONL dataset file', 'use the read method to yield generated instances from each database in a JSONL file', 'set the DEBUG environment variable to limit reading to the first four databases', 'review the NeuralDBFileReader class and its read method for reading JSONL database files', 'refactor the NeuralDBFileReader read method to support additional file formats beyond JSONL', 'build a python module that creates a NeuralDBParser instance to parse database facts and queries', 'run the NeuralDBParser load_instances method to parse a database dict with facts and queries', 'test the NeuralDBParser _maybe_sample method to randomly sample queries up to a max limit', 'review the NeuralDBParser _read_query method that processes query answers and answer types', 'refactor the NeuralDBParser _process_answer method to return custom answer types instead of None', 'create a Seq2SeqDataset from a generator that yields feature dictionaries for sequence-to-sequence training', 'create a Seq2SeqDataset from a generator with an auto_pad function applied to each instance', 'get the number of feature instances stored in a Seq2SeqDataset using len()', 'get a single feature dictionary from a Seq2SeqDataset by index using bracket notation', 'convert a Seq2SeqDataset features list into a dictionary mapping each key to a list of values']
```

Usage

```
{'create_seq2seq_dataset': 'create a Seq2SeqDataset from a generator that yields feature dictionaries for sequence-to-sequence training', 'create_seq2seq_dataset_with_padding': 'create a Seq2SeqDataset from a generator with an auto_pad function applied to each instance', 'get_dataset_length': 'get the number of feature instances stored in a Seq2SeqDataset using len()', 'get_dataset_item': 'get a single feature dictionary from a Seq2SeqDataset by index using bracket notation', 'convert_dataset_to_dict': 'convert a Seq2SeqDataset features list into a dictionary mapping each key to a list of values'}
```

