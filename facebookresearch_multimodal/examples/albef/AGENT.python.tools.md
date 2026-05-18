# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/albef/finetune_retrieval.py

Prompts

```
['run the ALBEF retrieval model training loop with AdamW optimizer and cosine annealing warm restarts', 'encode a batch of text inputs into embeddings and features using the ALBEF model', 'encode a batch of image inputs into embeddings and features using the ALBEF model', 'run the full image-text retrieval evaluation pipeline encoding both modalities and computing similarity scores', 'compute retrieval metrics R@1 R@5 and R@10 for image-to-text and text-to-image scores', 'run the ALBEF VQA fine-tuning script with a YAML config file via --config argument', 'train an ALBEF model for visual question answering using AdamW optimizer and cosine annealing scheduler', 'evaluate a trained ALBEF VQA model on a test dataset and return top-k answer predictions', 'save VQA model checkpoints with optimizer and scheduler state at the end of each training epoch', 'initialize distributed training mode for multi-GPU ALBEF VQA fine-tuning using DistributedDataParallel', 'build a pretrained ALBEF VQA model from a config dict using albef_model_for_vqa', 'build a pretrained ALBEF retrieval model from a config dict using albef_model_for_retrieval', 'run VQA inference with ALBEFModelForVQA forward to get top-k answer predictions', 'run retrieval training with ALBEFModelForRetrieval forward to compute image-text contrastive and matching loss', 'create a PredictionHead module to predict next token scores from hidden states', 'init a PyTorch distributed process group using environment variables for rank and world size', 'save results from all distributed ranks to a single JSON file in a directory', 'add weight decay parameter groups to a PyTorch model separating bias and weight parameters', 'setup distributed printing to only output from the master process in a multi-GPU run', 'get the world size of the current distributed process group or return 1 if not initialized']
```

Usage

```
{'run_train': 'run the ALBEF retrieval model training loop with AdamW optimizer and cosine annealing warm restarts', 'run_encode_text': 'encode a batch of text inputs into embeddings and features using the ALBEF model', 'run_encode_image': 'encode a batch of image inputs into embeddings and features using the ALBEF model', 'run_evaluation': 'run the full image-text retrieval evaluation pipeline encoding both modalities and computing similarity scores', 'run_itm_eval': 'compute retrieval metrics R@1 R@5 and R@10 for image-to-text and text-to-image scores'}
```

## File: facebookresearch_multimodal/examples/albef/finetune_vqa.py

Prompts

```
['run the ALBEF retrieval model training loop with AdamW optimizer and cosine annealing warm restarts', 'encode a batch of text inputs into embeddings and features using the ALBEF model', 'encode a batch of image inputs into embeddings and features using the ALBEF model', 'run the full image-text retrieval evaluation pipeline encoding both modalities and computing similarity scores', 'compute retrieval metrics R@1 R@5 and R@10 for image-to-text and text-to-image scores', 'run the ALBEF VQA fine-tuning script with a YAML config file via --config argument', 'train an ALBEF model for visual question answering using AdamW optimizer and cosine annealing scheduler', 'evaluate a trained ALBEF VQA model on a test dataset and return top-k answer predictions', 'save VQA model checkpoints with optimizer and scheduler state at the end of each training epoch', 'initialize distributed training mode for multi-GPU ALBEF VQA fine-tuning using DistributedDataParallel', 'build a pretrained ALBEF VQA model from a config dict using albef_model_for_vqa', 'build a pretrained ALBEF retrieval model from a config dict using albef_model_for_retrieval', 'run VQA inference with ALBEFModelForVQA forward to get top-k answer predictions', 'run retrieval training with ALBEFModelForRetrieval forward to compute image-text contrastive and matching loss', 'create a PredictionHead module to predict next token scores from hidden states', 'init a PyTorch distributed process group using environment variables for rank and world size', 'save results from all distributed ranks to a single JSON file in a directory', 'add weight decay parameter groups to a PyTorch model separating bias and weight parameters', 'setup distributed printing to only output from the master process in a multi-GPU run', 'get the world size of the current distributed process group or return 1 if not initialized']
```

Usage

```
{'run_vqa_finetuning': 'run the ALBEF VQA fine-tuning script with a YAML config file via --config argument', 'train_vqa_model': 'train an ALBEF model for visual question answering using AdamW optimizer and cosine annealing scheduler', 'evaluate_vqa_model': 'evaluate a trained ALBEF VQA model on a test dataset and return top-k answer predictions', 'save_vqa_checkpoints': 'save VQA model checkpoints with optimizer and scheduler state at the end of each training epoch', 'init_distributed_vqa_training': 'initialize distributed training mode for multi-GPU ALBEF VQA fine-tuning using DistributedDataParallel'}
```

