# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/models/metalearner/get_metadata.py

Prompts

```
['build a GetMetaData instance with TimeSeriesData to compute time series meta-data including features and best model', 'run tune_executor on a GetMetaData object to get best hyper-parameters and errors for each candidate model', 'run get_meta_data on a GetMetaData object to get features, best hyper-parameters, and best model name', 'review the GetMetaDataVal dataclass to understand the structure of meta-data results including hpt_res, features, and best_model', 'test the GetMetaData class validation methods to check time series length, constant values, and NaN or infinity values', 'build a MetaLearnHPT meta-learner using a default model like holtwinters or prophet for hyper-parameter recommendation', 'train the MetaLearnHPT multi-task neural network with SGD or Adam optimizer and early stopping', 'predict recommended hyper-parameters for a new time series using the trained MetaLearnHPT model', 'save a trained MetaLearnHPT model to a pickle file or load one from disk', 'build a MultitaskNet PyTorch module with shared layers and task-specific categorical and numerical output heads', 'train a meta-learner model selection classifier using RandomForest on time series metadata', 'predict the best forecasting model for a new time series using the trained meta-learner', 'predict the best forecasting model using fuzzy bootstrap method with significance level', 'save a trained meta-learner model to a pickle file and load it later', 'create a balanced dataset via random downsampling of imbalanced time series metadata', 'train a MetaLearnPredictability classifier using RandomForest to predict time series predictability from metadata features', 'predict whether a TimeSeriesData object is predictable using a trained MetaLearnPredictability model', 'predict predictability for multiple time series given their feature arrays using pred_by_feature', 'save a trained MetaLearnPredictability model to disk with joblib or load a pre-trained model from file', 'preprocess and rescale time series features to zero-mean unit-variance before training the classifier']
```

Usage

```
{'build_GetMetaData': 'build a GetMetaData instance with TimeSeriesData to compute time series meta-data including features and best model', 'run_tune_executor': 'run tune_executor on a GetMetaData object to get best hyper-parameters and errors for each candidate model', 'run_get_meta_data': 'run get_meta_data on a GetMetaData object to get features, best hyper-parameters, and best model name', 'review_GetMetaDataVal': 'review the GetMetaDataVal dataclass to understand the structure of meta-data results including hpt_res, features, and best_model', 'test_GetMetaData_validation': 'test the GetMetaData class validation methods to check time series length, constant values, and NaN or infinity values'}
```

## File: facebookresearch_kats/kats/models/metalearner/metalearner_hpt.py

Prompts

```
['build a GetMetaData instance with TimeSeriesData to compute time series meta-data including features and best model', 'run tune_executor on a GetMetaData object to get best hyper-parameters and errors for each candidate model', 'run get_meta_data on a GetMetaData object to get features, best hyper-parameters, and best model name', 'review the GetMetaDataVal dataclass to understand the structure of meta-data results including hpt_res, features, and best_model', 'test the GetMetaData class validation methods to check time series length, constant values, and NaN or infinity values', 'build a MetaLearnHPT meta-learner using a default model like holtwinters or prophet for hyper-parameter recommendation', 'train the MetaLearnHPT multi-task neural network with SGD or Adam optimizer and early stopping', 'predict recommended hyper-parameters for a new time series using the trained MetaLearnHPT model', 'save a trained MetaLearnHPT model to a pickle file or load one from disk', 'build a MultitaskNet PyTorch module with shared layers and task-specific categorical and numerical output heads', 'train a meta-learner model selection classifier using RandomForest on time series metadata', 'predict the best forecasting model for a new time series using the trained meta-learner', 'predict the best forecasting model using fuzzy bootstrap method with significance level', 'save a trained meta-learner model to a pickle file and load it later', 'create a balanced dataset via random downsampling of imbalanced time series metadata', 'train a MetaLearnPredictability classifier using RandomForest to predict time series predictability from metadata features', 'predict whether a TimeSeriesData object is predictable using a trained MetaLearnPredictability model', 'predict predictability for multiple time series given their feature arrays using pred_by_feature', 'save a trained MetaLearnPredictability model to disk with joblib or load a pre-trained model from file', 'preprocess and rescale time series features to zero-mean unit-variance before training the classifier']
```

Usage

```
{'build_MetaLearnHPT_default_model': 'build a MetaLearnHPT meta-learner using a default model like holtwinters or prophet for hyper-parameter recommendation', 'train_MetaLearnHPT': 'train the MetaLearnHPT multi-task neural network with SGD or Adam optimizer and early stopping', 'pred_MetaLearnHPT': 'predict recommended hyper-parameters for a new time series using the trained MetaLearnHPT model', 'save_load_MetaLearnHPT': 'save a trained MetaLearnHPT model to a pickle file or load one from disk', 'build_MultitaskNet': 'build a MultitaskNet PyTorch module with shared layers and task-specific categorical and numerical output heads'}
```

