# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/test_agents/counter.py

Prompts

```
['build a CounterAgent that counts unique utterances seen during ParlAI dialogue interactions', 'create a TimesSeenMetric to track the max number of times any example was seen', 'create a UniqueMetric to count the number of unique utterances in a Counter', 'test the CounterAgent batch_act method to count observations and filter padding messages', 'review the CounterAgent report method to get num_pad, unique, and times_seen metrics', 'build a NullAgent that returns an empty torch.nn.Module via build_model', 'build a NullAgent that returns an NLLLoss criterion via build_criterion', 'run the NullAgent train_step method which returns an empty Output object', 'run the NullAgent eval_step method which returns an empty Output object', 'create a NullAgent instance for preprocessing-only use without training or evaluation', 'create a MockDict agent that maps special tokens to fixed indices and increments for unknown tokens', 'test the MockDict txt2vec method to convert space-separated text into a list of token indices', 'build a MockTorchAgent that uses MockDict and returns training and evaluation confirmation messages', 'test the SilentTorchAgent that returns null Output for both train_step and eval_step calls', 'review the MockTrainUpdatesAgent to simulate gradient accumulation and track training update counts', 'build a transformer generator agent that prepends prefix tokens to all generated text', 'test the get_prefix_tokens method to verify it returns correct prefix tokens for a batch', 'create a batch of prefix tokens from PREFIX_TEXT for all items in the batch', 'review the TransformerGeneratorPrefixAgent class and its get_prefix_tokens override for prefix token generation', 'refactor the get_prefix_tokens method to support dynamic prefix text instead of hardcoded PREFIX_TEXT', 'build a UnigramModel with a dictionary to create a unigram distribution generator for testing', 'create a UnigramEncoder module that returns None in its forward pass for testing', 'create a UnigramDecoder module that unsqueezes input and returns it with None state', 'test the UnigramAgent by building it as a TorchGeneratorAgent subclass for quick optimization', 'review the UnigramModel output method to expand parameters across desired tensor dimensions']
```

Usage

```
{'build_counter_agent': 'build a CounterAgent that counts unique utterances seen during ParlAI dialogue interactions', 'create_times_seen_metric': 'create a TimesSeenMetric to track the max number of times any example was seen', 'create_unique_metric': 'create a UniqueMetric to count the number of unique utterances in a Counter', 'test_counter_agent_batch_act': 'test the CounterAgent batch_act method to count observations and filter padding messages', 'review_counter_agent_report': 'review the CounterAgent report method to get num_pad, unique, and times_seen metrics'}
```

## File: facebookresearch_parlai/parlai/agents/test_agents/null.py

Prompts

```
['build a CounterAgent that counts unique utterances seen during ParlAI dialogue interactions', 'create a TimesSeenMetric to track the max number of times any example was seen', 'create a UniqueMetric to count the number of unique utterances in a Counter', 'test the CounterAgent batch_act method to count observations and filter padding messages', 'review the CounterAgent report method to get num_pad, unique, and times_seen metrics', 'build a NullAgent that returns an empty torch.nn.Module via build_model', 'build a NullAgent that returns an NLLLoss criterion via build_criterion', 'run the NullAgent train_step method which returns an empty Output object', 'run the NullAgent eval_step method which returns an empty Output object', 'create a NullAgent instance for preprocessing-only use without training or evaluation', 'create a MockDict agent that maps special tokens to fixed indices and increments for unknown tokens', 'test the MockDict txt2vec method to convert space-separated text into a list of token indices', 'build a MockTorchAgent that uses MockDict and returns training and evaluation confirmation messages', 'test the SilentTorchAgent that returns null Output for both train_step and eval_step calls', 'review the MockTrainUpdatesAgent to simulate gradient accumulation and track training update counts', 'build a transformer generator agent that prepends prefix tokens to all generated text', 'test the get_prefix_tokens method to verify it returns correct prefix tokens for a batch', 'create a batch of prefix tokens from PREFIX_TEXT for all items in the batch', 'review the TransformerGeneratorPrefixAgent class and its get_prefix_tokens override for prefix token generation', 'refactor the get_prefix_tokens method to support dynamic prefix text instead of hardcoded PREFIX_TEXT', 'build a UnigramModel with a dictionary to create a unigram distribution generator for testing', 'create a UnigramEncoder module that returns None in its forward pass for testing', 'create a UnigramDecoder module that unsqueezes input and returns it with None state', 'test the UnigramAgent by building it as a TorchGeneratorAgent subclass for quick optimization', 'review the UnigramModel output method to expand parameters across desired tensor dimensions']
```

