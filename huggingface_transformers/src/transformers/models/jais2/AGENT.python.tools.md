# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/jais2/configuration_jais2.py

Prompts

```
['create a Jais2Config instance with default model configuration for the Jais-2-8B-Chat model', 'build a Jais2Config from a dictionary of model parameters including hidden_size, num_hidden_layers, and vocab_size', 'validate the Jais2Config architecture to ensure hidden_size is a multiple of num_attention_heads', 'initialize a Jais2Model with a Jais2Config for the jais2-7b style configuration', 'access the model configuration from an instantiated Jais2Model via model.config', 'build a Jais2ForCausalLM model from a Jais2Config for autoregressive text generation', 'run a forward pass on Jais2Model with input_ids and attention_mask to get hidden states', 'generate text from Jais2ForCausalLM using model.generate with a tokenizer prompt input', 'train Jais2ForCausalLM by passing input_ids and labels through forward for loss computation', 'create a Jais2Config instance with custom vocab_size, hidden_size, and attention parameters for the Jais-2 model', 'build a Jais2ForCausalLM model from pretrained checkpoint inceptionai/Jais-2-8B-Chat for causal language generation', 'run the Jais2ForCausalLM forward pass and generate text output from tokenized input prompts', 'create a Jais2Model with LayerNorm output normalization and Jais2DecoderLayer blocks for feature extraction', 'review the Jais2DecoderLayer that extends LlamaDecoderLayer with input and post-attention LayerNorm layers']
```

Usage

```
{'create_config_jais2': 'create a Jais2Config instance with default model configuration for the Jais-2-8B-Chat model', 'build_config_from_dict': 'build a Jais2Config from a dictionary of model parameters including hidden_size, num_hidden_layers, and vocab_size', 'validate_jais2_architecture': 'validate the Jais2Config architecture to ensure hidden_size is a multiple of num_attention_heads', 'initialize_jais2_model': 'initialize a Jais2Model with a Jais2Config for the jais2-7b style configuration', 'access_model_config': 'access the model configuration from an instantiated Jais2Model via model.config'}
```

## File: huggingface_transformers/src/transformers/models/jais2/modeling_jais2.py

Prompts

```
['create a Jais2Config instance with default model configuration for the Jais-2-8B-Chat model', 'build a Jais2Config from a dictionary of model parameters including hidden_size, num_hidden_layers, and vocab_size', 'validate the Jais2Config architecture to ensure hidden_size is a multiple of num_attention_heads', 'initialize a Jais2Model with a Jais2Config for the jais2-7b style configuration', 'access the model configuration from an instantiated Jais2Model via model.config', 'build a Jais2ForCausalLM model from a Jais2Config for autoregressive text generation', 'run a forward pass on Jais2Model with input_ids and attention_mask to get hidden states', 'generate text from Jais2ForCausalLM using model.generate with a tokenizer prompt input', 'train Jais2ForCausalLM by passing input_ids and labels through forward for loss computation', 'create a Jais2Config instance with custom vocab_size, hidden_size, and attention parameters for the Jais-2 model', 'build a Jais2ForCausalLM model from pretrained checkpoint inceptionai/Jais-2-8B-Chat for causal language generation', 'run the Jais2ForCausalLM forward pass and generate text output from tokenized input prompts', 'create a Jais2Model with LayerNorm output normalization and Jais2DecoderLayer blocks for feature extraction', 'review the Jais2DecoderLayer that extends LlamaDecoderLayer with input and post-attention LayerNorm layers']
```

Usage

```
{'build_causal_lm_model': 'build a Jais2ForCausalLM model from a Jais2Config for autoregressive text generation', 'initialize_jais2_model': 'initialize a Jais2Model with Jais2Config to create the base transformer encoder stack', 'run_forward_pass': 'run a forward pass on Jais2Model with input_ids and attention_mask to get hidden states', 'generate_text': 'generate text from Jais2ForCausalLM using model.generate with a tokenizer prompt input', 'train_with_labels': 'train Jais2ForCausalLM by passing input_ids and labels through forward for loss computation'}
```

## File: huggingface_transformers/src/transformers/models/jais2/modular_jais2.py

Prompts

```
['create a Jais2Config instance with default model configuration for the Jais-2-8B-Chat model', 'build a Jais2Config from a dictionary of model parameters including hidden_size, num_hidden_layers, and vocab_size', 'validate the Jais2Config architecture to ensure hidden_size is a multiple of num_attention_heads', 'initialize a Jais2Model with a Jais2Config for the jais2-7b style configuration', 'access the model configuration from an instantiated Jais2Model via model.config', 'build a Jais2ForCausalLM model from a Jais2Config for autoregressive text generation', 'run a forward pass on Jais2Model with input_ids and attention_mask to get hidden states', 'generate text from Jais2ForCausalLM using model.generate with a tokenizer prompt input', 'train Jais2ForCausalLM by passing input_ids and labels through forward for loss computation', 'create a Jais2Config instance with custom vocab_size, hidden_size, and attention parameters for the Jais-2 model', 'build a Jais2ForCausalLM model from pretrained checkpoint inceptionai/Jais-2-8B-Chat for causal language generation', 'run the Jais2ForCausalLM forward pass and generate text output from tokenized input prompts', 'create a Jais2Model with LayerNorm output normalization and Jais2DecoderLayer blocks for feature extraction', 'review the Jais2DecoderLayer that extends LlamaDecoderLayer with input and post-attention LayerNorm layers']
```

Usage

```
{'create_Jais2Config': 'create a Jais2Config instance with custom vocab_size, hidden_size, and attention parameters for the Jais-2 model', 'build_Jais2ForCausalLM': 'build a Jais2ForCausalLM model from pretrained checkpoint inceptionai/Jais-2-8B-Chat for causal language generation', 'run_Jais2_generate': 'run the Jais2ForCausalLM forward pass and generate text output from tokenized input prompts', 'create_Jais2Model': 'create a Jais2Model with LayerNorm output normalization and Jais2DecoderLayer blocks for feature extraction', 'review_Jais2DecoderLayer': 'review the Jais2DecoderLayer that extends LlamaDecoderLayer with input and post-attention LayerNorm layers'}
```

