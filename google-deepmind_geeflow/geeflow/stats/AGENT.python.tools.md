# Agent Python Tools

- repo: google-deepmind/geeflow
- repo_uri: https://github.com/google-deepmind/geeflow

## File: google-deepmind_geeflow/geeflow/stats/compute_stats_beam.py

Prompts

```
['run the compute_stats_beam module to compute and save data stats for a TFDS dataset split', 'create an Apache Beam pipeline that reads a TFDS split and computes per-band stats', 'create Apache Beam pipelines for multiple TFDS dataset splits in one call', 'convert a TFDS example to NumPy arrays using jax.tree.map and utils.to_np', 'run the main entry point to execute a Beam pipeline in direct or cloud mode', 'extract features from an example dictionary splitting multi-band features into individual bands with group IDs', 'convert extracted feature tuples into CounterAccumulator objects for numeric or non-numeric stats tracking', 'aggregate multiple CounterAccumulator instances by merging them into a single accumulator per key', 'write final computed stats to JSON files in the output directory after all reduction steps complete', 'create a StatsAccumulator to compute cumulative mean, std, var, min, max over numeric data arrays', 'create a CounterAccumulator to track frequency counts, mode, and histogram bins for numeric or string data', 'create a BandsAccumulator to maintain separate stat accumulators for each band dimension of multi-dimensional arrays', 'save accumulated stats to a JSON file using save_json on StatsAccumulator or BandsAccumulator', 'load previously saved stats from JSON files using load_json with optional band prefix glob support', 'test the CounterAccumulator mask method to exclude outlier values and recompute masked statistics', 'test the hist_quantile function to compute quantile values from histogram bin data']
```

Usage

```
{'run_compute_stats': 'run the compute_stats_beam module to compute and save data stats for a TFDS dataset split', 'create_pipeline_for_split': 'create an Apache Beam pipeline that reads a TFDS split and computes per-band stats', 'create_pipeline': 'create Apache Beam pipelines for multiple TFDS dataset splits in one call', 'convert_format': 'convert a TFDS example to NumPy arrays using jax.tree.map and utils.to_np', 'main': 'run the main entry point to execute a Beam pipeline in direct or cloud mode'}
```

## File: google-deepmind_geeflow/geeflow/stats/compute_stats_beam_utils.py

Prompts

```
['run the compute_stats_beam module to compute and save data stats for a TFDS dataset split', 'create an Apache Beam pipeline that reads a TFDS split and computes per-band stats', 'create Apache Beam pipelines for multiple TFDS dataset splits in one call', 'convert a TFDS example to NumPy arrays using jax.tree.map and utils.to_np', 'run the main entry point to execute a Beam pipeline in direct or cloud mode', 'extract features from an example dictionary splitting multi-band features into individual bands with group IDs', 'convert extracted feature tuples into CounterAccumulator objects for numeric or non-numeric stats tracking', 'aggregate multiple CounterAccumulator instances by merging them into a single accumulator per key', 'write final computed stats to JSON files in the output directory after all reduction steps complete', 'create a StatsAccumulator to compute cumulative mean, std, var, min, max over numeric data arrays', 'create a CounterAccumulator to track frequency counts, mode, and histogram bins for numeric or string data', 'create a BandsAccumulator to maintain separate stat accumulators for each band dimension of multi-dimensional arrays', 'save accumulated stats to a JSON file using save_json on StatsAccumulator or BandsAccumulator', 'load previously saved stats from JSON files using load_json with optional band prefix glob support', 'test the CounterAccumulator mask method to exclude outlier values and recompute masked statistics', 'test the hist_quantile function to compute quantile values from histogram bin data']
```

Usage

```
{'create_pipeline': 'create a Beam pipeline for distributed stats computation with multi-step aggregation and JSON output', 'extract_features': 'extract features from an example dictionary splitting multi-band features into individual bands with group IDs', 'convert_to_accumulator': 'convert extracted feature tuples into CounterAccumulator objects for numeric or non-numeric stats tracking', 'aggregate': 'aggregate multiple CounterAccumulator instances by merging them into a single accumulator per key', 'write_stats': 'write final computed stats to JSON files in the output directory after all reduction steps complete'}
```

