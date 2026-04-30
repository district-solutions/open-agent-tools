# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/arrays/period/test_arrow_compat.py

Prompts

```
['create an ArrowPeriodType with a frequency string and compare equality and hash consistency', 'test converting a PeriodArray to a PyArrow array with ArrowPeriodType extension type', 'test converting a PeriodArray with NaT values to a PyArrow array preserving nulls', 'test roundtripping a DataFrame with PeriodArray columns through a PyArrow table', 'test concatenating PyArrow tables with PeriodArray columns and converting back to pandas', 'test loading a PyArrow table from an empty chunked array with PeriodType schema', 'test roundtripping a PeriodArray DataFrame through PyArrow without schema metadata', 'test the PeriodArray.astype method with integer dtypes including int, np.int32, np.int64, uint32, uint64', 'test the PeriodArray.astype method with copy=False and copy=True to verify view vs copy behavior', 'test the PeriodArray.astype method to convert a PeriodArray to a Categorical with correct categories', 'test the PeriodArray.astype method to convert between PeriodDtype with different frequencies like D to M', 'test the PeriodArray.astype method to convert to datetime64[ns] and verify TypeError for timedelta64[ns]', 'test pd.PeriodIndex construction from lists of Period objects, integers, strings, and datetime ranges with optional freq parameter', 'test pd.PeriodIndex construction from a numpy readonly object array containing Period objects', 'test PeriodArray._from_datetime64 conversion of numpy datetime64 arrays to PeriodArray with a specified frequency', 'test pd.PeriodIndex raises IncompatibleFrequency when input Period objects have mismatched frequencies', 'test PeriodArray raises IncompatibleFrequency when constructed with a dtype having a different frequency than the input array', 'test the PeriodIndex array min and max reduction methods with NaT values', 'test the PeriodIndex array min and max with skipna=False returning NaT', 'test the PeriodIndex array min and max on an empty array returning NaT', 'test creating a PeriodIndex array with mixed valid periods and NaT values', 'test comparing PeriodIndex array reduction results with expected Period values']
```

Usage

