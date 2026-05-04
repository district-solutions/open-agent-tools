# Agent Python Tools

- repo: facebookresearch/balance
- repo_uri: https://github.com/facebookresearch/balance

## File: facebookresearch_balance/balance/utils/data_transformation.py

Prompts

```
["add NA indicator columns to a DataFrame, replacing nulls with 0 or '_NA' and creating boolean indicator columns", "add NA indicator columns to a DataFrame while preserving pre-existing '_is_na_*' indicator columns without duplication", 'drop rows with missing values from a DataFrame and their corresponding design weight values', 'cut numeric variables of a DataFrame into equal-sized quantile buckets with a specified number of bins', "lump infrequent categorical levels into a single '_lumped_other' category based on a minimum proportion threshold", 'find the intersection of variables across multiple pandas DataFrames and return them ordered', 'remove entries that are NA or infinite across multiple aligned numpy or pandas arrays', 'guess the ID column name in a pandas DataFrame from a list of candidate column names', 'validate and extract non-null series values aligned with their corresponding weight array', 'convert a pandas Series to numeric values, drop NaN, and validate at least one value remains', 'create a function that truncates a string to a given length and appends ellipsis if needed', 'build a logging formatter that truncates log messages to 2000 characters to avoid verbose output', 'test the _truncate_text function to ensure it truncates strings longer than the specified length', "review the TruncationFormatter class and its integration with Python's logging module", 'refactor the TruncationFormatter to make the truncation length configurable instead of hardcoded to 2000', 'build a model matrix from a pandas DataFrame using a patsy formula string', 'create a model matrix from sample and target DataFrames with NA indicator handling', 'build a combined design matrix for IPW weighting with optional scaling and penalty rescaling', 'generate an additive formula string from a list of variable names', 'expand dot notation in a formula to include all variables from a list']
```

Usage

```
{'add_na_indicator': "add NA indicator columns to a DataFrame, replacing nulls with 0 or '_NA' and creating boolean indicator columns", 'add_na_indicator_to_combined': "add NA indicator columns to a DataFrame while preserving pre-existing '_is_na_*' indicator columns without duplication", 'drop_na_rows': 'drop rows with missing values from a DataFrame and their corresponding design weight values', 'quantize': 'cut numeric variables of a DataFrame into equal-sized quantile buckets with a specified number of bins', 'fct_lump': "lump infrequent categorical levels into a single '_lumped_other' category based on a minimum proportion threshold"}
```

## File: facebookresearch_balance/balance/utils/input_validation.py

Prompts

```
["add NA indicator columns to a DataFrame, replacing nulls with 0 or '_NA' and creating boolean indicator columns", "add NA indicator columns to a DataFrame while preserving pre-existing '_is_na_*' indicator columns without duplication", 'drop rows with missing values from a DataFrame and their corresponding design weight values', 'cut numeric variables of a DataFrame into equal-sized quantile buckets with a specified number of bins', "lump infrequent categorical levels into a single '_lumped_other' category based on a minimum proportion threshold", 'find the intersection of variables across multiple pandas DataFrames and return them ordered', 'remove entries that are NA or infinite across multiple aligned numpy or pandas arrays', 'guess the ID column name in a pandas DataFrame from a list of candidate column names', 'validate and extract non-null series values aligned with their corresponding weight array', 'convert a pandas Series to numeric values, drop NaN, and validate at least one value remains', 'create a function that truncates a string to a given length and appends ellipsis if needed', 'build a logging formatter that truncates log messages to 2000 characters to avoid verbose output', 'test the _truncate_text function to ensure it truncates strings longer than the specified length', "review the TruncationFormatter class and its integration with Python's logging module", 'refactor the TruncationFormatter to make the truncation length configurable instead of hardcoded to 2000', 'build a model matrix from a pandas DataFrame using a patsy formula string', 'create a model matrix from sample and target DataFrames with NA indicator handling', 'build a combined design matrix for IPW weighting with optional scaling and penalty rescaling', 'generate an additive formula string from a list of variable names', 'expand dot notation in a formula to include all variables from a list']
```

Usage

```
{'choose_variables_intersection': 'find the intersection of variables across multiple pandas DataFrames and return them ordered', 'rm_mutual_nas_clean_arrays': 'remove entries that are NA or infinite across multiple aligned numpy or pandas arrays', 'guess_id_column_dataframe': 'guess the ID column name in a pandas DataFrame from a list of candidate column names', 'extract_series_and_weights_filter': 'validate and extract non-null series values aligned with their corresponding weight array', 'coerce_to_numeric_and_validate': 'convert a pandas Series to numeric values, drop NaN, and validate at least one value remains'}
```

