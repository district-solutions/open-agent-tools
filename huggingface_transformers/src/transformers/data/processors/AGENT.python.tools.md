# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/data/processors/glue.py

Prompts

```
['convert GLUE InputExamples to tokenized InputFeatures using a tokenizer and task configuration', 'create an MrpcProcessor to load and parse MRPC dataset examples from TSV files for GLUE tasks', 'create an MnliProcessor to load and parse MultiNLI entailment examples from TSV files for GLUE tasks', 'create an StsbProcessor to load and parse STS-B regression examples from TSV files for GLUE tasks', 'use the glue_processors dictionary to instantiate the correct processor class for a given GLUE task name', 'convert SQuAD examples into model-ready features with tokenized inputs and answer spans', 'create a SQuAD data processor to load training and development examples from JSON files', 'build a SQuAD example object from question, context, answer text, and character offsets', 'run parallel SQuAD example-to-feature conversion with multiprocessing and tokenizer alignment', 'test model evaluation results using SQuAD result objects with start and end logits', 'create a SingleSentenceClassificationProcessor from a CSV file with specified columns and split', 'build tokenized InputFeatures from text examples using a tokenizer with padding and masking', 'create a PyTorch TensorDataset from classification examples with input_ids, attention_mask, and labels', 'create a PyTorch TensorDataset from regression examples with float labels and padded input sequences', 'summarize an InputExample by serializing it to a JSON string with guid, text_a, text_b, and label fields', 'create an XnliProcessor instance for a specified language to load XNLI dataset examples', 'run get_train_examples on XnliProcessor to load training data from TSV files for a given language', 'run get_test_examples on XnliProcessor to filter and load test examples matching the target language', 'review the get_labels method that returns the three XNLI classification labels', 'build processor configuration using xnli_processors, xnli_output_modes, and xnli_tasks_num_labels dicts']
```

Usage

```
{'convert_examples_to_features': 'convert GLUE InputExamples to tokenized InputFeatures using a tokenizer and task configuration', 'create_mrpc_processor': 'create an MrpcProcessor to load and parse MRPC dataset examples from TSV files for GLUE tasks', 'create_mnli_processor': 'create an MnliProcessor to load and parse MultiNLI entailment examples from TSV files for GLUE tasks', 'create_stsb_processor': 'create an StsbProcessor to load and parse STS-B regression examples from TSV files for GLUE tasks', 'use_glue_processors_dict': 'use the glue_processors dictionary to instantiate the correct processor class for a given GLUE task name'}
```

## File: huggingface_transformers/src/transformers/data/processors/squad.py

Prompts

```
['convert GLUE InputExamples to tokenized InputFeatures using a tokenizer and task configuration', 'create an MrpcProcessor to load and parse MRPC dataset examples from TSV files for GLUE tasks', 'create an MnliProcessor to load and parse MultiNLI entailment examples from TSV files for GLUE tasks', 'create an StsbProcessor to load and parse STS-B regression examples from TSV files for GLUE tasks', 'use the glue_processors dictionary to instantiate the correct processor class for a given GLUE task name', 'convert SQuAD examples into model-ready features with tokenized inputs and answer spans', 'create a SQuAD data processor to load training and development examples from JSON files', 'build a SQuAD example object from question, context, answer text, and character offsets', 'run parallel SQuAD example-to-feature conversion with multiprocessing and tokenizer alignment', 'test model evaluation results using SQuAD result objects with start and end logits', 'create a SingleSentenceClassificationProcessor from a CSV file with specified columns and split', 'build tokenized InputFeatures from text examples using a tokenizer with padding and masking', 'create a PyTorch TensorDataset from classification examples with input_ids, attention_mask, and labels', 'create a PyTorch TensorDataset from regression examples with float labels and padded input sequences', 'summarize an InputExample by serializing it to a JSON string with guid, text_a, text_b, and label fields', 'create an XnliProcessor instance for a specified language to load XNLI dataset examples', 'run get_train_examples on XnliProcessor to load training data from TSV files for a given language', 'run get_test_examples on XnliProcessor to filter and load test examples matching the target language', 'review the get_labels method that returns the three XNLI classification labels', 'build processor configuration using xnli_processors, xnli_output_modes, and xnli_tasks_num_labels dicts']
```

Usage

```
{'convert_squad_examples_to_features': 'convert SQuAD examples into model-ready features with tokenized inputs and answer spans', 'create_squad_processor': 'create a SQuAD data processor to load training and development examples from JSON files', 'build_squad_example': 'build a SQuAD example object from question, context, answer text, and character offsets', 'run_squad_feature_conversion': 'run parallel SQuAD example-to-feature conversion with multiprocessing and tokenizer alignment', 'test_squad_result': 'test model evaluation results using SQuAD result objects with start and end logits'}
```

