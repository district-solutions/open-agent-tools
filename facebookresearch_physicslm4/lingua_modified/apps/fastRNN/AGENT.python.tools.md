# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/eval.py

Prompts

```
['run evaluation of a consolidated fastRNN model using lm_eval harness and save results to JSON', 'run the eval.py CLI with a YAML config file and optional dot-list overrides for EvalArgs', 'launch evaluation by passing an EvalArgs config with checkpoint dir, generator, and harness settings', 'review the EvalArgs dataclass fields including ckpt_dir, generator, harness, validation, and global_step', 'review the launch_eval function that consolidates checkpoints, loads models, runs lm_eval, and logs metrics', 'run the main function to generate text from prompts using a consolidated fastRNN model checkpoint', 'load a consolidated fastRNN model and tokenizer from a checkpoint path supporting mingru, minlstm, or hawk model types', 'create a StateCache module to manage convolution and state buffers for RNN generation with configurable head dimensions', 'build a PackedRNNGenerator that extends PackedCausalTransformerGenerator for efficient packed sequence generation with GRU, LSTM, or RGLRU modules', 'review the generate_next_token method in PackedRNNGenerator that performs sequential single-token forward passes', 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'manage training state with step count, accumulation steps, scheduler, and data loader state', 'parse CLI and config file arguments via OmegaConf to launch distributed fastRNN model training', 'check if current training step matches a given frequency for logging, checkpointing, or evaluation']
```

Usage

```
{'run_eval_fastRNN_model': 'run evaluation of a consolidated fastRNN model using lm_eval harness and save results to JSON', 'run_eval_with_config': 'run the eval.py CLI with a YAML config file and optional dot-list overrides for EvalArgs', 'launch_eval_with_args': 'launch evaluation by passing an EvalArgs config with checkpoint dir, generator, and harness settings', 'review_EvalArgs_dataclass': 'review the EvalArgs dataclass fields including ckpt_dir, generator, harness, validation, and global_step', 'review_launch_eval_function': 'review the launch_eval function that consolidates checkpoints, loads models, runs lm_eval, and logs metrics'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/generate.py

Prompts

```
['run evaluation of a consolidated fastRNN model using lm_eval harness and save results to JSON', 'run the eval.py CLI with a YAML config file and optional dot-list overrides for EvalArgs', 'launch evaluation by passing an EvalArgs config with checkpoint dir, generator, and harness settings', 'review the EvalArgs dataclass fields including ckpt_dir, generator, harness, validation, and global_step', 'review the launch_eval function that consolidates checkpoints, loads models, runs lm_eval, and logs metrics', 'run the main function to generate text from prompts using a consolidated fastRNN model checkpoint', 'load a consolidated fastRNN model and tokenizer from a checkpoint path supporting mingru, minlstm, or hawk model types', 'create a StateCache module to manage convolution and state buffers for RNN generation with configurable head dimensions', 'build a PackedRNNGenerator that extends PackedCausalTransformerGenerator for efficient packed sequence generation with GRU, LSTM, or RGLRU modules', 'review the generate_next_token method in PackedRNNGenerator that performs sequential single-token forward passes', 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'manage training state with step count, accumulation steps, scheduler, and data loader state', 'parse CLI and config file arguments via OmegaConf to launch distributed fastRNN model training', 'check if current training step matches a given frequency for logging, checkpointing, or evaluation']
```

Usage

```
{'run_generate': 'run the main function to generate text from prompts using a consolidated fastRNN model checkpoint', 'load_consolidated_model_and_tokenizer': 'load a consolidated fastRNN model and tokenizer from a checkpoint path supporting mingru, minlstm, or hawk model types', 'create_StateCache': 'create a StateCache module to manage convolution and state buffers for RNN generation with configurable head dimensions', 'build_PackedRNNGenerator': 'build a PackedRNNGenerator that extends PackedCausalTransformerGenerator for efficient packed sequence generation with GRU, LSTM, or RGLRU modules', 'review_PackedRNNGenerator_generate_next_token': 'review the generate_next_token method in PackedRNNGenerator that performs sequential single-token forward passes'}
```

## File: facebookresearch_physicslm4/lingua_modified/apps/fastRNN/train.py

Prompts

```
['run evaluation of a consolidated fastRNN model using lm_eval harness and save results to JSON', 'run the eval.py CLI with a YAML config file and optional dot-list overrides for EvalArgs', 'launch evaluation by passing an EvalArgs config with checkpoint dir, generator, and harness settings', 'review the EvalArgs dataclass fields including ckpt_dir, generator, harness, validation, and global_step', 'review the launch_eval function that consolidates checkpoints, loads models, runs lm_eval, and logs metrics', 'run the main function to generate text from prompts using a consolidated fastRNN model checkpoint', 'load a consolidated fastRNN model and tokenizer from a checkpoint path supporting mingru, minlstm, or hawk model types', 'create a StateCache module to manage convolution and state buffers for RNN generation with configurable head dimensions', 'build a PackedRNNGenerator that extends PackedCausalTransformerGenerator for efficient packed sequence generation with GRU, LSTM, or RGLRU modules', 'review the generate_next_token method in PackedRNNGenerator that performs sequential single-token forward passes', 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'manage training state with step count, accumulation steps, scheduler, and data loader state', 'parse CLI and config file arguments via OmegaConf to launch distributed fastRNN model training', 'check if current training step matches a given frequency for logging, checkpointing, or evaluation']
```

Usage

```
{'train_fastRNN_model': 'run the fastRNN training loop for minGRU, minLSTM, or hawk models via CLI config', 'validate_train_args': 'validate TrainArgs configuration including vocab size, data paths, and distributed parallelism settings', 'TrainState': 'manage training state with step count, accumulation steps, scheduler, and data loader state', 'main': 'parse CLI and config file arguments via OmegaConf to launch distributed fastRNN model training', 'every_n_steps': 'check if current training step matches a given frequency for logging, checkpointing, or evaluation'}
```

