# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/ooc/test_ooc.py

Prompts

```
['test out-of-core spilling for a single streaming query with group_by, agg, and join operations', 'test out-of-core spill lifecycle across multiple consecutive streaming queries', 'test forcing out-of-core spilling by setting POLARS_OOC_SPILL_POLICY and memory budget environment variables', 'test verifying out-of-core spill, trigger, reload, and clean log messages in captured stderr', "test collecting a polars LazyFrame query with engine='streaming' and comparing against in-memory results"]
```

Usage

```
{'test_ooc_spill': 'test out-of-core spilling for a single streaming query with group_by, agg, and join operations', 'test_ooc_spill_multiple_queries': 'test out-of-core spill lifecycle across multiple consecutive streaming queries', 'test_force_spill': 'test forcing out-of-core spilling by setting POLARS_OOC_SPILL_POLICY and memory budget environment variables', 'test_assert_spill_reload_clean': 'test verifying out-of-core spill, trigger, reload, and clean log messages in captured stderr', 'test_lazyframe_streaming_collect': "test collecting a polars LazyFrame query with engine='streaming' and comparing against in-memory results"}
```

