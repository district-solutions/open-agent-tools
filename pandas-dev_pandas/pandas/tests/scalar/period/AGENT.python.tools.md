# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/scalar/period/test_arithmetic.py

Prompts

```
['test adding an integer to a Period returns the Period shifted by that amount', 'test adding and subtracting DateOffset and Tick objects to a Period with various frequencies', 'test subtracting one Period from another returns a timedelta offset or raises IncompatibleFrequency', 'test adding and subtracting NaT from a Period returns NaT', 'test comparing two Period objects with the same frequency using equality and ordering operators', 'test Period.asfreq to convert between annual, quarterly, monthly, weekly, daily, hourly, minutely, and secondly frequencies', "test Period.asfreq with start ('S') and end ('E') mode for frequency conversion direction", 'test Period.asfreq behavior near year 0001-01-01 for various frequencies', 'test Period.asfreq with multi-period frequencies like 3Y, 2M and offsets', 'test Period.asfreq with combined frequencies like 1D1h and 1h1D', 'test creating a pandas Period from strings, datetime objects, ordinals, and keyword arguments with various frequencies', 'test that disallowed offset frequencies like BYearBegin, QuarterBegin, and CustomBusinessDay raise ValueError when passed to Period constructor', 'test converting a Period to a Timestamp using start or end time with various frequency aliases', 'test accessing Period properties like year, month, day, quarter, weekday, is_leap_year, and days_in_month', 'test converting a Period from one frequency to another using the asfreq method with how parameter', 'test sorting and comparing Period instances with the same frequency using standard comparison operators', 'test that deprecated frequency aliases like MTH, MONTH, BUS, HR, sec raise INVALID_FREQ_ERR_MSG ValueError', 'test adding and subtracting integers from Period instances to advance or reverse ordinal positions', 'test string representation and formatting of Period instances including strftime and format specifiers', 'test creating NaT Period values from NaT strings, iNaT integers, and None inputs']
```

Usage

