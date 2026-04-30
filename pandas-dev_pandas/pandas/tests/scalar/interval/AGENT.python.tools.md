# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/scalar/interval/test_arithmetic.py

Prompts

```
['test the Interval class arithmetic addition with numeric scalars and in-place operators', 'test the Interval class arithmetic subtraction with numeric scalars and in-place operators', 'test the Interval class arithmetic multiplication with numeric scalars and in-place operators', 'test the Interval class arithmetic division with numeric scalars and in-place operators', 'test the Interval class floor division arithmetic with numeric scalars and in-place operators', 'test Interval constructor with numeric left and right endpoints', 'test Interval constructor raises ValueError when given string endpoints', 'test Interval constructor raises ValueError when given invalid closed option', 'test Interval constructor raises ValueError when left endpoint is greater than right endpoint', 'test Interval constructor raises error when Timestamp endpoints have mismatched timezones', 'create an Interval and test scalar containment with closed endpoints', 'test Interval containment where one Interval is checked inside another', 'test Interval containment with infinite-length bounds using float inf', 'test Interval containment with zero-length degenerate intervals', 'test Interval containment across int, Timestamp, and Timedelta types', 'test the pandas Interval repr and str formatting for right-closed and left-closed intervals', 'test the pandas Interval class properties including closed, left, right, and mid attributes', 'test that hashing a pandas Interval instance does not raise an exception', 'test the Interval.length property with numeric, timedelta, and infinity endpoints', 'test Interval.length with Timestamp endpoints across multiple timezones', 'test Interval.is_empty with different left/right endpoints and closed parameter values', 'test that an Interval overlaps with itself for all closed parameter combinations', 'test that a nested Interval always overlaps with its parent Interval', 'test that two disjoint Intervals never overlap regardless of closed parameters', 'test that two Intervals sharing an endpoint overlap only when both endpoints are closed', 'test that calling overlaps with a non-Interval argument raises TypeError']
```

Usage

