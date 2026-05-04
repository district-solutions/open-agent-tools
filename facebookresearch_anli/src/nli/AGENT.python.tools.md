# Agent Python Tools

- repo: facebookresearch/anli
- repo_uri: https://github.com/facebookresearch/anli

## File: facebookresearch_anli/src/nli/evaluation.py

Prompts

```
['run the NLI model evaluation on a checkpoint with specified eval data and model class', 'run the NLI evaluation using only CPU instead of GPU for the model checkpoint', 'run the NLI evaluation and save predictions to a specified output path as JSONL', 'run the NLI evaluation with a custom per GPU batch size for faster processing', 'run the NLI evaluation with a custom max sequence length for tokenized inputs', 'run NLI inference on a premise and hypothesis pair using a pretrained model checkpoint', 'run evaluation on a dataloader and return predictions with logits and probabilities for each sample', 'run softmax computation on a list of scores to get normalized probability values', 'review the inference function that loads a model, tokenizes input, and returns NLI predictions', 'review the id2label mapping that converts numeric labels to entailment, neutral, contradiction', 'summarize attribution scores by summing across dimensions and normalizing by their L2 norm', 'get model predictions from a BERT-like model with optional gradient computation for attribution analysis', 'get a LayerIntegratedGradients object for a given model to perform attribution-based inspection', 'get human-readable token strings from tokenized input IDs using a HuggingFace tokenizer', 'cleanup token lists and importance scores by filtering out special tokens like [CLS] and [SEP]', 'run NLI model training on SNLI/MNLI/ANLI datasets with BERT, RoBERTa, XLNet, or ALBERT using argparse CLI', 'resume NLI training from a saved checkpoint path with model, optimizer, and scheduler state', 'run NLI model training with FP16 mixed precision using Apex AMP optimization levels O0 to O3', 'run multi-node multi-GPU distributed NLI training with NCCL backend and gradient accumulation', 'build a PyTorch dataset for NLI tasks that transforms premise-hypothesis pairs with a tokenizer', 'build an evaluation DataLoader with sequential sampling and custom batching schema for NLI inference']
```

Usage

```
{'run_evaluation': 'run the NLI model evaluation on a checkpoint with specified eval data and model class', 'run_evaluation_cpu': 'run the NLI evaluation using only CPU instead of GPU for the model checkpoint', 'run_evaluation_save_predictions': 'run the NLI evaluation and save predictions to a specified output path as JSONL', 'run_evaluation_batch_size': 'run the NLI evaluation with a custom per GPU batch size for faster processing', 'run_evaluation_max_length': 'run the NLI evaluation with a custom max sequence length for tokenized inputs'}
```

## File: facebookresearch_anli/src/nli/inference_debug.py

Prompts

```
['run the NLI model evaluation on a checkpoint with specified eval data and model class', 'run the NLI evaluation using only CPU instead of GPU for the model checkpoint', 'run the NLI evaluation and save predictions to a specified output path as JSONL', 'run the NLI evaluation with a custom per GPU batch size for faster processing', 'run the NLI evaluation with a custom max sequence length for tokenized inputs', 'run NLI inference on a premise and hypothesis pair using a pretrained model checkpoint', 'run evaluation on a dataloader and return predictions with logits and probabilities for each sample', 'run softmax computation on a list of scores to get normalized probability values', 'review the inference function that loads a model, tokenizes input, and returns NLI predictions', 'review the id2label mapping that converts numeric labels to entailment, neutral, contradiction', 'summarize attribution scores by summing across dimensions and normalizing by their L2 norm', 'get model predictions from a BERT-like model with optional gradient computation for attribution analysis', 'get a LayerIntegratedGradients object for a given model to perform attribution-based inspection', 'get human-readable token strings from tokenized input IDs using a HuggingFace tokenizer', 'cleanup token lists and importance scores by filtering out special tokens like [CLS] and [SEP]', 'run NLI model training on SNLI/MNLI/ANLI datasets with BERT, RoBERTa, XLNet, or ALBERT using argparse CLI', 'resume NLI training from a saved checkpoint path with model, optimizer, and scheduler state', 'run NLI model training with FP16 mixed precision using Apex AMP optimization levels O0 to O3', 'run multi-node multi-GPU distributed NLI training with NCCL backend and gradient accumulation', 'build a PyTorch dataset for NLI tasks that transforms premise-hypothesis pairs with a tokenizer', 'build an evaluation DataLoader with sequential sampling and custom batching schema for NLI inference']
```

