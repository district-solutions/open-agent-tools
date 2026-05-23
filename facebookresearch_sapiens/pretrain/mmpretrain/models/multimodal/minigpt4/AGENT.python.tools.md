# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/minigpt4/minigpt4.py

Prompts

```
['build a MiniGPT4 multimodal model with vision encoder, Q-Former, and LLaMA language model', 'encode input images through the vision encoder and Q-Former to produce LLaMA-compatible embeddings', 'wrap image embeddings with before and after prompt text tokens for the language model', 'run the MiniGPT4 training forward pass and compute caption loss on image-text pairs', 'predict image captions by running MiniGPT4 inference on input image tensors']
```

Usage

```
{'build_minigpt4_model': 'build a MiniGPT4 multimodal model with vision encoder, Q-Former, and LLaMA language model', 'encode_img_method': 'encode input images through the vision encoder and Q-Former to produce LLaMA-compatible embeddings', 'prompt_wrap_method': 'wrap image embeddings with before and after prompt text tokens for the language model', 'run_minigpt4_training': 'run the MiniGPT4 training forward pass and compute caption loss on image-text pairs', 'predict_minigpt4_captions': 'predict image captions by running MiniGPT4 inference on input image tensors'}
```

