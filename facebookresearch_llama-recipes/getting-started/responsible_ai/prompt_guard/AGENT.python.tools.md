# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/getting-started/responsible_ai/prompt_guard/inference.py

Prompts

```
['load the PromptGuard 2 model and tokenizer from HuggingFace onto CPU or CUDA device', 'evaluate a single text string for malicious jailbreak or prompt injection probability', 'get temperature-adjusted softmax class scores for a single text input using the PromptGuard model', 'compute jailbreak scores for a list of texts with chunking and parallel batch processing', 'process a batch of texts through the PromptGuard model and return class probabilities', 'evaluate a single text string for embedded instructions from third party inputs', 'batch evaluate a list of texts for jailbreak scores with chunking and parallel processing', 'batch evaluate a list of texts for indirect injection scores with chunking and parallel processing']
```

Usage

```
{'load_promptguard_model': 'load the PromptGuard 2 model and tokenizer from HuggingFace onto CPU or CUDA device', 'get_jailbreak_score': 'evaluate a single text string for malicious jailbreak or prompt injection probability', 'get_class_scores': 'get temperature-adjusted softmax class scores for a single text input using the PromptGuard model', 'batch_jailbreak_scores': 'compute jailbreak scores for a list of texts with chunking and parallel batch processing', 'process_text_batch': 'process a batch of texts through the PromptGuard model and return class probabilities'}
```

## File: facebookresearch_llama-recipes/getting-started/responsible_ai/prompt_guard/prompt_guard_1_inference.py

Prompts

```
['load the PromptGuard 2 model and tokenizer from HuggingFace onto CPU or CUDA device', 'evaluate a single text string for malicious jailbreak or prompt injection probability', 'get temperature-adjusted softmax class scores for a single text input using the PromptGuard model', 'compute jailbreak scores for a list of texts with chunking and parallel batch processing', 'process a batch of texts through the PromptGuard model and return class probabilities', 'evaluate a single text string for embedded instructions from third party inputs', 'batch evaluate a list of texts for jailbreak scores with chunking and parallel processing', 'batch evaluate a list of texts for indirect injection scores with chunking and parallel processing']
```

Usage

```
{'load_promptguard_model': 'load the PromptGuard 1 model and tokenizer from Hugging Face for prompt injection detection', 'get_jailbreak_score': 'evaluate a single text string for malicious jailbreak or prompt injection probability', 'get_indirect_injection_score': 'evaluate a single text string for embedded instructions from third party inputs', 'get_jailbreak_scores_for_texts': 'batch evaluate a list of texts for jailbreak scores with chunking and parallel processing', 'get_indirect_injection_scores_for_texts': 'batch evaluate a list of texts for indirect injection scores with chunking and parallel processing'}
```

