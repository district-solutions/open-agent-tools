# Agent Python Tools

- repo: facebookresearch/spiritlm
- repo_uri: https://github.com/facebookresearch/spiritlm

## File: facebookresearch_spiritlm/tests/test_spirit_model.py

Prompts

```
['test the Spiritlm model _parse_speech_and_text method to split content into speech and text segments', 'test the Spiritlm model _parse_speech_and_text method with expressive Hu and Pi tokens', 'test the does_end_with_speech_token utility to check if a string ends with a speech token', 'test the find_prompt_last_speech_start_position utility to locate the last speech start position in a prompt', 'test the does_start_with_speech_token utility to check if a string starts with a speech token', 'test the expressive tokenizer encode_units method with an audio file path input', 'test the expressive tokenizer encode_units method with a torchaudio tensor input', 'test the base tokenizer encode_units method to extract hubert tokens from audio', 'test the expressive tokenizer encode_string method to produce bracketed token strings', 'test the base tokenizer encode_string method to produce hubert-only bracketed token strings']
```

Usage

```
{'test_parse_speech_and_text': 'test the Spiritlm model _parse_speech_and_text method to split content into speech and text segments', 'test_parse_speech_and_text_with_expressive_tokens': 'test the Spiritlm model _parse_speech_and_text method with expressive Hu and Pi tokens', 'test_does_end_with_speech_token': 'test the does_end_with_speech_token utility to check if a string ends with a speech token', 'test_find_prompt_last_speech_start_position': 'test the find_prompt_last_speech_start_position utility to locate the last speech start position in a prompt', 'test_does_start_with_speech_token': 'test the does_start_with_speech_token utility to check if a string starts with a speech token'}
```

## File: facebookresearch_spiritlm/tests/test_tokenizer.py

Prompts

```
['test the Spiritlm model _parse_speech_and_text method to split content into speech and text segments', 'test the Spiritlm model _parse_speech_and_text method with expressive Hu and Pi tokens', 'test the does_end_with_speech_token utility to check if a string ends with a speech token', 'test the find_prompt_last_speech_start_position utility to locate the last speech start position in a prompt', 'test the does_start_with_speech_token utility to check if a string starts with a speech token', 'test the expressive tokenizer encode_units method with an audio file path input', 'test the expressive tokenizer encode_units method with a torchaudio tensor input', 'test the base tokenizer encode_units method to extract hubert tokens from audio', 'test the expressive tokenizer encode_string method to produce bracketed token strings', 'test the base tokenizer encode_string method to produce hubert-only bracketed token strings']
```

Usage

```
{'test_spiritlm_expressive_encode_units': 'test the expressive tokenizer encode_units method with an audio file path input', 'test_spiritlm_expressive_encode_units_tensor': 'test the expressive tokenizer encode_units method with a torchaudio tensor input', 'test_spiritlm_base_encode_units': 'test the base tokenizer encode_units method to extract hubert tokens from audio', 'test_spiritlm_expressive_encode_string': 'test the expressive tokenizer encode_string method to produce bracketed token strings', 'test_spiritlm_base_encode_string': 'test the base tokenizer encode_string method to produce hubert-only bracketed token strings'}
```

