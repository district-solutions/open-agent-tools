# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/wav2vec2_conformer/configuration_wav2vec2_conformer.py

Prompts

```
['create a Wav2Vec2ConformerConfig instance with default speech recognition model settings', 'create a Wav2Vec2ConformerConfig with custom conv_dim, hidden_size, and num_hidden_layers parameters', 'validate the Wav2Vec2ConformerConfig architecture ensuring conv_dim, conv_stride, and conv_kernel lengths match', 'compute the inputs_to_logits_ratio property from Wav2Vec2ConformerConfig conv_stride values', 'initialize a Wav2Vec2ConformerModel using a Wav2Vec2ConformerConfig for random weight initialization', 'convert a fairseq wav2vec2 conformer checkpoint to a Hugging Face PyTorch model', 'load convolutional layer weights from a fairseq checkpoint into the feature extractor', 'recursively map and load fairseq model weights into a Hugging Face wav2vec2 conformer model', 'set tensor values recursively on a Hugging Face model pointer with shape validation', 'run the CLI script to convert a fairseq wav2vec2 conformer checkpoint to Hugging Face format', 'build a Wav2Vec2ConformerModel to extract audio features from raw speech waveform tensors', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss for self-supervised audio learning', 'run Wav2Vec2ConformerForCTC with CTC loss for automatic speech recognition with a language modeling head', 'run Wav2Vec2ConformerForSequenceClassification to classify audio inputs into discrete label categories', 'run Wav2Vec2ConformerForXVector with TDNN layers and AMSoftmax loss for speaker verification', 'create a Wav2Vec2ConformerForCTC model for automatic speech recognition with CTC loss', 'build a Wav2Vec2ConformerSelfAttention module with rotary or relative positional embeddings', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss on audio inputs', 'build a Wav2Vec2ConformerEncoderLayer conformer block with feed-forward, self-attention, and convolution modules']
```

Usage

```
{'create_wav2vec2_conformer_config': 'create a Wav2Vec2ConformerConfig instance with default speech recognition model settings', 'create_custom_wav2vec2_conformer_config': 'create a Wav2Vec2ConformerConfig with custom conv_dim, hidden_size, and num_hidden_layers parameters', 'validate_wav2vec2_conformer_config': 'validate the Wav2Vec2ConformerConfig architecture ensuring conv_dim, conv_stride, and conv_kernel lengths match', 'compute_inputs_to_logits_ratio': 'compute the inputs_to_logits_ratio property from Wav2Vec2ConformerConfig conv_stride values', 'initialize_wav2vec2_conformer_model': 'initialize a Wav2Vec2ConformerModel using a Wav2Vec2ConformerConfig for random weight initialization'}
```

