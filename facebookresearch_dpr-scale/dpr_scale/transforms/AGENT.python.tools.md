# Agent Python Tools

- repo: facebookresearch/dpr-scale
- repo_uri: https://github.com/facebookresearch/dpr-scale

## File: facebookresearch_dpr-scale/dpr_scale/transforms/dpr_distill_transform.py

Prompts

```
['create a DPRDistillTransform module with a text_transform and pos_ctx_sample settings', 'run the DPRDistillTransform forward pass on a batch of question and context vector data', 'transform a list of question texts into tokenized IDs using the text_transform', 'sample a single positive context vector from a list of embeddings for training', 'review the DPRDistillTransform class and its forward method for question and context embedding processing', 'create a DPRTransform module to tokenize questions and positive negative context pairs for dense retrieval training', 'create a DPRCrossAttentionTransform module to tokenize concatenated question context pairs for cross attention training', 'run the DPRTransform forward pass on a batch of DPR training data with positive and negative contexts', 'run the DPRCrossAttentionTransform forward pass on a batch to produce concatenated question context token tensors', 'review the DPRTransform class and its positive negative context sampling logic with relevance score weighting', 'create a BertTransform instance with a custom model path and max sequence length', 'run the BertTransform forward method to tokenize a list of text strings into tensors', 'build a BERT tokenizer wrapper that handles padding truncation and special tokens automatically', 'test the BertTransform forward method with sample text inputs and verify tensor output shape', 'review the BertTransform init to understand how model paths are resolved via PathManager', 'create an HFTransform module to tokenize text using a HuggingFace tokenizer with configurable max sequence length', 'run the HFTransform forward pass to tokenize a list of single text strings with padding and truncation', 'run the HFTransform forward pass to tokenize text pairs using the HuggingFace tokenizer with special tokens', 'build an HFTransform module with a custom model path and custom max sequence length for tokenization', 'review the HFTransform class to understand tokenizer configuration options like add_special_tokens and return_tensors']
```

Usage

```
{'create_dpr_distill_transform': 'create a DPRDistillTransform module with a text_transform and pos_ctx_sample settings', 'run_dpr_distill_forward': 'run the DPRDistillTransform forward pass on a batch of question and context vector data', 'transform_question_embeddings': 'transform a list of question texts into tokenized IDs using the text_transform', 'sample_positive_context_vectors': 'sample a single positive context vector from a list of embeddings for training', 'review_dpr_distill_transform': 'review the DPRDistillTransform class and its forward method for question and context embedding processing'}
```

## File: facebookresearch_dpr-scale/dpr_scale/transforms/dpr_transform.py

Prompts

```
['create a DPRDistillTransform module with a text_transform and pos_ctx_sample settings', 'run the DPRDistillTransform forward pass on a batch of question and context vector data', 'transform a list of question texts into tokenized IDs using the text_transform', 'sample a single positive context vector from a list of embeddings for training', 'review the DPRDistillTransform class and its forward method for question and context embedding processing', 'create a DPRTransform module to tokenize questions and positive negative context pairs for dense retrieval training', 'create a DPRCrossAttentionTransform module to tokenize concatenated question context pairs for cross attention training', 'run the DPRTransform forward pass on a batch of DPR training data with positive and negative contexts', 'run the DPRCrossAttentionTransform forward pass on a batch to produce concatenated question context token tensors', 'review the DPRTransform class and its positive negative context sampling logic with relevance score weighting', 'create a BertTransform instance with a custom model path and max sequence length', 'run the BertTransform forward method to tokenize a list of text strings into tensors', 'build a BERT tokenizer wrapper that handles padding truncation and special tokens automatically', 'test the BertTransform forward method with sample text inputs and verify tensor output shape', 'review the BertTransform init to understand how model paths are resolved via PathManager', 'create an HFTransform module to tokenize text using a HuggingFace tokenizer with configurable max sequence length', 'run the HFTransform forward pass to tokenize a list of single text strings with padding and truncation', 'run the HFTransform forward pass to tokenize text pairs using the HuggingFace tokenizer with special tokens', 'build an HFTransform module with a custom model path and custom max sequence length for tokenization', 'review the HFTransform class to understand tokenizer configuration options like add_special_tokens and return_tensors']
```

Usage

```
{'create_dpr_transform': 'create a DPRTransform module to tokenize questions and positive negative context pairs for dense retrieval training', 'create_dpr_cross_attention_transform': 'create a DPRCrossAttentionTransform module to tokenize concatenated question context pairs for cross attention training', 'run_dpr_transform_forward': 'run the DPRTransform forward pass on a batch of DPR training data with positive and negative contexts', 'run_dpr_cross_attention_forward': 'run the DPRCrossAttentionTransform forward pass on a batch to produce concatenated question context token tensors', 'review_dpr_transform_sampling': 'review the DPRTransform class and its positive negative context sampling logic with relevance score weighting'}
```

