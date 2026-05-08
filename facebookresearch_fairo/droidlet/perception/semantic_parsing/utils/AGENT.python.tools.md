# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/utils/interaction_logger.py

Prompts

```
['create an InteractionLogger instance to log NSP component interaction data to JSON files', 'log interaction data with a session_id to a per-session JSON logging file', 'review the InteractionLogger class and its logInteraction method for session-based JSON logging', 'refactor the InteractionLogger constructor to accept filepath and headers parameters', 'summarize the logInteraction method that appends data to session-specific JSON files', 'create an NSPLogger instance with a filepath and list of headers to initialize a pipe-delimited CSV log file', 'write pipe-delimited CSV headers to a log file using the NSPLogger init_file_headers method', 'append a row of dialogue data to the NSPLogger pipe-delimited CSV log file', 'review the NSPLogger class and its pipe-delimited CSV logging methods for dialogue output', 'summarize the NSPLogger class which provides pipe-delimited CSV logging for NSP component dialogue data', 'preprocess a chat string by tokenizing it with spaCy after inserting spaces around numbers and punctuation', 'tokenize a chat string using spaCy English tokenizer after inserting spaces around numbers and brackets', 'insert spaces between numbers and adjacent punctuation like brackets, commas, colons, and the letter x', 'run the preprocess module as a CLI script that reads lines from stdin and prints tokenized output', 'pass a debug string starting with _ttad_ or equal to _debug_ to bypass tokenization and return as-is', 'run the validate_json CLI to validate a dataset of parse trees against JSON schemas', 'create a JSONValidator instance that loads schemas from a directory and resolves cross references', 'validate JSON parse trees from a dataset file where each row has a command and parse tree separated by a pipe', 'validate a single parse tree dictionary against the loaded JSON schema and return a boolean result', 'review the JSONValidator class and its schema loading, reference resolving, and validation methods']
```

Usage

