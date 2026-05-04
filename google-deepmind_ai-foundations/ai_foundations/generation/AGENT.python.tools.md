# Agent Python Tools

- repo: google-deepmind/ai-foundations
- repo_uri: https://github.com/google-deepmind/ai-foundations

## File: google-deepmind_ai-foundations/ai_foundations/generation/gemma.py

Prompts

```
['generate text from a Gemma model given an input prompt with random or greedy sampling', 'sample text from a Gemma model using greedy sampling to pick the most likely next token', 'extract layer-wise attention weights and QKV matrices from a Gemma model for visualization', 'get the next token logits probability distribution from a Gemma model given input text', 'load a Gemma-1B or Gemma-4B model with tokenizer and parameters for text generation', 'generate text from a starting prompt using a trained Keras model with random or greedy sampling', 'sample a token index from a probability distribution using JAX random choice with a PRNG key', 'select the highest probability token index from a predicted next token probability distribution', 'generate text using greedy decoding mode to always pick the most likely next token', 'generate text using random sampling mode to produce diverse outputs from a Keras model', 'load the Gemma-1B model with its tokenizer and pre-trained parameters', 'load the Gemma-4B model with its tokenizer and pre-trained parameters', 'load the Gemma-1B-AttentionWeight model variant with its tokenizer and parameters', 'review the load_gemma function to understand supported model names and return types', 'test the load_gemma function with an unsupported model name to verify ValueError is raised']
```

Usage

```
{'generate_text_gemma': 'generate text from a Gemma model given an input prompt with random or greedy sampling', 'sample_greedy_gemma': 'sample text from a Gemma model using greedy sampling to pick the most likely next token', 'extract_attention_weights': 'extract layer-wise attention weights and QKV matrices from a Gemma model for visualization', 'get_next_token_logits': 'get the next token logits probability distribution from a Gemma model given input text', 'load_gemma_model': 'load a Gemma-1B or Gemma-4B model with tokenizer and parameters for text generation'}
```

## File: google-deepmind_ai-foundations/ai_foundations/generation/generate.py

Prompts

```
['generate text from a Gemma model given an input prompt with random or greedy sampling', 'sample text from a Gemma model using greedy sampling to pick the most likely next token', 'extract layer-wise attention weights and QKV matrices from a Gemma model for visualization', 'get the next token logits probability distribution from a Gemma model given input text', 'load a Gemma-1B or Gemma-4B model with tokenizer and parameters for text generation', 'generate text from a starting prompt using a trained Keras model with random or greedy sampling', 'sample a token index from a probability distribution using JAX random choice with a PRNG key', 'select the highest probability token index from a predicted next token probability distribution', 'generate text using greedy decoding mode to always pick the most likely next token', 'generate text using random sampling mode to produce diverse outputs from a Keras model', 'load the Gemma-1B model with its tokenizer and pre-trained parameters', 'load the Gemma-4B model with its tokenizer and pre-trained parameters', 'load the Gemma-1B-AttentionWeight model variant with its tokenizer and parameters', 'review the load_gemma function to understand supported model names and return types', 'test the load_gemma function with an unsupported model name to verify ValueError is raised']
```

Usage

```
{'generate_text_with_prompt': 'generate text from a starting prompt using a trained Keras model with random or greedy sampling', 'sample_token_from_probs': 'sample a token index from a probability distribution using JAX random choice with a PRNG key', 'greedy_decode_token': 'select the highest probability token index from a predicted next token probability distribution', 'generate_text_greedy_mode': 'generate text using greedy decoding mode to always pick the most likely next token', 'generate_text_random_mode': 'generate text using random sampling mode to produce diverse outputs from a Keras model'}
```

## File: google-deepmind_ai-foundations/ai_foundations/generation/loaders.py

Prompts

```
['generate text from a Gemma model given an input prompt with random or greedy sampling', 'sample text from a Gemma model using greedy sampling to pick the most likely next token', 'extract layer-wise attention weights and QKV matrices from a Gemma model for visualization', 'get the next token logits probability distribution from a Gemma model given input text', 'load a Gemma-1B or Gemma-4B model with tokenizer and parameters for text generation', 'generate text from a starting prompt using a trained Keras model with random or greedy sampling', 'sample a token index from a probability distribution using JAX random choice with a PRNG key', 'select the highest probability token index from a predicted next token probability distribution', 'generate text using greedy decoding mode to always pick the most likely next token', 'generate text using random sampling mode to produce diverse outputs from a Keras model', 'load the Gemma-1B model with its tokenizer and pre-trained parameters', 'load the Gemma-4B model with its tokenizer and pre-trained parameters', 'load the Gemma-1B-AttentionWeight model variant with its tokenizer and parameters', 'review the load_gemma function to understand supported model names and return types', 'test the load_gemma function with an unsupported model name to verify ValueError is raised']
```

Usage

```
{'load_gemma_1b': 'load the Gemma-1B model with its tokenizer and pre-trained parameters', 'load_gemma_4b': 'load the Gemma-4B model with its tokenizer and pre-trained parameters', 'load_gemma_attention_weight': 'load the Gemma-1B-AttentionWeight model variant with its tokenizer and parameters', 'review_load_gemma': 'review the load_gemma function to understand supported model names and return types', 'test_load_gemma_unsupported': 'test the load_gemma function with an unsupported model name to verify ValueError is raised'}
```

