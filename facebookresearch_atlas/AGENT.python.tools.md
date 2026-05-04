# Agent Python Tools

- repo: facebookresearch/atlas
- repo_uri: https://github.com/facebookresearch/atlas

## File: facebookresearch_atlas/evaluate.py

Prompts

```
['run the evaluate module to evaluate an ATLAS model on a dataset and log metrics', 'run the run_retrieval_only function to retrieve passages for queries without generating answers', 'run the evaluate function to perform retrieval and generation evaluation on a dataset', "build a FAISS index from passages using the model's build_index method during evaluation", 'get an evaluation data iterator that batches and pads examples across distributed ranks', 'run the finetune_qa script to finetune an Atlas model for a question answering task', 'run the finetune_qa script in distributed mode using torchrun or SLURM for multi-GPU training', 'set default parser options for finetuning an Atlas model with QA task hyperparameters', 'check that warmup, save, and eval frequency arguments are lower than the total training steps', 'get the integer value of a named CLI argument from a list of command-line arguments', 'run the Atlas model training loop with model, index, optimizer, and scheduler arguments', 'train the Atlas model with reader and retriever loss combined in each step', "build an FAISS index from passages using the model's embedder during training", 'save the Atlas model, optimizer, and scheduler state to a checkpoint directory', 'load or initialize the Atlas model with optimizer and scheduler from checkpoint or scratch']
```

Usage

```
{'run_evaluation': 'run the evaluate module to evaluate an ATLAS model on a dataset and log metrics', 'run_retrieval_only': 'run the run_retrieval_only function to retrieve passages for queries without generating answers', 'run_full_evaluation': 'run the evaluate function to perform retrieval and generation evaluation on a dataset', 'build_index': "build a FAISS index from passages using the model's build_index method during evaluation", 'get_eval_data_iterator': 'get an evaluation data iterator that batches and pads examples across distributed ranks'}
```

## File: facebookresearch_atlas/finetune_qa.py

Prompts

```
['run the evaluate module to evaluate an ATLAS model on a dataset and log metrics', 'run the run_retrieval_only function to retrieve passages for queries without generating answers', 'run the evaluate function to perform retrieval and generation evaluation on a dataset', "build a FAISS index from passages using the model's build_index method during evaluation", 'get an evaluation data iterator that batches and pads examples across distributed ranks', 'run the finetune_qa script to finetune an Atlas model for a question answering task', 'run the finetune_qa script in distributed mode using torchrun or SLURM for multi-GPU training', 'set default parser options for finetuning an Atlas model with QA task hyperparameters', 'check that warmup, save, and eval frequency arguments are lower than the total training steps', 'get the integer value of a named CLI argument from a list of command-line arguments', 'run the Atlas model training loop with model, index, optimizer, and scheduler arguments', 'train the Atlas model with reader and retriever loss combined in each step', "build an FAISS index from passages using the model's embedder during training", 'save the Atlas model, optimizer, and scheduler state to a checkpoint directory', 'load or initialize the Atlas model with optimizer and scheduler from checkpoint or scratch']
```

Usage

```
{'run_finetune_atlas_qa': 'run the finetune_qa script to finetune an Atlas model for a question answering task', 'run_finetune_atlas_qa_distributed': 'run the finetune_qa script in distributed mode using torchrun or SLURM for multi-GPU training', 'set_parser_options_qa': 'set default parser options for finetuning an Atlas model with QA task hyperparameters', 'check_valid_input_params': 'check that warmup, save, and eval frequency arguments are lower than the total training steps', 'get_argument_value': 'get the integer value of a named CLI argument from a list of command-line arguments'}
```

## File: facebookresearch_atlas/train.py

Prompts

```
['run the evaluate module to evaluate an ATLAS model on a dataset and log metrics', 'run the run_retrieval_only function to retrieve passages for queries without generating answers', 'run the evaluate function to perform retrieval and generation evaluation on a dataset', "build a FAISS index from passages using the model's build_index method during evaluation", 'get an evaluation data iterator that batches and pads examples across distributed ranks', 'run the finetune_qa script to finetune an Atlas model for a question answering task', 'run the finetune_qa script in distributed mode using torchrun or SLURM for multi-GPU training', 'set default parser options for finetuning an Atlas model with QA task hyperparameters', 'check that warmup, save, and eval frequency arguments are lower than the total training steps', 'get the integer value of a named CLI argument from a list of command-line arguments', 'run the Atlas model training loop with model, index, optimizer, and scheduler arguments', 'train the Atlas model with reader and retriever loss combined in each step', "build an FAISS index from passages using the model's embedder during training", 'save the Atlas model, optimizer, and scheduler state to a checkpoint directory', 'load or initialize the Atlas model with optimizer and scheduler from checkpoint or scratch']
```

Usage

```
{'run_atlas_training': 'run the Atlas model training loop with model, index, optimizer, and scheduler arguments', 'train_model_with_retriever': 'train the Atlas model with reader and retriever loss combined in each step', 'build_index_for_passages': "build an FAISS index from passages using the model's embedder during training", 'save_atlas_checkpoint': 'save the Atlas model, optimizer, and scheduler state to a checkpoint directory', 'load_atlas_model': 'load or initialize the Atlas model with optimizer and scheduler from checkpoint or scratch'}
```

