# Agent Python Tools

- repo: facebookresearch/layerskip
- repo_uri: https://github.com/facebookresearch/layerskip

## File: facebookresearch_layerskip/tests/test_autoregressive_generator.py

Prompts

```
['test the AutoRegressiveGenerationStrategy to halt token generation early using a custom stopping criteria lambda', 'test the AutoRegressiveGenerationStrategy to apply custom logit processors during autoregressive token generation', 'run the pytest fixture to create a LlamaForCausalLM model, tokenizer, and GenerationConfig for testing', 'test the generate_token_ids method with input token IDs, EOS tokens, and a GenerationConfig', 'review the GenerationConfig class to understand how max_steps controls the number of generation steps', 'test the _make_causal_mask function to create lower triangular attention masks with past key value support', 'test the _expand_mask function to expand attention masks for multi-head attention shape requirements', 'test the _prepare_decoder_attention_mask function to combine causal and attention masks for decoder input', 'test the top_k_top_p_filtering function to filter logits using top-k and top-p sampling strategies', 'test the decode_next_token function to decode next tokens using argmax or probabilistic sampling', 'test the SelfSpeculativeGenerationStrategy single_step_speculation method for EOS token handling', 'test the generate_token_ids method with custom logits processors during token generation', 'test the GenerationConfig class with max_steps, exit_layer, and num_speculations parameters', 'test the model_and_config pytest fixture that loads a causal LM model and tokenizer', 'test that speculation matches are less than or equal to total speculations', 'test the SpeculativeTextStreamer put method in non-blocking mode to verify threading is used', 'test the SpeculativeTextStreamer thread safety by calling put multiple times concurrently', 'test the SpeculativeTextStreamer put method in blocking mode to verify tokenizer decode is called', 'test the SpeculativeTextStreamer delete method to verify tokens are removed from the text cache', 'test the SpeculativeTextStreamer put method with draft and non-draft token handling']
```

Usage

```
{'test_generate_token_ids_with_stopping_criteria': 'test the AutoRegressiveGenerationStrategy to halt token generation early using a custom stopping criteria lambda', 'test_generate_token_ids_with_logit_processors': 'test the AutoRegressiveGenerationStrategy to apply custom logit processors during autoregressive token generation', 'run_model_and_config_fixture': 'run the pytest fixture to create a LlamaForCausalLM model, tokenizer, and GenerationConfig for testing', 'test_AutoRegressiveGenerationStrategy_generate_token_ids': 'test the generate_token_ids method with input token IDs, EOS tokens, and a GenerationConfig', 'review_GenerationConfig_max_steps': 'review the GenerationConfig class to understand how max_steps controls the number of generation steps'}
```

## File: facebookresearch_layerskip/tests/test_llama_model_utils.py

Prompts

```
['test the AutoRegressiveGenerationStrategy to halt token generation early using a custom stopping criteria lambda', 'test the AutoRegressiveGenerationStrategy to apply custom logit processors during autoregressive token generation', 'run the pytest fixture to create a LlamaForCausalLM model, tokenizer, and GenerationConfig for testing', 'test the generate_token_ids method with input token IDs, EOS tokens, and a GenerationConfig', 'review the GenerationConfig class to understand how max_steps controls the number of generation steps', 'test the _make_causal_mask function to create lower triangular attention masks with past key value support', 'test the _expand_mask function to expand attention masks for multi-head attention shape requirements', 'test the _prepare_decoder_attention_mask function to combine causal and attention masks for decoder input', 'test the top_k_top_p_filtering function to filter logits using top-k and top-p sampling strategies', 'test the decode_next_token function to decode next tokens using argmax or probabilistic sampling', 'test the SelfSpeculativeGenerationStrategy single_step_speculation method for EOS token handling', 'test the generate_token_ids method with custom logits processors during token generation', 'test the GenerationConfig class with max_steps, exit_layer, and num_speculations parameters', 'test the model_and_config pytest fixture that loads a causal LM model and tokenizer', 'test that speculation matches are less than or equal to total speculations', 'test the SpeculativeTextStreamer put method in non-blocking mode to verify threading is used', 'test the SpeculativeTextStreamer thread safety by calling put multiple times concurrently', 'test the SpeculativeTextStreamer put method in blocking mode to verify tokenizer decode is called', 'test the SpeculativeTextStreamer delete method to verify tokens are removed from the text cache', 'test the SpeculativeTextStreamer put method with draft and non-draft token handling']
```

Usage

```
{'test_make_causal_mask': 'test the _make_causal_mask function to create lower triangular attention masks with past key value support', 'test_expand_mask': 'test the _expand_mask function to expand attention masks for multi-head attention shape requirements', 'test_prepare_decoder_attention_mask': 'test the _prepare_decoder_attention_mask function to combine causal and attention masks for decoder input', 'test_top_k_top_p_filtering': 'test the top_k_top_p_filtering function to filter logits using top-k and top-p sampling strategies', 'test_decode_next_token': 'test the decode_next_token function to decode next tokens using argmax or probabilistic sampling'}
```