## File: facebookresearch_dpr-scale/dpr_scale/transforms/hf_bert.py

Prompts

```
['create a DPRDistillTransform module with a text_transform and pos_ctx_sample settings', 'run the DPRDistillTransform forward pass on a batch of question and context vector data', 'transform a list of question texts into tokenized IDs using the text_transform', 'sample a single positive context vector from a list of embeddings for training', 'review the DPRDistillTransform class and its forward method for question and context embedding processing', 'create a DPRTransform module to tokenize questions and positive negative context pairs for dense retrieval training', 'create a DPRCrossAttentionTransform module to tokenize concatenated question context pairs for cross attention training', 'run the DPRTransform forward pass on a batch of DPR training data with positive and negative contexts', 'run the DPRCrossAttentionTransform forward pass on a batch to produce concatenated question context token tensors', 'review the DPRTransform class and its positive negative context sampling logic with relevance score weighting', 'create a BertTransform instance with a custom model path and max sequence length', 'run the BertTransform forward method to tokenize a list of text strings into tensors', 'build a BERT tokenizer wrapper that handles padding truncation and special tokens automatically', 'test the BertTransform forward method with sample text inputs and verify tensor output shape', 'review the BertTransform init to understand how model paths are resolved via PathManager', 'create an HFTransform module to tokenize text using a HuggingFace tokenizer with configurable max sequence length', 'run the HFTransform forward pass to tokenize a list of single text strings with padding and truncation', 'run the HFTransform forward pass to tokenize text pairs using the HuggingFace tokenizer with special tokens', 'build an HFTransform module with a custom model path and custom max sequence length for tokenization', 'review the HFTransform class to understand tokenizer configuration options like add_special_tokens and return_tensors']
```

Usage

```
{'create_bert_transform': 'create a BertTransform instance with a custom model path and max sequence length', 'run_bert_tokenization': 'run the BertTransform forward method to tokenize a list of text strings into tensors', 'build_bert_tokenizer': 'build a BERT tokenizer wrapper that handles padding truncation and special tokens automatically', 'test_bert_transform_forward': 'test the BertTransform forward method with sample text inputs and verify tensor output shape', 'review_bert_transform_init': 'review the BertTransform init to understand how model paths are resolved via PathManager'}
```

## File: facebookresearch_dpr-scale/dpr_scale/transforms/hf_transform.py

Prompts

```
['create a DPRDistillTransform module with a text_transform and pos_ctx_sample settings', 'run the DPRDistillTransform forward pass on a batch of question and context vector data', 'transform a list of question texts into tokenized IDs using the text_transform', 'sample a single positive context vector from a list of embeddings for training', 'review the DPRDistillTransform class and its forward method for question and context embedding processing', 'create a DPRTransform module to tokenize questions and positive negative context pairs for dense retrieval training', 'create a DPRCrossAttentionTransform module to tokenize concatenated question context pairs for cross attention training', 'run the DPRTransform forward pass on a batch of DPR training data with positive and negative contexts', 'run the DPRCrossAttentionTransform forward pass on a batch to produce concatenated question context token tensors', 'review the DPRTransform class and its positive negative context sampling logic with relevance score weighting', 'create a BertTransform instance with a custom model path and max sequence length', 'run the BertTransform forward method to tokenize a list of text strings into tensors', 'build a BERT tokenizer wrapper that handles padding truncation and special tokens automatically', 'test the BertTransform forward method with sample text inputs and verify tensor output shape', 'review the BertTransform init to understand how model paths are resolved via PathManager', 'create an HFTransform module to tokenize text using a HuggingFace tokenizer with configurable max sequence length', 'run the HFTransform forward pass to tokenize a list of single text strings with padding and truncation', 'run the HFTransform forward pass to tokenize text pairs using the HuggingFace tokenizer with special tokens', 'build an HFTransform module with a custom model path and custom max sequence length for tokenization', 'review the HFTransform class to understand tokenizer configuration options like add_special_tokens and return_tensors']
```

Usage

```
{'create_hftransform_tokenizer': 'create an HFTransform module to tokenize text using a HuggingFace tokenizer with configurable max sequence length', 'run_hftransform_forward_single': 'run the HFTransform forward pass to tokenize a list of single text strings with padding and truncation', 'run_hftransform_forward_pair': 'run the HFTransform forward pass to tokenize text pairs using the HuggingFace tokenizer with special tokens', 'build_hftransform_custom_model': 'build an HFTransform module with a custom model path and custom max sequence length for tokenization', 'review_hftransform_config': 'review the HFTransform class to understand tokenizer configuration options like add_special_tokens and return_tensors'}
```

