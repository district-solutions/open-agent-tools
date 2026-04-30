# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/arrays/timedeltas/test_constructors.py

Prompts

```
['test TimedeltaArray._from_sequence raises TypeError when passed a bool dtype array', 'test TimedeltaArray._from_sequence raises ValueError for invalid dtypes like category, int64, datetime64, and unsupported resolutions', 'test TimedeltaArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test TimedeltaArray._from_sequence raises ValueError when passed object dtype', 'test TimedeltaArray._from_sequence rejects unsupported timedelta64 resolutions such as yearly (m8[Y])', 'test that cumprod raises TypeError on TimedeltaArray._accumulate', 'test that cumsum returns correct cumulative sum on TimedeltaArray._accumulate', 'create a TimedeltaArray from a sequence of string timedelta values', 'test equality of two TimedeltaArray objects using assert_timedelta_array_equal', 'test TimedeltaArray._accumulate with different time units via dtype parameterization', 'test TimedeltaIndex reduction methods (std, min, max, median, mean) return NaT on empty input', 'test TimedeltaIndex.sum() returns Timedelta(0) on empty input regardless of skipna', 'test TimedeltaArray.min() and max() compute correct values and handle NaT with skipna', 'test TimedeltaArray.sum() handles skipna and min_count parameters correctly', 'test numpy.sum() on TimedeltaIndex returns Timedelta, not timedelta64']
```

Usage

```
{'test_TimedeltaArray_constructor_raises_bool': 'test TimedeltaArray._from_sequence raises TypeError when passed a bool dtype array', 'test_TimedeltaArray_constructor_invalid_dtypes': 'test TimedeltaArray._from_sequence raises ValueError for invalid dtypes like category, int64, datetime64, and unsupported resolutions', 'test_TimedeltaArray_copy_behavior': 'test TimedeltaArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test_TimedeltaArray_constructor_object_dtype': 'test TimedeltaArray._from_sequence raises ValueError when passed object dtype', 'test_TimedeltaArray_constructor_resolution_validation': 'test TimedeltaArray._from_sequence rejects unsupported timedelta64 resolutions such as yearly (m8[Y])'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/timedeltas/test_cumulative.py

Prompts

```
['test TimedeltaArray._from_sequence raises TypeError when passed a bool dtype array', 'test TimedeltaArray._from_sequence raises ValueError for invalid dtypes like category, int64, datetime64, and unsupported resolutions', 'test TimedeltaArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test TimedeltaArray._from_sequence raises ValueError when passed object dtype', 'test TimedeltaArray._from_sequence rejects unsupported timedelta64 resolutions such as yearly (m8[Y])', 'test that cumprod raises TypeError on TimedeltaArray._accumulate', 'test that cumsum returns correct cumulative sum on TimedeltaArray._accumulate', 'create a TimedeltaArray from a sequence of string timedelta values', 'test equality of two TimedeltaArray objects using assert_timedelta_array_equal', 'test TimedeltaArray._accumulate with different time units via dtype parameterization', 'test TimedeltaIndex reduction methods (std, min, max, median, mean) return NaT on empty input', 'test TimedeltaIndex.sum() returns Timedelta(0) on empty input regardless of skipna', 'test TimedeltaArray.min() and max() compute correct values and handle NaT with skipna', 'test TimedeltaArray.sum() handles skipna and min_count parameters correctly', 'test numpy.sum() on TimedeltaIndex returns Timedelta, not timedelta64']
```

Usage

```
{'test_accumulators_disallowed': 'test that cumprod raises TypeError on TimedeltaArray._accumulate', 'test_cumsum': 'test that cumsum returns correct cumulative sum on TimedeltaArray._accumulate', 'create_TimedeltaArray_from_sequence': 'create a TimedeltaArray from a sequence of string timedelta values', 'test_assert_timedelta_array_equal': 'test equality of two TimedeltaArray objects using assert_timedelta_array_equal', 'test_dtype_parameterization': 'test TimedeltaArray._accumulate with different time units via dtype parameterization'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/timedeltas/test_reductions.py

Prompts

```
['test TimedeltaArray._from_sequence raises TypeError when passed a bool dtype array', 'test TimedeltaArray._from_sequence raises ValueError for invalid dtypes like category, int64, datetime64, and unsupported resolutions', 'test TimedeltaArray._from_sequence copy parameter controls whether the underlying ndarray is shared or copied', 'test TimedeltaArray._from_sequence raises ValueError when passed object dtype', 'test TimedeltaArray._from_sequence rejects unsupported timedelta64 resolutions such as yearly (m8[Y])', 'test that cumprod raises TypeError on TimedeltaArray._accumulate', 'test that cumsum returns correct cumulative sum on TimedeltaArray._accumulate', 'create a TimedeltaArray from a sequence of string timedelta values', 'test equality of two TimedeltaArray objects using assert_timedelta_array_equal', 'test TimedeltaArray._accumulate with different time units via dtype parameterization', 'test TimedeltaIndex reduction methods (std, min, max, median, mean) return NaT on empty input', 'test TimedeltaIndex.sum() returns Timedelta(0) on empty input regardless of skipna', 'test TimedeltaArray.min() and max() compute correct values and handle NaT with skipna', 'test TimedeltaArray.sum() handles skipna and min_count parameters correctly', 'test numpy.sum() on TimedeltaIndex returns Timedelta, not timedelta64']
```

Usage

```
{'test_timedeltaindex_reductions_empty': 'test TimedeltaIndex reduction methods (std, min, max, median, mean) return NaT on empty input', 'test_timedeltaindex_sum_empty': 'test TimedeltaIndex.sum() returns Timedelta(0) on empty input regardless of skipna', 'test_timedeltaindex_min_max': 'test TimedeltaArray.min() and max() compute correct values and handle NaT with skipna', 'test_timedeltaindex_sum': 'test TimedeltaArray.sum() handles skipna and min_count parameters correctly', 'test_timedeltaindex_npsum': 'test numpy.sum() on TimedeltaIndex returns Timedelta, not timedelta64'}
```

