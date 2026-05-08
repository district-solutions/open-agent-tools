# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/signal_processing/utils/types/channel_info.py

Prompts

```
['create a DOTChannelInfo object with detector and source indices, distances, and spatial coordinates', 'create a Metric2ChannelInfo object with detector source indices and is_Metric1 boolean labels', 'create a StringChannelInfo object from a list of column names for a time series', 'slice a ChannelInfo object by index or range to get a subset of channel rows', 'compare two ChannelInfo objects for equality using the __eq__ method', 'create a TimeSeries object from numpy timestamp and channel data arrays', 'select specific channels from a TimeSeries using numpy-style indexing', 'apply a function to TimeSeries channel data and return a new TimeSeries', 'create a LabeledTimeSeries with timestamps, channel data, and ChannelInfo metadata', 'select channels by name from a StringLabeledTimeSeries using a list of channel names']
```

Usage

```
{'create_DOTChannelInfo': 'create a DOTChannelInfo object with detector and source indices, distances, and spatial coordinates', 'create_Metric2ChannelInfo': 'create a Metric2ChannelInfo object with detector source indices and is_Metric1 boolean labels', 'create_StringChannelInfo': 'create a StringChannelInfo object from a list of column names for a time series', 'slice_ChannelInfo': 'slice a ChannelInfo object by index or range to get a subset of channel rows', 'compare_ChannelInfo': 'compare two ChannelInfo objects for equality using the __eq__ method'}
```

## File: facebookresearch_labgraph/signal_processing/utils/types/time_series.py

Prompts

```
['create a DOTChannelInfo object with detector and source indices, distances, and spatial coordinates', 'create a Metric2ChannelInfo object with detector source indices and is_Metric1 boolean labels', 'create a StringChannelInfo object from a list of column names for a time series', 'slice a ChannelInfo object by index or range to get a subset of channel rows', 'compare two ChannelInfo objects for equality using the __eq__ method', 'create a TimeSeries object from numpy timestamp and channel data arrays', 'select specific channels from a TimeSeries using numpy-style indexing', 'apply a function to TimeSeries channel data and return a new TimeSeries', 'create a LabeledTimeSeries with timestamps, channel data, and ChannelInfo metadata', 'select channels by name from a StringLabeledTimeSeries using a list of channel names']
```

Usage

```
{'create_TimeSeries': 'create a TimeSeries object from numpy timestamp and channel data arrays', 'select_channels_TimeSeries': 'select specific channels from a TimeSeries using numpy-style indexing', 'transform_channel_data_TimeSeries': 'apply a function to TimeSeries channel data and return a new TimeSeries', 'create_LabeledTimeSeries': 'create a LabeledTimeSeries with timestamps, channel data, and ChannelInfo metadata', 'select_channels_by_set_StringLabeledTimeSeries': 'select channels by name from a StringLabeledTimeSeries using a list of channel names'}
```

