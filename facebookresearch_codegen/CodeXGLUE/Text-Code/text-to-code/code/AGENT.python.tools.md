# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/CodeXGLUE/Text-Code/text-to-code/code/beam.py

Prompts

```
['build a Seq2Seq model with an encoder, decoder, and config for text-to-code generation', 'run beam search decoding on source sequences using the Seq2Seq forward method', 'create a Beam object with a given size, start symbol, and end symbol', 'advance the Beam state with word log-probabilities to update the search', 'build target token sequences from beam hypotheses by filtering out EOS tokens', 'compute the BLEU score of translated segments against one or more reference corpora', 'compute the BLEU score with Lin et al 2004 smoothing applied to n-gram precisions', 'extract all n-grams up to a given maximum order from an input text segment', 'compute the BLEU score from a reference file and a translation file', 'review the Python implementation of BLEU and smooth-BLEU scoring for machine translation evaluation', 'create a concodeDataset instance to load and tokenize natural language to code pairs from a JSON file', 'pad and truncate natural language and code token sequences to a fixed block size with label masks', 'cache tokenized input features and labels as a pickle file to avoid reprocessing the dataset', 'shard the dataset across distributed workers by filtering samples based on process rank and world size', 'get a single training sample as a pair of PyTorch tensors containing input IDs and token labels', 'train a text to code generation model using GPT-2 or RoBERTa on the CodeXGLUE dataset', 'evaluate the trained model on the dev set and compute perplexity scores', 'evaluate code generation quality using BLEU score and exact match on dev or test set', 'run beam search inference to generate code from natural language descriptions', 'load a pretrained model and resume training from the last saved checkpoint']
```

Usage

```
{'build_seq2seq_model': 'build a Seq2Seq model with an encoder, decoder, and config for text-to-code generation', 'run_beam_search': 'run beam search decoding on source sequences using the Seq2Seq forward method', 'create_beam': 'create a Beam object with a given size, start symbol, and end symbol', 'advance_beam': 'advance the Beam state with word log-probabilities to update the search', 'build_target_tokens': 'build target token sequences from beam hypotheses by filtering out EOS tokens'}
```

## File: facebookresearch_codegen/CodeXGLUE/Text-Code/text-to-code/code/bleu.py

Prompts

```
['build a Seq2Seq model with an encoder, decoder, and config for text-to-code generation', 'run beam search decoding on source sequences using the Seq2Seq forward method', 'create a Beam object with a given size, start symbol, and end symbol', 'advance the Beam state with word log-probabilities to update the search', 'build target token sequences from beam hypotheses by filtering out EOS tokens', 'compute the BLEU score of translated segments against one or more reference corpora', 'compute the BLEU score with Lin et al 2004 smoothing applied to n-gram precisions', 'extract all n-grams up to a given maximum order from an input text segment', 'compute the BLEU score from a reference file and a translation file', 'review the Python implementation of BLEU and smooth-BLEU scoring for machine translation evaluation', 'create a concodeDataset instance to load and tokenize natural language to code pairs from a JSON file', 'pad and truncate natural language and code token sequences to a fixed block size with label masks', 'cache tokenized input features and labels as a pickle file to avoid reprocessing the dataset', 'shard the dataset across distributed workers by filtering samples based on process rank and world size', 'get a single training sample as a pair of PyTorch tensors containing input IDs and token labels', 'train a text to code generation model using GPT-2 or RoBERTa on the CodeXGLUE dataset', 'evaluate the trained model on the dev set and compute perplexity scores', 'evaluate code generation quality using BLEU score and exact match on dev or test set', 'run beam search inference to generate code from natural language descriptions', 'load a pretrained model and resume training from the last saved checkpoint']
```

Usage

```
{'compute_bleu_score': 'compute the BLEU score of translated segments against one or more reference corpora', 'compute_bleu_with_smoothing': 'compute the BLEU score with Lin et al 2004 smoothing applied to n-gram precisions', 'extract_ngrams': 'extract all n-grams up to a given maximum order from an input text segment', 'compute_bleu_from_files': 'compute the BLEU score from a reference file and a translation file', 'review_bleu_implementation': 'review the Python implementation of BLEU and smooth-BLEU scoring for machine translation evaluation'}
```

