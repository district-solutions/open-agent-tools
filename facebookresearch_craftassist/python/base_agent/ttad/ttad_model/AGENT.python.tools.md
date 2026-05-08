# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/base_agent/ttad/ttad_model/make_dataset.py

Prompts

```
['run the script to parse a text file into a train/valid/test JSON dataset', 'create a function that tokenizes text using spaCy English tokenizer and returns space-joined tokens', 'parse a text file with grouped examples and JSON annotations into a structured JSON dataset', 'split parsed examples into train, valid, and test sets and save as JSON', 'review the tokenize function that uses spaCy English tokenizer to split and rejoin text tokens', 'initialize an ActionDictBuilder with model, embeddings, and grammar paths for TTAD semantic parsing', 'parse a list of chat messages into an action dictionary using the TTAD model', 'recursively remove NOT_IMPLEMENTED entries from a nested action dictionary', 'load a TTAD model with embeddings and dialogue grammar for semantic parsing', 'predict an action tree from chat history using the TTAD model and word-to-index mapping']
```

Usage

```
{'run_make_dataset': 'run the script to parse a text file into a train/valid/test JSON dataset', 'create_tokenize_function': 'create a function that tokenizes text using spaCy English tokenizer and returns space-joined tokens', 'parse_text_to_json_dataset': 'parse a text file with grouped examples and JSON annotations into a structured JSON dataset', 'split_dataset_train_valid_test': 'split parsed examples into train, valid, and test sets and save as JSON', 'review_tokenize': 'review the tokenize function that uses spaCy English tokenizer to split and rejoin text tokens'}
```

## File: facebookresearch_craftassist/python/base_agent/ttad/ttad_model/ttad_model_wrapper.py

Prompts

```
['run the script to parse a text file into a train/valid/test JSON dataset', 'create a function that tokenizes text using spaCy English tokenizer and returns space-joined tokens', 'parse a text file with grouped examples and JSON annotations into a structured JSON dataset', 'split parsed examples into train, valid, and test sets and save as JSON', 'review the tokenize function that uses spaCy English tokenizer to split and rejoin text tokens', 'initialize an ActionDictBuilder with model, embeddings, and grammar paths for TTAD semantic parsing', 'parse a list of chat messages into an action dictionary using the TTAD model', 'recursively remove NOT_IMPLEMENTED entries from a nested action dictionary', 'load a TTAD model with embeddings and dialogue grammar for semantic parsing', 'predict an action tree from chat history using the TTAD model and word-to-index mapping']
```

Usage

```
{'init_action_dict_builder': 'initialize an ActionDictBuilder with model, embeddings, and grammar paths for TTAD semantic parsing', 'parse_chat_to_actions': 'parse a list of chat messages into an action dictionary using the TTAD model', 'remove_not_implemented_actions': 'recursively remove NOT_IMPLEMENTED entries from a nested action dictionary', 'load_ttad_model': 'load a TTAD model with embeddings and dialogue grammar for semantic parsing', 'predict_action_tree': 'predict an action tree from chat history using the TTAD model and word-to-index mapping'}
```

