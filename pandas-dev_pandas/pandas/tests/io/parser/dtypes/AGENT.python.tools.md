# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/io/parser/dtypes/test_categorical.py

Prompts

```
["test read_csv with dtype='category' parses all columns as categorical", 'test read_csv with dict dtype specifying a single column as categorical', "test read_csv with dtype='category' preserves unsorted category order", "test read_csv with dtype='category' handles missing values in categorical columns", "test read_csv with dtype='category' handles high cardinality numeric data", 'test read_csv with CategoricalDtype specifying custom categories and ordered flag', 'test read_csv with CategoricalDtype coerces numeric string values to categorical', 'test read_csv with CategoricalDtype coerces datetime string values to categorical', 'test read_csv with CategoricalDtype coerces timedelta string values to categorical', 'test read_csv with CategoricalDtype coerces boolean string values to categorical', 'test specifying a single dtype for all columns when reading a CSV file with pandas read_csv', 'test specifying per-column dtypes as a dictionary when reading a CSV file with pandas read_csv', 'test that read_csv raises TypeError when an invalid dtype string is specified in a per-column dtype dictionary', 'test that read_csv raises ValueError when an integer dtype is used with NA values in the column', 'test using a collections.defaultdict as a dtype specification for read_csv with default and per-column values', "test reading a CSV with dtype_backend='numpy_nullable' to get nullable integer, float, boolean, and string dtypes", 'test string column inference behavior when reading a CSV file with pandas read_csv', 'test read_csv with dtype=str on an empty CSV header-only file returns an empty DataFrame with string dtype', 'test read_csv with a dtype dict specifying column name to numpy dtype on an empty CSV body', 'test read_csv with index_col and dtype dict on an empty CSV body with a specified index column', 'test read_csv with multi-column index_col and dtype dict on an empty CSV body', 'test read_csv with various dtype specifications including category, datetime64, timedelta64, and per-column numpy dtypes on empty CSV']
```

Usage

```
{'test_categorical_dtype': "test read_csv with dtype='category' parses all columns as categorical", 'test_categorical_dtype_single': 'test read_csv with dict dtype specifying a single column as categorical', 'test_categorical_dtype_unsorted': "test read_csv with dtype='category' preserves unsorted category order", 'test_categorical_dtype_missing': "test read_csv with dtype='category' handles missing values in categorical columns", 'test_categorical_dtype_high_cardinality_numeric': "test read_csv with dtype='category' handles high cardinality numeric data", 'test_categorical_category_dtype': 'test read_csv with CategoricalDtype specifying custom categories and ordered flag', 'test_categorical_coerces_numeric': 'test read_csv with CategoricalDtype coerces numeric string values to categorical', 'test_categorical_coerces_datetime': 'test read_csv with CategoricalDtype coerces datetime string values to categorical', 'test_categorical_coerces_timedelta': 'test read_csv with CategoricalDtype coerces timedelta string values to categorical', 'test_categorical_dtype_coerces_boolean': 'test read_csv with CategoricalDtype coerces boolean string values to categorical'}
```

## File: pandas-dev_pandas/pandas/tests/io/parser/dtypes/test_dtypes_basic.py

Prompts

```
["test read_csv with dtype='category' parses all columns as categorical", 'test read_csv with dict dtype specifying a single column as categorical', "test read_csv with dtype='category' preserves unsorted category order", "test read_csv with dtype='category' handles missing values in categorical columns", "test read_csv with dtype='category' handles high cardinality numeric data", 'test read_csv with CategoricalDtype specifying custom categories and ordered flag', 'test read_csv with CategoricalDtype coerces numeric string values to categorical', 'test read_csv with CategoricalDtype coerces datetime string values to categorical', 'test read_csv with CategoricalDtype coerces timedelta string values to categorical', 'test read_csv with CategoricalDtype coerces boolean string values to categorical', 'test specifying a single dtype for all columns when reading a CSV file with pandas read_csv', 'test specifying per-column dtypes as a dictionary when reading a CSV file with pandas read_csv', 'test that read_csv raises TypeError when an invalid dtype string is specified in a per-column dtype dictionary', 'test that read_csv raises ValueError when an integer dtype is used with NA values in the column', 'test using a collections.defaultdict as a dtype specification for read_csv with default and per-column values', "test reading a CSV with dtype_backend='numpy_nullable' to get nullable integer, float, boolean, and string dtypes", 'test string column inference behavior when reading a CSV file with pandas read_csv', 'test read_csv with dtype=str on an empty CSV header-only file returns an empty DataFrame with string dtype', 'test read_csv with a dtype dict specifying column name to numpy dtype on an empty CSV body', 'test read_csv with index_col and dtype dict on an empty CSV body with a specified index column', 'test read_csv with multi-column index_col and dtype dict on an empty CSV body', 'test read_csv with various dtype specifications including category, datetime64, timedelta64, and per-column numpy dtypes on empty CSV']
```

