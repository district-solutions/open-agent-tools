# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mluke/convert_mluke_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert an original mLUKE PyTorch checkpoint to HuggingFace LukeForMaskedLM format', 'load an original mLUKE entity vocabulary file and return a language-prefixed entity mapping', 'run the mLUKE checkpoint conversion script via argparse CLI with checkpoint and metadata paths', 'add entity special tokens <ent> and <ent2> to an XLMRobertaTokenizer for mLUKE', 'initialize entity-aware self-attention query weights from original checkpoint for each encoder layer', 'create an MLukeTokenizer instance with vocab and entity vocab files for multilingual Luke tokenization', 'encode text with entity spans using MLukeTokenizer to produce input_ids and entity_ids for entity classification tasks', 'build input sequences with entity token spans for entity_pair_classification task using _create_input_sequence', 'pad batched encoded inputs with entity_ids, entity_position_ids, and entity_attention_mask using the pad method', 'save the entity vocabulary file as JSON to a specified directory using save_vocabulary']
```

Usage

```
{'convert_mluke_checkpoint': 'convert an original mLUKE PyTorch checkpoint to HuggingFace LukeForMaskedLM format', 'load_original_entity_vocab': 'load an original mLUKE entity vocabulary file and return a language-prefixed entity mapping', 'run_convert_script_cli': 'run the mLUKE checkpoint conversion script via argparse CLI with checkpoint and metadata paths', 'add_special_tokens_to_tokenizer': 'add entity special tokens <ent> and <ent2> to an XLMRobertaTokenizer for mLUKE', 'initialize_entity_attention_weights': 'initialize entity-aware self-attention query weights from original checkpoint for each encoder layer'}
```

## File: huggingface_transformers/src/transformers/models/mluke/tokenization_mluke.py

Prompts

```
['convert an original mLUKE PyTorch checkpoint to HuggingFace LukeForMaskedLM format', 'load an original mLUKE entity vocabulary file and return a language-prefixed entity mapping', 'run the mLUKE checkpoint conversion script via argparse CLI with checkpoint and metadata paths', 'add entity special tokens <ent> and <ent2> to an XLMRobertaTokenizer for mLUKE', 'initialize entity-aware self-attention query weights from original checkpoint for each encoder layer', 'create an MLukeTokenizer instance with vocab and entity vocab files for multilingual Luke tokenization', 'encode text with entity spans using MLukeTokenizer to produce input_ids and entity_ids for entity classification tasks', 'build input sequences with entity token spans for entity_pair_classification task using _create_input_sequence', 'pad batched encoded inputs with entity_ids, entity_position_ids, and entity_attention_mask using the pad method', 'save the entity vocabulary file as JSON to a specified directory using save_vocabulary']
```

Usage

```
{'create_mluke_tokenizer': 'create an MLukeTokenizer instance with vocab and entity vocab files for multilingual Luke tokenization', 'encode_entity_spans': 'encode text with entity spans using MLukeTokenizer to produce input_ids and entity_ids for entity classification tasks', 'build_input_sequence': 'build input sequences with entity token spans for entity_pair_classification task using _create_input_sequence', 'pad_entity_inputs': 'pad batched encoded inputs with entity_ids, entity_position_ids, and entity_attention_mask using the pad method', 'save_entity_vocab': 'save the entity vocabulary file as JSON to a specified directory using save_vocabulary'}
```

