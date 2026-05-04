# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/models/hubert/hubert.py

Prompts

```
['build a HubertModel instance using HubertConfig and HubertPretrainingTask for audio pretraining', 'extract audio features from source tensors using the HubertModel extract_features method', 'apply temporal and channel masking to HUBERT encoder input features during pretraining', 'compute NCE loss logits via cosine similarity between projected features and label embeddings', 'remove pretraining-specific modules like target_glu and final_proj to prepare HUBERT for fine-tuning', 'build a HubertCtc model instance using HubertCtc.build_model with config and task', 'build a HubertEncoder to extract features from audio source with padding mask', 'run the HubertCtc forward pass to get encoder output logits for CTC decoding', 'get normalized softmax or log softmax probabilities from HubertCtc encoder output', 'get CTC logits from HubertCtc net output with padding mask applied']
```

Usage

```
{'build_hubert_model': 'build a HubertModel instance using HubertConfig and HubertPretrainingTask for audio pretraining', 'extract_features_hubert': 'extract audio features from source tensors using the HubertModel extract_features method', 'apply_mask_hubert': 'apply temporal and channel masking to HUBERT encoder input features during pretraining', 'compute_nce_loss_hubert': 'compute NCE loss logits via cosine similarity between projected features and label embeddings', 'remove_pretraining_modules_hubert': 'remove pretraining-specific modules like target_glu and final_proj to prepare HUBERT for fine-tuning'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/models/hubert/hubert_asr.py

Prompts

```
['build a HubertModel instance using HubertConfig and HubertPretrainingTask for audio pretraining', 'extract audio features from source tensors using the HubertModel extract_features method', 'apply temporal and channel masking to HUBERT encoder input features during pretraining', 'compute NCE loss logits via cosine similarity between projected features and label embeddings', 'remove pretraining-specific modules like target_glu and final_proj to prepare HUBERT for fine-tuning', 'build a HubertCtc model instance using HubertCtc.build_model with config and task', 'build a HubertEncoder to extract features from audio source with padding mask', 'run the HubertCtc forward pass to get encoder output logits for CTC decoding', 'get normalized softmax or log softmax probabilities from HubertCtc encoder output', 'get CTC logits from HubertCtc net output with padding mask applied']
```

Usage

```
{'build_hubert_ctc_model': 'build a HubertCtc model instance using HubertCtc.build_model with config and task', 'build_hubert_encoder': 'build a HubertEncoder to extract features from audio source with padding mask', 'run_hubert_ctc_forward': 'run the HubertCtc forward pass to get encoder output logits for CTC decoding', 'get_normalized_probs': 'get normalized softmax or log softmax probabilities from HubertCtc encoder output', 'get_logits': 'get CTC logits from HubertCtc net output with padding mask applied'}
```

