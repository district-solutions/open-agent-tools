# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/xlm_roberta_xl/convert_xlm_roberta_xl_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a fairseq XLM-RoBERTa-XL checkpoint to a PyTorch HuggingFace model', 'convert a fairseq XLM-RoBERTa-XL checkpoint with a classification head to PyTorch', 'convert a fairseq XLM-RoBERTa-XL masked LM checkpoint to PyTorch HuggingFace format', 'verify the converted model produces outputs matching the original fairseq checkpoint', 'save the converted XLM-RoBERTa-XL model to a specified output directory', 'create an XLMRobertaXLModel encoder for bidirectional self-attention and sequence encoding', 'build an XLMRobertaXLForCausalLM model with language modeling head for autoregressive generation', 'run an XLMRobertaXLForMaskedLM model for masked language modeling with bidirectional context', 'test XLMRobertaXLForSequenceClassification on GLUE-style sequence classification tasks', 'review XLMRobertaXLSelfAttention and XLMRobertaXLCrossAttention modules with cache support for efficient inference', 'run XLMRobertaXLForCausalLM for next-token prediction with left-to-right language modeling loss', 'run XLMRobertaXLForSequenceClassification for GLUE-style sequence classification or regression tasks', 'run XLMRobertaXLForQuestionAnswering for extractive question answering with start and end logits', 'run XLMRobertaXLModel as the base encoder to produce contextual hidden states and cross-attention outputs']
```

Usage

```
{'convert_xlm_roberta_xl_checkpoint': 'convert a fairseq XLM-RoBERTa-XL checkpoint to a PyTorch HuggingFace model', 'convert_classification_head': 'convert a fairseq XLM-RoBERTa-XL checkpoint with a classification head to PyTorch', 'convert_masked_lm': 'convert a fairseq XLM-RoBERTa-XL masked LM checkpoint to PyTorch HuggingFace format', 'verify_conversion_output': 'verify the converted model produces outputs matching the original fairseq checkpoint', 'save_pretrained_model': 'save the converted XLM-RoBERTa-XL model to a specified output directory'}
```

## File: huggingface_transformers/src/transformers/models/xlm_roberta_xl/modeling_xlm_roberta_xl.py

Prompts

```
['convert a fairseq XLM-RoBERTa-XL checkpoint to a PyTorch HuggingFace model', 'convert a fairseq XLM-RoBERTa-XL checkpoint with a classification head to PyTorch', 'convert a fairseq XLM-RoBERTa-XL masked LM checkpoint to PyTorch HuggingFace format', 'verify the converted model produces outputs matching the original fairseq checkpoint', 'save the converted XLM-RoBERTa-XL model to a specified output directory', 'create an XLMRobertaXLModel encoder for bidirectional self-attention and sequence encoding', 'build an XLMRobertaXLForCausalLM model with language modeling head for autoregressive generation', 'run an XLMRobertaXLForMaskedLM model for masked language modeling with bidirectional context', 'test XLMRobertaXLForSequenceClassification on GLUE-style sequence classification tasks', 'review XLMRobertaXLSelfAttention and XLMRobertaXLCrossAttention modules with cache support for efficient inference', 'run XLMRobertaXLForCausalLM for next-token prediction with left-to-right language modeling loss', 'run XLMRobertaXLForSequenceClassification for GLUE-style sequence classification or regression tasks', 'run XLMRobertaXLForQuestionAnswering for extractive question answering with start and end logits', 'run XLMRobertaXLModel as the base encoder to produce contextual hidden states and cross-attention outputs']
```

Usage

```
{'create_xlm_roberta_xl_encoder': 'create an XLMRobertaXLModel encoder for bidirectional self-attention and sequence encoding', 'build_xlm_roberta_xl_causal_lm': 'build an XLMRobertaXLForCausalLM model with language modeling head for autoregressive generation', 'run_xlm_roberta_xl_masked_lm': 'run an XLMRobertaXLForMaskedLM model for masked language modeling with bidirectional context', 'test_xlm_roberta_xl_classification': 'test XLMRobertaXLForSequenceClassification on GLUE-style sequence classification tasks', 'review_xlm_roberta_xl_attention': 'review XLMRobertaXLSelfAttention and XLMRobertaXLCrossAttention modules with cache support for efficient inference'}
```

## File: huggingface_transformers/src/transformers/models/xlm_roberta_xl/modular_xlm_roberta_xl.py

Prompts

```
['convert a fairseq XLM-RoBERTa-XL checkpoint to a PyTorch HuggingFace model', 'convert a fairseq XLM-RoBERTa-XL checkpoint with a classification head to PyTorch', 'convert a fairseq XLM-RoBERTa-XL masked LM checkpoint to PyTorch HuggingFace format', 'verify the converted model produces outputs matching the original fairseq checkpoint', 'save the converted XLM-RoBERTa-XL model to a specified output directory', 'create an XLMRobertaXLModel encoder for bidirectional self-attention and sequence encoding', 'build an XLMRobertaXLForCausalLM model with language modeling head for autoregressive generation', 'run an XLMRobertaXLForMaskedLM model for masked language modeling with bidirectional context', 'test XLMRobertaXLForSequenceClassification on GLUE-style sequence classification tasks', 'review XLMRobertaXLSelfAttention and XLMRobertaXLCrossAttention modules with cache support for efficient inference', 'run XLMRobertaXLForCausalLM for next-token prediction with left-to-right language modeling loss', 'run XLMRobertaXLForSequenceClassification for GLUE-style sequence classification or regression tasks', 'run XLMRobertaXLForQuestionAnswering for extractive question answering with start and end logits', 'run XLMRobertaXLModel as the base encoder to produce contextual hidden states and cross-attention outputs']
```

Usage

```
{'run_xlm_roberta_xl_causal_lm': 'run XLMRobertaXLForCausalLM for next-token prediction with left-to-right language modeling loss', 'run_xlm_roberta_xl_masked_lm': 'run XLMRobertaXLForMaskedLM for masked language modeling with bidirectional self-attention', 'run_xlm_roberta_xl_sequence_classification': 'run XLMRobertaXLForSequenceClassification for GLUE-style sequence classification or regression tasks', 'run_xlm_roberta_xl_question_answering': 'run XLMRobertaXLForQuestionAnswering for extractive question answering with start and end logits', 'run_xlm_roberta_xl_model': 'run XLMRobertaXLModel as the base encoder to produce contextual hidden states and cross-attention outputs'}
```

