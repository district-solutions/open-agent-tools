# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/umt5/configuration_umt5.py

Prompts

```
['create a UMT5Config instance with custom model parameters like d_model, num_layers, and vocab_size', 'validate the UMT5Config feed_forward_proj setting to ensure it uses a valid activation format', 'configure UMT5Config with custom relative_attention_num_buckets and relative_attention_max_distance values', 'build a UMT5Config instance configured as an encoder-decoder model with cache enabled', 'review the UMT5Config default hyperparameters including d_model=512, num_heads=6, and dropout_rate=0.1', 'convert a T5X checkpoint to a PyTorch checkpoint using a config file and output path', 'convert T5X-Flax model parameters to PyTorch state dict for encoder-only or encoder-decoder models', 'load T5X checkpoint weights into a UMT5 PyTorch model with configurable encoder-only and scalable attention', 'prepare a PyTorch state dict from converted T5X parameters with shared embeddings and lm head fallback', 'run the CLI to convert a UMT5 T5X checkpoint to PyTorch with optional encoder-only and scalable attention flags', 'create a UMT5ForConditionalGeneration model for text-to-text generation tasks like summarization', 'build a UMT5EncoderModel that encodes input text into hidden state representations', 'test UMT5ForSequenceClassification for sentence-level classification tasks like GLUE benchmarks', 'run UMT5ForQuestionAnswering to predict start and end positions of answers in context text', 'review UMT5ForTokenClassification for token-level tagging tasks like NER using encoder-only architecture']
```

Usage

```
{'create_umt5_config': 'create a UMT5Config instance with custom model parameters like d_model, num_layers, and vocab_size', 'validate_umt5_architecture': 'validate the UMT5Config feed_forward_proj setting to ensure it uses a valid activation format', 'configure_umt5_attention': 'configure UMT5Config with custom relative_attention_num_buckets and relative_attention_max_distance values', 'build_umt5_encoder_decoder': 'build a UMT5Config instance configured as an encoder-decoder model with cache enabled', 'review_umt5_config_defaults': 'review the UMT5Config default hyperparameters including d_model=512, num_heads=6, and dropout_rate=0.1'}
```

## File: huggingface_transformers/src/transformers/models/umt5/convert_umt5_checkpoint_to_pytorch.py

Prompts

```
['create a UMT5Config instance with custom model parameters like d_model, num_layers, and vocab_size', 'validate the UMT5Config feed_forward_proj setting to ensure it uses a valid activation format', 'configure UMT5Config with custom relative_attention_num_buckets and relative_attention_max_distance values', 'build a UMT5Config instance configured as an encoder-decoder model with cache enabled', 'review the UMT5Config default hyperparameters including d_model=512, num_heads=6, and dropout_rate=0.1', 'convert a T5X checkpoint to a PyTorch checkpoint using a config file and output path', 'convert T5X-Flax model parameters to PyTorch state dict for encoder-only or encoder-decoder models', 'load T5X checkpoint weights into a UMT5 PyTorch model with configurable encoder-only and scalable attention', 'prepare a PyTorch state dict from converted T5X parameters with shared embeddings and lm head fallback', 'run the CLI to convert a UMT5 T5X checkpoint to PyTorch with optional encoder-only and scalable attention flags', 'create a UMT5ForConditionalGeneration model for text-to-text generation tasks like summarization', 'build a UMT5EncoderModel that encodes input text into hidden state representations', 'test UMT5ForSequenceClassification for sentence-level classification tasks like GLUE benchmarks', 'run UMT5ForQuestionAnswering to predict start and end positions of answers in context text', 'review UMT5ForTokenClassification for token-level tagging tasks like NER using encoder-only architecture']
```

Usage

```
{'convert_t5x_checkpoint_to_pytorch': 'convert a T5X checkpoint to a PyTorch checkpoint using a config file and output path', 'convert_t5x_to_pytorch': 'convert T5X-Flax model parameters to PyTorch state dict for encoder-only or encoder-decoder models', 'load_t5x_weights_in_t5': 'load T5X checkpoint weights into a UMT5 PyTorch model with configurable encoder-only and scalable attention', 'make_state_dict': 'prepare a PyTorch state dict from converted T5X parameters with shared embeddings and lm head fallback', 'convert_umt5_checkpoint_cli': 'run the CLI to convert a UMT5 T5X checkpoint to PyTorch with optional encoder-only and scalable attention flags'}
```

## File: huggingface_transformers/src/transformers/models/umt5/modeling_umt5.py

Prompts

```
['create a UMT5Config instance with custom model parameters like d_model, num_layers, and vocab_size', 'validate the UMT5Config feed_forward_proj setting to ensure it uses a valid activation format', 'configure UMT5Config with custom relative_attention_num_buckets and relative_attention_max_distance values', 'build a UMT5Config instance configured as an encoder-decoder model with cache enabled', 'review the UMT5Config default hyperparameters including d_model=512, num_heads=6, and dropout_rate=0.1', 'convert a T5X checkpoint to a PyTorch checkpoint using a config file and output path', 'convert T5X-Flax model parameters to PyTorch state dict for encoder-only or encoder-decoder models', 'load T5X checkpoint weights into a UMT5 PyTorch model with configurable encoder-only and scalable attention', 'prepare a PyTorch state dict from converted T5X parameters with shared embeddings and lm head fallback', 'run the CLI to convert a UMT5 T5X checkpoint to PyTorch with optional encoder-only and scalable attention flags', 'create a UMT5ForConditionalGeneration model for text-to-text generation tasks like summarization', 'build a UMT5EncoderModel that encodes input text into hidden state representations', 'test UMT5ForSequenceClassification for sentence-level classification tasks like GLUE benchmarks', 'run UMT5ForQuestionAnswering to predict start and end positions of answers in context text', 'review UMT5ForTokenClassification for token-level tagging tasks like NER using encoder-only architecture']
```

Usage

```
{'create_umt5_conditional_generation_model': 'create a UMT5ForConditionalGeneration model for text-to-text generation tasks like summarization', 'build_umt5_encoder_model': 'build a UMT5EncoderModel that encodes input text into hidden state representations', 'test_umt5_sequence_classification': 'test UMT5ForSequenceClassification for sentence-level classification tasks like GLUE benchmarks', 'run_umt5_question_answering': 'run UMT5ForQuestionAnswering to predict start and end positions of answers in context text', 'review_umt5_token_classification': 'review UMT5ForTokenClassification for token-level tagging tasks like NER using encoder-only architecture'}
```

