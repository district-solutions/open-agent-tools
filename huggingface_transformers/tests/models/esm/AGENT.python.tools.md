# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/esm/test_modeling_esm.py

Prompts

```
['test EsmModelTester to prepare config and inputs for ESM model testing', 'test EsmModel forward pass with input_ids and attention_mask to verify output shapes', 'test EsmForMaskedLM model with token labels to verify masked language modeling logits', 'test EsmForTokenClassification model to verify token classification logits match expected shapes', 'test ESM model gradient checkpointing by running forward and backward passes', 'create an EsmForProteinFolding model with a small config and run inference on input_ids to get positions and angles', 'test that EsmForProteinFolding produces equivalent outputs for batched and unbatched inputs', 'test EsmConfig with is_folding_model flag and esmfold_config dict for protein folding settings', 'test reverse loading mapping for EsmForProteinFolding with rotary position embeddings', 'test inference on the pretrained facebook/esmfold_v1 model and verify position output values', 'test that EsmTokenizer tokenizes a protein sequence like LAGVS into individual amino acid tokens', 'test that EsmTokenizer encodes a sequence into IDs wrapped with cls and eos special tokens', 'test batch tokenization of multiple protein sequences without padding using EsmTokenizer', 'test batch tokenization of multiple protein sequences with padding to equal length using EsmTokenizer', 'test adding new tokens and special tokens to the EsmTokenizer vocabulary']
```

Usage

```
{'test_EsmModelTester_prepare_config_and_inputs': 'test EsmModelTester to prepare config and inputs for ESM model testing', 'test_EsmModelTest_model_forward': 'test EsmModel forward pass with input_ids and attention_mask to verify output shapes', 'test_EsmForMaskedLM': 'test EsmForMaskedLM model with token labels to verify masked language modeling logits', 'test_EsmForTokenClassification': 'test EsmForTokenClassification model to verify token classification logits match expected shapes', 'test_Esm_gradient_checkpointing': 'test ESM model gradient checkpointing by running forward and backward passes'}
```

## File: huggingface_transformers/tests/models/esm/test_modeling_esmfold.py

Prompts

```
['test EsmModelTester to prepare config and inputs for ESM model testing', 'test EsmModel forward pass with input_ids and attention_mask to verify output shapes', 'test EsmForMaskedLM model with token labels to verify masked language modeling logits', 'test EsmForTokenClassification model to verify token classification logits match expected shapes', 'test ESM model gradient checkpointing by running forward and backward passes', 'create an EsmForProteinFolding model with a small config and run inference on input_ids to get positions and angles', 'test that EsmForProteinFolding produces equivalent outputs for batched and unbatched inputs', 'test EsmConfig with is_folding_model flag and esmfold_config dict for protein folding settings', 'test reverse loading mapping for EsmForProteinFolding with rotary position embeddings', 'test inference on the pretrained facebook/esmfold_v1 model and verify position output values', 'test that EsmTokenizer tokenizes a protein sequence like LAGVS into individual amino acid tokens', 'test that EsmTokenizer encodes a sequence into IDs wrapped with cls and eos special tokens', 'test batch tokenization of multiple protein sequences without padding using EsmTokenizer', 'test batch tokenization of multiple protein sequences with padding to equal length using EsmTokenizer', 'test adding new tokens and special tokens to the EsmTokenizer vocabulary']
```

Usage

```
{'create_model_esmfold': 'create an EsmForProteinFolding model with a small config and run inference on input_ids to get positions and angles', 'test_batching_equivalence_esmfold': 'test that EsmForProteinFolding produces equivalent outputs for batched and unbatched inputs', 'test_config_esmfold': 'test EsmConfig with is_folding_model flag and esmfold_config dict for protein folding settings', 'test_reverse_loading_mapping_esmfold': 'test reverse loading mapping for EsmForProteinFolding with rotary position embeddings', 'test_inference_protein_folding_esmfold': 'test inference on the pretrained facebook/esmfold_v1 model and verify position output values'}
```

## File: huggingface_transformers/tests/models/esm/test_tokenization_esm.py

Prompts

```
['test EsmModelTester to prepare config and inputs for ESM model testing', 'test EsmModel forward pass with input_ids and attention_mask to verify output shapes', 'test EsmForMaskedLM model with token labels to verify masked language modeling logits', 'test EsmForTokenClassification model to verify token classification logits match expected shapes', 'test ESM model gradient checkpointing by running forward and backward passes', 'create an EsmForProteinFolding model with a small config and run inference on input_ids to get positions and angles', 'test that EsmForProteinFolding produces equivalent outputs for batched and unbatched inputs', 'test EsmConfig with is_folding_model flag and esmfold_config dict for protein folding settings', 'test reverse loading mapping for EsmForProteinFolding with rotary position embeddings', 'test inference on the pretrained facebook/esmfold_v1 model and verify position output values', 'test that EsmTokenizer tokenizes a protein sequence like LAGVS into individual amino acid tokens', 'test that EsmTokenizer encodes a sequence into IDs wrapped with cls and eos special tokens', 'test batch tokenization of multiple protein sequences without padding using EsmTokenizer', 'test batch tokenization of multiple protein sequences with padding to equal length using EsmTokenizer', 'test adding new tokens and special tokens to the EsmTokenizer vocabulary']
```

Usage

```
{'test_esm_tokenize_protein_sequence': 'test that EsmTokenizer tokenizes a protein sequence like LAGVS into individual amino acid tokens', 'test_esm_encode_with_special_tokens': 'test that EsmTokenizer encodes a sequence into IDs wrapped with cls and eos special tokens', 'test_esm_batch_tokenize_no_padding': 'test batch tokenization of multiple protein sequences without padding using EsmTokenizer', 'test_esm_batch_tokenize_with_padding': 'test batch tokenization of multiple protein sequences with padding to equal length using EsmTokenizer', 'test_esm_add_tokens_and_special_tokens': 'test adding new tokens and special tokens to the EsmTokenizer vocabulary'}
```

