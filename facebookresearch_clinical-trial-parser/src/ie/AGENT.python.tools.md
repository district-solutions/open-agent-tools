# Agent Python Tools

- repo: facebookresearch/clinical-trial-parser
- repo_uri: https://github.com/facebookresearch/clinical-trial-parser

## File: facebookresearch_clinical-trial-parser/src/ie/ner.py

Prompts

```
['run the NER model to extract medical terms from clinical trial eligibility criteria text', 'create an OfflinePredictor instance from a Caffe2 model file for named entity recognition', 'predict medical entity slots from text using the OfflinePredictor and group results by label', 'tokenize input text with an optional begin-of-sentence token using the Transformer module', 'group consecutive word predictions by label into named entity slots with averaged confidence scores', 'run the CLI tool to process annotated eligibility criteria TSV into train and test NER datasets', 'transform NER slot annotations and text by applying a text transformer and rebuilding label offsets', 'process an input TSV file, deduplicate samples, transform annotations, and split into train and test sets', 'parse command line arguments for input file, train output file, and test output file paths', 'review the transform function that rebuilds NER label offsets after applying text transformations']
```

Usage

```
{'run_NER_extraction': 'run the NER model to extract medical terms from clinical trial eligibility criteria text', 'create_OfflinePredictor': 'create an OfflinePredictor instance from a Caffe2 model file for named entity recognition', 'predict_medical_entities': 'predict medical entity slots from text using the OfflinePredictor and group results by label', 'tokenize_text': 'tokenize input text with an optional begin-of-sentence token using the Transformer module', 'group_slots': 'group consecutive word predictions by label into named entity slots with averaged confidence scores'}
```

## File: facebookresearch_clinical-trial-parser/src/ie/process_ner_data.py

Prompts

```
['run the NER model to extract medical terms from clinical trial eligibility criteria text', 'create an OfflinePredictor instance from a Caffe2 model file for named entity recognition', 'predict medical entity slots from text using the OfflinePredictor and group results by label', 'tokenize input text with an optional begin-of-sentence token using the Transformer module', 'group consecutive word predictions by label into named entity slots with averaged confidence scores', 'run the CLI tool to process annotated eligibility criteria TSV into train and test NER datasets', 'transform NER slot annotations and text by applying a text transformer and rebuilding label offsets', 'process an input TSV file, deduplicate samples, transform annotations, and split into train and test sets', 'parse command line arguments for input file, train output file, and test output file paths', 'review the transform function that rebuilds NER label offsets after applying text transformations']
```

Usage

```
{'run_process_ner_data': 'run the CLI tool to process annotated eligibility criteria TSV into train and test NER datasets', 'transform_ner_slots': 'transform NER slot annotations and text by applying a text transformer and rebuilding label offsets', 'main_process_and_split': 'process an input TSV file, deduplicate samples, transform annotations, and split into train and test sets', 'parse_args_cli': 'parse command line arguments for input file, train output file, and test output file paths', 'review_transform_function': 'review the transform function that rebuilds NER label offsets after applying text transformations'}
```

