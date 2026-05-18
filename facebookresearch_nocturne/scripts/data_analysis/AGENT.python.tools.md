# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/scripts/data_analysis/data_analysis.py

Prompts

```
['run analysis to compute expert accelerations and number of vehicles across the dataset files', 'analyze and plot expert acceleration histograms and vehicle count distributions for valid and invalid files', 'run a Nocturne simulation with expert control enabled to extract vehicle speed and position data', 'review the run_analysis function that approximates acceleration using an Euler step over 90 timesteps', 'summarize the analyze_accels function that generates acceleration and vehicle count plots saved as PNG files', 'run a speed test on simulation files to measure observation retrieval time and print average and standard deviation', 'run the Hydra-configured analysis that loads valid files and executes a speed test on the first ten entries', 'review the run_speed_test function that creates Simulation objects, samples vehicles, and measures flattened_visible_state performance', 'summarize the analyze_accels function that reads valid_files.json and passes file keys to run_speed_test', 'test the run_speed_test function by passing a list of scenario files and a Hydra config object']
```

Usage

```
{'run_analysis_compute_expert_accelerations': 'run analysis to compute expert accelerations and number of vehicles across the dataset files', 'analyze_accels_plot_histograms': 'analyze and plot expert acceleration histograms and vehicle count distributions for valid and invalid files', 'run_simulation_with_expert_control': 'run a Nocturne simulation with expert control enabled to extract vehicle speed and position data', 'review_run_analysis_euler_acceleration': 'review the run_analysis function that approximates acceleration using an Euler step over 90 timesteps', 'summarize_analyze_accels_output': 'summarize the analyze_accels function that generates acceleration and vehicle count plots saved as PNG files'}
```

## File: facebookresearch_nocturne/scripts/data_analysis/speed_test.py

Prompts

```
['run analysis to compute expert accelerations and number of vehicles across the dataset files', 'analyze and plot expert acceleration histograms and vehicle count distributions for valid and invalid files', 'run a Nocturne simulation with expert control enabled to extract vehicle speed and position data', 'review the run_analysis function that approximates acceleration using an Euler step over 90 timesteps', 'summarize the analyze_accels function that generates acceleration and vehicle count plots saved as PNG files', 'run a speed test on simulation files to measure observation retrieval time and print average and standard deviation', 'run the Hydra-configured analysis that loads valid files and executes a speed test on the first ten entries', 'review the run_speed_test function that creates Simulation objects, samples vehicles, and measures flattened_visible_state performance', 'summarize the analyze_accels function that reads valid_files.json and passes file keys to run_speed_test', 'test the run_speed_test function by passing a list of scenario files and a Hydra config object']
```

Usage

```
{'run_speed_test': 'run a speed test on simulation files to measure observation retrieval time and print average and standard deviation', 'run_analyze_accels': 'run the Hydra-configured analysis that loads valid files and executes a speed test on the first ten entries', 'review_run_speed_test': 'review the run_speed_test function that creates Simulation objects, samples vehicles, and measures flattened_visible_state performance', 'summarize_analyze_accels': 'summarize the analyze_accels function that reads valid_files.json and passes file keys to run_speed_test', 'test_run_speed_test': 'test the run_speed_test function by passing a list of scenario files and a Hydra config object'}
```

