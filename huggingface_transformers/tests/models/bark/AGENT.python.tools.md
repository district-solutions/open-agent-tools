# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/bark/test_modeling_bark.py

Prompts

```
['test the BarkSemanticModel with config and input tensors for decoder past with large inputs', 'test the BarkCoarseModel with config and input tensors for decoder past with large inputs', 'test the BarkFineModel with codebook embeddings and resize token embeddings for each codebook', 'run integration tests for BarkModel end-to-end generation using the suno/bark pretrained model', 'test Bark model generation in FP16 precision with beam search and sampling parameters', 'test that BarkProcessor can save and reload from a local directory with matching vocab', 'test BarkProcessor speaker embeddings by passing voice presets as dicts, npz files, or hub presets', 'test BarkProcessor text encoding matches the underlying tokenizer output with padding and attention masks', 'test BarkProcessor save and load with speaker embeddings, custom BOS and EOS tokens', 'verify and remove unavailable speaker embeddings from a BarkProcessor before saving to disk']
```

Usage

```
{'test_bark_semantic_model': 'test the BarkSemanticModel with config and input tensors for decoder past with large inputs', 'test_bark_coarse_model': 'test the BarkCoarseModel with config and input tensors for decoder past with large inputs', 'test_bark_fine_model': 'test the BarkFineModel with codebook embeddings and resize token embeddings for each codebook', 'test_bark_model_integration': 'run integration tests for BarkModel end-to-end generation using the suno/bark pretrained model', 'test_bark_generation_fp16': 'test Bark model generation in FP16 precision with beam search and sampling parameters'}
```

## File: huggingface_transformers/tests/models/bark/test_processing_bark.py

Prompts

```
['test the BarkSemanticModel with config and input tensors for decoder past with large inputs', 'test the BarkCoarseModel with config and input tensors for decoder past with large inputs', 'test the BarkFineModel with codebook embeddings and resize token embeddings for each codebook', 'run integration tests for BarkModel end-to-end generation using the suno/bark pretrained model', 'test Bark model generation in FP16 precision with beam search and sampling parameters', 'test that BarkProcessor can save and reload from a local directory with matching vocab', 'test BarkProcessor speaker embeddings by passing voice presets as dicts, npz files, or hub presets', 'test BarkProcessor text encoding matches the underlying tokenizer output with padding and attention masks', 'test BarkProcessor save and load with speaker embeddings, custom BOS and EOS tokens', 'verify and remove unavailable speaker embeddings from a BarkProcessor before saving to disk']
```

Usage

```
{'test_bark_processor_save_load': 'test that BarkProcessor can save and reload from a local directory with matching vocab', 'test_bark_processor_speaker_embeddings': 'test BarkProcessor speaker embeddings by passing voice presets as dicts, npz files, or hub presets', 'test_bark_processor_tokenizer': 'test BarkProcessor text encoding matches the underlying tokenizer output with padding and attention masks', 'test_bark_processor_additional_features': 'test BarkProcessor save and load with speaker embeddings, custom BOS and EOS tokens', 'verify_bark_speaker_embeddings': 'verify and remove unavailable speaker embeddings from a BarkProcessor before saving to disk'}
```

