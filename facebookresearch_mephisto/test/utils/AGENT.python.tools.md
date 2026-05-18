# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/utils/test_db.py

Prompts

```
['test the mephisto db utility functions for selecting rows, serializing data, and managing database tables', 'test select_rows_by_list_of_field_values to query granted_qualifications by worker and qualification IDs', 'test serialize_data_for_table to convert SQLite datetime fields to ISO format strings for export', 'test delete_entire_exported_data to wipe all database rows except the migrations table', 'test the retry_generate_id decorator that retries DB inserts on unique constraint conflicts', 'test the serialize_date_to_python function with common datetime string formats', 'test parsing ISO 8601 datetime strings like 2002-02-02T02:02:02.000Z', 'test parsing Unix millisecond timestamps into Python datetime objects', 'test that invalid date strings raise a ParserError exception', 'review the serialize_date_to_python function for handling int timestamps and date strings']
```

Usage

```
{'test_db_utils': 'test the mephisto db utility functions for selecting rows, serializing data, and managing database tables', 'test_select_rows_by_field_values': 'test select_rows_by_list_of_field_values to query granted_qualifications by worker and qualification IDs', 'test_serialize_data_for_table': 'test serialize_data_for_table to convert SQLite datetime fields to ISO format strings for export', 'test_delete_exported_data': 'test delete_entire_exported_data to wipe all database rows except the migrations table', 'test_retry_generate_id': 'test the retry_generate_id decorator that retries DB inserts on unique constraint conflicts'}
```

## File: facebookresearch_mephisto/test/utils/test_misc.py

Prompts

```
['test the mephisto db utility functions for selecting rows, serializing data, and managing database tables', 'test select_rows_by_list_of_field_values to query granted_qualifications by worker and qualification IDs', 'test serialize_data_for_table to convert SQLite datetime fields to ISO format strings for export', 'test delete_entire_exported_data to wipe all database rows except the migrations table', 'test the retry_generate_id decorator that retries DB inserts on unique constraint conflicts', 'test the serialize_date_to_python function with common datetime string formats', 'test parsing ISO 8601 datetime strings like 2002-02-02T02:02:02.000Z', 'test parsing Unix millisecond timestamps into Python datetime objects', 'test that invalid date strings raise a ParserError exception', 'review the serialize_date_to_python function for handling int timestamps and date strings']
```

Usage

```
{'test_serialize_date_to_python': 'test the serialize_date_to_python function with common datetime string formats', 'test_date_parsing_iso8601': 'test parsing ISO 8601 datetime strings like 2002-02-02T02:02:02.000Z', 'test_date_parsing_unix_timestamp': 'test parsing Unix millisecond timestamps into Python datetime objects', 'test_date_parsing_invalid': 'test that invalid date strings raise a ParserError exception', 'review_serialize_date_to_python': 'review the serialize_date_to_python function for handling int timestamps and date strings'}
```

