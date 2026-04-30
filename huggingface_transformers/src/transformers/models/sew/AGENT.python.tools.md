# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/sew/configuration_sew.py

Prompts

```
['create a SEWConfig instance with default architecture parameters for a squeeze-and-whisper model', 'create a SEWConfig instance with custom conv_dim, conv_stride, and conv_kernel for the feature encoder', 'test the SEWConfig validate_architecture method to verify conv_dim, conv_stride, and conv_kernel lengths match', 'test the SEWConfig inputs_to_logits_ratio property that computes the product of all conv_stride values', 'review the SEWConfig class that configures squeeze-and-whisper speech model architecture parameters', 'convert a fairseq SEW checkpoint to a HuggingFace PyTorch model with CLI arguments', 'convert a fairseq SEW model config to a HuggingFace SEWConfig object', 'recursively load fairseq model weights into a HuggingFace SEW model structure', 'load convolutional layer weights from a fairseq checkpoint into a feature extractor', 'set tensor values recursively into nested HuggingFace model attributes by key path', 'build a SEWModel for audio feature extraction and encoding from raw waveform inputs', 'create a SEWForCTC model with a CTC language modeling head for speech recognition', 'run a SEWForSequenceClassification model for keyword spotting or audio classification tasks', 'test the SEWEncoder with multi-headed attention, positional conv embeddings, and feed-forward layers', 'review the SEWFeatureEncoder that constructs features from raw audio waveform using convolutional layers', 'build a SEW model for audio feature extraction using SEWModel with a SEWConfig', 'run the SEWModel forward pass on audio input values with an optional attention mask', 'create a SEWForCTC model for speech recognition with connectionist temporal classification', 'create a SEWForSequenceClassification model for audio classification tasks', 'run the SEWEncoder forward pass with hidden states, attention mask, and optional outputs']
```

Usage

```
{'create_SEWConfig': 'create a SEWConfig instance with default architecture parameters for a squeeze-and-whisper model', 'create_SEWConfig_custom': 'create a SEWConfig instance with custom conv_dim, conv_stride, and conv_kernel for the feature encoder', 'test_SEWConfig_validate_architecture': 'test the SEWConfig validate_architecture method to verify conv_dim, conv_stride, and conv_kernel lengths match', 'test_SEWConfig_inputs_to_logits_ratio': 'test the SEWConfig inputs_to_logits_ratio property that computes the product of all conv_stride values', 'review_SEWConfig': 'review the SEWConfig class that configures squeeze-and-whisper speech model architecture parameters'}
```

