# Agent Python Tools

- repo: facebookresearch/generic-neuromotor-interface
- repo_uri: https://github.com/facebookresearch/generic-neuromotor-interface

## File: facebookresearch_generic-neuromotor-interface/generic_neuromotor_interface/explore_data/load.py

Prompts

```
['load an EMG HDF5 dataset and automatically determine the correct loader for the dataset type', 'create an EMGData instance from an HDF5 file to access timeseries EMG signals and timestamps', 'partition EMG timeseries data by slicing between two timestamp values using searchsorted indexing', 'create a WristAngleData instance to load wrist angle data with extension flexion and radial ulnar deviation channels', 'create a DiscreteGesturesData instance to load discrete gesture EMG data with associated prompts from HDF5', 'plot EMG signals over time with each channel vertically offset and a scale bar', 'plot EMG data on a custom matplotlib axes with configurable vertical offset quantile', 'plot wrist flexion/extension and radial/ulnar deviation angles over time', 'plot wrist angle data on a custom matplotlib axes with normalized time', 'review the plot module functions for EMG and wrist angle visualization capabilities']
```

Usage

```
{'load_data_auto': 'load an EMG HDF5 dataset and automatically determine the correct loader for the dataset type', 'create_EMGData': 'create an EMGData instance from an HDF5 file to access timeseries EMG signals and timestamps', 'partition_EMGData': 'partition EMG timeseries data by slicing between two timestamp values using searchsorted indexing', 'create_WristAngleData': 'create a WristAngleData instance to load wrist angle data with extension flexion and radial ulnar deviation channels', 'create_DiscreteGesturesData': 'create a DiscreteGesturesData instance to load discrete gesture EMG data with associated prompts from HDF5'}
```

## File: facebookresearch_generic-neuromotor-interface/generic_neuromotor_interface/explore_data/plot.py

Prompts

```
['load an EMG HDF5 dataset and automatically determine the correct loader for the dataset type', 'create an EMGData instance from an HDF5 file to access timeseries EMG signals and timestamps', 'partition EMG timeseries data by slicing between two timestamp values using searchsorted indexing', 'create a WristAngleData instance to load wrist angle data with extension flexion and radial ulnar deviation channels', 'create a DiscreteGesturesData instance to load discrete gesture EMG data with associated prompts from HDF5', 'plot EMG signals over time with each channel vertically offset and a scale bar', 'plot EMG data on a custom matplotlib axes with configurable vertical offset quantile', 'plot wrist flexion/extension and radial/ulnar deviation angles over time', 'plot wrist angle data on a custom matplotlib axes with normalized time', 'review the plot module functions for EMG and wrist angle visualization capabilities']
```

Usage

```
{'plot_emg_channels': 'plot EMG signals over time with each channel vertically offset and a scale bar', 'plot_emg_custom_axes': 'plot EMG data on a custom matplotlib axes with configurable vertical offset quantile', 'plot_wrist_angles': 'plot wrist flexion/extension and radial/ulnar deviation angles over time', 'plot_wrist_custom_axes': 'plot wrist angle data on a custom matplotlib axes with normalized time', 'review_plot_module': 'review the plot module functions for EMG and wrist angle visualization capabilities'}
```

