# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/luke/test_modeling_luke.py

Prompts

```
['test the LukeModel base architecture with input tokens and entity IDs to verify hidden state shapes', 'test LukeForMaskedLM to predict masked tokens and entity labels using input and entity IDs', 'test LukeForEntityClassification to classify entities using entity IDs and attention masks', 'test LukeForEntitySpanClassification with entity start and end positions to classify entity spans', 'run inference with a pretrained LUKE model using LukeTokenizer and entity spans on input text', 'test the LukeTokenizer build_inputs_with_special_tokens method for single and pair sequences', 'test the LukeTokenizer padding and entity_spans handling for batch inputs with entity spans', 'test the LukeTokenizer encoding of single text with named entities and character spans', 'test the LukeTokenizer entity_classification task with entity spans and special <ent> tokens', 'test the LukeTokenizer entity_pair_classification task with head and tail entity spans using <ent2> tokens']
```

Usage

```
{'test_luke_model': 'test the LukeModel base architecture with input tokens and entity IDs to verify hidden state shapes', 'test_luke_masked_lm': 'test LukeForMaskedLM to predict masked tokens and entity labels using input and entity IDs', 'test_luke_entity_classification': 'test LukeForEntityClassification to classify entities using entity IDs and attention masks', 'test_luke_entity_span_classification': 'test LukeForEntitySpanClassification with entity start and end positions to classify entity spans', 'test_luke_integration_inference': 'run inference with a pretrained LUKE model using LukeTokenizer and entity spans on input text'}
```

## File: huggingface_transformers/tests/models/luke/test_tokenization_luke.py

Prompts

```
['test the LukeModel base architecture with input tokens and entity IDs to verify hidden state shapes', 'test LukeForMaskedLM to predict masked tokens and entity labels using input and entity IDs', 'test LukeForEntityClassification to classify entities using entity IDs and attention masks', 'test LukeForEntitySpanClassification with entity start and end positions to classify entity spans', 'run inference with a pretrained LUKE model using LukeTokenizer and entity spans on input text', 'test the LukeTokenizer build_inputs_with_special_tokens method for single and pair sequences', 'test the LukeTokenizer padding and entity_spans handling for batch inputs with entity spans', 'test the LukeTokenizer encoding of single text with named entities and character spans', 'test the LukeTokenizer entity_classification task with entity spans and special <ent> tokens', 'test the LukeTokenizer entity_pair_classification task with head and tail entity spans using <ent2> tokens']
```

Usage

```
{'test_luke_tokenizer_sequence_builders': 'test the LukeTokenizer build_inputs_with_special_tokens method for single and pair sequences', 'test_luke_tokenizer_padding_entity_inputs': 'test the LukeTokenizer padding and entity_spans handling for batch inputs with entity spans', 'test_luke_tokenizer_single_text_entity_encoding': 'test the LukeTokenizer encoding of single text with named entities and character spans', 'test_luke_tokenizer_entity_classification': 'test the LukeTokenizer entity_classification task with entity spans and special <ent> tokens', 'test_luke_tokenizer_entity_pair_classification': 'test the LukeTokenizer entity_pair_classification task with head and tail entity spans using <ent2> tokens'}
```

