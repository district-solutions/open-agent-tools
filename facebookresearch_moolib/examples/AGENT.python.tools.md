# Agent Python Tools

- repo: facebookresearch/moolib
- repo_uri: https://github.com/facebookresearch/moolib

## File: facebookresearch_moolib/examples/a2c.py

Prompts

```
['train an A2C reinforcement learning agent on CartPole-v0 using moolib distributed training', 'create a PyTorch Model with LSTM core for policy and baseline output in A2C', 'compute the A2C loss with policy gradient, baseline, and entropy components', 'log training metrics like episode return and loss values to a TSV file', 'setup moolib EnvPool, Broker, and Accumulator for distributed reinforcement learning training', 'run plot.py on a TSV log file to generate a terminal plot of episode returns over steps', 'run plot.py on a CSV file with the --errorbars flag to show error bars on the plot', 'run plot.py with --smoothing cumsum and --window 100 to apply cumulative sum smoothing to the data', 'run plot.py with multiple glob patterns to overlay plots from several log files on one chart', 'run plot.py with --width 120 and --height 40 to set custom terminal plot dimensions', 'run a single experiment with multiple moolib peers using sbatch on a Slurm cluster', 'run the sbatch experiment script in dry mode to preview the command without submitting', 'get the broker address from SSH connection env var or fall back to the local hostname', 'check if the current working directory is mounted on an NFS filesystem using statfs', 'check if the moolib broker is online by connecting and sending a sync RPC call']
```

Usage

```
{'train_A2C_CartPole': 'train an A2C reinforcement learning agent on CartPole-v0 using moolib distributed training', 'create_Model_with_LSTM': 'create a PyTorch Model with LSTM core for policy and baseline output in A2C', 'compute_a2c_loss': 'compute the A2C loss with policy gradient, baseline, and entropy components', 'log_training_metrics': 'log training metrics like episode return and loss values to a TSV file', 'setup_moolib_distributed_training': 'setup moolib EnvPool, Broker, and Accumulator for distributed reinforcement learning training'}
```

## File: facebookresearch_moolib/examples/plot.py

Prompts

```
['train an A2C reinforcement learning agent on CartPole-v0 using moolib distributed training', 'create a PyTorch Model with LSTM core for policy and baseline output in A2C', 'compute the A2C loss with policy gradient, baseline, and entropy components', 'log training metrics like episode return and loss values to a TSV file', 'setup moolib EnvPool, Broker, and Accumulator for distributed reinforcement learning training', 'run plot.py on a TSV log file to generate a terminal plot of episode returns over steps', 'run plot.py on a CSV file with the --errorbars flag to show error bars on the plot', 'run plot.py with --smoothing cumsum and --window 100 to apply cumulative sum smoothing to the data', 'run plot.py with multiple glob patterns to overlay plots from several log files on one chart', 'run plot.py with --width 120 and --height 40 to set custom terminal plot dimensions', 'run a single experiment with multiple moolib peers using sbatch on a Slurm cluster', 'run the sbatch experiment script in dry mode to preview the command without submitting', 'get the broker address from SSH connection env var or fall back to the local hostname', 'check if the current working directory is mounted on an NFS filesystem using statfs', 'check if the moolib broker is online by connecting and sending a sync RPC call']
```

Usage

```
{'run_plot_tsv': 'run plot.py on a TSV log file to generate a terminal plot of episode returns over steps', 'run_plot_csv_with_errorbars': 'run plot.py on a CSV file with the --errorbars flag to show error bars on the plot', 'run_plot_with_smoothing': 'run plot.py with --smoothing cumsum and --window 100 to apply cumulative sum smoothing to the data', 'run_plot_multiple_files': 'run plot.py with multiple glob patterns to overlay plots from several log files on one chart', 'run_plot_custom_dimensions': 'run plot.py with --width 120 and --height 40 to set custom terminal plot dimensions'}
```

## File: facebookresearch_moolib/examples/sbatch_experiment.py

Prompts

```
['train an A2C reinforcement learning agent on CartPole-v0 using moolib distributed training', 'create a PyTorch Model with LSTM core for policy and baseline output in A2C', 'compute the A2C loss with policy gradient, baseline, and entropy components', 'log training metrics like episode return and loss values to a TSV file', 'setup moolib EnvPool, Broker, and Accumulator for distributed reinforcement learning training', 'run plot.py on a TSV log file to generate a terminal plot of episode returns over steps', 'run plot.py on a CSV file with the --errorbars flag to show error bars on the plot', 'run plot.py with --smoothing cumsum and --window 100 to apply cumulative sum smoothing to the data', 'run plot.py with multiple glob patterns to overlay plots from several log files on one chart', 'run plot.py with --width 120 and --height 40 to set custom terminal plot dimensions', 'run a single experiment with multiple moolib peers using sbatch on a Slurm cluster', 'run the sbatch experiment script in dry mode to preview the command without submitting', 'get the broker address from SSH connection env var or fall back to the local hostname', 'check if the current working directory is mounted on an NFS filesystem using statfs', 'check if the moolib broker is online by connecting and sending a sync RPC call']
```

Usage

```
{'run_sbatch_experiment': 'run a single experiment with multiple moolib peers using sbatch on a Slurm cluster', 'run_sbatch_dry': 'run the sbatch experiment script in dry mode to preview the command without submitting', 'get_address': 'get the broker address from SSH connection env var or fall back to the local hostname', 'check_nfs': 'check if the current working directory is mounted on an NFS filesystem using statfs', 'check_broker_online': 'check if the moolib broker is online by connecting and sending a sync RPC call'}
```