## File: facebookresearch_balance/balance/utils/logging_utils.py

Prompts

```
["add NA indicator columns to a DataFrame, replacing nulls with 0 or '_NA' and creating boolean indicator columns", "add NA indicator columns to a DataFrame while preserving pre-existing '_is_na_*' indicator columns without duplication", 'drop rows with missing values from a DataFrame and their corresponding design weight values', 'cut numeric variables of a DataFrame into equal-sized quantile buckets with a specified number of bins', "lump infrequent categorical levels into a single '_lumped_other' category based on a minimum proportion threshold", 'find the intersection of variables across multiple pandas DataFrames and return them ordered', 'remove entries that are NA or infinite across multiple aligned numpy or pandas arrays', 'guess the ID column name in a pandas DataFrame from a list of candidate column names', 'validate and extract non-null series values aligned with their corresponding weight array', 'convert a pandas Series to numeric values, drop NaN, and validate at least one value remains', 'create a function that truncates a string to a given length and appends ellipsis if needed', 'build a logging formatter that truncates log messages to 2000 characters to avoid verbose output', 'test the _truncate_text function to ensure it truncates strings longer than the specified length', "review the TruncationFormatter class and its integration with Python's logging module", 'refactor the TruncationFormatter to make the truncation length configurable instead of hardcoded to 2000', 'build a model matrix from a pandas DataFrame using a patsy formula string', 'create a model matrix from sample and target DataFrames with NA indicator handling', 'build a combined design matrix for IPW weighting with optional scaling and penalty rescaling', 'generate an additive formula string from a list of variable names', 'expand dot notation in a formula to include all variables from a list']
```

Usage

```
{'create_truncate_text': 'create a function that truncates a string to a given length and appends ellipsis if needed', 'build_truncation_formatter': 'build a logging formatter that truncates log messages to 2000 characters to avoid verbose output', 'test_truncate_text': 'test the _truncate_text function to ensure it truncates strings longer than the specified length', 'review_truncation_formatter': "review the TruncationFormatter class and its integration with Python's logging module", 'refactor_truncation_formatter': 'refactor the TruncationFormatter to make the truncation length configurable instead of hardcoded to 2000'}
```

## File: facebookresearch_balance/balance/utils/model_matrix.py

Prompts

```
["add NA indicator columns to a DataFrame, replacing nulls with 0 or '_NA' and creating boolean indicator columns", "add NA indicator columns to a DataFrame while preserving pre-existing '_is_na_*' indicator columns without duplication", 'drop rows with missing values from a DataFrame and their corresponding design weight values', 'cut numeric variables of a DataFrame into equal-sized quantile buckets with a specified number of bins', "lump infrequent categorical levels into a single '_lumped_other' category based on a minimum proportion threshold", 'find the intersection of variables across multiple pandas DataFrames and return them ordered', 'remove entries that are NA or infinite across multiple aligned numpy or pandas arrays', 'guess the ID column name in a pandas DataFrame from a list of candidate column names', 'validate and extract non-null series values aligned with their corresponding weight array', 'convert a pandas Series to numeric values, drop NaN, and validate at least one value remains', 'create a function that truncates a string to a given length and appends ellipsis if needed', 'build a logging formatter that truncates log messages to 2000 characters to avoid verbose output', 'test the _truncate_text function to ensure it truncates strings longer than the specified length', "review the TruncationFormatter class and its integration with Python's logging module", 'refactor the TruncationFormatter to make the truncation length configurable instead of hardcoded to 2000', 'build a model matrix from a pandas DataFrame using a patsy formula string', 'create a model matrix from sample and target DataFrames with NA indicator handling', 'build a combined design matrix for IPW weighting with optional scaling and penalty rescaling', 'generate an additive formula string from a list of variable names', 'expand dot notation in a formula to include all variables from a list']
```

Usage

```
{'build_model_matrix_from_dataframe': 'build a model matrix from a pandas DataFrame using a patsy formula string', 'create_model_matrix_sample_target': 'create a model matrix from sample and target DataFrames with NA indicator handling', 'build_design_matrix_for_ipw': 'build a combined design matrix for IPW weighting with optional scaling and penalty rescaling', 'generate_additive_formula': 'generate an additive formula string from a list of variable names', 'expand_dot_formula': 'expand dot notation in a formula to include all variables from a list'}
```

