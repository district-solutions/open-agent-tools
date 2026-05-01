# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/roberta/test_modeling_roberta.py

Prompts

```
['test the RobertaModel class by running create_and_check_model with a config and input tensors', 'test RobertaForMaskedLM by running create_and_check_for_masked_lm with input ids and labels', 'test RobertaForCausalLM by running create_and_check_for_causal_lm with decoder config and labels', 'test RobertaEmbeddings.create_position_ids_from_input_ids to verify padding index is respected', 'test inference with RobertaForMaskedLM.from_pretrained using the roberta-base model and fixed input ids', 'load a JSON vocabulary file into a Python dictionary using load_vocab', 'load a BPE merges file into a list of tuples using load_merges', 'test the RobertaTokenizer by tokenizing text and converting tokens to IDs', 'create a RobertaTokenizer instance from a vocab dictionary and merges list', 'run the RobertaTokenizationTest suite to validate tokenizer behavior with integration test data']
```

Usage

```
{'test_roberta_model': 'test the RobertaModel class by running create_and_check_model with a config and input tensors', 'test_roberta_masked_lm': 'test RobertaForMaskedLM by running create_and_check_for_masked_lm with input ids and labels', 'test_roberta_causal_lm': 'test RobertaForCausalLM by running create_and_check_for_causal_lm with decoder config and labels', 'test_roberta_embeddings_position_ids': 'test RobertaEmbeddings.create_position_ids_from_input_ids to verify padding index is respected', 'test_roberta_integration_inference': 'test inference with RobertaForMaskedLM.from_pretrained using the roberta-base model and fixed input ids'}
```

## File: huggingface_transformers/tests/models/roberta/test_tokenization_roberta.py

Prompts

```
['test the RobertaModel class by running create_and_check_model with a config and input tensors', 'test RobertaForMaskedLM by running create_and_check_for_masked_lm with input ids and labels', 'test RobertaForCausalLM by running create_and_check_for_causal_lm with decoder config and labels', 'test RobertaEmbeddings.create_position_ids_from_input_ids to verify padding index is respected', 'test inference with RobertaForMaskedLM.from_pretrained using the roberta-base model and fixed input ids', 'load a JSON vocabulary file into a Python dictionary using load_vocab', 'load a BPE merges file into a list of tuples using load_merges', 'test the RobertaTokenizer by tokenizing text and converting tokens to IDs', 'create a RobertaTokenizer instance from a vocab dictionary and merges list', 'run the RobertaTokenizationTest suite to validate tokenizer behavior with integration test data']
```

Usage

```
{'load_vocab_json': 'load a JSON vocabulary file into a Python dictionary using load_vocab', 'load_merges_bpe': 'load a BPE merges file into a list of tuples using load_merges', 'test_roberta_tokenizer': 'test the RobertaTokenizer by tokenizing text and converting tokens to IDs', 'create_roberta_tokenizer_from_vocab': 'create a RobertaTokenizer instance from a vocab dictionary and merges list', 'run_roberta_tokenization_tests': 'run the RobertaTokenizationTest suite to validate tokenizer behavior with integration test data'}
```

