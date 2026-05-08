# Agent Python Tools

- repo: facebookresearch/memory
- repo_uri: https://github.com/facebookresearch/memory

## File: facebookresearch_memory/apps/fastRNN/eval.py

Prompts

```
['run a fastRNN model evaluation using lm_eval harness with a config file and checkpoint directory', 'run the launch_eval function to evaluate a consolidated fastRNN model and log results to JSON', 'run the eval.py CLI with a config file and dot-list overrides for evaluation arguments', 'review the EvalArgs dataclass to understand evaluation configuration options like ckpt_dir and generator settings', 'review the main function to understand how OmegaConf merges default, file, and CLI config values', 'run the fastRNN generate script with a checkpoint path to generate text from prompts', 'load a consolidated fastRNN model and tokenizer from a checkpoint directory path', 'create a PackedRNNGenerator instance with config, model, and tokenizer for text generation', 'create a StateCache module to store convolution and hidden state buffers for RNN generation', 'review the PackedRNNGenerator generate_next_token method for sequential token generation logic', 'run the fastRNN training loop with a config file via train.py config=path/to/config.yaml', 'train a minGRU language model using train.py with model_type=minGRU and a YAML config', 'train a minLSTM language model using train.py with model_type=minLSTM and a YAML config', 'train a HAWK RNN model using train.py with model_type=hawk and a YAML config', 'review the TrainArgs dataclass to understand training hyperparameters like steps, grad_acc_steps, and model_type']
```

Usage

```
{'run_fastRNN_evaluation': 'run a fastRNN model evaluation using lm_eval harness with a config file and checkpoint directory', 'run_launch_eval': 'run the launch_eval function to evaluate a consolidated fastRNN model and log results to JSON', 'run_eval_cli': 'run the eval.py CLI with a config file and dot-list overrides for evaluation arguments', 'review_EvalArgs': 'review the EvalArgs dataclass to understand evaluation configuration options like ckpt_dir and generator settings', 'review_main_config_merge': 'review the main function to understand how OmegaConf merges default, file, and CLI config values'}
```

## File: facebookresearch_memory/apps/fastRNN/generate.py

Prompts

```
['run a fastRNN model evaluation using lm_eval harness with a config file and checkpoint directory', 'run the launch_eval function to evaluate a consolidated fastRNN model and log results to JSON', 'run the eval.py CLI with a config file and dot-list overrides for evaluation arguments', 'review the EvalArgs dataclass to understand evaluation configuration options like ckpt_dir and generator settings', 'review the main function to understand how OmegaConf merges default, file, and CLI config values', 'run the fastRNN generate script with a checkpoint path to generate text from prompts', 'load a consolidated fastRNN model and tokenizer from a checkpoint directory path', 'create a PackedRNNGenerator instance with config, model, and tokenizer for text generation', 'create a StateCache module to store convolution and hidden state buffers for RNN generation', 'review the PackedRNNGenerator generate_next_token method for sequential token generation logic', 'run the fastRNN training loop with a config file via train.py config=path/to/config.yaml', 'train a minGRU language model using train.py with model_type=minGRU and a YAML config', 'train a minLSTM language model using train.py with model_type=minLSTM and a YAML config', 'train a HAWK RNN model using train.py with model_type=hawk and a YAML config', 'review the TrainArgs dataclass to understand training hyperparameters like steps, grad_acc_steps, and model_type']
```

Usage

```
{'run_fastRNN_generation': 'run the fastRNN generate script with a checkpoint path to generate text from prompts', 'load_consolidated_model_and_tokenizer': 'load a consolidated fastRNN model and tokenizer from a checkpoint directory path', 'create_PackedRNNGenerator': 'create a PackedRNNGenerator instance with config, model, and tokenizer for text generation', 'create_StateCache': 'create a StateCache module to store convolution and hidden state buffers for RNN generation', 'review_PackedRNNGenerator_generate_next_token': 'review the PackedRNNGenerator generate_next_token method for sequential token generation logic'}
```

## File: facebookresearch_memory/apps/fastRNN/train.py

Prompts

```
['run a fastRNN model evaluation using lm_eval harness with a config file and checkpoint directory', 'run the launch_eval function to evaluate a consolidated fastRNN model and log results to JSON', 'run the eval.py CLI with a config file and dot-list overrides for evaluation arguments', 'review the EvalArgs dataclass to understand evaluation configuration options like ckpt_dir and generator settings', 'review the main function to understand how OmegaConf merges default, file, and CLI config values', 'run the fastRNN generate script with a checkpoint path to generate text from prompts', 'load a consolidated fastRNN model and tokenizer from a checkpoint directory path', 'create a PackedRNNGenerator instance with config, model, and tokenizer for text generation', 'create a StateCache module to store convolution and hidden state buffers for RNN generation', 'review the PackedRNNGenerator generate_next_token method for sequential token generation logic', 'run the fastRNN training loop with a config file via train.py config=path/to/config.yaml', 'train a minGRU language model using train.py with model_type=minGRU and a YAML config', 'train a minLSTM language model using train.py with model_type=minLSTM and a YAML config', 'train a HAWK RNN model using train.py with model_type=hawk and a YAML config', 'review the TrainArgs dataclass to understand training hyperparameters like steps, grad_acc_steps, and model_type']
```

Usage

```
{'run_fastRNN_training': 'run the fastRNN training loop with a config file via train.py config=path/to/config.yaml', 'train_minGRU_model': 'train a minGRU language model using train.py with model_type=minGRU and a YAML config', 'train_minLSTM_model': 'train a minLSTM language model using train.py with model_type=minLSTM and a YAML config', 'train_hawk_model': 'train a HAWK RNN model using train.py with model_type=hawk and a YAML config', 'review_TrainArgs': 'review the TrainArgs dataclass to understand training hyperparameters like steps, grad_acc_steps, and model_type'}
```

