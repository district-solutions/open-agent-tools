# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/reductions/test_reductions.py

Prompts

```
['test the Series min and max reduction operations on various dtypes including datetime, nullable, and timedelta', 'test the Series idxmin and idxmax methods to find the index of the minimum or maximum value', 'test the Series sum operation handles integer overflow for int32 and int64 dtypes', 'test the Series mode method for numerical, string, datetime, timedelta, and categorical data', 'test the RangeIndex min and max reduction operations on large ranges with various step values', 'test the Series.sum() statistical reduction on float64 data with NaN handling', 'test the Series.mean() statistical reduction on float64 data with NaN handling', 'test the Series.var() and Series.std() statistical reductions with custom ddof values', 'test the Series.skew() statistical reduction against scipy.stats.skew with NaN handling', 'test the Series.kurt() statistical reduction against scipy.stats.kurtosis with NaN handling']
```

Usage

```
{'test_series_min_max_reductions': 'test the Series min and max reduction operations on various dtypes including datetime, nullable, and timedelta', 'test_series_idxminmax': 'test the Series idxmin and idxmax methods to find the index of the minimum or maximum value', 'test_series_sum_overflow': 'test the Series sum operation handles integer overflow for int32 and int64 dtypes', 'test_series_mode': 'test the Series mode method for numerical, string, datetime, timedelta, and categorical data', 'test_index_minmax_range': 'test the RangeIndex min and max reduction operations on large ranges with various step values'}
```

## File: pandas-dev_pandas/pandas/tests/reductions/test_stat_reductions.py

Prompts

```
['test the Series min and max reduction operations on various dtypes including datetime, nullable, and timedelta', 'test the Series idxmin and idxmax methods to find the index of the minimum or maximum value', 'test the Series sum operation handles integer overflow for int32 and int64 dtypes', 'test the Series mode method for numerical, string, datetime, timedelta, and categorical data', 'test the RangeIndex min and max reduction operations on large ranges with various step values', 'test the Series.sum() statistical reduction on float64 data with NaN handling', 'test the Series.mean() statistical reduction on float64 data with NaN handling', 'test the Series.var() and Series.std() statistical reductions with custom ddof values', 'test the Series.skew() statistical reduction against scipy.stats.skew with NaN handling', 'test the Series.kurt() statistical reduction against scipy.stats.kurtosis with NaN handling']
```

Usage

```
{'test_series_stat_reductions_sum': 'test the Series.sum() statistical reduction on float64 data with NaN handling', 'test_series_stat_reductions_mean': 'test the Series.mean() statistical reduction on float64 data with NaN handling', 'test_series_stat_reductions_var_std': 'test the Series.var() and Series.std() statistical reductions with custom ddof values', 'test_series_stat_reductions_skew': 'test the Series.skew() statistical reduction against scipy.stats.skew with NaN handling', 'test_series_stat_reductions_kurt': 'test the Series.kurt() statistical reduction against scipy.stats.kurtosis with NaN handling'}
```

