# Agent Python Tools

- repo: facebookresearch/libri-light
- repo_uri: https://github.com/facebookresearch/libri-light

## File: facebookresearch_libri-light/eval/PER_src/seq_alignment.py

Prompts

```
['run beam search decoding on CTC score predictions with a specified number of beams to keep', 'run phone error rate evaluation on a validation loader using beam search and multiprocessing', 'compute the phone error rate between ground truth and detected label sequences using Needleman-Wunsch alignment', 'prepare sequence and phone label data by moving tensors to CUDA and trimming to max sequence length', 'cut a sequence tensor to the maximum sequence length across the batch dimension', 'create a SingleSequenceDataset to load audio sequences with phoneme labels using multiprocessing', 'build a CTCPhoneCriterion module with optional LSTM for phoneme recognition CTC loss', 'run a training step over a data loader with model, criterion, and optimizer', 'run a validation step over a data loader to compute average CTC loss', 'prepare audio sequence and phoneme label data by moving tensors to GPU and cutting to max length']
```

Usage

```
{'run_beam_search_ctc': 'run beam search decoding on CTC score predictions with a specified number of beams to keep', 'run_per_evaluation': 'run phone error rate evaluation on a validation loader using beam search and multiprocessing', 'compute_seq_per': 'compute the phone error rate between ground truth and detected label sequences using Needleman-Wunsch alignment', 'prepare_data_cuda': 'prepare sequence and phone label data by moving tensors to CUDA and trimming to max sequence length', 'cut_data_max_seq': 'cut a sequence tensor to the maximum sequence length across the batch dimension'}
```

## File: facebookresearch_libri-light/eval/PER_src/simplePhonemLearner.py

Prompts

```
['run beam search decoding on CTC score predictions with a specified number of beams to keep', 'run phone error rate evaluation on a validation loader using beam search and multiprocessing', 'compute the phone error rate between ground truth and detected label sequences using Needleman-Wunsch alignment', 'prepare sequence and phone label data by moving tensors to CUDA and trimming to max sequence length', 'cut a sequence tensor to the maximum sequence length across the batch dimension', 'create a SingleSequenceDataset to load audio sequences with phoneme labels using multiprocessing', 'build a CTCPhoneCriterion module with optional LSTM for phoneme recognition CTC loss', 'run a training step over a data loader with model, criterion, and optimizer', 'run a validation step over a data loader to compute average CTC loss', 'prepare audio sequence and phoneme label data by moving tensors to GPU and cutting to max length']
```

Usage

```
{'create_single_sequence_dataset': 'create a SingleSequenceDataset to load audio sequences with phoneme labels using multiprocessing', 'build_ctc_phone_criterion': 'build a CTCPhoneCriterion module with optional LSTM for phoneme recognition CTC loss', 'run_train_step': 'run a training step over a data loader with model, criterion, and optimizer', 'run_val_step': 'run a validation step over a data loader to compute average CTC loss', 'prepare_data_for_gpu': 'prepare audio sequence and phoneme label data by moving tensors to GPU and cutting to max length'}
```

