# Agent Python Tools

- repo: facebookresearch/lama
- repo_uri: https://github.com/facebookresearch/lama

## File: facebookresearch_lama/lama/build_encoded_dataset.py

Prompts

```
['encode a list of sentences into contextual embeddings using a language model and return an EncodedDataset', 'load a precomputed EncodedDataset from a pickle file at the given path', 'create an EncodedDataset object from a list of encoded sentence tuples with embeddings and lengths', 'save an EncodedDataset to disk as a pickle file at the specified path', 'average embeddings across all model layers to produce a single aggregated embedding tensor', 'get the ranking metrics MRR, P@X, and perplexity for masked language model predictions using log_probs and masked_indices', 'get the negation overlap and Spearman rank correlation between affirmative and negated masked language model predictions', 'extract the top-k maximum log probability values and their indices from masked language model output tensors', 'print and return the top-k predicted token word forms with their log probabilities from a vocabulary', 'compute whether the top-ranked prediction is identical between an affirmative and its negated masked statement', 'run get_general_parser to create an argparse parser with language model and BERT ELMo GPT arguments', 'run get_eval_generation_parser to create a parser for text generation evaluation with sentence splitting', 'run get_eval_KB_completion_parser to create a parser for knowledge base completion evaluation with batch settings', 'run parse_args on a parser to parse CLI arguments and validate model-specific required options', 'run __add_bert_args to add BERT model directory and vocabulary arguments to an existing parser', 'print sentence-level token predictions with perplexity scores and top-k ranking for a language model', 'load a vocabulary file into a list of token strings from a given file path', 'review the print_sentence_predictions function to understand how it computes perplexity and ranks token predictions', 'refactor print_sentence_predictions to support multiple masked indices instead of only the first', 'summarize the load_vocab function that reads a text file and returns stripped token strings']
```

Usage

```
{'encode_sentences': 'encode a list of sentences into contextual embeddings using a language model and return an EncodedDataset', 'load_encoded_dataset': 'load a precomputed EncodedDataset from a pickle file at the given path', 'create_encoded_dataset': 'create an EncodedDataset object from a list of encoded sentence tuples with embeddings and lengths', 'save_encoded_dataset': 'save an EncodedDataset to disk as a pickle file at the specified path', 'aggregate_layers': 'average embeddings across all model layers to produce a single aggregated embedding tensor'}
```

## File: facebookresearch_lama/lama/evaluation_metrics.py

Prompts

```
['encode a list of sentences into contextual embeddings using a language model and return an EncodedDataset', 'load a precomputed EncodedDataset from a pickle file at the given path', 'create an EncodedDataset object from a list of encoded sentence tuples with embeddings and lengths', 'save an EncodedDataset to disk as a pickle file at the specified path', 'average embeddings across all model layers to produce a single aggregated embedding tensor', 'get the ranking metrics MRR, P@X, and perplexity for masked language model predictions using log_probs and masked_indices', 'get the negation overlap and Spearman rank correlation between affirmative and negated masked language model predictions', 'extract the top-k maximum log probability values and their indices from masked language model output tensors', 'print and return the top-k predicted token word forms with their log probabilities from a vocabulary', 'compute whether the top-ranked prediction is identical between an affirmative and its negated masked statement', 'run get_general_parser to create an argparse parser with language model and BERT ELMo GPT arguments', 'run get_eval_generation_parser to create a parser for text generation evaluation with sentence splitting', 'run get_eval_KB_completion_parser to create a parser for knowledge base completion evaluation with batch settings', 'run parse_args on a parser to parse CLI arguments and validate model-specific required options', 'run __add_bert_args to add BERT model directory and vocabulary arguments to an existing parser', 'print sentence-level token predictions with perplexity scores and top-k ranking for a language model', 'load a vocabulary file into a list of token strings from a given file path', 'review the print_sentence_predictions function to understand how it computes perplexity and ranks token predictions', 'refactor print_sentence_predictions to support multiple masked indices instead of only the first', 'summarize the load_vocab function that reads a text file and returns stripped token strings']
```

Usage

```
{'get_ranking': 'get the ranking metrics MRR, P@X, and perplexity for masked language model predictions using log_probs and masked_indices', 'get_negation_metric': 'get the negation overlap and Spearman rank correlation between affirmative and negated masked language model predictions', 'max_probs_values_indices': 'extract the top-k maximum log probability values and their indices from masked language model output tensors', 'print_top_k': 'print and return the top-k predicted token word forms with their log probabilities from a vocabulary', 'overlap_negation': 'compute whether the top-ranked prediction is identical between an affirmative and its negated masked statement'}
```

