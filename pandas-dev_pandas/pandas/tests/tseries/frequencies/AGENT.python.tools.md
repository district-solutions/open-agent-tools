# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/tseries/frequencies/test_freq_code.py

Prompts

```
['test the Period._dtype._get_to_timestamp_base method to return the correct base frequency code for various offset types', 'test to_offset to bump fractional numeric multipliers to a coarser frequency resolution', 'test to_offset to raise ValueError when given a frequency with insufficient precision', 'test adding a frequency offset to a numpy datetime64 value to produce the correct resulting timestamp', 'test creating a Period from a date string and a frequency offset string via to_offset', 'test the pandas is_superperiod function to check if one frequency is a superperiod of another', 'test the pandas is_subperiod function to check if one frequency is a subperiod of another', 'test the symmetry of is_superperiod and is_subperiod with offset objects like YearEnd, MonthEnd, Hour, Minute', 'test is_subperiod and is_superperiod identity behavior for string frequency aliases like D, B, M, Q, Y', 'test is_subperiod with anchored frequency strings like Y-DEC, Y-MAR, Q-DEC, Q-MAR to verify month anchor compatibility', 'test the frequencies.infer_freq function to infer frequency from a DatetimeIndex with daily intervals', 'test the frequencies.infer_freq function to infer frequency from a pandas Series with datetime index', 'test the frequencies.infer_freq function to correctly infer business hour frequency from weekday-only timestamps', 'test the frequencies.infer_freq function to support non-nanosecond DatetimeArray and TimedeltaArray', 'test the frequencies.infer_freq function to support pyarrow-backed timestamp Series and Index']
```

Usage

```
{'test_get_to_timestamp_base': 'test the Period._dtype._get_to_timestamp_base method to return the correct base frequency code for various offset types', 'test_resolution_bumping': 'test to_offset to bump fractional numeric multipliers to a coarser frequency resolution', 'test_invalid_frequency': 'test to_offset to raise ValueError when given a frequency with insufficient precision', 'test_offset_compatibility': 'test adding a frequency offset to a numpy datetime64 value to produce the correct resulting timestamp', 'test_period_from_offset': 'test creating a Period from a date string and a frequency offset string via to_offset'}
```

## File: pandas-dev_pandas/pandas/tests/tseries/frequencies/test_frequencies.py

Prompts

```
['test the Period._dtype._get_to_timestamp_base method to return the correct base frequency code for various offset types', 'test to_offset to bump fractional numeric multipliers to a coarser frequency resolution', 'test to_offset to raise ValueError when given a frequency with insufficient precision', 'test adding a frequency offset to a numpy datetime64 value to produce the correct resulting timestamp', 'test creating a Period from a date string and a frequency offset string via to_offset', 'test the pandas is_superperiod function to check if one frequency is a superperiod of another', 'test the pandas is_subperiod function to check if one frequency is a subperiod of another', 'test the symmetry of is_superperiod and is_subperiod with offset objects like YearEnd, MonthEnd, Hour, Minute', 'test is_subperiod and is_superperiod identity behavior for string frequency aliases like D, B, M, Q, Y', 'test is_subperiod with anchored frequency strings like Y-DEC, Y-MAR, Q-DEC, Q-MAR to verify month anchor compatibility', 'test the frequencies.infer_freq function to infer frequency from a DatetimeIndex with daily intervals', 'test the frequencies.infer_freq function to infer frequency from a pandas Series with datetime index', 'test the frequencies.infer_freq function to correctly infer business hour frequency from weekday-only timestamps', 'test the frequencies.infer_freq function to support non-nanosecond DatetimeArray and TimedeltaArray', 'test the frequencies.infer_freq function to support pyarrow-backed timestamp Series and Index']
```

Usage

```
{'test_is_superperiod': 'test the pandas is_superperiod function to check if one frequency is a superperiod of another', 'test_is_subperiod': 'test the pandas is_subperiod function to check if one frequency is a subperiod of another', 'test_super_sub_symmetry': 'test the symmetry of is_superperiod and is_subperiod with offset objects like YearEnd, MonthEnd, Hour, Minute', 'test_is_subperiod_identity': 'test is_subperiod and is_superperiod identity behavior for string frequency aliases like D, B, M, Q, Y', 'test_is_subperiod_anchored_identity': 'test is_subperiod with anchored frequency strings like Y-DEC, Y-MAR, Q-DEC, Q-MAR to verify month anchor compatibility'}
```

## File: pandas-dev_pandas/pandas/tests/tseries/frequencies/test_inference.py

Prompts

```
['test the Period._dtype._get_to_timestamp_base method to return the correct base frequency code for various offset types', 'test to_offset to bump fractional numeric multipliers to a coarser frequency resolution', 'test to_offset to raise ValueError when given a frequency with insufficient precision', 'test adding a frequency offset to a numpy datetime64 value to produce the correct resulting timestamp', 'test creating a Period from a date string and a frequency offset string via to_offset', 'test the pandas is_superperiod function to check if one frequency is a superperiod of another', 'test the pandas is_subperiod function to check if one frequency is a subperiod of another', 'test the symmetry of is_superperiod and is_subperiod with offset objects like YearEnd, MonthEnd, Hour, Minute', 'test is_subperiod and is_superperiod identity behavior for string frequency aliases like D, B, M, Q, Y', 'test is_subperiod with anchored frequency strings like Y-DEC, Y-MAR, Q-DEC, Q-MAR to verify month anchor compatibility', 'test the frequencies.infer_freq function to infer frequency from a DatetimeIndex with daily intervals', 'test the frequencies.infer_freq function to infer frequency from a pandas Series with datetime index', 'test the frequencies.infer_freq function to correctly infer business hour frequency from weekday-only timestamps', 'test the frequencies.infer_freq function to support non-nanosecond DatetimeArray and TimedeltaArray', 'test the frequencies.infer_freq function to support pyarrow-backed timestamp Series and Index']
```

Usage

```
{'test_infer_freq_datetime_index': 'test the frequencies.infer_freq function to infer frequency from a DatetimeIndex with daily intervals', 'test_infer_freq_series': 'test the frequencies.infer_freq function to infer frequency from a pandas Series with datetime index', 'test_infer_freq_business_hour': 'test the frequencies.infer_freq function to correctly infer business hour frequency from weekday-only timestamps', 'test_infer_freq_non_nano': 'test the frequencies.infer_freq function to support non-nanosecond DatetimeArray and TimedeltaArray', 'test_infer_freq_pyarrow': 'test the frequencies.infer_freq function to support pyarrow-backed timestamp Series and Index'}
```

