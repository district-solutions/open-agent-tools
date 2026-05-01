# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/dia/test_feature_extraction_dia.py

Prompts

```
['test the DiaFeatureExtractor call method with batched and unbatched audio inputs returning numpy tensors', 'create a DiaFeatureExtractor instance with feature_size, padding_value, sampling_rate, and hop_length parameters', 'test DiaFeatureExtractor truncation and padding behavior with max_length constraints and error handling', 'test DiaFeatureExtractor integration with real audio data from librispeech dataset and verify output shapes and values', 'test DiaFeatureExtractor with stereo audio inputs by setting feature_size to 2 and verifying output', 'test the DiaModelTester class by creating a DiaConfig with encoder and decoder configs for the Dia model', 'test the DiaModel forward pass by running input IDs through the model and verifying output hidden state shapes', 'test the DiaForConditionalGeneration model by generating audio tokens from text prompts using greedy search', 'test the Dia encoder and decoder as standalone modules by saving and reloading them separately', 'test that the Dia composite model correctly dispatches to SDPA attention implementation across all submodules', 'test that DiaProcessor saves and loads pretrained tokenizer, feature extractor, and audio tokenizer correctly', 'test that DiaProcessor tokenizes text input and matches standalone tokenizer output', 'test that DiaProcessor handles text-only input with proper BOS and padding token masks', 'test that DiaProcessor encodes raw audio into codebook tokens with correct delay pattern padding', 'test the build_indices and apply_audio_delay static methods for audio channel delay and reversal', 'test the DiaTokenizer to tokenize text into individual byte-level character tokens', 'test the DiaTokenizer to convert token strings into their corresponding integer IDs', 'test the DiaTokenizer to convert integer token IDs back into token strings', 'test loading a DiaTokenizer from a pretrained model checkpoint on HuggingFace Hub', 'test the DiaTokenizer to decode token IDs back into the original text sequence']
```

Usage

```
{'test_DiaFeatureExtractor_call': 'test the DiaFeatureExtractor call method with batched and unbatched audio inputs returning numpy tensors', 'create_DiaFeatureExtractor': 'create a DiaFeatureExtractor instance with feature_size, padding_value, sampling_rate, and hop_length parameters', 'test_DiaFeatureExtractor_truncation_padding': 'test DiaFeatureExtractor truncation and padding behavior with max_length constraints and error handling', 'test_DiaFeatureExtractor_integration': 'test DiaFeatureExtractor integration with real audio data from librispeech dataset and verify output shapes and values', 'test_DiaFeatureExtractor_stereo': 'test DiaFeatureExtractor with stereo audio inputs by setting feature_size to 2 and verifying output'}
```

## File: huggingface_transformers/tests/models/dia/test_modeling_dia.py

Prompts

```
['test the DiaFeatureExtractor call method with batched and unbatched audio inputs returning numpy tensors', 'create a DiaFeatureExtractor instance with feature_size, padding_value, sampling_rate, and hop_length parameters', 'test DiaFeatureExtractor truncation and padding behavior with max_length constraints and error handling', 'test DiaFeatureExtractor integration with real audio data from librispeech dataset and verify output shapes and values', 'test DiaFeatureExtractor with stereo audio inputs by setting feature_size to 2 and verifying output', 'test the DiaModelTester class by creating a DiaConfig with encoder and decoder configs for the Dia model', 'test the DiaModel forward pass by running input IDs through the model and verifying output hidden state shapes', 'test the DiaForConditionalGeneration model by generating audio tokens from text prompts using greedy search', 'test the Dia encoder and decoder as standalone modules by saving and reloading them separately', 'test that the Dia composite model correctly dispatches to SDPA attention implementation across all submodules', 'test that DiaProcessor saves and loads pretrained tokenizer, feature extractor, and audio tokenizer correctly', 'test that DiaProcessor tokenizes text input and matches standalone tokenizer output', 'test that DiaProcessor handles text-only input with proper BOS and padding token masks', 'test that DiaProcessor encodes raw audio into codebook tokens with correct delay pattern padding', 'test the build_indices and apply_audio_delay static methods for audio channel delay and reversal', 'test the DiaTokenizer to tokenize text into individual byte-level character tokens', 'test the DiaTokenizer to convert token strings into their corresponding integer IDs', 'test the DiaTokenizer to convert integer token IDs back into token strings', 'test loading a DiaTokenizer from a pretrained model checkpoint on HuggingFace Hub', 'test the DiaTokenizer to decode token IDs back into the original text sequence']
```

Usage

```
{'test_DiaModelTester_config': 'test the DiaModelTester class by creating a DiaConfig with encoder and decoder configs for the Dia model', 'test_DiaModel_forward': 'test the DiaModel forward pass by running input IDs through the model and verifying output hidden state shapes', 'test_DiaForConditionalGeneration_generate_tts': 'test the DiaForConditionalGeneration model by generating audio tokens from text prompts using greedy search', 'test_DiaEncoderDecoder_standalone': 'test the Dia encoder and decoder as standalone modules by saving and reloading them separately', 'test_DiaModel_sdpa_dispatch': 'test that the Dia composite model correctly dispatches to SDPA attention implementation across all submodules'}
```

