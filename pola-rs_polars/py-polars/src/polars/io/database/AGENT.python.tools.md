# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/io/database/_cursor_proxies.py

Prompts

```
['create an ODBCCursorProxy with a connection string to query ODBC data sources via arrow-odbc', 'fetch ODBC query results as an iterable of PyArrow RecordBatches with configurable batch size', 'create a SurrealDBCursorProxy wrapping a sync or async SurrealDB client for database queries', 'fetch all SurrealDB query results as a list of dictionaries using the cursor proxy', 'fetch SurrealDB results in batches by calling fetchmany with a size parameter', 'build a ConnectionExecutor to wrap a database connection and enable query execution with Polars DataFrame conversion', 'execute a SQL query using ConnectionExecutor with options and validate that only SELECT queries are used for read operations', 'convert a database query result set to a Polars DataFrame using to_polars with optional batch iteration and schema overrides', 'fetch Arrow-native data from a database cursor using driver-specific properties from the Arrow driver registry', 'fetch database result rows incrementally with batch support as a fallback when Arrow-native fetching is not available', 'build a function to infer Polars dtype from a database type name string like INT2 or NUMERIC(10,2)', 'test inferring Polars dtype from a database cursor description tuple with type_code and metadata', 'create a function that maps integer bit width and signed flag to the matching Polars integer dtype', 'summarize how timeunit_from_precision converts a numeric precision value into a time unit string', 'review the dtype_from_database_typename function that handles floats, integers, decimals, strings, booleans, and temporal types', 'read database results from a SQL query into a Polars DataFrame using a connection object', 'iterate over database query results in batches using read_database with iter_batches and batch_size', 'read database data from an ODBC connection string using the arrow-odbc package', 'read database results in parallel from a URI using connectorx with partition_on and partition_num', 'read database results from a URI using the ADBC engine with parameterized query execution']
```

Usage

```
{'create_odbc_cursor_proxy': 'create an ODBCCursorProxy with a connection string to query ODBC data sources via arrow-odbc', 'fetch_odbc_record_batches': 'fetch ODBC query results as an iterable of PyArrow RecordBatches with configurable batch size', 'create_surrealdb_cursor_proxy': 'create a SurrealDBCursorProxy wrapping a sync or async SurrealDB client for database queries', 'fetch_surrealdb_all_results': 'fetch all SurrealDB query results as a list of dictionaries using the cursor proxy', 'fetch_surrealdb_batch_results': 'fetch SurrealDB results in batches by calling fetchmany with a size parameter'}
```

## File: pola-rs_polars/py-polars/src/polars/io/database/_executor.py

Prompts

```
['create an ODBCCursorProxy with a connection string to query ODBC data sources via arrow-odbc', 'fetch ODBC query results as an iterable of PyArrow RecordBatches with configurable batch size', 'create a SurrealDBCursorProxy wrapping a sync or async SurrealDB client for database queries', 'fetch all SurrealDB query results as a list of dictionaries using the cursor proxy', 'fetch SurrealDB results in batches by calling fetchmany with a size parameter', 'build a ConnectionExecutor to wrap a database connection and enable query execution with Polars DataFrame conversion', 'execute a SQL query using ConnectionExecutor with options and validate that only SELECT queries are used for read operations', 'convert a database query result set to a Polars DataFrame using to_polars with optional batch iteration and schema overrides', 'fetch Arrow-native data from a database cursor using driver-specific properties from the Arrow driver registry', 'fetch database result rows incrementally with batch support as a fallback when Arrow-native fetching is not available', 'build a function to infer Polars dtype from a database type name string like INT2 or NUMERIC(10,2)', 'test inferring Polars dtype from a database cursor description tuple with type_code and metadata', 'create a function that maps integer bit width and signed flag to the matching Polars integer dtype', 'summarize how timeunit_from_precision converts a numeric precision value into a time unit string', 'review the dtype_from_database_typename function that handles floats, integers, decimals, strings, booleans, and temporal types', 'read database results from a SQL query into a Polars DataFrame using a connection object', 'iterate over database query results in batches using read_database with iter_batches and batch_size', 'read database data from an ODBC connection string using the arrow-odbc package', 'read database results in parallel from a URI using connectorx with partition_on and partition_num', 'read database results from a URI using the ADBC engine with parameterized query execution']
```

Usage

```
{'build_query_executor': 'build a ConnectionExecutor to wrap a database connection and enable query execution with Polars DataFrame conversion', 'execute_sql_query': 'execute a SQL query using ConnectionExecutor with options and validate that only SELECT queries are used for read operations', 'convert_result_to_dataframe': 'convert a database query result set to a Polars DataFrame using to_polars with optional batch iteration and schema overrides', 'fetch_arrow_data': 'fetch Arrow-native data from a database cursor using driver-specific properties from the Arrow driver registry', 'fetch_row_data_fallback': 'fetch database result rows incrementally with batch support as a fallback when Arrow-native fetching is not available'}
```

