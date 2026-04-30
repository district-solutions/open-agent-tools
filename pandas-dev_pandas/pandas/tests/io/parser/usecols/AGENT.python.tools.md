# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/io/parser/usecols/test_parse_dates.py

Prompts

```
['test read_csv with usecols and parse_dates to parse date column as index from CSV data', 'test read_csv with usecols and parse_dates to parse date column while selecting all columns from CSV data', 'test read_csv with parse_dates and index_col to set parsed date column as DataFrame index', 'test read_csv with parse_dates and header=None to parse dates from unnamed columns', 'test read_csv with pyarrow engine requires string column names instead of integer positions for usecols', 'test selecting columns by integer indices or string names with read_csv usecols parameter', 'test using usecols with custom column names and header row in read_csv', 'test filtering columns with a callable function passed to read_csv usecols parameter', 'test combining usecols with index_col to set index from selected columns in read_csv', 'test raising error when usecols column names do not match actual CSV columns in read_csv']
```

Usage

```
{'test_usecols_with_parse_dates2': 'test read_csv with usecols and parse_dates to parse date column as index from CSV data', 'test_usecols_with_parse_dates3': 'test read_csv with usecols and parse_dates to parse date column while selecting all columns from CSV data', 'test_parse_dates_with_index_col': 'test read_csv with parse_dates and index_col to set parsed date column as DataFrame index', 'test_parse_dates_with_header_none': 'test read_csv with parse_dates and header=None to parse dates from unnamed columns', 'test_pyarrow_usecols_with_names': 'test read_csv with pyarrow engine requires string column names instead of integer positions for usecols'}
```

## File: pandas-dev_pandas/pandas/tests/io/parser/usecols/test_usecols_basic.py

Prompts

```
['test read_csv with usecols and parse_dates to parse date column as index from CSV data', 'test read_csv with usecols and parse_dates to parse date column while selecting all columns from CSV data', 'test read_csv with parse_dates and index_col to set parsed date column as DataFrame index', 'test read_csv with parse_dates and header=None to parse dates from unnamed columns', 'test read_csv with pyarrow engine requires string column names instead of integer positions for usecols', 'test selecting columns by integer indices or string names with read_csv usecols parameter', 'test using usecols with custom column names and header row in read_csv', 'test filtering columns with a callable function passed to read_csv usecols parameter', 'test combining usecols with index_col to set index from selected columns in read_csv', 'test raising error when usecols column names do not match actual CSV columns in read_csv']
```

Usage

```
{'test_usecols_column_selection': 'test selecting columns by integer indices or string names with read_csv usecols parameter', 'test_usecols_with_custom_names': 'test using usecols with custom column names and header row in read_csv', 'test_usecols_callable_filter': 'test filtering columns with a callable function passed to read_csv usecols parameter', 'test_usecols_index_col_conflict': 'test combining usecols with index_col to set index from selected columns in read_csv', 'test_usecols_names_mismatch_error': 'test raising error when usecols column names do not match actual CSV columns in read_csv'}
```