Usage

```
{'test_dtype_all_columns': 'test specifying a single dtype for all columns when reading a CSV file with pandas read_csv', 'test_dtype_per_column': 'test specifying per-column dtypes as a dictionary when reading a CSV file with pandas read_csv', 'test_invalid_dtype_per_column': 'test that read_csv raises TypeError when an invalid dtype string is specified in a per-column dtype dictionary', 'test_raise_on_passed_int_dtype_with_nas': 'test that read_csv raises ValueError when an integer dtype is used with NA values in the column', 'test_dtypes_defaultdict': 'test using a collections.defaultdict as a dtype specification for read_csv with default and per-column values', 'test_dtype_backend': "test reading a CSV with dtype_backend='numpy_nullable' to get nullable integer, float, boolean, and string dtypes", 'test_string_inference': 'test string column inference behavior when reading a CSV file with pandas read_csv'}
```

## File: pandas-dev_pandas/pandas/tests/io/parser/dtypes/test_empty.py

Prompts

```
["test read_csv with dtype='category' parses all columns as categorical", 'test read_csv with dict dtype specifying a single column as categorical', "test read_csv with dtype='category' preserves unsorted category order", "test read_csv with dtype='category' handles missing values in categorical columns", "test read_csv with dtype='category' handles high cardinality numeric data", 'test read_csv with CategoricalDtype specifying custom categories and ordered flag', 'test read_csv with CategoricalDtype coerces numeric string values to categorical', 'test read_csv with CategoricalDtype coerces datetime string values to categorical', 'test read_csv with CategoricalDtype coerces timedelta string values to categorical', 'test read_csv with CategoricalDtype coerces boolean string values to categorical', 'test specifying a single dtype for all columns when reading a CSV file with pandas read_csv', 'test specifying per-column dtypes as a dictionary when reading a CSV file with pandas read_csv', 'test that read_csv raises TypeError when an invalid dtype string is specified in a per-column dtype dictionary', 'test that read_csv raises ValueError when an integer dtype is used with NA values in the column', 'test using a collections.defaultdict as a dtype specification for read_csv with default and per-column values', "test reading a CSV with dtype_backend='numpy_nullable' to get nullable integer, float, boolean, and string dtypes", 'test string column inference behavior when reading a CSV file with pandas read_csv', 'test read_csv with dtype=str on an empty CSV header-only file returns an empty DataFrame with string dtype', 'test read_csv with a dtype dict specifying column name to numpy dtype on an empty CSV body', 'test read_csv with index_col and dtype dict on an empty CSV body with a specified index column', 'test read_csv with multi-column index_col and dtype dict on an empty CSV body', 'test read_csv with various dtype specifications including category, datetime64, timedelta64, and per-column numpy dtypes on empty CSV']
```

Usage

```
{'test_dtype_all_columns_empty': 'test read_csv with dtype=str on an empty CSV header-only file returns an empty DataFrame with string dtype', 'test_empty_pass_dtype': 'test read_csv with a dtype dict specifying column name to numpy dtype on an empty CSV body', 'test_empty_with_index_pass_dtype': 'test read_csv with index_col and dtype dict on an empty CSV body with a specified index column', 'test_empty_with_multi_index_pass_dtype': 'test read_csv with multi-column index_col and dtype dict on an empty CSV body', 'test_empty_dtype': 'test read_csv with various dtype specifications including category, datetime64, timedelta64, and per-column numpy dtypes on empty CSV'}
```

