# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/conftest.py

Prompts

```
['test the pytest fixture df that returns a polars DataFrame with boolean, integer, float, string, date, datetime, time, and list columns', 'test the pytest fixture fruits_cars that returns a polars DataFrame with integer, fruit, and car columns', 'test the pytest fixture str_ints_df that generates a polars DataFrame with random strings and float values', 'test the pytest fixtures iso8601_format_datetime, iso8601_tz_aware_format_datetime, and iso8601_format_date that provide ISO8601 format parameterized test data', 'test the MemoryUsage class and memory_usage_without_pyarrow fixture for measuring peak memory usage in debug builds', 'test the test_conftest.py test_memory_usage function which exercises the memory_usage fixture for tracking Python, Polars, and NumPy memory', 'test pl.Schema creation with a dictionary mapping column names to polars dtypes', 'test pl.Schema equality and inequality comparisons for schemas with different column orderings and dtypes', 'test pl.Schema parsing of native Python dtypes like int and datetime into polars types', 'test LazyFrame collect_schema matches computed schema for grouped aggregations and expressions', 'test LazyFrame explode preserves correct schema for nested List and Array dtypes']
```

Usage

```
{'test_fixture_df': 'test the pytest fixture df that returns a polars DataFrame with boolean, integer, float, string, date, datetime, time, and list columns', 'test_fixture_fruits_cars': 'test the pytest fixture fruits_cars that returns a polars DataFrame with integer, fruit, and car columns', 'test_fixture_str_ints_df': 'test the pytest fixture str_ints_df that generates a polars DataFrame with random strings and float values', 'test_fixture_iso8601_formats': 'test the pytest fixtures iso8601_format_datetime, iso8601_tz_aware_format_datetime, and iso8601_format_date that provide ISO8601 format parameterized test data', 'test_memory_usage_class': 'test the MemoryUsage class and memory_usage_without_pyarrow fixture for measuring peak memory usage in debug builds'}
```

## File: pola-rs_polars/py-polars/tests/unit/test_conftest.py

Prompts

```
['test the pytest fixture df that returns a polars DataFrame with boolean, integer, float, string, date, datetime, time, and list columns', 'test the pytest fixture fruits_cars that returns a polars DataFrame with integer, fruit, and car columns', 'test the pytest fixture str_ints_df that generates a polars DataFrame with random strings and float values', 'test the pytest fixtures iso8601_format_datetime, iso8601_tz_aware_format_datetime, and iso8601_format_date that provide ISO8601 format parameterized test data', 'test the MemoryUsage class and memory_usage_without_pyarrow fixture for measuring peak memory usage in debug builds', 'test the test_conftest.py test_memory_usage function which exercises the memory_usage fixture for tracking Python, Polars, and NumPy memory', 'test pl.Schema creation with a dictionary mapping column names to polars dtypes', 'test pl.Schema equality and inequality comparisons for schemas with different column orderings and dtypes', 'test pl.Schema parsing of native Python dtypes like int and datetime into polars types', 'test LazyFrame collect_schema matches computed schema for grouped aggregations and expressions', 'test LazyFrame explode preserves correct schema for nested List and Array dtypes']
```

Usage

```
{'test_memory_usage': 'test the test_conftest.py test_memory_usage function which exercises the memory_usage fixture for tracking Python, Polars, and NumPy memory'}
```

## File: pola-rs_polars/py-polars/tests/unit/test_schema.py

Prompts

```
['test the pytest fixture df that returns a polars DataFrame with boolean, integer, float, string, date, datetime, time, and list columns', 'test the pytest fixture fruits_cars that returns a polars DataFrame with integer, fruit, and car columns', 'test the pytest fixture str_ints_df that generates a polars DataFrame with random strings and float values', 'test the pytest fixtures iso8601_format_datetime, iso8601_tz_aware_format_datetime, and iso8601_format_date that provide ISO8601 format parameterized test data', 'test the MemoryUsage class and memory_usage_without_pyarrow fixture for measuring peak memory usage in debug builds', 'test the test_conftest.py test_memory_usage function which exercises the memory_usage fixture for tracking Python, Polars, and NumPy memory', 'test pl.Schema creation with a dictionary mapping column names to polars dtypes', 'test pl.Schema equality and inequality comparisons for schemas with different column orderings and dtypes', 'test pl.Schema parsing of native Python dtypes like int and datetime into polars types', 'test LazyFrame collect_schema matches computed schema for grouped aggregations and expressions', 'test LazyFrame explode preserves correct schema for nested List and Array dtypes']
```

Usage

```
{'test_pl_Schema_creation': 'test pl.Schema creation with a dictionary mapping column names to polars dtypes', 'test_pl_Schema_equality': 'test pl.Schema equality and inequality comparisons for schemas with different column orderings and dtypes', 'test_pl_Schema_parse_python_dtypes': 'test pl.Schema parsing of native Python dtypes like int and datetime into polars types', 'test_LazyFrame_collect_schema': 'test LazyFrame collect_schema matches computed schema for grouped aggregations and expressions', 'test_LazyFrame_explode_schema': 'test LazyFrame explode preserves correct schema for nested List and Array dtypes'}
```

