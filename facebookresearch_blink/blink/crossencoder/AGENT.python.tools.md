# Agent Python Tools

- repo: facebookresearch/blink
- repo_uri: https://github.com/facebookresearch/blink

## File: facebookresearch_blink/blink/crossencoder/crossencoder.py

Prompts

```
['build a CrossEncoderRanker from params dict using load_crossencoder to initialize a BERT or RoBERTa cross-encoder model', 'score candidate entity mentions against a context using CrossEncoderRanker score_candidate method with token vectors and context length', 'save the CrossEncoderRanker model weights and tokenizer vocabulary to an output directory using the save method', 'load a pretrained CrossEncoderRanker model checkpoint from a file path using the load_model method', 'convert token index tensors to BERT input format with segment indices and attention masks using to_bert_input', 'prepare crossencoder training data by encoding mentions and candidates into PyTorch tensors', 'prepare tokenized context representations for crossencoder mention samples using a HuggingFace tokenizer', 'prepare tokenized candidate entity representations and labels from nearest neighbor results', 'filter crossencoder input tensors to remove examples where the gold entity is not among candidates', 'review the crossencoder data processing module for mention and candidate tokenization logic', 'run the cross-encoder reranker training loop with train and validation datasets from a data path', 'run evaluation of a cross-encoder reranker on a validation dataloader and return normalized accuracy', 'run the modify function to concatenate context and candidate token inputs and truncate to max sequence length', 'run get_optimizer to create a BERT optimizer for the cross-encoder model with the given learning rate', 'run get_scheduler to create a warmup linear learning rate schedule for the training optimizer']
```

Usage

```
{'build_crossencoder_ranker': 'build a CrossEncoderRanker from params dict using load_crossencoder to initialize a BERT or RoBERTa cross-encoder model', 'score_candidates_with_crossencoder': 'score candidate entity mentions against a context using CrossEncoderRanker score_candidate method with token vectors and context length', 'save_crossencoder_model': 'save the CrossEncoderRanker model weights and tokenizer vocabulary to an output directory using the save method', 'load_crossencoder_checkpoint': 'load a pretrained CrossEncoderRanker model checkpoint from a file path using the load_model method', 'convert_tokens_to_bert_input': 'convert token index tensors to BERT input format with segment indices and attention masks using to_bert_input'}
```

## File: facebookresearch_blink/blink/crossencoder/data_process.py

Prompts

```
['build a CrossEncoderRanker from params dict using load_crossencoder to initialize a BERT or RoBERTa cross-encoder model', 'score candidate entity mentions against a context using CrossEncoderRanker score_candidate method with token vectors and context length', 'save the CrossEncoderRanker model weights and tokenizer vocabulary to an output directory using the save method', 'load a pretrained CrossEncoderRanker model checkpoint from a file path using the load_model method', 'convert token index tensors to BERT input format with segment indices and attention masks using to_bert_input', 'prepare crossencoder training data by encoding mentions and candidates into PyTorch tensors', 'prepare tokenized context representations for crossencoder mention samples using a HuggingFace tokenizer', 'prepare tokenized candidate entity representations and labels from nearest neighbor results', 'filter crossencoder input tensors to remove examples where the gold entity is not among candidates', 'review the crossencoder data processing module for mention and candidate tokenization logic', 'run the cross-encoder reranker training loop with train and validation datasets from a data path', 'run evaluation of a cross-encoder reranker on a validation dataloader and return normalized accuracy', 'run the modify function to concatenate context and candidate token inputs and truncate to max sequence length', 'run get_optimizer to create a BERT optimizer for the cross-encoder model with the given learning rate', 'run get_scheduler to create a warmup linear learning rate schedule for the training optimizer']
```

Usage

```
{'prepare_crossencoder_data': 'prepare crossencoder training data by encoding mentions and candidates into PyTorch tensors', 'prepare_crossencoder_mentions': 'prepare tokenized context representations for crossencoder mention samples using a HuggingFace tokenizer', 'prepare_crossencoder_candidates': 'prepare tokenized candidate entity representations and labels from nearest neighbor results', 'filter_crossencoder_tensor_input': 'filter crossencoder input tensors to remove examples where the gold entity is not among candidates', 'review_data_process_module': 'review the crossencoder data processing module for mention and candidate tokenization logic'}
```

## File: facebookresearch_blink/blink/crossencoder/train_cross.py

Prompts

```
['build a CrossEncoderRanker from params dict using load_crossencoder to initialize a BERT or RoBERTa cross-encoder model', 'score candidate entity mentions against a context using CrossEncoderRanker score_candidate method with token vectors and context length', 'save the CrossEncoderRanker model weights and tokenizer vocabulary to an output directory using the save method', 'load a pretrained CrossEncoderRanker model checkpoint from a file path using the load_model method', 'convert token index tensors to BERT input format with segment indices and attention masks using to_bert_input', 'prepare crossencoder training data by encoding mentions and candidates into PyTorch tensors', 'prepare tokenized context representations for crossencoder mention samples using a HuggingFace tokenizer', 'prepare tokenized candidate entity representations and labels from nearest neighbor results', 'filter crossencoder input tensors to remove examples where the gold entity is not among candidates', 'review the crossencoder data processing module for mention and candidate tokenization logic', 'run the cross-encoder reranker training loop with train and validation datasets from a data path', 'run evaluation of a cross-encoder reranker on a validation dataloader and return normalized accuracy', 'run the modify function to concatenate context and candidate token inputs and truncate to max sequence length', 'run get_optimizer to create a BERT optimizer for the cross-encoder model with the given learning rate', 'run get_scheduler to create a warmup linear learning rate schedule for the training optimizer']
```

Usage

```
{'run_crossencoder_training': 'run the cross-encoder reranker training loop with train and validation datasets from a data path', 'run_evaluate_reranker': 'run evaluation of a cross-encoder reranker on a validation dataloader and return normalized accuracy', 'run_modify_inputs': 'run the modify function to concatenate context and candidate token inputs and truncate to max sequence length', 'run_get_optimizer': 'run get_optimizer to create a BERT optimizer for the cross-encoder model with the given learning rate', 'run_get_scheduler': 'run get_scheduler to create a warmup linear learning rate schedule for the training optimizer'}
```