## File: google-deepmind_geeflow/geeflow/stats/stats_util.py

Prompts

```
['run the compute_stats_beam module to compute and save data stats for a TFDS dataset split', 'create an Apache Beam pipeline that reads a TFDS split and computes per-band stats', 'create Apache Beam pipelines for multiple TFDS dataset splits in one call', 'convert a TFDS example to NumPy arrays using jax.tree.map and utils.to_np', 'run the main entry point to execute a Beam pipeline in direct or cloud mode', 'extract features from an example dictionary splitting multi-band features into individual bands with group IDs', 'convert extracted feature tuples into CounterAccumulator objects for numeric or non-numeric stats tracking', 'aggregate multiple CounterAccumulator instances by merging them into a single accumulator per key', 'write final computed stats to JSON files in the output directory after all reduction steps complete', 'create a StatsAccumulator to compute cumulative mean, std, var, min, max over numeric data arrays', 'create a CounterAccumulator to track frequency counts, mode, and histogram bins for numeric or string data', 'create a BandsAccumulator to maintain separate stat accumulators for each band dimension of multi-dimensional arrays', 'save accumulated stats to a JSON file using save_json on StatsAccumulator or BandsAccumulator', 'load previously saved stats from JSON files using load_json with optional band prefix glob support', 'test the CounterAccumulator mask method to exclude outlier values and recompute masked statistics', 'test the hist_quantile function to compute quantile values from histogram bin data']
```

Usage

```
{'create_StatsAccumulator': 'create a StatsAccumulator to compute cumulative mean, std, var, min, max over numeric data arrays', 'create_CounterAccumulator': 'create a CounterAccumulator to track frequency counts, mode, and histogram bins for numeric or string data', 'create_BandsAccumulator': 'create a BandsAccumulator to maintain separate stat accumulators for each band dimension of multi-dimensional arrays', 'save_json_stats': 'save accumulated stats to a JSON file using save_json on StatsAccumulator or BandsAccumulator', 'load_json_stats': 'load previously saved stats from JSON files using load_json with optional band prefix glob support'}
```

## File: google-deepmind_geeflow/geeflow/stats/stats_util_test.py

Prompts

```
['run the compute_stats_beam module to compute and save data stats for a TFDS dataset split', 'create an Apache Beam pipeline that reads a TFDS split and computes per-band stats', 'create Apache Beam pipelines for multiple TFDS dataset splits in one call', 'convert a TFDS example to NumPy arrays using jax.tree.map and utils.to_np', 'run the main entry point to execute a Beam pipeline in direct or cloud mode', 'extract features from an example dictionary splitting multi-band features into individual bands with group IDs', 'convert extracted feature tuples into CounterAccumulator objects for numeric or non-numeric stats tracking', 'aggregate multiple CounterAccumulator instances by merging them into a single accumulator per key', 'write final computed stats to JSON files in the output directory after all reduction steps complete', 'create a StatsAccumulator to compute cumulative mean, std, var, min, max over numeric data arrays', 'create a CounterAccumulator to track frequency counts, mode, and histogram bins for numeric or string data', 'create a BandsAccumulator to maintain separate stat accumulators for each band dimension of multi-dimensional arrays', 'save accumulated stats to a JSON file using save_json on StatsAccumulator or BandsAccumulator', 'load previously saved stats from JSON files using load_json with optional band prefix glob support', 'test the CounterAccumulator mask method to exclude outlier values and recompute masked statistics', 'test the hist_quantile function to compute quantile values from histogram bin data']
```

Usage

```
{'create_StatsAccumulator': 'create a StatsAccumulator to compute running mean, std, var, min, max, and total over incremental data', 'create_CounterAccumulator': 'create a CounterAccumulator to track mode, histogram bins, median, IQR, and MAD alongside standard stats', 'test_CounterAccumulator_mask': 'test the CounterAccumulator mask method to exclude outlier values and recompute masked statistics', 'create_BandsAccumulator': 'create a BandsAccumulator to compute per-band statistics across multi-dimensional numpy arrays', 'test_hist_quantile': 'test the hist_quantile function to compute quantile values from histogram bin data'}
```