```
{'create_interaction_logger': 'create an InteractionLogger instance to log NSP component interaction data to JSON files', 'log_interaction_data': 'log interaction data with a session_id to a per-session JSON logging file', 'review_interaction_logger_class': 'review the InteractionLogger class and its logInteraction method for session-based JSON logging', 'refactor_interaction_logger_init': 'refactor the InteractionLogger constructor to accept filepath and headers parameters', 'summarize_log_interaction': 'summarize the logInteraction method that appends data to session-specific JSON files'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/utils/nsp_logger.py

Prompts

```
['create an InteractionLogger instance to log NSP component interaction data to JSON files', 'log interaction data with a session_id to a per-session JSON logging file', 'review the InteractionLogger class and its logInteraction method for session-based JSON logging', 'refactor the InteractionLogger constructor to accept filepath and headers parameters', 'summarize the logInteraction method that appends data to session-specific JSON files', 'create an NSPLogger instance with a filepath and list of headers to initialize a pipe-delimited CSV log file', 'write pipe-delimited CSV headers to a log file using the NSPLogger init_file_headers method', 'append a row of dialogue data to the NSPLogger pipe-delimited CSV log file', 'review the NSPLogger class and its pipe-delimited CSV logging methods for dialogue output', 'summarize the NSPLogger class which provides pipe-delimited CSV logging for NSP component dialogue data', 'preprocess a chat string by tokenizing it with spaCy after inserting spaces around numbers and punctuation', 'tokenize a chat string using spaCy English tokenizer after inserting spaces around numbers and brackets', 'insert spaces between numbers and adjacent punctuation like brackets, commas, colons, and the letter x', 'run the preprocess module as a CLI script that reads lines from stdin and prints tokenized output', 'pass a debug string starting with _ttad_ or equal to _debug_ to bypass tokenization and return as-is', 'run the validate_json CLI to validate a dataset of parse trees against JSON schemas', 'create a JSONValidator instance that loads schemas from a directory and resolves cross references', 'validate JSON parse trees from a dataset file where each row has a command and parse tree separated by a pipe', 'validate a single parse tree dictionary against the loaded JSON schema and return a boolean result', 'review the JSONValidator class and its schema loading, reference resolving, and validation methods']
```

Usage

```
{'create_nsp_logger': 'create an NSPLogger instance with a filepath and list of headers to initialize a pipe-delimited CSV log file', 'init_file_headers': 'write pipe-delimited CSV headers to a log file using the NSPLogger init_file_headers method', 'log_dialogue_outputs': 'append a row of dialogue data to the NSPLogger pipe-delimited CSV log file', 'review_nsp_logger_class': 'review the NSPLogger class and its pipe-delimited CSV logging methods for dialogue output', 'summarize_nsp_logger': 'summarize the NSPLogger class which provides pipe-delimited CSV logging for NSP component dialogue data'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/utils/preprocess.py

Prompts

```
['create an InteractionLogger instance to log NSP component interaction data to JSON files', 'log interaction data with a session_id to a per-session JSON logging file', 'review the InteractionLogger class and its logInteraction method for session-based JSON logging', 'refactor the InteractionLogger constructor to accept filepath and headers parameters', 'summarize the logInteraction method that appends data to session-specific JSON files', 'create an NSPLogger instance with a filepath and list of headers to initialize a pipe-delimited CSV log file', 'write pipe-delimited CSV headers to a log file using the NSPLogger init_file_headers method', 'append a row of dialogue data to the NSPLogger pipe-delimited CSV log file', 'review the NSPLogger class and its pipe-delimited CSV logging methods for dialogue output', 'summarize the NSPLogger class which provides pipe-delimited CSV logging for NSP component dialogue data', 'preprocess a chat string by tokenizing it with spaCy after inserting spaces around numbers and punctuation', 'tokenize a chat string using spaCy English tokenizer after inserting spaces around numbers and brackets', 'insert spaces between numbers and adjacent punctuation like brackets, commas, colons, and the letter x', 'run the preprocess module as a CLI script that reads lines from stdin and prints tokenized output', 'pass a debug string starting with _ttad_ or equal to _debug_ to bypass tokenization and return as-is', 'run the validate_json CLI to validate a dataset of parse trees against JSON schemas', 'create a JSONValidator instance that loads schemas from a directory and resolves cross references', 'validate JSON parse trees from a dataset file where each row has a command and parse tree separated by a pipe', 'validate a single parse tree dictionary against the loaded JSON schema and return a boolean result', 'review the JSONValidator class and its schema loading, reference resolving, and validation methods']
```

Usage

```
{'preprocess_chat': 'preprocess a chat string by tokenizing it with spaCy after inserting spaces around numbers and punctuation', 'word_tokenize': 'tokenize a chat string using spaCy English tokenizer after inserting spaces around numbers and brackets', 'insert_spaces': 'insert spaces between numbers and adjacent punctuation like brackets, commas, colons, and the letter x', 'run_preprocess_cli': 'run the preprocess module as a CLI script that reads lines from stdin and prints tokenized output', 'debug_preprocess_chat': 'pass a debug string starting with _ttad_ or equal to _debug_ to bypass tokenization and return as-is'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/utils/validate_json.py

Prompts

```
['create an InteractionLogger instance to log NSP component interaction data to JSON files', 'log interaction data with a session_id to a per-session JSON logging file', 'review the InteractionLogger class and its logInteraction method for session-based JSON logging', 'refactor the InteractionLogger constructor to accept filepath and headers parameters', 'summarize the logInteraction method that appends data to session-specific JSON files', 'create an NSPLogger instance with a filepath and list of headers to initialize a pipe-delimited CSV log file', 'write pipe-delimited CSV headers to a log file using the NSPLogger init_file_headers method', 'append a row of dialogue data to the NSPLogger pipe-delimited CSV log file', 'review the NSPLogger class and its pipe-delimited CSV logging methods for dialogue output', 'summarize the NSPLogger class which provides pipe-delimited CSV logging for NSP component dialogue data', 'preprocess a chat string by tokenizing it with spaCy after inserting spaces around numbers and punctuation', 'tokenize a chat string using spaCy English tokenizer after inserting spaces around numbers and brackets', 'insert spaces between numbers and adjacent punctuation like brackets, commas, colons, and the letter x', 'run the preprocess module as a CLI script that reads lines from stdin and prints tokenized output', 'pass a debug string starting with _ttad_ or equal to _debug_ to bypass tokenization and return as-is', 'run the validate_json CLI to validate a dataset of parse trees against JSON schemas', 'create a JSONValidator instance that loads schemas from a directory and resolves cross references', 'validate JSON parse trees from a dataset file where each row has a command and parse tree separated by a pipe', 'validate a single parse tree dictionary against the loaded JSON schema and return a boolean result', 'review the JSONValidator class and its schema loading, reference resolving, and validation methods']
```

Usage

```
{'run_validate_json_cli': 'run the validate_json CLI to validate a dataset of parse trees against JSON schemas', 'create_JSONValidator': 'create a JSONValidator instance that loads schemas from a directory and resolves cross references', 'validate_data': 'validate JSON parse trees from a dataset file where each row has a command and parse tree separated by a pipe', 'validate_instance': 'validate a single parse tree dictionary against the loaded JSON schema and return a boolean result', 'review_JSONValidator_class': 'review the JSONValidator class and its schema loading, reference resolving, and validation methods'}
```

