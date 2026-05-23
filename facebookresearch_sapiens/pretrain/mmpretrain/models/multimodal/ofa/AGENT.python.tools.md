# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/ofa/ofa.py

Prompts

```
['build an OFA multimodal model for caption, vqa, or refcoco tasks with encoder and decoder configs', 'run the OFA model predict method on images with data samples to generate predictions', 'create a Trie data structure with an eos token for constrained beam search decoding', 'apply constraint masking on logits using a Trie and decoder prompts during beam search', 'post process OFA model outputs to decode captions, answers, or bounding boxes from tokens', 'build an OFA encoder-decoder model with ResNet image encoder and transformer decoder for multimodal tasks', 'create an OFA encoder that processes text tokens and images with relative position embeddings', 'create an OFA decoder with self-attention, cross-attention, and FFN blocks for autoregressive generation', 'build a multi-head attention module with optional learnable head scaling and key-value caching', 'generate text or image tokens using the OFA encoder-decoder with beam search and caching']
```

Usage

```
{'build_OFA_model': 'build an OFA multimodal model for caption, vqa, or refcoco tasks with encoder and decoder configs', 'predict_OFA': 'run the OFA model predict method on images with data samples to generate predictions', 'create_Trie': 'create a Trie data structure with an eos token for constrained beam search decoding', 'apply_constraint_apply_constraint': 'apply constraint masking on logits using a Trie and decoder prompts during beam search', 'post_process_OFA': 'post process OFA model outputs to decode captions, answers, or bounding boxes from tokens'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/ofa/ofa_modules.py

Prompts

```
['build an OFA multimodal model for caption, vqa, or refcoco tasks with encoder and decoder configs', 'run the OFA model predict method on images with data samples to generate predictions', 'create a Trie data structure with an eos token for constrained beam search decoding', 'apply constraint masking on logits using a Trie and decoder prompts during beam search', 'post process OFA model outputs to decode captions, answers, or bounding boxes from tokens', 'build an OFA encoder-decoder model with ResNet image encoder and transformer decoder for multimodal tasks', 'create an OFA encoder that processes text tokens and images with relative position embeddings', 'create an OFA decoder with self-attention, cross-attention, and FFN blocks for autoregressive generation', 'build a multi-head attention module with optional learnable head scaling and key-value caching', 'generate text or image tokens using the OFA encoder-decoder with beam search and caching']
```

Usage

```
{'build_OFAEncoderDecoder': 'build an OFA encoder-decoder model with ResNet image encoder and transformer decoder for multimodal tasks', 'create_OFAEncoder': 'create an OFA encoder that processes text tokens and images with relative position embeddings', 'create_OFADecoder': 'create an OFA decoder with self-attention, cross-attention, and FFN blocks for autoregressive generation', 'build_MultiheadAttention': 'build a multi-head attention module with optional learnable head scaling and key-value caching', 'generate_with_OFAEncoderDecoder': 'generate text or image tokens using the OFA encoder-decoder with beam search and caching'}
```

