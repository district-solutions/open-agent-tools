# Agent Python Tools

- repo: facebookresearch/access
- repo_uri: https://github.com/facebookresearch/access

## File: facebookresearch_access/access/feature_extraction.py

Prompts

```
['compute the lexical complexity score of a sentence using fasttext word ranks and the 75th percentile', 'calculate the Levenshtein similarity ratio between a complex sentence and a simple sentence', 'compute the maximum dependency tree depth of a sentence using spaCy parsing', 'get the fasttext vocabulary rank of a word from the preloaded word-to-rank mapping', 'get the natural log of one plus the fasttext vocabulary rank of a word', 'replace bracket tokens like -lrb- and -rrb- with actual parentheses in text', 'add noise to a sentence by shuffling, dropping, and blanking words randomly', 'normalize backticks and double single quotes to standard quotes in text', 'split a file into multiple output files using round robin line distribution', 'merge multiple input files into one output file in round robin or sequential order', 'create a ComposedPreprocessor to chain multiple preprocessors and encode sentences sequentially', 'encode sentences into subword pieces using the SentencePiecePreprocessor with a custom vocab size', 'extract and remove angle bracket special tokens from the beginning of a sentence', 'add a LevenshteinPreprocessor to prepend a target edit distance ratio token to sentences', 'dump preprocessors to a pickle file and load them back from a directory path', 'create a fairseq simplifier from an experiment directory to simplify complex source files', 'create a preprocessed simplifier that encodes input files before simplification and decodes output', 'memoize a simplifier function to cache predictions by file hash and reuse previous results', 'run the fairseq simplifier on a complex source file and write simplified predictions to an output file', 'run a preprocessed simplifier pipeline that encodes, simplifies, and decodes source files', 'tokenize a sentence into words using NIST tokenizer and fix special entity tokens', 'remove all punctuation-only tokens from a text string and return cleaned text', 'remove English stopwords from a text string and return the remaining words', 'process text with spaCy NLP model and return an annotated Doc object', 'check if a single word consists entirely of punctuation characters']
```

Usage

```
{'get_lexical_complexity_score': 'compute the lexical complexity score of a sentence using fasttext word ranks and the 75th percentile', 'get_levenshtein_similarity': 'calculate the Levenshtein similarity ratio between a complex sentence and a simple sentence', 'get_dependency_tree_depth': 'compute the maximum dependency tree depth of a sentence using spaCy parsing', 'get_rank': 'get the fasttext vocabulary rank of a word from the preloaded word-to-rank mapping', 'get_log_rank': 'get the natural log of one plus the fasttext vocabulary rank of a word'}
```

## File: facebookresearch_access/access/preprocess.py

Prompts

```
['compute the lexical complexity score of a sentence using fasttext word ranks and the 75th percentile', 'calculate the Levenshtein similarity ratio between a complex sentence and a simple sentence', 'compute the maximum dependency tree depth of a sentence using spaCy parsing', 'get the fasttext vocabulary rank of a word from the preloaded word-to-rank mapping', 'get the natural log of one plus the fasttext vocabulary rank of a word', 'replace bracket tokens like -lrb- and -rrb- with actual parentheses in text', 'add noise to a sentence by shuffling, dropping, and blanking words randomly', 'normalize backticks and double single quotes to standard quotes in text', 'split a file into multiple output files using round robin line distribution', 'merge multiple input files into one output file in round robin or sequential order', 'create a ComposedPreprocessor to chain multiple preprocessors and encode sentences sequentially', 'encode sentences into subword pieces using the SentencePiecePreprocessor with a custom vocab size', 'extract and remove angle bracket special tokens from the beginning of a sentence', 'add a LevenshteinPreprocessor to prepend a target edit distance ratio token to sentences', 'dump preprocessors to a pickle file and load them back from a directory path', 'create a fairseq simplifier from an experiment directory to simplify complex source files', 'create a preprocessed simplifier that encodes input files before simplification and decodes output', 'memoize a simplifier function to cache predictions by file hash and reuse previous results', 'run the fairseq simplifier on a complex source file and write simplified predictions to an output file', 'run a preprocessed simplifier pipeline that encodes, simplifies, and decodes source files', 'tokenize a sentence into words using NIST tokenizer and fix special entity tokens', 'remove all punctuation-only tokens from a text string and return cleaned text', 'remove English stopwords from a text string and return the remaining words', 'process text with spaCy NLP model and return an annotated Doc object', 'check if a single word consists entirely of punctuation characters']
```