```
{'test_interval_addition': 'test the Interval class arithmetic addition with numeric scalars and in-place operators', 'test_interval_subtraction': 'test the Interval class arithmetic subtraction with numeric scalars and in-place operators', 'test_interval_multiplication': 'test the Interval class arithmetic multiplication with numeric scalars and in-place operators', 'test_interval_division': 'test the Interval class arithmetic division with numeric scalars and in-place operators', 'test_interval_floordivision': 'test the Interval class floor division arithmetic with numeric scalars and in-place operators'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/interval/test_constructors.py

Prompts

```
['test the Interval class arithmetic addition with numeric scalars and in-place operators', 'test the Interval class arithmetic subtraction with numeric scalars and in-place operators', 'test the Interval class arithmetic multiplication with numeric scalars and in-place operators', 'test the Interval class arithmetic division with numeric scalars and in-place operators', 'test the Interval class floor division arithmetic with numeric scalars and in-place operators', 'test Interval constructor with numeric left and right endpoints', 'test Interval constructor raises ValueError when given string endpoints', 'test Interval constructor raises ValueError when given invalid closed option', 'test Interval constructor raises ValueError when left endpoint is greater than right endpoint', 'test Interval constructor raises error when Timestamp endpoints have mismatched timezones', 'create an Interval and test scalar containment with closed endpoints', 'test Interval containment where one Interval is checked inside another', 'test Interval containment with infinite-length bounds using float inf', 'test Interval containment with zero-length degenerate intervals', 'test Interval containment across int, Timestamp, and Timedelta types', 'test the pandas Interval repr and str formatting for right-closed and left-closed intervals', 'test the pandas Interval class properties including closed, left, right, and mid attributes', 'test that hashing a pandas Interval instance does not raise an exception', 'test the Interval.length property with numeric, timedelta, and infinity endpoints', 'test Interval.length with Timestamp endpoints across multiple timezones', 'test Interval.is_empty with different left/right endpoints and closed parameter values', 'test that an Interval overlaps with itself for all closed parameter combinations', 'test that a nested Interval always overlaps with its parent Interval', 'test that two disjoint Intervals never overlap regardless of closed parameters', 'test that two Intervals sharing an endpoint overlap only when both endpoints are closed', 'test that calling overlaps with a non-Interval argument raises TypeError']
```

Usage

```
{'test_interval_constructor_numeric': 'test Interval constructor with numeric left and right endpoints', 'test_interval_constructor_string_errors': 'test Interval constructor raises ValueError when given string endpoints', 'test_interval_constructor_closed_invalid': 'test Interval constructor raises ValueError when given invalid closed option', 'test_interval_constructor_reversed_bounds': 'test Interval constructor raises ValueError when left endpoint is greater than right endpoint', 'test_interval_constructor_timezone_mismatch': 'test Interval constructor raises error when Timestamp endpoints have mismatched timezones'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/interval/test_contains.py

Prompts

```
['test the Interval class arithmetic addition with numeric scalars and in-place operators', 'test the Interval class arithmetic subtraction with numeric scalars and in-place operators', 'test the Interval class arithmetic multiplication with numeric scalars and in-place operators', 'test the Interval class arithmetic division with numeric scalars and in-place operators', 'test the Interval class floor division arithmetic with numeric scalars and in-place operators', 'test Interval constructor with numeric left and right endpoints', 'test Interval constructor raises ValueError when given string endpoints', 'test Interval constructor raises ValueError when given invalid closed option', 'test Interval constructor raises ValueError when left endpoint is greater than right endpoint', 'test Interval constructor raises error when Timestamp endpoints have mismatched timezones', 'create an Interval and test scalar containment with closed endpoints', 'test Interval containment where one Interval is checked inside another', 'test Interval containment with infinite-length bounds using float inf', 'test Interval containment with zero-length degenerate intervals', 'test Interval containment across int, Timestamp, and Timedelta types', 'test the pandas Interval repr and str formatting for right-closed and left-closed intervals', 'test the pandas Interval class properties including closed, left, right, and mid attributes', 'test that hashing a pandas Interval instance does not raise an exception', 'test the Interval.length property with numeric, timedelta, and infinity endpoints', 'test Interval.length with Timestamp endpoints across multiple timezones', 'test Interval.is_empty with different left/right endpoints and closed parameter values', 'test that an Interval overlaps with itself for all closed parameter combinations', 'test that a nested Interval always overlaps with its parent Interval', 'test that two disjoint Intervals never overlap regardless of closed parameters', 'test that two Intervals sharing an endpoint overlap only when both endpoints are closed', 'test that calling overlaps with a non-Interval argument raises TypeError']
```

Usage

```
{'create_interval_contains_scalar': 'create an Interval and test scalar containment with closed endpoints', 'test_interval_contains_interval': 'test Interval containment where one Interval is checked inside another', 'test_interval_contains_infinite': 'test Interval containment with infinite-length bounds using float inf', 'test_interval_contains_zero_length': 'test Interval containment with zero-length degenerate intervals', 'test_interval_contains_mixed_types': 'test Interval containment across int, Timestamp, and Timedelta types'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/interval/test_formats.py

Prompts

```
['test the Interval class arithmetic addition with numeric scalars and in-place operators', 'test the Interval class arithmetic subtraction with numeric scalars and in-place operators', 'test the Interval class arithmetic multiplication with numeric scalars and in-place operators', 'test the Interval class arithmetic division with numeric scalars and in-place operators', 'test the Interval class floor division arithmetic with numeric scalars and in-place operators', 'test Interval constructor with numeric left and right endpoints', 'test Interval constructor raises ValueError when given string endpoints', 'test Interval constructor raises ValueError when given invalid closed option', 'test Interval constructor raises ValueError when left endpoint is greater than right endpoint', 'test Interval constructor raises error when Timestamp endpoints have mismatched timezones', 'create an Interval and test scalar containment with closed endpoints', 'test Interval containment where one Interval is checked inside another', 'test Interval containment with infinite-length bounds using float inf', 'test Interval containment with zero-length degenerate intervals', 'test Interval containment across int, Timestamp, and Timedelta types', 'test the pandas Interval repr and str formatting for right-closed and left-closed intervals', 'test the pandas Interval class properties including closed, left, right, and mid attributes', 'test that hashing a pandas Interval instance does not raise an exception', 'test the Interval.length property with numeric, timedelta, and infinity endpoints', 'test Interval.length with Timestamp endpoints across multiple timezones', 'test Interval.is_empty with different left/right endpoints and closed parameter values', 'test that an Interval overlaps with itself for all closed parameter combinations', 'test that a nested Interval always overlaps with its parent Interval', 'test that two disjoint Intervals never overlap regardless of closed parameters', 'test that two Intervals sharing an endpoint overlap only when both endpoints are closed', 'test that calling overlaps with a non-Interval argument raises TypeError']
```

Usage

```
{'test_interval_repr': 'test the pandas Interval repr and str formatting for right-closed and left-closed intervals'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/interval/test_interval.py

Prompts

```
['test the Interval class arithmetic addition with numeric scalars and in-place operators', 'test the Interval class arithmetic subtraction with numeric scalars and in-place operators', 'test the Interval class arithmetic multiplication with numeric scalars and in-place operators', 'test the Interval class arithmetic division with numeric scalars and in-place operators', 'test the Interval class floor division arithmetic with numeric scalars and in-place operators', 'test Interval constructor with numeric left and right endpoints', 'test Interval constructor raises ValueError when given string endpoints', 'test Interval constructor raises ValueError when given invalid closed option', 'test Interval constructor raises ValueError when left endpoint is greater than right endpoint', 'test Interval constructor raises error when Timestamp endpoints have mismatched timezones', 'create an Interval and test scalar containment with closed endpoints', 'test Interval containment where one Interval is checked inside another', 'test Interval containment with infinite-length bounds using float inf', 'test Interval containment with zero-length degenerate intervals', 'test Interval containment across int, Timestamp, and Timedelta types', 'test the pandas Interval repr and str formatting for right-closed and left-closed intervals', 'test the pandas Interval class properties including closed, left, right, and mid attributes', 'test that hashing a pandas Interval instance does not raise an exception', 'test the Interval.length property with numeric, timedelta, and infinity endpoints', 'test Interval.length with Timestamp endpoints across multiple timezones', 'test Interval.is_empty with different left/right endpoints and closed parameter values', 'test that an Interval overlaps with itself for all closed parameter combinations', 'test that a nested Interval always overlaps with its parent Interval', 'test that two disjoint Intervals never overlap regardless of closed parameters', 'test that two Intervals sharing an endpoint overlap only when both endpoints are closed', 'test that calling overlaps with a non-Interval argument raises TypeError']
```

Usage

```
{'test_interval_properties': 'test the pandas Interval class properties including closed, left, right, and mid attributes', 'test_interval_hash': 'test that hashing a pandas Interval instance does not raise an exception', 'test_interval_length': 'test the Interval.length property with numeric, timedelta, and infinity endpoints', 'test_interval_length_timestamp': 'test Interval.length with Timestamp endpoints across multiple timezones', 'test_interval_is_empty': 'test Interval.is_empty with different left/right endpoints and closed parameter values'}
```

## File: pandas-dev_pandas/pandas/tests/scalar/interval/test_overlaps.py

Prompts

```
['test the Interval class arithmetic addition with numeric scalars and in-place operators', 'test the Interval class arithmetic subtraction with numeric scalars and in-place operators', 'test the Interval class arithmetic multiplication with numeric scalars and in-place operators', 'test the Interval class arithmetic division with numeric scalars and in-place operators', 'test the Interval class floor division arithmetic with numeric scalars and in-place operators', 'test Interval constructor with numeric left and right endpoints', 'test Interval constructor raises ValueError when given string endpoints', 'test Interval constructor raises ValueError when given invalid closed option', 'test Interval constructor raises ValueError when left endpoint is greater than right endpoint', 'test Interval constructor raises error when Timestamp endpoints have mismatched timezones', 'create an Interval and test scalar containment with closed endpoints', 'test Interval containment where one Interval is checked inside another', 'test Interval containment with infinite-length bounds using float inf', 'test Interval containment with zero-length degenerate intervals', 'test Interval containment across int, Timestamp, and Timedelta types', 'test the pandas Interval repr and str formatting for right-closed and left-closed intervals', 'test the pandas Interval class properties including closed, left, right, and mid attributes', 'test that hashing a pandas Interval instance does not raise an exception', 'test the Interval.length property with numeric, timedelta, and infinity endpoints', 'test Interval.length with Timestamp endpoints across multiple timezones', 'test Interval.is_empty with different left/right endpoints and closed parameter values', 'test that an Interval overlaps with itself for all closed parameter combinations', 'test that a nested Interval always overlaps with its parent Interval', 'test that two disjoint Intervals never overlap regardless of closed parameters', 'test that two Intervals sharing an endpoint overlap only when both endpoints are closed', 'test that calling overlaps with a non-Interval argument raises TypeError']
```

Usage

```
{'test_overlaps_self': 'test that an Interval overlaps with itself for all closed parameter combinations', 'test_overlaps_nested': 'test that a nested Interval always overlaps with its parent Interval', 'test_overlaps_disjoint': 'test that two disjoint Intervals never overlap regardless of closed parameters', 'test_overlaps_endpoint': 'test that two Intervals sharing an endpoint overlap only when both endpoints are closed', 'test_overlaps_invalid_type': 'test that calling overlaps with a non-Interval argument raises TypeError'}
```

