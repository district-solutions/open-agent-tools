# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/lxmert/convert_lxmert_original_tf_checkpoint_to_pytorch.py

Prompts

```
['convert a TensorFlow LXMERT checkpoint to a PyTorch model state dict file', 'load TensorFlow checkpoint weights into a PyTorch LXMERT model', 'run the LXMERT TF-to-PyTorch conversion script via argparse CLI with checkpoint, config, and output paths', 'build a PyTorch LxmertForPreTraining model from a JSON configuration file', 'test the TensorFlow to PyTorch weight mapping logic for kernel, bias, and embedding conversions', 'build a LxmertModel that encodes language and visual features for multimodal understanding', 'build a LxmertForPreTraining model with masked language modeling and visual object prediction heads', 'build a LxmertForQuestionAnswering model with a visual answering head for downstream VQA tasks', 'run the LxmertModel forward pass with input_ids, visual_feats, and visual_pos tensors', 'resize token embeddings and tied bias weights for the LxmertForPreTraining model vocabulary']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow LXMERT checkpoint to a PyTorch model state dict file', 'load_tf_weights_in_lxmert': 'load TensorFlow checkpoint weights into a PyTorch LXMERT model', 'run_lxmert_conversion_cli': 'run the LXMERT TF-to-PyTorch conversion script via argparse CLI with checkpoint, config, and output paths', 'build_lxmert_model_from_config': 'build a PyTorch LxmertForPreTraining model from a JSON configuration file', 'test_lxmert_weight_mapping': 'test the TensorFlow to PyTorch weight mapping logic for kernel, bias, and embedding conversions'}
```

## File: huggingface_transformers/src/transformers/models/lxmert/modeling_lxmert.py

Prompts

```
['convert a TensorFlow LXMERT checkpoint to a PyTorch model state dict file', 'load TensorFlow checkpoint weights into a PyTorch LXMERT model', 'run the LXMERT TF-to-PyTorch conversion script via argparse CLI with checkpoint, config, and output paths', 'build a PyTorch LxmertForPreTraining model from a JSON configuration file', 'test the TensorFlow to PyTorch weight mapping logic for kernel, bias, and embedding conversions', 'build a LxmertModel that encodes language and visual features for multimodal understanding', 'build a LxmertForPreTraining model with masked language modeling and visual object prediction heads', 'build a LxmertForQuestionAnswering model with a visual answering head for downstream VQA tasks', 'run the LxmertModel forward pass with input_ids, visual_feats, and visual_pos tensors', 'resize token embeddings and tied bias weights for the LxmertForPreTraining model vocabulary']
```

Usage

```
{'build_lxmert_model': 'build a LxmertModel that encodes language and visual features for multimodal understanding', 'build_lxmert_pretraining': 'build a LxmertForPreTraining model with masked language modeling and visual object prediction heads', 'build_lxmert_qa': 'build a LxmertForQuestionAnswering model with a visual answering head for downstream VQA tasks', 'run_lxmert_forward': 'run the LxmertModel forward pass with input_ids, visual_feats, and visual_pos tensors', 'resize_token_embeddings': 'resize token embeddings and tied bias weights for the LxmertForPreTraining model vocabulary'}
```

