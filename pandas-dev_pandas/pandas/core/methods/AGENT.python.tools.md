# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/core/methods/describe.py

Prompts

```
['describe a pandas Series or DataFrame with custom percentiles, include, and exclude filters', 'describe a numeric pandas Series returning count, mean, std, min, percentiles, and max', 'describe a categorical pandas Series returning count, unique, top, and freq', 'describe a datetime pandas Series returning count, mean, min, percentiles, and max', 'select the appropriate describe function for a pandas Series based on its dtype', 'test the SelectN class nlargest method to return the n largest values from an object', 'test the SelectN class nsmallest method to return the n smallest values from an object', 'test the SelectNSeries compute method to get the n largest or smallest values from a Series', 'test the SelectNFrame compute method to get the n largest or smallest rows from a DataFrame across columns', 'test the SelectN is_valid_dtype_n_method helper to check if a dtype supports nsmallest and nlargest operations', "convert a pandas DataFrame to a dictionary using orient='dict' with column-to-index mappings", "convert a pandas DataFrame to a list of row dictionaries with orient='records'", 'convert a pandas DataFrame to split format with index, columns, and data arrays', 'convert a pandas DataFrame to tight format including index_names and column_names metadata', "convert a pandas DataFrame to index-keyed dictionary with orient='index' for unique indices"]
```

Usage

```
{'describe_ndframe': 'describe a pandas Series or DataFrame with custom percentiles, include, and exclude filters', 'describe_numeric_1d': 'describe a numeric pandas Series returning count, mean, std, min, percentiles, and max', 'describe_categorical_1d': 'describe a categorical pandas Series returning count, unique, top, and freq', 'describe_timestamp_1d': 'describe a datetime pandas Series returning count, mean, min, percentiles, and max', 'select_describe_func': 'select the appropriate describe function for a pandas Series based on its dtype'}
```

## File: pandas-dev_pandas/pandas/core/methods/selectn.py

Prompts

```
['describe a pandas Series or DataFrame with custom percentiles, include, and exclude filters', 'describe a numeric pandas Series returning count, mean, std, min, percentiles, and max', 'describe a categorical pandas Series returning count, unique, top, and freq', 'describe a datetime pandas Series returning count, mean, min, percentiles, and max', 'select the appropriate describe function for a pandas Series based on its dtype', 'test the SelectN class nlargest method to return the n largest values from an object', 'test the SelectN class nsmallest method to return the n smallest values from an object', 'test the SelectNSeries compute method to get the n largest or smallest values from a Series', 'test the SelectNFrame compute method to get the n largest or smallest rows from a DataFrame across columns', 'test the SelectN is_valid_dtype_n_method helper to check if a dtype supports nsmallest and nlargest operations', "convert a pandas DataFrame to a dictionary using orient='dict' with column-to-index mappings", "convert a pandas DataFrame to a list of row dictionaries with orient='records'", 'convert a pandas DataFrame to split format with index, columns, and data arrays', 'convert a pandas DataFrame to tight format including index_names and column_names metadata', "convert a pandas DataFrame to index-keyed dictionary with orient='index' for unique indices"]
```

Usage

```
{'test_SelectN_nlargest': 'test the SelectN class nlargest method to return the n largest values from an object', 'test_SelectN_nsmallest': 'test the SelectN class nsmallest method to return the n smallest values from an object', 'test_SelectNSeries_compute': 'test the SelectNSeries compute method to get the n largest or smallest values from a Series', 'test_SelectNFrame_compute': 'test the SelectNFrame compute method to get the n largest or smallest rows from a DataFrame across columns', 'test_SelectN_is_valid_dtype_n_method': 'test the SelectN is_valid_dtype_n_method helper to check if a dtype supports nsmallest and nlargest operations'}
```

## File: pandas-dev_pandas/pandas/core/methods/to_dict.py

Prompts

```
['describe a pandas Series or DataFrame with custom percentiles, include, and exclude filters', 'describe a numeric pandas Series returning count, mean, std, min, percentiles, and max', 'describe a categorical pandas Series returning count, unique, top, and freq', 'describe a datetime pandas Series returning count, mean, min, percentiles, and max', 'select the appropriate describe function for a pandas Series based on its dtype', 'test the SelectN class nlargest method to return the n largest values from an object', 'test the SelectN class nsmallest method to return the n smallest values from an object', 'test the SelectNSeries compute method to get the n largest or smallest values from a Series', 'test the SelectNFrame compute method to get the n largest or smallest rows from a DataFrame across columns', 'test the SelectN is_valid_dtype_n_method helper to check if a dtype supports nsmallest and nlargest operations', "convert a pandas DataFrame to a dictionary using orient='dict' with column-to-index mappings", "convert a pandas DataFrame to a list of row dictionaries with orient='records'", 'convert a pandas DataFrame to split format with index, columns, and data arrays', 'convert a pandas DataFrame to tight format including index_names and column_names metadata', "convert a pandas DataFrame to index-keyed dictionary with orient='index' for unique indices"]
```

Usage

```
{'convert_dataframe_to_dict': "convert a pandas DataFrame to a dictionary using orient='dict' with column-to-index mappings", 'convert_dataframe_to_records': "convert a pandas DataFrame to a list of row dictionaries with orient='records'", 'convert_dataframe_to_split': 'convert a pandas DataFrame to split format with index, columns, and data arrays', 'convert_dataframe_to_tight': 'convert a pandas DataFrame to tight format including index_names and column_names metadata', 'convert_dataframe_to_index': "convert a pandas DataFrame to index-keyed dictionary with orient='index' for unique indices"}
```

