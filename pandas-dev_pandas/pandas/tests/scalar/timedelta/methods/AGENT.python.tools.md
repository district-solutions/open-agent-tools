# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/scalar/timedelta/methods/test_as_unit.py

Prompts

```
['test the Timedelta.as_unit method converts between time units like ns, us, ms, and s', 'test that Timedelta.as_unit raises OutOfBoundsTimedelta when casting to a finer unit would overflow', 'test that Timedelta.as_unit rounds lossily by default and raises ValueError when round_ok=False', 'test that Timedelta.as_unit correctly converts between non-nano units like ms and us', 'test that Timedelta.as_unit preserves components like days, hours, and total_seconds after conversion', 'test the Timedelta.round method with various frequencies including ns, us, ms, s, min, h, and D', 'test the Timedelta.round method raises ValueError for non-fixed frequencies like YE, ME and invalid frequency strings', 'test the Timedelta.min.ceil and Timedelta.max.floor methods for correct boundary behavior and OutOfBoundsTimedelta exceptions', 'test the Timedelta.round, floor, and ceil methods across all supported units with property-based testing via hypothesis', 'test the Timedelta.round, floor, and ceil methods preserve resolution unit when operating on non-nanosecond Timedelta objects']
```

Usage

```
{'test_as_unit': 'test the Timedelta.as_unit method converts between time units like ns, us, ms, and s', 'test_as_unit_overflows': 'test that Timedelta.as_unit raises OutOfBoundsTimedelta when casting to a finer unit would overflow', 'test_as_unit_rounding': 'test that Timedelta.as_unit rounds lossily by default and raises ValueError when round_ok=False', 'test_as_unit_non_nano': 'test that Timedelta.as_unit correctly converts between non-nano units like ms and us', 'test_Timedelta_components': 'test that Timedelta.as_unit preserves components like days, hours, and total_seconds after conversion'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/timedelta/methods/test_round.py

Prompts

```
['test the Timedelta.as_unit method converts between time units like ns, us, ms, and s', 'test that Timedelta.as_unit raises OutOfBoundsTimedelta when casting to a finer unit would overflow', 'test that Timedelta.as_unit rounds lossily by default and raises ValueError when round_ok=False', 'test that Timedelta.as_unit correctly converts between non-nano units like ms and us', 'test that Timedelta.as_unit preserves components like days, hours, and total_seconds after conversion', 'test the Timedelta.round method with various frequencies including ns, us, ms, s, min, h, and D', 'test the Timedelta.round method raises ValueError for non-fixed frequencies like YE, ME and invalid frequency strings', 'test the Timedelta.min.ceil and Timedelta.max.floor methods for correct boundary behavior and OutOfBoundsTimedelta exceptions', 'test the Timedelta.round, floor, and ceil methods across all supported units with property-based testing via hypothesis', 'test the Timedelta.round, floor, and ceil methods preserve resolution unit when operating on non-nanosecond Timedelta objects']
```

Usage

```
{'test_timedelta_round': 'test the Timedelta.round method with various frequencies including ns, us, ms, s, min, h, and D', 'test_timedelta_round_invalid': 'test the Timedelta.round method raises ValueError for non-fixed frequencies like YE, ME and invalid frequency strings', 'test_timedelta_round_implementation_bounds': 'test the Timedelta.min.ceil and Timedelta.max.floor methods for correct boundary behavior and OutOfBoundsTimedelta exceptions', 'test_timedelta_round_sanity': 'test the Timedelta.round, floor, and ceil methods across all supported units with property-based testing via hypothesis', 'test_timedelta_round_non_nano': 'test the Timedelta.round, floor, and ceil methods preserve resolution unit when operating on non-nanosecond Timedelta objects'}
```

