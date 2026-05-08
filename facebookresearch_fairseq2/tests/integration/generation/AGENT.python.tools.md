# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/integration/generation/test_incremental_decode.py

Prompts

```
['test that incremental decoding with IncrementalStateBag produces logits matching full-sequence decoding', 'run the NLLB model on padded source and target sequences to generate logits', 'create a source or target token encoder for a specific language and task', 'pad a list of token index sequences with a specified pad value and get their layout', 'use an IncrementalStateBag to track decoder state across incremental decoding steps', 'test greedy sampling translation using TopKSampler with k=1 on an NLLB model', 'run a TopKSampler with k=1 to perform greedy decoding for sequence generation', 'run a SamplingSeq2SeqGenerator with a model, vocab info, and sampler for text generation', 'run a TextTranslator to batch translate English sentences to German using an NLLB model', 'run the NLLB model hub to load a pretrained model and tokenizer by name', 'test the BannedSequenceProcessor to verify banned token sequences are excluded during beam search generation', 'test the BeamSearchSeq2SeqGenerator with BannedSequenceProcessor step processors to filter output tokens', 'test the TextTranslator batch_translate method with banned sequence constraints for English to Spanish translation', 'test loading the nllb-200_dense_distill_600m model and tokenizer from the NLLB model hub', 'test creating a raw text encoder from the NLLB tokenizer for encoding banned word sequences']
```

Usage

```
{'test_incremental_decoding': 'test that incremental decoding with IncrementalStateBag produces logits matching full-sequence decoding', 'run_nllb_model_inference': 'run the NLLB model on padded source and target sequences to generate logits', 'create_nllb_tokenizer_encoder': 'create a source or target token encoder for a specific language and task', 'pad_token_sequences': 'pad a list of token index sequences with a specified pad value and get their layout', 'use_incremental_state_bag': 'use an IncrementalStateBag to track decoder state across incremental decoding steps'}
```

## File: facebookresearch_fairseq2/tests/integration/generation/test_sampling.py

Prompts

```
['test that incremental decoding with IncrementalStateBag produces logits matching full-sequence decoding', 'run the NLLB model on padded source and target sequences to generate logits', 'create a source or target token encoder for a specific language and task', 'pad a list of token index sequences with a specified pad value and get their layout', 'use an IncrementalStateBag to track decoder state across incremental decoding steps', 'test greedy sampling translation using TopKSampler with k=1 on an NLLB model', 'run a TopKSampler with k=1 to perform greedy decoding for sequence generation', 'run a SamplingSeq2SeqGenerator with a model, vocab info, and sampler for text generation', 'run a TextTranslator to batch translate English sentences to German using an NLLB model', 'run the NLLB model hub to load a pretrained model and tokenizer by name', 'test the BannedSequenceProcessor to verify banned token sequences are excluded during beam search generation', 'test the BeamSearchSeq2SeqGenerator with BannedSequenceProcessor step processors to filter output tokens', 'test the TextTranslator batch_translate method with banned sequence constraints for English to Spanish translation', 'test loading the nllb-200_dense_distill_600m model and tokenizer from the NLLB model hub', 'test creating a raw text encoder from the NLLB tokenizer for encoding banned word sequences']
```

Usage

```
{'test_greedy_sampling': 'test greedy sampling translation using TopKSampler with k=1 on an NLLB model', 'run_TopKSampler': 'run a TopKSampler with k=1 to perform greedy decoding for sequence generation', 'run_SamplingSeq2SeqGenerator': 'run a SamplingSeq2SeqGenerator with a model, vocab info, and sampler for text generation', 'run_TextTranslator': 'run a TextTranslator to batch translate English sentences to German using an NLLB model', 'run_nllb_model_hub': 'run the NLLB model hub to load a pretrained model and tokenizer by name'}
```

## File: facebookresearch_fairseq2/tests/integration/generation/test_step_processor.py

Prompts

```
['test that incremental decoding with IncrementalStateBag produces logits matching full-sequence decoding', 'run the NLLB model on padded source and target sequences to generate logits', 'create a source or target token encoder for a specific language and task', 'pad a list of token index sequences with a specified pad value and get their layout', 'use an IncrementalStateBag to track decoder state across incremental decoding steps', 'test greedy sampling translation using TopKSampler with k=1 on an NLLB model', 'run a TopKSampler with k=1 to perform greedy decoding for sequence generation', 'run a SamplingSeq2SeqGenerator with a model, vocab info, and sampler for text generation', 'run a TextTranslator to batch translate English sentences to German using an NLLB model', 'run the NLLB model hub to load a pretrained model and tokenizer by name', 'test the BannedSequenceProcessor to verify banned token sequences are excluded during beam search generation', 'test the BeamSearchSeq2SeqGenerator with BannedSequenceProcessor step processors to filter output tokens', 'test the TextTranslator batch_translate method with banned sequence constraints for English to Spanish translation', 'test loading the nllb-200_dense_distill_600m model and tokenizer from the NLLB model hub', 'test creating a raw text encoder from the NLLB tokenizer for encoding banned word sequences']
```

Usage

```
{'test_BannedSequenceProcessor': 'test the BannedSequenceProcessor to verify banned token sequences are excluded during beam search generation', 'test_BeamSearchSeq2SeqGenerator_with_step_processors': 'test the BeamSearchSeq2SeqGenerator with BannedSequenceProcessor step processors to filter output tokens', 'test_TextTranslator_batch_translate': 'test the TextTranslator batch_translate method with banned sequence constraints for English to Spanish translation', 'test_NLLB_model_loading': 'test loading the nllb-200_dense_distill_600m model and tokenizer from the NLLB model hub', 'test_create_raw_encoder': 'test creating a raw text encoder from the NLLB tokenizer for encoding banned word sequences'}
```

