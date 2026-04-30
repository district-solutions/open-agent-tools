# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/funnel/configuration_funnel.py

Prompts

```
['create a FunnelConfig instance with custom block_sizes, d_model, and n_head for a Funnel Transformer model', 'validate a FunnelConfig instance to ensure block_sizes and block_repeats lengths match and pooling_type is valid', 'read the num_hidden_layers property from a FunnelConfig to get the sum of block_sizes', 'read the num_blocks property from a FunnelConfig to get the number of blocks from block_sizes length', 'build a FunnelConfig from a dictionary of model hyperparameters using PreTrainedConfig initialization', 'convert a TensorFlow Funnel checkpoint to a PyTorch model state dict using config and checkpoint paths', 'load TensorFlow checkpoint weights into a PyTorch Funnel model by mapping variable names and shapes', 'run the Funnel TF-to-PyTorch conversion CLI with checkpoint path, config file, and output path arguments', 'build a PyTorch FunnelBaseModel or FunnelModel from a JSON config and load pretrained TensorFlow weights', 'review the TF-to-PyTorch checkpoint conversion function including weight mapping and layer traversal logic', 'build a FunnelModel with encoder-decoder architecture for efficient long-sequence modeling', 'run sequence classification on text using FunnelForSequenceClassification with a classification head', 'run masked language modeling with FunnelForMaskedLM for BERT-style token prediction', 'run ELECTRA-style pretraining with FunnelForPreTraining and discriminator predictions', 'run extractive question answering with FunnelForQuestionAnswering using start and end position logits']
```

Usage

```
{'create_FunnelConfig': 'create a FunnelConfig instance with custom block_sizes, d_model, and n_head for a Funnel Transformer model', 'validate_FunnelConfig_architecture': 'validate a FunnelConfig instance to ensure block_sizes and block_repeats lengths match and pooling_type is valid', 'read_FunnelConfig_num_hidden_layers': 'read the num_hidden_layers property from a FunnelConfig to get the sum of block_sizes', 'read_FunnelConfig_num_blocks': 'read the num_blocks property from a FunnelConfig to get the number of blocks from block_sizes length', 'build_FunnelConfig_from_dict': 'build a FunnelConfig from a dictionary of model hyperparameters using PreTrainedConfig initialization'}
```

## File: huggingface_transformers/src/transformers/models/funnel/convert_funnel_original_tf_checkpoint_to_pytorch.py

Prompts

```
['create a FunnelConfig instance with custom block_sizes, d_model, and n_head for a Funnel Transformer model', 'validate a FunnelConfig instance to ensure block_sizes and block_repeats lengths match and pooling_type is valid', 'read the num_hidden_layers property from a FunnelConfig to get the sum of block_sizes', 'read the num_blocks property from a FunnelConfig to get the number of blocks from block_sizes length', 'build a FunnelConfig from a dictionary of model hyperparameters using PreTrainedConfig initialization', 'convert a TensorFlow Funnel checkpoint to a PyTorch model state dict using config and checkpoint paths', 'load TensorFlow checkpoint weights into a PyTorch Funnel model by mapping variable names and shapes', 'run the Funnel TF-to-PyTorch conversion CLI with checkpoint path, config file, and output path arguments', 'build a PyTorch FunnelBaseModel or FunnelModel from a JSON config and load pretrained TensorFlow weights', 'review the TF-to-PyTorch checkpoint conversion function including weight mapping and layer traversal logic', 'build a FunnelModel with encoder-decoder architecture for efficient long-sequence modeling', 'run sequence classification on text using FunnelForSequenceClassification with a classification head', 'run masked language modeling with FunnelForMaskedLM for BERT-style token prediction', 'run ELECTRA-style pretraining with FunnelForPreTraining and discriminator predictions', 'run extractive question answering with FunnelForQuestionAnswering using start and end position logits']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow Funnel checkpoint to a PyTorch model state dict using config and checkpoint paths', 'load_tf_weights_in_funnel': 'load TensorFlow checkpoint weights into a PyTorch Funnel model by mapping variable names and shapes', 'run_convert_funnel_cli': 'run the Funnel TF-to-PyTorch conversion CLI with checkpoint path, config file, and output path arguments', 'build_funnel_pytorch_model': 'build a PyTorch FunnelBaseModel or FunnelModel from a JSON config and load pretrained TensorFlow weights', 'review_convert_tf_checkpoint_to_pytorch': 'review the TF-to-PyTorch checkpoint conversion function including weight mapping and layer traversal logic'}
```

## File: huggingface_transformers/src/transformers/models/funnel/modeling_funnel.py

Prompts

```
['create a FunnelConfig instance with custom block_sizes, d_model, and n_head for a Funnel Transformer model', 'validate a FunnelConfig instance to ensure block_sizes and block_repeats lengths match and pooling_type is valid', 'read the num_hidden_layers property from a FunnelConfig to get the sum of block_sizes', 'read the num_blocks property from a FunnelConfig to get the number of blocks from block_sizes length', 'build a FunnelConfig from a dictionary of model hyperparameters using PreTrainedConfig initialization', 'convert a TensorFlow Funnel checkpoint to a PyTorch model state dict using config and checkpoint paths', 'load TensorFlow checkpoint weights into a PyTorch Funnel model by mapping variable names and shapes', 'run the Funnel TF-to-PyTorch conversion CLI with checkpoint path, config file, and output path arguments', 'build a PyTorch FunnelBaseModel or FunnelModel from a JSON config and load pretrained TensorFlow weights', 'review the TF-to-PyTorch checkpoint conversion function including weight mapping and layer traversal logic', 'build a FunnelModel with encoder-decoder architecture for efficient long-sequence modeling', 'run sequence classification on text using FunnelForSequenceClassification with a classification head', 'run masked language modeling with FunnelForMaskedLM for BERT-style token prediction', 'run ELECTRA-style pretraining with FunnelForPreTraining and discriminator predictions', 'run extractive question answering with FunnelForQuestionAnswering using start and end position logits']
```

Usage

```
{'build_funnel_model': 'build a FunnelModel with encoder-decoder architecture for efficient long-sequence modeling', 'run_sequence_classification': 'run sequence classification on text using FunnelForSequenceClassification with a classification head', 'run_masked_language_modeling': 'run masked language modeling with FunnelForMaskedLM for BERT-style token prediction', 'run_electra_pretraining': 'run ELECTRA-style pretraining with FunnelForPreTraining and discriminator predictions', 'run_question_answering': 'run extractive question answering with FunnelForQuestionAnswering using start and end position logits'}
```

