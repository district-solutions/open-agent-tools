# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/rl/envs/utils/code.py

Prompts

```
['extract the first python code block from a text string using triple backtick delimiters', 'extract a single python code block from text returning None if multiple blocks exist', 'shorten execution error info and stack traces to a maximum of 512 characters', 'compute code execution outcome flags from a list of ExecStatus results for private and public tests', 'check if code execution outcomes match the predefined failure criteria including parsing and compiling errors', 'truncate a message body from the left to fit within a maximum token limit', 'truncate a message body from the right to fit within a maximum token limit', 'truncate a message body and insert abbreviation tokens to indicate truncation', 'review the maybe_truncate_message function for left and right truncation logic', 'summarize the maybe_truncate_message function that truncates message bodies to a token budget', 'inspect a Trajectory object with rich pretty printing and configurable truncation length', 'print a Trajectory as decoded strings using a Tokenizer with syntax highlighting', 'zip a Trajectory into tuples of token strings, ids, sources, and rewards', 'print a Trajectory as a rich table with token id, source, and reward columns', 'run the CLI module to pretty-print a trajectory JSON file from stdin or a file path']
```

Usage

```
{'extract_first_code': 'extract the first python code block from a text string using triple backtick delimiters', 'extract_single_code': 'extract a single python code block from text returning None if multiple blocks exist', 'shorten_exec_info': 'shorten execution error info and stack traces to a maximum of 512 characters', 'code_exec_outcomes': 'compute code execution outcome flags from a list of ExecStatus results for private and public tests', 'failed_code_exec_outcomes': 'check if code execution outcomes match the predefined failure criteria including parsing and compiling errors'}
```

## File: facebookresearch_cwm/cwm/rl/envs/utils/dialogs.py

Prompts

```
['extract the first python code block from a text string using triple backtick delimiters', 'extract a single python code block from text returning None if multiple blocks exist', 'shorten execution error info and stack traces to a maximum of 512 characters', 'compute code execution outcome flags from a list of ExecStatus results for private and public tests', 'check if code execution outcomes match the predefined failure criteria including parsing and compiling errors', 'truncate a message body from the left to fit within a maximum token limit', 'truncate a message body from the right to fit within a maximum token limit', 'truncate a message body and insert abbreviation tokens to indicate truncation', 'review the maybe_truncate_message function for left and right truncation logic', 'summarize the maybe_truncate_message function that truncates message bodies to a token budget', 'inspect a Trajectory object with rich pretty printing and configurable truncation length', 'print a Trajectory as decoded strings using a Tokenizer with syntax highlighting', 'zip a Trajectory into tuples of token strings, ids, sources, and rewards', 'print a Trajectory as a rich table with token id, source, and reward columns', 'run the CLI module to pretty-print a trajectory JSON file from stdin or a file path']
```

Usage

```
{'truncate_message_left': 'truncate a message body from the left to fit within a maximum token limit', 'truncate_message_right': 'truncate a message body from the right to fit within a maximum token limit', 'truncate_message_with_abbrev': 'truncate a message body and insert abbreviation tokens to indicate truncation', 'review_maybe_truncate_message': 'review the maybe_truncate_message function for left and right truncation logic', 'summarize_maybe_truncate_message': 'summarize the maybe_truncate_message function that truncates message bodies to a token budget'}
```

## File: facebookresearch_cwm/cwm/rl/envs/utils/print_traj.py

Prompts

```
['extract the first python code block from a text string using triple backtick delimiters', 'extract a single python code block from text returning None if multiple blocks exist', 'shorten execution error info and stack traces to a maximum of 512 characters', 'compute code execution outcome flags from a list of ExecStatus results for private and public tests', 'check if code execution outcomes match the predefined failure criteria including parsing and compiling errors', 'truncate a message body from the left to fit within a maximum token limit', 'truncate a message body from the right to fit within a maximum token limit', 'truncate a message body and insert abbreviation tokens to indicate truncation', 'review the maybe_truncate_message function for left and right truncation logic', 'summarize the maybe_truncate_message function that truncates message bodies to a token budget', 'inspect a Trajectory object with rich pretty printing and configurable truncation length', 'print a Trajectory as decoded strings using a Tokenizer with syntax highlighting', 'zip a Trajectory into tuples of token strings, ids, sources, and rewards', 'print a Trajectory as a rich table with token id, source, and reward columns', 'run the CLI module to pretty-print a trajectory JSON file from stdin or a file path']
```

Usage

```
{'print_traj': 'inspect a Trajectory object with rich pretty printing and configurable truncation length', 'print_traj_str': 'print a Trajectory as decoded strings using a Tokenizer with syntax highlighting', 'zip_traj': 'zip a Trajectory into tuples of token strings, ids, sources, and rewards', 'print_traj_table': 'print a Trajectory as a rich table with token id, source, and reward columns', 'cli_print_trajectory': 'run the CLI module to pretty-print a trajectory JSON file from stdin or a file path'}
```

