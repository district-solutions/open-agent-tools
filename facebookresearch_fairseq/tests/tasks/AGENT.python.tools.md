# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/tests/tasks/test_denoising.py

Prompts

```
['test the DenoisingTask class to verify masked tokens match original tokens', 'run the unittest for fairseq denoising task with BART base architecture', 'test FileBinarizer.multiprocess_dataset to binarize raw text data with mmap implementation', 'test VocabularyDatasetBinarizer to convert raw text tokens into binarized dataset format', 'test the batch iterator for masked datasets with max tokens and positions constraints', 'test the MaskedLMTask to verify masked tokens match original tokens correctly', 'run the unit test that validates token masking behavior in the masked language model task', 'build a MaskedLMConfig with custom mask_prob, random_token_prob, and leave_unmasked_prob settings', 'create a VocabularyDatasetBinarizer from a vocabulary to binarize raw text data for training', 'test the FileBinarizer multiprocess_dataset method to binarize input files with mmap implementation', 'test the MultilingualDenoisingTask to verify masked tokens match original tokens after denoising', 'run the unittest for multilingual denoising with BART base architecture and word-level masking', 'test the VocabularyDatasetBinarizer by binarizing raw text data with a built vocabulary', 'test FileBinarizer.multiprocess_dataset to binarize input files using mmap dataset implementation', 'test the MultilingualDenoisingTask batch iterator to verify masked source tokens and target alignment', 'test the SpanMaskedLMTask to verify it correctly masks token spans with sentinel tokens', 'run the test_masks_token_spans unit test to validate span masking behavior in fairseq', 'review the TestSpanMaskedLM class and its test_masks_token_spans method for span masking logic', 'test the VocabularyDatasetBinarizer used with SpanMaskedLMTask for binarizing raw text data', 'test the SpanMaskedLMTask get_batch_iterator to verify masked source and target token alignment']
```

Usage

```
{'test_denoising_task': 'test the DenoisingTask class to verify masked tokens match original tokens', 'run_denoising_unit_test': 'run the unittest for fairseq denoising task with BART base architecture', 'test_filebinarizer_multiprocess': 'test FileBinarizer.multiprocess_dataset to binarize raw text data with mmap implementation', 'test_vocabulary_dataset_binarizer': 'test VocabularyDatasetBinarizer to convert raw text tokens into binarized dataset format', 'test_denoising_batch_iterator': 'test the batch iterator for masked datasets with max tokens and positions constraints'}
```

## File: facebookresearch_fairseq/tests/tasks/test_masked_lm.py

Prompts

```
['test the DenoisingTask class to verify masked tokens match original tokens', 'run the unittest for fairseq denoising task with BART base architecture', 'test FileBinarizer.multiprocess_dataset to binarize raw text data with mmap implementation', 'test VocabularyDatasetBinarizer to convert raw text tokens into binarized dataset format', 'test the batch iterator for masked datasets with max tokens and positions constraints', 'test the MaskedLMTask to verify masked tokens match original tokens correctly', 'run the unit test that validates token masking behavior in the masked language model task', 'build a MaskedLMConfig with custom mask_prob, random_token_prob, and leave_unmasked_prob settings', 'create a VocabularyDatasetBinarizer from a vocabulary to binarize raw text data for training', 'test the FileBinarizer multiprocess_dataset method to binarize input files with mmap implementation', 'test the MultilingualDenoisingTask to verify masked tokens match original tokens after denoising', 'run the unittest for multilingual denoising with BART base architecture and word-level masking', 'test the VocabularyDatasetBinarizer by binarizing raw text data with a built vocabulary', 'test FileBinarizer.multiprocess_dataset to binarize input files using mmap dataset implementation', 'test the MultilingualDenoisingTask batch iterator to verify masked source tokens and target alignment', 'test the SpanMaskedLMTask to verify it correctly masks token spans with sentinel tokens', 'run the test_masks_token_spans unit test to validate span masking behavior in fairseq', 'review the TestSpanMaskedLM class and its test_masks_token_spans method for span masking logic', 'test the VocabularyDatasetBinarizer used with SpanMaskedLMTask for binarizing raw text data', 'test the SpanMaskedLMTask get_batch_iterator to verify masked source and target token alignment']
```

Usage

```
{'test_MaskedLM_task': 'test the MaskedLMTask to verify masked tokens match original tokens correctly', 'run_MaskedLM_test': 'run the unit test that validates token masking behavior in the masked language model task', 'build_MaskedLMConfig': 'build a MaskedLMConfig with custom mask_prob, random_token_prob, and leave_unmasked_prob settings', 'create_VocabularyDatasetBinarizer': 'create a VocabularyDatasetBinarizer from a vocabulary to binarize raw text data for training', 'test_FileBinarizer_multiprocess': 'test the FileBinarizer multiprocess_dataset method to binarize input files with mmap implementation'}
```

## File: facebookresearch_fairseq/tests/tasks/test_multilingual_denoising.py

