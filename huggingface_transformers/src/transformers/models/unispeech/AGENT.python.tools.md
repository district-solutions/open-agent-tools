# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/unispeech/configuration_unispeech.py

Prompts

```
['create a UniSpeechConfig instance with default architecture settings for the UniSpeech model', 'create a UniSpeechConfig with custom convolutional layer dimensions and dropout parameters', 'test the validate_architecture method to ensure conv_dim, conv_stride, and conv_kernel lengths match', 'summarize the inputs_to_logits_ratio property that computes the downsampling ratio from conv_stride', 'review the UniSpeechConfig class and its default hyperparameters for feature encoder and transformer layers', 'convert a fairseq UniSpeech checkpoint to a HuggingFace PyTorch model with optional fine-tuned CTC support', 'recursively map fairseq model weights to corresponding HuggingFace UniSpeech model layers', 'load convolutional feature extractor layers from a fairseq checkpoint into the HuggingFace feature extractor', 'recursively navigate HuggingFace model attributes and assign weight values with shape validation', 'run the CLI to convert a fairseq UniSpeech checkpoint to HuggingFace format via argparse', 'build a UniSpeechModel for extracting audio features and encoding speech representations', 'run UniSpeechForCTC with CTC loss for speech recognition and language modeling tasks', 'run UniSpeechForPreTraining with vector quantization and contrastive loss for self-supervised pre-training', 'run UniSpeechForSequenceClassification for audio classification tasks like keyword spotting', 'test the UniSpeechFeatureEncoder that converts raw audio waveforms into feature representations', 'create a UniSpeechModel for audio feature extraction with configurable encoder and stable layer norm', 'run UniSpeechForPreTraining with gumbel vector quantization and contrastive learning on audio inputs', 'run UniSpeechForCTC for automatic speech recognition with CTC loss on audio sequences', 'run UniSpeechForSequenceClassification for audio sequence classification tasks', 'test UniSpeechGumbelVectorQuantizer forward pass with gumbel-softmax sampling and perplexity computation']
```

Usage

```
{'create_unispeech_config': 'create a UniSpeechConfig instance with default architecture settings for the UniSpeech model', 'create_custom_unispeech_config': 'create a UniSpeechConfig with custom convolutional layer dimensions and dropout parameters', 'test_validate_architecture': 'test the validate_architecture method to ensure conv_dim, conv_stride, and conv_kernel lengths match', 'summarize_inputs_to_logits_ratio': 'summarize the inputs_to_logits_ratio property that computes the downsampling ratio from conv_stride', 'review_unispeech_config': 'review the UniSpeechConfig class and its default hyperparameters for feature encoder and transformer layers'}
```

