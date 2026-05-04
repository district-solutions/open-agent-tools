# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/concordia/contrib/language_models/huggingface/huggingface_model.py

Prompts

```
['build a HuggingFaceLanguageModel instance using a model name and API key from HuggingFace', 'sample text from a HuggingFaceLanguageModel by providing a prompt with temperature and max tokens', 'sample a choice from multiple responses using log probability scoring on a HuggingFaceLanguageModel', 'compute the log probability of a response given a prompt using the model logits', 'get the tokenizer instance or device from a HuggingFaceLanguageModel for inspection', 'initialize a PyTorch Gemma language model with a HuggingFace model name and device', 'generate text completion from a prompt using the Gemma model with temperature and top_k controls', 'sample a choice from a list of candidate responses using the Gemma model', 'review the sample_text method to understand how terminator strings truncate generated responses', 'refactor the sample_choice method to improve InvalidResponseError handling for unmatched responses']
```

Usage

```
{'build_huggingface_model': 'build a HuggingFaceLanguageModel instance using a model name and API key from HuggingFace', 'sample_text_generation': 'sample text from a HuggingFaceLanguageModel by providing a prompt with temperature and max tokens', 'sample_choice_responses': 'sample a choice from multiple responses using log probability scoring on a HuggingFaceLanguageModel', 'compute_log_probability': 'compute the log probability of a response given a prompt using the model logits', 'get_tokenizer_device': 'get the tokenizer instance or device from a HuggingFaceLanguageModel for inspection'}
```

## File: google-deepmind_concordia/concordia/contrib/language_models/huggingface/pytorch_gemma_model.py

Prompts

```
['build a HuggingFaceLanguageModel instance using a model name and API key from HuggingFace', 'sample text from a HuggingFaceLanguageModel by providing a prompt with temperature and max tokens', 'sample a choice from multiple responses using log probability scoring on a HuggingFaceLanguageModel', 'compute the log probability of a response given a prompt using the model logits', 'get the tokenizer instance or device from a HuggingFaceLanguageModel for inspection', 'initialize a PyTorch Gemma language model with a HuggingFace model name and device', 'generate text completion from a prompt using the Gemma model with temperature and top_k controls', 'sample a choice from a list of candidate responses using the Gemma model', 'review the sample_text method to understand how terminator strings truncate generated responses', 'refactor the sample_choice method to improve InvalidResponseError handling for unmatched responses']
```

Usage

```
{'init_pytorch_gemma_model': 'initialize a PyTorch Gemma language model with a HuggingFace model name and device', 'sample_text_completion': 'generate text completion from a prompt using the Gemma model with temperature and top_k controls', 'sample_choice_response': 'sample a choice from a list of candidate responses using the Gemma model', 'review_sample_text_terminators': 'review the sample_text method to understand how terminator strings truncate generated responses', 'refactor_sample_choice_error_handling': 'refactor the sample_choice method to improve InvalidResponseError handling for unmatched responses'}
```

