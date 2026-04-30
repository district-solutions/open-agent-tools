# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/core/tools/datetimes.py

Prompts

```
['create a function that converts string, numeric, or array inputs to pandas datetime objects', 'test the should_cache function that decides whether caching is beneficial for date parsing', 'build a helper that converts 1D list-like date inputs to DatetimeIndex with format and timezone support', 'assemble datetime Series from a DataFrame with year, month, day columns and optional time components', 'review the DateParseError exception class raised when string date parsing fails', 'create a call to pandas.to_numeric that converts a Series of string numbers to float64', "test to_numeric with errors='coerce' to convert invalid string values to NaN", "refactor to_numeric calls to use downcast='signed' for smallest signed integer dtype", "summarize to_numeric behavior with downcast='float' to reduce to smallest float dtype", "review to_numeric usage with dtype_backend='numpy_nullable' for nullable integer and float types", "create a function that converts a single string like '1 days 06:05:01' to a Timedelta object", 'create a function that converts numeric values to timedeltas by specifying a unit such as seconds or days', 'create a function that converts a list of string timedeltas to a TimedeltaIndex with NaT for invalid entries', 'create a function that converts a pandas Series of string or numeric values to a Series of timedeltas', "test the to_timedelta function with errors='coerce' to handle invalid inputs by returning NaT", "create a time object from a string using pandas.to_time with a fixed format like '%H:%M'", 'create time objects from a list of strings by inferring the time format automatically', "create time objects from a pandas Series with errors='coerce' to convert invalid values to None", 'create a single time object from a string argument using pandas.to_time', 'test the _guess_time_format_for_array function to detect the format of time strings']
```

Usage

```
{'create_to_datetime': 'create a function that converts string, numeric, or array inputs to pandas datetime objects', 'test_should_cache': 'test the should_cache function that decides whether caching is beneficial for date parsing', 'build_convert_listlike_datetimes': 'build a helper that converts 1D list-like date inputs to DatetimeIndex with format and timezone support', 'assemble_from_unit_mappings': 'assemble datetime Series from a DataFrame with year, month, day columns and optional time components', 'review_DateParseError': 'review the DateParseError exception class raised when string date parsing fails'}
```

## File: pandas-dev_pandas/pandas/core/tools/numeric.py

Prompts

```
['create a function that converts string, numeric, or array inputs to pandas datetime objects', 'test the should_cache function that decides whether caching is beneficial for date parsing', 'build a helper that converts 1D list-like date inputs to DatetimeIndex with format and timezone support', 'assemble datetime Series from a DataFrame with year, month, day columns and optional time components', 'review the DateParseError exception class raised when string date parsing fails', 'create a call to pandas.to_numeric that converts a Series of string numbers to float64', "test to_numeric with errors='coerce' to convert invalid string values to NaN", "refactor to_numeric calls to use downcast='signed' for smallest signed integer dtype", "summarize to_numeric behavior with downcast='float' to reduce to smallest float dtype", "review to_numeric usage with dtype_backend='numpy_nullable' for nullable integer and float types", "create a function that converts a single string like '1 days 06:05:01' to a Timedelta object", 'create a function that converts numeric values to timedeltas by specifying a unit such as seconds or days', 'create a function that converts a list of string timedeltas to a TimedeltaIndex with NaT for invalid entries', 'create a function that converts a pandas Series of string or numeric values to a Series of timedeltas', "test the to_timedelta function with errors='coerce' to handle invalid inputs by returning NaT", "create a time object from a string using pandas.to_time with a fixed format like '%H:%M'", 'create time objects from a list of strings by inferring the time format automatically', "create time objects from a pandas Series with errors='coerce' to convert invalid values to None", 'create a single time object from a string argument using pandas.to_time', 'test the _guess_time_format_for_array function to detect the format of time strings']
```

Usage

```
{'create_to_numeric_basic': 'create a call to pandas.to_numeric that converts a Series of string numbers to float64', 'test_to_numeric_coerce': "test to_numeric with errors='coerce' to convert invalid string values to NaN", 'refactor_to_numeric_downcast': "refactor to_numeric calls to use downcast='signed' for smallest signed integer dtype", 'summarize_to_numeric_downcast_float': "summarize to_numeric behavior with downcast='float' to reduce to smallest float dtype", 'review_to_numeric_dtype_backend': "review to_numeric usage with dtype_backend='numpy_nullable' for nullable integer and float types"}
```

