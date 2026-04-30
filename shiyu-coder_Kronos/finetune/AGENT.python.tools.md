# Agent Python Tools

- repo: shiyu-coder/Kronos
- repo_uri: https://github.com/shiyu-coder/Kronos

## File: shiyu-coder_Kronos/finetune/dataset.py

Prompts

```
["create a QlibDataset instance for training with data_type='train' to load financial time series data", "create a QlibDataset instance for validation with data_type='val' to load financial time series data", 'test the QlibDataset __len__ method to get the number of samples per epoch', 'test the QlibDataset __getitem__ method to retrieve normalized feature tensors and time stamps', 'review the QlibDataset set_epoch_seed method to set per-epoch randomness for distributed training', 'run the QlibDataPreprocessor to load, process, and split financial data into train, val, and test sets', 'initialize the Qlib environment with a custom data path and CN region configuration', 'load raw OHLCV financial data from Qlib for multiple symbols and compute derived features', 'split loaded financial data into train, validation, and test sets by time ranges and save as pickle files', 'filter out symbols with insufficient data length relative to lookback and predict windows', 'run Kronos inference and backtesting on Qlib test data with CLI arguments for device selection', 'build a PyTorch Dataset that iterates sliding windows over Qlib time-series data for model inference', 'run Qlib backtesting with TopkDropoutStrategy and generate cumulative return plots for multiple signals', 'generate prediction signals from a fine-tuned Kronos model on Qlib test data and return as pivot DataFrames', 'load fine-tuned KronosTokenizer and Kronos predictor models from pretrained checkpoints onto a device', 'run the script with torchrun to fine-tune the Kronos predictor model on financial time-series data', 'create distributed dataloaders for training and validation using QlibDataset with DistributedSampler', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and distributed data parallel', 'setup distributed data parallel training with torchrun, DDP wrapping, and multi-GPU coordination', 'save the best checkpoint during training when validation loss improves below the previous best', 'run tokenizer finetuning via torchrun with DDP, AdamW optimizer, and OneCycleLR scheduler', 'create distributed dataloaders using DistributedSampler with configurable rank and world size']
```

Usage

```
{'create_QlibDataset': "create a QlibDataset instance for training with data_type='train' to load financial time series data", 'create_QlibDataset_val': "create a QlibDataset instance for validation with data_type='val' to load financial time series data", 'test_QlibDataset_len': 'test the QlibDataset __len__ method to get the number of samples per epoch', 'test_QlibDataset_getitem': 'test the QlibDataset __getitem__ method to retrieve normalized feature tensors and time stamps', 'review_QlibDataset_set_epoch_seed': 'review the QlibDataset set_epoch_seed method to set per-epoch randomness for distributed training'}
```

## File: shiyu-coder_Kronos/finetune/qlib_data_preprocess.py

Prompts

```
["create a QlibDataset instance for training with data_type='train' to load financial time series data", "create a QlibDataset instance for validation with data_type='val' to load financial time series data", 'test the QlibDataset __len__ method to get the number of samples per epoch', 'test the QlibDataset __getitem__ method to retrieve normalized feature tensors and time stamps', 'review the QlibDataset set_epoch_seed method to set per-epoch randomness for distributed training', 'run the QlibDataPreprocessor to load, process, and split financial data into train, val, and test sets', 'initialize the Qlib environment with a custom data path and CN region configuration', 'load raw OHLCV financial data from Qlib for multiple symbols and compute derived features', 'split loaded financial data into train, validation, and test sets by time ranges and save as pickle files', 'filter out symbols with insufficient data length relative to lookback and predict windows', 'run Kronos inference and backtesting on Qlib test data with CLI arguments for device selection', 'build a PyTorch Dataset that iterates sliding windows over Qlib time-series data for model inference', 'run Qlib backtesting with TopkDropoutStrategy and generate cumulative return plots for multiple signals', 'generate prediction signals from a fine-tuned Kronos model on Qlib test data and return as pivot DataFrames', 'load fine-tuned KronosTokenizer and Kronos predictor models from pretrained checkpoints onto a device', 'run the script with torchrun to fine-tune the Kronos predictor model on financial time-series data', 'create distributed dataloaders for training and validation using QlibDataset with DistributedSampler', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and distributed data parallel', 'setup distributed data parallel training with torchrun, DDP wrapping, and multi-GPU coordination', 'save the best checkpoint during training when validation loss improves below the previous best', 'run tokenizer finetuning via torchrun with DDP, AdamW optimizer, and OneCycleLR scheduler', 'create distributed dataloaders using DistributedSampler with configurable rank and world size']
```

