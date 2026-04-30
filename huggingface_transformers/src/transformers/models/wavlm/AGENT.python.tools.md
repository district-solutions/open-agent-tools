# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/wavlm/configuration_wavlm.py

Prompts

```
['create a WavLMConfig instance with default hyperparameters for the WavLM speech model', 'create a WavLMConfig instance with custom conv_dim, hidden_size, and num_hidden_layers', 'validate the WavLMConfig architecture by ensuring conv_dim, conv_stride, and conv_kernel have matching lengths', 'compute the inputs_to_logits_ratio property from WavLMConfig conv_stride tuple', 'initialize a WavLMModel with a WavLMConfig instance for speech recognition tasks', 'convert a fairseq WavLM checkpoint to a Hugging Face WavLM model and save to disk', 'recursively load and map fairseq model weights to a Hugging Face WavLM model', 'set tensor values recursively on a Hugging Face model pointer by dotted key path', 'load feature extractor convolution layer weights from fairseq into Hugging Face WavLM', 'run the CLI to convert a WavLM fairseq checkpoint to a Hugging Face PyTorch model', 'convert an S3PRL WavLM checkpoint to HuggingFace transformers format using argparse CLI', 'convert S3PRL downstream classification weights to a HuggingFace WavLMForSequenceClassification model', 'convert S3PRL diarization weights to a HuggingFace WavLMForAudioFrameClassification model', 'convert S3PRL x-vector embedding weights to a HuggingFace WavLMForXVector model', 'summarize the S3PRL-to-HuggingFace WavLM checkpoint conversion CLI tool', 'build a WavLM base model for self-supervised speech feature extraction', 'create a WavLM model with CTC language modeling head for automatic speech recognition', 'run a WavLM model with sequence classification head for keyword spotting tasks', 'test a WavLM model with XVector head for speaker verification tasks', 'summarize a WavLM model with token classification head for audio frame classification', 'create WavLMAttention with relative position bias and gated GRU-based positional encoding', 'build WavLMEncoder with positional conv embedding, layer drop, and multi-head self-attention layers', 'run WavLMForCTC for automatic speech recognition with connectionist temporal classification', 'build WavLMForSequenceClassification for audio sequence classification tasks']
```

Usage

```
{'create_wavlm_config': 'create a WavLMConfig instance with default hyperparameters for the WavLM speech model', 'create_wavlm_config_custom': 'create a WavLMConfig instance with custom conv_dim, hidden_size, and num_hidden_layers', 'validate_wavlm_config': 'validate the WavLMConfig architecture by ensuring conv_dim, conv_stride, and conv_kernel have matching lengths', 'compute_inputs_to_logits_ratio': 'compute the inputs_to_logits_ratio property from WavLMConfig conv_stride tuple', 'initialize_wavlm_model': 'initialize a WavLMModel with a WavLMConfig instance for speech recognition tasks'}
```

