# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/scalar/timedelta/test_arithmetic.py

Prompts

```
['test scalar Timedelta addition and subtraction with datetime, Timestamp, timedelta, and timedelta64 operands', 'test scalar Timedelta multiplication and division with numeric scalars, NaT, offsets, and timedelta64 arrays', 'test scalar Timedelta modulo and divmod operations with timedeltalike scalars, numeric scalars, and offsets', 'test scalar Timedelta comparison operators with pytimedelta bounds, tick offsets, and object arrays', 'test scalar Timedelta multiplication by numeric scalars, arrays, and NaN producing Timedelta or NaT results', 'test constructing a Timedelta from keyword arguments like nanoseconds, microseconds, and days', 'test the Timedelta unit keyword to control resolution for s, ms, us, and ns units', 'test parsing Timedelta from string representations including ISO 8601 duration format', 'test Timedelta construction raises OutOfBoundsTimedelta for out-of-range values', 'test constructing Timedelta from numpy integer and float dtypes', 'test the Timedelta repr method returns correct string representation for various units', 'test the Timedelta isoformat method returns correct ISO 8601 duration strings', 'test the Timedelta _repr_base method with default format for various durations', 'test the Timedelta _repr_base method with sub_day format for various durations', 'test the Timedelta _repr_base method with long format for various durations', 'test the Timedelta _repr_base method with all format including nanoseconds', 'test the TestNonNano class for Timedelta operations with non-nanosecond resolution units', 'test the TestTimedeltaUnaryOps class for unary operations like negation, absolute value, and invert on Timedelta', 'test the TestTimedeltas class for Timedelta conversions between pandas, numpy, and Python timedelta types', 'test Timedelta true division and floor division with timedeltalike and numeric operands', 'test the boolean truthiness of Timedelta scalar values including NaT and zero']
```

Usage

