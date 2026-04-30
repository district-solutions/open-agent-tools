# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/benchmark/conftest.py

Prompts

```
['test the pytest fixture groupby_data that generates a polars DataFrame with group-by benchmark data', "test the polars filter operation that selects rows where id1 equals 'id046' and aggregates id6 and v3 columns", "test the polars filter operation that excludes rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test the polars lazy frame filter with eq_missing predicate on a grouped data frame', 'test the polars lazy frame filter with negated eq_missing predicate to exclude matching rows', 'test the polars lazy frame filter, select with cast and sum aggregation, and collect pipeline', 'test group-by aggregation with single column key and sum on polars lazy frame', 'test group-by aggregation with two column keys and sum on polars lazy frame', 'test group-by aggregation with single column key and sum plus mean on polars lazy frame', 'test group-by aggregation with single column key and mean across multiple columns on polars lazy frame', 'test group-by aggregation with two column keys and median plus std on polars lazy frame', 'test the benchmark test function that writes a CSV, reads it eagerly and lazily, and verifies matching shapes', 'test the join_where method with strict inequality conditions (less than, greater than) between two lazy dataframes', 'test the join_where method with non-strict inequality conditions (less than or equal, greater than or equal) between two lazy dataframes', 'test the join_where method with a single inequality condition and a computed column alias', 'test the join_where method raises ColumnNotFoundError when referencing a non-existent column', 'test the join_where method with a non-elementwise condition using pl.len() as a column reference', 'test the polars DataFrame.with_columns performance regression with 10,000 columns and verify ratio under 100x']
```

Usage

```
{'test_groupby_data_fixture': 'test the pytest fixture groupby_data that generates a polars DataFrame with group-by benchmark data'}
```

## File: pola-rs_polars/py-polars/tests/benchmark/test_filter.py

Prompts

```
['test the pytest fixture groupby_data that generates a polars DataFrame with group-by benchmark data', "test the polars filter operation that selects rows where id1 equals 'id046' and aggregates id6 and v3 columns", "test the polars filter operation that excludes rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test the polars lazy frame filter with eq_missing predicate on a grouped data frame', 'test the polars lazy frame filter with negated eq_missing predicate to exclude matching rows', 'test the polars lazy frame filter, select with cast and sum aggregation, and collect pipeline', 'test group-by aggregation with single column key and sum on polars lazy frame', 'test group-by aggregation with two column keys and sum on polars lazy frame', 'test group-by aggregation with single column key and sum plus mean on polars lazy frame', 'test group-by aggregation with single column key and mean across multiple columns on polars lazy frame', 'test group-by aggregation with two column keys and median plus std on polars lazy frame', 'test the benchmark test function that writes a CSV, reads it eagerly and lazily, and verifies matching shapes', 'test the join_where method with strict inequality conditions (less than, greater than) between two lazy dataframes', 'test the join_where method with non-strict inequality conditions (less than or equal, greater than or equal) between two lazy dataframes', 'test the join_where method with a single inequality condition and a computed column alias', 'test the join_where method raises ColumnNotFoundError when referencing a non-existent column', 'test the join_where method with a non-elementwise condition using pl.len() as a column reference', 'test the polars DataFrame.with_columns performance regression with 10,000 columns and verify ratio under 100x']
```

Usage

```
{'test_filter1': "test the polars filter operation that selects rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test_filter2': "test the polars filter operation that excludes rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test_lazy_filter': 'test the polars lazy frame filter with eq_missing predicate on a grouped data frame', 'test_filter_negation': 'test the polars lazy frame filter with negated eq_missing predicate to exclude matching rows', 'test_filter_select_collect': 'test the polars lazy frame filter, select with cast and sum aggregation, and collect pipeline'}
```

## File: pola-rs_polars/py-polars/tests/benchmark/test_group_by.py

Prompts

```
['test the pytest fixture groupby_data that generates a polars DataFrame with group-by benchmark data', "test the polars filter operation that selects rows where id1 equals 'id046' and aggregates id6 and v3 columns", "test the polars filter operation that excludes rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test the polars lazy frame filter with eq_missing predicate on a grouped data frame', 'test the polars lazy frame filter with negated eq_missing predicate to exclude matching rows', 'test the polars lazy frame filter, select with cast and sum aggregation, and collect pipeline', 'test group-by aggregation with single column key and sum on polars lazy frame', 'test group-by aggregation with two column keys and sum on polars lazy frame', 'test group-by aggregation with single column key and sum plus mean on polars lazy frame', 'test group-by aggregation with single column key and mean across multiple columns on polars lazy frame', 'test group-by aggregation with two column keys and median plus std on polars lazy frame', 'test the benchmark test function that writes a CSV, reads it eagerly and lazily, and verifies matching shapes', 'test the join_where method with strict inequality conditions (less than, greater than) between two lazy dataframes', 'test the join_where method with non-strict inequality conditions (less than or equal, greater than or equal) between two lazy dataframes', 'test the join_where method with a single inequality condition and a computed column alias', 'test the join_where method raises ColumnNotFoundError when referencing a non-existent column', 'test the join_where method with a non-elementwise condition using pl.len() as a column reference', 'test the polars DataFrame.with_columns performance regression with 10,000 columns and verify ratio under 100x']
```

Usage

```
{'test_groupby_h2oai_q1': 'test group-by aggregation with single column key and sum on polars lazy frame', 'test_groupby_h2oai_q2': 'test group-by aggregation with two column keys and sum on polars lazy frame', 'test_groupby_h2oai_q3': 'test group-by aggregation with single column key and sum plus mean on polars lazy frame', 'test_groupby_h2oai_q4': 'test group-by aggregation with single column key and mean across multiple columns on polars lazy frame', 'test_groupby_h2oai_q6': 'test group-by aggregation with two column keys and median plus std on polars lazy frame'}
```

