# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/moshi/test_modeling_moshi.py

Prompts

```
['run the MoshiDecoderTest suite to test MoshiModel and MoshiForCausalLM model classes', 'run the MoshiTest suite to test MoshiForConditionalGeneration generation and audio code outputs', 'run the MoshiIntegrationTests suite to test pretrained kmhf/hf-moshiko and kmhf/hf-moshika models', 'test the _config_zero_init function that recursively sets initializer parameters to near zero', 'test the Moshi decoder token embedding resize functionality with various vocab sizes and padding', 'test the Moshi tokenizer by tokenizing text and converting tokens to IDs using PreTrainedTokenizerFast', 'test the MoshiConverter to convert a SentencePiece vocab model into a HuggingFace tokenizer object', 'test training a new Moshi tokenizer from a text corpus using train_new_from_iterator', 'test adding special tokens to the Moshi tokenizer using AddedToken and additional_special_tokens', 'test encoding text to IDs and decoding IDs back to text with the Moshi fast tokenizer']
```

Usage

```
{'run_moshi_decoder_tests': 'run the MoshiDecoderTest suite to test MoshiModel and MoshiForCausalLM model classes', 'run_moshi_conditional_tests': 'run the MoshiTest suite to test MoshiForConditionalGeneration generation and audio code outputs', 'run_moshi_integration_tests': 'run the MoshiIntegrationTests suite to test pretrained kmhf/hf-moshiko and kmhf/hf-moshika models', 'test_moshi_config_zero_init': 'test the _config_zero_init function that recursively sets initializer parameters to near zero', 'test_moshi_resize_embeddings': 'test the Moshi decoder token embedding resize functionality with various vocab sizes and padding'}
```

## File: huggingface_transformers/tests/models/moshi/test_tokenization_moshi.py

Prompts

```
['run the MoshiDecoderTest suite to test MoshiModel and MoshiForCausalLM model classes', 'run the MoshiTest suite to test MoshiForConditionalGeneration generation and audio code outputs', 'run the MoshiIntegrationTests suite to test pretrained kmhf/hf-moshiko and kmhf/hf-moshika models', 'test the _config_zero_init function that recursively sets initializer parameters to near zero', 'test the Moshi decoder token embedding resize functionality with various vocab sizes and padding', 'test the Moshi tokenizer by tokenizing text and converting tokens to IDs using PreTrainedTokenizerFast', 'test the MoshiConverter to convert a SentencePiece vocab model into a HuggingFace tokenizer object', 'test training a new Moshi tokenizer from a text corpus using train_new_from_iterator', 'test adding special tokens to the Moshi tokenizer using AddedToken and additional_special_tokens', 'test encoding text to IDs and decoding IDs back to text with the Moshi fast tokenizer']
```

Usage

```
{'test_moshi_tokenizer_full': 'test the Moshi tokenizer by tokenizing text and converting tokens to IDs using PreTrainedTokenizerFast', 'test_moshi_converter_sentencepiece': 'test the MoshiConverter to convert a SentencePiece vocab model into a HuggingFace tokenizer object', 'test_moshi_train_new_tokenizer': 'test training a new Moshi tokenizer from a text corpus using train_new_from_iterator', 'test_moshi_special_tokens': 'test adding special tokens to the Moshi tokenizer using AddedToken and additional_special_tokens', 'test_moshi_encode_decode': 'test encoding text to IDs and decoding IDs back to text with the Moshi fast tokenizer'}
```

