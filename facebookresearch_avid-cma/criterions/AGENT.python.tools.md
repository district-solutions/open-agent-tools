# Agent Python Tools

- repo: facebookresearch/avid-cma
- repo_uri: https://github.com/facebookresearch/avid-cma

## File: facebookresearch_avid-cma/criterions/avid.py

Prompts

```
['build an AVID criterion module to compute cross-modal and within-modal NCE loss for video and audio embeddings', 'create an AVIDSimilarityMemoryBank to store and update video and audio embeddings with momentum-based EMA updates', 'run the AVID forward pass to compute total loss from video and audio embeddings and target labels', 'review the AVIDSimilarityMemoryBank update_memory method to understand how embeddings are gathered across GPUs and updated with momentum', 'summarize the AVIDSimilarityMemoryBank sample_negatives method that draws negatives using an AliasMethod distribution while avoiding self', 'build a python module to create an AVID_CMA criterion for audio-visual instance discrimination with memory bank', 'run the CMASampler to find audio-visual correspondences from video and audio memory banks across GPUs', 'create an AVIDSimilarityPositiveExpansion memory bank for positive set discrimination with cross and within modal losses', 'test the AVID_CMA forward pass computing weighted cross and within modal discrimination losses from embeddings', 'review the CMASampler sample_instance method for computing cosine similarity and top-k audio-visual correspondences', 'build a python module that instantiates NCECriterion with a given nLem parameter for noise contrastive estimation', 'run the NCECriterion forward pass with positive and negative score tensors to compute the NCE loss', 'compute the partition function from negative score outputs using batch mean aggregation across distributed processes', 'review the NCECriterion class to understand how it handles distributed training with torch.distributed gathering', 'test the NCECriterion forward method by passing mock positive and negative score tensors and verifying loss output']
```

Usage

```
{'build_AVID_criterion': 'build an AVID criterion module to compute cross-modal and within-modal NCE loss for video and audio embeddings', 'create_AVIDSimilarityMemoryBank': 'create an AVIDSimilarityMemoryBank to store and update video and audio embeddings with momentum-based EMA updates', 'run_AVID_forward': 'run the AVID forward pass to compute total loss from video and audio embeddings and target labels', 'review_AVIDSimilarityMemoryBank_update_memory': 'review the AVIDSimilarityMemoryBank update_memory method to understand how embeddings are gathered across GPUs and updated with momentum', 'summarize_AVID_sample_negatives': 'summarize the AVIDSimilarityMemoryBank sample_negatives method that draws negatives using an AliasMethod distribution while avoiding self'}
```

## File: facebookresearch_avid-cma/criterions/avid_cma.py

Prompts

```
['build an AVID criterion module to compute cross-modal and within-modal NCE loss for video and audio embeddings', 'create an AVIDSimilarityMemoryBank to store and update video and audio embeddings with momentum-based EMA updates', 'run the AVID forward pass to compute total loss from video and audio embeddings and target labels', 'review the AVIDSimilarityMemoryBank update_memory method to understand how embeddings are gathered across GPUs and updated with momentum', 'summarize the AVIDSimilarityMemoryBank sample_negatives method that draws negatives using an AliasMethod distribution while avoiding self', 'build a python module to create an AVID_CMA criterion for audio-visual instance discrimination with memory bank', 'run the CMASampler to find audio-visual correspondences from video and audio memory banks across GPUs', 'create an AVIDSimilarityPositiveExpansion memory bank for positive set discrimination with cross and within modal losses', 'test the AVID_CMA forward pass computing weighted cross and within modal discrimination losses from embeddings', 'review the CMASampler sample_instance method for computing cosine similarity and top-k audio-visual correspondences', 'build a python module that instantiates NCECriterion with a given nLem parameter for noise contrastive estimation', 'run the NCECriterion forward pass with positive and negative score tensors to compute the NCE loss', 'compute the partition function from negative score outputs using batch mean aggregation across distributed processes', 'review the NCECriterion class to understand how it handles distributed training with torch.distributed gathering', 'test the NCECriterion forward method by passing mock positive and negative score tensors and verifying loss output']
```

Usage

```
{'build_AVID_CMA_criterion': 'build a python module to create an AVID_CMA criterion for audio-visual instance discrimination with memory bank', 'run_CMASampler_sample': 'run the CMASampler to find audio-visual correspondences from video and audio memory banks across GPUs', 'create_AVIDSimilarityPositiveExpansion': 'create an AVIDSimilarityPositiveExpansion memory bank for positive set discrimination with cross and within modal losses', 'test_AVID_CMA_forward': 'test the AVID_CMA forward pass computing weighted cross and within modal discrimination losses from embeddings', 'review_CMASampler_sample_instance': 'review the CMASampler sample_instance method for computing cosine similarity and top-k audio-visual correspondences'}
```

## File: facebookresearch_avid-cma/criterions/nce.py

Prompts

```
['build an AVID criterion module to compute cross-modal and within-modal NCE loss for video and audio embeddings', 'create an AVIDSimilarityMemoryBank to store and update video and audio embeddings with momentum-based EMA updates', 'run the AVID forward pass to compute total loss from video and audio embeddings and target labels', 'review the AVIDSimilarityMemoryBank update_memory method to understand how embeddings are gathered across GPUs and updated with momentum', 'summarize the AVIDSimilarityMemoryBank sample_negatives method that draws negatives using an AliasMethod distribution while avoiding self', 'build a python module to create an AVID_CMA criterion for audio-visual instance discrimination with memory bank', 'run the CMASampler to find audio-visual correspondences from video and audio memory banks across GPUs', 'create an AVIDSimilarityPositiveExpansion memory bank for positive set discrimination with cross and within modal losses', 'test the AVID_CMA forward pass computing weighted cross and within modal discrimination losses from embeddings', 'review the CMASampler sample_instance method for computing cosine similarity and top-k audio-visual correspondences', 'build a python module that instantiates NCECriterion with a given nLem parameter for noise contrastive estimation', 'run the NCECriterion forward pass with positive and negative score tensors to compute the NCE loss', 'compute the partition function from negative score outputs using batch mean aggregation across distributed processes', 'review the NCECriterion class to understand how it handles distributed training with torch.distributed gathering', 'test the NCECriterion forward method by passing mock positive and negative score tensors and verifying loss output']
```

Usage

```
{'build_NCECriterion': 'build a python module that instantiates NCECriterion with a given nLem parameter for noise contrastive estimation', 'run_NCECriterion_forward': 'run the NCECriterion forward pass with positive and negative score tensors to compute the NCE loss', 'compute_partition_function': 'compute the partition function from negative score outputs using batch mean aggregation across distributed processes', 'review_NCECriterion_distributed': 'review the NCECriterion class to understand how it handles distributed training with torch.distributed gathering', 'test_NCECriterion_loss': 'test the NCECriterion forward method by passing mock positive and negative score tensors and verifying loss output'}
```

