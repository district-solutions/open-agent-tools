# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/luke/convert_luke_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a LUKE original PyTorch checkpoint to HuggingFace LukeModel format with entity-aware attention', 'load an entity vocabulary from a TSV file into a dictionary mapping entity titles to indices', 'run the LUKE checkpoint conversion CLI with checkpoint, metadata, entity vocab, and output paths', 'test the LUKE checkpoint conversion verifies hidden state shapes and values match expected tensors', 'review the entity vocab loader that parses TSV lines into a title-to-index mapping', 'run the LUKE model forward pass to get word and entity hidden states with optional pooling', 'build a classification head on top of entity hidden states for entity classification tasks like Open Entity', 'build a classification head on top of two entity hidden states for entity pair classification tasks like TACRED', 'build a span classification head using start, end, and entity hidden states for NER tasks', 'run a question answering head that predicts start and end token positions from sequence outputs', 'create a LUKE tokenizer with entity-aware encoding for named entity recognition tasks', 'build input sequences with entity spans and entity IDs for LUKE model tokenization', 'encode text paired with entity spans and entity names into token IDs and entity representations', 'pad batches of tokenized inputs with entity IDs, entity position IDs, and attention masks', 'truncate input sequences and entity spans to fit within max_length and max_entity_length constraints']
```

Usage

```
{'convert_luke_checkpoint': 'convert a LUKE original PyTorch checkpoint to HuggingFace LukeModel format with entity-aware attention', 'load_entity_vocab': 'load an entity vocabulary from a TSV file into a dictionary mapping entity titles to indices', 'run_convert_luke_cli': 'run the LUKE checkpoint conversion CLI with checkpoint, metadata, entity vocab, and output paths', 'test_convert_luke_checkpoint': 'test the LUKE checkpoint conversion verifies hidden state shapes and values match expected tensors', 'review_load_entity_vocab': 'review the entity vocab loader that parses TSV lines into a title-to-index mapping'}
```

## File: huggingface_transformers/src/transformers/models/luke/modeling_luke.py

Prompts

```
['convert a LUKE original PyTorch checkpoint to HuggingFace LukeModel format with entity-aware attention', 'load an entity vocabulary from a TSV file into a dictionary mapping entity titles to indices', 'run the LUKE checkpoint conversion CLI with checkpoint, metadata, entity vocab, and output paths', 'test the LUKE checkpoint conversion verifies hidden state shapes and values match expected tensors', 'review the entity vocab loader that parses TSV lines into a title-to-index mapping', 'run the LUKE model forward pass to get word and entity hidden states with optional pooling', 'build a classification head on top of entity hidden states for entity classification tasks like Open Entity', 'build a classification head on top of two entity hidden states for entity pair classification tasks like TACRED', 'build a span classification head using start, end, and entity hidden states for NER tasks', 'run a question answering head that predicts start and end token positions from sequence outputs', 'create a LUKE tokenizer with entity-aware encoding for named entity recognition tasks', 'build input sequences with entity spans and entity IDs for LUKE model tokenization', 'encode text paired with entity spans and entity names into token IDs and entity representations', 'pad batches of tokenized inputs with entity IDs, entity position IDs, and attention masks', 'truncate input sequences and entity spans to fit within max_length and max_entity_length constraints']
```

Usage

```
{'run_luke_model_forward': 'run the LUKE model forward pass to get word and entity hidden states with optional pooling', 'build_entity_classification_head': 'build a classification head on top of entity hidden states for entity classification tasks like Open Entity', 'build_entity_pair_classification_head': 'build a classification head on top of two entity hidden states for entity pair classification tasks like TACRED', 'build_entity_span_classification_head': 'build a span classification head using start, end, and entity hidden states for NER tasks', 'run_question_answering_head': 'run a question answering head that predicts start and end token positions from sequence outputs'}
```

## File: huggingface_transformers/src/transformers/models/luke/tokenization_luke.py

Prompts

```
['convert a LUKE original PyTorch checkpoint to HuggingFace LukeModel format with entity-aware attention', 'load an entity vocabulary from a TSV file into a dictionary mapping entity titles to indices', 'run the LUKE checkpoint conversion CLI with checkpoint, metadata, entity vocab, and output paths', 'test the LUKE checkpoint conversion verifies hidden state shapes and values match expected tensors', 'review the entity vocab loader that parses TSV lines into a title-to-index mapping', 'run the LUKE model forward pass to get word and entity hidden states with optional pooling', 'build a classification head on top of entity hidden states for entity classification tasks like Open Entity', 'build a classification head on top of two entity hidden states for entity pair classification tasks like TACRED', 'build a span classification head using start, end, and entity hidden states for NER tasks', 'run a question answering head that predicts start and end token positions from sequence outputs', 'create a LUKE tokenizer with entity-aware encoding for named entity recognition tasks', 'build input sequences with entity spans and entity IDs for LUKE model tokenization', 'encode text paired with entity spans and entity names into token IDs and entity representations', 'pad batches of tokenized inputs with entity IDs, entity position IDs, and attention masks', 'truncate input sequences and entity spans to fit within max_length and max_entity_length constraints']
```

Usage

```
{'create_luke_tokenizer': 'create a LUKE tokenizer with entity-aware encoding for named entity recognition tasks', 'build_entity_input_sequence': 'build input sequences with entity spans and entity IDs for LUKE model tokenization', 'encode_text_with_entities': 'encode text paired with entity spans and entity names into token IDs and entity representations', 'pad_entity_sequences': 'pad batches of tokenized inputs with entity IDs, entity position IDs, and attention masks', 'truncate_entity_tokens': 'truncate input sequences and entity spans to fit within max_length and max_entity_length constraints'}
```