Usage

```
{'run_qlib_data_preprocess': 'run the QlibDataPreprocessor to load, process, and split financial data into train, val, and test sets', 'initialize_qlib_environment': 'initialize the Qlib environment with a custom data path and CN region configuration', 'load_qlib_financial_data': 'load raw OHLCV financial data from Qlib for multiple symbols and compute derived features', 'split_dataset_train_val_test': 'split loaded financial data into train, validation, and test sets by time ranges and save as pickle files', 'filter_symbols_insufficient_data': 'filter out symbols with insufficient data length relative to lookback and predict windows'}
```

## File: shiyu-coder_Kronos/finetune/qlib_test.py

Prompts

```
["create a QlibDataset instance for training with data_type='train' to load financial time series data", "create a QlibDataset instance for validation with data_type='val' to load financial time series data", 'test the QlibDataset __len__ method to get the number of samples per epoch', 'test the QlibDataset __getitem__ method to retrieve normalized feature tensors and time stamps', 'review the QlibDataset set_epoch_seed method to set per-epoch randomness for distributed training', 'run the QlibDataPreprocessor to load, process, and split financial data into train, val, and test sets', 'initialize the Qlib environment with a custom data path and CN region configuration', 'load raw OHLCV financial data from Qlib for multiple symbols and compute derived features', 'split loaded financial data into train, validation, and test sets by time ranges and save as pickle files', 'filter out symbols with insufficient data length relative to lookback and predict windows', 'run Kronos inference and backtesting on Qlib test data with CLI arguments for device selection', 'build a PyTorch Dataset that iterates sliding windows over Qlib time-series data for model inference', 'run Qlib backtesting with TopkDropoutStrategy and generate cumulative return plots for multiple signals', 'generate prediction signals from a fine-tuned Kronos model on Qlib test data and return as pivot DataFrames', 'load fine-tuned KronosTokenizer and Kronos predictor models from pretrained checkpoints onto a device', 'run the script with torchrun to fine-tune the Kronos predictor model on financial time-series data', 'create distributed dataloaders for training and validation using QlibDataset with DistributedSampler', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and distributed data parallel', 'setup distributed data parallel training with torchrun, DDP wrapping, and multi-GPU coordination', 'save the best checkpoint during training when validation loss improves below the previous best', 'run tokenizer finetuning via torchrun with DDP, AdamW optimizer, and OneCycleLR scheduler', 'create distributed dataloaders using DistributedSampler with configurable rank and world size']
```

Usage

```
{'run_qlib_inference_backtest': 'run Kronos inference and backtesting on Qlib test data with CLI arguments for device selection', 'build_qlib_test_dataset': 'build a PyTorch Dataset that iterates sliding windows over Qlib time-series data for model inference', 'run_qlib_backtest': 'run Qlib backtesting with TopkDropoutStrategy and generate cumulative return plots for multiple signals', 'generate_predictions': 'generate prediction signals from a fine-tuned Kronos model on Qlib test data and return as pivot DataFrames', 'load_kronos_models': 'load fine-tuned KronosTokenizer and Kronos predictor models from pretrained checkpoints onto a device'}
```

## File: shiyu-coder_Kronos/finetune/train_predictor.py

Prompts

