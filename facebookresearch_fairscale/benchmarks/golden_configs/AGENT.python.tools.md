# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/benchmarks/golden_configs/lm_wikitext2.py

Prompts

```
['get the FSDP model config with vocab size, embedding dim, and decoder layers for WikiText-2', 'get the Pipe benchmark config with learning rate, batch size, and cross entropy loss', 'get the MOE model config with mixture of experts settings and 20 decoder layers', 'get the Offload Transformer golden real stats including avg words per second and peak memory', 'get the Offload Sequential benchmark config with 100 layers and checkpoint activation enabled', 'get the golden reference benchmark stats for the OSS MNIST real data experiment', 'summarize the get_golden_real_stats function that returns reference speed, memory, and loss values', 'review the get_golden_real_stats function to verify the reference benchmark thresholds are current']
```

Usage

```
{'get_FSDP_model_config': 'get the FSDP model config with vocab size, embedding dim, and decoder layers for WikiText-2', 'get_Pipe_benchmark_config': 'get the Pipe benchmark config with learning rate, batch size, and cross entropy loss', 'get_MOE_model_config': 'get the MOE model config with mixture of experts settings and 20 decoder layers', 'get_Offload_Transformer_golden_stats': 'get the Offload Transformer golden real stats including avg words per second and peak memory', 'get_Offload_Sequential_benchmark_config': 'get the Offload Sequential benchmark config with 100 layers and checkpoint activation enabled'}
```

## File: facebookresearch_fairscale/benchmarks/golden_configs/oss_mnist.py

Prompts

```
['get the FSDP model config with vocab size, embedding dim, and decoder layers for WikiText-2', 'get the Pipe benchmark config with learning rate, batch size, and cross entropy loss', 'get the MOE model config with mixture of experts settings and 20 decoder layers', 'get the Offload Transformer golden real stats including avg words per second and peak memory', 'get the Offload Sequential benchmark config with 100 layers and checkpoint activation enabled', 'get the golden reference benchmark stats for the OSS MNIST real data experiment', 'summarize the get_golden_real_stats function that returns reference speed, memory, and loss values', 'review the get_golden_real_stats function to verify the reference benchmark thresholds are current']
```

Usage

```
{'get_golden_real_stats': 'get the golden reference benchmark stats for the OSS MNIST real data experiment', 'summarize_get_golden_real_stats': 'summarize the get_golden_real_stats function that returns reference speed, memory, and loss values', 'review_get_golden_real_stats': 'review the get_golden_real_stats function to verify the reference benchmark thresholds are current'}
```

