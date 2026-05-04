# Agent Python Tools

- repo: facebookresearch/dme
- repo_uri: https://github.com/facebookresearch/dme

## File: facebookresearch_dme/dme/args.py

Prompts

```
['parse command line arguments for the DME model training experiment configuration', 'get a list of available pre-trained embeddings with their file paths and dimensions', 'preprocess the args namespace to set up cache paths, checkpoint paths, and resolve embeddings', 'configure the optimizer type, learning rate, and learning rate scheduling parameters', 'set embedder parameters including attention type, dropout, projection size, and embedding mix mode', 'load pretrained word embeddings from a text file and cache them as a pickle for fast reuse', 'match pretrained embeddings to a vocabulary index by exact or lowercase word key lookup', 'normalize embeddings by subtracting the mean of matched indices and zero out unmatched indices', 'build a cached vocabulary set from multiple embedding file paths with specified dimensions', 'create a single PyTorch embedding layer initialized with pretrained word vectors and frozen weights', 'build a SentEncoder with args and logger to encode sentences using a bidirectional LSTM', 'create an embedder by calling get_embedder with args specifying mixmode as cat or proj_sum', 'run the SentEncoder forward pass with words tensor and sequence lengths to get encoded representations', 'review the SentEncoder class to understand how it uses packed sequences with a bidirectional LSTM', 'refactor get_embedder to support additional mixmode options beyond cat and proj_sum', 'create a logger that writes debug logs to a file and info logs to the console', 'create a LogFormatter that prefixes log messages with level, timestamp, and elapsed time', 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure a logger with debug level for file output and info level for console output']
```

Usage

```
{'parse_dme_training_args': 'parse command line arguments for the DME model training experiment configuration', 'get_available_embeddings': 'get a list of available pre-trained embeddings with their file paths and dimensions', 'preprocess_args': 'preprocess the args namespace to set up cache paths, checkpoint paths, and resolve embeddings', 'configure_optimizer_and_lr': 'configure the optimizer type, learning rate, and learning rate scheduling parameters', 'set_embedder_config': 'set embedder parameters including attention type, dropout, projection size, and embedding mix mode'}
```

## File: facebookresearch_dme/dme/embedders.py

Prompts

```
['parse command line arguments for the DME model training experiment configuration', 'get a list of available pre-trained embeddings with their file paths and dimensions', 'preprocess the args namespace to set up cache paths, checkpoint paths, and resolve embeddings', 'configure the optimizer type, learning rate, and learning rate scheduling parameters', 'set embedder parameters including attention type, dropout, projection size, and embedding mix mode', 'load pretrained word embeddings from a text file and cache them as a pickle for fast reuse', 'match pretrained embeddings to a vocabulary index by exact or lowercase word key lookup', 'normalize embeddings by subtracting the mean of matched indices and zero out unmatched indices', 'build a cached vocabulary set from multiple embedding file paths with specified dimensions', 'create a single PyTorch embedding layer initialized with pretrained word vectors and frozen weights', 'build a SentEncoder with args and logger to encode sentences using a bidirectional LSTM', 'create an embedder by calling get_embedder with args specifying mixmode as cat or proj_sum', 'run the SentEncoder forward pass with words tensor and sequence lengths to get encoded representations', 'review the SentEncoder class to understand how it uses packed sequences with a bidirectional LSTM', 'refactor get_embedder to support additional mixmode options beyond cat and proj_sum', 'create a logger that writes debug logs to a file and info logs to the console', 'create a LogFormatter that prefixes log messages with level, timestamp, and elapsed time', 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure a logger with debug level for file output and info level for console output']
```

Usage

```
{'load_cached_pretrained_embeddings': 'load pretrained word embeddings from a text file and cache them as a pickle for fast reuse', 'match_pretrained_embeddings': 'match pretrained embeddings to a vocabulary index by exact or lowercase word key lookup', 'normalize_embeddings': 'normalize embeddings by subtracting the mean of matched indices and zero out unmatched indices', 'get_embeds_vocab': 'build a cached vocabulary set from multiple embedding file paths with specified dimensions', 'SingleEmbedder': 'create a single PyTorch embedding layer initialized with pretrained word vectors and frozen weights'}
```