```
["create a QlibDataset instance for training with data_type='train' to load financial time series data", "create a QlibDataset instance for validation with data_type='val' to load financial time series data", 'test the QlibDataset __len__ method to get the number of samples per epoch', 'test the QlibDataset __getitem__ method to retrieve normalized feature tensors and time stamps', 'review the QlibDataset set_epoch_seed method to set per-epoch randomness for distributed training', 'run the QlibDataPreprocessor to load, process, and split financial data into train, val, and test sets', 'initialize the Qlib environment with a custom data path and CN region configuration', 'load raw OHLCV financial data from Qlib for multiple symbols and compute derived features', 'split loaded financial data into train, validation, and test sets by time ranges and save as pickle files', 'filter out symbols with insufficient data length relative to lookback and predict windows', 'run Kronos inference and backtesting on Qlib test data with CLI arguments for device selection', 'build a PyTorch Dataset that iterates sliding windows over Qlib time-series data for model inference', 'run Qlib backtesting with TopkDropoutStrategy and generate cumulative return plots for multiple signals', 'generate prediction signals from a fine-tuned Kronos model on Qlib test data and return as pivot DataFrames', 'load fine-tuned KronosTokenizer and Kronos predictor models from pretrained checkpoints onto a device', 'run the script with torchrun to fine-tune the Kronos predictor model on financial time-series data', 'create distributed dataloaders for training and validation using QlibDataset with DistributedSampler', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and distributed data parallel', 'setup distributed data parallel training with torchrun, DDP wrapping, and multi-GPU coordination', 'save the best checkpoint during training when validation loss improves below the previous best', 'run tokenizer finetuning via torchrun with DDP, AdamW optimizer, and OneCycleLR scheduler', 'create distributed dataloaders using DistributedSampler with configurable rank and world size']
```

Usage

```
{'run_train_predictor': 'run the script with torchrun to fine-tune the Kronos predictor model on financial time-series data', 'create_dataloaders': 'create distributed dataloaders for training and validation using QlibDataset with DistributedSampler', 'train_model': 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and distributed data parallel', 'setup_ddp_training': 'setup distributed data parallel training with torchrun, DDP wrapping, and multi-GPU coordination', 'save_best_model': 'save the best checkpoint during training when validation loss improves below the previous best'}
```

## File: shiyu-coder_Kronos/finetune/train_tokenizer.py

Prompts

```
["create a QlibDataset instance for training with data_type='train' to load financial time series data", "create a QlibDataset instance for validation with data_type='val' to load financial time series data", 'test the QlibDataset __len__ method to get the number of samples per epoch', 'test the QlibDataset __getitem__ method to retrieve normalized feature tensors and time stamps', 'review the QlibDataset set_epoch_seed method to set per-epoch randomness for distributed training', 'run the QlibDataPreprocessor to load, process, and split financial data into train, val, and test sets', 'initialize the Qlib environment with a custom data path and CN region configuration', 'load raw OHLCV financial data from Qlib for multiple symbols and compute derived features', 'split loaded financial data into train, validation, and test sets by time ranges and save as pickle files', 'filter out symbols with insufficient data length relative to lookback and predict windows', 'run Kronos inference and backtesting on Qlib test data with CLI arguments for device selection', 'build a PyTorch Dataset that iterates sliding windows over Qlib time-series data for model inference', 'run Qlib backtesting with TopkDropoutStrategy and generate cumulative return plots for multiple signals', 'generate prediction signals from a fine-tuned Kronos model on Qlib test data and return as pivot DataFrames', 'load fine-tuned KronosTokenizer and Kronos predictor models from pretrained checkpoints onto a device', 'run the script with torchrun to fine-tune the Kronos predictor model on financial time-series data', 'create distributed dataloaders for training and validation using QlibDataset with DistributedSampler', 'train the Kronos predictor model with AdamW optimizer, OneCycleLR scheduler, and distributed data parallel', 'setup distributed data parallel training with torchrun, DDP wrapping, and multi-GPU coordination', 'save the best checkpoint during training when validation loss improves below the previous best', 'run tokenizer finetuning via torchrun with DDP, AdamW optimizer, and OneCycleLR scheduler', 'create distributed dataloaders using DistributedSampler with configurable rank and world size']
```

Usage

```
{'create_dataloaders': 'create distributed dataloaders for training and validation with configurable batch size and workers', 'train_model': 'train a KronosTokenizer model with distributed data parallel, gradient accumulation, and validation', 'run_train_tokenizer': 'run tokenizer finetuning via torchrun with DDP, AdamW optimizer, and OneCycleLR scheduler', 'setup_ddp_training': 'setup distributed data parallel training with CometML logging and checkpoint saving', 'create_dataloaders_distributed': 'create distributed dataloaders using DistributedSampler with configurable rank and world size'}
```

