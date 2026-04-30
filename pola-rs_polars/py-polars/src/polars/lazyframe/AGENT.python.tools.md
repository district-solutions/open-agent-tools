# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/lazyframe/frame.py

Prompts

```
['create a polars LazyFrame from a dictionary of column data and optional schema', 'run a lazy computation graph and materialize the result into a DataFrame', 'build a join between two LazyFrames using inner, left, or cross join strategies', 'test filtering LazyFrame rows with boolean predicate expressions', 'summarize profiling timing information for each node in a LazyFrame query plan', 'create a lazy group by aggregation that computes sum, mean, and count for each group', 'build a lazy group by query that filters groups using having predicates after aggregation', 'test the lazy group by head and tail methods to get first and last rows of each group', 'refactor the lazy group by map_groups method to apply a custom function over each group', 'summarize the lazy group by statistical methods including max, min, mean, median, and quantile', 'cancel an in-process query at earliest convenience', 'fetch the result of an in-process query returning None if not ready', 'await the result of an in-process query synchronously', 'create a QueryOptFlags instance with predicate_pushdown and projection_pushdown enabled', 'build a QueryOptFlags instance with all optimizations disabled using the none factory method', 'update QueryOptFlags instance with custom optimization settings like slice_pushdown and comm_subplan_elim', 'test QueryOptFlags._eager() method that creates flags optimized for eager evaluation mode', 'refactor decorated functions to forward deprecated optimization flag parameters to the new optimizations parameter']
```

Usage

```
{'create_lazyframe_from_dict': 'create a polars LazyFrame from a dictionary of column data and optional schema', 'run_collect_lazyframe': 'run a lazy computation graph and materialize the result into a DataFrame', 'build_join_lazyframes': 'build a join between two LazyFrames using inner, left, or cross join strategies', 'test_filter_lazyframe': 'test filtering LazyFrame rows with boolean predicate expressions', 'summarize_profile_lazyframe': 'summarize profiling timing information for each node in a LazyFrame query plan'}
```

## File: pola-rs_polars/py-polars/src/polars/lazyframe/group_by.py

Prompts

```
['create a polars LazyFrame from a dictionary of column data and optional schema', 'run a lazy computation graph and materialize the result into a DataFrame', 'build a join between two LazyFrames using inner, left, or cross join strategies', 'test filtering LazyFrame rows with boolean predicate expressions', 'summarize profiling timing information for each node in a LazyFrame query plan', 'create a lazy group by aggregation that computes sum, mean, and count for each group', 'build a lazy group by query that filters groups using having predicates after aggregation', 'test the lazy group by head and tail methods to get first and last rows of each group', 'refactor the lazy group by map_groups method to apply a custom function over each group', 'summarize the lazy group by statistical methods including max, min, mean, median, and quantile', 'cancel an in-process query at earliest convenience', 'fetch the result of an in-process query returning None if not ready', 'await the result of an in-process query synchronously', 'create a QueryOptFlags instance with predicate_pushdown and projection_pushdown enabled', 'build a QueryOptFlags instance with all optimizations disabled using the none factory method', 'update QueryOptFlags instance with custom optimization settings like slice_pushdown and comm_subplan_elim', 'test QueryOptFlags._eager() method that creates flags optimized for eager evaluation mode', 'refactor decorated functions to forward deprecated optimization flag parameters to the new optimizations parameter']
```

Usage

```
{'create_lazygroupby_agg': 'create a lazy group by aggregation that computes sum, mean, and count for each group', 'build_lazygroupby_having': 'build a lazy group by query that filters groups using having predicates after aggregation', 'test_lazygroupby_head_tail': 'test the lazy group by head and tail methods to get first and last rows of each group', 'refactor_lazygroupby_map_groups': 'refactor the lazy group by map_groups method to apply a custom function over each group', 'summarize_lazygroupby_stats': 'summarize the lazy group by statistical methods including max, min, mean, median, and quantile'}
```

## File: pola-rs_polars/py-polars/src/polars/lazyframe/in_process.py

Prompts

```
['create a polars LazyFrame from a dictionary of column data and optional schema', 'run a lazy computation graph and materialize the result into a DataFrame', 'build a join between two LazyFrames using inner, left, or cross join strategies', 'test filtering LazyFrame rows with boolean predicate expressions', 'summarize profiling timing information for each node in a LazyFrame query plan', 'create a lazy group by aggregation that computes sum, mean, and count for each group', 'build a lazy group by query that filters groups using having predicates after aggregation', 'test the lazy group by head and tail methods to get first and last rows of each group', 'refactor the lazy group by map_groups method to apply a custom function over each group', 'summarize the lazy group by statistical methods including max, min, mean, median, and quantile', 'cancel an in-process query at earliest convenience', 'fetch the result of an in-process query returning None if not ready', 'await the result of an in-process query synchronously', 'create a QueryOptFlags instance with predicate_pushdown and projection_pushdown enabled', 'build a QueryOptFlags instance with all optimizations disabled using the none factory method', 'update QueryOptFlags instance with custom optimization settings like slice_pushdown and comm_subplan_elim', 'test QueryOptFlags._eager() method that creates flags optimized for eager evaluation mode', 'refactor decorated functions to forward deprecated optimization flag parameters to the new optimizations parameter']
```

Usage

```
{'cancel_inprocess_query': 'cancel an in-process query at earliest convenience', 'fetch_inprocess_query': 'fetch the result of an in-process query returning None if not ready', 'fetch_blocking_inprocess_query': 'await the result of an in-process query synchronously'}
```

## File: pola-rs_polars/py-polars/src/polars/lazyframe/opt_flags.py

Prompts

```
['create a polars LazyFrame from a dictionary of column data and optional schema', 'run a lazy computation graph and materialize the result into a DataFrame', 'build a join between two LazyFrames using inner, left, or cross join strategies', 'test filtering LazyFrame rows with boolean predicate expressions', 'summarize profiling timing information for each node in a LazyFrame query plan', 'create a lazy group by aggregation that computes sum, mean, and count for each group', 'build a lazy group by query that filters groups using having predicates after aggregation', 'test the lazy group by head and tail methods to get first and last rows of each group', 'refactor the lazy group by map_groups method to apply a custom function over each group', 'summarize the lazy group by statistical methods including max, min, mean, median, and quantile', 'cancel an in-process query at earliest convenience', 'fetch the result of an in-process query returning None if not ready', 'await the result of an in-process query synchronously', 'create a QueryOptFlags instance with predicate_pushdown and projection_pushdown enabled', 'build a QueryOptFlags instance with all optimizations disabled using the none factory method', 'update QueryOptFlags instance with custom optimization settings like slice_pushdown and comm_subplan_elim', 'test QueryOptFlags._eager() method that creates flags optimized for eager evaluation mode', 'refactor decorated functions to forward deprecated optimization flag parameters to the new optimizations parameter']
```

Usage

```
{'create_QueryOptFlags': 'create a QueryOptFlags instance with predicate_pushdown and projection_pushdown enabled', 'build_optimizations_none': 'build a QueryOptFlags instance with all optimizations disabled using the none factory method', 'update_optimization_flags': 'update QueryOptFlags instance with custom optimization settings like slice_pushdown and comm_subplan_elim', 'test_eager_mode_flags': 'test QueryOptFlags._eager() method that creates flags optimized for eager evaluation mode', 'refactor_deprecated_flags': 'refactor decorated functions to forward deprecated optimization flag parameters to the new optimizations parameter'}
```

