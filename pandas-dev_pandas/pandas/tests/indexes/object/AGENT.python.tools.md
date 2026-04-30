# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/indexes/object/test_astype.py

Prompts

```
['test that casting an Index of np.datetime64 NaTs to timedelta64 raises TypeError', 'test the pandas Index.get_indexer method with pad and backfill methods on string object-dtype Index', 'test that pandas Index.get_indexer raises TypeError for unsupported operations on string object-dtype Index', 'test pandas Index.get_indexer correctly handles NA values without mangling pairwise NA comparisons', 'test pandas Index.get_indexer matches None values in object-dtype Index without casting to string', 'test pandas Index.get_indexer_non_unique handles nulls and non-unique object-dtype Index values', 'test pandas Index.get_indexer_non_unique handles numpy NaT values in object-dtype Index', 'test pandas Index contains correctly handles mixed-resolution datetime64 values in object-dtype Index', 'test pandas Index.get_loc correctly handles mixed-resolution datetime64 values in object-dtype Index', 'test pandas Index.get_indexer works with mixed-resolution datetime64 in monotonic object-dtype Index', 'test pandas Index.get_indexer handles mixed-resolution datetime64 in non-monotonic object-dtype Index']
```

Usage

```
{'test_astype_invalid_nas_to_tdt64_raises': 'test that casting an Index of np.datetime64 NaTs to timedelta64 raises TypeError'}
```

## File: pandas-dev_pandas/pandas/tests/indexes/object/test_indexing.py

Prompts

```
['test that casting an Index of np.datetime64 NaTs to timedelta64 raises TypeError', 'test the pandas Index.get_indexer method with pad and backfill methods on string object-dtype Index', 'test that pandas Index.get_indexer raises TypeError for unsupported operations on string object-dtype Index', 'test pandas Index.get_indexer correctly handles NA values without mangling pairwise NA comparisons', 'test pandas Index.get_indexer matches None values in object-dtype Index without casting to string', 'test pandas Index.get_indexer_non_unique handles nulls and non-unique object-dtype Index values', 'test pandas Index.get_indexer_non_unique handles numpy NaT values in object-dtype Index', 'test pandas Index contains correctly handles mixed-resolution datetime64 values in object-dtype Index', 'test pandas Index.get_loc correctly handles mixed-resolution datetime64 values in object-dtype Index', 'test pandas Index.get_indexer works with mixed-resolution datetime64 in monotonic object-dtype Index', 'test pandas Index.get_indexer handles mixed-resolution datetime64 in non-monotonic object-dtype Index']
```

Usage

```
{'test_get_indexer_strings': 'test the pandas Index.get_indexer method with pad and backfill methods on string object-dtype Index', 'test_get_indexer_strings_raises': 'test that pandas Index.get_indexer raises TypeError for unsupported operations on string object-dtype Index', 'test_get_indexer_with_NA_values': 'test pandas Index.get_indexer correctly handles NA values without mangling pairwise NA comparisons', 'test_get_indexer_infer_string_missing_values': 'test pandas Index.get_indexer matches None values in object-dtype Index without casting to string', 'test_get_indexer_non_unique_nas': 'test pandas Index.get_indexer_non_unique handles nulls and non-unique object-dtype Index values', 'test_get_indexer_non_unique_np_nats': 'test pandas Index.get_indexer_non_unique handles numpy NaT values in object-dtype Index', 'test_contains_mixed_resolution_datetime': 'test pandas Index contains correctly handles mixed-resolution datetime64 values in object-dtype Index', 'test_get_loc_mixed_resolution_datetime': 'test pandas Index.get_loc correctly handles mixed-resolution datetime64 values in object-dtype Index', 'test_get_indexer_monotonic_datetime': 'test pandas Index.get_indexer works with mixed-resolution datetime64 in monotonic object-dtype Index', 'test_get_indexer_non_monotonic_datetime': 'test pandas Index.get_indexer handles mixed-resolution datetime64 in non-monotonic object-dtype Index'}
```