## File: pandas-dev_pandas/pandas/core/tools/timedeltas.py

Prompts

```
['create a function that converts string, numeric, or array inputs to pandas datetime objects', 'test the should_cache function that decides whether caching is beneficial for date parsing', 'build a helper that converts 1D list-like date inputs to DatetimeIndex with format and timezone support', 'assemble datetime Series from a DataFrame with year, month, day columns and optional time components', 'review the DateParseError exception class raised when string date parsing fails', 'create a call to pandas.to_numeric that converts a Series of string numbers to float64', "test to_numeric with errors='coerce' to convert invalid string values to NaN", "refactor to_numeric calls to use downcast='signed' for smallest signed integer dtype", "summarize to_numeric behavior with downcast='float' to reduce to smallest float dtype", "review to_numeric usage with dtype_backend='numpy_nullable' for nullable integer and float types", "create a function that converts a single string like '1 days 06:05:01' to a Timedelta object", 'create a function that converts numeric values to timedeltas by specifying a unit such as seconds or days', 'create a function that converts a list of string timedeltas to a TimedeltaIndex with NaT for invalid entries', 'create a function that converts a pandas Series of string or numeric values to a Series of timedeltas', "test the to_timedelta function with errors='coerce' to handle invalid inputs by returning NaT", "create a time object from a string using pandas.to_time with a fixed format like '%H:%M'", 'create time objects from a list of strings by inferring the time format automatically', "create time objects from a pandas Series with errors='coerce' to convert invalid values to None", 'create a single time object from a string argument using pandas.to_time', 'test the _guess_time_format_for_array function to detect the format of time strings']
```

Usage

```
{'create_to_timedelta_scalar_string': "create a function that converts a single string like '1 days 06:05:01' to a Timedelta object", 'create_to_timedelta_numeric_unit': 'create a function that converts numeric values to timedeltas by specifying a unit such as seconds or days', 'create_to_timedelta_list_strings': 'create a function that converts a list of string timedeltas to a TimedeltaIndex with NaT for invalid entries', 'create_to_timedelta_series': 'create a function that converts a pandas Series of string or numeric values to a Series of timedeltas', 'test_to_timedelta_errors_coerce': "test the to_timedelta function with errors='coerce' to handle invalid inputs by returning NaT"}
```

## File: pandas-dev_pandas/pandas/core/tools/times.py

Prompts

```
['create a function that converts string, numeric, or array inputs to pandas datetime objects', 'test the should_cache function that decides whether caching is beneficial for date parsing', 'build a helper that converts 1D list-like date inputs to DatetimeIndex with format and timezone support', 'assemble datetime Series from a DataFrame with year, month, day columns and optional time components', 'review the DateParseError exception class raised when string date parsing fails', 'create a call to pandas.to_numeric that converts a Series of string numbers to float64', "test to_numeric with errors='coerce' to convert invalid string values to NaN", "refactor to_numeric calls to use downcast='signed' for smallest signed integer dtype", "summarize to_numeric behavior with downcast='float' to reduce to smallest float dtype", "review to_numeric usage with dtype_backend='numpy_nullable' for nullable integer and float types", "create a function that converts a single string like '1 days 06:05:01' to a Timedelta object", 'create a function that converts numeric values to timedeltas by specifying a unit such as seconds or days', 'create a function that converts a list of string timedeltas to a TimedeltaIndex with NaT for invalid entries', 'create a function that converts a pandas Series of string or numeric values to a Series of timedeltas', "test the to_timedelta function with errors='coerce' to handle invalid inputs by returning NaT", "create a time object from a string using pandas.to_time with a fixed format like '%H:%M'", 'create time objects from a list of strings by inferring the time format automatically', "create time objects from a pandas Series with errors='coerce' to convert invalid values to None", 'create a single time object from a string argument using pandas.to_time', 'test the _guess_time_format_for_array function to detect the format of time strings']
```

Usage

```
{'create_to_time_parse_string': "create a time object from a string using pandas.to_time with a fixed format like '%H:%M'", 'create_to_time_infer_format': 'create time objects from a list of strings by inferring the time format automatically', 'create_to_time_coerce_errors': "create time objects from a pandas Series with errors='coerce' to convert invalid values to None", 'create_to_time_single_value': 'create a single time object from a string argument using pandas.to_time', 'test_guess_time_format': 'test the _guess_time_format_for_array function to detect the format of time strings'}
```

