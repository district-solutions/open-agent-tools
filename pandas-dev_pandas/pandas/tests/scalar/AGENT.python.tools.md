# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/scalar/test_na_scalar.py

Prompts

```
['test that NA is a singleton by verifying NA is NA and creating a new instance returns the same object', "test that NA repr, str, format, and f-string formatting all produce '<NA>' with optional width padding", "test that bool(NA) and not NA both raise TypeError with message 'boolean value of NA is ambiguous'", 'test arithmetic operations between NA and various types (int, float, str, bytes, np.nan) return NA or (NA, NA) for divmod', 'test comparison operations between NA and various types (int, float, date, time, NaT, np.nan) all return NA', 'test that NA raised to zero-like values (0, -0, False, np zeros) equals 1 regardless of asarray', 'test that non-zero values raised to NA equal the original value, except negative one which returns NA', 'test unary operations +NA, -NA, abs(NA), ~NA all return NA', 'test logical and (&), or (|), xor (^) operations between NA and booleans follow short-circuit and three-valued logic rules', 'test numpy ufuncs like np.log, np.add, np.divmod, np.frexp applied to NA return NA or (NA, NA) tuples', 'test NaT deprecated dayofweek, dayofyear, and daysinmonth attributes raise Pandas4Warning', "test NaT repr, str, and isoformat methods return 'NaT' string", 'test NaT field operations return nan and boolean operations return False for DatetimeArray, TimedeltaArray, and PeriodArray', 'test accessing date fields on DatetimeIndex and Series.dt accessor returns expected Index and Series', 'test Timestamp, Timedelta, Period constructors with None, nan, iNaT, NaT return NaT singleton', 'test NaT arithmetic operations with scalars return NaT or raise TypeError for invalid operations', 'test NaT methods like astimezone, ctime, strftime raise ValueError', 'test NaT comparison operators with Timedelta, Timestamp, and NaT return False', 'test NaT addition and subtraction with timedelta scalars and offsets returns NaT']
```

Usage

```
{'test_singleton_na': 'test that NA is a singleton by verifying NA is NA and creating a new instance returns the same object', 'test_na_repr_format': "test that NA repr, str, format, and f-string formatting all produce '<NA>' with optional width padding", 'test_na_truthiness_raises': "test that bool(NA) and not NA both raise TypeError with message 'boolean value of NA is ambiguous'", 'test_na_arithmetic_ops': 'test arithmetic operations between NA and various types (int, float, str, bytes, np.nan) return NA or (NA, NA) for divmod', 'test_na_comparison_ops': 'test comparison operations between NA and various types (int, float, date, time, NaT, np.nan) all return NA', 'test_na_pow_special': 'test that NA raised to zero-like values (0, -0, False, np zeros) equals 1 regardless of asarray', 'test_na_rpow_special': 'test that non-zero values raised to NA equal the original value, except negative one which returns NA', 'test_na_unary_ops': 'test unary operations +NA, -NA, abs(NA), ~NA all return NA', 'test_na_logical_and_or_xor': 'test logical and (&), or (|), xor (^) operations between NA and booleans follow short-circuit and three-valued logic rules', 'test_na_ufunc': 'test numpy ufuncs like np.log, np.add, np.divmod, np.frexp applied to NA return NA or (NA, NA) tuples'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/test_nat.py

Prompts

```
['test that NA is a singleton by verifying NA is NA and creating a new instance returns the same object', "test that NA repr, str, format, and f-string formatting all produce '<NA>' with optional width padding", "test that bool(NA) and not NA both raise TypeError with message 'boolean value of NA is ambiguous'", 'test arithmetic operations between NA and various types (int, float, str, bytes, np.nan) return NA or (NA, NA) for divmod', 'test comparison operations between NA and various types (int, float, date, time, NaT, np.nan) all return NA', 'test that NA raised to zero-like values (0, -0, False, np zeros) equals 1 regardless of asarray', 'test that non-zero values raised to NA equal the original value, except negative one which returns NA', 'test unary operations +NA, -NA, abs(NA), ~NA all return NA', 'test logical and (&), or (|), xor (^) operations between NA and booleans follow short-circuit and three-valued logic rules', 'test numpy ufuncs like np.log, np.add, np.divmod, np.frexp applied to NA return NA or (NA, NA) tuples', 'test NaT deprecated dayofweek, dayofyear, and daysinmonth attributes raise Pandas4Warning', "test NaT repr, str, and isoformat methods return 'NaT' string", 'test NaT field operations return nan and boolean operations return False for DatetimeArray, TimedeltaArray, and PeriodArray', 'test accessing date fields on DatetimeIndex and Series.dt accessor returns expected Index and Series', 'test Timestamp, Timedelta, Period constructors with None, nan, iNaT, NaT return NaT singleton', 'test NaT arithmetic operations with scalars return NaT or raise TypeError for invalid operations', 'test NaT methods like astimezone, ctime, strftime raise ValueError', 'test NaT comparison operators with Timedelta, Timestamp, and NaT return False', 'test NaT addition and subtraction with timedelta scalars and offsets returns NaT']
```

Usage

```
{'test_nat_deprecated_day_attrs': 'test NaT deprecated dayofweek, dayofyear, and daysinmonth attributes raise Pandas4Warning', 'test_nat_formatting': "test NaT repr, str, and isoformat methods return 'NaT' string", 'test_nat_fields': 'test NaT field operations return nan and boolean operations return False for DatetimeArray, TimedeltaArray, and PeriodArray', 'test_nat_vector_field_access': 'test accessing date fields on DatetimeIndex and Series.dt accessor returns expected Index and Series', 'test_nat_identity': 'test Timestamp, Timedelta, Period constructors with None, nan, iNaT, NaT return NaT singleton', 'test_nat_arithmetic_scalar': 'test NaT arithmetic operations with scalars return NaT or raise TypeError for invalid operations', 'test_nat_methods_raise': 'test NaT methods like astimezone, ctime, strftime raise ValueError', 'test_nat_comparisons': 'test NaT comparison operators with Timedelta, Timestamp, and NaT return False', 'test_nat_addsub_tdlike_scalar': 'test NaT addition and subtraction with timedelta scalars and offsets returns NaT'}
```

