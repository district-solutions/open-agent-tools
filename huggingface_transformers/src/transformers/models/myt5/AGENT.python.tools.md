# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/myt5/convert_myt5_original_tf_checkpoint_to_pytorch.py

Prompts

```
['convert a TensorFlow MyT5 checkpoint to a PyTorch model using the config json file and output path', 'load TensorFlow checkpoint weights into a PyTorch T5ForConditionalGeneration model with scope mapping', 'run the CLI to convert a TensorFlow MyT5 checkpoint to PyTorch with tf_checkpoint_path config_file and pytorch_dump_path args', 'review the convert_tf_checkpoint_to_pytorch function that initializes T5Config and T5ForConditionalGeneration from a TF checkpoint', 'summarize the load_tf_weights_in_t5 function that maps TF variable names to PyTorch model pointers and transposes weight arrays', 'create a MyT5Tokenizer instance from a byte_maps.json vocab file with custom extra_ids and special tokens', 'build a ByteRewriter from rewriting rules dict or JSON file path to construct hash trees for byte sequence rewriting', 'test the morphological_encode method that applies decompose and merge rewriting rules to hex-encoded byte sequences', 'review the convert_tokens_to_string method that decodes hex byte tokens back to a UTF-8 string with morphological decoding', 'summarize the morphological_decode method that reverses merge and decompose operations on token sequences']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow MyT5 checkpoint to a PyTorch model using the config json file and output path', 'load_tf_weights_in_t5': 'load TensorFlow checkpoint weights into a PyTorch T5ForConditionalGeneration model with scope mapping', 'build_cli_convert_myt5': 'run the CLI to convert a TensorFlow MyT5 checkpoint to PyTorch with tf_checkpoint_path config_file and pytorch_dump_path args', 'review_convert_tf_checkpoint_to_pytorch': 'review the convert_tf_checkpoint_to_pytorch function that initializes T5Config and T5ForConditionalGeneration from a TF checkpoint', 'summarize_load_tf_weights_in_t5': 'summarize the load_tf_weights_in_t5 function that maps TF variable names to PyTorch model pointers and transposes weight arrays'}
```

## File: huggingface_transformers/src/transformers/models/myt5/tokenization_myt5.py

Prompts

```
['convert a TensorFlow MyT5 checkpoint to a PyTorch model using the config json file and output path', 'load TensorFlow checkpoint weights into a PyTorch T5ForConditionalGeneration model with scope mapping', 'run the CLI to convert a TensorFlow MyT5 checkpoint to PyTorch with tf_checkpoint_path config_file and pytorch_dump_path args', 'review the convert_tf_checkpoint_to_pytorch function that initializes T5Config and T5ForConditionalGeneration from a TF checkpoint', 'summarize the load_tf_weights_in_t5 function that maps TF variable names to PyTorch model pointers and transposes weight arrays', 'create a MyT5Tokenizer instance from a byte_maps.json vocab file with custom extra_ids and special tokens', 'build a ByteRewriter from rewriting rules dict or JSON file path to construct hash trees for byte sequence rewriting', 'test the morphological_encode method that applies decompose and merge rewriting rules to hex-encoded byte sequences', 'review the convert_tokens_to_string method that decodes hex byte tokens back to a UTF-8 string with morphological decoding', 'summarize the morphological_decode method that reverses merge and decompose operations on token sequences']
```

Usage

```
{'create_myt5_tokenizer': 'create a MyT5Tokenizer instance from a byte_maps.json vocab file with custom extra_ids and special tokens', 'build_byte_rewriter': 'build a ByteRewriter from rewriting rules dict or JSON file path to construct hash trees for byte sequence rewriting', 'test_morphological_encode': 'test the morphological_encode method that applies decompose and merge rewriting rules to hex-encoded byte sequences', 'review_convert_tokens_to_string': 'review the convert_tokens_to_string method that decodes hex byte tokens back to a UTF-8 string with morphological decoding', 'summarize_morphological_decode': 'summarize the morphological_decode method that reverses merge and decompose operations on token sequences'}
```

