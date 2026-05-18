# Agent Python Tools

- repo: facebookresearch/noresqa
- repo_uri: https://github.com/facebookresearch/noresqa

## File: facebookresearch_noresqa/main.py

Prompts

```
['run NORESQA speech quality prediction on a test audio file against a reference NMR file', 'run NORESQA-MOS prediction to estimate MOS score of a test audio file using a clean reference', 'run NORESQA predictions on a test file against a list of NMR files from a text file', 'review the extract_stft function that computes STFT magnitude and phase features from audio', 'review the model_prediction_noresqa function that returns preference probability and SDR quantification scores', 'build a NORESQA model with metric_type=0 to predict audio quality using base_encoder and TemporalConvNet', 'build a NORESQA model with metric_type=1 to predict MOS scores using a wav2vec SSL backbone', 'create a model_dimred module that applies multi-scale 2D convolutions and pooling for dimensionality reduction', 'create a TemporalConvNet with dilated temporal convolutional blocks for sequential audio feature extraction', 'create a PoolAtt attention-pooling module that computes weighted pooling over variable-length sequences']
```

Usage

```
{'run_noresqa_prediction': 'run NORESQA speech quality prediction on a test audio file against a reference NMR file', 'run_noresqa_mos_prediction': 'run NORESQA-MOS prediction to estimate MOS score of a test audio file using a clean reference', 'run_noresqa_batch_list': 'run NORESQA predictions on a test file against a list of NMR files from a text file', 'review_extract_stft': 'review the extract_stft function that computes STFT magnitude and phase features from audio', 'review_model_prediction_noresqa': 'review the model_prediction_noresqa function that returns preference probability and SDR quantification scores'}
```

## File: facebookresearch_noresqa/model.py

Prompts

```
['run NORESQA speech quality prediction on a test audio file against a reference NMR file', 'run NORESQA-MOS prediction to estimate MOS score of a test audio file using a clean reference', 'run NORESQA predictions on a test file against a list of NMR files from a text file', 'review the extract_stft function that computes STFT magnitude and phase features from audio', 'review the model_prediction_noresqa function that returns preference probability and SDR quantification scores', 'build a NORESQA model with metric_type=0 to predict audio quality using base_encoder and TemporalConvNet', 'build a NORESQA model with metric_type=1 to predict MOS scores using a wav2vec SSL backbone', 'create a model_dimred module that applies multi-scale 2D convolutions and pooling for dimensionality reduction', 'create a TemporalConvNet with dilated temporal convolutional blocks for sequential audio feature extraction', 'create a PoolAtt attention-pooling module that computes weighted pooling over variable-length sequences']
```

Usage

```
{'build_NORESQA_metric0': 'build a NORESQA model with metric_type=0 to predict audio quality using base_encoder and TemporalConvNet', 'build_NORESQA_metric1': 'build a NORESQA model with metric_type=1 to predict MOS scores using a wav2vec SSL backbone', 'create_model_dimred': 'create a model_dimred module that applies multi-scale 2D convolutions and pooling for dimensionality reduction', 'create_TemporalConvNet': 'create a TemporalConvNet with dilated temporal convolutional blocks for sequential audio feature extraction', 'create_PoolAtt': 'create a PoolAtt attention-pooling module that computes weighted pooling over variable-length sequences'}
```

