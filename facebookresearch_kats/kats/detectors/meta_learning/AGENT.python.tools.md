# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/detectors/meta_learning/hpt_tuning.py

Prompts

```
['extract time series features from a TimeSeriesData object using get_ts_features', 'preprocess raw metadata DataFrame into data_x and data_y for MetaDetectHptSelect using metadata_detect_reader', 'train a MetaDetectHptSelect model with neural network hyperparameters on time series feature data', 'predict optimal hyperparameters for a detection algorithm from a TimeSeriesData using get_hpt_from_ts', 'predict optimal hyperparameters from feature arrays or DataFrames using get_hpt_from_features', 'extract time series features from a TimeSeriesData object using Kats TsFeatures', 'preprocess a pandas DataFrame of detection metadata by converting string columns to dicts and scaling parameters', 'train a MetaDetectModelSelect classifier on metadata to recommend the best detection model for time series', 'predict the most suitable detection model for a given TimeSeriesData using a trained MetaDetectModelSelect', 'predict the best detection model for multiple time series by passing a DataFrame of features', 'get metadata features and hyperparameter results for a given algorithm name using SynthMetadataReader', 'load raw synthetic detection training data from the bundled CSV file using SynthMetadataReader', 'extract preprocessed feature columns as data_x DataFrame for meta-learning detection training', 'extract hyperparameter tuning results as data_y DataFrame scaled by seconds per day for an algorithm', 'scale down n_control, n_test, historical_window, and scan_window parameters by dividing by seconds in a day']
```

Usage

```
{'extract_time_series_features': 'extract time series features from a TimeSeriesData object using get_ts_features', 'preprocess_metadata_for_hpt': 'preprocess raw metadata DataFrame into data_x and data_y for MetaDetectHptSelect using metadata_detect_reader', 'train_meta_hpt_model': 'train a MetaDetectHptSelect model with neural network hyperparameters on time series feature data', 'predict_hpt_from_time_series': 'predict optimal hyperparameters for a detection algorithm from a TimeSeriesData using get_hpt_from_ts', 'predict_hpt_from_features': 'predict optimal hyperparameters from feature arrays or DataFrames using get_hpt_from_features'}
```

## File: facebookresearch_kats/kats/detectors/meta_learning/metalearning_detection_model.py

Prompts

```
['extract time series features from a TimeSeriesData object using get_ts_features', 'preprocess raw metadata DataFrame into data_x and data_y for MetaDetectHptSelect using metadata_detect_reader', 'train a MetaDetectHptSelect model with neural network hyperparameters on time series feature data', 'predict optimal hyperparameters for a detection algorithm from a TimeSeriesData using get_hpt_from_ts', 'predict optimal hyperparameters from feature arrays or DataFrames using get_hpt_from_features', 'extract time series features from a TimeSeriesData object using Kats TsFeatures', 'preprocess a pandas DataFrame of detection metadata by converting string columns to dicts and scaling parameters', 'train a MetaDetectModelSelect classifier on metadata to recommend the best detection model for time series', 'predict the most suitable detection model for a given TimeSeriesData using a trained MetaDetectModelSelect', 'predict the best detection model for multiple time series by passing a DataFrame of features', 'get metadata features and hyperparameter results for a given algorithm name using SynthMetadataReader', 'load raw synthetic detection training data from the bundled CSV file using SynthMetadataReader', 'extract preprocessed feature columns as data_x DataFrame for meta-learning detection training', 'extract hyperparameter tuning results as data_y DataFrame scaled by seconds per day for an algorithm', 'scale down n_control, n_test, historical_window, and scan_window parameters by dividing by seconds in a day']
```

Usage

```
{'extract_ts_features': 'extract time series features from a TimeSeriesData object using Kats TsFeatures', 'preprocess_detection_metadata': 'preprocess a pandas DataFrame of detection metadata by converting string columns to dicts and scaling parameters', 'train_meta_detect_model': 'train a MetaDetectModelSelect classifier on metadata to recommend the best detection model for time series', 'predict_best_detection_model': 'predict the most suitable detection model for a given TimeSeriesData using a trained MetaDetectModelSelect', 'predict_by_feature_dataframe': 'predict the best detection model for multiple time series by passing a DataFrame of features'}
```

## File: facebookresearch_kats/kats/detectors/meta_learning/synth_metadata_reader.py

Prompts

```
['extract time series features from a TimeSeriesData object using get_ts_features', 'preprocess raw metadata DataFrame into data_x and data_y for MetaDetectHptSelect using metadata_detect_reader', 'train a MetaDetectHptSelect model with neural network hyperparameters on time series feature data', 'predict optimal hyperparameters for a detection algorithm from a TimeSeriesData using get_hpt_from_ts', 'predict optimal hyperparameters from feature arrays or DataFrames using get_hpt_from_features', 'extract time series features from a TimeSeriesData object using Kats TsFeatures', 'preprocess a pandas DataFrame of detection metadata by converting string columns to dicts and scaling parameters', 'train a MetaDetectModelSelect classifier on metadata to recommend the best detection model for time series', 'predict the most suitable detection model for a given TimeSeriesData using a trained MetaDetectModelSelect', 'predict the best detection model for multiple time series by passing a DataFrame of features', 'get metadata features and hyperparameter results for a given algorithm name using SynthMetadataReader', 'load raw synthetic detection training data from the bundled CSV file using SynthMetadataReader', 'extract preprocessed feature columns as data_x DataFrame for meta-learning detection training', 'extract hyperparameter tuning results as data_y DataFrame scaled by seconds per day for an algorithm', 'scale down n_control, n_test, historical_window, and scan_window parameters by dividing by seconds in a day']
```

Usage

```
{'get_metadata_for_algorithm': 'get metadata features and hyperparameter results for a given algorithm name using SynthMetadataReader', 'load_raw_synthetic_data': 'load raw synthetic detection training data from the bundled CSV file using SynthMetadataReader', 'extract_features_data_x': 'extract preprocessed feature columns as data_x DataFrame for meta-learning detection training', 'extract_hpt_results_data_y': 'extract hyperparameter tuning results as data_y DataFrame scaled by seconds per day for an algorithm', 'scale_down_parameters': 'scale down n_control, n_test, historical_window, and scan_window parameters by dividing by seconds in a day'}
```

