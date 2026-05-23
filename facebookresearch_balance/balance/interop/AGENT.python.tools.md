# Agent Python Tools

- repo: facebookresearch/balance
- repo_uri: https://github.com/facebookresearch/balance

## File: facebookresearch_balance/balance/interop/_common.py

Prompts

```
['get the active weight column name from a balance Sample object', 'drop balance adjustment history columns like weight_pre_adjust and weight_adjusted_N from a DataFrame', 'drop rows with NaN weights from a DataFrame before forwarding to a downstream adapter', 'validate that a weight column has at least one positive entry and no negative entries', 'attach a balance Sample as provenance metadata to a downstream result object', 'build a diff_diff SurveyDesign from a balance Sample with survey design columns and weight type', 'aggregate a respondent-level balance Sample into a geo-period panel via diff_diff aggregate_survey', 'fit a diff-diff estimator like CallawaySantAnna on a balance Sample with survey design in one call', 'combine balance ASMD and Kish ESS with diff-diff design-effect into a single flat diagnostic dict', 'review the fit_did function logic that splits estimator kwargs between __init__ and fit signatures']
```

Usage

```
{'get_active_weight_column': 'get the active weight column name from a balance Sample object', 'drop_history_columns': 'drop balance adjustment history columns like weight_pre_adjust and weight_adjusted_N from a DataFrame', 'drop_nan_weight_rows': 'drop rows with NaN weights from a DataFrame before forwarding to a downstream adapter', 'validate_nonzero_weights': 'validate that a weight column has at least one positive entry and no negative entries', 'attach_balance_provenance': 'attach a balance Sample as provenance metadata to a downstream result object'}
```

## File: facebookresearch_balance/balance/interop/diff_diff.py

Prompts

```
['get the active weight column name from a balance Sample object', 'drop balance adjustment history columns like weight_pre_adjust and weight_adjusted_N from a DataFrame', 'drop rows with NaN weights from a DataFrame before forwarding to a downstream adapter', 'validate that a weight column has at least one positive entry and no negative entries', 'attach a balance Sample as provenance metadata to a downstream result object', 'build a diff_diff SurveyDesign from a balance Sample with survey design columns and weight type', 'aggregate a respondent-level balance Sample into a geo-period panel via diff_diff aggregate_survey', 'fit a diff-diff estimator like CallawaySantAnna on a balance Sample with survey design in one call', 'combine balance ASMD and Kish ESS with diff-diff design-effect into a single flat diagnostic dict', 'review the fit_did function logic that splits estimator kwargs between __init__ and fit signatures']
```

Usage

```
{'build_survey_design_from_balance_sample': 'build a diff_diff SurveyDesign from a balance Sample with survey design columns and weight type', 'aggregate_panel_for_did_from_microdata': 'aggregate a respondent-level balance Sample into a geo-period panel via diff_diff aggregate_survey', 'fit_did_estimator_on_balance_sample': 'fit a diff-diff estimator like CallawaySantAnna on a balance Sample with survey design in one call', 'generate_cross_package_diagnostics_dict': 'combine balance ASMD and Kish ESS with diff-diff design-effect into a single flat diagnostic dict', 'review_fit_did_kwargs_splitting_logic': 'review the fit_did function logic that splits estimator kwargs between __init__ and fit signatures'}
```