Usage

```
{'run_NLI_inference': 'run NLI inference on a premise and hypothesis pair using a pretrained model checkpoint', 'run_eval_model': 'run evaluation on a dataloader and return predictions with logits and probabilities for each sample', 'run_softmax': 'run softmax computation on a list of scores to get normalized probability values', 'review_inference': 'review the inference function that loads a model, tokenizes input, and returns NLI predictions', 'review_id2label': 'review the id2label mapping that converts numeric labels to entailment, neutral, contradiction'}
```

## File: facebookresearch_anli/src/nli/inspection_tools.py

Prompts

```
['run the NLI model evaluation on a checkpoint with specified eval data and model class', 'run the NLI evaluation using only CPU instead of GPU for the model checkpoint', 'run the NLI evaluation and save predictions to a specified output path as JSONL', 'run the NLI evaluation with a custom per GPU batch size for faster processing', 'run the NLI evaluation with a custom max sequence length for tokenized inputs', 'run NLI inference on a premise and hypothesis pair using a pretrained model checkpoint', 'run evaluation on a dataloader and return predictions with logits and probabilities for each sample', 'run softmax computation on a list of scores to get normalized probability values', 'review the inference function that loads a model, tokenizes input, and returns NLI predictions', 'review the id2label mapping that converts numeric labels to entailment, neutral, contradiction', 'summarize attribution scores by summing across dimensions and normalizing by their L2 norm', 'get model predictions from a BERT-like model with optional gradient computation for attribution analysis', 'get a LayerIntegratedGradients object for a given model to perform attribution-based inspection', 'get human-readable token strings from tokenized input IDs using a HuggingFace tokenizer', 'cleanup token lists and importance scores by filtering out special tokens like [CLS] and [SEP]', 'run NLI model training on SNLI/MNLI/ANLI datasets with BERT, RoBERTa, XLNet, or ALBERT using argparse CLI', 'resume NLI training from a saved checkpoint path with model, optimizer, and scheduler state', 'run NLI model training with FP16 mixed precision using Apex AMP optimization levels O0 to O3', 'run multi-node multi-GPU distributed NLI training with NCCL backend and gradient accumulation', 'build a PyTorch dataset for NLI tasks that transforms premise-hypothesis pairs with a tokenizer', 'build an evaluation DataLoader with sequential sampling and custom batching schema for NLI inference']
```

Usage

```
{'summarize_attributions': 'summarize attribution scores by summing across dimensions and normalizing by their L2 norm', 'get_model_prediction': 'get model predictions from a BERT-like model with optional gradient computation for attribution analysis', 'get_lig_object': 'get a LayerIntegratedGradients object for a given model to perform attribution-based inspection', 'get_tokenized_input_tokens': 'get human-readable token strings from tokenized input IDs using a HuggingFace tokenizer', 'cleanup_tokenization_special_tokens': 'cleanup token lists and importance scores by filtering out special tokens like [CLS] and [SEP]'}
```

## File: facebookresearch_anli/src/nli/training.py

Prompts

