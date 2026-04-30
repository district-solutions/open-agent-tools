# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/indexes/string/test_astype.py

Prompts

```
['test Index.astype(str) converts bytes elements to str without decoding errors', 'test Series.astype(str) behaves consistently with Index.astype(str) for bytes-to-str conversion', 'test Index.astype(str) produces a str-dtyped Index from object-dtyped input containing mixed types', 'test tm.assert_index_equal validates that converted Index matches expected str Index', 'test tm.assert_series_equal validates that converted Series matches expected str Series', 'test the Index.get_loc method to retrieve the position of a label in a string Index', 'test that Index.get_loc raises KeyError when a label is not found in a string Index', 'test Index.get_indexer with pad and backfill methods on a string Index', 'test Index.get_indexer with missing values (None, np.nan, pd.NA) in a string Index', 'test Index.get_indexer_non_unique with non-unique NA values in a string Index', 'test Index.slice_locs with negative step slices on a string Index', 'test Index.slice_locs on a non-unique string Index with duplicate labels']
```

Usage

```
{'test_astype_str_from_bytes': 'test Index.astype(str) converts bytes elements to str without decoding errors', 'test_series_astype_str_from_bytes': 'test Series.astype(str) behaves consistently with Index.astype(str) for bytes-to-str conversion', 'test_astype_str_dtype': 'test Index.astype(str) produces a str-dtyped Index from object-dtyped input containing mixed types', 'test_assert_index_equal': 'test tm.assert_index_equal validates that converted Index matches expected str Index', 'test_assert_series_equal': 'test tm.assert_series_equal validates that converted Series matches expected str Series'}
```

## File: pandas-dev_pandas/pandas/tests/indexes/string/test_indexing.py

Prompts

```
['test Index.astype(str) converts bytes elements to str without decoding errors', 'test Series.astype(str) behaves consistently with Index.astype(str) for bytes-to-str conversion', 'test Index.astype(str) produces a str-dtyped Index from object-dtyped input containing mixed types', 'test tm.assert_index_equal validates that converted Index matches expected str Index', 'test tm.assert_series_equal validates that converted Series matches expected str Series', 'test the Index.get_loc method to retrieve the position of a label in a string Index', 'test that Index.get_loc raises KeyError when a label is not found in a string Index', 'test Index.get_indexer with pad and backfill methods on a string Index', 'test Index.get_indexer with missing values (None, np.nan, pd.NA) in a string Index', 'test Index.get_indexer_non_unique with non-unique NA values in a string Index', 'test Index.slice_locs with negative step slices on a string Index', 'test Index.slice_locs on a non-unique string Index with duplicate labels']
```

Usage

```
{'test_get_loc': 'test the Index.get_loc method to retrieve the position of a label in a string Index', 'test_get_loc_raises': 'test that Index.get_loc raises KeyError when a label is not found in a string Index', 'test_get_indexer_strings': 'test Index.get_indexer with pad and backfill methods on a string Index', 'test_get_indexer_missing': 'test Index.get_indexer with missing values (None, np.nan, pd.NA) in a string Index', 'test_get_indexer_non_unique_nas': 'test Index.get_indexer_non_unique with non-unique NA values in a string Index', 'test_slice_locs_negative_step': 'test Index.slice_locs with negative step slices on a string Index', 'test_slice_locs_dup': 'test Index.slice_locs on a non-unique string Index with duplicate labels'}
```

