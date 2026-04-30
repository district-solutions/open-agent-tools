# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/cloud/test_prepare_cloud_plan.py

Prompts

```
['test the prepare_cloud_plan function serializes a LazyFrame with cloud source and basic operations to bytes', 'test the prepare_cloud_plan function handles LazyFrames containing map_elements and map_batches UDFs', 'test the prepare_cloud_plan function with custom QueryOptFlags to toggle projection_pushdown optimization', 'test that prepare_cloud_plan raises InvalidOperationError when allow_local_scans is False with local data sources', 'test that prepare_cloud_plan succeeds with local data sources when allow_local_scans is True']
```

Usage

```
{'test_prepare_cloud_plan': 'test the prepare_cloud_plan function serializes a LazyFrame with cloud source and basic operations to bytes', 'test_prepare_cloud_plan_udf': 'test the prepare_cloud_plan function handles LazyFrames containing map_elements and map_batches UDFs', 'test_prepare_cloud_plan_optimization_toggle': 'test the prepare_cloud_plan function with custom QueryOptFlags to toggle projection_pushdown optimization', 'test_prepare_cloud_plan_fail_on_local_data_source': 'test that prepare_cloud_plan raises InvalidOperationError when allow_local_scans is False with local data sources', 'test_prepare_cloud_plan_succeed_on_local_data_source': 'test that prepare_cloud_plan succeeds with local data sources when allow_local_scans is True'}
```

