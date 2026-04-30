# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/fsmt/convert_fsmt_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a fairseq FSMT checkpoint to a PyTorch HuggingFace FSMT model with vocab files and config', 'run the CLI script to convert a fairseq FSMT checkpoint to HuggingFace PyTorch format', 'rewrite fairseq dictionary keys by stripping @@ word-breaking symbols and adding </w> word-ending tokens', 'build best-score hyperparameter defaults for length_penalty across supported WMT FSMT models', 'summarize the organization name mapping for all supported fairseq and allenai FSMT models', 'build an FSMT translation model using FSMTForConditionalGeneration for ru-en, en-ru, de-en, or en-de machine translation', 'create an FSMTModel encoder-decoder architecture with separate source and target vocabularies and sinusoidal positional embeddings', 'test the multi-headed Attention class with encoder-decoder attention and causal masking for seq2seq translation', 'run beam search translation generation with FSMTForConditionalGeneration using num_beams and early_stopping parameters', 'review the SinusoidalPositionalEmbedding class that generates deterministic positional embeddings with automatic expansion', 'create an FSMTTokenizer instance with source and target language vocabularies and merge rules for machine translation', 'build a tokenization pipeline that applies Moses preprocessing, BPE encoding, and language-specific tokenization', 'run byte-pair encoding on a token to split it into subword tokens using the vocabulary merge ranks', 'save the source vocabulary, target vocabulary, and BPE merge files to a directory for model serialization', 'test Moses text preprocessing including unicode punctuation replacement and non-printing character removal']
```

Usage

```
{'convert_fsmt_checkpoint_to_pytorch': 'convert a fairseq FSMT checkpoint to a PyTorch HuggingFace FSMT model with vocab files and config', 'run_convert_cli': 'run the CLI script to convert a fairseq FSMT checkpoint to HuggingFace PyTorch format', 'rewrite_dict_keys': 'rewrite fairseq dictionary keys by stripping @@ word-breaking symbols and adding </w> word-ending tokens', 'build_best_score_hparams': 'build best-score hyperparameter defaults for length_penalty across supported WMT FSMT models', 'summarize_org_names': 'summarize the organization name mapping for all supported fairseq and allenai FSMT models'}
```

## File: huggingface_transformers/src/transformers/models/fsmt/modeling_fsmt.py

Prompts

```
['convert a fairseq FSMT checkpoint to a PyTorch HuggingFace FSMT model with vocab files and config', 'run the CLI script to convert a fairseq FSMT checkpoint to HuggingFace PyTorch format', 'rewrite fairseq dictionary keys by stripping @@ word-breaking symbols and adding </w> word-ending tokens', 'build best-score hyperparameter defaults for length_penalty across supported WMT FSMT models', 'summarize the organization name mapping for all supported fairseq and allenai FSMT models', 'build an FSMT translation model using FSMTForConditionalGeneration for ru-en, en-ru, de-en, or en-de machine translation', 'create an FSMTModel encoder-decoder architecture with separate source and target vocabularies and sinusoidal positional embeddings', 'test the multi-headed Attention class with encoder-decoder attention and causal masking for seq2seq translation', 'run beam search translation generation with FSMTForConditionalGeneration using num_beams and early_stopping parameters', 'review the SinusoidalPositionalEmbedding class that generates deterministic positional embeddings with automatic expansion', 'create an FSMTTokenizer instance with source and target language vocabularies and merge rules for machine translation', 'build a tokenization pipeline that applies Moses preprocessing, BPE encoding, and language-specific tokenization', 'run byte-pair encoding on a token to split it into subword tokens using the vocabulary merge ranks', 'save the source vocabulary, target vocabulary, and BPE merge files to a directory for model serialization', 'test Moses text preprocessing including unicode punctuation replacement and non-printing character removal']
```

Usage

```
{'build_fsmt_translation_model': 'build an FSMT translation model using FSMTForConditionalGeneration for ru-en, en-ru, de-en, or en-de machine translation', 'create_fsmt_encoder_decoder': 'create an FSMTModel encoder-decoder architecture with separate source and target vocabularies and sinusoidal positional embeddings', 'test_attention_mechanism': 'test the multi-headed Attention class with encoder-decoder attention and causal masking for seq2seq translation', 'run_beam_search_translation': 'run beam search translation generation with FSMTForConditionalGeneration using num_beams and early_stopping parameters', 'review_sinusoidal_embeddings': 'review the SinusoidalPositionalEmbedding class that generates deterministic positional embeddings with automatic expansion'}
```

## File: huggingface_transformers/src/transformers/models/fsmt/tokenization_fsmt.py

Prompts

```
['convert a fairseq FSMT checkpoint to a PyTorch HuggingFace FSMT model with vocab files and config', 'run the CLI script to convert a fairseq FSMT checkpoint to HuggingFace PyTorch format', 'rewrite fairseq dictionary keys by stripping @@ word-breaking symbols and adding </w> word-ending tokens', 'build best-score hyperparameter defaults for length_penalty across supported WMT FSMT models', 'summarize the organization name mapping for all supported fairseq and allenai FSMT models', 'build an FSMT translation model using FSMTForConditionalGeneration for ru-en, en-ru, de-en, or en-de machine translation', 'create an FSMTModel encoder-decoder architecture with separate source and target vocabularies and sinusoidal positional embeddings', 'test the multi-headed Attention class with encoder-decoder attention and causal masking for seq2seq translation', 'run beam search translation generation with FSMTForConditionalGeneration using num_beams and early_stopping parameters', 'review the SinusoidalPositionalEmbedding class that generates deterministic positional embeddings with automatic expansion', 'create an FSMTTokenizer instance with source and target language vocabularies and merge rules for machine translation', 'build a tokenization pipeline that applies Moses preprocessing, BPE encoding, and language-specific tokenization', 'run byte-pair encoding on a token to split it into subword tokens using the vocabulary merge ranks', 'save the source vocabulary, target vocabulary, and BPE merge files to a directory for model serialization', 'test Moses text preprocessing including unicode punctuation replacement and non-printing character removal']
```

Usage

```
{'create_FSMTTokenizer': 'create an FSMTTokenizer instance with source and target language vocabularies and merge rules for machine translation', 'build_tokenization_pipeline': 'build a tokenization pipeline that applies Moses preprocessing, BPE encoding, and language-specific tokenization', 'run_bpe_encoding': 'run byte-pair encoding on a token to split it into subword tokens using the vocabulary merge ranks', 'save_vocabulary': 'save the source vocabulary, target vocabulary, and BPE merge files to a directory for model serialization', 'test_moses_preprocessing': 'test Moses text preprocessing including unicode punctuation replacement and non-printing character removal'}
```

