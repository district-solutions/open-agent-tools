# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/megatron/model/distributed.py

Prompts

```
['create a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'review the DistributedDataParallel init that broadcasts parameters across the data parallel group', 'test the allreduce_params inner function that performs gradient all-reduce across data parallel ranks', 'refactor the DistributedDataParallel forward method to set needs_reduction before delegating to the module', 'summarize the state_dict and load_state_dict methods that delegate to the wrapped module', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create a normal distribution weight initializer for embedding layers with configurable standard deviation', 'add token type embeddings to an existing GPT-2 model with a specified number of token types', 'get parameter groups separated by weight decay and no weight decay for optimizer configuration', 'create a BertModel instance from args with custom hidden size, layers, and attention heads', 'create a BertModel instance from a pretrained checkpoint using args.pretrained_bert flag', 'run a forward pass through BertModel with input tokens, token type ids, and attention mask', 'get parameter groups separated by weight decay and no weight decay for optimizer setup', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertConfig from a JSON file or vocabulary size with custom hidden size and attention heads', 'create a BERT model with model parallel embeddings and encoder layers for sequence encoding', 'run BERT pre-training with masked language modeling and next sentence prediction heads', 'test BERT sequence classification by passing input tokens and labels to get classification logits', 'load a BERT question answering model and predict start and end logits for span extraction']
```

Usage

```
{'create_DistributedDataParallel': 'create a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'review_DistributedDataParallel_init': 'review the DistributedDataParallel init that broadcasts parameters across the data parallel group', 'test_allreduce_params': 'test the allreduce_params inner function that performs gradient all-reduce across data parallel ranks', 'refactor_DistributedDataParallel_forward': 'refactor the DistributedDataParallel forward method to set needs_reduction before delegating to the module', 'summarize_state_dict_load_state_dict': 'summarize the state_dict and load_state_dict methods that delegate to the wrapped module'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/megatron/model/gpt2_modeling.py

Prompts

```
['create a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'review the DistributedDataParallel init that broadcasts parameters across the data parallel group', 'test the allreduce_params inner function that performs gradient all-reduce across data parallel ranks', 'refactor the DistributedDataParallel forward method to set needs_reduction before delegating to the module', 'summarize the state_dict and load_state_dict methods that delegate to the wrapped module', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create a normal distribution weight initializer for embedding layers with configurable standard deviation', 'add token type embeddings to an existing GPT-2 model with a specified number of token types', 'get parameter groups separated by weight decay and no weight decay for optimizer configuration', 'create a BertModel instance from args with custom hidden size, layers, and attention heads', 'create a BertModel instance from a pretrained checkpoint using args.pretrained_bert flag', 'run a forward pass through BertModel with input tokens, token type ids, and attention mask', 'get parameter groups separated by weight decay and no weight decay for optimizer setup', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertConfig from a JSON file or vocabulary size with custom hidden size and attention heads', 'create a BERT model with model parallel embeddings and encoder layers for sequence encoding', 'run BERT pre-training with masked language modeling and next sentence prediction heads', 'test BERT sequence classification by passing input tokens and labels to get classification logits', 'load a BERT question answering model and predict start and end logits for span extraction']
```

Usage

```
{'build_GPT2Model': 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run_GPT2Model_forward': 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create_init_method_normal': 'create a normal distribution weight initializer for embedding layers with configurable standard deviation', 'add_tokentype_embeddings': 'add token type embeddings to an existing GPT-2 model with a specified number of token types', 'get_params_for_weight_decay_optimization': 'get parameter groups separated by weight decay and no weight decay for optimizer configuration'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/megatron/model/model.py

Prompts

```
['create a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'review the DistributedDataParallel init that broadcasts parameters across the data parallel group', 'test the allreduce_params inner function that performs gradient all-reduce across data parallel ranks', 'refactor the DistributedDataParallel forward method to set needs_reduction before delegating to the module', 'summarize the state_dict and load_state_dict methods that delegate to the wrapped module', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create a normal distribution weight initializer for embedding layers with configurable standard deviation', 'add token type embeddings to an existing GPT-2 model with a specified number of token types', 'get parameter groups separated by weight decay and no weight decay for optimizer configuration', 'create a BertModel instance from args with custom hidden size, layers, and attention heads', 'create a BertModel instance from a pretrained checkpoint using args.pretrained_bert flag', 'run a forward pass through BertModel with input tokens, token type ids, and attention mask', 'get parameter groups separated by weight decay and no weight decay for optimizer setup', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertConfig from a JSON file or vocabulary size with custom hidden size and attention heads', 'create a BERT model with model parallel embeddings and encoder layers for sequence encoding', 'run BERT pre-training with masked language modeling and next sentence prediction heads', 'test BERT sequence classification by passing input tokens and labels to get classification logits', 'load a BERT question answering model and predict start and end logits for span extraction']
```

Usage

```
{'create_bertmodel_from_config': 'create a BertModel instance from args with custom hidden size, layers, and attention heads', 'create_bertmodel_from_pretrained': 'create a BertModel instance from a pretrained checkpoint using args.pretrained_bert flag', 'run_bertmodel_forward': 'run a forward pass through BertModel with input tokens, token type ids, and attention mask', 'get_params_for_weight_decay': 'get parameter groups separated by weight decay and no weight decay for optimizer setup', 'review_bertmodel_state_dict': 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/model_parallel/megatron/model/modeling.py

Prompts

```
['create a DistributedDataParallel wrapper around a PyTorch module for model parallel training', 'review the DistributedDataParallel init that broadcasts parameters across the data parallel group', 'test the allreduce_params inner function that performs gradient all-reduce across data parallel ranks', 'refactor the DistributedDataParallel forward method to set needs_reduction before delegating to the module', 'summarize the state_dict and load_state_dict methods that delegate to the wrapped module', 'build a GPT-2 language model with configurable layers, vocab size, and attention heads', 'run the GPT-2 model forward pass with input ids, position ids, and attention mask', 'create a normal distribution weight initializer for embedding layers with configurable standard deviation', 'add token type embeddings to an existing GPT-2 model with a specified number of token types', 'get parameter groups separated by weight decay and no weight decay for optimizer configuration', 'create a BertModel instance from args with custom hidden size, layers, and attention heads', 'create a BertModel instance from a pretrained checkpoint using args.pretrained_bert flag', 'run a forward pass through BertModel with input tokens, token type ids, and attention mask', 'get parameter groups separated by weight decay and no weight decay for optimizer setup', 'review the BertModel state_dict and load_state_dict methods for saving and loading model weights', 'build a BertConfig from a JSON file or vocabulary size with custom hidden size and attention heads', 'create a BERT model with model parallel embeddings and encoder layers for sequence encoding', 'run BERT pre-training with masked language modeling and next sentence prediction heads', 'test BERT sequence classification by passing input tokens and labels to get classification logits', 'load a BERT question answering model and predict start and end logits for span extraction']
```

Usage

```
{'build_BertConfig': 'build a BertConfig from a JSON file or vocabulary size with custom hidden size and attention heads', 'create_BertModel': 'create a BERT model with model parallel embeddings and encoder layers for sequence encoding', 'run_BertForPreTraining': 'run BERT pre-training with masked language modeling and next sentence prediction heads', 'test_BertForSequenceClassification': 'test BERT sequence classification by passing input tokens and labels to get classification logits', 'load_BertForQuestionAnswering': 'load a BERT question answering model and predict start and end logits for span extraction'}
```