## File: huggingface_transformers/src/transformers/models/wav2vec2_conformer/convert_wav2vec2_conformer_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['create a Wav2Vec2ConformerConfig instance with default speech recognition model settings', 'create a Wav2Vec2ConformerConfig with custom conv_dim, hidden_size, and num_hidden_layers parameters', 'validate the Wav2Vec2ConformerConfig architecture ensuring conv_dim, conv_stride, and conv_kernel lengths match', 'compute the inputs_to_logits_ratio property from Wav2Vec2ConformerConfig conv_stride values', 'initialize a Wav2Vec2ConformerModel using a Wav2Vec2ConformerConfig for random weight initialization', 'convert a fairseq wav2vec2 conformer checkpoint to a Hugging Face PyTorch model', 'load convolutional layer weights from a fairseq checkpoint into the feature extractor', 'recursively map and load fairseq model weights into a Hugging Face wav2vec2 conformer model', 'set tensor values recursively on a Hugging Face model pointer with shape validation', 'run the CLI script to convert a fairseq wav2vec2 conformer checkpoint to Hugging Face format', 'build a Wav2Vec2ConformerModel to extract audio features from raw speech waveform tensors', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss for self-supervised audio learning', 'run Wav2Vec2ConformerForCTC with CTC loss for automatic speech recognition with a language modeling head', 'run Wav2Vec2ConformerForSequenceClassification to classify audio inputs into discrete label categories', 'run Wav2Vec2ConformerForXVector with TDNN layers and AMSoftmax loss for speaker verification', 'create a Wav2Vec2ConformerForCTC model for automatic speech recognition with CTC loss', 'build a Wav2Vec2ConformerSelfAttention module with rotary or relative positional embeddings', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss on audio inputs', 'build a Wav2Vec2ConformerEncoderLayer conformer block with feed-forward, self-attention, and convolution modules']
```

Usage

```
{'convert_wav2vec2_conformer_checkpoint': 'convert a fairseq wav2vec2 conformer checkpoint to a Hugging Face PyTorch model', 'load_conv_layer': 'load convolutional layer weights from a fairseq checkpoint into the feature extractor', 'recursively_load_weights': 'recursively map and load fairseq model weights into a Hugging Face wav2vec2 conformer model', 'set_recursively': 'set tensor values recursively on a Hugging Face model pointer with shape validation', 'run_cli_convert': 'run the CLI script to convert a fairseq wav2vec2 conformer checkpoint to Hugging Face format'}
```

## File: huggingface_transformers/src/transformers/models/wav2vec2_conformer/modeling_wav2vec2_conformer.py

Prompts

```
['create a Wav2Vec2ConformerConfig instance with default speech recognition model settings', 'create a Wav2Vec2ConformerConfig with custom conv_dim, hidden_size, and num_hidden_layers parameters', 'validate the Wav2Vec2ConformerConfig architecture ensuring conv_dim, conv_stride, and conv_kernel lengths match', 'compute the inputs_to_logits_ratio property from Wav2Vec2ConformerConfig conv_stride values', 'initialize a Wav2Vec2ConformerModel using a Wav2Vec2ConformerConfig for random weight initialization', 'convert a fairseq wav2vec2 conformer checkpoint to a Hugging Face PyTorch model', 'load convolutional layer weights from a fairseq checkpoint into the feature extractor', 'recursively map and load fairseq model weights into a Hugging Face wav2vec2 conformer model', 'set tensor values recursively on a Hugging Face model pointer with shape validation', 'run the CLI script to convert a fairseq wav2vec2 conformer checkpoint to Hugging Face format', 'build a Wav2Vec2ConformerModel to extract audio features from raw speech waveform tensors', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss for self-supervised audio learning', 'run Wav2Vec2ConformerForCTC with CTC loss for automatic speech recognition with a language modeling head', 'run Wav2Vec2ConformerForSequenceClassification to classify audio inputs into discrete label categories', 'run Wav2Vec2ConformerForXVector with TDNN layers and AMSoftmax loss for speaker verification', 'create a Wav2Vec2ConformerForCTC model for automatic speech recognition with CTC loss', 'build a Wav2Vec2ConformerSelfAttention module with rotary or relative positional embeddings', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss on audio inputs', 'build a Wav2Vec2ConformerEncoderLayer conformer block with feed-forward, self-attention, and convolution modules']
```

Usage

```
{'build_wav2vec2_conformer_model': 'build a Wav2Vec2ConformerModel to extract audio features from raw speech waveform tensors', 'run_wav2vec2_conformer_for_pretraining': 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss for self-supervised audio learning', 'run_wav2vec2_conformer_for_ctc': 'run Wav2Vec2ConformerForCTC with CTC loss for automatic speech recognition with a language modeling head', 'run_wav2vec2_conformer_for_sequence_classification': 'run Wav2Vec2ConformerForSequenceClassification to classify audio inputs into discrete label categories', 'run_wav2vec2_conformer_for_xvector': 'run Wav2Vec2ConformerForXVector with TDNN layers and AMSoftmax loss for speaker verification'}
```

## File: huggingface_transformers/src/transformers/models/wav2vec2_conformer/modular_wav2vec2_conformer.py

Prompts

```
['create a Wav2Vec2ConformerConfig instance with default speech recognition model settings', 'create a Wav2Vec2ConformerConfig with custom conv_dim, hidden_size, and num_hidden_layers parameters', 'validate the Wav2Vec2ConformerConfig architecture ensuring conv_dim, conv_stride, and conv_kernel lengths match', 'compute the inputs_to_logits_ratio property from Wav2Vec2ConformerConfig conv_stride values', 'initialize a Wav2Vec2ConformerModel using a Wav2Vec2ConformerConfig for random weight initialization', 'convert a fairseq wav2vec2 conformer checkpoint to a Hugging Face PyTorch model', 'load convolutional layer weights from a fairseq checkpoint into the feature extractor', 'recursively map and load fairseq model weights into a Hugging Face wav2vec2 conformer model', 'set tensor values recursively on a Hugging Face model pointer with shape validation', 'run the CLI script to convert a fairseq wav2vec2 conformer checkpoint to Hugging Face format', 'build a Wav2Vec2ConformerModel to extract audio features from raw speech waveform tensors', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss for self-supervised audio learning', 'run Wav2Vec2ConformerForCTC with CTC loss for automatic speech recognition with a language modeling head', 'run Wav2Vec2ConformerForSequenceClassification to classify audio inputs into discrete label categories', 'run Wav2Vec2ConformerForXVector with TDNN layers and AMSoftmax loss for speaker verification', 'create a Wav2Vec2ConformerForCTC model for automatic speech recognition with CTC loss', 'build a Wav2Vec2ConformerSelfAttention module with rotary or relative positional embeddings', 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss on audio inputs', 'build a Wav2Vec2ConformerEncoderLayer conformer block with feed-forward, self-attention, and convolution modules']
```

Usage

```
{'build_wav2vec2_conformer_model': 'build a Wav2Vec2ConformerModel from a Wav2Vec2ConformerConfig for audio feature extraction', 'create_wav2vec2_conformer_for_ctc': 'create a Wav2Vec2ConformerForCTC model for automatic speech recognition with CTC loss', 'build_wav2vec2_conformer_self_attention': 'build a Wav2Vec2ConformerSelfAttention module with rotary or relative positional embeddings', 'run_wav2vec2_conformer_pretraining': 'run Wav2Vec2ConformerForPreTraining with contrastive and diversity loss on audio inputs', 'build_wav2vec2_conformer_encoder_layer': 'build a Wav2Vec2ConformerEncoderLayer conformer block with feed-forward, self-attention, and convolution modules'}
```

