# Agent Python Tools

- repo: facebookresearch/luckmatters
- repo_uri: https://github.com/facebookresearch/luckmatters

## File: facebookresearch_luckmatters/student_specialization/visualization/utils.py

Prompts

```
['find a single experiment run matching specific hyperparameter conditions from a list of data dicts', 'find all experiment runs matching specific hyperparameter conditions from a list of data dicts', 'load stats and config from a single experiment folder returning args, stats, and path', 'load stats from all unique experiment folders under a root directory deduplicating by prefix', 'convert full stats in a folder to a summary file keeping only first and last entries', 'run the figure_l_shape function to plot L-shape scatter plots of correlation vs weight norms', 'run the figure_success_rate function to plot successful recovery rate across teacher indices', 'run the figure_loss function to plot evaluation log loss convergence curves with std bands', 'run the visualize module with a root directory argument to load data and generate plots', 'review the figure_l_shape function which generates scatter plots of teacher correlation against fan-out weight norms', 'run the visualize_multi module with a root directory to plot multi-layer L-shape statistics', 'run plot_multilayer_l_shape to generate scatter plots of student-teacher correlation across layers and epochs', 'create a multi-layer L-shape plot showing student usefulness vs beta values across training epochs', 'review the plot_multilayer_l_shape function to understand how it visualizes student-teacher correlation per layer', 'summarize the visualize_multi module which loads stats and plots student-teacher correlation across network layers']
```

Usage

```
{'find_params_by_condition': 'find a single experiment run matching specific hyperparameter conditions from a list of data dicts', 'find_all_params_by_condition': 'find all experiment runs matching specific hyperparameter conditions from a list of data dicts', 'load_stats_from_folder': 'load stats and config from a single experiment folder returning args, stats, and path', 'load_data_from_root': 'load stats from all unique experiment folders under a root directory deduplicating by prefix', 'convert_stats_to_summary': 'convert full stats in a folder to a summary file keeping only first and last entries'}
```

## File: facebookresearch_luckmatters/student_specialization/visualization/visualize.py

Prompts

```
['find a single experiment run matching specific hyperparameter conditions from a list of data dicts', 'find all experiment runs matching specific hyperparameter conditions from a list of data dicts', 'load stats and config from a single experiment folder returning args, stats, and path', 'load stats from all unique experiment folders under a root directory deduplicating by prefix', 'convert full stats in a folder to a summary file keeping only first and last entries', 'run the figure_l_shape function to plot L-shape scatter plots of correlation vs weight norms', 'run the figure_success_rate function to plot successful recovery rate across teacher indices', 'run the figure_loss function to plot evaluation log loss convergence curves with std bands', 'run the visualize module with a root directory argument to load data and generate plots', 'review the figure_l_shape function which generates scatter plots of teacher correlation against fan-out weight norms', 'run the visualize_multi module with a root directory to plot multi-layer L-shape statistics', 'run plot_multilayer_l_shape to generate scatter plots of student-teacher correlation across layers and epochs', 'create a multi-layer L-shape plot showing student usefulness vs beta values across training epochs', 'review the plot_multilayer_l_shape function to understand how it visualizes student-teacher correlation per layer', 'summarize the visualize_multi module which loads stats and plots student-teacher correlation across network layers']
```

Usage

```
{'run_visualize_l_shape': 'run the figure_l_shape function to plot L-shape scatter plots of correlation vs weight norms', 'run_visualize_success_rate': 'run the figure_success_rate function to plot successful recovery rate across teacher indices', 'run_visualize_loss': 'run the figure_loss function to plot evaluation log loss convergence curves with std bands', 'run_visualize_cli': 'run the visualize module with a root directory argument to load data and generate plots', 'review_figure_l_shape': 'review the figure_l_shape function which generates scatter plots of teacher correlation against fan-out weight norms'}
```

## File: facebookresearch_luckmatters/student_specialization/visualization/visualize_multi.py

Prompts

```
['find a single experiment run matching specific hyperparameter conditions from a list of data dicts', 'find all experiment runs matching specific hyperparameter conditions from a list of data dicts', 'load stats and config from a single experiment folder returning args, stats, and path', 'load stats from all unique experiment folders under a root directory deduplicating by prefix', 'convert full stats in a folder to a summary file keeping only first and last entries', 'run the figure_l_shape function to plot L-shape scatter plots of correlation vs weight norms', 'run the figure_success_rate function to plot successful recovery rate across teacher indices', 'run the figure_loss function to plot evaluation log loss convergence curves with std bands', 'run the visualize module with a root directory argument to load data and generate plots', 'review the figure_l_shape function which generates scatter plots of teacher correlation against fan-out weight norms', 'run the visualize_multi module with a root directory to plot multi-layer L-shape statistics', 'run plot_multilayer_l_shape to generate scatter plots of student-teacher correlation across layers and epochs', 'create a multi-layer L-shape plot showing student usefulness vs beta values across training epochs', 'review the plot_multilayer_l_shape function to understand how it visualizes student-teacher correlation per layer', 'summarize the visualize_multi module which loads stats and plots student-teacher correlation across network layers']
```

Usage

```
{'run_visualize_multi': 'run the visualize_multi module with a root directory to plot multi-layer L-shape statistics', 'run_plot_multilayer_l_shape': 'run plot_multilayer_l_shape to generate scatter plots of student-teacher correlation across layers and epochs', 'create_multilayer_l_shape_plot': 'create a multi-layer L-shape plot showing student usefulness vs beta values across training epochs', 'review_plot_multilayer_l_shape': 'review the plot_multilayer_l_shape function to understand how it visualizes student-teacher correlation per layer', 'summarize_visualize_multi': 'summarize the visualize_multi module which loads stats and plots student-teacher correlation across network layers'}
```