## File: pola-rs_polars/py-polars/tests/benchmark/test_io.py

Prompts

```
['test the pytest fixture groupby_data that generates a polars DataFrame with group-by benchmark data', "test the polars filter operation that selects rows where id1 equals 'id046' and aggregates id6 and v3 columns", "test the polars filter operation that excludes rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test the polars lazy frame filter with eq_missing predicate on a grouped data frame', 'test the polars lazy frame filter with negated eq_missing predicate to exclude matching rows', 'test the polars lazy frame filter, select with cast and sum aggregation, and collect pipeline', 'test group-by aggregation with single column key and sum on polars lazy frame', 'test group-by aggregation with two column keys and sum on polars lazy frame', 'test group-by aggregation with single column key and sum plus mean on polars lazy frame', 'test group-by aggregation with single column key and mean across multiple columns on polars lazy frame', 'test group-by aggregation with two column keys and median plus std on polars lazy frame', 'test the benchmark test function that writes a CSV, reads it eagerly and lazily, and verifies matching shapes', 'test the join_where method with strict inequality conditions (less than, greater than) between two lazy dataframes', 'test the join_where method with non-strict inequality conditions (less than or equal, greater than or equal) between two lazy dataframes', 'test the join_where method with a single inequality condition and a computed column alias', 'test the join_where method raises ColumnNotFoundError when referencing a non-existent column', 'test the join_where method with a non-elementwise condition using pl.len() as a column reference', 'test the polars DataFrame.with_columns performance regression with 10,000 columns and verify ratio under 100x']
```

Usage

```
{'test_write_read_scan_large_csv': 'test the benchmark test function that writes a CSV, reads it eagerly and lazily, and verifies matching shapes'}
```

## File: pola-rs_polars/py-polars/tests/benchmark/test_join_where.py

Prompts

```
['test the pytest fixture groupby_data that generates a polars DataFrame with group-by benchmark data', "test the polars filter operation that selects rows where id1 equals 'id046' and aggregates id6 and v3 columns", "test the polars filter operation that excludes rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test the polars lazy frame filter with eq_missing predicate on a grouped data frame', 'test the polars lazy frame filter with negated eq_missing predicate to exclude matching rows', 'test the polars lazy frame filter, select with cast and sum aggregation, and collect pipeline', 'test group-by aggregation with single column key and sum on polars lazy frame', 'test group-by aggregation with two column keys and sum on polars lazy frame', 'test group-by aggregation with single column key and sum plus mean on polars lazy frame', 'test group-by aggregation with single column key and mean across multiple columns on polars lazy frame', 'test group-by aggregation with two column keys and median plus std on polars lazy frame', 'test the benchmark test function that writes a CSV, reads it eagerly and lazily, and verifies matching shapes', 'test the join_where method with strict inequality conditions (less than, greater than) between two lazy dataframes', 'test the join_where method with non-strict inequality conditions (less than or equal, greater than or equal) between two lazy dataframes', 'test the join_where method with a single inequality condition and a computed column alias', 'test the join_where method raises ColumnNotFoundError when referencing a non-existent column', 'test the join_where method with a non-elementwise condition using pl.len() as a column reference', 'test the polars DataFrame.with_columns performance regression with 10,000 columns and verify ratio under 100x']
```

Usage

```
{'test_join_where_inequalities': 'test the join_where method with strict inequality conditions (less than, greater than) between two lazy dataframes', 'test_join_where_non_strict_inequalities': 'test the join_where method with non-strict inequality conditions (less than or equal, greater than or equal) between two lazy dataframes', 'test_join_where_single_inequality': 'test the join_where method with a single inequality condition and a computed column alias', 'test_join_where_invalid_column': 'test the join_where method raises ColumnNotFoundError when referencing a non-existent column', 'test_join_where_not_elementwise': 'test the join_where method with a non-elementwise condition using pl.len() as a column reference'}
```

## File: pola-rs_polars/py-polars/tests/benchmark/test_with_columns.py

Prompts

```
['test the pytest fixture groupby_data that generates a polars DataFrame with group-by benchmark data', "test the polars filter operation that selects rows where id1 equals 'id046' and aggregates id6 and v3 columns", "test the polars filter operation that excludes rows where id1 equals 'id046' and aggregates id6 and v3 columns", 'test the polars lazy frame filter with eq_missing predicate on a grouped data frame', 'test the polars lazy frame filter with negated eq_missing predicate to exclude matching rows', 'test the polars lazy frame filter, select with cast and sum aggregation, and collect pipeline', 'test group-by aggregation with single column key and sum on polars lazy frame', 'test group-by aggregation with two column keys and sum on polars lazy frame', 'test group-by aggregation with single column key and sum plus mean on polars lazy frame', 'test group-by aggregation with single column key and mean across multiple columns on polars lazy frame', 'test group-by aggregation with two column keys and median plus std on polars lazy frame', 'test the benchmark test function that writes a CSV, reads it eagerly and lazily, and verifies matching shapes', 'test the join_where method with strict inequality conditions (less than, greater than) between two lazy dataframes', 'test the join_where method with non-strict inequality conditions (less than or equal, greater than or equal) between two lazy dataframes', 'test the join_where method with a single inequality condition and a computed column alias', 'test the join_where method raises ColumnNotFoundError when referencing a non-existent column', 'test the join_where method with a non-elementwise condition using pl.len() as a column reference', 'test the polars DataFrame.with_columns performance regression with 10,000 columns and verify ratio under 100x']
```

Usage

```
{'test_with_columns_quadratic_19503': 'test the polars DataFrame.with_columns performance regression with 10,000 columns and verify ratio under 100x'}
```