```
{'test_timedelta_addition_subtraction': 'test scalar Timedelta addition and subtraction with datetime, Timestamp, timedelta, and timedelta64 operands', 'test_timedelta_multiplication_division': 'test scalar Timedelta multiplication and division with numeric scalars, NaT, offsets, and timedelta64 arrays', 'test_timedelta_modulo_divmod': 'test scalar Timedelta modulo and divmod operations with timedeltalike scalars, numeric scalars, and offsets', 'test_timedelta_comparison': 'test scalar Timedelta comparison operators with pytimedelta bounds, tick offsets, and object arrays', 'test_timedelta_multiplication_by_numeric': 'test scalar Timedelta multiplication by numeric scalars, arrays, and NaN producing Timedelta or NaT results'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/timedelta/test_constructors.py

Prompts

```
['test scalar Timedelta addition and subtraction with datetime, Timestamp, timedelta, and timedelta64 operands', 'test scalar Timedelta multiplication and division with numeric scalars, NaT, offsets, and timedelta64 arrays', 'test scalar Timedelta modulo and divmod operations with timedeltalike scalars, numeric scalars, and offsets', 'test scalar Timedelta comparison operators with pytimedelta bounds, tick offsets, and object arrays', 'test scalar Timedelta multiplication by numeric scalars, arrays, and NaN producing Timedelta or NaT results', 'test constructing a Timedelta from keyword arguments like nanoseconds, microseconds, and days', 'test the Timedelta unit keyword to control resolution for s, ms, us, and ns units', 'test parsing Timedelta from string representations including ISO 8601 duration format', 'test Timedelta construction raises OutOfBoundsTimedelta for out-of-range values', 'test constructing Timedelta from numpy integer and float dtypes', 'test the Timedelta repr method returns correct string representation for various units', 'test the Timedelta isoformat method returns correct ISO 8601 duration strings', 'test the Timedelta _repr_base method with default format for various durations', 'test the Timedelta _repr_base method with sub_day format for various durations', 'test the Timedelta _repr_base method with long format for various durations', 'test the Timedelta _repr_base method with all format including nanoseconds', 'test the TestNonNano class for Timedelta operations with non-nanosecond resolution units', 'test the TestTimedeltaUnaryOps class for unary operations like negation, absolute value, and invert on Timedelta', 'test the TestTimedeltas class for Timedelta conversions between pandas, numpy, and Python timedelta types', 'test Timedelta true division and floor division with timedeltalike and numeric operands', 'test the boolean truthiness of Timedelta scalar values including NaT and zero']
```

Usage

```
{'test_timedelta_keyword_construction': 'test constructing a Timedelta from keyword arguments like nanoseconds, microseconds, and days', 'test_timedelta_unit_keyword': 'test the Timedelta unit keyword to control resolution for s, ms, us, and ns units', 'test_timedelta_string_parsing': 'test parsing Timedelta from string representations including ISO 8601 duration format', 'test_timedelta_overflow_handling': 'test Timedelta construction raises OutOfBoundsTimedelta for out-of-range values', 'test_timedelta_np_dtypes': 'test constructing Timedelta from numpy integer and float dtypes'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/timedelta/test_formats.py

Prompts

```
['test scalar Timedelta addition and subtraction with datetime, Timestamp, timedelta, and timedelta64 operands', 'test scalar Timedelta multiplication and division with numeric scalars, NaT, offsets, and timedelta64 arrays', 'test scalar Timedelta modulo and divmod operations with timedeltalike scalars, numeric scalars, and offsets', 'test scalar Timedelta comparison operators with pytimedelta bounds, tick offsets, and object arrays', 'test scalar Timedelta multiplication by numeric scalars, arrays, and NaN producing Timedelta or NaT results', 'test constructing a Timedelta from keyword arguments like nanoseconds, microseconds, and days', 'test the Timedelta unit keyword to control resolution for s, ms, us, and ns units', 'test parsing Timedelta from string representations including ISO 8601 duration format', 'test Timedelta construction raises OutOfBoundsTimedelta for out-of-range values', 'test constructing Timedelta from numpy integer and float dtypes', 'test the Timedelta repr method returns correct string representation for various units', 'test the Timedelta isoformat method returns correct ISO 8601 duration strings', 'test the Timedelta _repr_base method with default format for various durations', 'test the Timedelta _repr_base method with sub_day format for various durations', 'test the Timedelta _repr_base method with long format for various durations', 'test the Timedelta _repr_base method with all format including nanoseconds', 'test the TestNonNano class for Timedelta operations with non-nanosecond resolution units', 'test the TestTimedeltaUnaryOps class for unary operations like negation, absolute value, and invert on Timedelta', 'test the TestTimedeltas class for Timedelta conversions between pandas, numpy, and Python timedelta types', 'test Timedelta true division and floor division with timedeltalike and numeric operands', 'test the boolean truthiness of Timedelta scalar values including NaT and zero']
```

Usage

```
{'test_Timedelta_repr': 'test the Timedelta repr method returns correct string representation for various units', 'test_Timedelta_isoformat': 'test the Timedelta isoformat method returns correct ISO 8601 duration strings', 'test_Timedelta__repr_base_none': 'test the Timedelta _repr_base method with default format for various durations', 'test_Timedelta__repr_base_sub_day': 'test the Timedelta _repr_base method with sub_day format for various durations', 'test_Timedelta__repr_base_long': 'test the Timedelta _repr_base method with long format for various durations', 'test_Timedelta__repr_base_all': 'test the Timedelta _repr_base method with all format including nanoseconds'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/timedelta/test_timedelta.py

Prompts

```
['test scalar Timedelta addition and subtraction with datetime, Timestamp, timedelta, and timedelta64 operands', 'test scalar Timedelta multiplication and division with numeric scalars, NaT, offsets, and timedelta64 arrays', 'test scalar Timedelta modulo and divmod operations with timedeltalike scalars, numeric scalars, and offsets', 'test scalar Timedelta comparison operators with pytimedelta bounds, tick offsets, and object arrays', 'test scalar Timedelta multiplication by numeric scalars, arrays, and NaN producing Timedelta or NaT results', 'test constructing a Timedelta from keyword arguments like nanoseconds, microseconds, and days', 'test the Timedelta unit keyword to control resolution for s, ms, us, and ns units', 'test parsing Timedelta from string representations including ISO 8601 duration format', 'test Timedelta construction raises OutOfBoundsTimedelta for out-of-range values', 'test constructing Timedelta from numpy integer and float dtypes', 'test the Timedelta repr method returns correct string representation for various units', 'test the Timedelta isoformat method returns correct ISO 8601 duration strings', 'test the Timedelta _repr_base method with default format for various durations', 'test the Timedelta _repr_base method with sub_day format for various durations', 'test the Timedelta _repr_base method with long format for various durations', 'test the Timedelta _repr_base method with all format including nanoseconds', 'test the TestNonNano class for Timedelta operations with non-nanosecond resolution units', 'test the TestTimedeltaUnaryOps class for unary operations like negation, absolute value, and invert on Timedelta', 'test the TestTimedeltas class for Timedelta conversions between pandas, numpy, and Python timedelta types', 'test Timedelta true division and floor division with timedeltalike and numeric operands', 'test the boolean truthiness of Timedelta scalar values including NaT and zero']
```

Usage

```
{'test_timedelta_non_nano_operations': 'test the TestNonNano class for Timedelta operations with non-nanosecond resolution units', 'test_timedelta_unary_ops': 'test the TestTimedeltaUnaryOps class for unary operations like negation, absolute value, and invert on Timedelta', 'test_timedelta_conversions': 'test the TestTimedeltas class for Timedelta conversions between pandas, numpy, and Python timedelta types', 'test_timedelta_truediv_floordiv': 'test Timedelta true division and floor division with timedeltalike and numeric operands', 'test_timedelta_truthiness': 'test the boolean truthiness of Timedelta scalar values including NaT and zero'}
```

