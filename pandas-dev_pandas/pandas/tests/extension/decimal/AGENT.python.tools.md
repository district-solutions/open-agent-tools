# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/extension/decimal/array.py

Prompts

```
['create a custom pandas extension dtype for decimal.Decimal values with configurable precision context', 'build a pandas ExtensionArray that wraps decimal.Decimal values with arithmetic and comparison operations', 'test numpy ufunc dispatch on DecimalArray by verifying __array_ufunc__ handles arithmetic operations', 'test the _reduce method on DecimalArray for operations like sum with skipna and keepdims support', 'review the _cmp_method on DecimalArray that implements element-wise comparison operators', 'test the DecimalArray extension array for pandas with custom decimal dtype support', 'test groupby aggregation on DecimalArray columns preserves decimal dtype in results', 'test numpy ufunc operations on DecimalArray and Series with decimal dtype', 'test arithmetic operators on Series with DecimalArray including division trap handling', 'test fillna behavior on DecimalArray with NaN values and copy keyword warnings']
```

Usage

```
{'create_decimal_dtype': 'create a custom pandas extension dtype for decimal.Decimal values with configurable precision context', 'build_decimal_array': 'build a pandas ExtensionArray that wraps decimal.Decimal values with arithmetic and comparison operations', 'test_decimal_ufunc_dispatch': 'test numpy ufunc dispatch on DecimalArray by verifying __array_ufunc__ handles arithmetic operations', 'test_decimal_reduction': 'test the _reduce method on DecimalArray for operations like sum with skipna and keepdims support', 'review_decimal_comparison': 'review the _cmp_method on DecimalArray that implements element-wise comparison operators'}
```

## File: pandas-dev_pandas/pandas/tests/extension/decimal/test_decimal.py

Prompts

```
['create a custom pandas extension dtype for decimal.Decimal values with configurable precision context', 'build a pandas ExtensionArray that wraps decimal.Decimal values with arithmetic and comparison operations', 'test numpy ufunc dispatch on DecimalArray by verifying __array_ufunc__ handles arithmetic operations', 'test the _reduce method on DecimalArray for operations like sum with skipna and keepdims support', 'review the _cmp_method on DecimalArray that implements element-wise comparison operators', 'test the DecimalArray extension array for pandas with custom decimal dtype support', 'test groupby aggregation on DecimalArray columns preserves decimal dtype in results', 'test numpy ufunc operations on DecimalArray and Series with decimal dtype', 'test arithmetic operators on Series with DecimalArray including division trap handling', 'test fillna behavior on DecimalArray with NaN values and copy keyword warnings']
```

Usage

```
{'test_decimal_extension_array': 'test the DecimalArray extension array for pandas with custom decimal dtype support', 'test_decimal_groupby_agg': 'test groupby aggregation on DecimalArray columns preserves decimal dtype in results', 'test_decimal_ufunc_operations': 'test numpy ufunc operations on DecimalArray and Series with decimal dtype', 'test_decimal_arithmetic_series': 'test arithmetic operators on Series with DecimalArray including division trap handling', 'test_decimal_fillna_behavior': 'test fillna behavior on DecimalArray with NaN values and copy keyword warnings'}
```

