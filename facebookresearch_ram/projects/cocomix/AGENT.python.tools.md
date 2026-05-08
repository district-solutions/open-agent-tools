# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cocomix/test.py

Prompts

```
['run the main function to evaluate a single model checkpoint and save results to eval_results.json', 'run the main function to evaluate all checkpoints at eval_freq intervals and save cumulative results', 'evaluate the perplexity of a language model on a validation dataset with optional eval_limit', 'evaluate the perplexity of a GPT-2 model on the OpenWebText validation dataset using memmap', 'evaluate a model checkpoint by loading it and running lm_eval tasks plus OpenWebText perplexity', 'create a Logger instance to write timestamped logs to a file and optionally log to wandb', 'use the Logger log method to write a timestamped string to both the log file and stdout', 'call set_random_seed to set a fixed seed across random, numpy, torch, and CUDA', 'use metric_synchronize_between_processes to average metric values across all distributed training processes', 'use tqdm_distributed to show a tqdm progress bar only on the main process during distributed training']
```

Usage

```
{'run_evaluation_single_checkpoint': 'run the main function to evaluate a single model checkpoint and save results to eval_results.json', 'run_evaluation_all_checkpoints': 'run the main function to evaluate all checkpoints at eval_freq intervals and save cumulative results', 'evaluate_ppl': 'evaluate the perplexity of a language model on a validation dataset with optional eval_limit', 'evaluate_openwebtext': 'evaluate the perplexity of a GPT-2 model on the OpenWebText validation dataset using memmap', 'eval_checkpoint': 'evaluate a model checkpoint by loading it and running lm_eval tasks plus OpenWebText perplexity'}
```

## File: facebookresearch_ram/projects/cocomix/utils.py

Prompts

```
['run the main function to evaluate a single model checkpoint and save results to eval_results.json', 'run the main function to evaluate all checkpoints at eval_freq intervals and save cumulative results', 'evaluate the perplexity of a language model on a validation dataset with optional eval_limit', 'evaluate the perplexity of a GPT-2 model on the OpenWebText validation dataset using memmap', 'evaluate a model checkpoint by loading it and running lm_eval tasks plus OpenWebText perplexity', 'create a Logger instance to write timestamped logs to a file and optionally log to wandb', 'use the Logger log method to write a timestamped string to both the log file and stdout', 'call set_random_seed to set a fixed seed across random, numpy, torch, and CUDA', 'use metric_synchronize_between_processes to average metric values across all distributed training processes', 'use tqdm_distributed to show a tqdm progress bar only on the main process during distributed training']
```

Usage

```
{'create_logger_for_training': 'create a Logger instance to write timestamped logs to a file and optionally log to wandb', 'log_message_with_logger': 'use the Logger log method to write a timestamped string to both the log file and stdout', 'set_random_seed_reproducibility': 'call set_random_seed to set a fixed seed across random, numpy, torch, and CUDA', 'synchronize_metrics_distributed': 'use metric_synchronize_between_processes to average metric values across all distributed training processes', 'create_distributed_progress_bar': 'use tqdm_distributed to show a tqdm progress bar only on the main process during distributed training'}
```