## File: facebookresearch_codegen/CodeXGLUE/Text-Code/text-to-code/code/dataset.py

Prompts

```
['build a Seq2Seq model with an encoder, decoder, and config for text-to-code generation', 'run beam search decoding on source sequences using the Seq2Seq forward method', 'create a Beam object with a given size, start symbol, and end symbol', 'advance the Beam state with word log-probabilities to update the search', 'build target token sequences from beam hypotheses by filtering out EOS tokens', 'compute the BLEU score of translated segments against one or more reference corpora', 'compute the BLEU score with Lin et al 2004 smoothing applied to n-gram precisions', 'extract all n-grams up to a given maximum order from an input text segment', 'compute the BLEU score from a reference file and a translation file', 'review the Python implementation of BLEU and smooth-BLEU scoring for machine translation evaluation', 'create a concodeDataset instance to load and tokenize natural language to code pairs from a JSON file', 'pad and truncate natural language and code token sequences to a fixed block size with label masks', 'cache tokenized input features and labels as a pickle file to avoid reprocessing the dataset', 'shard the dataset across distributed workers by filtering samples based on process rank and world size', 'get a single training sample as a pair of PyTorch tensors containing input IDs and token labels', 'train a text to code generation model using GPT-2 or RoBERTa on the CodeXGLUE dataset', 'evaluate the trained model on the dev set and compute perplexity scores', 'evaluate code generation quality using BLEU score and exact match on dev or test set', 'run beam search inference to generate code from natural language descriptions', 'load a pretrained model and resume training from the last saved checkpoint']
```

Usage

```
{'create_concode_dataset': 'create a concodeDataset instance to load and tokenize natural language to code pairs from a JSON file', 'pad_and_get_mask': 'pad and truncate natural language and code token sequences to a fixed block size with label masks', 'cache_tokenized_features': 'cache tokenized input features and labels as a pickle file to avoid reprocessing the dataset', 'distribute_dataset_sharding': 'shard the dataset across distributed workers by filtering samples based on process rank and world size', 'get_dataset_item': 'get a single training sample as a pair of PyTorch tensors containing input IDs and token labels'}
```

## File: facebookresearch_codegen/CodeXGLUE/Text-Code/text-to-code/code/run.py

Prompts

```
['build a Seq2Seq model with an encoder, decoder, and config for text-to-code generation', 'run beam search decoding on source sequences using the Seq2Seq forward method', 'create a Beam object with a given size, start symbol, and end symbol', 'advance the Beam state with word log-probabilities to update the search', 'build target token sequences from beam hypotheses by filtering out EOS tokens', 'compute the BLEU score of translated segments against one or more reference corpora', 'compute the BLEU score with Lin et al 2004 smoothing applied to n-gram precisions', 'extract all n-grams up to a given maximum order from an input text segment', 'compute the BLEU score from a reference file and a translation file', 'review the Python implementation of BLEU and smooth-BLEU scoring for machine translation evaluation', 'create a concodeDataset instance to load and tokenize natural language to code pairs from a JSON file', 'pad and truncate natural language and code token sequences to a fixed block size with label masks', 'cache tokenized input features and labels as a pickle file to avoid reprocessing the dataset', 'shard the dataset across distributed workers by filtering samples based on process rank and world size', 'get a single training sample as a pair of PyTorch tensors containing input IDs and token labels', 'train a text to code generation model using GPT-2 or RoBERTa on the CodeXGLUE dataset', 'evaluate the trained model on the dev set and compute perplexity scores', 'evaluate code generation quality using BLEU score and exact match on dev or test set', 'run beam search inference to generate code from natural language descriptions', 'load a pretrained model and resume training from the last saved checkpoint']
```

Usage

```
{'train_text_to_code_model': 'train a text to code generation model using GPT-2 or RoBERTa on the CodeXGLUE dataset', 'evaluate_model_perplexity': 'evaluate the trained model on the dev set and compute perplexity scores', 'eval_bleu_code_generation': 'evaluate code generation quality using BLEU score and exact match on dev or test set', 'run_beam_search_inference': 'run beam search inference to generate code from natural language descriptions', 'load_resume_checkpoint': 'load a pretrained model and resume training from the last saved checkpoint'}
```