## File: facebookresearch_kats/kats/models/metalearner/metalearner_modelselect.py

Prompts

```
['build a GetMetaData instance with TimeSeriesData to compute time series meta-data including features and best model', 'run tune_executor on a GetMetaData object to get best hyper-parameters and errors for each candidate model', 'run get_meta_data on a GetMetaData object to get features, best hyper-parameters, and best model name', 'review the GetMetaDataVal dataclass to understand the structure of meta-data results including hpt_res, features, and best_model', 'test the GetMetaData class validation methods to check time series length, constant values, and NaN or infinity values', 'build a MetaLearnHPT meta-learner using a default model like holtwinters or prophet for hyper-parameter recommendation', 'train the MetaLearnHPT multi-task neural network with SGD or Adam optimizer and early stopping', 'predict recommended hyper-parameters for a new time series using the trained MetaLearnHPT model', 'save a trained MetaLearnHPT model to a pickle file or load one from disk', 'build a MultitaskNet PyTorch module with shared layers and task-specific categorical and numerical output heads', 'train a meta-learner model selection classifier using RandomForest on time series metadata', 'predict the best forecasting model for a new time series using the trained meta-learner', 'predict the best forecasting model using fuzzy bootstrap method with significance level', 'save a trained meta-learner model to a pickle file and load it later', 'create a balanced dataset via random downsampling of imbalanced time series metadata', 'train a MetaLearnPredictability classifier using RandomForest to predict time series predictability from metadata features', 'predict whether a TimeSeriesData object is predictable using a trained MetaLearnPredictability model', 'predict predictability for multiple time series given their feature arrays using pred_by_feature', 'save a trained MetaLearnPredictability model to disk with joblib or load a pre-trained model from file', 'preprocess and rescale time series features to zero-mean unit-variance before training the classifier']
```

Usage

```
{'train_MetaLearnModelSelect': 'train a meta-learner model selection classifier using RandomForest on time series metadata', 'pred_MetaLearnModelSelect': 'predict the best forecasting model for a new time series using the trained meta-learner', 'pred_fuzzy_MetaLearnModelSelect': 'predict the best forecasting model using fuzzy bootstrap method with significance level', 'save_load_MetaLearnModelSelect': 'save a trained meta-learner model to a pickle file and load it later', 'fit_resample_RandomDownSampler': 'create a balanced dataset via random downsampling of imbalanced time series metadata'}
```

## File: facebookresearch_kats/kats/models/metalearner/metalearner_predictability.py

Prompts

```
['build a GetMetaData instance with TimeSeriesData to compute time series meta-data including features and best model', 'run tune_executor on a GetMetaData object to get best hyper-parameters and errors for each candidate model', 'run get_meta_data on a GetMetaData object to get features, best hyper-parameters, and best model name', 'review the GetMetaDataVal dataclass to understand the structure of meta-data results including hpt_res, features, and best_model', 'test the GetMetaData class validation methods to check time series length, constant values, and NaN or infinity values', 'build a MetaLearnHPT meta-learner using a default model like holtwinters or prophet for hyper-parameter recommendation', 'train the MetaLearnHPT multi-task neural network with SGD or Adam optimizer and early stopping', 'predict recommended hyper-parameters for a new time series using the trained MetaLearnHPT model', 'save a trained MetaLearnHPT model to a pickle file or load one from disk', 'build a MultitaskNet PyTorch module with shared layers and task-specific categorical and numerical output heads', 'train a meta-learner model selection classifier using RandomForest on time series metadata', 'predict the best forecasting model for a new time series using the trained meta-learner', 'predict the best forecasting model using fuzzy bootstrap method with significance level', 'save a trained meta-learner model to a pickle file and load it later', 'create a balanced dataset via random downsampling of imbalanced time series metadata', 'train a MetaLearnPredictability classifier using RandomForest to predict time series predictability from metadata features', 'predict whether a TimeSeriesData object is predictable using a trained MetaLearnPredictability model', 'predict predictability for multiple time series given their feature arrays using pred_by_feature', 'save a trained MetaLearnPredictability model to disk with joblib or load a pre-trained model from file', 'preprocess and rescale time series features to zero-mean unit-variance before training the classifier']
```

Usage

```
{'train_metalearner_predictability': 'train a MetaLearnPredictability classifier using RandomForest to predict time series predictability from metadata features', 'predict_time_series': 'predict whether a TimeSeriesData object is predictable using a trained MetaLearnPredictability model', 'predict_by_features': 'predict predictability for multiple time series given their feature arrays using pred_by_feature', 'save_load_model': 'save a trained MetaLearnPredictability model to disk with joblib or load a pre-trained model from file', 'preprocess_features': 'preprocess and rescale time series features to zero-mean unit-variance before training the classifier'}
```