Usage

```
{'build_nullagent_model': 'build a NullAgent that returns an empty torch.nn.Module via build_model', 'build_nullagent_criterion': 'build a NullAgent that returns an NLLLoss criterion via build_criterion', 'run_nullagent_train_step': 'run the NullAgent train_step method which returns an empty Output object', 'run_nullagent_eval_step': 'run the NullAgent eval_step method which returns an empty Output object', 'create_nullagent_for_preprocessing': 'create a NullAgent instance for preprocessing-only use without training or evaluation'}
```

## File: facebookresearch_parlai/parlai/agents/test_agents/test_agents.py

Prompts

```
['build a CounterAgent that counts unique utterances seen during ParlAI dialogue interactions', 'create a TimesSeenMetric to track the max number of times any example was seen', 'create a UniqueMetric to count the number of unique utterances in a Counter', 'test the CounterAgent batch_act method to count observations and filter padding messages', 'review the CounterAgent report method to get num_pad, unique, and times_seen metrics', 'build a NullAgent that returns an empty torch.nn.Module via build_model', 'build a NullAgent that returns an NLLLoss criterion via build_criterion', 'run the NullAgent train_step method which returns an empty Output object', 'run the NullAgent eval_step method which returns an empty Output object', 'create a NullAgent instance for preprocessing-only use without training or evaluation', 'create a MockDict agent that maps special tokens to fixed indices and increments for unknown tokens', 'test the MockDict txt2vec method to convert space-separated text into a list of token indices', 'build a MockTorchAgent that uses MockDict and returns training and evaluation confirmation messages', 'test the SilentTorchAgent that returns null Output for both train_step and eval_step calls', 'review the MockTrainUpdatesAgent to simulate gradient accumulation and track training update counts', 'build a transformer generator agent that prepends prefix tokens to all generated text', 'test the get_prefix_tokens method to verify it returns correct prefix tokens for a batch', 'create a batch of prefix tokens from PREFIX_TEXT for all items in the batch', 'review the TransformerGeneratorPrefixAgent class and its get_prefix_tokens override for prefix token generation', 'refactor the get_prefix_tokens method to support dynamic prefix text instead of hardcoded PREFIX_TEXT', 'build a UnigramModel with a dictionary to create a unigram distribution generator for testing', 'create a UnigramEncoder module that returns None in its forward pass for testing', 'create a UnigramDecoder module that unsqueezes input and returns it with None state', 'test the UnigramAgent by building it as a TorchGeneratorAgent subclass for quick optimization', 'review the UnigramModel output method to expand parameters across desired tensor dimensions']
```

Usage

```
{'create_mock_dict_agent': 'create a MockDict agent that maps special tokens to fixed indices and increments for unknown tokens', 'test_mock_dict_txt2vec': 'test the MockDict txt2vec method to convert space-separated text into a list of token indices', 'build_mock_torch_agent': 'build a MockTorchAgent that uses MockDict and returns training and evaluation confirmation messages', 'test_silent_torch_agent': 'test the SilentTorchAgent that returns null Output for both train_step and eval_step calls', 'review_mock_train_updates_agent': 'review the MockTrainUpdatesAgent to simulate gradient accumulation and track training update counts'}
```

## File: facebookresearch_parlai/parlai/agents/test_agents/transformer_generator_prefix.py

Prompts

