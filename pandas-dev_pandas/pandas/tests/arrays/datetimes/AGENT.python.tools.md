# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/arrays/datetimes/test_constructors.py

Prompts

```
['test DatetimeArray._from_sequence raises TypeError when given an invalid MultiIndex input type', 'test DatetimeArray._from_sequence, pd.to_datetime, and pd.DatetimeIndex raise ValueError when mixing tz-naive and tz-aware timestamps', 'test DatetimeArray._from_sequence constructs a datetime array from a pandas array of int64 values and verifies frequency inference', 'test DatetimeArray._from_sequence, pd.DatetimeIndex, and pd.to_datetime raise TypeError when given a boolean dtype array', 'test DatetimeArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test DatetimeArray._from_sequence preserves numpy datetime64 unit from the input array dtype', 'test DatetimeArray._from_sequence raises TypeError when data is already tz-aware but a different timezone dtype is specified', 'test DatetimeArray._from_sequence returns identical array when input dtype matches the data timezone', 'test DatetimeArray._from_sequence handles 2D arrays in both C and Fortran memory order', 'test DatetimeTZDtype.__from_arrow__ converts pyarrow timestamp arrays with different units and timezones to DatetimeArray', 'test DatetimeArray._accumulate with cummin and cummax operations preserving frequency', 'test that DatetimeArray._accumulate raises TypeError for cumsum operation', 'test that DatetimeArray._accumulate raises TypeError for cumprod operation', 'test tm.assert_datetime_array_equal validates DatetimeArray equality results', 'test to_offset converts inferred_freq to a frequency offset for DatetimeArray', 'test DatetimeArray.min() and DatetimeArray.max() return correct min/max values with timezone and unit', 'test DatetimeArray.median() computes correct median value skipping NaT entries', 'test DatetimeArray.mean() computes correct mean value with timedelta arithmetic', 'test DatetimeArray.median() on 2D reshaped arrays with axis parameter', 'test DatetimeArray.mean() on 2D reshaped arrays with axis parameter']
```

Usage