Usage

```
{'replace_lrb_rrb': 'replace bracket tokens like -lrb- and -rrb- with actual parentheses in text', 'add_noise': 'add noise to a sentence by shuffling, dropping, and blanking words randomly', 'normalize_quotes': 'normalize backticks and double single quotes to standard quotes in text', 'split_file': 'split a file into multiple output files using round robin line distribution', 'merge_files': 'merge multiple input files into one output file in round robin or sequential order'}
```

## File: facebookresearch_access/access/preprocessors.py

Prompts

```
['compute the lexical complexity score of a sentence using fasttext word ranks and the 75th percentile', 'calculate the Levenshtein similarity ratio between a complex sentence and a simple sentence', 'compute the maximum dependency tree depth of a sentence using spaCy parsing', 'get the fasttext vocabulary rank of a word from the preloaded word-to-rank mapping', 'get the natural log of one plus the fasttext vocabulary rank of a word', 'replace bracket tokens like -lrb- and -rrb- with actual parentheses in text', 'add noise to a sentence by shuffling, dropping, and blanking words randomly', 'normalize backticks and double single quotes to standard quotes in text', 'split a file into multiple output files using round robin line distribution', 'merge multiple input files into one output file in round robin or sequential order', 'create a ComposedPreprocessor to chain multiple preprocessors and encode sentences sequentially', 'encode sentences into subword pieces using the SentencePiecePreprocessor with a custom vocab size', 'extract and remove angle bracket special tokens from the beginning of a sentence', 'add a LevenshteinPreprocessor to prepend a target edit distance ratio token to sentences', 'dump preprocessors to a pickle file and load them back from a directory path', 'create a fairseq simplifier from an experiment directory to simplify complex source files', 'create a preprocessed simplifier that encodes input files before simplification and decodes output', 'memoize a simplifier function to cache predictions by file hash and reuse previous results', 'run the fairseq simplifier on a complex source file and write simplified predictions to an output file', 'run a preprocessed simplifier pipeline that encodes, simplifies, and decodes source files', 'tokenize a sentence into words using NIST tokenizer and fix special entity tokens', 'remove all punctuation-only tokens from a text string and return cleaned text', 'remove English stopwords from a text string and return the remaining words', 'process text with spaCy NLP model and return an annotated Doc object', 'check if a single word consists entirely of punctuation characters']
```

Usage

```
{'create_composed_preprocessor': 'create a ComposedPreprocessor to chain multiple preprocessors and encode sentences sequentially', 'encode_sentences_with_sentencepiece': 'encode sentences into subword pieces using the SentencePiecePreprocessor with a custom vocab size', 'extract_special_tokens': 'extract and remove angle bracket special tokens from the beginning of a sentence', 'add_levenshtein_feature': 'add a LevenshteinPreprocessor to prepend a target edit distance ratio token to sentences', 'dump_and_load_preprocessors': 'dump preprocessors to a pickle file and load them back from a directory path'}
```

## File: facebookresearch_access/access/simplifiers.py

Prompts

