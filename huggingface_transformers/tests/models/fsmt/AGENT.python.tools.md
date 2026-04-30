# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/fsmt/test_modeling_fsmt.py

Prompts

```
['test the FSMTModelTester class that generates config and input dicts for FSMT model tests', 'test the FSMTModelTest class for FSMTModel and FSMTForConditionalGeneration inference and generation', 'test the FSMTHeadTests class for helper functions like shift_tokens_right and _prepare_fsmt_decoder_inputs', 'test the FSMTModelIntegrationTests class for slow translation inference with real pretrained models', 'test the TestSinusoidalPositionalEmbeddings class for positional embedding lookup behavior', 'test the shift_tokens_right function that shifts input IDs right and fills the first position with bos_token_id', 'test the _prepare_fsmt_decoder_inputs function that generates decoder input ids and causal attention masks', 'test the invert_mask function that inverts binary attention masks for FSMT decoder attention', 'test the FSMTTokenizer full tokenization with a custom vocab, merges, and BPE tokenization', 'test the FSMTTokenizer online config loading from pretrained model weights', 'test the FSMTTokenizer sequence builders for encoding sentences and pairs with special tokens', 'test the FSMTTokenizer encode-decode roundtrip for English-Russian translation pairs', 'test the FSMTTokenizer lowercase tokenization for English text input']
```

Usage

```
{'test_FSMTModelTester': 'test the FSMTModelTester class that generates config and input dicts for FSMT model tests', 'test_FSMTModelTest': 'test the FSMTModelTest class for FSMTModel and FSMTForConditionalGeneration inference and generation', 'test_FSMTHeadTests': 'test the FSMTHeadTests class for helper functions like shift_tokens_right and _prepare_fsmt_decoder_inputs', 'test_FSMTModelIntegrationTests': 'test the FSMTModelIntegrationTests class for slow translation inference with real pretrained models', 'test_SinusoidalPositionalEmbeddings': 'test the TestSinusoidalPositionalEmbeddings class for positional embedding lookup behavior', 'test_shift_tokens_right': 'test the shift_tokens_right function that shifts input IDs right and fills the first position with bos_token_id', 'test_prepare_fsmt_decoder_inputs': 'test the _prepare_fsmt_decoder_inputs function that generates decoder input ids and causal attention masks', 'test_invert_mask': 'test the invert_mask function that inverts binary attention masks for FSMT decoder attention'}
```

## File: huggingface_transformers/tests/models/fsmt/test_tokenization_fsmt.py

Prompts

```
['test the FSMTModelTester class that generates config and input dicts for FSMT model tests', 'test the FSMTModelTest class for FSMTModel and FSMTForConditionalGeneration inference and generation', 'test the FSMTHeadTests class for helper functions like shift_tokens_right and _prepare_fsmt_decoder_inputs', 'test the FSMTModelIntegrationTests class for slow translation inference with real pretrained models', 'test the TestSinusoidalPositionalEmbeddings class for positional embedding lookup behavior', 'test the shift_tokens_right function that shifts input IDs right and fills the first position with bos_token_id', 'test the _prepare_fsmt_decoder_inputs function that generates decoder input ids and causal attention masks', 'test the invert_mask function that inverts binary attention masks for FSMT decoder attention', 'test the FSMTTokenizer full tokenization with a custom vocab, merges, and BPE tokenization', 'test the FSMTTokenizer online config loading from pretrained model weights', 'test the FSMTTokenizer sequence builders for encoding sentences and pairs with special tokens', 'test the FSMTTokenizer encode-decode roundtrip for English-Russian translation pairs', 'test the FSMTTokenizer lowercase tokenization for English text input']
```

Usage

```
{'test_full_tokenizer': 'test the FSMTTokenizer full tokenization with a custom vocab, merges, and BPE tokenization', 'test_online_tokenizer_config': 'test the FSMTTokenizer online config loading from pretrained model weights', 'test_sequence_builders': 'test the FSMTTokenizer sequence builders for encoding sentences and pairs with special tokens', 'test_match_encode_decode': 'test the FSMTTokenizer encode-decode roundtrip for English-Russian translation pairs', 'test_tokenizer_lower': 'test the FSMTTokenizer lowercase tokenization for English text input'}
```

