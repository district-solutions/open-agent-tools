# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/utils/data/datapipes/dataframe/dataframe_wrapper.py

Prompts

```
['create a pandas DataFrame from data and column names using the dataframe wrapper', 'concatenate a buffer of pandas DataFrames into a single DataFrame', 'iterate over a DataFrame yielding named tuples without the index column', 'test whether a data object is a pandas DataFrame or Series column', 'get the length and column names of a pandas DataFrame', 'create a DataFrameTracer that traces a PyTorch DataPipe as a DataFrame with schema inference', 'build a CaptureDataFrame to record DataFrame operations for later execution', 'test capturing arithmetic, attribute access, and indexing operations on a DataFrame', 'run batch, groupby, and shuffle operations on a traced DataFrame DataPipe', 'disable capture mode globally using disable_capture to stop recording operations']
```

Usage

```
{'create_dataframe': 'create a pandas DataFrame from data and column names using the dataframe wrapper', 'concat_dataframes': 'concatenate a buffer of pandas DataFrames into a single DataFrame', 'iterate_dataframe': 'iterate over a DataFrame yielding named tuples without the index column', 'test_dataframe_type': 'test whether a data object is a pandas DataFrame or Series column', 'get_dataframe_info': 'get the length and column names of a pandas DataFrame'}
```

## File: pytorch_pytorch/torch/utils/data/datapipes/dataframe/dataframes.py

Prompts

```
['create a pandas DataFrame from data and column names using the dataframe wrapper', 'concatenate a buffer of pandas DataFrames into a single DataFrame', 'iterate over a DataFrame yielding named tuples without the index column', 'test whether a data object is a pandas DataFrame or Series column', 'get the length and column names of a pandas DataFrame', 'create a DataFrameTracer that traces a PyTorch DataPipe as a DataFrame with schema inference', 'build a CaptureDataFrame to record DataFrame operations for later execution', 'test capturing arithmetic, attribute access, and indexing operations on a DataFrame', 'run batch, groupby, and shuffle operations on a traced DataFrame DataPipe', 'disable capture mode globally using disable_capture to stop recording operations']
```

Usage

```
{'create_dataframe_tracer': 'create a DataFrameTracer that traces a PyTorch DataPipe as a DataFrame with schema inference', 'build_capture_dataframe': 'build a CaptureDataFrame to record DataFrame operations for later execution', 'test_capture_operations': 'test capturing arithmetic, attribute access, and indexing operations on a DataFrame', 'run_dataframe_batch': 'run batch, groupby, and shuffle operations on a traced DataFrame DataPipe', 'disable_capture_mode': 'disable capture mode globally using disable_capture to stop recording operations'}
```

