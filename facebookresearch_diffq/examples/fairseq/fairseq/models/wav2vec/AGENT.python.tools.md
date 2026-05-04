# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/models/wav2vec/wav2vec.py

Prompts

```
['build a Wav2VecModel from Wav2VecConfig to extract audio features using convolutional layers', 'create a ConvFeatureExtractionModel with configurable conv layers and log compression for audio feature extraction', 'create a ConvAggegator with skip connections and residual scaling to aggregate extracted audio features', 'create a Wav2VecPredictionsModel to compute contrastive CPC logits and targets from aggregated features', 'review the Wav2VecConfig dataclass to understand hyperparameters for prediction steps, negatives, and vector quantization', 'build a Wav2Vec2Model from a Wav2Vec2Config to pre-train on raw audio waveforms', 'extract contextual features from audio waveforms using the Wav2Vec2Model extract_features method', 'quantize audio features using the GumbelVectorQuantizer in Wav2Vec2Model to get discrete codes', 'remove pre-training modules like quantizer and final_proj from Wav2Vec2Model for fine-tuning', 'configure a Wav2Vec2Config dataclass to set encoder layers, dropout, masking, and quantization parameters', 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build a wav2vec seq2seq model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'build a Wav2VecEncoder from a Wav2Vec2AsrConfig to extract audio features', 'build a TransformerDecoder for wav2vec seq2seq using TransformerDecoder with config and dictionary', 'create a normalized nn.Embedding layer with padding index using the Embedding helper function']
```

Usage

```
{'build_wav2vec_model': 'build a Wav2VecModel from Wav2VecConfig to extract audio features using convolutional layers', 'create_conv_feature_extractor': 'create a ConvFeatureExtractionModel with configurable conv layers and log compression for audio feature extraction', 'create_conv_aggregator': 'create a ConvAggegator with skip connections and residual scaling to aggregate extracted audio features', 'create_wav2vec_predictions': 'create a Wav2VecPredictionsModel to compute contrastive CPC logits and targets from aggregated features', 'review_wav2vec_config': 'review the Wav2VecConfig dataclass to understand hyperparameters for prediction steps, negatives, and vector quantization'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/models/wav2vec/wav2vec2.py

Prompts

```
['build a Wav2VecModel from Wav2VecConfig to extract audio features using convolutional layers', 'create a ConvFeatureExtractionModel with configurable conv layers and log compression for audio feature extraction', 'create a ConvAggegator with skip connections and residual scaling to aggregate extracted audio features', 'create a Wav2VecPredictionsModel to compute contrastive CPC logits and targets from aggregated features', 'review the Wav2VecConfig dataclass to understand hyperparameters for prediction steps, negatives, and vector quantization', 'build a Wav2Vec2Model from a Wav2Vec2Config to pre-train on raw audio waveforms', 'extract contextual features from audio waveforms using the Wav2Vec2Model extract_features method', 'quantize audio features using the GumbelVectorQuantizer in Wav2Vec2Model to get discrete codes', 'remove pre-training modules like quantizer and final_proj from Wav2Vec2Model for fine-tuning', 'configure a Wav2Vec2Config dataclass to set encoder layers, dropout, masking, and quantization parameters', 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build a wav2vec seq2seq model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'build a Wav2VecEncoder from a Wav2Vec2AsrConfig to extract audio features', 'build a TransformerDecoder for wav2vec seq2seq using TransformerDecoder with config and dictionary', 'create a normalized nn.Embedding layer with padding index using the Embedding helper function']
```

Usage

```
{'build_wav2vec2_model': 'build a Wav2Vec2Model from a Wav2Vec2Config to pre-train on raw audio waveforms', 'extract_features_wav2vec2': 'extract contextual features from audio waveforms using the Wav2Vec2Model extract_features method', 'quantize_wav2vec2': 'quantize audio features using the GumbelVectorQuantizer in Wav2Vec2Model to get discrete codes', 'remove_pretraining_modules': 'remove pre-training modules like quantizer and final_proj from Wav2Vec2Model for fine-tuning', 'configure_wav2vec2': 'configure a Wav2Vec2Config dataclass to set encoder layers, dropout, masking, and quantization parameters'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/models/wav2vec/wav2vec2_asr.py

Prompts

```
['build a Wav2VecModel from Wav2VecConfig to extract audio features using convolutional layers', 'create a ConvFeatureExtractionModel with configurable conv layers and log compression for audio feature extraction', 'create a ConvAggegator with skip connections and residual scaling to aggregate extracted audio features', 'create a Wav2VecPredictionsModel to compute contrastive CPC logits and targets from aggregated features', 'review the Wav2VecConfig dataclass to understand hyperparameters for prediction steps, negatives, and vector quantization', 'build a Wav2Vec2Model from a Wav2Vec2Config to pre-train on raw audio waveforms', 'extract contextual features from audio waveforms using the Wav2Vec2Model extract_features method', 'quantize audio features using the GumbelVectorQuantizer in Wav2Vec2Model to get discrete codes', 'remove pre-training modules like quantizer and final_proj from Wav2Vec2Model for fine-tuning', 'configure a Wav2Vec2Config dataclass to set encoder layers, dropout, masking, and quantization parameters', 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build a wav2vec seq2seq model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'build a Wav2VecEncoder from a Wav2Vec2AsrConfig to extract audio features', 'build a TransformerDecoder for wav2vec seq2seq using TransformerDecoder with config and dictionary', 'create a normalized nn.Embedding layer with padding index using the Embedding helper function']
```

Usage

```
{'build_wav2vec_ctc_model': 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build_wav2vec_seq2seq_model': 'build a wav2vec seq2seq model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'build_wav2vec_encoder': 'build a Wav2VecEncoder from a Wav2Vec2AsrConfig to extract audio features', 'build_transformer_decoder': 'build a TransformerDecoder for wav2vec seq2seq using TransformerDecoder with config and dictionary', 'create_embedding_layer': 'create a normalized nn.Embedding layer with padding index using the Embedding helper function'}
```

