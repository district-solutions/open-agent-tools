# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/tests/speech_recognition/asr_test_base.py

Prompts

```
['create a dummy Fairseq Dictionary with a specified vocabulary size for testing', 'create a dummy Fairseq task and argument parser to facilitate model and criterion testing', 'create dummy forward input tensors with random features, source lengths, and previous output tokens', 'test a FairseqEncoderDecoderModel subclass by running forward pass and checking normalized probability output', 'test a FairseqEncoderModel subclass by running forward pass and validating encoder output structure', 'test the Seq2SeqCollater collate method to batch speech recognition samples by frame length', 'run the unittest suite for Seq2SeqCollater to verify batch creation and padding behavior', 'review the TestSeq2SeqCollator class and its test_collate method for speech recognition data collation', 'create a Seq2SeqCollater instance to collate speech frames and targets into a padded batch', 'summarize the test_collate test case that validates sorting, padding, and token counting in batches', 'test the CrossEntropyWithAccCriterion class to verify correct predictions are counted accurately', 'test the CrossEntropyWithAccCriterion class to verify incorrect predictions are counted accurately', 'review the CrossEntropyWithAccCriterionTest class and its test methods for speech recognition criteria', 'summarize the CrossEntropyWithAccCriterionTest class and its cross-entropy accuracy test methods', 'refactor the CrossEntropyWithAccCriterionTest class to add additional test cases for edge cases', 'test the VGGTransformerModel mid configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel big configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel base configuration with 3 transformer layers and reduced dimensions', 'test the VGGTransformerEncoder with standard, limited context, and windowed sampling configurations', 'test the TransformerDecoder with a dummy dictionary and encoder output tokens']
```

Usage

```
{'create_dummy_dictionary': 'create a dummy Fairseq Dictionary with a specified vocabulary size for testing', 'create_dummy_task_and_parser': 'create a dummy Fairseq task and argument parser to facilitate model and criterion testing', 'create_dummy_input': 'create dummy forward input tensors with random features, source lengths, and previous output tokens', 'test_encoder_decoder_model': 'test a FairseqEncoderDecoderModel subclass by running forward pass and checking normalized probability output', 'test_encoder_model': 'test a FairseqEncoderModel subclass by running forward pass and validating encoder output structure'}
```

## File: facebookresearch_fairseq/tests/speech_recognition/test_collaters.py

Prompts

```
['create a dummy Fairseq Dictionary with a specified vocabulary size for testing', 'create a dummy Fairseq task and argument parser to facilitate model and criterion testing', 'create dummy forward input tensors with random features, source lengths, and previous output tokens', 'test a FairseqEncoderDecoderModel subclass by running forward pass and checking normalized probability output', 'test a FairseqEncoderModel subclass by running forward pass and validating encoder output structure', 'test the Seq2SeqCollater collate method to batch speech recognition samples by frame length', 'run the unittest suite for Seq2SeqCollater to verify batch creation and padding behavior', 'review the TestSeq2SeqCollator class and its test_collate method for speech recognition data collation', 'create a Seq2SeqCollater instance to collate speech frames and targets into a padded batch', 'summarize the test_collate test case that validates sorting, padding, and token counting in batches', 'test the CrossEntropyWithAccCriterion class to verify correct predictions are counted accurately', 'test the CrossEntropyWithAccCriterion class to verify incorrect predictions are counted accurately', 'review the CrossEntropyWithAccCriterionTest class and its test methods for speech recognition criteria', 'summarize the CrossEntropyWithAccCriterionTest class and its cross-entropy accuracy test methods', 'refactor the CrossEntropyWithAccCriterionTest class to add additional test cases for edge cases', 'test the VGGTransformerModel mid configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel big configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel base configuration with 3 transformer layers and reduced dimensions', 'test the VGGTransformerEncoder with standard, limited context, and windowed sampling configurations', 'test the TransformerDecoder with a dummy dictionary and encoder output tokens']
```

Usage

```
{'test_seq2seq_collater_collate': 'test the Seq2SeqCollater collate method to batch speech recognition samples by frame length', 'run_seq2seq_collator_unit_tests': 'run the unittest suite for Seq2SeqCollater to verify batch creation and padding behavior', 'review_testseq2seqcollator_class': 'review the TestSeq2SeqCollator class and its test_collate method for speech recognition data collation', 'create_seq2seq_collater_batch': 'create a Seq2SeqCollater instance to collate speech frames and targets into a padded batch', 'summarize_collater_test': 'summarize the test_collate test case that validates sorting, padding, and token counting in batches'}
```

## File: facebookresearch_fairseq/tests/speech_recognition/test_cross_entropy.py

Prompts