Prompts

```
['test the DenoisingTask class to verify masked tokens match original tokens', 'run the unittest for fairseq denoising task with BART base architecture', 'test FileBinarizer.multiprocess_dataset to binarize raw text data with mmap implementation', 'test VocabularyDatasetBinarizer to convert raw text tokens into binarized dataset format', 'test the batch iterator for masked datasets with max tokens and positions constraints', 'test the MaskedLMTask to verify masked tokens match original tokens correctly', 'run the unit test that validates token masking behavior in the masked language model task', 'build a MaskedLMConfig with custom mask_prob, random_token_prob, and leave_unmasked_prob settings', 'create a VocabularyDatasetBinarizer from a vocabulary to binarize raw text data for training', 'test the FileBinarizer multiprocess_dataset method to binarize input files with mmap implementation', 'test the MultilingualDenoisingTask to verify masked tokens match original tokens after denoising', 'run the unittest for multilingual denoising with BART base architecture and word-level masking', 'test the VocabularyDatasetBinarizer by binarizing raw text data with a built vocabulary', 'test FileBinarizer.multiprocess_dataset to binarize input files using mmap dataset implementation', 'test the MultilingualDenoisingTask batch iterator to verify masked source tokens and target alignment', 'test the SpanMaskedLMTask to verify it correctly masks token spans with sentinel tokens', 'run the test_masks_token_spans unit test to validate span masking behavior in fairseq', 'review the TestSpanMaskedLM class and its test_masks_token_spans method for span masking logic', 'test the VocabularyDatasetBinarizer used with SpanMaskedLMTask for binarizing raw text data', 'test the SpanMaskedLMTask get_batch_iterator to verify masked source and target token alignment']
```

Usage

```
{'test_multilingual_denoising_task': 'test the MultilingualDenoisingTask to verify masked tokens match original tokens after denoising', 'run_test_multilingual_denoising': 'run the unittest for multilingual denoising with BART base architecture and word-level masking', 'test_VocabularyDatasetBinarizer': 'test the VocabularyDatasetBinarizer by binarizing raw text data with a built vocabulary', 'test_FileBinarizer_multiprocess_dataset': 'test FileBinarizer.multiprocess_dataset to binarize input files using mmap dataset implementation', 'test_MultilingualDenoisingTask_batch_iterator': 'test the MultilingualDenoisingTask batch iterator to verify masked source tokens and target alignment'}
```

## File: facebookresearch_fairseq/tests/tasks/test_span_masked_lm.py

Prompts

```
['test the DenoisingTask class to verify masked tokens match original tokens', 'run the unittest for fairseq denoising task with BART base architecture', 'test FileBinarizer.multiprocess_dataset to binarize raw text data with mmap implementation', 'test VocabularyDatasetBinarizer to convert raw text tokens into binarized dataset format', 'test the batch iterator for masked datasets with max tokens and positions constraints', 'test the MaskedLMTask to verify masked tokens match original tokens correctly', 'run the unit test that validates token masking behavior in the masked language model task', 'build a MaskedLMConfig with custom mask_prob, random_token_prob, and leave_unmasked_prob settings', 'create a VocabularyDatasetBinarizer from a vocabulary to binarize raw text data for training', 'test the FileBinarizer multiprocess_dataset method to binarize input files with mmap implementation', 'test the MultilingualDenoisingTask to verify masked tokens match original tokens after denoising', 'run the unittest for multilingual denoising with BART base architecture and word-level masking', 'test the VocabularyDatasetBinarizer by binarizing raw text data with a built vocabulary', 'test FileBinarizer.multiprocess_dataset to binarize input files using mmap dataset implementation', 'test the MultilingualDenoisingTask batch iterator to verify masked source tokens and target alignment', 'test the SpanMaskedLMTask to verify it correctly masks token spans with sentinel tokens', 'run the test_masks_token_spans unit test to validate span masking behavior in fairseq', 'review the TestSpanMaskedLM class and its test_masks_token_spans method for span masking logic', 'test the VocabularyDatasetBinarizer used with SpanMaskedLMTask for binarizing raw text data', 'test the SpanMaskedLMTask get_batch_iterator to verify masked source and target token alignment']
```

Usage

```
{'test_span_masked_lm_task': 'test the SpanMaskedLMTask to verify it correctly masks token spans with sentinel tokens', 'run_test_masks_token_spans': 'run the test_masks_token_spans unit test to validate span masking behavior in fairseq', 'review_TestSpanMaskedLM_class': 'review the TestSpanMaskedLM class and its test_masks_token_spans method for span masking logic', 'test_VocabularyDatasetBinarizer_with_span_masked_lm': 'test the VocabularyDatasetBinarizer used with SpanMaskedLMTask for binarizing raw text data', 'test_SpanMaskedLMTask_batch_iterator': 'test the SpanMaskedLMTask get_batch_iterator to verify masked source and target token alignment'}
```