## File: facebookresearch_multimodal/examples/albef/model.py

Prompts

```
['run the ALBEF retrieval model training loop with AdamW optimizer and cosine annealing warm restarts', 'encode a batch of text inputs into embeddings and features using the ALBEF model', 'encode a batch of image inputs into embeddings and features using the ALBEF model', 'run the full image-text retrieval evaluation pipeline encoding both modalities and computing similarity scores', 'compute retrieval metrics R@1 R@5 and R@10 for image-to-text and text-to-image scores', 'run the ALBEF VQA fine-tuning script with a YAML config file via --config argument', 'train an ALBEF model for visual question answering using AdamW optimizer and cosine annealing scheduler', 'evaluate a trained ALBEF VQA model on a test dataset and return top-k answer predictions', 'save VQA model checkpoints with optimizer and scheduler state at the end of each training epoch', 'initialize distributed training mode for multi-GPU ALBEF VQA fine-tuning using DistributedDataParallel', 'build a pretrained ALBEF VQA model from a config dict using albef_model_for_vqa', 'build a pretrained ALBEF retrieval model from a config dict using albef_model_for_retrieval', 'run VQA inference with ALBEFModelForVQA forward to get top-k answer predictions', 'run retrieval training with ALBEFModelForRetrieval forward to compute image-text contrastive and matching loss', 'create a PredictionHead module to predict next token scores from hidden states', 'init a PyTorch distributed process group using environment variables for rank and world size', 'save results from all distributed ranks to a single JSON file in a directory', 'add weight decay parameter groups to a PyTorch model separating bias and weight parameters', 'setup distributed printing to only output from the master process in a multi-GPU run', 'get the world size of the current distributed process group or return 1 if not initialized']
```

Usage

```
{'build_albef_vqa_model': 'build a pretrained ALBEF VQA model from a config dict using albef_model_for_vqa', 'build_albef_retrieval_model': 'build a pretrained ALBEF retrieval model from a config dict using albef_model_for_retrieval', 'run_vqa_inference': 'run VQA inference with ALBEFModelForVQA forward to get top-k answer predictions', 'run_retrieval_training': 'run retrieval training with ALBEFModelForRetrieval forward to compute image-text contrastive and matching loss', 'create_prediction_head': 'create a PredictionHead module to predict next token scores from hidden states'}
```

## File: facebookresearch_multimodal/examples/albef/utils.py

Prompts

```
['run the ALBEF retrieval model training loop with AdamW optimizer and cosine annealing warm restarts', 'encode a batch of text inputs into embeddings and features using the ALBEF model', 'encode a batch of image inputs into embeddings and features using the ALBEF model', 'run the full image-text retrieval evaluation pipeline encoding both modalities and computing similarity scores', 'compute retrieval metrics R@1 R@5 and R@10 for image-to-text and text-to-image scores', 'run the ALBEF VQA fine-tuning script with a YAML config file via --config argument', 'train an ALBEF model for visual question answering using AdamW optimizer and cosine annealing scheduler', 'evaluate a trained ALBEF VQA model on a test dataset and return top-k answer predictions', 'save VQA model checkpoints with optimizer and scheduler state at the end of each training epoch', 'initialize distributed training mode for multi-GPU ALBEF VQA fine-tuning using DistributedDataParallel', 'build a pretrained ALBEF VQA model from a config dict using albef_model_for_vqa', 'build a pretrained ALBEF retrieval model from a config dict using albef_model_for_retrieval', 'run VQA inference with ALBEFModelForVQA forward to get top-k answer predictions', 'run retrieval training with ALBEFModelForRetrieval forward to compute image-text contrastive and matching loss', 'create a PredictionHead module to predict next token scores from hidden states', 'init a PyTorch distributed process group using environment variables for rank and world size', 'save results from all distributed ranks to a single JSON file in a directory', 'add weight decay parameter groups to a PyTorch model separating bias and weight parameters', 'setup distributed printing to only output from the master process in a multi-GPU run', 'get the world size of the current distributed process group or return 1 if not initialized']
```

Usage

```
{'init_distributed_mode': 'init a PyTorch distributed process group using environment variables for rank and world size', 'save_result': 'save results from all distributed ranks to a single JSON file in a directory', 'add_weight_decay': 'add weight decay parameter groups to a PyTorch model separating bias and weight parameters', 'setup_for_distributed': 'setup distributed printing to only output from the master process in a multi-GPU run', 'get_world_size': 'get the world size of the current distributed process group or return 1 if not initialized'}
```

