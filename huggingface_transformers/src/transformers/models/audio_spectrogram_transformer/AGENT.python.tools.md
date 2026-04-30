# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/audio_spectrogram_transformer/convert_audio_spectrogram_transformer_original_to_pytorch.py

Prompts

```
['convert an Audio Spectrogram Transformer checkpoint from the original AST repository to a Hugging Face PyTorch model', 'get the AST config for a given model name including stride, labels, and id2label mappings', 'rename a checkpoint key from the original AST naming convention to the Hugging Face AST naming convention', 'convert a state dict from the original AST format to the Hugging Face AST format splitting qkv weights into separate query key and value tensors', 'run the CLI conversion script to convert an AST checkpoint from the original repository to a Hugging Face model', 'create an ASTFeatureExtractor instance with custom num_mel_bins, max_length, and normalization parameters', 'extract mel-filter bank features from raw audio waveform and pad or truncate to a fixed max_length', 'normalize log-Mel spectrogram features using AudioSet mean and standard deviation values', 'call the feature extractor on raw speech audio and return padded input_values with optional tensor conversion', 'build an audio spectrogram transformer pipeline that extracts fbank features and normalizes them for model input', 'create an ASTModel instance for extracting audio spectrogram features from mel input tensors', 'build an ASTForAudioClassification model with a classifier head for audio classification tasks like AudioSet', 'test the ASTEmbeddings forward method that constructs CLS, distillation, and patch embeddings with positional encoding', 'review the ASTLayer forward method that applies layer norm, self-attention, and feed-forward with residual connections', 'summarize the ASTSelfAttention class that computes query, key, value projections and attention scores for audio sequences']
```

Usage

```
{'convert_audio_spectrogram_transformer_checkpoint': 'convert an Audio Spectrogram Transformer checkpoint from the original AST repository to a Hugging Face PyTorch model', 'get_audio_spectrogram_transformer_config': 'get the AST config for a given model name including stride, labels, and id2label mappings', 'rename_key': 'rename a checkpoint key from the original AST naming convention to the Hugging Face AST naming convention', 'convert_state_dict': 'convert a state dict from the original AST format to the Hugging Face AST format splitting qkv weights into separate query key and value tensors', 'run_ast_checkpoint_conversion_cli': 'run the CLI conversion script to convert an AST checkpoint from the original repository to a Hugging Face model'}
```

## File: huggingface_transformers/src/transformers/models/audio_spectrogram_transformer/feature_extraction_audio_spectrogram_transformer.py

Prompts

```
['convert an Audio Spectrogram Transformer checkpoint from the original AST repository to a Hugging Face PyTorch model', 'get the AST config for a given model name including stride, labels, and id2label mappings', 'rename a checkpoint key from the original AST naming convention to the Hugging Face AST naming convention', 'convert a state dict from the original AST format to the Hugging Face AST format splitting qkv weights into separate query key and value tensors', 'run the CLI conversion script to convert an AST checkpoint from the original repository to a Hugging Face model', 'create an ASTFeatureExtractor instance with custom num_mel_bins, max_length, and normalization parameters', 'extract mel-filter bank features from raw audio waveform and pad or truncate to a fixed max_length', 'normalize log-Mel spectrogram features using AudioSet mean and standard deviation values', 'call the feature extractor on raw speech audio and return padded input_values with optional tensor conversion', 'build an audio spectrogram transformer pipeline that extracts fbank features and normalizes them for model input', 'create an ASTModel instance for extracting audio spectrogram features from mel input tensors', 'build an ASTForAudioClassification model with a classifier head for audio classification tasks like AudioSet', 'test the ASTEmbeddings forward method that constructs CLS, distillation, and patch embeddings with positional encoding', 'review the ASTLayer forward method that applies layer norm, self-attention, and feed-forward with residual connections', 'summarize the ASTSelfAttention class that computes query, key, value projections and attention scores for audio sequences']
```

Usage

```
{'create_ASTFeatureExtractor': 'create an ASTFeatureExtractor instance with custom num_mel_bins, max_length, and normalization parameters', 'extract_fbank_features': 'extract mel-filter bank features from raw audio waveform and pad or truncate to a fixed max_length', 'normalize_audio_features': 'normalize log-Mel spectrogram features using AudioSet mean and standard deviation values', 'call_feature_extractor': 'call the feature extractor on raw speech audio and return padded input_values with optional tensor conversion', 'build_audio_pipeline': 'build an audio spectrogram transformer pipeline that extracts fbank features and normalizes them for model input'}
```

## File: huggingface_transformers/src/transformers/models/audio_spectrogram_transformer/modeling_audio_spectrogram_transformer.py

Prompts

```
['convert an Audio Spectrogram Transformer checkpoint from the original AST repository to a Hugging Face PyTorch model', 'get the AST config for a given model name including stride, labels, and id2label mappings', 'rename a checkpoint key from the original AST naming convention to the Hugging Face AST naming convention', 'convert a state dict from the original AST format to the Hugging Face AST format splitting qkv weights into separate query key and value tensors', 'run the CLI conversion script to convert an AST checkpoint from the original repository to a Hugging Face model', 'create an ASTFeatureExtractor instance with custom num_mel_bins, max_length, and normalization parameters', 'extract mel-filter bank features from raw audio waveform and pad or truncate to a fixed max_length', 'normalize log-Mel spectrogram features using AudioSet mean and standard deviation values', 'call the feature extractor on raw speech audio and return padded input_values with optional tensor conversion', 'build an audio spectrogram transformer pipeline that extracts fbank features and normalizes them for model input', 'create an ASTModel instance for extracting audio spectrogram features from mel input tensors', 'build an ASTForAudioClassification model with a classifier head for audio classification tasks like AudioSet', 'test the ASTEmbeddings forward method that constructs CLS, distillation, and patch embeddings with positional encoding', 'review the ASTLayer forward method that applies layer norm, self-attention, and feed-forward with residual connections', 'summarize the ASTSelfAttention class that computes query, key, value projections and attention scores for audio sequences']
```

Usage

```
{'create_ASTModel': 'create an ASTModel instance for extracting audio spectrogram features from mel input tensors', 'build_ASTForAudioClassification': 'build an ASTForAudioClassification model with a classifier head for audio classification tasks like AudioSet', 'test_ASTEmbeddings_forward': 'test the ASTEmbeddings forward method that constructs CLS, distillation, and patch embeddings with positional encoding', 'review_ASTLayer_forward': 'review the ASTLayer forward method that applies layer norm, self-attention, and feed-forward with residual connections', 'summarize_ASTSelfAttention': 'summarize the ASTSelfAttention class that computes query, key, value projections and attention scores for audio sequences'}
```