```
{'create_ArrowPeriodType': 'create an ArrowPeriodType with a frequency string and compare equality and hash consistency', 'test_arrow_array': 'test converting a PeriodArray to a PyArrow array with ArrowPeriodType extension type', 'test_arrow_array_missing': 'test converting a PeriodArray with NaT values to a PyArrow array preserving nulls', 'test_arrow_table_roundtrip': 'test roundtripping a DataFrame with PeriodArray columns through a PyArrow table', 'test_arrow_concat_tables': 'test concatenating PyArrow tables with PeriodArray columns and converting back to pandas', 'test_arrow_load_from_zero_chunks': 'test loading a PyArrow table from an empty chunked array with PeriodType schema', 'test_arrow_roundtrip_without_metadata': 'test roundtripping a PeriodArray DataFrame through PyArrow without schema metadata'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/period/test_astype.py

Prompts

```
['create an ArrowPeriodType with a frequency string and compare equality and hash consistency', 'test converting a PeriodArray to a PyArrow array with ArrowPeriodType extension type', 'test converting a PeriodArray with NaT values to a PyArrow array preserving nulls', 'test roundtripping a DataFrame with PeriodArray columns through a PyArrow table', 'test concatenating PyArrow tables with PeriodArray columns and converting back to pandas', 'test loading a PyArrow table from an empty chunked array with PeriodType schema', 'test roundtripping a PeriodArray DataFrame through PyArrow without schema metadata', 'test the PeriodArray.astype method with integer dtypes including int, np.int32, np.int64, uint32, uint64', 'test the PeriodArray.astype method with copy=False and copy=True to verify view vs copy behavior', 'test the PeriodArray.astype method to convert a PeriodArray to a Categorical with correct categories', 'test the PeriodArray.astype method to convert between PeriodDtype with different frequencies like D to M', 'test the PeriodArray.astype method to convert to datetime64[ns] and verify TypeError for timedelta64[ns]', 'test pd.PeriodIndex construction from lists of Period objects, integers, strings, and datetime ranges with optional freq parameter', 'test pd.PeriodIndex construction from a numpy readonly object array containing Period objects', 'test PeriodArray._from_datetime64 conversion of numpy datetime64 arrays to PeriodArray with a specified frequency', 'test pd.PeriodIndex raises IncompatibleFrequency when input Period objects have mismatched frequencies', 'test PeriodArray raises IncompatibleFrequency when constructed with a dtype having a different frequency than the input array', 'test the PeriodIndex array min and max reduction methods with NaT values', 'test the PeriodIndex array min and max with skipna=False returning NaT', 'test the PeriodIndex array min and max on an empty array returning NaT', 'test creating a PeriodIndex array with mixed valid periods and NaT values', 'test comparing PeriodIndex array reduction results with expected Period values']
```

Usage

```
{'test_astype_int': 'test the PeriodArray.astype method with integer dtypes including int, np.int32, np.int64, uint32, uint64', 'test_astype_copies': 'test the PeriodArray.astype method with copy=False and copy=True to verify view vs copy behavior', 'test_astype_categorical': 'test the PeriodArray.astype method to convert a PeriodArray to a Categorical with correct categories', 'test_astype_period': 'test the PeriodArray.astype method to convert between PeriodDtype with different frequencies like D to M', 'test_astype_datetime': 'test the PeriodArray.astype method to convert to datetime64[ns] and verify TypeError for timedelta64[ns]'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/period/test_constructors.py

Prompts

```
['create an ArrowPeriodType with a frequency string and compare equality and hash consistency', 'test converting a PeriodArray to a PyArrow array with ArrowPeriodType extension type', 'test converting a PeriodArray with NaT values to a PyArrow array preserving nulls', 'test roundtripping a DataFrame with PeriodArray columns through a PyArrow table', 'test concatenating PyArrow tables with PeriodArray columns and converting back to pandas', 'test loading a PyArrow table from an empty chunked array with PeriodType schema', 'test roundtripping a PeriodArray DataFrame through PyArrow without schema metadata', 'test the PeriodArray.astype method with integer dtypes including int, np.int32, np.int64, uint32, uint64', 'test the PeriodArray.astype method with copy=False and copy=True to verify view vs copy behavior', 'test the PeriodArray.astype method to convert a PeriodArray to a Categorical with correct categories', 'test the PeriodArray.astype method to convert between PeriodDtype with different frequencies like D to M', 'test the PeriodArray.astype method to convert to datetime64[ns] and verify TypeError for timedelta64[ns]', 'test pd.PeriodIndex construction from lists of Period objects, integers, strings, and datetime ranges with optional freq parameter', 'test pd.PeriodIndex construction from a numpy readonly object array containing Period objects', 'test PeriodArray._from_datetime64 conversion of numpy datetime64 arrays to PeriodArray with a specified frequency', 'test pd.PeriodIndex raises IncompatibleFrequency when input Period objects have mismatched frequencies', 'test PeriodArray raises IncompatibleFrequency when constructed with a dtype having a different frequency than the input array', 'test the PeriodIndex array min and max reduction methods with NaT values', 'test the PeriodIndex array min and max with skipna=False returning NaT', 'test the PeriodIndex array min and max on an empty array returning NaT', 'test creating a PeriodIndex array with mixed valid periods and NaT values', 'test comparing PeriodIndex array reduction results with expected Period values']
```

Usage

```
{'test_period_array_ok': 'test pd.PeriodIndex construction from lists of Period objects, integers, strings, and datetime ranges with optional freq parameter', 'test_period_array_readonly_object': 'test pd.PeriodIndex construction from a numpy readonly object array containing Period objects', 'test_period_array_from_datetime64': 'test PeriodArray._from_datetime64 conversion of numpy datetime64 arrays to PeriodArray with a specified frequency', 'test_period_array_raises': 'test pd.PeriodIndex raises IncompatibleFrequency when input Period objects have mismatched frequencies', 'test_period_array_freq_mismatch': 'test PeriodArray raises IncompatibleFrequency when constructed with a dtype having a different frequency than the input array'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/period/test_reductions.py

Prompts

```
['create an ArrowPeriodType with a frequency string and compare equality and hash consistency', 'test converting a PeriodArray to a PyArrow array with ArrowPeriodType extension type', 'test converting a PeriodArray with NaT values to a PyArrow array preserving nulls', 'test roundtripping a DataFrame with PeriodArray columns through a PyArrow table', 'test concatenating PyArrow tables with PeriodArray columns and converting back to pandas', 'test loading a PyArrow table from an empty chunked array with PeriodType schema', 'test roundtripping a PeriodArray DataFrame through PyArrow without schema metadata', 'test the PeriodArray.astype method with integer dtypes including int, np.int32, np.int64, uint32, uint64', 'test the PeriodArray.astype method with copy=False and copy=True to verify view vs copy behavior', 'test the PeriodArray.astype method to convert a PeriodArray to a Categorical with correct categories', 'test the PeriodArray.astype method to convert between PeriodDtype with different frequencies like D to M', 'test the PeriodArray.astype method to convert to datetime64[ns] and verify TypeError for timedelta64[ns]', 'test pd.PeriodIndex construction from lists of Period objects, integers, strings, and datetime ranges with optional freq parameter', 'test pd.PeriodIndex construction from a numpy readonly object array containing Period objects', 'test PeriodArray._from_datetime64 conversion of numpy datetime64 arrays to PeriodArray with a specified frequency', 'test pd.PeriodIndex raises IncompatibleFrequency when input Period objects have mismatched frequencies', 'test PeriodArray raises IncompatibleFrequency when constructed with a dtype having a different frequency than the input array', 'test the PeriodIndex array min and max reduction methods with NaT values', 'test the PeriodIndex array min and max with skipna=False returning NaT', 'test the PeriodIndex array min and max on an empty array returning NaT', 'test creating a PeriodIndex array with mixed valid periods and NaT values', 'test comparing PeriodIndex array reduction results with expected Period values']
```

Usage

```
{'test_period_array_min_max': 'test the PeriodIndex array min and max reduction methods with NaT values', 'test_period_array_min_max_skipna': 'test the PeriodIndex array min and max with skipna=False returning NaT', 'test_period_array_min_max_empty': 'test the PeriodIndex array min and max on an empty array returning NaT', 'test_period_array_creation': 'test creating a PeriodIndex array with mixed valid periods and NaT values', 'test_period_array_comparison': 'test comparing PeriodIndex array reduction results with expected Period values'}
```