## File: pola-rs_polars/py-polars/src/polars/io/database/_inference.py

Prompts

```
['create an ODBCCursorProxy with a connection string to query ODBC data sources via arrow-odbc', 'fetch ODBC query results as an iterable of PyArrow RecordBatches with configurable batch size', 'create a SurrealDBCursorProxy wrapping a sync or async SurrealDB client for database queries', 'fetch all SurrealDB query results as a list of dictionaries using the cursor proxy', 'fetch SurrealDB results in batches by calling fetchmany with a size parameter', 'build a ConnectionExecutor to wrap a database connection and enable query execution with Polars DataFrame conversion', 'execute a SQL query using ConnectionExecutor with options and validate that only SELECT queries are used for read operations', 'convert a database query result set to a Polars DataFrame using to_polars with optional batch iteration and schema overrides', 'fetch Arrow-native data from a database cursor using driver-specific properties from the Arrow driver registry', 'fetch database result rows incrementally with batch support as a fallback when Arrow-native fetching is not available', 'build a function to infer Polars dtype from a database type name string like INT2 or NUMERIC(10,2)', 'test inferring Polars dtype from a database cursor description tuple with type_code and metadata', 'create a function that maps integer bit width and signed flag to the matching Polars integer dtype', 'summarize how timeunit_from_precision converts a numeric precision value into a time unit string', 'review the dtype_from_database_typename function that handles floats, integers, decimals, strings, booleans, and temporal types', 'read database results from a SQL query into a Polars DataFrame using a connection object', 'iterate over database query results in batches using read_database with iter_batches and batch_size', 'read database data from an ODBC connection string using the arrow-odbc package', 'read database results in parallel from a URI using connectorx with partition_on and partition_num', 'read database results from a URI using the ADBC engine with parameterized query execution']
```

Usage

```
{'build_dtype_from_database_typename': 'build a function to infer Polars dtype from a database type name string like INT2 or NUMERIC(10,2)', 'test_dtype_from_cursor_description': 'test inferring Polars dtype from a database cursor description tuple with type_code and metadata', 'create_integer_dtype_from_nbits': 'create a function that maps integer bit width and signed flag to the matching Polars integer dtype', 'summarize_timeunit_from_precision': 'summarize how timeunit_from_precision converts a numeric precision value into a time unit string', 'review_dtype_from_database_typename': 'review the dtype_from_database_typename function that handles floats, integers, decimals, strings, booleans, and temporal types'}
```

## File: pola-rs_polars/py-polars/src/polars/io/database/functions.py

Prompts

```
['create an ODBCCursorProxy with a connection string to query ODBC data sources via arrow-odbc', 'fetch ODBC query results as an iterable of PyArrow RecordBatches with configurable batch size', 'create a SurrealDBCursorProxy wrapping a sync or async SurrealDB client for database queries', 'fetch all SurrealDB query results as a list of dictionaries using the cursor proxy', 'fetch SurrealDB results in batches by calling fetchmany with a size parameter', 'build a ConnectionExecutor to wrap a database connection and enable query execution with Polars DataFrame conversion', 'execute a SQL query using ConnectionExecutor with options and validate that only SELECT queries are used for read operations', 'convert a database query result set to a Polars DataFrame using to_polars with optional batch iteration and schema overrides', 'fetch Arrow-native data from a database cursor using driver-specific properties from the Arrow driver registry', 'fetch database result rows incrementally with batch support as a fallback when Arrow-native fetching is not available', 'build a function to infer Polars dtype from a database type name string like INT2 or NUMERIC(10,2)', 'test inferring Polars dtype from a database cursor description tuple with type_code and metadata', 'create a function that maps integer bit width and signed flag to the matching Polars integer dtype', 'summarize how timeunit_from_precision converts a numeric precision value into a time unit string', 'review the dtype_from_database_typename function that handles floats, integers, decimals, strings, booleans, and temporal types', 'read database results from a SQL query into a Polars DataFrame using a connection object', 'iterate over database query results in batches using read_database with iter_batches and batch_size', 'read database data from an ODBC connection string using the arrow-odbc package', 'read database results in parallel from a URI using connectorx with partition_on and partition_num', 'read database results from a URI using the ADBC engine with parameterized query execution']
```

Usage

```
{'read_database_load_query': 'read database results from a SQL query into a Polars DataFrame using a connection object', 'read_database_batch_iter': 'iterate over database query results in batches using read_database with iter_batches and batch_size', 'read_database_odbc_connect': 'read database data from an ODBC connection string using the arrow-odbc package', 'read_database_uri_parallel': 'read database results in parallel from a URI using connectorx with partition_on and partition_num', 'read_database_uri_adbc': 'read database results from a URI using the ADBC engine with parameterized query execution'}
```

