# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/frame/constructors/test_from_dict.py

Prompts

```
["test DataFrame.from_dict with orient='index' to construct a DataFrame from a dict of Series", "test DataFrame.from_dict with orient='columns' to construct a DataFrame from a nested dict of scalars", "test DataFrame.from_dict with orient='index' and columns parameter to rename column headers", 'test DataFrame.from_dict with a list of dicts raises a Pandas4Warning deprecation warning', 'test DataFrame.from_dict with all scalar values raises ValueError without an index', 'test DataFrame.from_records with numpy recarray containing datetime fields and null values', 'test DataFrame.from_records with list of tuples and explicit columns parameter', 'test DataFrame.from_records with dict of series and columns parameter', 'test DataFrame.from_records with iterator and nrows parameter to limit rows', 'test DataFrame.from_records with 2D ndarray preserving dtype and columns']
```

Usage

```
{'test_from_dict_orient_index': "test DataFrame.from_dict with orient='index' to construct a DataFrame from a dict of Series", 'test_from_dict_orient_columns': "test DataFrame.from_dict with orient='columns' to construct a DataFrame from a nested dict of scalars", 'test_from_dict_columns_parameter': "test DataFrame.from_dict with orient='index' and columns parameter to rename column headers", 'test_from_dict_list_deprecated': 'test DataFrame.from_dict with a list of dicts raises a Pandas4Warning deprecation warning', 'test_from_dict_scalars_requires_index': 'test DataFrame.from_dict with all scalar values raises ValueError without an index'}
```

## File: pandas-dev_pandas/pandas/tests/frame/constructors/test_from_records.py

Prompts

```
["test DataFrame.from_dict with orient='index' to construct a DataFrame from a dict of Series", "test DataFrame.from_dict with orient='columns' to construct a DataFrame from a nested dict of scalars", "test DataFrame.from_dict with orient='index' and columns parameter to rename column headers", 'test DataFrame.from_dict with a list of dicts raises a Pandas4Warning deprecation warning', 'test DataFrame.from_dict with all scalar values raises ValueError without an index', 'test DataFrame.from_records with numpy recarray containing datetime fields and null values', 'test DataFrame.from_records with list of tuples and explicit columns parameter', 'test DataFrame.from_records with dict of series and columns parameter', 'test DataFrame.from_records with iterator and nrows parameter to limit rows', 'test DataFrame.from_records with 2D ndarray preserving dtype and columns']
```

Usage

```
{'test_from_records_recarray': 'test DataFrame.from_records with numpy recarray containing datetime fields and null values', 'test_from_records_tuples': 'test DataFrame.from_records with list of tuples and explicit columns parameter', 'test_from_records_dict': 'test DataFrame.from_records with dict of series and columns parameter', 'test_from_records_iterator': 'test DataFrame.from_records with iterator and nrows parameter to limit rows', 'test_from_records_ndarray_2d': 'test DataFrame.from_records with 2D ndarray preserving dtype and columns'}
```