## File: huggingface_transformers/src/transformers/models/unispeech/convert_unispeech_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['create a UniSpeechConfig instance with default architecture settings for the UniSpeech model', 'create a UniSpeechConfig with custom convolutional layer dimensions and dropout parameters', 'test the validate_architecture method to ensure conv_dim, conv_stride, and conv_kernel lengths match', 'summarize the inputs_to_logits_ratio property that computes the downsampling ratio from conv_stride', 'review the UniSpeechConfig class and its default hyperparameters for feature encoder and transformer layers', 'convert a fairseq UniSpeech checkpoint to a HuggingFace PyTorch model with optional fine-tuned CTC support', 'recursively map fairseq model weights to corresponding HuggingFace UniSpeech model layers', 'load convolutional feature extractor layers from a fairseq checkpoint into the HuggingFace feature extractor', 'recursively navigate HuggingFace model attributes and assign weight values with shape validation', 'run the CLI to convert a fairseq UniSpeech checkpoint to HuggingFace format via argparse', 'build a UniSpeechModel for extracting audio features and encoding speech representations', 'run UniSpeechForCTC with CTC loss for speech recognition and language modeling tasks', 'run UniSpeechForPreTraining with vector quantization and contrastive loss for self-supervised pre-training', 'run UniSpeechForSequenceClassification for audio classification tasks like keyword spotting', 'test the UniSpeechFeatureEncoder that converts raw audio waveforms into feature representations', 'create a UniSpeechModel for audio feature extraction with configurable encoder and stable layer norm', 'run UniSpeechForPreTraining with gumbel vector quantization and contrastive learning on audio inputs', 'run UniSpeechForCTC for automatic speech recognition with CTC loss on audio sequences', 'run UniSpeechForSequenceClassification for audio sequence classification tasks', 'test UniSpeechGumbelVectorQuantizer forward pass with gumbel-softmax sampling and perplexity computation']
```

Usage

```
{'convert_unispeech_checkpoint': 'convert a fairseq UniSpeech checkpoint to a HuggingFace PyTorch model with optional fine-tuned CTC support', 'recursively_load_weights': 'recursively map fairseq model weights to corresponding HuggingFace UniSpeech model layers', 'load_conv_layer': 'load convolutional feature extractor layers from a fairseq checkpoint into the HuggingFace feature extractor', 'set_recursively': 'recursively navigate HuggingFace model attributes and assign weight values with shape validation', 'run_convert_cli': 'run the CLI to convert a fairseq UniSpeech checkpoint to HuggingFace format via argparse'}
```

## File: huggingface_transformers/src/transformers/models/unispeech/modeling_unispeech.py

Prompts

```
['create a UniSpeechConfig instance with default architecture settings for the UniSpeech model', 'create a UniSpeechConfig with custom convolutional layer dimensions and dropout parameters', 'test the validate_architecture method to ensure conv_dim, conv_stride, and conv_kernel lengths match', 'summarize the inputs_to_logits_ratio property that computes the downsampling ratio from conv_stride', 'review the UniSpeechConfig class and its default hyperparameters for feature encoder and transformer layers', 'convert a fairseq UniSpeech checkpoint to a HuggingFace PyTorch model with optional fine-tuned CTC support', 'recursively map fairseq model weights to corresponding HuggingFace UniSpeech model layers', 'load convolutional feature extractor layers from a fairseq checkpoint into the HuggingFace feature extractor', 'recursively navigate HuggingFace model attributes and assign weight values with shape validation', 'run the CLI to convert a fairseq UniSpeech checkpoint to HuggingFace format via argparse', 'build a UniSpeechModel for extracting audio features and encoding speech representations', 'run UniSpeechForCTC with CTC loss for speech recognition and language modeling tasks', 'run UniSpeechForPreTraining with vector quantization and contrastive loss for self-supervised pre-training', 'run UniSpeechForSequenceClassification for audio classification tasks like keyword spotting', 'test the UniSpeechFeatureEncoder that converts raw audio waveforms into feature representations', 'create a UniSpeechModel for audio feature extraction with configurable encoder and stable layer norm', 'run UniSpeechForPreTraining with gumbel vector quantization and contrastive learning on audio inputs', 'run UniSpeechForCTC for automatic speech recognition with CTC loss on audio sequences', 'run UniSpeechForSequenceClassification for audio sequence classification tasks', 'test UniSpeechGumbelVectorQuantizer forward pass with gumbel-softmax sampling and perplexity computation']
```

Usage

```
{'build_unispeech_model': 'build a UniSpeechModel for extracting audio features and encoding speech representations', 'run_unispeech_for_ctc': 'run UniSpeechForCTC with CTC loss for speech recognition and language modeling tasks', 'run_unispeech_for_pretraining': 'run UniSpeechForPreTraining with vector quantization and contrastive loss for self-supervised pre-training', 'run_unispeech_for_sequence_classification': 'run UniSpeechForSequenceClassification for audio classification tasks like keyword spotting', 'test_unispeech_feature_encoder': 'test the UniSpeechFeatureEncoder that converts raw audio waveforms into feature representations'}
```

## File: huggingface_transformers/src/transformers/models/unispeech/modular_unispeech.py

Prompts

```
['create a UniSpeechConfig instance with default architecture settings for the UniSpeech model', 'create a UniSpeechConfig with custom convolutional layer dimensions and dropout parameters', 'test the validate_architecture method to ensure conv_dim, conv_stride, and conv_kernel lengths match', 'summarize the inputs_to_logits_ratio property that computes the downsampling ratio from conv_stride', 'review the UniSpeechConfig class and its default hyperparameters for feature encoder and transformer layers', 'convert a fairseq UniSpeech checkpoint to a HuggingFace PyTorch model with optional fine-tuned CTC support', 'recursively map fairseq model weights to corresponding HuggingFace UniSpeech model layers', 'load convolutional feature extractor layers from a fairseq checkpoint into the HuggingFace feature extractor', 'recursively navigate HuggingFace model attributes and assign weight values with shape validation', 'run the CLI to convert a fairseq UniSpeech checkpoint to HuggingFace format via argparse', 'build a UniSpeechModel for extracting audio features and encoding speech representations', 'run UniSpeechForCTC with CTC loss for speech recognition and language modeling tasks', 'run UniSpeechForPreTraining with vector quantization and contrastive loss for self-supervised pre-training', 'run UniSpeechForSequenceClassification for audio classification tasks like keyword spotting', 'test the UniSpeechFeatureEncoder that converts raw audio waveforms into feature representations', 'create a UniSpeechModel for audio feature extraction with configurable encoder and stable layer norm', 'run UniSpeechForPreTraining with gumbel vector quantization and contrastive learning on audio inputs', 'run UniSpeechForCTC for automatic speech recognition with CTC loss on audio sequences', 'run UniSpeechForSequenceClassification for audio sequence classification tasks', 'test UniSpeechGumbelVectorQuantizer forward pass with gumbel-softmax sampling and perplexity computation']
```

Usage

```
{'create_unispeech_model': 'create a UniSpeechModel for audio feature extraction with configurable encoder and stable layer norm', 'run_unispeech_pretraining': 'run UniSpeechForPreTraining with gumbel vector quantization and contrastive learning on audio inputs', 'run_unispeech_ctc': 'run UniSpeechForCTC for automatic speech recognition with CTC loss on audio sequences', 'run_unispeech_classification': 'run UniSpeechForSequenceClassification for audio sequence classification tasks', 'test_gumbel_vector_quantizer': 'test UniSpeechGumbelVectorQuantizer forward pass with gumbel-softmax sampling and perplexity computation'}
```