## File: facebookresearch_layerskip/tests/test_self_speculation_generator.py

Prompts

```
['test the AutoRegressiveGenerationStrategy to halt token generation early using a custom stopping criteria lambda', 'test the AutoRegressiveGenerationStrategy to apply custom logit processors during autoregressive token generation', 'run the pytest fixture to create a LlamaForCausalLM model, tokenizer, and GenerationConfig for testing', 'test the generate_token_ids method with input token IDs, EOS tokens, and a GenerationConfig', 'review the GenerationConfig class to understand how max_steps controls the number of generation steps', 'test the _make_causal_mask function to create lower triangular attention masks with past key value support', 'test the _expand_mask function to expand attention masks for multi-head attention shape requirements', 'test the _prepare_decoder_attention_mask function to combine causal and attention masks for decoder input', 'test the top_k_top_p_filtering function to filter logits using top-k and top-p sampling strategies', 'test the decode_next_token function to decode next tokens using argmax or probabilistic sampling', 'test the SelfSpeculativeGenerationStrategy single_step_speculation method for EOS token handling', 'test the generate_token_ids method with custom logits processors during token generation', 'test the GenerationConfig class with max_steps, exit_layer, and num_speculations parameters', 'test the model_and_config pytest fixture that loads a causal LM model and tokenizer', 'test that speculation matches are less than or equal to total speculations', 'test the SpeculativeTextStreamer put method in non-blocking mode to verify threading is used', 'test the SpeculativeTextStreamer thread safety by calling put multiple times concurrently', 'test the SpeculativeTextStreamer put method in blocking mode to verify tokenizer decode is called', 'test the SpeculativeTextStreamer delete method to verify tokens are removed from the text cache', 'test the SpeculativeTextStreamer put method with draft and non-draft token handling']
```

Usage

```
{'test_single_step_speculation': 'test the SelfSpeculativeGenerationStrategy single_step_speculation method for EOS token handling', 'test_generate_token_ids': 'test the generate_token_ids method with custom logits processors during token generation', 'test_generation_config': 'test the GenerationConfig class with max_steps, exit_layer, and num_speculations parameters', 'test_model_fixture': 'test the model_and_config pytest fixture that loads a causal LM model and tokenizer', 'test_speculation_matches': 'test that speculation matches are less than or equal to total speculations'}
```

## File: facebookresearch_layerskip/tests/test_speculative_streamer.py

Prompts

```
['test the AutoRegressiveGenerationStrategy to halt token generation early using a custom stopping criteria lambda', 'test the AutoRegressiveGenerationStrategy to apply custom logit processors during autoregressive token generation', 'run the pytest fixture to create a LlamaForCausalLM model, tokenizer, and GenerationConfig for testing', 'test the generate_token_ids method with input token IDs, EOS tokens, and a GenerationConfig', 'review the GenerationConfig class to understand how max_steps controls the number of generation steps', 'test the _make_causal_mask function to create lower triangular attention masks with past key value support', 'test the _expand_mask function to expand attention masks for multi-head attention shape requirements', 'test the _prepare_decoder_attention_mask function to combine causal and attention masks for decoder input', 'test the top_k_top_p_filtering function to filter logits using top-k and top-p sampling strategies', 'test the decode_next_token function to decode next tokens using argmax or probabilistic sampling', 'test the SelfSpeculativeGenerationStrategy single_step_speculation method for EOS token handling', 'test the generate_token_ids method with custom logits processors during token generation', 'test the GenerationConfig class with max_steps, exit_layer, and num_speculations parameters', 'test the model_and_config pytest fixture that loads a causal LM model and tokenizer', 'test that speculation matches are less than or equal to total speculations', 'test the SpeculativeTextStreamer put method in non-blocking mode to verify threading is used', 'test the SpeculativeTextStreamer thread safety by calling put multiple times concurrently', 'test the SpeculativeTextStreamer put method in blocking mode to verify tokenizer decode is called', 'test the SpeculativeTextStreamer delete method to verify tokens are removed from the text cache', 'test the SpeculativeTextStreamer put method with draft and non-draft token handling']
```

Usage

```
{'test_put_tokens_non_blocking': 'test the SpeculativeTextStreamer put method in non-blocking mode to verify threading is used', 'test_thread_safety': 'test the SpeculativeTextStreamer thread safety by calling put multiple times concurrently', 'test_put_tokens_blocking': 'test the SpeculativeTextStreamer put method in blocking mode to verify tokenizer decode is called', 'test_delete_tokens': 'test the SpeculativeTextStreamer delete method to verify tokens are removed from the text cache', 'test_draft_handling': 'test the SpeculativeTextStreamer put method with draft and non-draft token handling'}
```

