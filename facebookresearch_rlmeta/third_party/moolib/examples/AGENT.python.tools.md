# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/moolib/examples/a2c.py

Prompts

```
['run the A2C reinforcement learning training loop for CartPole-v0 using moolib distributed training', 'build a PyTorch model with linear layers and optional LSTM for policy and baseline output', 'create the A2C loss function computing policy gradient, baseline, and entropy losses from rollout data', 'review the train function that orchestrates environment interaction, gradient computation, and distributed reduction', 'summarize the log_to_file function that incrementally writes training metrics to a TSV file', 'run the plot.py script with a TSV or CSV log file to generate a terminal plot', 'run the plot.py script with --smoothing cumsum to apply cumulative moving average smoothing', 'run the plot.py script with --errorbars flag to display error bars on the plot', 'load a TSV or CSV file and extract x/y arrays with rolling window smoothing applied', 'plot multiple x/y data series using gnuplotlib with configurable terminal size and axis ranges', 'run the sbatch experiment script in dry mode to preview the slurm job command without submitting', 'run the sbatch experiment with multiple peers by setting the num_peers flag to launch an array job', 'get the broker address from the SSH_CONNECTION env var or fall back to the local hostname and default port', 'check if the current working directory is mounted on an NFS filesystem using libc statfs', 'check if the moolib broker is online by connecting via RPC and calling a sync ping']
```

Usage

```
{'run_a2c_training': 'run the A2C reinforcement learning training loop for CartPole-v0 using moolib distributed training', 'build_Model_class': 'build a PyTorch model with linear layers and optional LSTM for policy and baseline output', 'create_a2c_loss': 'create the A2C loss function computing policy gradient, baseline, and entropy losses from rollout data', 'review_train_function': 'review the train function that orchestrates environment interaction, gradient computation, and distributed reduction', 'summarize_log_to_file': 'summarize the log_to_file function that incrementally writes training metrics to a TSV file'}
```

## File: facebookresearch_rlmeta/third_party/moolib/examples/plot.py

Prompts

```
['run the A2C reinforcement learning training loop for CartPole-v0 using moolib distributed training', 'build a PyTorch model with linear layers and optional LSTM for policy and baseline output', 'create the A2C loss function computing policy gradient, baseline, and entropy losses from rollout data', 'review the train function that orchestrates environment interaction, gradient computation, and distributed reduction', 'summarize the log_to_file function that incrementally writes training metrics to a TSV file', 'run the plot.py script with a TSV or CSV log file to generate a terminal plot', 'run the plot.py script with --smoothing cumsum to apply cumulative moving average smoothing', 'run the plot.py script with --errorbars flag to display error bars on the plot', 'load a TSV or CSV file and extract x/y arrays with rolling window smoothing applied', 'plot multiple x/y data series using gnuplotlib with configurable terminal size and axis ranges', 'run the sbatch experiment script in dry mode to preview the slurm job command without submitting', 'run the sbatch experiment with multiple peers by setting the num_peers flag to launch an array job', 'get the broker address from the SSH_CONNECTION env var or fall back to the local hostname and default port', 'check if the current working directory is mounted on an NFS filesystem using libc statfs', 'check if the moolib broker is online by connecting via RPC and calling a sync ping']
```

Usage

```
{'run_plot_cli': 'run the plot.py script with a TSV or CSV log file to generate a terminal plot', 'run_plot_with_smoothing': 'run the plot.py script with --smoothing cumsum to apply cumulative moving average smoothing', 'run_plot_with_errorbars': 'run the plot.py script with --errorbars flag to display error bars on the plot', 'load_file_function': 'load a TSV or CSV file and extract x/y arrays with rolling window smoothing applied', 'plot_function': 'plot multiple x/y data series using gnuplotlib with configurable terminal size and axis ranges'}
```

## File: facebookresearch_rlmeta/third_party/moolib/examples/sbatch_experiment.py

Prompts

```
['run the A2C reinforcement learning training loop for CartPole-v0 using moolib distributed training', 'build a PyTorch model with linear layers and optional LSTM for policy and baseline output', 'create the A2C loss function computing policy gradient, baseline, and entropy losses from rollout data', 'review the train function that orchestrates environment interaction, gradient computation, and distributed reduction', 'summarize the log_to_file function that incrementally writes training metrics to a TSV file', 'run the plot.py script with a TSV or CSV log file to generate a terminal plot', 'run the plot.py script with --smoothing cumsum to apply cumulative moving average smoothing', 'run the plot.py script with --errorbars flag to display error bars on the plot', 'load a TSV or CSV file and extract x/y arrays with rolling window smoothing applied', 'plot multiple x/y data series using gnuplotlib with configurable terminal size and axis ranges', 'run the sbatch experiment script in dry mode to preview the slurm job command without submitting', 'run the sbatch experiment with multiple peers by setting the num_peers flag to launch an array job', 'get the broker address from the SSH_CONNECTION env var or fall back to the local hostname and default port', 'check if the current working directory is mounted on an NFS filesystem using libc statfs', 'check if the moolib broker is online by connecting via RPC and calling a sync ping']
```

Usage

```
{'run_sbatch_experiment_dry': 'run the sbatch experiment script in dry mode to preview the slurm job command without submitting', 'run_sbatch_experiment_with_peers': 'run the sbatch experiment with multiple peers by setting the num_peers flag to launch an array job', 'get_address_broker': 'get the broker address from the SSH_CONNECTION env var or fall back to the local hostname and default port', 'check_nfs_mount': 'check if the current working directory is mounted on an NFS filesystem using libc statfs', 'check_broker_online': 'check if the moolib broker is online by connecting via RPC and calling a sync ping'}
```