## File: huggingface_transformers/src/transformers/data/processors/utils.py

Prompts

```
['convert GLUE InputExamples to tokenized InputFeatures using a tokenizer and task configuration', 'create an MrpcProcessor to load and parse MRPC dataset examples from TSV files for GLUE tasks', 'create an MnliProcessor to load and parse MultiNLI entailment examples from TSV files for GLUE tasks', 'create an StsbProcessor to load and parse STS-B regression examples from TSV files for GLUE tasks', 'use the glue_processors dictionary to instantiate the correct processor class for a given GLUE task name', 'convert SQuAD examples into model-ready features with tokenized inputs and answer spans', 'create a SQuAD data processor to load training and development examples from JSON files', 'build a SQuAD example object from question, context, answer text, and character offsets', 'run parallel SQuAD example-to-feature conversion with multiprocessing and tokenizer alignment', 'test model evaluation results using SQuAD result objects with start and end logits', 'create a SingleSentenceClassificationProcessor from a CSV file with specified columns and split', 'build tokenized InputFeatures from text examples using a tokenizer with padding and masking', 'create a PyTorch TensorDataset from classification examples with input_ids, attention_mask, and labels', 'create a PyTorch TensorDataset from regression examples with float labels and padded input sequences', 'summarize an InputExample by serializing it to a JSON string with guid, text_a, text_b, and label fields', 'create an XnliProcessor instance for a specified language to load XNLI dataset examples', 'run get_train_examples on XnliProcessor to load training data from TSV files for a given language', 'run get_test_examples on XnliProcessor to filter and load test examples matching the target language', 'review the get_labels method that returns the three XNLI classification labels', 'build processor configuration using xnli_processors, xnli_output_modes, and xnli_tasks_num_labels dicts']
```

Usage

```
{'create_processor_from_csv': 'create a SingleSentenceClassificationProcessor from a CSV file with specified columns and split', 'build_classification_features': 'build tokenized InputFeatures from text examples using a tokenizer with padding and masking', 'create_classification_dataset': 'create a PyTorch TensorDataset from classification examples with input_ids, attention_mask, and labels', 'create_regression_dataset': 'create a PyTorch TensorDataset from regression examples with float labels and padded input sequences', 'summarize_input_example': 'summarize an InputExample by serializing it to a JSON string with guid, text_a, text_b, and label fields'}
```

## File: huggingface_transformers/src/transformers/data/processors/xnli.py

Prompts

```
['convert GLUE InputExamples to tokenized InputFeatures using a tokenizer and task configuration', 'create an MrpcProcessor to load and parse MRPC dataset examples from TSV files for GLUE tasks', 'create an MnliProcessor to load and parse MultiNLI entailment examples from TSV files for GLUE tasks', 'create an StsbProcessor to load and parse STS-B regression examples from TSV files for GLUE tasks', 'use the glue_processors dictionary to instantiate the correct processor class for a given GLUE task name', 'convert SQuAD examples into model-ready features with tokenized inputs and answer spans', 'create a SQuAD data processor to load training and development examples from JSON files', 'build a SQuAD example object from question, context, answer text, and character offsets', 'run parallel SQuAD example-to-feature conversion with multiprocessing and tokenizer alignment', 'test model evaluation results using SQuAD result objects with start and end logits', 'create a SingleSentenceClassificationProcessor from a CSV file with specified columns and split', 'build tokenized InputFeatures from text examples using a tokenizer with padding and masking', 'create a PyTorch TensorDataset from classification examples with input_ids, attention_mask, and labels', 'create a PyTorch TensorDataset from regression examples with float labels and padded input sequences', 'summarize an InputExample by serializing it to a JSON string with guid, text_a, text_b, and label fields', 'create an XnliProcessor instance for a specified language to load XNLI dataset examples', 'run get_train_examples on XnliProcessor to load training data from TSV files for a given language', 'run get_test_examples on XnliProcessor to filter and load test examples matching the target language', 'review the get_labels method that returns the three XNLI classification labels', 'build processor configuration using xnli_processors, xnli_output_modes, and xnli_tasks_num_labels dicts']
```

Usage

```
{'create_XnliProcessor': 'create an XnliProcessor instance for a specified language to load XNLI dataset examples', 'run_get_train_examples': 'run get_train_examples on XnliProcessor to load training data from TSV files for a given language', 'run_get_test_examples': 'run get_test_examples on XnliProcessor to filter and load test examples matching the target language', 'review_get_labels': 'review the get_labels method that returns the three XNLI classification labels', 'build_xnli_processor_config': 'build processor configuration using xnli_processors, xnli_output_modes, and xnli_tasks_num_labels dicts'}
```