```
['compute the lexical complexity score of a sentence using fasttext word ranks and the 75th percentile', 'calculate the Levenshtein similarity ratio between a complex sentence and a simple sentence', 'compute the maximum dependency tree depth of a sentence using spaCy parsing', 'get the fasttext vocabulary rank of a word from the preloaded word-to-rank mapping', 'get the natural log of one plus the fasttext vocabulary rank of a word', 'replace bracket tokens like -lrb- and -rrb- with actual parentheses in text', 'add noise to a sentence by shuffling, dropping, and blanking words randomly', 'normalize backticks and double single quotes to standard quotes in text', 'split a file into multiple output files using round robin line distribution', 'merge multiple input files into one output file in round robin or sequential order', 'create a ComposedPreprocessor to chain multiple preprocessors and encode sentences sequentially', 'encode sentences into subword pieces using the SentencePiecePreprocessor with a custom vocab size', 'extract and remove angle bracket special tokens from the beginning of a sentence', 'add a LevenshteinPreprocessor to prepend a target edit distance ratio token to sentences', 'dump preprocessors to a pickle file and load them back from a directory path', 'create a fairseq simplifier from an experiment directory to simplify complex source files', 'create a preprocessed simplifier that encodes input files before simplification and decodes output', 'memoize a simplifier function to cache predictions by file hash and reuse previous results', 'run the fairseq simplifier on a complex source file and write simplified predictions to an output file', 'run a preprocessed simplifier pipeline that encodes, simplifies, and decodes source files', 'tokenize a sentence into words using NIST tokenizer and fix special entity tokens', 'remove all punctuation-only tokens from a text string and return cleaned text', 'remove English stopwords from a text string and return the remaining words', 'process text with spaCy NLP model and return an annotated Doc object', 'check if a single word consists entirely of punctuation characters']
```

Usage

```
{'create_fairseq_simplifier': 'create a fairseq simplifier from an experiment directory to simplify complex source files', 'create_preprocessed_simplifier': 'create a preprocessed simplifier that encodes input files before simplification and decodes output', 'memoize_simplifier': 'memoize a simplifier function to cache predictions by file hash and reuse previous results', 'run_fairseq_simplifier': 'run the fairseq simplifier on a complex source file and write simplified predictions to an output file', 'run_preprocessed_simplifier': 'run a preprocessed simplifier pipeline that encodes, simplifies, and decodes source files'}
```

## File: facebookresearch_access/access/text.py

Prompts

```
['compute the lexical complexity score of a sentence using fasttext word ranks and the 75th percentile', 'calculate the Levenshtein similarity ratio between a complex sentence and a simple sentence', 'compute the maximum dependency tree depth of a sentence using spaCy parsing', 'get the fasttext vocabulary rank of a word from the preloaded word-to-rank mapping', 'get the natural log of one plus the fasttext vocabulary rank of a word', 'replace bracket tokens like -lrb- and -rrb- with actual parentheses in text', 'add noise to a sentence by shuffling, dropping, and blanking words randomly', 'normalize backticks and double single quotes to standard quotes in text', 'split a file into multiple output files using round robin line distribution', 'merge multiple input files into one output file in round robin or sequential order', 'create a ComposedPreprocessor to chain multiple preprocessors and encode sentences sequentially', 'encode sentences into subword pieces using the SentencePiecePreprocessor with a custom vocab size', 'extract and remove angle bracket special tokens from the beginning of a sentence', 'add a LevenshteinPreprocessor to prepend a target edit distance ratio token to sentences', 'dump preprocessors to a pickle file and load them back from a directory path', 'create a fairseq simplifier from an experiment directory to simplify complex source files', 'create a preprocessed simplifier that encodes input files before simplification and decodes output', 'memoize a simplifier function to cache predictions by file hash and reuse previous results', 'run the fairseq simplifier on a complex source file and write simplified predictions to an output file', 'run a preprocessed simplifier pipeline that encodes, simplifies, and decodes source files', 'tokenize a sentence into words using NIST tokenizer and fix special entity tokens', 'remove all punctuation-only tokens from a text string and return cleaned text', 'remove English stopwords from a text string and return the remaining words', 'process text with spaCy NLP model and return an annotated Doc object', 'check if a single word consists entirely of punctuation characters']
```

Usage

```
{'word_tokenize': 'tokenize a sentence into words using NIST tokenizer and fix special entity tokens', 'remove_punctuation_tokens': 'remove all punctuation-only tokens from a text string and return cleaned text', 'remove_stopwords': 'remove English stopwords from a text string and return the remaining words', 'spacy_process': 'process text with spaCy NLP model and return an annotated Doc object', 'is_punctuation': 'check if a single word consists entirely of punctuation characters'}
```

