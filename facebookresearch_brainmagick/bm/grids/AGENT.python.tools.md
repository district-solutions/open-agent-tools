# Agent Python Tools

- repo: facebookresearch/brainmagick
- repo_uri: https://github.com/facebookresearch/brainmagick

## File: facebookresearch_brainmagick/bm/grids/_explorers.py

Prompts

```
['create a BMExplorer subclass to customize Dora grid metrics and experiment tracking layout', 'call get_grid_metrics to return a treetable layout with train, valid, and test metric groups', 'call process_history to aggregate a list of per-epoch metric dicts into a single nested stages dict', 'create a ClipExplorer subclass that tracks wer and wer_vocab test metrics for CLIP experiments', 'override the test_metrics class attribute in a BMExplorer subclass to add custom test metric names', 'create a MainHP HiPlotExplorer subclass to visualize training and validation loss metrics', 'run process_metrics on experiment metrics to extract train_loss, valid_loss, and best_loss', 'test process_metrics to verify wer_vocab is included when test metrics contain wer_vocab', 'review postprocess_exp to configure XY display axis and line thickness for HiPlot experiments', 'refactor MainHP process_metrics to add new metric fields from the experiment metrics dictionary', 'create a SimpleGridSearcher instance, define grid parameters, and run grid search experiments with a launcher', 'define grid search parameters with parameter names and their possible values for experiment combinations', 'launch all parameter combination experiments by calling grid_search on a configured SimpleGridSearcher instance', 'extract experiment signature strings from an explorer method by patching a launcher and collecting XP folder names', 'generate a unique version string from the calling grid file name and a version number for experiment flags']
```

Usage

```
{'create_bm_explorer': 'create a BMExplorer subclass to customize Dora grid metrics and experiment tracking layout', 'get_grid_metrics': 'call get_grid_metrics to return a treetable layout with train, valid, and test metric groups', 'process_history': 'call process_history to aggregate a list of per-epoch metric dicts into a single nested stages dict', 'create_clip_explorer': 'create a ClipExplorer subclass that tracks wer and wer_vocab test metrics for CLIP experiments', 'customize_test_metrics': 'override the test_metrics class attribute in a BMExplorer subclass to add custom test metric names'}
```

## File: facebookresearch_brainmagick/bm/grids/_hiplot.py

Prompts

```
['create a BMExplorer subclass to customize Dora grid metrics and experiment tracking layout', 'call get_grid_metrics to return a treetable layout with train, valid, and test metric groups', 'call process_history to aggregate a list of per-epoch metric dicts into a single nested stages dict', 'create a ClipExplorer subclass that tracks wer and wer_vocab test metrics for CLIP experiments', 'override the test_metrics class attribute in a BMExplorer subclass to add custom test metric names', 'create a MainHP HiPlotExplorer subclass to visualize training and validation loss metrics', 'run process_metrics on experiment metrics to extract train_loss, valid_loss, and best_loss', 'test process_metrics to verify wer_vocab is included when test metrics contain wer_vocab', 'review postprocess_exp to configure XY display axis and line thickness for HiPlot experiments', 'refactor MainHP process_metrics to add new metric fields from the experiment metrics dictionary', 'create a SimpleGridSearcher instance, define grid parameters, and run grid search experiments with a launcher', 'define grid search parameters with parameter names and their possible values for experiment combinations', 'launch all parameter combination experiments by calling grid_search on a configured SimpleGridSearcher instance', 'extract experiment signature strings from an explorer method by patching a launcher and collecting XP folder names', 'generate a unique version string from the calling grid file name and a version number for experiment flags']
```

Usage

```
{'create_MainHP_explorer': 'create a MainHP HiPlotExplorer subclass to visualize training and validation loss metrics', 'run_process_metrics': 'run process_metrics on experiment metrics to extract train_loss, valid_loss, and best_loss', 'test_process_metrics_wer': 'test process_metrics to verify wer_vocab is included when test metrics contain wer_vocab', 'review_postprocess_exp': 'review postprocess_exp to configure XY display axis and line thickness for HiPlot experiments', 'refactor_MainHP_metrics': 'refactor MainHP process_metrics to add new metric fields from the experiment metrics dictionary'}
```

## File: facebookresearch_brainmagick/bm/grids/_utils.py

Prompts

```
['create a BMExplorer subclass to customize Dora grid metrics and experiment tracking layout', 'call get_grid_metrics to return a treetable layout with train, valid, and test metric groups', 'call process_history to aggregate a list of per-epoch metric dicts into a single nested stages dict', 'create a ClipExplorer subclass that tracks wer and wer_vocab test metrics for CLIP experiments', 'override the test_metrics class attribute in a BMExplorer subclass to add custom test metric names', 'create a MainHP HiPlotExplorer subclass to visualize training and validation loss metrics', 'run process_metrics on experiment metrics to extract train_loss, valid_loss, and best_loss', 'test process_metrics to verify wer_vocab is included when test metrics contain wer_vocab', 'review postprocess_exp to configure XY display axis and line thickness for HiPlot experiments', 'refactor MainHP process_metrics to add new metric fields from the experiment metrics dictionary', 'create a SimpleGridSearcher instance, define grid parameters, and run grid search experiments with a launcher', 'define grid search parameters with parameter names and their possible values for experiment combinations', 'launch all parameter combination experiments by calling grid_search on a configured SimpleGridSearcher instance', 'extract experiment signature strings from an explorer method by patching a launcher and collecting XP folder names', 'generate a unique version string from the calling grid file name and a version number for experiment flags']
```

Usage

```
{'run_SimpleGridSearcher': 'create a SimpleGridSearcher instance, define grid parameters, and run grid search experiments with a launcher', 'define_grid_param': 'define grid search parameters with parameter names and their possible values for experiment combinations', 'run_grid_search': 'launch all parameter combination experiments by calling grid_search on a configured SimpleGridSearcher instance', 'get_all_explorer_sigs': 'extract experiment signature strings from an explorer method by patching a launcher and collecting XP folder names', 'get_dummy_version': 'generate a unique version string from the calling grid file name and a version number for experiment flags'}
```