```
['build a CounterAgent that counts unique utterances seen during ParlAI dialogue interactions', 'create a TimesSeenMetric to track the max number of times any example was seen', 'create a UniqueMetric to count the number of unique utterances in a Counter', 'test the CounterAgent batch_act method to count observations and filter padding messages', 'review the CounterAgent report method to get num_pad, unique, and times_seen metrics', 'build a NullAgent that returns an empty torch.nn.Module via build_model', 'build a NullAgent that returns an NLLLoss criterion via build_criterion', 'run the NullAgent train_step method which returns an empty Output object', 'run the NullAgent eval_step method which returns an empty Output object', 'create a NullAgent instance for preprocessing-only use without training or evaluation', 'create a MockDict agent that maps special tokens to fixed indices and increments for unknown tokens', 'test the MockDict txt2vec method to convert space-separated text into a list of token indices', 'build a MockTorchAgent that uses MockDict and returns training and evaluation confirmation messages', 'test the SilentTorchAgent that returns null Output for both train_step and eval_step calls', 'review the MockTrainUpdatesAgent to simulate gradient accumulation and track training update counts', 'build a transformer generator agent that prepends prefix tokens to all generated text', 'test the get_prefix_tokens method to verify it returns correct prefix tokens for a batch', 'create a batch of prefix tokens from PREFIX_TEXT for all items in the batch', 'review the TransformerGeneratorPrefixAgent class and its get_prefix_tokens override for prefix token generation', 'refactor the get_prefix_tokens method to support dynamic prefix text instead of hardcoded PREFIX_TEXT', 'build a UnigramModel with a dictionary to create a unigram distribution generator for testing', 'create a UnigramEncoder module that returns None in its forward pass for testing', 'create a UnigramDecoder module that unsqueezes input and returns it with None state', 'test the UnigramAgent by building it as a TorchGeneratorAgent subclass for quick optimization', 'review the UnigramModel output method to expand parameters across desired tensor dimensions']
```

Usage

```
{'build_transformer_prefix_agent': 'build a transformer generator agent that prepends prefix tokens to all generated text', 'test_get_prefix_tokens': 'test the get_prefix_tokens method to verify it returns correct prefix tokens for a batch', 'create_prefix_token_batch': 'create a batch of prefix tokens from PREFIX_TEXT for all items in the batch', 'review_transformer_generator_prefix_agent': 'review the TransformerGeneratorPrefixAgent class and its get_prefix_tokens override for prefix token generation', 'refactor_get_prefix_tokens': 'refactor the get_prefix_tokens method to support dynamic prefix text instead of hardcoded PREFIX_TEXT'}
```

## File: facebookresearch_parlai/parlai/agents/test_agents/unigram.py

Prompts

```
['build a CounterAgent that counts unique utterances seen during ParlAI dialogue interactions', 'create a TimesSeenMetric to track the max number of times any example was seen', 'create a UniqueMetric to count the number of unique utterances in a Counter', 'test the CounterAgent batch_act method to count observations and filter padding messages', 'review the CounterAgent report method to get num_pad, unique, and times_seen metrics', 'build a NullAgent that returns an empty torch.nn.Module via build_model', 'build a NullAgent that returns an NLLLoss criterion via build_criterion', 'run the NullAgent train_step method which returns an empty Output object', 'run the NullAgent eval_step method which returns an empty Output object', 'create a NullAgent instance for preprocessing-only use without training or evaluation', 'create a MockDict agent that maps special tokens to fixed indices and increments for unknown tokens', 'test the MockDict txt2vec method to convert space-separated text into a list of token indices', 'build a MockTorchAgent that uses MockDict and returns training and evaluation confirmation messages', 'test the SilentTorchAgent that returns null Output for both train_step and eval_step calls', 'review the MockTrainUpdatesAgent to simulate gradient accumulation and track training update counts', 'build a transformer generator agent that prepends prefix tokens to all generated text', 'test the get_prefix_tokens method to verify it returns correct prefix tokens for a batch', 'create a batch of prefix tokens from PREFIX_TEXT for all items in the batch', 'review the TransformerGeneratorPrefixAgent class and its get_prefix_tokens override for prefix token generation', 'refactor the get_prefix_tokens method to support dynamic prefix text instead of hardcoded PREFIX_TEXT', 'build a UnigramModel with a dictionary to create a unigram distribution generator for testing', 'create a UnigramEncoder module that returns None in its forward pass for testing', 'create a UnigramDecoder module that unsqueezes input and returns it with None state', 'test the UnigramAgent by building it as a TorchGeneratorAgent subclass for quick optimization', 'review the UnigramModel output method to expand parameters across desired tensor dimensions']
```

Usage

```
{'build_unigram_model': 'build a UnigramModel with a dictionary to create a unigram distribution generator for testing', 'create_unigram_encoder': 'create a UnigramEncoder module that returns None in its forward pass for testing', 'create_unigram_decoder': 'create a UnigramDecoder module that unsqueezes input and returns it with None state', 'test_unigram_agent': 'test the UnigramAgent by building it as a TorchGeneratorAgent subclass for quick optimization', 'review_unigram_model_output': 'review the UnigramModel output method to expand parameters across desired tensor dimensions'}
```

