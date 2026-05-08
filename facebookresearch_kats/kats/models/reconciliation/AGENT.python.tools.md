# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/models/reconciliation/base_models.py

Prompts

```
['create a BaseTHModel instance with model_name and model_params for a supported forecasting model', 'create a BaseTHModel instance by passing precomputed residuals and forecasts arrays directly', 'create a GetAggregateTS instance from a univariate TimeSeriesData object for aggregation', 'aggregate a time series to multiple temporal levels using GetAggregateTS aggregate method', 'review the BASE_MODELS dictionary mapping model names to kats forecasting model classes', 'fit a TemporalHierarchicalModel with base models across multiple temporal aggregation levels', 'predict reconciled forecasts using methods like struc, svar, hvar, mint_shrink, or mint_sample', 'get the W weighting matrix for temporal hierarchical reconciliation using struc, svar, hvar, or mint methods', 'get the S aggregation matrix that maps disaggregated forecasts to their temporal hierarchy levels', 'validate and filter out bad forecasts by comparing base model forecasts against median forecasts']
```

Usage

```
{'create_BaseTHModel_with_model_info': 'create a BaseTHModel instance with model_name and model_params for a supported forecasting model', 'create_BaseTHModel_with_residuals': 'create a BaseTHModel instance by passing precomputed residuals and forecasts arrays directly', 'create_GetAggregateTS_for_time_series': 'create a GetAggregateTS instance from a univariate TimeSeriesData object for aggregation', 'aggregate_time_series_to_levels': 'aggregate a time series to multiple temporal levels using GetAggregateTS aggregate method', 'review_BASE_MODELS_registry': 'review the BASE_MODELS dictionary mapping model names to kats forecasting model classes'}
```

## File: facebookresearch_kats/kats/models/reconciliation/thm.py

Prompts

```
['create a BaseTHModel instance with model_name and model_params for a supported forecasting model', 'create a BaseTHModel instance by passing precomputed residuals and forecasts arrays directly', 'create a GetAggregateTS instance from a univariate TimeSeriesData object for aggregation', 'aggregate a time series to multiple temporal levels using GetAggregateTS aggregate method', 'review the BASE_MODELS dictionary mapping model names to kats forecasting model classes', 'fit a TemporalHierarchicalModel with base models across multiple temporal aggregation levels', 'predict reconciled forecasts using methods like struc, svar, hvar, mint_shrink, or mint_sample', 'get the W weighting matrix for temporal hierarchical reconciliation using struc, svar, hvar, or mint methods', 'get the S aggregation matrix that maps disaggregated forecasts to their temporal hierarchy levels', 'validate and filter out bad forecasts by comparing base model forecasts against median forecasts']
```

Usage

```
{'fit_temporal_hierarchical_model': 'fit a TemporalHierarchicalModel with base models across multiple temporal aggregation levels', 'predict_reconciled_forecasts': 'predict reconciled forecasts using methods like struc, svar, hvar, mint_shrink, or mint_sample', 'get_W_matrix': 'get the W weighting matrix for temporal hierarchical reconciliation using struc, svar, hvar, or mint methods', 'get_S_matrix': 'get the S aggregation matrix that maps disaggregated forecasts to their temporal hierarchy levels', 'median_validation_filter': 'validate and filter out bad forecasts by comparing base model forecasts against median forecasts'}
```

