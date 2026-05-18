# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/apps/altogether/infer.py

Prompts

```
['run image captioning inference on tarball shards using the Altogether model via CLI', 'load a trained Altogether captioning model and CLIP encoder from a checkpoint path', 'create an iterable PyTorch dataset that reads image-text pairs from a tarball shard', 'run batched inference on image-text pairs and generate captions with temperature sampling', 'submit distributed inference jobs across shards using submitit on a SLURM cluster']
```

Usage

```
{'run_ALTOGETHER_inference': 'run image captioning inference on tarball shards using the Altogether model via CLI', 'load_model_from_checkpoint': 'load a trained Altogether captioning model and CLIP encoder from a checkpoint path', 'create_tarball_dataset_iterator': 'create an iterable PyTorch dataset that reads image-text pairs from a tarball shard', 'run_batch_inference_loop': 'run batched inference on image-text pairs and generate captions with temperature sampling', 'submit_distributed_inference_jobs': 'submit distributed inference jobs across shards using submitit on a SLURM cluster'}
```

