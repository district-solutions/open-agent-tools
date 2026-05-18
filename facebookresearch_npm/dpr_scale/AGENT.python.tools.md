# Agent Python Tools

- repo: facebookresearch/npm
- repo_uri: https://github.com/facebookresearch/npm

## File: facebookresearch_npm/dpr_scale/generate_lm_embeddings.py

Prompts

```
['run the main function to generate language model embeddings using Hydra config and PyTorch Lightning', 'run the nested run_test function to fit and test a single test path with context embeddings', 'generate embeddings for multiple test paths by splitting paths with a plus sign separator', 'generate embeddings for 10 test paths by replacing backslash question mark wildcards with indices', 'configure the MaskedLanguageModelingEncodingTask target and disable training batches for embedding generation', 'run the DPR scale training pipeline using Hydra config and PyTorch Lightning trainer', 'run the DPR scale test pipeline with a pretrained checkpoint path and datamodule', 'test multiple DPR model checkpoints by splitting paths with the plus separator syntax', 'instantiate a DPR task model from Hydra config with non-recursive instantiation', 'configure a PyTorch Lightning trainer with checkpoint callback and learning rate monitor']
```

Usage

```
{'run_lm_embedding_generation': 'run the main function to generate language model embeddings using Hydra config and PyTorch Lightning', 'run_test_single_path': 'run the nested run_test function to fit and test a single test path with context embeddings', 'generate_embeddings_with_plus_separator': 'generate embeddings for multiple test paths by splitting paths with a plus sign separator', 'generate_embeddings_with_wildcard': 'generate embeddings for 10 test paths by replacing backslash question mark wildcards with indices', 'configure_mlm_encoding_task': 'configure the MaskedLanguageModelingEncodingTask target and disable training batches for embedding generation'}
```

## File: facebookresearch_npm/dpr_scale/main.py

Prompts

```
['run the main function to generate language model embeddings using Hydra config and PyTorch Lightning', 'run the nested run_test function to fit and test a single test path with context embeddings', 'generate embeddings for multiple test paths by splitting paths with a plus sign separator', 'generate embeddings for 10 test paths by replacing backslash question mark wildcards with indices', 'configure the MaskedLanguageModelingEncodingTask target and disable training batches for embedding generation', 'run the DPR scale training pipeline using Hydra config and PyTorch Lightning trainer', 'run the DPR scale test pipeline with a pretrained checkpoint path and datamodule', 'test multiple DPR model checkpoints by splitting paths with the plus separator syntax', 'instantiate a DPR task model from Hydra config with non-recursive instantiation', 'configure a PyTorch Lightning trainer with checkpoint callback and learning rate monitor']
```

Usage

```
{'run_dpr_training': 'run the DPR scale training pipeline using Hydra config and PyTorch Lightning trainer', 'run_dpr_testing': 'run the DPR scale test pipeline with a pretrained checkpoint path and datamodule', 'test_multiple_checkpoints': 'test multiple DPR model checkpoints by splitting paths with the plus separator syntax', 'instantiate_dpr_task': 'instantiate a DPR task model from Hydra config with non-recursive instantiation', 'configure_dpr_trainer': 'configure a PyTorch Lightning trainer with checkpoint callback and learning rate monitor'}
```

