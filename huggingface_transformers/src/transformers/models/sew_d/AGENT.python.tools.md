# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/sew_d/configuration_sew_d.py

Prompts

```
['create a SEWDConfig instance with custom model hyperparameters for a squeeze-and-excited Wav2Vec model', 'validate the SEWDConfig convolutional layer dimensions are consistent across conv_dim, conv_stride, and conv_kernel', 'compute the inputs_to_logits_ratio property from SEWDConfig conv_stride values', 'configure SEWDConfig with spec augment masking parameters for time and feature axis augmentation', 'initialize SEWDConfig from a pretrained checkpoint configuration for model loading', 'convert a fairseq SEW checkpoint to a HuggingFace SEWD model with optional fine-tuned weights and tokenizer', 'convert a fairseq SEW model config to a HuggingFace SEWDConfig with matching architecture parameters', 'recursively load and map fairseq model weights into a HuggingFace SEWD model using a key mapping table', 'load feature extractor convolution layer weights from a fairseq checkpoint into a HuggingFace feature extractor', 'set recursively loaded weight tensors into the correct nested HuggingFace model attribute with shape validation', 'create a SEWDModel for speech feature extraction with configurable encoder layers and attention heads', 'run SEWDForCTC model for speech recognition with CTC loss and vocabulary-based token prediction', 'run SEWDForSequenceClassification for audio classification tasks like keyword spotting', 'test SpecAugment data augmentation by masking time and feature indices during training', 'review DisentangledSelfAttention with relative position bias and content-position attention types']
```

Usage

```
{'create_SEWDConfig': 'create a SEWDConfig instance with custom model hyperparameters for a squeeze-and-excited Wav2Vec model', 'validate_SEWDConfig_architecture': 'validate the SEWDConfig convolutional layer dimensions are consistent across conv_dim, conv_stride, and conv_kernel', 'compute_SEWDConfig_inputs_to_logits_ratio': 'compute the inputs_to_logits_ratio property from SEWDConfig conv_stride values', 'configure_SEWDConfig_spec_augment': 'configure SEWDConfig with spec augment masking parameters for time and feature axis augmentation', 'initialize_SEWDConfig_from_pretrained': 'initialize SEWDConfig from a pretrained checkpoint configuration for model loading'}
```

## File: huggingface_transformers/src/transformers/models/sew_d/convert_sew_d_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['create a SEWDConfig instance with custom model hyperparameters for a squeeze-and-excited Wav2Vec model', 'validate the SEWDConfig convolutional layer dimensions are consistent across conv_dim, conv_stride, and conv_kernel', 'compute the inputs_to_logits_ratio property from SEWDConfig conv_stride values', 'configure SEWDConfig with spec augment masking parameters for time and feature axis augmentation', 'initialize SEWDConfig from a pretrained checkpoint configuration for model loading', 'convert a fairseq SEW checkpoint to a HuggingFace SEWD model with optional fine-tuned weights and tokenizer', 'convert a fairseq SEW model config to a HuggingFace SEWDConfig with matching architecture parameters', 'recursively load and map fairseq model weights into a HuggingFace SEWD model using a key mapping table', 'load feature extractor convolution layer weights from a fairseq checkpoint into a HuggingFace feature extractor', 'set recursively loaded weight tensors into the correct nested HuggingFace model attribute with shape validation', 'create a SEWDModel for speech feature extraction with configurable encoder layers and attention heads', 'run SEWDForCTC model for speech recognition with CTC loss and vocabulary-based token prediction', 'run SEWDForSequenceClassification for audio classification tasks like keyword spotting', 'test SpecAugment data augmentation by masking time and feature indices during training', 'review DisentangledSelfAttention with relative position bias and content-position attention types']
```

Usage

```
{'convert_sew_checkpoint': 'convert a fairseq SEW checkpoint to a HuggingFace SEWD model with optional fine-tuned weights and tokenizer', 'convert_config': 'convert a fairseq SEW model config to a HuggingFace SEWDConfig with matching architecture parameters', 'recursively_load_weights': 'recursively load and map fairseq model weights into a HuggingFace SEWD model using a key mapping table', 'load_conv_layer': 'load feature extractor convolution layer weights from a fairseq checkpoint into a HuggingFace feature extractor', 'set_recursively': 'set recursively loaded weight tensors into the correct nested HuggingFace model attribute with shape validation'}
```

## File: huggingface_transformers/src/transformers/models/sew_d/modeling_sew_d.py

Prompts

```
['create a SEWDConfig instance with custom model hyperparameters for a squeeze-and-excited Wav2Vec model', 'validate the SEWDConfig convolutional layer dimensions are consistent across conv_dim, conv_stride, and conv_kernel', 'compute the inputs_to_logits_ratio property from SEWDConfig conv_stride values', 'configure SEWDConfig with spec augment masking parameters for time and feature axis augmentation', 'initialize SEWDConfig from a pretrained checkpoint configuration for model loading', 'convert a fairseq SEW checkpoint to a HuggingFace SEWD model with optional fine-tuned weights and tokenizer', 'convert a fairseq SEW model config to a HuggingFace SEWDConfig with matching architecture parameters', 'recursively load and map fairseq model weights into a HuggingFace SEWD model using a key mapping table', 'load feature extractor convolution layer weights from a fairseq checkpoint into a HuggingFace feature extractor', 'set recursively loaded weight tensors into the correct nested HuggingFace model attribute with shape validation', 'create a SEWDModel for speech feature extraction with configurable encoder layers and attention heads', 'run SEWDForCTC model for speech recognition with CTC loss and vocabulary-based token prediction', 'run SEWDForSequenceClassification for audio classification tasks like keyword spotting', 'test SpecAugment data augmentation by masking time and feature indices during training', 'review DisentangledSelfAttention with relative position bias and content-position attention types']
```

Usage

```
{'create_SEWDModel': 'create a SEWDModel for speech feature extraction with configurable encoder layers and attention heads', 'run_SEWDForCTC': 'run SEWDForCTC model for speech recognition with CTC loss and vocabulary-based token prediction', 'run_SEWDForSequenceClassification': 'run SEWDForSequenceClassification for audio classification tasks like keyword spotting', 'test_SpecAugment_masking': 'test SpecAugment data augmentation by masking time and feature indices during training', 'review_DisentangledSelfAttention': 'review DisentangledSelfAttention with relative position bias and content-position attention types'}
```

