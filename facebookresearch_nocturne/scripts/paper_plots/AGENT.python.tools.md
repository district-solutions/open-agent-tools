# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/scripts/paper_plots/create_zsc_plot.py

Prompts

```
['create a heatmap of ZSC cross-play results from a numpy file and save as an image', 'compute and print the average self-play vs cross-play scores with standard error from a numpy file', 'refactor create_heat_map to accept zsc_path as a parameter instead of relying on a global variable', 'review compute_average_change to verify the standard error calculation for cross-play metrics', 'run the ZSC plotting pipeline to generate heatmaps and compute average change statistics', 'run a stored SampleFactory agent over all scenario files in a validation set and save metrics', 'run a single rollout of a SampleFactory actor in the driving environment and collect goal and collision stats', 'evaluate generalization for all agent checkpoints in a folder using multiprocessing across train and test sets', 'pull experiment results from the W&B server and save them as a CSV file for plotting', 'plot number of training steps versus goal achieved percentage using W&B CSV data', 'run the main function to generate cone and feature images for Nocturne traffic scenarios', 'create a Nocturne Simulation from a scenario JSON file with all vehicles set to expert control', 'build an MP4 movie by stepping a simulation and capturing frames via a scenario function', 'generate a PNG image from a Nocturne scenario using a custom scenario rendering function', 'review the main loop that iterates over scenario files and generates cone and feature images']
```

Usage

```
{'create_heatmap_zsc_results': 'create a heatmap of ZSC cross-play results from a numpy file and save as an image', 'compute_average_change_self_vs_cross': 'compute and print the average self-play vs cross-play scores with standard error from a numpy file', 'refactor_create_heatmap_accept_path': 'refactor create_heat_map to accept zsc_path as a parameter instead of relying on a global variable', 'review_compute_average_change': 'review compute_average_change to verify the standard error calculation for cross-play metrics', 'run_zsc_plotting_pipeline': 'run the ZSC plotting pipeline to generate heatmaps and compute average change statistics'}
```

## File: facebookresearch_nocturne/scripts/paper_plots/eval_sample_factory.py

Prompts

```
['create a heatmap of ZSC cross-play results from a numpy file and save as an image', 'compute and print the average self-play vs cross-play scores with standard error from a numpy file', 'refactor create_heat_map to accept zsc_path as a parameter instead of relying on a global variable', 'review compute_average_change to verify the standard error calculation for cross-play metrics', 'run the ZSC plotting pipeline to generate heatmaps and compute average change statistics', 'run a stored SampleFactory agent over all scenario files in a validation set and save metrics', 'run a single rollout of a SampleFactory actor in the driving environment and collect goal and collision stats', 'evaluate generalization for all agent checkpoints in a folder using multiprocessing across train and test sets', 'pull experiment results from the W&B server and save them as a CSV file for plotting', 'plot number of training steps versus goal achieved percentage using W&B CSV data', 'run the main function to generate cone and feature images for Nocturne traffic scenarios', 'create a Nocturne Simulation from a scenario JSON file with all vehicles set to expert control', 'build an MP4 movie by stepping a simulation and capturing frames via a scenario function', 'generate a PNG image from a Nocturne scenario using a custom scenario rendering function', 'review the main loop that iterates over scenario files and generates cone and feature images']
```

Usage

```
{'run_eval_sample_factory': 'run a stored SampleFactory agent over all scenario files in a validation set and save metrics', 'run_rollouts_single_episode': 'run a single rollout of a SampleFactory actor in the driving environment and collect goal and collision stats', 'eval_generalization_checkpoints': 'evaluate generalization for all agent checkpoints in a folder using multiprocessing across train and test sets', 'load_wandb_experiment': 'pull experiment results from the W&B server and save them as a CSV file for plotting', 'plot_goal_achieved_over_steps': 'plot number of training steps versus goal achieved percentage using W&B CSV data'}
```

## File: facebookresearch_nocturne/scripts/paper_plots/generate_scenes.py

Prompts

```
['create a heatmap of ZSC cross-play results from a numpy file and save as an image', 'compute and print the average self-play vs cross-play scores with standard error from a numpy file', 'refactor create_heat_map to accept zsc_path as a parameter instead of relying on a global variable', 'review compute_average_change to verify the standard error calculation for cross-play metrics', 'run the ZSC plotting pipeline to generate heatmaps and compute average change statistics', 'run a stored SampleFactory agent over all scenario files in a validation set and save metrics', 'run a single rollout of a SampleFactory actor in the driving environment and collect goal and collision stats', 'evaluate generalization for all agent checkpoints in a folder using multiprocessing across train and test sets', 'pull experiment results from the W&B server and save them as a CSV file for plotting', 'plot number of training steps versus goal achieved percentage using W&B CSV data', 'run the main function to generate cone and feature images for Nocturne traffic scenarios', 'create a Nocturne Simulation from a scenario JSON file with all vehicles set to expert control', 'build an MP4 movie by stepping a simulation and capturing frames via a scenario function', 'generate a PNG image from a Nocturne scenario using a custom scenario rendering function', 'review the main loop that iterates over scenario files and generates cone and feature images']
```

Usage

```
{'run_generate_scenes': 'run the main function to generate cone and feature images for Nocturne traffic scenarios', 'create_simulation_with_get_sim': 'create a Nocturne Simulation from a scenario JSON file with all vehicles set to expert control', 'build_movie_with_make_movie': 'build an MP4 movie by stepping a simulation and capturing frames via a scenario function', 'generate_image_with_make_image': 'generate a PNG image from a Nocturne scenario using a custom scenario rendering function', 'review_main_scenario_loop': 'review the main loop that iterates over scenario files and generates cone and feature images'}
```

