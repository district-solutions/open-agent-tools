# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/emotion_conversion/emotion_models/duration_predictor.py

Prompts

```
['train a CnnPredictor model to predict token durations from clustered speech data using TSV and KM files', 'load a saved CnnPredictor checkpoint from a file path and return the model in eval mode', 'save a CnnPredictor model state dict with padding token and model class config to a file path', 'predict durations for a batch of token sequences and inflate each token by its predicted duration count', 'collate a batch of token sequences and duration labels into padded tensors with attention masks', 'train a CNN pitch predictor model for F0 prediction from phoneme tokens using hydra config', 'load a saved CnnPredictor checkpoint from a file path and restore model state and F0 stats', 'run inference with CnnPredictor to predict F0 values from token sequences with speaker and style embeddings', 'compute adaptive F0 quantization bins from speaker statistics using histogram-based percentile binning', 'convert F0 frequency values to bin indices and back using bucketize or one-hot probability distributions', 'create a Stat object to track running mean and std of torch tensor values', 'update a Stat object with new torch tensor data to accumulate statistics', 'create an F0Stat object to track F0 statistics filtering out unvoiced zero frames', 'create an Accuracy object to track prediction accuracy with a tolerance threshold', 'compute the accuracy score from an Accuracy object using a tolerance value']
```

Usage

```
{'train_duration_predictor': 'train a CnnPredictor model to predict token durations from clustered speech data using TSV and KM files', 'load_checkpoint': 'load a saved CnnPredictor checkpoint from a file path and return the model in eval mode', 'save_checkpoint': 'save a CnnPredictor model state dict with padding token and model class config to a file path', 'inflate_input': 'predict durations for a batch of token sequences and inflate each token by its predicted duration count', 'collate_batch': 'collate a batch of token sequences and duration labels into padded tensors with attention masks'}
```

## File: facebookresearch_fairseq/examples/emotion_conversion/emotion_models/pitch_predictor.py

Prompts

```
['train a CnnPredictor model to predict token durations from clustered speech data using TSV and KM files', 'load a saved CnnPredictor checkpoint from a file path and return the model in eval mode', 'save a CnnPredictor model state dict with padding token and model class config to a file path', 'predict durations for a batch of token sequences and inflate each token by its predicted duration count', 'collate a batch of token sequences and duration labels into padded tensors with attention masks', 'train a CNN pitch predictor model for F0 prediction from phoneme tokens using hydra config', 'load a saved CnnPredictor checkpoint from a file path and restore model state and F0 stats', 'run inference with CnnPredictor to predict F0 values from token sequences with speaker and style embeddings', 'compute adaptive F0 quantization bins from speaker statistics using histogram-based percentile binning', 'convert F0 frequency values to bin indices and back using bucketize or one-hot probability distributions', 'create a Stat object to track running mean and std of torch tensor values', 'update a Stat object with new torch tensor data to accumulate statistics', 'create an F0Stat object to track F0 statistics filtering out unvoiced zero frames', 'create an Accuracy object to track prediction accuracy with a tolerance threshold', 'compute the accuracy score from an Accuracy object using a tolerance value']
```

Usage

```
{'train_CnnPredictor': 'train a CNN pitch predictor model for F0 prediction from phoneme tokens using hydra config', 'load_ckpt_CnnPredictor': 'load a saved CnnPredictor checkpoint from a file path and restore model state and F0 stats', 'inference_CnnPredictor': 'run inference with CnnPredictor to predict F0 values from token sequences with speaker and style embeddings', 'quantize_f0': 'compute adaptive F0 quantization bins from speaker statistics using histogram-based percentile binning', 'freq2bin_bin2freq': 'convert F0 frequency values to bin indices and back using bucketize or one-hot probability distributions'}
```

## File: facebookresearch_fairseq/examples/emotion_conversion/emotion_models/utils.py

Prompts

```
['train a CnnPredictor model to predict token durations from clustered speech data using TSV and KM files', 'load a saved CnnPredictor checkpoint from a file path and return the model in eval mode', 'save a CnnPredictor model state dict with padding token and model class config to a file path', 'predict durations for a batch of token sequences and inflate each token by its predicted duration count', 'collate a batch of token sequences and duration labels into padded tensors with attention masks', 'train a CNN pitch predictor model for F0 prediction from phoneme tokens using hydra config', 'load a saved CnnPredictor checkpoint from a file path and restore model state and F0 stats', 'run inference with CnnPredictor to predict F0 values from token sequences with speaker and style embeddings', 'compute adaptive F0 quantization bins from speaker statistics using histogram-based percentile binning', 'convert F0 frequency values to bin indices and back using bucketize or one-hot probability distributions', 'create a Stat object to track running mean and std of torch tensor values', 'update a Stat object with new torch tensor data to accumulate statistics', 'create an F0Stat object to track F0 statistics filtering out unvoiced zero frames', 'create an Accuracy object to track prediction accuracy with a tolerance threshold', 'compute the accuracy score from an Accuracy object using a tolerance value']
```

Usage

```
{'create_Stat_class': 'create a Stat object to track running mean and std of torch tensor values', 'update_Stat_with_tensor': 'update a Stat object with new torch tensor data to accumulate statistics', 'create_F0Stat_class': 'create an F0Stat object to track F0 statistics filtering out unvoiced zero frames', 'create_Accuracy_class': 'create an Accuracy object to track prediction accuracy with a tolerance threshold', 'compute_Accuracy_score': 'compute the accuracy score from an Accuracy object using a tolerance value'}
```

