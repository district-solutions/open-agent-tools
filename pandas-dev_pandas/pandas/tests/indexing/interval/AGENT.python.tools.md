# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/indexing/interval/test_interval.py

Prompts

```
['test interval index getitem with scalar keys using loc or iloc indexing', 'test interval index getitem on nonoverlapping monotonic intervals with increasing or decreasing order', 'test loc getitem on DataFrame with CategoricalIndex containing IntervalIndex categories', 'test setitem on Series with IntervalIndex using slice-based loc assignment', 'test MultiIndex with IntervalIndex level slicing using scalar float keys', 'test loc indexing on a Series with IntervalIndex using exact interval label matches', 'test loc indexing on a Series with IntervalIndex using scalar values that fall within intervals', 'test loc slicing on a Series with IntervalIndex using interval bounds as slice endpoints', 'test loc indexing on a Series with overlapping IntervalIndex intervals for scalars and intervals', 'test loc indexing on a Series with non-unique IntervalIndex returning multiple matching rows']
```

Usage

```
{'test_getitem_with_scalar': 'test interval index getitem with scalar keys using loc or iloc indexing', 'test_getitem_nonoverlapping_monotonic': 'test interval index getitem on nonoverlapping monotonic intervals with increasing or decreasing order', 'test_loc_getitem_frame': 'test loc getitem on DataFrame with CategoricalIndex containing IntervalIndex categories', 'test_setitem_interval_with_slice': 'test setitem on Series with IntervalIndex using slice-based loc assignment', 'test_mi_intervalindex_slicing_with_scalar': 'test MultiIndex with IntervalIndex level slicing using scalar float keys'}
```

## File: pandas-dev_pandas/pandas/tests/indexing/interval/test_interval_new.py

Prompts

```
['test interval index getitem with scalar keys using loc or iloc indexing', 'test interval index getitem on nonoverlapping monotonic intervals with increasing or decreasing order', 'test loc getitem on DataFrame with CategoricalIndex containing IntervalIndex categories', 'test setitem on Series with IntervalIndex using slice-based loc assignment', 'test MultiIndex with IntervalIndex level slicing using scalar float keys', 'test loc indexing on a Series with IntervalIndex using exact interval label matches', 'test loc indexing on a Series with IntervalIndex using scalar values that fall within intervals', 'test loc slicing on a Series with IntervalIndex using interval bounds as slice endpoints', 'test loc indexing on a Series with overlapping IntervalIndex intervals for scalars and intervals', 'test loc indexing on a Series with non-unique IntervalIndex returning multiple matching rows']
```

Usage

```
{'test_loc_with_interval': 'test loc indexing on a Series with IntervalIndex using exact interval label matches', 'test_loc_with_scalar': 'test loc indexing on a Series with IntervalIndex using scalar values that fall within intervals', 'test_loc_with_slices': 'test loc slicing on a Series with IntervalIndex using interval bounds as slice endpoints', 'test_loc_with_overlap': 'test loc indexing on a Series with overlapping IntervalIndex intervals for scalars and intervals', 'test_non_unique': 'test loc indexing on a Series with non-unique IntervalIndex returning multiple matching rows'}
```

