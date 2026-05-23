# Agent Python Tools

- repo: facebookresearch/spiritlm
- repo_uri: https://github.com/facebookresearch/spiritlm

## File: facebookresearch_spiritlm/spiritlm/model/spiritlm_model.py

Prompts

```
['generate speech or text output from a Spiritlm model given interleaved speech and text inputs', 'build a prompt string from a list of GenerationInput objects with specified output modality', 'create a GenerationInput dataclass instance with content and ContentType for speech or text', 'decode generated token output into speech audio or text based on the specified output modality', 'parse generated content string into alternating speech and text chunks with modality labels', 'find the last speech token start position in a prompt string', 'convert an audio file path, numpy array, or bytes to a 16kHz WAV tensor', 'check if an encoded string starts with a speech token like Hu, Pi, or St', 'check if an encoded string ends with a speech token like Hu, Pi, or St', 'get a list of forbidden token IDs for speech or text generation']
```

Usage

```
{'generate_speech_text': 'generate speech or text output from a Spiritlm model given interleaved speech and text inputs', 'build_prompt_from_inputs': 'build a prompt string from a list of GenerationInput objects with specified output modality', 'create_generation_input': 'create a GenerationInput dataclass instance with content and ContentType for speech or text', 'decode_generated_output': 'decode generated token output into speech audio or text based on the specified output modality', 'parse_speech_and_text': 'parse generated content string into alternating speech and text chunks with modality labels'}
```

## File: facebookresearch_spiritlm/spiritlm/model/utils.py

Prompts

```
['generate speech or text output from a Spiritlm model given interleaved speech and text inputs', 'build a prompt string from a list of GenerationInput objects with specified output modality', 'create a GenerationInput dataclass instance with content and ContentType for speech or text', 'decode generated token output into speech audio or text based on the specified output modality', 'parse generated content string into alternating speech and text chunks with modality labels', 'find the last speech token start position in a prompt string', 'convert an audio file path, numpy array, or bytes to a 16kHz WAV tensor', 'check if an encoded string starts with a speech token like Hu, Pi, or St', 'check if an encoded string ends with a speech token like Hu, Pi, or St', 'get a list of forbidden token IDs for speech or text generation']
```

Usage

```
{'find_prompt_last_speech_start_position': 'find the last speech token start position in a prompt string', 'convert_to_wav_tensor': 'convert an audio file path, numpy array, or bytes to a 16kHz WAV tensor', 'does_start_with_speech_token': 'check if an encoded string starts with a speech token like Hu, Pi, or St', 'does_end_with_speech_token': 'check if an encoded string ends with a speech token like Hu, Pi, or St', 'get_forbidden_tokens': 'get a list of forbidden token IDs for speech or text generation'}
```

