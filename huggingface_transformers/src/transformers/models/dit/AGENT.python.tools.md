# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dit/convert_dit_unilm_to_pytorch.py

Prompts

```
['convert a DiT checkpoint from the unilm repository to a HuggingFace BEiT model', 'create a list of key renames to map original DiT checkpoint keys to BEiT model keys', 'split combined qkv projection matrices into separate query, key, and value weights for each layer', 'prepare a test image from the COCO dataset to verify model output shapes after conversion', 'run the DiT-to-BEiT conversion script via CLI with a checkpoint URL and output directory']
```

Usage

```
{'convert_dit_checkpoint': 'convert a DiT checkpoint from the unilm repository to a HuggingFace BEiT model', 'create_rename_keys': 'create a list of key renames to map original DiT checkpoint keys to BEiT model keys', 'read_in_q_k_v': 'split combined qkv projection matrices into separate query, key, and value weights for each layer', 'prepare_img': 'prepare a test image from the COCO dataset to verify model output shapes after conversion', 'run_convert_script': 'run the DiT-to-BEiT conversion script via CLI with a checkpoint URL and output directory'}
```