```
{'test_DatetimeArray_from_sequence_invalid_type': 'test DatetimeArray._from_sequence raises TypeError when given an invalid MultiIndex input type', 'test_DatetimeArray_mixing_naive_tzaware_raises': 'test DatetimeArray._from_sequence, pd.to_datetime, and pd.DatetimeIndex raise ValueError when mixing tz-naive and tz-aware timestamps', 'test_DatetimeArray_from_pandas_array': 'test DatetimeArray._from_sequence constructs a datetime array from a pandas array of int64 values and verifies frequency inference', 'test_DatetimeArray_bool_dtype_raises': 'test DatetimeArray._from_sequence, pd.DatetimeIndex, and pd.to_datetime raise TypeError when given a boolean dtype array', 'test_DatetimeArray_copy': 'test DatetimeArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test_DatetimeArray_numpy_datetime_unit': 'test DatetimeArray._from_sequence preserves numpy datetime64 unit from the input array dtype', 'test_DatetimeArray_tz_dtype_mismatch_raises': 'test DatetimeArray._from_sequence raises TypeError when data is already tz-aware but a different timezone dtype is specified', 'test_DatetimeArray_tz_dtype_matches': 'test DatetimeArray._from_sequence returns identical array when input dtype matches the data timezone', 'test_DatetimeArray_2d': 'test DatetimeArray._from_sequence handles 2D arrays in both C and Fortran memory order', 'test_DatetimeArray_from_arrow_different_units_tz': 'test DatetimeTZDtype.__from_arrow__ converts pyarrow timestamp arrays with different units and timezones to DatetimeArray'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/datetimes/test_cumulative.py

Prompts

```
['test DatetimeArray._from_sequence raises TypeError when given an invalid MultiIndex input type', 'test DatetimeArray._from_sequence, pd.to_datetime, and pd.DatetimeIndex raise ValueError when mixing tz-naive and tz-aware timestamps', 'test DatetimeArray._from_sequence constructs a datetime array from a pandas array of int64 values and verifies frequency inference', 'test DatetimeArray._from_sequence, pd.DatetimeIndex, and pd.to_datetime raise TypeError when given a boolean dtype array', 'test DatetimeArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test DatetimeArray._from_sequence preserves numpy datetime64 unit from the input array dtype', 'test DatetimeArray._from_sequence raises TypeError when data is already tz-aware but a different timezone dtype is specified', 'test DatetimeArray._from_sequence returns identical array when input dtype matches the data timezone', 'test DatetimeArray._from_sequence handles 2D arrays in both C and Fortran memory order', 'test DatetimeTZDtype.__from_arrow__ converts pyarrow timestamp arrays with different units and timezones to DatetimeArray', 'test DatetimeArray._accumulate with cummin and cummax operations preserving frequency', 'test that DatetimeArray._accumulate raises TypeError for cumsum operation', 'test that DatetimeArray._accumulate raises TypeError for cumprod operation', 'test tm.assert_datetime_array_equal validates DatetimeArray equality results', 'test to_offset converts inferred_freq to a frequency offset for DatetimeArray', 'test DatetimeArray.min() and DatetimeArray.max() return correct min/max values with timezone and unit', 'test DatetimeArray.median() computes correct median value skipping NaT entries', 'test DatetimeArray.mean() computes correct mean value with timedelta arithmetic', 'test DatetimeArray.median() on 2D reshaped arrays with axis parameter', 'test DatetimeArray.mean() on 2D reshaped arrays with axis parameter']
```

Usage

```
{'test_accumulators_freq': 'test DatetimeArray._accumulate with cummin and cummax operations preserving frequency', 'test_accumulators_disallowed_cumsum': 'test that DatetimeArray._accumulate raises TypeError for cumsum operation', 'test_accumulators_disallowed_cumprod': 'test that DatetimeArray._accumulate raises TypeError for cumprod operation', 'test_assert_datetime_array_equal': 'test tm.assert_datetime_array_equal validates DatetimeArray equality results', 'test_to_offset_inferred_freq': 'test to_offset converts inferred_freq to a frequency offset for DatetimeArray'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/datetimes/test_reductions.py

Prompts

```
['test DatetimeArray._from_sequence raises TypeError when given an invalid MultiIndex input type', 'test DatetimeArray._from_sequence, pd.to_datetime, and pd.DatetimeIndex raise ValueError when mixing tz-naive and tz-aware timestamps', 'test DatetimeArray._from_sequence constructs a datetime array from a pandas array of int64 values and verifies frequency inference', 'test DatetimeArray._from_sequence, pd.DatetimeIndex, and pd.to_datetime raise TypeError when given a boolean dtype array', 'test DatetimeArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test DatetimeArray._from_sequence preserves numpy datetime64 unit from the input array dtype', 'test DatetimeArray._from_sequence raises TypeError when data is already tz-aware but a different timezone dtype is specified', 'test DatetimeArray._from_sequence returns identical array when input dtype matches the data timezone', 'test DatetimeArray._from_sequence handles 2D arrays in both C and Fortran memory order', 'test DatetimeTZDtype.__from_arrow__ converts pyarrow timestamp arrays with different units and timezones to DatetimeArray', 'test DatetimeArray._accumulate with cummin and cummax operations preserving frequency', 'test that DatetimeArray._accumulate raises TypeError for cumsum operation', 'test that DatetimeArray._accumulate raises TypeError for cumprod operation', 'test tm.assert_datetime_array_equal validates DatetimeArray equality results', 'test to_offset converts inferred_freq to a frequency offset for DatetimeArray', 'test DatetimeArray.min() and DatetimeArray.max() return correct min/max values with timezone and unit', 'test DatetimeArray.median() computes correct median value skipping NaT entries', 'test DatetimeArray.mean() computes correct mean value with timedelta arithmetic', 'test DatetimeArray.median() on 2D reshaped arrays with axis parameter', 'test DatetimeArray.mean() on 2D reshaped arrays with axis parameter']
```

Usage

```
{'test_datetimearray_min_max': 'test DatetimeArray.min() and DatetimeArray.max() return correct min/max values with timezone and unit', 'test_datetimearray_median': 'test DatetimeArray.median() computes correct median value skipping NaT entries', 'test_datetimearray_mean': 'test DatetimeArray.mean() computes correct mean value with timedelta arithmetic', 'test_datetimearray_median_2d': 'test DatetimeArray.median() on 2D reshaped arrays with axis parameter', 'test_datetimearray_mean_2d': 'test DatetimeArray.mean() on 2D reshaped arrays with axis parameter'}
```

