# Agent Python Tools

- repo: facebookresearch/lingua
- repo_uri: https://github.com/facebookresearch/lingua

## File: facebookresearch_lingua/apps/fastRNN/eval.py

Prompts

```
['run the fastRNN evaluation pipeline on a consolidated model checkpoint using lm_eval harness', 'run launch_eval with an EvalArgs config to evaluate a PackedRNN model and log results', 'run eval.py with a config file and dot-list CLI overrides to evaluate a fastRNN model', 'review the EvalArgs dataclass to understand evaluation configuration options for fastRNN models', 'review the launch_eval function to understand checkpoint consolidation and lm_eval integration', 'run the fastRNN generator CLI to generate text from prompts using a consolidated model checkpoint', 'load a consolidated fastRNN model and tokenizer from a checkpoint path for minGRU, minLSTM, or hawk model types', 'create a PackedRNNGenerator instance with config args, a model, and a tokenizer for packed sequence generation', 'use the StateCache module to manage convolution and state cache buffers for GRU, LSTM, or RGLRU RNN layers', 'run the PackedRNNGenerator generate method to produce text from a list of prompts with token-level sampling', 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'build a TrainArgs dataclass to configure training hyperparameters, data, optimizer, and distributed settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, data paths, distributed parallelism, and checkpoint configuration', 'parallelize an LMMinGRU, LMMinLSTM, or LMHawk model across GPUs and run the full training loop']
```

Usage

```
{'run_fastRNN_evaluation': 'run the fastRNN evaluation pipeline on a consolidated model checkpoint using lm_eval harness', 'run_launch_eval': 'run launch_eval with an EvalArgs config to evaluate a PackedRNN model and log results', 'run_eval_cli': 'run eval.py with a config file and dot-list CLI overrides to evaluate a fastRNN model', 'review_EvalArgs': 'review the EvalArgs dataclass to understand evaluation configuration options for fastRNN models', 'review_launch_eval': 'review the launch_eval function to understand checkpoint consolidation and lm_eval integration'}
```

## File: facebookresearch_lingua/apps/fastRNN/generate.py

Prompts

```
['run the fastRNN evaluation pipeline on a consolidated model checkpoint using lm_eval harness', 'run launch_eval with an EvalArgs config to evaluate a PackedRNN model and log results', 'run eval.py with a config file and dot-list CLI overrides to evaluate a fastRNN model', 'review the EvalArgs dataclass to understand evaluation configuration options for fastRNN models', 'review the launch_eval function to understand checkpoint consolidation and lm_eval integration', 'run the fastRNN generator CLI to generate text from prompts using a consolidated model checkpoint', 'load a consolidated fastRNN model and tokenizer from a checkpoint path for minGRU, minLSTM, or hawk model types', 'create a PackedRNNGenerator instance with config args, a model, and a tokenizer for packed sequence generation', 'use the StateCache module to manage convolution and state cache buffers for GRU, LSTM, or RGLRU RNN layers', 'run the PackedRNNGenerator generate method to produce text from a list of prompts with token-level sampling', 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'build a TrainArgs dataclass to configure training hyperparameters, data, optimizer, and distributed settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, data paths, distributed parallelism, and checkpoint configuration', 'parallelize an LMMinGRU, LMMinLSTM, or LMHawk model across GPUs and run the full training loop']
```

Usage

```
{'run_fastRNN_generation': 'run the fastRNN generator CLI to generate text from prompts using a consolidated model checkpoint', 'load_consolidated_model_and_tokenizer': 'load a consolidated fastRNN model and tokenizer from a checkpoint path for minGRU, minLSTM, or hawk model types', 'create_PackedRNNGenerator': 'create a PackedRNNGenerator instance with config args, a model, and a tokenizer for packed sequence generation', 'use_StateCache': 'use the StateCache module to manage convolution and state cache buffers for GRU, LSTM, or RGLRU RNN layers', 'run_PackedRNNGenerator_generate': 'run the PackedRNNGenerator generate method to produce text from a list of prompts with token-level sampling'}
```

## File: facebookresearch_lingua/apps/fastRNN/train.py

Prompts

```
['run the fastRNN evaluation pipeline on a consolidated model checkpoint using lm_eval harness', 'run launch_eval with an EvalArgs config to evaluate a PackedRNN model and log results', 'run eval.py with a config file and dot-list CLI overrides to evaluate a fastRNN model', 'review the EvalArgs dataclass to understand evaluation configuration options for fastRNN models', 'review the launch_eval function to understand checkpoint consolidation and lm_eval integration', 'run the fastRNN generator CLI to generate text from prompts using a consolidated model checkpoint', 'load a consolidated fastRNN model and tokenizer from a checkpoint path for minGRU, minLSTM, or hawk model types', 'create a PackedRNNGenerator instance with config args, a model, and a tokenizer for packed sequence generation', 'use the StateCache module to manage convolution and state cache buffers for GRU, LSTM, or RGLRU RNN layers', 'run the PackedRNNGenerator generate method to produce text from a list of prompts with token-level sampling', 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'build a TrainArgs dataclass to configure training hyperparameters, data, optimizer, and distributed settings', 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate TrainArgs to check vocab size, data paths, distributed parallelism, and checkpoint configuration', 'parallelize an LMMinGRU, LMMinLSTM, or LMHawk model across GPUs and run the full training loop']
```

Usage

```
{'run_fastRNN_training': 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'build_train_args': 'build a TrainArgs dataclass to configure training hyperparameters, data, optimizer, and distributed settings', 'create_train_state': 'create a TrainState object to track optimizer steps, accumulation steps, scheduler, and dataloader state', 'validate_train_args': 'validate TrainArgs to check vocab size, data paths, distributed parallelism, and checkpoint configuration', 'parallelize_and_train_model': 'parallelize an LMMinGRU, LMMinLSTM, or LMHawk model across GPUs and run the full training loop'}
```

