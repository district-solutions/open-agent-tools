# Agent Python Tools

- repo: facebookresearch/cpcaudio
- repo_uri: https://github.com/facebookresearch/cpc_audio

## File: facebookresearch_cpcaudio/cpc/criterion/criterion.py

Prompts

```
['build a CPC unsupervised criterion module with nPredicts steps and negative sampling for contrastive prediction training', 'create a prediction network with RNN, LSTM, conv, or transformer predictors for contrastive prediction coding', 'create a speaker classification criterion with a linear classifier and cross entropy loss for speaker identification', 'create a phone classification criterion with a linear or multi-layer classifier for phoneme prediction tasks', 'create a CTC phone criterion module with a linear classifier and CTC loss for sequence-to-sequence phone recognition', 'create an EqualizedConv1d layer with He initialization and zero bias for audio feature extraction', 'create an EqualizedConv2d layer with He initialization and zero bias for image feature extraction', 'create an EqualizedLinear layer with He initialization and zero bias for a fully connected layer', 'upscale a 2D tensor by a given integer factor using nearest-neighbor style expansion', 'apply per-sample normalization to a tensor by dividing by its L2 norm along dimension 1', 'run beam search decoding on CTC score predictions with a specified number of beams and blank label', 'run label chain collapsing on a 2D tensor to remove consecutive duplicate labels and return padded output', 'run Needleman-Wunsch sequence alignment scoring between two sequences with configurable deletion, mismatch, and reward scores', 'run sequence PER calculation using Needleman-Wunsch alignment with normalized error rate between ground truth and detected labels', 'run parallel PER evaluation across a data loader using beam search decoding and multiprocessing for batched audio features']
```

Usage

```
{'build_CPCUnsupersivedCriterion': 'build a CPC unsupervised criterion module with nPredicts steps and negative sampling for contrastive prediction training', 'create_PredictionNetwork': 'create a prediction network with RNN, LSTM, conv, or transformer predictors for contrastive prediction coding', 'create_SpeakerCriterion': 'create a speaker classification criterion with a linear classifier and cross entropy loss for speaker identification', 'create_PhoneCriterion': 'create a phone classification criterion with a linear or multi-layer classifier for phoneme prediction tasks', 'create_CTCTPhoneCriterion': 'create a CTC phone criterion module with a linear classifier and CTC loss for sequence-to-sequence phone recognition'}
```

## File: facebookresearch_cpcaudio/cpc/criterion/custom_layers.py

Prompts

```
['build a CPC unsupervised criterion module with nPredicts steps and negative sampling for contrastive prediction training', 'create a prediction network with RNN, LSTM, conv, or transformer predictors for contrastive prediction coding', 'create a speaker classification criterion with a linear classifier and cross entropy loss for speaker identification', 'create a phone classification criterion with a linear or multi-layer classifier for phoneme prediction tasks', 'create a CTC phone criterion module with a linear classifier and CTC loss for sequence-to-sequence phone recognition', 'create an EqualizedConv1d layer with He initialization and zero bias for audio feature extraction', 'create an EqualizedConv2d layer with He initialization and zero bias for image feature extraction', 'create an EqualizedLinear layer with He initialization and zero bias for a fully connected layer', 'upscale a 2D tensor by a given integer factor using nearest-neighbor style expansion', 'apply per-sample normalization to a tensor by dividing by its L2 norm along dimension 1', 'run beam search decoding on CTC score predictions with a specified number of beams and blank label', 'run label chain collapsing on a 2D tensor to remove consecutive duplicate labels and return padded output', 'run Needleman-Wunsch sequence alignment scoring between two sequences with configurable deletion, mismatch, and reward scores', 'run sequence PER calculation using Needleman-Wunsch alignment with normalized error rate between ground truth and detected labels', 'run parallel PER evaluation across a data loader using beam search decoding and multiprocessing for batched audio features']
```

Usage

```
{'create_equalized_conv1d_layer': 'create an EqualizedConv1d layer with He initialization and zero bias for audio feature extraction', 'create_equalized_conv2d_layer': 'create an EqualizedConv2d layer with He initialization and zero bias for image feature extraction', 'create_equalized_linear_layer': 'create an EqualizedLinear layer with He initialization and zero bias for a fully connected layer', 'upscale_2d_tensor': 'upscale a 2D tensor by a given integer factor using nearest-neighbor style expansion', 'apply_normalization_layer': 'apply per-sample normalization to a tensor by dividing by its L2 norm along dimension 1'}
```

## File: facebookresearch_cpcaudio/cpc/criterion/seq_alignment.py

Prompts

```
['build a CPC unsupervised criterion module with nPredicts steps and negative sampling for contrastive prediction training', 'create a prediction network with RNN, LSTM, conv, or transformer predictors for contrastive prediction coding', 'create a speaker classification criterion with a linear classifier and cross entropy loss for speaker identification', 'create a phone classification criterion with a linear or multi-layer classifier for phoneme prediction tasks', 'create a CTC phone criterion module with a linear classifier and CTC loss for sequence-to-sequence phone recognition', 'create an EqualizedConv1d layer with He initialization and zero bias for audio feature extraction', 'create an EqualizedConv2d layer with He initialization and zero bias for image feature extraction', 'create an EqualizedLinear layer with He initialization and zero bias for a fully connected layer', 'upscale a 2D tensor by a given integer factor using nearest-neighbor style expansion', 'apply per-sample normalization to a tensor by dividing by its L2 norm along dimension 1', 'run beam search decoding on CTC score predictions with a specified number of beams and blank label', 'run label chain collapsing on a 2D tensor to remove consecutive duplicate labels and return padded output', 'run Needleman-Wunsch sequence alignment scoring between two sequences with configurable deletion, mismatch, and reward scores', 'run sequence PER calculation using Needleman-Wunsch alignment with normalized error rate between ground truth and detected labels', 'run parallel PER evaluation across a data loader using beam search decoding and multiprocessing for batched audio features']
```

Usage

```
{'run_beam_search_ctc': 'run beam search decoding on CTC score predictions with a specified number of beams and blank label', 'run_collapse_label_chain': 'run label chain collapsing on a 2D tensor to remove consecutive duplicate labels and return padded output', 'run_needleman_wunsch_align_score': 'run Needleman-Wunsch sequence alignment scoring between two sequences with configurable deletion, mismatch, and reward scores', 'run_get_seq_per': 'run sequence PER calculation using Needleman-Wunsch alignment with normalized error rate between ground truth and detected labels', 'run_get_per': 'run parallel PER evaluation across a data loader using beam search decoding and multiprocessing for batched audio features'}
```