```
['run the NLI model evaluation on a checkpoint with specified eval data and model class', 'run the NLI evaluation using only CPU instead of GPU for the model checkpoint', 'run the NLI evaluation and save predictions to a specified output path as JSONL', 'run the NLI evaluation with a custom per GPU batch size for faster processing', 'run the NLI evaluation with a custom max sequence length for tokenized inputs', 'run NLI inference on a premise and hypothesis pair using a pretrained model checkpoint', 'run evaluation on a dataloader and return predictions with logits and probabilities for each sample', 'run softmax computation on a list of scores to get normalized probability values', 'review the inference function that loads a model, tokenizes input, and returns NLI predictions', 'review the id2label mapping that converts numeric labels to entailment, neutral, contradiction', 'summarize attribution scores by summing across dimensions and normalizing by their L2 norm', 'get model predictions from a BERT-like model with optional gradient computation for attribution analysis', 'get a LayerIntegratedGradients object for a given model to perform attribution-based inspection', 'get human-readable token strings from tokenized input IDs using a HuggingFace tokenizer', 'cleanup token lists and importance scores by filtering out special tokens like [CLS] and [SEP]', 'run NLI model training on SNLI/MNLI/ANLI datasets with BERT, RoBERTa, XLNet, or ALBERT using argparse CLI', 'resume NLI training from a saved checkpoint path with model, optimizer, and scheduler state', 'run NLI model training with FP16 mixed precision using Apex AMP optimization levels O0 to O3', 'run multi-node multi-GPU distributed NLI training with NCCL backend and gradient accumulation', 'build a PyTorch dataset for NLI tasks that transforms premise-hypothesis pairs with a tokenizer', 'build an evaluation DataLoader with sequential sampling and custom batching schema for NLI inference']
```

Usage

```
{'run_NLI_training': 'run NLI model training on SNLI/MNLI/ANLI datasets with BERT, RoBERTa, XLNet, or ALBERT using argparse CLI', 'run_eval_model': 'run evaluation of a trained NLI model on a dev dataset and return predictions with accuracy', 'run_resume_training': 'resume NLI training from a saved checkpoint path with model, optimizer, and scheduler state', 'run_fp16_training': 'run NLI model training with FP16 mixed precision using Apex AMP optimization levels O0 to O3', 'run_distributed_training': 'run multi-node multi-GPU distributed NLI training with NCCL backend and gradient accumulation'}
```

## File: facebookresearch_anli/src/nli/training_extra.py

Prompts

```
['run the NLI model evaluation on a checkpoint with specified eval data and model class', 'run the NLI evaluation using only CPU instead of GPU for the model checkpoint', 'run the NLI evaluation and save predictions to a specified output path as JSONL', 'run the NLI evaluation with a custom per GPU batch size for faster processing', 'run the NLI evaluation with a custom max sequence length for tokenized inputs', 'run NLI inference on a premise and hypothesis pair using a pretrained model checkpoint', 'run evaluation on a dataloader and return predictions with logits and probabilities for each sample', 'run softmax computation on a list of scores to get normalized probability values', 'review the inference function that loads a model, tokenizes input, and returns NLI predictions', 'review the id2label mapping that converts numeric labels to entailment, neutral, contradiction', 'summarize attribution scores by summing across dimensions and normalizing by their L2 norm', 'get model predictions from a BERT-like model with optional gradient computation for attribution analysis', 'get a LayerIntegratedGradients object for a given model to perform attribution-based inspection', 'get human-readable token strings from tokenized input IDs using a HuggingFace tokenizer', 'cleanup token lists and importance scores by filtering out special tokens like [CLS] and [SEP]', 'run NLI model training on SNLI/MNLI/ANLI datasets with BERT, RoBERTa, XLNet, or ALBERT using argparse CLI', 'resume NLI training from a saved checkpoint path with model, optimizer, and scheduler state', 'run NLI model training with FP16 mixed precision using Apex AMP optimization levels O0 to O3', 'run multi-node multi-GPU distributed NLI training with NCCL backend and gradient accumulation', 'build a PyTorch dataset for NLI tasks that transforms premise-hypothesis pairs with a tokenizer', 'build an evaluation DataLoader with sequential sampling and custom batching schema for NLI inference']
```

Usage

```
{'run_NLI_training': 'run NLI model training with BERT, RoBERTa, or XLNet on SNLI, MNLI, or ANLI datasets', 'run_distributed_training': 'run distributed multi-GPU training for NLI classification with gradient accumulation and fp16 support', 'run_evaluation': 'run evaluation of a trained NLI model on dev or test datasets and compute accuracy', 'build_NLIDataset': 'build a PyTorch dataset for NLI tasks that transforms premise-hypothesis pairs with a tokenizer', 'build_eval_dataloader': 'build an evaluation DataLoader with sequential sampling and custom batching schema for NLI inference'}
```

