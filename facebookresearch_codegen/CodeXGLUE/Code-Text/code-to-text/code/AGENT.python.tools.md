# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/CodeXGLUE/Code-Text/code-to-text/code/bleu.py

Prompts

```
['compute the BLEU score of a candidate sentence against a list of reference sentences', 'normalize and tokenize text using NIST-style preprocessing for machine translation evaluation', 'count n-grams of a given order in a list of words and return their frequencies', 'preprocess a list of reference sentences into a form usable for BLEU scoring', 'preprocess a candidate test sentence against cooked references to prepare for BLEU scoring', 'build a Seq2Seq model with an encoder, decoder, and config for code-to-text generation', 'run beam search inference on source code to generate natural language descriptions', 'create a Beam object with a specified size, start symbol, and end symbol', 'review the Seq2Seq forward pass that computes loss or generates predictions', 'test the Beam advance method to update scores and backpointers during search', 'run training for a code-to-text model using RoBERTa or XLM encoder with a transformer decoder', 'run evaluation on a dev set computing perplexity and BLEU-4 scores for code-to-text generation', 'run inference on test files to generate docstrings from source code and compute BLEU-4', 'read code and docstring pairs from a JSONL file into Example objects for training or testing', 'convert code and docstring examples into tokenized InputFeatures with padding and masks for the model']
```

Usage

```
{'compute_bleu_score': 'compute the BLEU score of a candidate sentence against a list of reference sentences', 'normalize_and_tokenize_text': 'normalize and tokenize text using NIST-style preprocessing for machine translation evaluation', 'count_ngrams_in_words': 'count n-grams of a given order in a list of words and return their frequencies', 'cook_reference_sentences': 'preprocess a list of reference sentences into a form usable for BLEU scoring', 'cook_test_sentence': 'preprocess a candidate test sentence against cooked references to prepare for BLEU scoring'}
```

## File: facebookresearch_codegen/CodeXGLUE/Code-Text/code-to-text/code/model.py

Prompts

```
['compute the BLEU score of a candidate sentence against a list of reference sentences', 'normalize and tokenize text using NIST-style preprocessing for machine translation evaluation', 'count n-grams of a given order in a list of words and return their frequencies', 'preprocess a list of reference sentences into a form usable for BLEU scoring', 'preprocess a candidate test sentence against cooked references to prepare for BLEU scoring', 'build a Seq2Seq model with an encoder, decoder, and config for code-to-text generation', 'run beam search inference on source code to generate natural language descriptions', 'create a Beam object with a specified size, start symbol, and end symbol', 'review the Seq2Seq forward pass that computes loss or generates predictions', 'test the Beam advance method to update scores and backpointers during search', 'run training for a code-to-text model using RoBERTa or XLM encoder with a transformer decoder', 'run evaluation on a dev set computing perplexity and BLEU-4 scores for code-to-text generation', 'run inference on test files to generate docstrings from source code and compute BLEU-4', 'read code and docstring pairs from a JSONL file into Example objects for training or testing', 'convert code and docstring examples into tokenized InputFeatures with padding and masks for the model']
```

Usage

```
{'build_seq2seq_model': 'build a Seq2Seq model with an encoder, decoder, and config for code-to-text generation', 'run_beam_search': 'run beam search inference on source code to generate natural language descriptions', 'create_beam_search': 'create a Beam object with a specified size, start symbol, and end symbol', 'review_forward_pass': 'review the Seq2Seq forward pass that computes loss or generates predictions', 'test_beam_advance': 'test the Beam advance method to update scores and backpointers during search'}
```

## File: facebookresearch_codegen/CodeXGLUE/Code-Text/code-to-text/code/run.py

Prompts

```
['compute the BLEU score of a candidate sentence against a list of reference sentences', 'normalize and tokenize text using NIST-style preprocessing for machine translation evaluation', 'count n-grams of a given order in a list of words and return their frequencies', 'preprocess a list of reference sentences into a form usable for BLEU scoring', 'preprocess a candidate test sentence against cooked references to prepare for BLEU scoring', 'build a Seq2Seq model with an encoder, decoder, and config for code-to-text generation', 'run beam search inference on source code to generate natural language descriptions', 'create a Beam object with a specified size, start symbol, and end symbol', 'review the Seq2Seq forward pass that computes loss or generates predictions', 'test the Beam advance method to update scores and backpointers during search', 'run training for a code-to-text model using RoBERTa or XLM encoder with a transformer decoder', 'run evaluation on a dev set computing perplexity and BLEU-4 scores for code-to-text generation', 'run inference on test files to generate docstrings from source code and compute BLEU-4', 'read code and docstring pairs from a JSONL file into Example objects for training or testing', 'convert code and docstring examples into tokenized InputFeatures with padding and masks for the model']
```

Usage

```
{'run_code_to_text_training': 'run training for a code-to-text model using RoBERTa or XLM encoder with a transformer decoder', 'run_code_to_text_evaluation': 'run evaluation on a dev set computing perplexity and BLEU-4 scores for code-to-text generation', 'run_code_to_text_testing': 'run inference on test files to generate docstrings from source code and compute BLEU-4', 'read_examples_from_jsonl': 'read code and docstring pairs from a JSONL file into Example objects for training or testing', 'convert_examples_to_features': 'convert code and docstring examples into tokenized InputFeatures with padding and masks for the model'}
```