```
{'test_period_add_integer': 'test adding an integer to a Period returns the Period shifted by that amount', 'test_period_add_offset': 'test adding and subtracting DateOffset and Tick objects to a Period with various frequencies', 'test_period_sub_period': 'test subtracting one Period from another returns a timedelta offset or raises IncompatibleFrequency', 'test_period_addsub_nat': 'test adding and subtracting NaT from a Period returns NaT', 'test_period_comparison_same_freq': 'test comparing two Period objects with the same frequency using equality and ordering operators'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/period/test_asfreq.py

Prompts

```
['test adding an integer to a Period returns the Period shifted by that amount', 'test adding and subtracting DateOffset and Tick objects to a Period with various frequencies', 'test subtracting one Period from another returns a timedelta offset or raises IncompatibleFrequency', 'test adding and subtracting NaT from a Period returns NaT', 'test comparing two Period objects with the same frequency using equality and ordering operators', 'test Period.asfreq to convert between annual, quarterly, monthly, weekly, daily, hourly, minutely, and secondly frequencies', "test Period.asfreq with start ('S') and end ('E') mode for frequency conversion direction", 'test Period.asfreq behavior near year 0001-01-01 for various frequencies', 'test Period.asfreq with multi-period frequencies like 3Y, 2M and offsets', 'test Period.asfreq with combined frequencies like 1D1h and 1h1D', 'test creating a pandas Period from strings, datetime objects, ordinals, and keyword arguments with various frequencies', 'test that disallowed offset frequencies like BYearBegin, QuarterBegin, and CustomBusinessDay raise ValueError when passed to Period constructor', 'test converting a Period to a Timestamp using start or end time with various frequency aliases', 'test accessing Period properties like year, month, day, quarter, weekday, is_leap_year, and days_in_month', 'test converting a Period from one frequency to another using the asfreq method with how parameter', 'test sorting and comparing Period instances with the same frequency using standard comparison operators', 'test that deprecated frequency aliases like MTH, MONTH, BUS, HR, sec raise INVALID_FREQ_ERR_MSG ValueError', 'test adding and subtracting integers from Period instances to advance or reverse ordinal positions', 'test string representation and formatting of Period instances including strftime and format specifiers', 'test creating NaT Period values from NaT strings, iNaT integers, and None inputs']
```

Usage

```
{'test_asfreq_frequency_conversion': 'test Period.asfreq to convert between annual, quarterly, monthly, weekly, daily, hourly, minutely, and secondly frequencies', 'test_asfreq_start_end_mode': "test Period.asfreq with start ('S') and end ('E') mode for frequency conversion direction", 'test_asfreq_near_zero_dates': 'test Period.asfreq behavior near year 0001-01-01 for various frequencies', 'test_asfreq_mult_period': 'test Period.asfreq with multi-period frequencies like 3Y, 2M and offsets', 'test_asfreq_combined_freq': 'test Period.asfreq with combined frequencies like 1D1h and 1h1D'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/period/test_period.py

Prompts

```
['test adding an integer to a Period returns the Period shifted by that amount', 'test adding and subtracting DateOffset and Tick objects to a Period with various frequencies', 'test subtracting one Period from another returns a timedelta offset or raises IncompatibleFrequency', 'test adding and subtracting NaT from a Period returns NaT', 'test comparing two Period objects with the same frequency using equality and ordering operators', 'test Period.asfreq to convert between annual, quarterly, monthly, weekly, daily, hourly, minutely, and secondly frequencies', "test Period.asfreq with start ('S') and end ('E') mode for frequency conversion direction", 'test Period.asfreq behavior near year 0001-01-01 for various frequencies', 'test Period.asfreq with multi-period frequencies like 3Y, 2M and offsets', 'test Period.asfreq with combined frequencies like 1D1h and 1h1D', 'test creating a pandas Period from strings, datetime objects, ordinals, and keyword arguments with various frequencies', 'test that disallowed offset frequencies like BYearBegin, QuarterBegin, and CustomBusinessDay raise ValueError when passed to Period constructor', 'test converting a Period to a Timestamp using start or end time with various frequency aliases', 'test accessing Period properties like year, month, day, quarter, weekday, is_leap_year, and days_in_month', 'test converting a Period from one frequency to another using the asfreq method with how parameter', 'test sorting and comparing Period instances with the same frequency using standard comparison operators', 'test that deprecated frequency aliases like MTH, MONTH, BUS, HR, sec raise INVALID_FREQ_ERR_MSG ValueError', 'test adding and subtracting integers from Period instances to advance or reverse ordinal positions', 'test string representation and formatting of Period instances including strftime and format specifiers', 'test creating NaT Period values from NaT strings, iNaT integers, and None inputs']
```

Usage

```
{'test_period_construction': 'test creating a pandas Period from strings, datetime objects, ordinals, and keyword arguments with various frequencies', 'test_period_disallowed_freqs': 'test that disallowed offset frequencies like BYearBegin, QuarterBegin, and CustomBusinessDay raise ValueError when passed to Period constructor', 'test_period_to_timestamp': 'test converting a Period to a Timestamp using start or end time with various frequency aliases', 'test_period_properties': 'test accessing Period properties like year, month, day, quarter, weekday, is_leap_year, and days_in_month', 'test_period_asfreq': 'test converting a Period from one frequency to another using the asfreq method with how parameter', 'test_period_comparison': 'test sorting and comparing Period instances with the same frequency using standard comparison operators', 'test_period_deprecated_freq': 'test that deprecated frequency aliases like MTH, MONTH, BUS, HR, sec raise INVALID_FREQ_ERR_MSG ValueError', 'test_period_arithmetic': 'test adding and subtracting integers from Period instances to advance or reverse ordinal positions', 'test_period_repr': 'test string representation and formatting of Period instances including strftime and format specifiers', 'test_period_nat': 'test creating NaT Period values from NaT strings, iNaT integers, and None inputs'}
```

