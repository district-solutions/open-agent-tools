# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/models/wav2vec/wav2vec.py

Prompts

```
['build a Wav2VecModel from Wav2VecConfig to extract self-supervised audio representations from raw waveforms', 'create a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio waveforms', 'create a ConvAggegator with configurable conv layers and skip connections to aggregate extracted audio features', 'create a Wav2VecPredictionsModel to compute contrastive CPC predictions with negative sampling for audio pretraining', 'review the Wav2VecConfig dataclass to understand hyperparameters for convolutional layers, dropout, and vector quantization', 'build a Wav2Vec2Model instance from a Wav2Vec2Config to pretrain on raw audio waveforms', 'extract features from raw audio using Wav2Vec2Model extract_features with optional masking disabled', 'quantize audio features to discrete codes using Wav2Vec2Model quantize with a GumbelVectorQuantizer', 'remove pretraining modules from Wav2Vec2Model to prepare for fine-tuning on a downstream task', 'build a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio', 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build a wav2vec seq2seq ASR model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'extract audio features from source audio using Wav2VecEncoder.forward with source and padding mask', 'get CTC logits from network output using Wav2VecCtc.get_logits with optional normalization', 'decode target tokens using TransformerDecoder.forward with encoder output and incremental state']
```

Usage

```
{'build_Wav2VecModel': 'build a Wav2VecModel from Wav2VecConfig to extract self-supervised audio representations from raw waveforms', 'create_ConvFeatureExtractionModel': 'create a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio waveforms', 'create_ConvAggegator': 'create a ConvAggegator with configurable conv layers and skip connections to aggregate extracted audio features', 'create_Wav2VecPredictionsModel': 'create a Wav2VecPredictionsModel to compute contrastive CPC predictions with negative sampling for audio pretraining', 'review_Wav2VecConfig': 'review the Wav2VecConfig dataclass to understand hyperparameters for convolutional layers, dropout, and vector quantization'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/models/wav2vec/wav2vec2.py

Prompts

```
['build a Wav2VecModel from Wav2VecConfig to extract self-supervised audio representations from raw waveforms', 'create a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio waveforms', 'create a ConvAggegator with configurable conv layers and skip connections to aggregate extracted audio features', 'create a Wav2VecPredictionsModel to compute contrastive CPC predictions with negative sampling for audio pretraining', 'review the Wav2VecConfig dataclass to understand hyperparameters for convolutional layers, dropout, and vector quantization', 'build a Wav2Vec2Model instance from a Wav2Vec2Config to pretrain on raw audio waveforms', 'extract features from raw audio using Wav2Vec2Model extract_features with optional masking disabled', 'quantize audio features to discrete codes using Wav2Vec2Model quantize with a GumbelVectorQuantizer', 'remove pretraining modules from Wav2Vec2Model to prepare for fine-tuning on a downstream task', 'build a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio', 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build a wav2vec seq2seq ASR model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'extract audio features from source audio using Wav2VecEncoder.forward with source and padding mask', 'get CTC logits from network output using Wav2VecCtc.get_logits with optional normalization', 'decode target tokens using TransformerDecoder.forward with encoder output and incremental state']
```

Usage

```
{'build_wav2vec2_model': 'build a Wav2Vec2Model instance from a Wav2Vec2Config to pretrain on raw audio waveforms', 'extract_features_wav2vec2': 'extract features from raw audio using Wav2Vec2Model extract_features with optional masking disabled', 'quantize_wav2vec2': 'quantize audio features to discrete codes using Wav2Vec2Model quantize with a GumbelVectorQuantizer', 'remove_pretraining_modules': 'remove pretraining modules from Wav2Vec2Model to prepare for fine-tuning on a downstream task', 'build_conv_feature_extractor': 'build a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/models/wav2vec/wav2vec2_asr.py

Prompts

```
['build a Wav2VecModel from Wav2VecConfig to extract self-supervised audio representations from raw waveforms', 'create a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio waveforms', 'create a ConvAggegator with configurable conv layers and skip connections to aggregate extracted audio features', 'create a Wav2VecPredictionsModel to compute contrastive CPC predictions with negative sampling for audio pretraining', 'review the Wav2VecConfig dataclass to understand hyperparameters for convolutional layers, dropout, and vector quantization', 'build a Wav2Vec2Model instance from a Wav2Vec2Config to pretrain on raw audio waveforms', 'extract features from raw audio using Wav2Vec2Model extract_features with optional masking disabled', 'quantize audio features to discrete codes using Wav2Vec2Model quantize with a GumbelVectorQuantizer', 'remove pretraining modules from Wav2Vec2Model to prepare for fine-tuning on a downstream task', 'build a ConvFeatureExtractionModel with configurable conv layers to extract features from raw audio', 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build a wav2vec seq2seq ASR model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'extract audio features from source audio using Wav2VecEncoder.forward with source and padding mask', 'get CTC logits from network output using Wav2VecCtc.get_logits with optional normalization', 'decode target tokens using TransformerDecoder.forward with encoder output and incremental state']
```

Usage

```
{'build_wav2vec_ctc_model': 'build a wav2vec CTC ASR model using Wav2VecCtc.build_model with config and task', 'build_wav2vec_seq2seq_model': 'build a wav2vec seq2seq ASR model using Wav2Vec2Seq2SeqModel.build_model with config and task', 'extract_features_wav2vec_encoder': 'extract audio features from source audio using Wav2VecEncoder.forward with source and padding mask', 'get_logits_wav2vec_ctc': 'get CTC logits from network output using Wav2VecCtc.get_logits with optional normalization', 'decode_transformer_decoder': 'decode target tokens using TransformerDecoder.forward with encoder output and incremental state'}
```

