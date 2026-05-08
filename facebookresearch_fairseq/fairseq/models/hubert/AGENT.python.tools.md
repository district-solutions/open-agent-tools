# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/hubert/hubert.py

Prompts

```
['build a HubertModel instance from HubertConfig and HubertPretrainingTask for speech pretraining', 'run the HubertModel forward pass with source audio and target labels to compute NCE logits', 'extract features from audio source using HubertModel extract_features with optional masking', 'apply temporal and channel masking to HubertModel encoder input features during pretraining', 'remove pretraining modules from HubertModel to prepare for downstream fine-tuning tasks', 'build a HubertCtc model from config and task for CTC-based speech recognition', 'build a HubertSeq2SeqModel from config and task for autoregressive speech recognition', 'build a HubertEncoder that loads a pretrained HuBERT model and extracts features', 'review the TransformerDecoder class for autoregressive token generation with encoder attention', 'test the HubertEncoder forward pass with source and padding mask inputs']
```

Usage

```
{'build_hubert_model': 'build a HubertModel instance from HubertConfig and HubertPretrainingTask for speech pretraining', 'run_forward_hubert': 'run the HubertModel forward pass with source audio and target labels to compute NCE logits', 'extract_features_hubert': 'extract features from audio source using HubertModel extract_features with optional masking', 'apply_mask_hubert': 'apply temporal and channel masking to HubertModel encoder input features during pretraining', 'remove_pretraining_modules_hubert': 'remove pretraining modules from HubertModel to prepare for downstream fine-tuning tasks'}
```

## File: facebookresearch_fairseq/fairseq/models/hubert/hubert_asr.py

Prompts

```
['build a HubertModel instance from HubertConfig and HubertPretrainingTask for speech pretraining', 'run the HubertModel forward pass with source audio and target labels to compute NCE logits', 'extract features from audio source using HubertModel extract_features with optional masking', 'apply temporal and channel masking to HubertModel encoder input features during pretraining', 'remove pretraining modules from HubertModel to prepare for downstream fine-tuning tasks', 'build a HubertCtc model from config and task for CTC-based speech recognition', 'build a HubertSeq2SeqModel from config and task for autoregressive speech recognition', 'build a HubertEncoder that loads a pretrained HuBERT model and extracts features', 'review the TransformerDecoder class for autoregressive token generation with encoder attention', 'test the HubertEncoder forward pass with source and padding mask inputs']
```

Usage

```
{'build_hubert_ctc_model': 'build a HubertCtc model from config and task for CTC-based speech recognition', 'build_hubert_seq2seq_model': 'build a HubertSeq2SeqModel from config and task for autoregressive speech recognition', 'build_hubert_encoder': 'build a HubertEncoder that loads a pretrained HuBERT model and extracts features', 'review_transformer_decoder': 'review the TransformerDecoder class for autoregressive token generation with encoder attention', 'test_hubert_encoder_forward': 'test the HubertEncoder forward pass with source and padding mask inputs'}
```

