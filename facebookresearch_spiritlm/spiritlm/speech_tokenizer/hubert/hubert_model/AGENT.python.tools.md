# Agent Python Tools

- repo: facebookresearch/spiritlm
- repo_uri: https://github.com/facebookresearch/spiritlm

## File: facebookresearch_spiritlm/spiritlm/speech_tokenizer/hubert/hubert_model/hubert_model.py

Prompts

```
['load a HuBERT model from a checkpoint file for inference or fine-tuning', 'build a new HuBERT model instance from HubertConfig and task configuration', 'extract speech features from audio waveforms using the HuBERT model encoder', 'apply temporal and channel masking to HuBERT model features for pretraining', 'remove pretraining-specific modules from a HuBERT model for downstream fine-tuning', 'build a Wav2Vec2Model from a Wav2Vec2Config to extract speech features from audio waveforms', 'extract speech features from audio using Wav2Vec2Model.extract_features with padding mask support', 'quantize extracted speech features using GumbelVectorQuantizer with configurable codebook groups and temperature', 'build a ConformerEncoder with relative positional encoding or rotary embeddings for speech processing', 'compute random mask spans for masked speech pretraining with static uniform normal or poisson distribution']
```

Usage

```
{'load_hubert_model': 'load a HuBERT model from a checkpoint file for inference or fine-tuning', 'build_hubert_model': 'build a new HuBERT model instance from HubertConfig and task configuration', 'extract_features': 'extract speech features from audio waveforms using the HuBERT model encoder', 'apply_mask': 'apply temporal and channel masking to HuBERT model features for pretraining', 'remove_pretraining_modules': 'remove pretraining-specific modules from a HuBERT model for downstream fine-tuning'}
```

## File: facebookresearch_spiritlm/spiritlm/speech_tokenizer/hubert/hubert_model/wav2vec2_model.py

Prompts

```
['load a HuBERT model from a checkpoint file for inference or fine-tuning', 'build a new HuBERT model instance from HubertConfig and task configuration', 'extract speech features from audio waveforms using the HuBERT model encoder', 'apply temporal and channel masking to HuBERT model features for pretraining', 'remove pretraining-specific modules from a HuBERT model for downstream fine-tuning', 'build a Wav2Vec2Model from a Wav2Vec2Config to extract speech features from audio waveforms', 'extract speech features from audio using Wav2Vec2Model.extract_features with padding mask support', 'quantize extracted speech features using GumbelVectorQuantizer with configurable codebook groups and temperature', 'build a ConformerEncoder with relative positional encoding or rotary embeddings for speech processing', 'compute random mask spans for masked speech pretraining with static uniform normal or poisson distribution']
```

Usage

```
{'build_wav2vec2_model': 'build a Wav2Vec2Model from a Wav2Vec2Config to extract speech features from audio waveforms', 'extract_features_wav2vec2': 'extract speech features from audio using Wav2Vec2Model.extract_features with padding mask support', 'quantize_features_gumbel': 'quantize extracted speech features using GumbelVectorQuantizer with configurable codebook groups and temperature', 'build_conformer_encoder': 'build a ConformerEncoder with relative positional encoding or rotary embeddings for speech processing', 'compute_mask_indices': 'compute random mask spans for masked speech pretraining with static uniform normal or poisson distribution'}
```

