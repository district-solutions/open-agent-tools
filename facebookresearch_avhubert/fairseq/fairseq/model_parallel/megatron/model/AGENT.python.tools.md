# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/megatron/model/distributed.py

Prompts

```
['build a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'create an allreduce_params callback to synchronize gradients across data parallel groups', 'test the DistributedDataParallel forward pass to verify gradient reduction is triggered', 'review the allreduce_hook mechanism that queues gradient synchronization callbacks', 'summarize the state_dict and load_state_dict methods for saving and loading model weights', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create token type embeddings for a GPT-2 model with a specified number of tokentypes', 'review the GPT-2 model parameters separated into weight decay and no weight decay groups', 'summarize the normal distribution initialization method used for GPT-2 embeddings', 'build a BertModel from args with custom hidden size, layers, and attention heads', 'build a BertModel from a pretrained checkpoint using tokenizer model type and cache dir', 'run the BertModel forward pass with input tokens, token type ids, and attention mask', 'create weight decay and no weight decay parameter groups for optimizer from a module', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertForPreTraining model with MLM and NSP heads from a BertConfig', 'build a BertForSequenceClassification model with a configurable number of output labels', 'build a BertForQuestionAnswering model that predicts start and end logits for span extraction', 'build a BertForTokenClassification model for token-level classification with a configurable number of labels', 'load TensorFlow checkpoint weights into a PyTorch BERT model from a given checkpoint path']
```

Usage

```
{'build_DistributedDataParallel': 'build a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'create_allreduce_params': 'create an allreduce_params callback to synchronize gradients across data parallel groups', 'test_forward': 'test the DistributedDataParallel forward pass to verify gradient reduction is triggered', 'review_allreduce_hook': 'review the allreduce_hook mechanism that queues gradient synchronization callbacks', 'summarize_state_dict': 'summarize the state_dict and load_state_dict methods for saving and loading model weights'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/megatron/model/gpt2_modeling.py

Prompts

```
['build a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'create an allreduce_params callback to synchronize gradients across data parallel groups', 'test the DistributedDataParallel forward pass to verify gradient reduction is triggered', 'review the allreduce_hook mechanism that queues gradient synchronization callbacks', 'summarize the state_dict and load_state_dict methods for saving and loading model weights', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create token type embeddings for a GPT-2 model with a specified number of tokentypes', 'review the GPT-2 model parameters separated into weight decay and no weight decay groups', 'summarize the normal distribution initialization method used for GPT-2 embeddings', 'build a BertModel from args with custom hidden size, layers, and attention heads', 'build a BertModel from a pretrained checkpoint using tokenizer model type and cache dir', 'run the BertModel forward pass with input tokens, token type ids, and attention mask', 'create weight decay and no weight decay parameter groups for optimizer from a module', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertForPreTraining model with MLM and NSP heads from a BertConfig', 'build a BertForSequenceClassification model with a configurable number of output labels', 'build a BertForQuestionAnswering model that predicts start and end logits for span extraction', 'build a BertForTokenClassification model for token-level classification with a configurable number of labels', 'load TensorFlow checkpoint weights into a PyTorch BERT model from a given checkpoint path']
```

Usage

```
{'build_gpt2_model': 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run_gpt2_forward': 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create_tokentype_embeddings': 'create token type embeddings for a GPT-2 model with a specified number of tokentypes', 'review_weight_decay_params': 'review the GPT-2 model parameters separated into weight decay and no weight decay groups', 'summarize_init_method_normal': 'summarize the normal distribution initialization method used for GPT-2 embeddings'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/megatron/model/model.py

Prompts

```
['build a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'create an allreduce_params callback to synchronize gradients across data parallel groups', 'test the DistributedDataParallel forward pass to verify gradient reduction is triggered', 'review the allreduce_hook mechanism that queues gradient synchronization callbacks', 'summarize the state_dict and load_state_dict methods for saving and loading model weights', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create token type embeddings for a GPT-2 model with a specified number of tokentypes', 'review the GPT-2 model parameters separated into weight decay and no weight decay groups', 'summarize the normal distribution initialization method used for GPT-2 embeddings', 'build a BertModel from args with custom hidden size, layers, and attention heads', 'build a BertModel from a pretrained checkpoint using tokenizer model type and cache dir', 'run the BertModel forward pass with input tokens, token type ids, and attention mask', 'create weight decay and no weight decay parameter groups for optimizer from a module', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertForPreTraining model with MLM and NSP heads from a BertConfig', 'build a BertForSequenceClassification model with a configurable number of output labels', 'build a BertForQuestionAnswering model that predicts start and end logits for span extraction', 'build a BertForTokenClassification model for token-level classification with a configurable number of labels', 'load TensorFlow checkpoint weights into a PyTorch BERT model from a given checkpoint path']
```

Usage

```
{'build_BertModel_from_config': 'build a BertModel from args with custom hidden size, layers, and attention heads', 'build_BertModel_from_pretrained': 'build a BertModel from a pretrained checkpoint using tokenizer model type and cache dir', 'run_BertModel_forward': 'run the BertModel forward pass with input tokens, token type ids, and attention mask', 'create_weight_decay_param_groups': 'create weight decay and no weight decay parameter groups for optimizer from a module', 'review_BertModel_state_dict': 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/model_parallel/megatron/model/modeling.py

Prompts

```
['build a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'create an allreduce_params callback to synchronize gradients across data parallel groups', 'test the DistributedDataParallel forward pass to verify gradient reduction is triggered', 'review the allreduce_hook mechanism that queues gradient synchronization callbacks', 'summarize the state_dict and load_state_dict methods for saving and loading model weights', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create token type embeddings for a GPT-2 model with a specified number of tokentypes', 'review the GPT-2 model parameters separated into weight decay and no weight decay groups', 'summarize the normal distribution initialization method used for GPT-2 embeddings', 'build a BertModel from args with custom hidden size, layers, and attention heads', 'build a BertModel from a pretrained checkpoint using tokenizer model type and cache dir', 'run the BertModel forward pass with input tokens, token type ids, and attention mask', 'create weight decay and no weight decay parameter groups for optimizer from a module', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertForPreTraining model with MLM and NSP heads from a BertConfig', 'build a BertForSequenceClassification model with a configurable number of output labels', 'build a BertForQuestionAnswering model that predicts start and end logits for span extraction', 'build a BertForTokenClassification model for token-level classification with a configurable number of labels', 'load TensorFlow checkpoint weights into a PyTorch BERT model from a given checkpoint path']
```

Usage

```
{'build_bert_pretraining_model': 'build a BertForPreTraining model with MLM and NSP heads from a BertConfig', 'build_bert_sequence_classification': 'build a BertForSequenceClassification model with a configurable number of output labels', 'build_bert_question_answering': 'build a BertForQuestionAnswering model that predicts start and end logits for span extraction', 'build_bert_token_classification': 'build a BertForTokenClassification model for token-level classification with a configurable number of labels', 'load_tf_weights_in_bert': 'load TensorFlow checkpoint weights into a PyTorch BERT model from a given checkpoint path'}
```

