# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/gm/tests/examples_test.py

Prompts

```
['test the gemma seq2seq example configuration by resolving the trainer and validating context specs with mocked data', 'test the seq2seq get_config function to retrieve a default training configuration for gemma models', 'test the DummyGemma model class by configuring it with batch input tokens for unit testing', 'test the konfig resolve function to build a trainer from a seq2seq configuration object', 'test the tensorflow_datasets mock_data context manager to generate 10 synthetic examples for validation', 'test the ChatSampler by loading Gemma3 4B model params and chatting with a prompt', 'test the ChatSampler stop_tokens feature to halt generation after a specific token', 'run a multi-turn chat using gm.text.ChatSampler with the Gemma3 4B model', 'load Gemma3 4B model parameters using gm.ckpts.load_params with CheckpointPath', 'create a ChatSampler instance with custom stop_tokens to control generation length']
```

Usage

```
{'test_examples': 'test the gemma seq2seq example configuration by resolving the trainer and validating context specs with mocked data', 'test_get_config': 'test the seq2seq get_config function to retrieve a default training configuration for gemma models', 'test_dummy_gemma': 'test the DummyGemma model class by configuring it with batch input tokens for unit testing', 'test_konfig_resolve': 'test the konfig resolve function to build a trainer from a seq2seq configuration object', 'test_mock_data': 'test the tensorflow_datasets mock_data context manager to generate 10 synthetic examples for validation'}
```

## File: google-deepmind_gemma/gemma/gm/tests/sampler_e2e_test.py

Prompts

```
['test the gemma seq2seq example configuration by resolving the trainer and validating context specs with mocked data', 'test the seq2seq get_config function to retrieve a default training configuration for gemma models', 'test the DummyGemma model class by configuring it with batch input tokens for unit testing', 'test the konfig resolve function to build a trainer from a seq2seq configuration object', 'test the tensorflow_datasets mock_data context manager to generate 10 synthetic examples for validation', 'test the ChatSampler by loading Gemma3 4B model params and chatting with a prompt', 'test the ChatSampler stop_tokens feature to halt generation after a specific token', 'run a multi-turn chat using gm.text.ChatSampler with the Gemma3 4B model', 'load Gemma3 4B model parameters using gm.ckpts.load_params with CheckpointPath', 'create a ChatSampler instance with custom stop_tokens to control generation length']
```

Usage

```
{'test_sampler_chat': 'test the ChatSampler by loading Gemma3 4B model params and chatting with a prompt', 'test_sampler_stop_token': 'test the ChatSampler stop_tokens feature to halt generation after a specific token', 'run_chat_with_gemma': 'run a multi-turn chat using gm.text.ChatSampler with the Gemma3 4B model', 'load_gemma_checkpoint': 'load Gemma3 4B model parameters using gm.ckpts.load_params with CheckpointPath', 'create_chatsampler_with_stop_tokens': 'create a ChatSampler instance with custom stop_tokens to control generation length'}
```

