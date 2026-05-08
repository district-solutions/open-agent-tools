# Agent Python Tools

- repo: facebookresearch/ct2hair
- repo_uri: https://github.com/facebookresearch/ct2hair

## File: facebookresearch_ct2hair/CT2Hair/interp.py

Prompts

```
['run the neural_interp function to interpolate hair strands using a config dictionary with output, strands, and head keys', 'review the neural_interp function that loads guide strands, fits a head model, and performs KNN-based neural interpolation', 'summarize the neural_interp function which smooths strands, processes head mesh, and saves interpolated and merged strand results', 'refactor the neural_interp function to support GPU-accelerated neural spline downsampling instead of CPU-based strand processing', 'test the neural_interp function with a mock config to verify strand loading, head model fitting, and interpolation output', 'run the strands_opt function to optimize hair strands against a target point cloud using neural cubic splines', 'create a StrandsOptimizerNeuralCubic instance to optimize hair strand control points against a target point cloud', 'create a module that loads binary strand files with load_bin_strands and saves optimized strands with save_bin_strands', 'create a function that converts splined points to strands with strandspc2strands and smooths them with smooth_strands', 'create a module that loads a point cloud with colors using load_pc for use as a target in strand optimization']
```

Usage

```
{'run_neural_interp': 'run the neural_interp function to interpolate hair strands using a config dictionary with output, strands, and head keys', 'review_neural_interp': 'review the neural_interp function that loads guide strands, fits a head model, and performs KNN-based neural interpolation', 'summarize_neural_interp': 'summarize the neural_interp function which smooths strands, processes head mesh, and saves interpolated and merged strand results', 'refactor_neural_interp': 'refactor the neural_interp function to support GPU-accelerated neural spline downsampling instead of CPU-based strand processing', 'test_neural_interp': 'test the neural_interp function with a mock config to verify strand loading, head model fitting, and interpolation output'}
```

## File: facebookresearch_ct2hair/CT2Hair/optim.py

Prompts

```
['run the neural_interp function to interpolate hair strands using a config dictionary with output, strands, and head keys', 'review the neural_interp function that loads guide strands, fits a head model, and performs KNN-based neural interpolation', 'summarize the neural_interp function which smooths strands, processes head mesh, and saves interpolated and merged strand results', 'refactor the neural_interp function to support GPU-accelerated neural spline downsampling instead of CPU-based strand processing', 'test the neural_interp function with a mock config to verify strand loading, head model fitting, and interpolation output', 'run the strands_opt function to optimize hair strands against a target point cloud using neural cubic splines', 'create a StrandsOptimizerNeuralCubic instance to optimize hair strand control points against a target point cloud', 'create a module that loads binary strand files with load_bin_strands and saves optimized strands with save_bin_strands', 'create a function that converts splined points to strands with strandspc2strands and smooths them with smooth_strands', 'create a module that loads a point cloud with colors using load_pc for use as a target in strand optimization']
```

Usage

```
{'run_strands_optimization': 'run the strands_opt function to optimize hair strands against a target point cloud using neural cubic splines', 'create_strands_optimizer': 'create a StrandsOptimizerNeuralCubic instance to optimize hair strand control points against a target point cloud', 'load_and_save_strands': 'create a module that loads binary strand files with load_bin_strands and saves optimized strands with save_bin_strands', 'smooth_and_convert_strands': 'create a function that converts splined points to strands with strandspc2strands and smooths them with smooth_strands', 'load_point_cloud_for_optimization': 'create a module that loads a point cloud with colors using load_pc for use as a target in strand optimization'}
```

