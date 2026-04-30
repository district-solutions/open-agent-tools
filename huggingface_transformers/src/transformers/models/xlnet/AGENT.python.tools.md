# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/xlnet/configuration_xlnet.py

Prompts

```
['create an XLNetConfig instance with default hyperparameters for model initialization', 'create an XLNetConfig with custom d_model, n_layer, n_head, and vocab_size for a modified XLNet model', 'test the XLNetConfig.validate_architecture method to verify d_model is divisible by n_head', 'review the XLNetConfig.max_position_embeddings property that returns -1 indicating no sequence length limit', 'summarize the XLNetConfig class attributes including d_model, n_layer, n_head, and attention settings', 'convert a TensorFlow XLNet checkpoint to a PyTorch model with optional finetuning task', 'build a mapping from TensorFlow XLNet weight names to PyTorch model parameters', 'load TensorFlow XLNet checkpoint weights into a PyTorch XLNet model', 'convert an XLNet TensorFlow checkpoint to PyTorch weights and config files', 'run the XLNet TF-to-PyTorch conversion script via command-line arguments', 'build an XLNet model with bidirectional relative attention and memory caching for sequence modeling', 'create an XLNet language model with a linear head for masked next-token prediction', 'run XLNet on GLUE tasks with sequence classification or regression head', 'test XLNet extractive QA with beam-search top-k start and end span prediction', 'summarize the XLNet relative attention mechanism with two-stream queries and positional encoding']
```

Usage

```
{'create_xlnet_config': 'create an XLNetConfig instance with default hyperparameters for model initialization', 'create_xlnet_config_custom': 'create an XLNetConfig with custom d_model, n_layer, n_head, and vocab_size for a modified XLNet model', 'test_validate_architecture': 'test the XLNetConfig.validate_architecture method to verify d_model is divisible by n_head', 'review_max_position_embeddings': 'review the XLNetConfig.max_position_embeddings property that returns -1 indicating no sequence length limit', 'summarize_xlnet_config': 'summarize the XLNetConfig class attributes including d_model, n_layer, n_head, and attention settings'}
```

## File: huggingface_transformers/src/transformers/models/xlnet/convert_xlnet_original_tf_checkpoint_to_pytorch.py

Prompts

```
['create an XLNetConfig instance with default hyperparameters for model initialization', 'create an XLNetConfig with custom d_model, n_layer, n_head, and vocab_size for a modified XLNet model', 'test the XLNetConfig.validate_architecture method to verify d_model is divisible by n_head', 'review the XLNetConfig.max_position_embeddings property that returns -1 indicating no sequence length limit', 'summarize the XLNetConfig class attributes including d_model, n_layer, n_head, and attention settings', 'convert a TensorFlow XLNet checkpoint to a PyTorch model with optional finetuning task', 'build a mapping from TensorFlow XLNet weight names to PyTorch model parameters', 'load TensorFlow XLNet checkpoint weights into a PyTorch XLNet model', 'convert an XLNet TensorFlow checkpoint to PyTorch weights and config files', 'run the XLNet TF-to-PyTorch conversion script via command-line arguments', 'build an XLNet model with bidirectional relative attention and memory caching for sequence modeling', 'create an XLNet language model with a linear head for masked next-token prediction', 'run XLNet on GLUE tasks with sequence classification or regression head', 'test XLNet extractive QA with beam-search top-k start and end span prediction', 'summarize the XLNet relative attention mechanism with two-stream queries and positional encoding']
```

Usage

```
{'convert_tf_xlnet_to_pytorch': 'convert a TensorFlow XLNet checkpoint to a PyTorch model with optional finetuning task', 'build_tf_xlnet_to_pytorch_map': 'build a mapping from TensorFlow XLNet weight names to PyTorch model parameters', 'load_tf_weights_in_xlnet': 'load TensorFlow XLNet checkpoint weights into a PyTorch XLNet model', 'convert_xlnet_checkpoint_to_pytorch': 'convert an XLNet TensorFlow checkpoint to PyTorch weights and config files', 'run_xlnet_conversion_cli': 'run the XLNet TF-to-PyTorch conversion script via command-line arguments'}
```

## File: huggingface_transformers/src/transformers/models/xlnet/modeling_xlnet.py

Prompts

```
['create an XLNetConfig instance with default hyperparameters for model initialization', 'create an XLNetConfig with custom d_model, n_layer, n_head, and vocab_size for a modified XLNet model', 'test the XLNetConfig.validate_architecture method to verify d_model is divisible by n_head', 'review the XLNetConfig.max_position_embeddings property that returns -1 indicating no sequence length limit', 'summarize the XLNetConfig class attributes including d_model, n_layer, n_head, and attention settings', 'convert a TensorFlow XLNet checkpoint to a PyTorch model with optional finetuning task', 'build a mapping from TensorFlow XLNet weight names to PyTorch model parameters', 'load TensorFlow XLNet checkpoint weights into a PyTorch XLNet model', 'convert an XLNet TensorFlow checkpoint to PyTorch weights and config files', 'run the XLNet TF-to-PyTorch conversion script via command-line arguments', 'build an XLNet model with bidirectional relative attention and memory caching for sequence modeling', 'create an XLNet language model with a linear head for masked next-token prediction', 'run XLNet on GLUE tasks with sequence classification or regression head', 'test XLNet extractive QA with beam-search top-k start and end span prediction', 'summarize the XLNet relative attention mechanism with two-stream queries and positional encoding']
```

Usage

```
{'build_xlnet_model': 'build an XLNet model with bidirectional relative attention and memory caching for sequence modeling', 'create_xlnet_lm_head_model': 'create an XLNet language model with a linear head for masked next-token prediction', 'run_xlnet_sequence_classification': 'run XLNet on GLUE tasks with sequence classification or regression head', 'test_xlnet_question_answering': 'test XLNet extractive QA with beam-search top-k start and end span prediction', 'summarize_xlnet_relative_attention': 'summarize the XLNet relative attention mechanism with two-stream queries and positional encoding'}
```

