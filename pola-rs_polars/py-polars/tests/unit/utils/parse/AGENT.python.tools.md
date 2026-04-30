# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/utils/parse/test_expr.py

Prompts

```
['test parse_into_expression with int, float, Series, date, and bytes inputs to verify they produce literal expressions', 'test parse_into_expression with a string column name to verify it produces a column expression', 'test parse_into_expression with existing Expr objects to verify they pass through unchanged', 'test parse_into_expression with str_as_lit=True to verify strings are treated as literals instead of column names', 'test parse_into_expression with structify=True to verify multiple columns are combined into a struct expression']
```

Usage

```
{'test_parse_into_expression_lit': 'test parse_into_expression with int, float, Series, date, and bytes inputs to verify they produce literal expressions', 'test_parse_into_expression_col': 'test parse_into_expression with a string column name to verify it produces a column expression', 'test_parse_into_expression_expr': 'test parse_into_expression with existing Expr objects to verify they pass through unchanged', 'test_parse_into_expression_str_as_lit': 'test parse_into_expression with str_as_lit=True to verify strings are treated as literals instead of column names', 'test_parse_into_expression_structify': 'test parse_into_expression with structify=True to verify multiple columns are combined into a struct expression'}
```