## File: huggingface_transformers/src/transformers/models/wavlm/convert_wavlm_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['create a WavLMConfig instance with default hyperparameters for the WavLM speech model', 'create a WavLMConfig instance with custom conv_dim, hidden_size, and num_hidden_layers', 'validate the WavLMConfig architecture by ensuring conv_dim, conv_stride, and conv_kernel have matching lengths', 'compute the inputs_to_logits_ratio property from WavLMConfig conv_stride tuple', 'initialize a WavLMModel with a WavLMConfig instance for speech recognition tasks', 'convert a fairseq WavLM checkpoint to a Hugging Face WavLM model and save to disk', 'recursively load and map fairseq model weights to a Hugging Face WavLM model', 'set tensor values recursively on a Hugging Face model pointer by dotted key path', 'load feature extractor convolution layer weights from fairseq into Hugging Face WavLM', 'run the CLI to convert a WavLM fairseq checkpoint to a Hugging Face PyTorch model', 'convert an S3PRL WavLM checkpoint to HuggingFace transformers format using argparse CLI', 'convert S3PRL downstream classification weights to a HuggingFace WavLMForSequenceClassification model', 'convert S3PRL diarization weights to a HuggingFace WavLMForAudioFrameClassification model', 'convert S3PRL x-vector embedding weights to a HuggingFace WavLMForXVector model', 'summarize the S3PRL-to-HuggingFace WavLM checkpoint conversion CLI tool', 'build a WavLM base model for self-supervised speech feature extraction', 'create a WavLM model with CTC language modeling head for automatic speech recognition', 'run a WavLM model with sequence classification head for keyword spotting tasks', 'test a WavLM model with XVector head for speaker verification tasks', 'summarize a WavLM model with token classification head for audio frame classification', 'create WavLMAttention with relative position bias and gated GRU-based positional encoding', 'build WavLMEncoder with positional conv embedding, layer drop, and multi-head self-attention layers', 'run WavLMForCTC for automatic speech recognition with connectionist temporal classification', 'build WavLMForSequenceClassification for audio sequence classification tasks']
```

Usage

```
{'convert_wavlm_checkpoint': 'convert a fairseq WavLM checkpoint to a Hugging Face WavLM model and save to disk', 'recursively_load_weights': 'recursively load and map fairseq model weights to a Hugging Face WavLM model', 'set_recursively': 'set tensor values recursively on a Hugging Face model pointer by dotted key path', 'load_conv_layer': 'load feature extractor convolution layer weights from fairseq into Hugging Face WavLM', 'convert_wavlm_cli': 'run the CLI to convert a WavLM fairseq checkpoint to a Hugging Face PyTorch model'}
```

## File: huggingface_transformers/src/transformers/models/wavlm/convert_wavlm_original_s3prl_checkpoint_to_pytorch.py

Prompts

```
['create a WavLMConfig instance with default hyperparameters for the WavLM speech model', 'create a WavLMConfig instance with custom conv_dim, hidden_size, and num_hidden_layers', 'validate the WavLMConfig architecture by ensuring conv_dim, conv_stride, and conv_kernel have matching lengths', 'compute the inputs_to_logits_ratio property from WavLMConfig conv_stride tuple', 'initialize a WavLMModel with a WavLMConfig instance for speech recognition tasks', 'convert a fairseq WavLM checkpoint to a Hugging Face WavLM model and save to disk', 'recursively load and map fairseq model weights to a Hugging Face WavLM model', 'set tensor values recursively on a Hugging Face model pointer by dotted key path', 'load feature extractor convolution layer weights from fairseq into Hugging Face WavLM', 'run the CLI to convert a WavLM fairseq checkpoint to a Hugging Face PyTorch model', 'convert an S3PRL WavLM checkpoint to HuggingFace transformers format using argparse CLI', 'convert S3PRL downstream classification weights to a HuggingFace WavLMForSequenceClassification model', 'convert S3PRL diarization weights to a HuggingFace WavLMForAudioFrameClassification model', 'convert S3PRL x-vector embedding weights to a HuggingFace WavLMForXVector model', 'summarize the S3PRL-to-HuggingFace WavLM checkpoint conversion CLI tool', 'build a WavLM base model for self-supervised speech feature extraction', 'create a WavLM model with CTC language modeling head for automatic speech recognition', 'run a WavLM model with sequence classification head for keyword spotting tasks', 'test a WavLM model with XVector head for speaker verification tasks', 'summarize a WavLM model with token classification head for audio frame classification', 'create WavLMAttention with relative position bias and gated GRU-based positional encoding', 'build WavLMEncoder with positional conv embedding, layer drop, and multi-head self-attention layers', 'run WavLMForCTC for automatic speech recognition with connectionist temporal classification', 'build WavLMForSequenceClassification for audio sequence classification tasks']
```

Usage

```
{'convert_s3prl_checkpoint': 'convert an S3PRL WavLM checkpoint to HuggingFace transformers format using argparse CLI', 'convert_classification': 'convert S3PRL downstream classification weights to a HuggingFace WavLMForSequenceClassification model', 'convert_diarization': 'convert S3PRL diarization weights to a HuggingFace WavLMForAudioFrameClassification model', 'convert_xvector': 'convert S3PRL x-vector embedding weights to a HuggingFace WavLMForXVector model', 'summarize_convert_s3prl_checkpoint': 'summarize the S3PRL-to-HuggingFace WavLM checkpoint conversion CLI tool'}
```

## File: huggingface_transformers/src/transformers/models/wavlm/modeling_wavlm.py

Prompts

```
['create a WavLMConfig instance with default hyperparameters for the WavLM speech model', 'create a WavLMConfig instance with custom conv_dim, hidden_size, and num_hidden_layers', 'validate the WavLMConfig architecture by ensuring conv_dim, conv_stride, and conv_kernel have matching lengths', 'compute the inputs_to_logits_ratio property from WavLMConfig conv_stride tuple', 'initialize a WavLMModel with a WavLMConfig instance for speech recognition tasks', 'convert a fairseq WavLM checkpoint to a Hugging Face WavLM model and save to disk', 'recursively load and map fairseq model weights to a Hugging Face WavLM model', 'set tensor values recursively on a Hugging Face model pointer by dotted key path', 'load feature extractor convolution layer weights from fairseq into Hugging Face WavLM', 'run the CLI to convert a WavLM fairseq checkpoint to a Hugging Face PyTorch model', 'convert an S3PRL WavLM checkpoint to HuggingFace transformers format using argparse CLI', 'convert S3PRL downstream classification weights to a HuggingFace WavLMForSequenceClassification model', 'convert S3PRL diarization weights to a HuggingFace WavLMForAudioFrameClassification model', 'convert S3PRL x-vector embedding weights to a HuggingFace WavLMForXVector model', 'summarize the S3PRL-to-HuggingFace WavLM checkpoint conversion CLI tool', 'build a WavLM base model for self-supervised speech feature extraction', 'create a WavLM model with CTC language modeling head for automatic speech recognition', 'run a WavLM model with sequence classification head for keyword spotting tasks', 'test a WavLM model with XVector head for speaker verification tasks', 'summarize a WavLM model with token classification head for audio frame classification', 'create WavLMAttention with relative position bias and gated GRU-based positional encoding', 'build WavLMEncoder with positional conv embedding, layer drop, and multi-head self-attention layers', 'run WavLMForCTC for automatic speech recognition with connectionist temporal classification', 'build WavLMForSequenceClassification for audio sequence classification tasks']
```

Usage

```
{'build_wavlm_model': 'build a WavLM base model for self-supervised speech feature extraction', 'create_wavlm_for_ctc': 'create a WavLM model with CTC language modeling head for automatic speech recognition', 'run_wavlm_for_sequence_classification': 'run a WavLM model with sequence classification head for keyword spotting tasks', 'test_wavlm_for_xvector': 'test a WavLM model with XVector head for speaker verification tasks', 'summarize_wavlm_for_audio_frame_classification': 'summarize a WavLM model with token classification head for audio frame classification'}
```

## File: huggingface_transformers/src/transformers/models/wavlm/modular_wavlm.py

Prompts

```
['create a WavLMConfig instance with default hyperparameters for the WavLM speech model', 'create a WavLMConfig instance with custom conv_dim, hidden_size, and num_hidden_layers', 'validate the WavLMConfig architecture by ensuring conv_dim, conv_stride, and conv_kernel have matching lengths', 'compute the inputs_to_logits_ratio property from WavLMConfig conv_stride tuple', 'initialize a WavLMModel with a WavLMConfig instance for speech recognition tasks', 'convert a fairseq WavLM checkpoint to a Hugging Face WavLM model and save to disk', 'recursively load and map fairseq model weights to a Hugging Face WavLM model', 'set tensor values recursively on a Hugging Face model pointer by dotted key path', 'load feature extractor convolution layer weights from fairseq into Hugging Face WavLM', 'run the CLI to convert a WavLM fairseq checkpoint to a Hugging Face PyTorch model', 'convert an S3PRL WavLM checkpoint to HuggingFace transformers format using argparse CLI', 'convert S3PRL downstream classification weights to a HuggingFace WavLMForSequenceClassification model', 'convert S3PRL diarization weights to a HuggingFace WavLMForAudioFrameClassification model', 'convert S3PRL x-vector embedding weights to a HuggingFace WavLMForXVector model', 'summarize the S3PRL-to-HuggingFace WavLM checkpoint conversion CLI tool', 'build a WavLM base model for self-supervised speech feature extraction', 'create a WavLM model with CTC language modeling head for automatic speech recognition', 'run a WavLM model with sequence classification head for keyword spotting tasks', 'test a WavLM model with XVector head for speaker verification tasks', 'summarize a WavLM model with token classification head for audio frame classification', 'create WavLMAttention with relative position bias and gated GRU-based positional encoding', 'build WavLMEncoder with positional conv embedding, layer drop, and multi-head self-attention layers', 'run WavLMForCTC for automatic speech recognition with connectionist temporal classification', 'build WavLMForSequenceClassification for audio sequence classification tasks']
```

Usage

```
{'build_wavlm_model': 'build a WavLM model using WavLMModel with WavLMConfig for audio feature extraction', 'create_wavlm_attention': 'create WavLMAttention with relative position bias and gated GRU-based positional encoding', 'build_wavlm_encoder': 'build WavLMEncoder with positional conv embedding, layer drop, and multi-head self-attention layers', 'run_wavlm_for_ctc': 'run WavLMForCTC for automatic speech recognition with connectionist temporal classification', 'build_wavlm_for_classification': 'build WavLMForSequenceClassification for audio sequence classification tasks'}
```

