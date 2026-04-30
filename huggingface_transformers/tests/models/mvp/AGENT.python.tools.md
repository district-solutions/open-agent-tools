# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mvp/test_modeling_mvp.py

Prompts

```
['test MvpForSequenceClassification forward pass with input_ids and labels returning logits and loss', 'test MvpForQuestionAnswering forward pass with input_ids and start/end positions returning start and end logits', 'test MvpForConditionalGeneration forward pass with input_ids and labels returning logits and loss for language modeling', 'test MvpDecoder past key values caching produces identical outputs for incremental decoding', 'test shift_tokens_right function shifts decoder input ids right with bos token and pad token handling', 'test MvpModel encoder and decoder can be saved and loaded separately with matching outputs', 'test MvpModel decoder handles large inputs with past key values producing consistent outputs', 'test MvpForConditionalGeneration resize_token_embeddings expands vocabulary while keeping input and output embeddings equal', 'test MvpForConditionalGeneration generates text in fp16 precision with beam search and sampling', 'test MvpModel from_pretrained inference produces expected output shapes and values on RUCAIBox/mvp']
```

Usage

```
{'test_MvpForSequenceClassification_forward': 'test MvpForSequenceClassification forward pass with input_ids and labels returning logits and loss', 'test_MvpForQuestionAnswering_forward': 'test MvpForQuestionAnswering forward pass with input_ids and start/end positions returning start and end logits', 'test_MvpForConditionalGeneration_forward': 'test MvpForConditionalGeneration forward pass with input_ids and labels returning logits and loss for language modeling', 'test_MvpDecoder_past_key_values': 'test MvpDecoder past key values caching produces identical outputs for incremental decoding', 'test_shift_tokens_right': 'test shift_tokens_right function shifts decoder input ids right with bos token and pad token handling', 'test_MvpModel_encoder_decoder_standalone': 'test MvpModel encoder and decoder can be saved and loaded separately with matching outputs', 'test_MvpModel_decoder_large_inputs': 'test MvpModel decoder handles large inputs with past key values producing consistent outputs', 'test_MvpModel_resize_tokens_embeddings': 'test MvpForConditionalGeneration resize_token_embeddings expands vocabulary while keeping input and output embeddings equal', 'test_MvpModel_generate_fp16': 'test MvpForConditionalGeneration generates text in fp16 precision with beam search and sampling', 'test_MvpModel_integration_inference': 'test MvpModel from_pretrained inference produces expected output shapes and values on RUCAIBox/mvp'}
```