## File: facebookresearch_dme/dme/encoders.py

Prompts

```
['parse command line arguments for the DME model training experiment configuration', 'get a list of available pre-trained embeddings with their file paths and dimensions', 'preprocess the args namespace to set up cache paths, checkpoint paths, and resolve embeddings', 'configure the optimizer type, learning rate, and learning rate scheduling parameters', 'set embedder parameters including attention type, dropout, projection size, and embedding mix mode', 'load pretrained word embeddings from a text file and cache them as a pickle for fast reuse', 'match pretrained embeddings to a vocabulary index by exact or lowercase word key lookup', 'normalize embeddings by subtracting the mean of matched indices and zero out unmatched indices', 'build a cached vocabulary set from multiple embedding file paths with specified dimensions', 'create a single PyTorch embedding layer initialized with pretrained word vectors and frozen weights', 'build a SentEncoder with args and logger to encode sentences using a bidirectional LSTM', 'create an embedder by calling get_embedder with args specifying mixmode as cat or proj_sum', 'run the SentEncoder forward pass with words tensor and sequence lengths to get encoded representations', 'review the SentEncoder class to understand how it uses packed sequences with a bidirectional LSTM', 'refactor get_embedder to support additional mixmode options beyond cat and proj_sum', 'create a logger that writes debug logs to a file and info logs to the console', 'create a LogFormatter that prefixes log messages with level, timestamp, and elapsed time', 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure a logger with debug level for file output and info level for console output']
```

Usage

```
{'build_sentencoder': 'build a SentEncoder with args and logger to encode sentences using a bidirectional LSTM', 'create_get_embedder': 'create an embedder by calling get_embedder with args specifying mixmode as cat or proj_sum', 'run_sentencoder_forward': 'run the SentEncoder forward pass with words tensor and sequence lengths to get encoded representations', 'review_sentencoder_rnn': 'review the SentEncoder class to understand how it uses packed sequences with a bidirectional LSTM', 'refactor_get_embedder_mixmode': 'refactor get_embedder to support additional mixmode options beyond cat and proj_sum'}
```

## File: facebookresearch_dme/dme/logger.py

Prompts

```
['parse command line arguments for the DME model training experiment configuration', 'get a list of available pre-trained embeddings with their file paths and dimensions', 'preprocess the args namespace to set up cache paths, checkpoint paths, and resolve embeddings', 'configure the optimizer type, learning rate, and learning rate scheduling parameters', 'set embedder parameters including attention type, dropout, projection size, and embedding mix mode', 'load pretrained word embeddings from a text file and cache them as a pickle for fast reuse', 'match pretrained embeddings to a vocabulary index by exact or lowercase word key lookup', 'normalize embeddings by subtracting the mean of matched indices and zero out unmatched indices', 'build a cached vocabulary set from multiple embedding file paths with specified dimensions', 'create a single PyTorch embedding layer initialized with pretrained word vectors and frozen weights', 'build a SentEncoder with args and logger to encode sentences using a bidirectional LSTM', 'create an embedder by calling get_embedder with args specifying mixmode as cat or proj_sum', 'run the SentEncoder forward pass with words tensor and sequence lengths to get encoded representations', 'review the SentEncoder class to understand how it uses packed sequences with a bidirectional LSTM', 'refactor get_embedder to support additional mixmode options beyond cat and proj_sum', 'create a logger that writes debug logs to a file and info logs to the console', 'create a LogFormatter that prefixes log messages with level, timestamp, and elapsed time', 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure a logger with debug level for file output and info level for console output']
```

Usage

```
{'create_logger_with_file_and_console_handlers': 'create a logger that writes debug logs to a file and info logs to the console', 'create_log_formatter_with_elapsed_time': 'create a LogFormatter that prefixes log messages with level, timestamp, and elapsed time', 'reset_logger_elapsed_time': 'reset the logger elapsed time by calling the reset_time method on the logger object', 'format_log_message_with_multiline_support': 'format a log message that replaces newlines with indented lines to align with the prefix', 'configure_logger_debug_and_info_levels': 'configure a logger with debug level for file output and info level for console output'}
```