## File: huggingface_transformers/src/transformers/models/sew/convert_sew_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['create a SEWConfig instance with default architecture parameters for a squeeze-and-whisper model', 'create a SEWConfig instance with custom conv_dim, conv_stride, and conv_kernel for the feature encoder', 'test the SEWConfig validate_architecture method to verify conv_dim, conv_stride, and conv_kernel lengths match', 'test the SEWConfig inputs_to_logits_ratio property that computes the product of all conv_stride values', 'review the SEWConfig class that configures squeeze-and-whisper speech model architecture parameters', 'convert a fairseq SEW checkpoint to a HuggingFace PyTorch model with CLI arguments', 'convert a fairseq SEW model config to a HuggingFace SEWConfig object', 'recursively load fairseq model weights into a HuggingFace SEW model structure', 'load convolutional layer weights from a fairseq checkpoint into a feature extractor', 'set tensor values recursively into nested HuggingFace model attributes by key path', 'build a SEWModel for audio feature extraction and encoding from raw waveform inputs', 'create a SEWForCTC model with a CTC language modeling head for speech recognition', 'run a SEWForSequenceClassification model for keyword spotting or audio classification tasks', 'test the SEWEncoder with multi-headed attention, positional conv embeddings, and feed-forward layers', 'review the SEWFeatureEncoder that constructs features from raw audio waveform using convolutional layers', 'build a SEW model for audio feature extraction using SEWModel with a SEWConfig', 'run the SEWModel forward pass on audio input values with an optional attention mask', 'create a SEWForCTC model for speech recognition with connectionist temporal classification', 'create a SEWForSequenceClassification model for audio classification tasks', 'run the SEWEncoder forward pass with hidden states, attention mask, and optional outputs']
```

Usage

```
{'convert_sew_checkpoint': 'convert a fairseq SEW checkpoint to a HuggingFace PyTorch model with CLI arguments', 'convert_config': 'convert a fairseq SEW model config to a HuggingFace SEWConfig object', 'recursively_load_weights': 'recursively load fairseq model weights into a HuggingFace SEW model structure', 'load_conv_layer': 'load convolutional layer weights from a fairseq checkpoint into a feature extractor', 'set_recursively': 'set tensor values recursively into nested HuggingFace model attributes by key path'}
```

## File: huggingface_transformers/src/transformers/models/sew/modeling_sew.py

Prompts

```
['create a SEWConfig instance with default architecture parameters for a squeeze-and-whisper model', 'create a SEWConfig instance with custom conv_dim, conv_stride, and conv_kernel for the feature encoder', 'test the SEWConfig validate_architecture method to verify conv_dim, conv_stride, and conv_kernel lengths match', 'test the SEWConfig inputs_to_logits_ratio property that computes the product of all conv_stride values', 'review the SEWConfig class that configures squeeze-and-whisper speech model architecture parameters', 'convert a fairseq SEW checkpoint to a HuggingFace PyTorch model with CLI arguments', 'convert a fairseq SEW model config to a HuggingFace SEWConfig object', 'recursively load fairseq model weights into a HuggingFace SEW model structure', 'load convolutional layer weights from a fairseq checkpoint into a feature extractor', 'set tensor values recursively into nested HuggingFace model attributes by key path', 'build a SEWModel for audio feature extraction and encoding from raw waveform inputs', 'create a SEWForCTC model with a CTC language modeling head for speech recognition', 'run a SEWForSequenceClassification model for keyword spotting or audio classification tasks', 'test the SEWEncoder with multi-headed attention, positional conv embeddings, and feed-forward layers', 'review the SEWFeatureEncoder that constructs features from raw audio waveform using convolutional layers', 'build a SEW model for audio feature extraction using SEWModel with a SEWConfig', 'run the SEWModel forward pass on audio input values with an optional attention mask', 'create a SEWForCTC model for speech recognition with connectionist temporal classification', 'create a SEWForSequenceClassification model for audio classification tasks', 'run the SEWEncoder forward pass with hidden states, attention mask, and optional outputs']
```

Usage

```
{'build_SEWModel': 'build a SEWModel for audio feature extraction and encoding from raw waveform inputs', 'create_SEWForCTC': 'create a SEWForCTC model with a CTC language modeling head for speech recognition', 'run_SEWForSequenceClassification': 'run a SEWForSequenceClassification model for keyword spotting or audio classification tasks', 'test_SEWEncoder': 'test the SEWEncoder with multi-headed attention, positional conv embeddings, and feed-forward layers', 'review_SEWFeatureEncoder': 'review the SEWFeatureEncoder that constructs features from raw audio waveform using convolutional layers'}
```

## File: huggingface_transformers/src/transformers/models/sew/modular_sew.py

Prompts

```
['create a SEWConfig instance with default architecture parameters for a squeeze-and-whisper model', 'create a SEWConfig instance with custom conv_dim, conv_stride, and conv_kernel for the feature encoder', 'test the SEWConfig validate_architecture method to verify conv_dim, conv_stride, and conv_kernel lengths match', 'test the SEWConfig inputs_to_logits_ratio property that computes the product of all conv_stride values', 'review the SEWConfig class that configures squeeze-and-whisper speech model architecture parameters', 'convert a fairseq SEW checkpoint to a HuggingFace PyTorch model with CLI arguments', 'convert a fairseq SEW model config to a HuggingFace SEWConfig object', 'recursively load fairseq model weights into a HuggingFace SEW model structure', 'load convolutional layer weights from a fairseq checkpoint into a feature extractor', 'set tensor values recursively into nested HuggingFace model attributes by key path', 'build a SEWModel for audio feature extraction and encoding from raw waveform inputs', 'create a SEWForCTC model with a CTC language modeling head for speech recognition', 'run a SEWForSequenceClassification model for keyword spotting or audio classification tasks', 'test the SEWEncoder with multi-headed attention, positional conv embeddings, and feed-forward layers', 'review the SEWFeatureEncoder that constructs features from raw audio waveform using convolutional layers', 'build a SEW model for audio feature extraction using SEWModel with a SEWConfig', 'run the SEWModel forward pass on audio input values with an optional attention mask', 'create a SEWForCTC model for speech recognition with connectionist temporal classification', 'create a SEWForSequenceClassification model for audio classification tasks', 'run the SEWEncoder forward pass with hidden states, attention mask, and optional outputs']
```

Usage

```
{'build_sew_model': 'build a SEW model for audio feature extraction using SEWModel with a SEWConfig', 'run_sew_model_forward': 'run the SEWModel forward pass on audio input values with an optional attention mask', 'create_sew_for_ctc': 'create a SEWForCTC model for speech recognition with connectionist temporal classification', 'create_sew_for_sequence_classification': 'create a SEWForSequenceClassification model for audio classification tasks', 'run_sew_encoder_forward': 'run the SEWEncoder forward pass with hidden states, attention mask, and optional outputs'}
```

