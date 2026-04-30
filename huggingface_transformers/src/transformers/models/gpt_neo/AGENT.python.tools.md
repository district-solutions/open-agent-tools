# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/gpt_neo/configuration_gpt_neo.py

Prompts

```
['create a GPTNeoConfig instance with custom model parameters like hidden_size and num_layers', 'validate that GPTNeoConfig attention_layers length matches num_layers', 'expand GPTNeoConfig attention_types into a flat list of per-layer attention types', 'run a custom torch.Tensor.unfold implementation for ONNX export compatibility', 'compute block length and number of blocks for GPTNeo local attention window', 'convert a TensorFlow GPT-Neo checkpoint to a PyTorch model using the config file and output path', 'load TensorFlow checkpoint weights into a PyTorch GPT-Neo model with name mapping and transpose handling', 'build a GPTNeoConfig from a JSON config file with n_embd, n_layer, n_head, and attention_types fields', 'run the CLI script to convert a mesh TensorFlow GPT-Neo checkpoint to PyTorch with required args', 'initialize the final linear output layer using the word embedding weights from the model', 'build a GPT-Neo causal language model for autoregressive text generation with optional flash attention', 'create a GPT-Neo sequence classification model for text categorization or regression', 'create a GPT-Neo token classification model for named entity recognition or part-of-speech tagging', 'create a GPT-Neo question answering model that predicts start and end positions of answers in context', 'build the base GPT-Neo transformer model with causal self-attention and local sliding window attention']
```

Usage

```
{'create_gpt_neo_config': 'create a GPTNeoConfig instance with custom model parameters like hidden_size and num_layers', 'validate_gpt_neo_config': 'validate that GPTNeoConfig attention_layers length matches num_layers', 'expand_attention_types': 'expand GPTNeoConfig attention_types into a flat list of per-layer attention types', 'custom_unfold_tensor': 'run a custom torch.Tensor.unfold implementation for ONNX export compatibility', 'custom_get_block_length': 'compute block length and number of blocks for GPTNeo local attention window'}
```

## File: huggingface_transformers/src/transformers/models/gpt_neo/convert_gpt_neo_mesh_tf_to_pytorch.py

Prompts

```
['create a GPTNeoConfig instance with custom model parameters like hidden_size and num_layers', 'validate that GPTNeoConfig attention_layers length matches num_layers', 'expand GPTNeoConfig attention_types into a flat list of per-layer attention types', 'run a custom torch.Tensor.unfold implementation for ONNX export compatibility', 'compute block length and number of blocks for GPTNeo local attention window', 'convert a TensorFlow GPT-Neo checkpoint to a PyTorch model using the config file and output path', 'load TensorFlow checkpoint weights into a PyTorch GPT-Neo model with name mapping and transpose handling', 'build a GPTNeoConfig from a JSON config file with n_embd, n_layer, n_head, and attention_types fields', 'run the CLI script to convert a mesh TensorFlow GPT-Neo checkpoint to PyTorch with required args', 'initialize the final linear output layer using the word embedding weights from the model', 'build a GPT-Neo causal language model for autoregressive text generation with optional flash attention', 'create a GPT-Neo sequence classification model for text categorization or regression', 'create a GPT-Neo token classification model for named entity recognition or part-of-speech tagging', 'create a GPT-Neo question answering model that predicts start and end positions of answers in context', 'build the base GPT-Neo transformer model with causal self-attention and local sliding window attention']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow GPT-Neo checkpoint to a PyTorch model using the config file and output path', 'load_tf_weights_in_gpt_neo': 'load TensorFlow checkpoint weights into a PyTorch GPT-Neo model with name mapping and transpose handling', 'build_gpt_neo_config_from_json': 'build a GPTNeoConfig from a JSON config file with n_embd, n_layer, n_head, and attention_types fields', 'run_tf_to_pytorch_conversion_cli': 'run the CLI script to convert a mesh TensorFlow GPT-Neo checkpoint to PyTorch with required args', 'set_output_embeddings_from_weights': 'initialize the final linear output layer using the word embedding weights from the model'}
```

## File: huggingface_transformers/src/transformers/models/gpt_neo/modeling_gpt_neo.py

Prompts

```
['create a GPTNeoConfig instance with custom model parameters like hidden_size and num_layers', 'validate that GPTNeoConfig attention_layers length matches num_layers', 'expand GPTNeoConfig attention_types into a flat list of per-layer attention types', 'run a custom torch.Tensor.unfold implementation for ONNX export compatibility', 'compute block length and number of blocks for GPTNeo local attention window', 'convert a TensorFlow GPT-Neo checkpoint to a PyTorch model using the config file and output path', 'load TensorFlow checkpoint weights into a PyTorch GPT-Neo model with name mapping and transpose handling', 'build a GPTNeoConfig from a JSON config file with n_embd, n_layer, n_head, and attention_types fields', 'run the CLI script to convert a mesh TensorFlow GPT-Neo checkpoint to PyTorch with required args', 'initialize the final linear output layer using the word embedding weights from the model', 'build a GPT-Neo causal language model for autoregressive text generation with optional flash attention', 'create a GPT-Neo sequence classification model for text categorization or regression', 'create a GPT-Neo token classification model for named entity recognition or part-of-speech tagging', 'create a GPT-Neo question answering model that predicts start and end positions of answers in context', 'build the base GPT-Neo transformer model with causal self-attention and local sliding window attention']
```

Usage

```
{'build_gpt_neo_causal_lm': 'build a GPT-Neo causal language model for autoregressive text generation with optional flash attention', 'create_gpt_neo_sequence_classifier': 'create a GPT-Neo sequence classification model for text categorization or regression', 'create_gpt_neo_token_classifier': 'create a GPT-Neo token classification model for named entity recognition or part-of-speech tagging', 'create_gpt_neo_question_answering': 'create a GPT-Neo question answering model that predicts start and end positions of answers in context', 'build_gpt_neo_base_model': 'build the base GPT-Neo transformer model with causal self-attention and local sliding window attention'}
```

