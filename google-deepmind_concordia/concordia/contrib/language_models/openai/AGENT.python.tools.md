# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/contrib/language_models/openai/base_gpt_model.py

Prompts

```
['initialize a BaseGPTModel instance with an OpenAI or Azure client and model name', 'sample text completion from a GPT model using the sample_text method with a prompt', 'sample a multiple choice answer from a GPT model using the sample_choice method', 'sample text with configurable reasoning effort and verbosity using the internal _sample_text method', 'configure verbosity level for GPT-4o models by setting medium verbosity in the model name', 'create a GptVisionModel instance with a chat model name and optional image model name for multimodal use', 'sample text from GptVisionModel by passing a prompt with inline markdown images for vision input', 'generate an image by calling sample_text with the image generation trigger prefix and a description', 'sample a multiple choice answer from GptVisionModel by passing a prompt and list of response options', 'parse a prompt string into multimodal content parts by extracting inline markdown images as image_url parts']
```

Usage

```
{'init_base_gpt_model': 'initialize a BaseGPTModel instance with an OpenAI or Azure client and model name', 'sample_text_gpt': 'sample text completion from a GPT model using the sample_text method with a prompt', 'sample_choice_gpt': 'sample a multiple choice answer from a GPT model using the sample_choice method', 'sample_text_with_reasoning': 'sample text with configurable reasoning effort and verbosity using the internal _sample_text method', 'configure_gpt_verbosity': 'configure verbosity level for GPT-4o models by setting medium verbosity in the model name'}
```

## File: google-deepmind_concordia/concordia/contrib/language_models/openai/gpt_model_multimodal.py

Prompts

```
['initialize a BaseGPTModel instance with an OpenAI or Azure client and model name', 'sample text completion from a GPT model using the sample_text method with a prompt', 'sample a multiple choice answer from a GPT model using the sample_choice method', 'sample text with configurable reasoning effort and verbosity using the internal _sample_text method', 'configure verbosity level for GPT-4o models by setting medium verbosity in the model name', 'create a GptVisionModel instance with a chat model name and optional image model name for multimodal use', 'sample text from GptVisionModel by passing a prompt with inline markdown images for vision input', 'generate an image by calling sample_text with the image generation trigger prefix and a description', 'sample a multiple choice answer from GptVisionModel by passing a prompt and list of response options', 'parse a prompt string into multimodal content parts by extracting inline markdown images as image_url parts']
```

Usage

```
{'create_GptVisionModel': 'create a GptVisionModel instance with a chat model name and optional image model name for multimodal use', 'sample_text_vision': 'sample text from GptVisionModel by passing a prompt with inline markdown images for vision input', 'sample_text_image_gen': 'generate an image by calling sample_text with the image generation trigger prefix and a description', 'sample_choice': 'sample a multiple choice answer from GptVisionModel by passing a prompt and list of response options', 'parse_prompt_to_content': 'parse a prompt string into multimodal content parts by extracting inline markdown images as image_url parts'}
```

