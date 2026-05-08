# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/multires_hubert/multires_hubert.py

Prompts

```
['build a MultiresHubertModel instance using MultiresHubertConfig and a MultiresHubertPretrainingTask', 'review the ConvAdapter class to understand how it performs upsampling and downsampling with skip connections', 'refactor the MultiresHubertModel forward method to support additional resolution levels in the U-net architecture', 'summarize the MultiresHubertConfig dataclass fields including label_rate_ratios, encoder dimensions, and masking parameters', 'test the apply_mask method to verify temporal and channel masking behavior with different mask probabilities', 'build a MultiresHubertCtc model from config and task using the build_model class method', 'build a MultiresHubertEncoder that loads a pretrained multires HuBERT checkpoint and projects to target vocabulary', 'run the MultiresHubertEncoder forward pass with source and padding_mask to extract encoder features', 'get normalized softmax or log-softmax probabilities from the MultiresHubertCtc model output logits', 'get CTC logits from the MultiresHubertCtc model output with padding positions masked to negative infinity']
```

Usage

```
{'build_multires_hubert_model': 'build a MultiresHubertModel instance using MultiresHubertConfig and a MultiresHubertPretrainingTask', 'review_conv_adapter': 'review the ConvAdapter class to understand how it performs upsampling and downsampling with skip connections', 'refactor_forward_method': 'refactor the MultiresHubertModel forward method to support additional resolution levels in the U-net architecture', 'summarize_multires_hubert_config': 'summarize the MultiresHubertConfig dataclass fields including label_rate_ratios, encoder dimensions, and masking parameters', 'test_apply_mask': 'test the apply_mask method to verify temporal and channel masking behavior with different mask probabilities'}
```

## File: facebookresearch_fairseq/fairseq/models/multires_hubert/multires_hubert_asr.py

Prompts

```
['build a MultiresHubertModel instance using MultiresHubertConfig and a MultiresHubertPretrainingTask', 'review the ConvAdapter class to understand how it performs upsampling and downsampling with skip connections', 'refactor the MultiresHubertModel forward method to support additional resolution levels in the U-net architecture', 'summarize the MultiresHubertConfig dataclass fields including label_rate_ratios, encoder dimensions, and masking parameters', 'test the apply_mask method to verify temporal and channel masking behavior with different mask probabilities', 'build a MultiresHubertCtc model from config and task using the build_model class method', 'build a MultiresHubertEncoder that loads a pretrained multires HuBERT checkpoint and projects to target vocabulary', 'run the MultiresHubertEncoder forward pass with source and padding_mask to extract encoder features', 'get normalized softmax or log-softmax probabilities from the MultiresHubertCtc model output logits', 'get CTC logits from the MultiresHubertCtc model output with padding positions masked to negative infinity']
```

Usage

```
{'build_multires_hubert_ctc_model': 'build a MultiresHubertCtc model from config and task using the build_model class method', 'build_multires_hubert_encoder': 'build a MultiresHubertEncoder that loads a pretrained multires HuBERT checkpoint and projects to target vocabulary', 'run_multires_hubert_encoder_forward': 'run the MultiresHubertEncoder forward pass with source and padding_mask to extract encoder features', 'get_normalized_probs_from_ctc': 'get normalized softmax or log-softmax probabilities from the MultiresHubertCtc model output logits', 'get_logits_from_ctc': 'get CTC logits from the MultiresHubertCtc model output with padding positions masked to negative infinity'}
```

