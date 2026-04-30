# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/io/spreadsheet/_utils.py

Prompts

```
['create a portable temporary file context manager that handles Windows file deletion safely', 'create an _XLFormatCache object to cache xlsxwriter Format objects per distinct format option set', 'setup an xlsxwriter Workbook and Worksheet from a file path, BytesIO, or existing workbook object', 'setup and unify all column-related formatting, totals, formulas, and sparklines for an Excel table export', 'apply conditional formatting rules to a DataFrame column range in an Excel worksheet', 'parse a table_style dict into a style name and validated table options for xlsxwriter', 'read an Excel spreadsheet file into a Polars DataFrame using the calamine engine', 'read an OpenOffice ODS spreadsheet file into a Polars DataFrame', 'read multiple sheets from an Excel workbook and return a dict mapping sheet names to DataFrames', 'read an Excel file with custom column type overrides and schema inference length', 'read data from multiple Excel workbooks using glob patterns and concatenate results']
```

Usage

```
{'create_PortableTemporaryFile': 'create a portable temporary file context manager that handles Windows file deletion safely'}
```

## File: pola-rs_polars/py-polars/src/polars/io/spreadsheet/_write_utils.py

Prompts

```
['create a portable temporary file context manager that handles Windows file deletion safely', 'create an _XLFormatCache object to cache xlsxwriter Format objects per distinct format option set', 'setup an xlsxwriter Workbook and Worksheet from a file path, BytesIO, or existing workbook object', 'setup and unify all column-related formatting, totals, formulas, and sparklines for an Excel table export', 'apply conditional formatting rules to a DataFrame column range in an Excel worksheet', 'parse a table_style dict into a style name and validated table options for xlsxwriter', 'read an Excel spreadsheet file into a Polars DataFrame using the calamine engine', 'read an OpenOffice ODS spreadsheet file into a Polars DataFrame', 'read multiple sheets from an Excel workbook and return a dict mapping sheet names to DataFrames', 'read an Excel file with custom column type overrides and schema inference length', 'read data from multiple Excel workbooks using glob patterns and concatenate results']
```

Usage

```
{'create_xl_format_cache': 'create an _XLFormatCache object to cache xlsxwriter Format objects per distinct format option set', 'setup_xl_workbook': 'setup an xlsxwriter Workbook and Worksheet from a file path, BytesIO, or existing workbook object', 'setup_xl_table_columns': 'setup and unify all column-related formatting, totals, formulas, and sparklines for an Excel table export', 'apply_xl_conditional_formats': 'apply conditional formatting rules to a DataFrame column range in an Excel worksheet', 'setup_xl_table_options': 'parse a table_style dict into a style name and validated table options for xlsxwriter'}
```

## File: pola-rs_polars/py-polars/src/polars/io/spreadsheet/functions.py

Prompts

```
['create a portable temporary file context manager that handles Windows file deletion safely', 'create an _XLFormatCache object to cache xlsxwriter Format objects per distinct format option set', 'setup an xlsxwriter Workbook and Worksheet from a file path, BytesIO, or existing workbook object', 'setup and unify all column-related formatting, totals, formulas, and sparklines for an Excel table export', 'apply conditional formatting rules to a DataFrame column range in an Excel worksheet', 'parse a table_style dict into a style name and validated table options for xlsxwriter', 'read an Excel spreadsheet file into a Polars DataFrame using the calamine engine', 'read an OpenOffice ODS spreadsheet file into a Polars DataFrame', 'read multiple sheets from an Excel workbook and return a dict mapping sheet names to DataFrames', 'read an Excel file with custom column type overrides and schema inference length', 'read data from multiple Excel workbooks using glob patterns and concatenate results']
```

Usage

```
{'read_excel_spreadsheet': 'read an Excel spreadsheet file into a Polars DataFrame using the calamine engine', 'read_ods_spreadsheet': 'read an OpenOffice ODS spreadsheet file into a Polars DataFrame', 'read_multiple_excel_sheets': 'read multiple sheets from an Excel workbook and return a dict mapping sheet names to DataFrames', 'read_excel_with_schema_overrides': 'read an Excel file with custom column type overrides and schema inference length', 'read_excel_from_multiple_files': 'read data from multiple Excel workbooks using glob patterns and concatenate results'}
```

