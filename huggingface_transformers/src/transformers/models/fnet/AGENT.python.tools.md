# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/fnet/convert_fnet_original_flax_checkpoint_to_pytorch.py

Prompts

```
['convert a Flax FNet checkpoint to PyTorch using the config file and save the result', 'build a PyTorch FNetForPreTraining model from a JSON configuration file', 'restore a Flax checkpoint from disk and extract the target parameters dictionary', 'map Flax embedding layer weights to PyTorch state dict with transposed kernels', 'save a PyTorch FNetForPreTraining model with loaded state dict to a directory', 'create an FNetModel encoder using FNetConfig with Fourier-based token mixing instead of self-attention', 'run FNetForSequenceClassification to classify text sequences for GLUE tasks', 'run FNetForMaskedLM to predict masked tokens using Fourier transform-based language modeling', 'run FNetForQuestionAnswering to extract start and end positions from a context passage', 'run FNetForTokenClassification to assign labels to each token for NER or POS tagging']
```

Usage

```
{'convert_flax_checkpoint_to_pytorch': 'convert a Flax FNet checkpoint to PyTorch using the config file and save the result', 'build_fnet_model_from_config': 'build a PyTorch FNetForPreTraining model from a JSON configuration file', 'restore_flax_checkpoint': 'restore a Flax checkpoint from disk and extract the target parameters dictionary', 'map_embeddings_to_pytorch': 'map Flax embedding layer weights to PyTorch state dict with transposed kernels', 'save_pytorch_model': 'save a PyTorch FNetForPreTraining model with loaded state dict to a directory'}
```

## File: huggingface_transformers/src/transformers/models/fnet/modeling_fnet.py

Prompts

```
['convert a Flax FNet checkpoint to PyTorch using the config file and save the result', 'build a PyTorch FNetForPreTraining model from a JSON configuration file', 'restore a Flax checkpoint from disk and extract the target parameters dictionary', 'map Flax embedding layer weights to PyTorch state dict with transposed kernels', 'save a PyTorch FNetForPreTraining model with loaded state dict to a directory', 'create an FNetModel encoder using FNetConfig with Fourier-based token mixing instead of self-attention', 'run FNetForSequenceClassification to classify text sequences for GLUE tasks', 'run FNetForMaskedLM to predict masked tokens using Fourier transform-based language modeling', 'run FNetForQuestionAnswering to extract start and end positions from a context passage', 'run FNetForTokenClassification to assign labels to each token for NER or POS tagging']
```

Usage

```
{'create_fnet_model': 'create an FNetModel encoder using FNetConfig with Fourier-based token mixing instead of self-attention', 'run_fnet_sequence_classification': 'run FNetForSequenceClassification to classify text sequences for GLUE tasks', 'run_fnet_masked_lm': 'run FNetForMaskedLM to predict masked tokens using Fourier transform-based language modeling', 'run_fnet_question_answering': 'run FNetForQuestionAnswering to extract start and end positions from a context passage', 'run_fnet_token_classification': 'run FNetForTokenClassification to assign labels to each token for NER or POS tagging'}
```

