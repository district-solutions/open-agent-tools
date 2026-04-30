# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/openai/convert_openai_original_tf_checkpoint_to_pytorch.py

Prompts

```
['convert an OpenAI GPT TensorFlow checkpoint to a PyTorch model with config and weights', 'load TensorFlow pre-trained weights from NumPy arrays into a PyTorch OpenAIGPTModel', 'run the CLI script to convert an OpenAI GPT checkpoint folder to PyTorch weights and config', 'review the convert_openai_checkpoint_to_pytorch function that builds a PyTorch model and saves weights', 'summarize the load_tf_weights_in_openai_gpt function that maps TensorFlow weight names to PyTorch pointers', 'build an OpenAI GPT language model with causal LM head for text generation and next-token prediction', 'create an OpenAI GPT sequence classifier with a linear classification head for sentiment or topic classification', 'test the OpenAI GPT double heads model with language modeling and multiple-choice classification for RocStories tasks', 'run the OpenAI GPT transformer forward pass with token embeddings, position embeddings, and multi-head attention', 'review the OpenAI GPT multi-head attention mechanism with causal masking and scaled dot-product computation', 'create an OpenAIGPTTokenizer instance with custom vocab and merges files for byte-pair encoding tokenization', 'build an OpenAIGPTTokenizer that lowercases all inputs and uses BERT BasicTokenizer for pre-BPE tokenization', 'review the OpenAIGPTTokenizer do_lower_case property that always returns True', 'summarize the OpenAIGPTTokenizer constructor that initializes a BPE tokenizer with vocab, merges, and unk_token', 'test the OpenAIGPTTokenizer vocab_files_names mapping for vocab.json, merges.txt, and tokenizer.json']
```

Usage

```
{'convert_openai_checkpoint_to_pytorch': 'convert an OpenAI GPT TensorFlow checkpoint to a PyTorch model with config and weights', 'load_tf_weights_in_openai_gpt': 'load TensorFlow pre-trained weights from NumPy arrays into a PyTorch OpenAIGPTModel', 'run_convert_cli': 'run the CLI script to convert an OpenAI GPT checkpoint folder to PyTorch weights and config', 'review_convert_function': 'review the convert_openai_checkpoint_to_pytorch function that builds a PyTorch model and saves weights', 'summarize_load_tf_weights': 'summarize the load_tf_weights_in_openai_gpt function that maps TensorFlow weight names to PyTorch pointers'}
```

## File: huggingface_transformers/src/transformers/models/openai/modeling_openai.py

Prompts

```
['convert an OpenAI GPT TensorFlow checkpoint to a PyTorch model with config and weights', 'load TensorFlow pre-trained weights from NumPy arrays into a PyTorch OpenAIGPTModel', 'run the CLI script to convert an OpenAI GPT checkpoint folder to PyTorch weights and config', 'review the convert_openai_checkpoint_to_pytorch function that builds a PyTorch model and saves weights', 'summarize the load_tf_weights_in_openai_gpt function that maps TensorFlow weight names to PyTorch pointers', 'build an OpenAI GPT language model with causal LM head for text generation and next-token prediction', 'create an OpenAI GPT sequence classifier with a linear classification head for sentiment or topic classification', 'test the OpenAI GPT double heads model with language modeling and multiple-choice classification for RocStories tasks', 'run the OpenAI GPT transformer forward pass with token embeddings, position embeddings, and multi-head attention', 'review the OpenAI GPT multi-head attention mechanism with causal masking and scaled dot-product computation', 'create an OpenAIGPTTokenizer instance with custom vocab and merges files for byte-pair encoding tokenization', 'build an OpenAIGPTTokenizer that lowercases all inputs and uses BERT BasicTokenizer for pre-BPE tokenization', 'review the OpenAIGPTTokenizer do_lower_case property that always returns True', 'summarize the OpenAIGPTTokenizer constructor that initializes a BPE tokenizer with vocab, merges, and unk_token', 'test the OpenAIGPTTokenizer vocab_files_names mapping for vocab.json, merges.txt, and tokenizer.json']
```

Usage

```
{'build_openai_gpt_language_model': 'build an OpenAI GPT language model with causal LM head for text generation and next-token prediction', 'create_openai_gpt_sequence_classifier': 'create an OpenAI GPT sequence classifier with a linear classification head for sentiment or topic classification', 'test_openai_gpt_double_heads_model': 'test the OpenAI GPT double heads model with language modeling and multiple-choice classification for RocStories tasks', 'run_openai_gpt_model_forward': 'run the OpenAI GPT transformer forward pass with token embeddings, position embeddings, and multi-head attention', 'review_attention_mechanism': 'review the OpenAI GPT multi-head attention mechanism with causal masking and scaled dot-product computation'}
```

## File: huggingface_transformers/src/transformers/models/openai/tokenization_openai.py

Prompts

```
['convert an OpenAI GPT TensorFlow checkpoint to a PyTorch model with config and weights', 'load TensorFlow pre-trained weights from NumPy arrays into a PyTorch OpenAIGPTModel', 'run the CLI script to convert an OpenAI GPT checkpoint folder to PyTorch weights and config', 'review the convert_openai_checkpoint_to_pytorch function that builds a PyTorch model and saves weights', 'summarize the load_tf_weights_in_openai_gpt function that maps TensorFlow weight names to PyTorch pointers', 'build an OpenAI GPT language model with causal LM head for text generation and next-token prediction', 'create an OpenAI GPT sequence classifier with a linear classification head for sentiment or topic classification', 'test the OpenAI GPT double heads model with language modeling and multiple-choice classification for RocStories tasks', 'run the OpenAI GPT transformer forward pass with token embeddings, position embeddings, and multi-head attention', 'review the OpenAI GPT multi-head attention mechanism with causal masking and scaled dot-product computation', 'create an OpenAIGPTTokenizer instance with custom vocab and merges files for byte-pair encoding tokenization', 'build an OpenAIGPTTokenizer that lowercases all inputs and uses BERT BasicTokenizer for pre-BPE tokenization', 'review the OpenAIGPTTokenizer do_lower_case property that always returns True', 'summarize the OpenAIGPTTokenizer constructor that initializes a BPE tokenizer with vocab, merges, and unk_token', 'test the OpenAIGPTTokenizer vocab_files_names mapping for vocab.json, merges.txt, and tokenizer.json']
```

Usage

```
{'create_OpenAIGPTTokenizer': 'create an OpenAIGPTTokenizer instance with custom vocab and merges files for byte-pair encoding tokenization', 'build_OpenAIGPTTokenizer_lowercase': 'build an OpenAIGPTTokenizer that lowercases all inputs and uses BERT BasicTokenizer for pre-BPE tokenization', 'review_OpenAIGPTTokenizer_do_lower_case': 'review the OpenAIGPTTokenizer do_lower_case property that always returns True', 'summarize_OpenAIGPTTokenizer_init': 'summarize the OpenAIGPTTokenizer constructor that initializes a BPE tokenizer with vocab, merges, and unk_token', 'test_OpenAIGPTTokenizer_vocab_files_names': 'test the OpenAIGPTTokenizer vocab_files_names mapping for vocab.json, merges.txt, and tokenizer.json'}
```