## File: huggingface_transformers/tests/models/dia/test_processing_dia.py

Prompts

```
['test the DiaFeatureExtractor call method with batched and unbatched audio inputs returning numpy tensors', 'create a DiaFeatureExtractor instance with feature_size, padding_value, sampling_rate, and hop_length parameters', 'test DiaFeatureExtractor truncation and padding behavior with max_length constraints and error handling', 'test DiaFeatureExtractor integration with real audio data from librispeech dataset and verify output shapes and values', 'test DiaFeatureExtractor with stereo audio inputs by setting feature_size to 2 and verifying output', 'test the DiaModelTester class by creating a DiaConfig with encoder and decoder configs for the Dia model', 'test the DiaModel forward pass by running input IDs through the model and verifying output hidden state shapes', 'test the DiaForConditionalGeneration model by generating audio tokens from text prompts using greedy search', 'test the Dia encoder and decoder as standalone modules by saving and reloading them separately', 'test that the Dia composite model correctly dispatches to SDPA attention implementation across all submodules', 'test that DiaProcessor saves and loads pretrained tokenizer, feature extractor, and audio tokenizer correctly', 'test that DiaProcessor tokenizes text input and matches standalone tokenizer output', 'test that DiaProcessor handles text-only input with proper BOS and padding token masks', 'test that DiaProcessor encodes raw audio into codebook tokens with correct delay pattern padding', 'test the build_indices and apply_audio_delay static methods for audio channel delay and reversal', 'test the DiaTokenizer to tokenize text into individual byte-level character tokens', 'test the DiaTokenizer to convert token strings into their corresponding integer IDs', 'test the DiaTokenizer to convert integer token IDs back into token strings', 'test loading a DiaTokenizer from a pretrained model checkpoint on HuggingFace Hub', 'test the DiaTokenizer to decode token IDs back into the original text sequence']
```

Usage

```
{'test_DiaProcessor_save_load': 'test that DiaProcessor saves and loads pretrained tokenizer, feature extractor, and audio tokenizer correctly', 'test_DiaProcessor_tokenize': 'test that DiaProcessor tokenizes text input and matches standalone tokenizer output', 'test_DiaProcessor_no_audio': 'test that DiaProcessor handles text-only input with proper BOS and padding token masks', 'test_DiaProcessor_audio': 'test that DiaProcessor encodes raw audio into codebook tokens with correct delay pattern padding', 'test_DiaProcessor_build_indices_and_delay': 'test the build_indices and apply_audio_delay static methods for audio channel delay and reversal'}
```

## File: huggingface_transformers/tests/models/dia/test_tokenization_dia.py

Prompts

```
['test the DiaFeatureExtractor call method with batched and unbatched audio inputs returning numpy tensors', 'create a DiaFeatureExtractor instance with feature_size, padding_value, sampling_rate, and hop_length parameters', 'test DiaFeatureExtractor truncation and padding behavior with max_length constraints and error handling', 'test DiaFeatureExtractor integration with real audio data from librispeech dataset and verify output shapes and values', 'test DiaFeatureExtractor with stereo audio inputs by setting feature_size to 2 and verifying output', 'test the DiaModelTester class by creating a DiaConfig with encoder and decoder configs for the Dia model', 'test the DiaModel forward pass by running input IDs through the model and verifying output hidden state shapes', 'test the DiaForConditionalGeneration model by generating audio tokens from text prompts using greedy search', 'test the Dia encoder and decoder as standalone modules by saving and reloading them separately', 'test that the Dia composite model correctly dispatches to SDPA attention implementation across all submodules', 'test that DiaProcessor saves and loads pretrained tokenizer, feature extractor, and audio tokenizer correctly', 'test that DiaProcessor tokenizes text input and matches standalone tokenizer output', 'test that DiaProcessor handles text-only input with proper BOS and padding token masks', 'test that DiaProcessor encodes raw audio into codebook tokens with correct delay pattern padding', 'test the build_indices and apply_audio_delay static methods for audio channel delay and reversal', 'test the DiaTokenizer to tokenize text into individual byte-level character tokens', 'test the DiaTokenizer to convert token strings into their corresponding integer IDs', 'test the DiaTokenizer to convert integer token IDs back into token strings', 'test loading a DiaTokenizer from a pretrained model checkpoint on HuggingFace Hub', 'test the DiaTokenizer to decode token IDs back into the original text sequence']
```

Usage

```
{'test_DiaTokenizer_tokenize': 'test the DiaTokenizer to tokenize text into individual byte-level character tokens', 'test_DiaTokenizer_convert_tokens_to_ids': 'test the DiaTokenizer to convert token strings into their corresponding integer IDs', 'test_DiaTokenizer_convert_ids_to_tokens': 'test the DiaTokenizer to convert integer token IDs back into token strings', 'test_DiaTokenizer_from_pretrained': 'test loading a DiaTokenizer from a pretrained model checkpoint on HuggingFace Hub', 'test_DiaTokenizer_decode': 'test the DiaTokenizer to decode token IDs back into the original text sequence'}
```

