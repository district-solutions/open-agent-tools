# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/bigbird_pegasus/convert_bigbird_pegasus_tf_to_pytorch.py

Prompts

```
['convert a BigBird Pegasus TensorFlow checkpoint to a PyTorch model and save it to a directory', 'convert a dictionary of TensorFlow weights into a BigBird Pegasus PyTorch model with a config update', 'load TensorFlow checkpoint variables from a directory into a dictionary of numpy arrays', 'rename a TensorFlow weight key to a Hugging Face PyTorch key using a list of pattern pairs', 'run the BigBird Pegasus TF-to-PyTorch conversion script from the command line with ckpt and save paths', 'generate summaries using BigBirdPegasusForConditionalGeneration model with encoder-decoder architecture for long documents', 'run sequence classification on encoder outputs using BigBirdPegasusForSequenceClassification with pooled last-eos token representation', 'perform extractive question answering with BigBirdPegasusForQuestionAnswering predicting start and end token positions', 'generate text autoregressively using BigBirdPegasusForCausalLM decoder-only with causal masking and past key value caching', 'use BigBirdPegasusBlockSparseAttention for O(n) linear-complexity attention on sequences up to 4096 tokens via block-sparse pattern']
```

Usage

```
{'convert_bigbird_pegasus_ckpt_to_pytorch': 'convert a BigBird Pegasus TensorFlow checkpoint to a PyTorch model and save it to a directory', 'convert_bigbird_pegasus': 'convert a dictionary of TensorFlow weights into a BigBird Pegasus PyTorch model with a config update', 'get_tf_weights_as_numpy': 'load TensorFlow checkpoint variables from a directory into a dictionary of numpy arrays', 'rename_state_dict_key': 'rename a TensorFlow weight key to a Hugging Face PyTorch key using a list of pattern pairs', 'run_bigbird_pegasus_conversion_cli': 'run the BigBird Pegasus TF-to-PyTorch conversion script from the command line with ckpt and save paths'}
```

## File: huggingface_transformers/src/transformers/models/bigbird_pegasus/modeling_bigbird_pegasus.py

Prompts

```
['convert a BigBird Pegasus TensorFlow checkpoint to a PyTorch model and save it to a directory', 'convert a dictionary of TensorFlow weights into a BigBird Pegasus PyTorch model with a config update', 'load TensorFlow checkpoint variables from a directory into a dictionary of numpy arrays', 'rename a TensorFlow weight key to a Hugging Face PyTorch key using a list of pattern pairs', 'run the BigBird Pegasus TF-to-PyTorch conversion script from the command line with ckpt and save paths', 'generate summaries using BigBirdPegasusForConditionalGeneration model with encoder-decoder architecture for long documents', 'run sequence classification on encoder outputs using BigBirdPegasusForSequenceClassification with pooled last-eos token representation', 'perform extractive question answering with BigBirdPegasusForQuestionAnswering predicting start and end token positions', 'generate text autoregressively using BigBirdPegasusForCausalLM decoder-only with causal masking and past key value caching', 'use BigBirdPegasusBlockSparseAttention for O(n) linear-complexity attention on sequences up to 4096 tokens via block-sparse pattern']
```

Usage

```
{'generate_summaries_with_bigbird_pegasus': 'generate summaries using BigBirdPegasusForConditionalGeneration model with encoder-decoder architecture for long documents', 'run_sequence_classification': 'run sequence classification on encoder outputs using BigBirdPegasusForSequenceClassification with pooled last-eos token representation', 'perform_question_answering': 'perform extractive question answering with BigBirdPegasusForQuestionAnswering predicting start and end token positions', 'generate_text_causal_lm': 'generate text autoregressively using BigBirdPegasusForCausalLM decoder-only with causal masking and past key value caching', 'use_block_sparse_attention': 'use BigBirdPegasusBlockSparseAttention for O(n) linear-complexity attention on sequences up to 4096 tokens via block-sparse pattern'}
```

