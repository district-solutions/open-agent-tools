# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/xmod/convert_xmod_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a fairseq X-MOD checkpoint to a HuggingFace PyTorch model with weight copying and validation', 'run the X-MOD checkpoint conversion CLI tool with fairseq checkpoint path and output directory arguments', 'build a HuggingFace XmodForMaskedLM model from a fairseq X-MOD checkpoint with copied weights', 'build a HuggingFace XmodForSequenceClassification model from a fairseq X-MOD checkpoint with classification head', 'verify the converted X-MOD model produces matching outputs against the original fairseq model', 'build a multilingual causal language model using XmodForCausalLM with decoder-only attention and cross-attention support', 'create a multilingual masked language model using XmodForMaskedLM with bidirectional self-attention for cloze tasks', 'test the XmodForSequenceClassification model for GLUE tasks with configurable classification or regression heads', 'refactor the XmodModel encoder to use per-language adapters for multilingual representation across multiple languages', 'review the XmodForQuestionAnswering model that outputs start and end logits for span-based question answering']
```

Usage

```
{'convert_xmod_checkpoint_to_pytorch': 'convert a fairseq X-MOD checkpoint to a HuggingFace PyTorch model with weight copying and validation', 'run_xmod_checkpoint_conversion_cli': 'run the X-MOD checkpoint conversion CLI tool with fairseq checkpoint path and output directory arguments', 'build_xmod_masked_lm_from_fairseq': 'build a HuggingFace XmodForMaskedLM model from a fairseq X-MOD checkpoint with copied weights', 'build_xmod_classification_model_from_fairseq': 'build a HuggingFace XmodForSequenceClassification model from a fairseq X-MOD checkpoint with classification head', 'verify_xmod_conversion_outputs': 'verify the converted X-MOD model produces matching outputs against the original fairseq model'}
```

## File: huggingface_transformers/src/transformers/models/xmod/modeling_xmod.py

Prompts

```
['convert a fairseq X-MOD checkpoint to a HuggingFace PyTorch model with weight copying and validation', 'run the X-MOD checkpoint conversion CLI tool with fairseq checkpoint path and output directory arguments', 'build a HuggingFace XmodForMaskedLM model from a fairseq X-MOD checkpoint with copied weights', 'build a HuggingFace XmodForSequenceClassification model from a fairseq X-MOD checkpoint with classification head', 'verify the converted X-MOD model produces matching outputs against the original fairseq model', 'build a multilingual causal language model using XmodForCausalLM with decoder-only attention and cross-attention support', 'create a multilingual masked language model using XmodForMaskedLM with bidirectional self-attention for cloze tasks', 'test the XmodForSequenceClassification model for GLUE tasks with configurable classification or regression heads', 'refactor the XmodModel encoder to use per-language adapters for multilingual representation across multiple languages', 'review the XmodForQuestionAnswering model that outputs start and end logits for span-based question answering']
```

Usage

```
{'build_xmod_causal_lm': 'build a multilingual causal language model using XmodForCausalLM with decoder-only attention and cross-attention support', 'create_xmod_masked_lm': 'create a multilingual masked language model using XmodForMaskedLM with bidirectional self-attention for cloze tasks', 'test_xmod_sequence_classification': 'test the XmodForSequenceClassification model for GLUE tasks with configurable classification or regression heads', 'refactor_xmod_language_adapters': 'refactor the XmodModel encoder to use per-language adapters for multilingual representation across multiple languages', 'review_xmod_question_answering': 'review the XmodForQuestionAnswering model that outputs start and end logits for span-based question answering'}
```

