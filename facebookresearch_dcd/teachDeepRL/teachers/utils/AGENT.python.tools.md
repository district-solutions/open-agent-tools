# Agent Python Tools

- repo: facebookresearch/dcd
- repo_uri: https://github.com/facebookresearch/dcd

## File: facebookresearch_dcd/teachDeepRL/teachers/utils/dataset.py

Prompts

```
['create a Databag with a given dimension and add vectors to it for nearest neighbor lookup', 'create a Dataset from separate x and y arrays using the from_xy class method', 'find the k nearest neighbors of an input vector x in a Dataset using nn_x', 'find the k nearest neighbors of an output vector y in a Dataset using nn_y', 'create a BufferedDataset with a configurable buffer size to batch KDTree rebuilds when adding data', 'create a GIF animation of GMM clusters with competence grids from a blackbox dictionary over episodes', 'plot rectangular regions with jet colormap and a colorbar showing absolute learning progress values', 'scale a numpy 1D array to [-1,1] given bounds and unscale it back to original range', 'truncate a matplotlib colormap to a specific min and max value range for custom visualization', 'create a 2D scatter plot with red dots and optionally emphasized blue dots for highlighted data', 'get a dictionary of environment parameter ranges initialized to None for roughness, stump_height, obstacle_spacing, and gap_width', 'generate a test set name string from environment parameter ranges by concatenating parameter keys with their min and max values', 'test the get_empty_env_ranges function to verify it returns a dictionary with all four environment parameters set to None', 'test the get_test_set_name function with sample environment ranges to confirm it builds the correct concatenated name string', 'refactor the get_test_set_name function to use identity comparison with == instead of is for string key checks']
```

Usage

```
{'create_Databag_add_vectors': 'create a Databag with a given dimension and add vectors to it for nearest neighbor lookup', 'create_Dataset_from_xy': 'create a Dataset from separate x and y arrays using the from_xy class method', 'find_nn_x_in_Dataset': 'find the k nearest neighbors of an input vector x in a Dataset using nn_x', 'find_nn_y_in_Dataset': 'find the k nearest neighbors of an output vector y in a Dataset using nn_y', 'create_BufferedDataset_with_buffer': 'create a BufferedDataset with a configurable buffer size to batch KDTree rebuilds when adding data'}
```

## File: facebookresearch_dcd/teachDeepRL/teachers/utils/plot_utils.py

Prompts

```
['create a Databag with a given dimension and add vectors to it for nearest neighbor lookup', 'create a Dataset from separate x and y arrays using the from_xy class method', 'find the k nearest neighbors of an input vector x in a Dataset using nn_x', 'find the k nearest neighbors of an output vector y in a Dataset using nn_y', 'create a BufferedDataset with a configurable buffer size to batch KDTree rebuilds when adding data', 'create a GIF animation of GMM clusters with competence grids from a blackbox dictionary over episodes', 'plot rectangular regions with jet colormap and a colorbar showing absolute learning progress values', 'scale a numpy 1D array to [-1,1] given bounds and unscale it back to original range', 'truncate a matplotlib colormap to a specific min and max value range for custom visualization', 'create a 2D scatter plot with red dots and optionally emphasized blue dots for highlighted data', 'get a dictionary of environment parameter ranges initialized to None for roughness, stump_height, obstacle_spacing, and gap_width', 'generate a test set name string from environment parameter ranges by concatenating parameter keys with their min and max values', 'test the get_empty_env_ranges function to verify it returns a dictionary with all four environment parameters set to None', 'test the get_test_set_name function with sample environment ranges to confirm it builds the correct concatenated name string', 'refactor the get_test_set_name function to use identity comparison with == instead of is for string key checks']
```

Usage

```
{'create_gmm_visualization_gif': 'create a GIF animation of GMM clusters with competence grids from a blackbox dictionary over episodes', 'plot_regions_with_colorbar': 'plot rectangular regions with jet colormap and a colorbar showing absolute learning progress values', 'scale_and_unscale_vectors': 'scale a numpy 1D array to [-1,1] given bounds and unscale it back to original range', 'truncate_colormap_range': 'truncate a matplotlib colormap to a specific min and max value range for custom visualization', 'create_scatter_plot_with_emphasis': 'create a 2D scatter plot with red dots and optionally emphasized blue dots for highlighted data'}
```

## File: facebookresearch_dcd/teachDeepRL/teachers/utils/test_utils.py

Prompts

```
['create a Databag with a given dimension and add vectors to it for nearest neighbor lookup', 'create a Dataset from separate x and y arrays using the from_xy class method', 'find the k nearest neighbors of an input vector x in a Dataset using nn_x', 'find the k nearest neighbors of an output vector y in a Dataset using nn_y', 'create a BufferedDataset with a configurable buffer size to batch KDTree rebuilds when adding data', 'create a GIF animation of GMM clusters with competence grids from a blackbox dictionary over episodes', 'plot rectangular regions with jet colormap and a colorbar showing absolute learning progress values', 'scale a numpy 1D array to [-1,1] given bounds and unscale it back to original range', 'truncate a matplotlib colormap to a specific min and max value range for custom visualization', 'create a 2D scatter plot with red dots and optionally emphasized blue dots for highlighted data', 'get a dictionary of environment parameter ranges initialized to None for roughness, stump_height, obstacle_spacing, and gap_width', 'generate a test set name string from environment parameter ranges by concatenating parameter keys with their min and max values', 'test the get_empty_env_ranges function to verify it returns a dictionary with all four environment parameters set to None', 'test the get_test_set_name function with sample environment ranges to confirm it builds the correct concatenated name string', 'refactor the get_test_set_name function to use identity comparison with == instead of is for string key checks']
```

Usage

```
{'get_empty_env_ranges': 'get a dictionary of environment parameter ranges initialized to None for roughness, stump_height, obstacle_spacing, and gap_width', 'get_test_set_name': 'generate a test set name string from environment parameter ranges by concatenating parameter keys with their min and max values', 'test_get_empty_env_ranges': 'test the get_empty_env_ranges function to verify it returns a dictionary with all four environment parameters set to None', 'test_get_test_set_name': 'test the get_test_set_name function with sample environment ranges to confirm it builds the correct concatenated name string', 'refactor_get_test_set_name': 'refactor the get_test_set_name function to use identity comparison with == instead of is for string key checks'}
```