```
['create a dummy Fairseq Dictionary with a specified vocabulary size for testing', 'create a dummy Fairseq task and argument parser to facilitate model and criterion testing', 'create dummy forward input tensors with random features, source lengths, and previous output tokens', 'test a FairseqEncoderDecoderModel subclass by running forward pass and checking normalized probability output', 'test a FairseqEncoderModel subclass by running forward pass and validating encoder output structure', 'test the Seq2SeqCollater collate method to batch speech recognition samples by frame length', 'run the unittest suite for Seq2SeqCollater to verify batch creation and padding behavior', 'review the TestSeq2SeqCollator class and its test_collate method for speech recognition data collation', 'create a Seq2SeqCollater instance to collate speech frames and targets into a padded batch', 'summarize the test_collate test case that validates sorting, padding, and token counting in batches', 'test the CrossEntropyWithAccCriterion class to verify correct predictions are counted accurately', 'test the CrossEntropyWithAccCriterion class to verify incorrect predictions are counted accurately', 'review the CrossEntropyWithAccCriterionTest class and its test methods for speech recognition criteria', 'summarize the CrossEntropyWithAccCriterionTest class and its cross-entropy accuracy test methods', 'refactor the CrossEntropyWithAccCriterionTest class to add additional test cases for edge cases', 'test the VGGTransformerModel mid configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel big configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel base configuration with 3 transformer layers and reduced dimensions', 'test the VGGTransformerEncoder with standard, limited context, and windowed sampling configurations', 'test the TransformerDecoder with a dummy dictionary and encoder output tokens']
```

Usage

```
{'test_cross_entropy_all_correct': 'test the CrossEntropyWithAccCriterion class to verify correct predictions are counted accurately', 'test_cross_entropy_all_wrong': 'test the CrossEntropyWithAccCriterion class to verify incorrect predictions are counted accurately', 'review_CrossEntropyWithAccCriterionTest': 'review the CrossEntropyWithAccCriterionTest class and its test methods for speech recognition criteria', 'summarize_CrossEntropyWithAccCriterionTest': 'summarize the CrossEntropyWithAccCriterionTest class and its cross-entropy accuracy test methods', 'refactor_CrossEntropyWithAccCriterionTest': 'refactor the CrossEntropyWithAccCriterionTest class to add additional test cases for edge cases'}
```

## File: facebookresearch_fairseq/tests/speech_recognition/test_vggtransformer.py

Prompts

```
['create a dummy Fairseq Dictionary with a specified vocabulary size for testing', 'create a dummy Fairseq task and argument parser to facilitate model and criterion testing', 'create dummy forward input tensors with random features, source lengths, and previous output tokens', 'test a FairseqEncoderDecoderModel subclass by running forward pass and checking normalized probability output', 'test a FairseqEncoderModel subclass by running forward pass and validating encoder output structure', 'test the Seq2SeqCollater collate method to batch speech recognition samples by frame length', 'run the unittest suite for Seq2SeqCollater to verify batch creation and padding behavior', 'review the TestSeq2SeqCollator class and its test_collate method for speech recognition data collation', 'create a Seq2SeqCollater instance to collate speech frames and targets into a padded batch', 'summarize the test_collate test case that validates sorting, padding, and token counting in batches', 'test the CrossEntropyWithAccCriterion class to verify correct predictions are counted accurately', 'test the CrossEntropyWithAccCriterion class to verify incorrect predictions are counted accurately', 'review the CrossEntropyWithAccCriterionTest class and its test methods for speech recognition criteria', 'summarize the CrossEntropyWithAccCriterionTest class and its cross-entropy accuracy test methods', 'refactor the CrossEntropyWithAccCriterionTest class to add additional test cases for edge cases', 'test the VGGTransformerModel mid configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel big configuration with 3 transformer layers for fast turnaround', 'test the VGGTransformerModel base configuration with 3 transformer layers and reduced dimensions', 'test the VGGTransformerEncoder with standard, limited context, and windowed sampling configurations', 'test the TransformerDecoder with a dummy dictionary and encoder output tokens']
```

Usage

```
{'test_VGGTransformerModel_mid': 'test the VGGTransformerModel mid configuration with 3 transformer layers for fast turnaround', 'test_VGGTransformerModel_big': 'test the VGGTransformerModel big configuration with 3 transformer layers for fast turnaround', 'test_VGGTransformerModel_base': 'test the VGGTransformerModel base configuration with 3 transformer layers and reduced dimensions', 'test_VGGTransformerEncoder': 'test the VGGTransformerEncoder with standard, limited context, and windowed sampling configurations', 'test_TransformerDecoder': 'test the TransformerDecoder with a dummy dictionary and encoder output tokens'}
```