## File: facebookresearch_lama/lama/options.py

Prompts

```
['encode a list of sentences into contextual embeddings using a language model and return an EncodedDataset', 'load a precomputed EncodedDataset from a pickle file at the given path', 'create an EncodedDataset object from a list of encoded sentence tuples with embeddings and lengths', 'save an EncodedDataset to disk as a pickle file at the specified path', 'average embeddings across all model layers to produce a single aggregated embedding tensor', 'get the ranking metrics MRR, P@X, and perplexity for masked language model predictions using log_probs and masked_indices', 'get the negation overlap and Spearman rank correlation between affirmative and negated masked language model predictions', 'extract the top-k maximum log probability values and their indices from masked language model output tensors', 'print and return the top-k predicted token word forms with their log probabilities from a vocabulary', 'compute whether the top-ranked prediction is identical between an affirmative and its negated masked statement', 'run get_general_parser to create an argparse parser with language model and BERT ELMo GPT arguments', 'run get_eval_generation_parser to create a parser for text generation evaluation with sentence splitting', 'run get_eval_KB_completion_parser to create a parser for knowledge base completion evaluation with batch settings', 'run parse_args on a parser to parse CLI arguments and validate model-specific required options', 'run __add_bert_args to add BERT model directory and vocabulary arguments to an existing parser', 'print sentence-level token predictions with perplexity scores and top-k ranking for a language model', 'load a vocabulary file into a list of token strings from a given file path', 'review the print_sentence_predictions function to understand how it computes perplexity and ranks token predictions', 'refactor print_sentence_predictions to support multiple masked indices instead of only the first', 'summarize the load_vocab function that reads a text file and returns stripped token strings']
```

Usage

```
{'run_general_parser': 'run get_general_parser to create an argparse parser with language model and BERT ELMo GPT arguments', 'run_eval_generation_parser': 'run get_eval_generation_parser to create a parser for text generation evaluation with sentence splitting', 'run_eval_KB_completion_parser': 'run get_eval_KB_completion_parser to create a parser for knowledge base completion evaluation with batch settings', 'run_parse_args': 'run parse_args on a parser to parse CLI arguments and validate model-specific required options', 'run_add_bert_args': 'run __add_bert_args to add BERT model directory and vocabulary arguments to an existing parser'}
```

## File: facebookresearch_lama/lama/utils.py

Prompts

```
['encode a list of sentences into contextual embeddings using a language model and return an EncodedDataset', 'load a precomputed EncodedDataset from a pickle file at the given path', 'create an EncodedDataset object from a list of encoded sentence tuples with embeddings and lengths', 'save an EncodedDataset to disk as a pickle file at the specified path', 'average embeddings across all model layers to produce a single aggregated embedding tensor', 'get the ranking metrics MRR, P@X, and perplexity for masked language model predictions using log_probs and masked_indices', 'get the negation overlap and Spearman rank correlation between affirmative and negated masked language model predictions', 'extract the top-k maximum log probability values and their indices from masked language model output tensors', 'print and return the top-k predicted token word forms with their log probabilities from a vocabulary', 'compute whether the top-ranked prediction is identical between an affirmative and its negated masked statement', 'run get_general_parser to create an argparse parser with language model and BERT ELMo GPT arguments', 'run get_eval_generation_parser to create a parser for text generation evaluation with sentence splitting', 'run get_eval_KB_completion_parser to create a parser for knowledge base completion evaluation with batch settings', 'run parse_args on a parser to parse CLI arguments and validate model-specific required options', 'run __add_bert_args to add BERT model directory and vocabulary arguments to an existing parser', 'print sentence-level token predictions with perplexity scores and top-k ranking for a language model', 'load a vocabulary file into a list of token strings from a given file path', 'review the print_sentence_predictions function to understand how it computes perplexity and ranks token predictions', 'refactor print_sentence_predictions to support multiple masked indices instead of only the first', 'summarize the load_vocab function that reads a text file and returns stripped token strings']
```

Usage

```
{'print_sentence_predictions': 'print sentence-level token predictions with perplexity scores and top-k ranking for a language model', 'load_vocab': 'load a vocabulary file into a list of token strings from a given file path', 'review_print_sentence_predictions': 'review the print_sentence_predictions function to understand how it computes perplexity and ranks token predictions', 'refactor_print_sentence_predictions': 'refactor print_sentence_predictions to support multiple masked indices instead of only the first', 'summarize_load_vocab': 'summarize the load_vocab function that reads a text file and returns stripped token strings'}
```

