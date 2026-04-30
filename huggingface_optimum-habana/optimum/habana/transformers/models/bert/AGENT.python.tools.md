# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/models/bert/modeling_bert.py

Prompts

```
['run the BERT model forward pass on HPU with bf16 autocast support using gaudi_BertModel_forward', 'run the BERT SDPA self-attention forward pass using Habana FusedSDPA for fast softmax on HPU', 'review the gaudi_BertModel_forward function to understand HPU-specific changes for bf16 autocast and attention mask handling', 'review the gaudi_Bert_Sdpa_SelfAttention_forward function to understand how FusedSDPA replaces scaled_dot_product_attention on HPU', 'refactor the BERT SDPA self-attention to use Habana FusedSDPA with fast softmax algorithm for inference on HPU']
```

Usage

```
{'run_bert_forward_hpu': 'run the BERT model forward pass on HPU with bf16 autocast support using gaudi_BertModel_forward', 'run_bert_sdpa_attention_hpu': 'run the BERT SDPA self-attention forward pass using Habana FusedSDPA for fast softmax on HPU', 'review_gaudi_bert_forward': 'review the gaudi_BertModel_forward function to understand HPU-specific changes for bf16 autocast and attention mask handling', 'review_fused_sdpa_attention': 'review the gaudi_Bert_Sdpa_SelfAttention_forward function to understand how FusedSDPA replaces scaled_dot_product_attention on HPU', 'refactor_bert_attention_for_hpu': 'refactor the BERT SDPA self-attention to use Habana FusedSDPA with fast softmax algorithm for inference on HPU'}
```

