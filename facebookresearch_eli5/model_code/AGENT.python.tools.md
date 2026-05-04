# Agent Python Tools

- repo: facebookresearch/eli5
- repo_uri: https://github.com/facebookresearch/eli5

## File: facebookresearch_eli5/model_code/compute_rouge.py

Prompts

```
['run the rouge_calculation function to compute ROUGE scores between hypotheses and references', 'run the open_data function to read aligned hypothesis and reference files line by line', 'run the prepare function to stem all tokens in hypotheses and references using PorterStemmer', 'run the CLI module with --hypotheses and --references flags to compute ROUGE scores', 'review the rouge_calculation function that uses the rouge library to compute averaged ROUGE scores', 'run the pos_tag module with --input, --output, and --dataset-name args to tag POS', 'run open_files to read the first 2000 lines of target and source dataset files', 'run tag_and_write to POS-tag target lines with spaCy and write 6 output files', 'run file_writer to write a list of lines to a file with newline separators', 'review tag_and_write to understand how verbs, nouns, and adjectives are extracted and saved', 'run the CLI script with --input and --output args to process ELI5 JSON data into source and target files', 'create source and target files from questions, documents, and answers for a named dataset split', 'create multitask source and target files combining language modeling, seq2seq, and masking tasks for training', 'create multitask training pairs with language modeling and seq2seq task prefixes from questions, documents, and answers', 'create a masked language modeling pair by replacing 15 percent of tokens in a document with [MASK]']
```

Usage

```
{'run_rouge_calculation': 'run the rouge_calculation function to compute ROUGE scores between hypotheses and references', 'run_open_data': 'run the open_data function to read aligned hypothesis and reference files line by line', 'run_prepare': 'run the prepare function to stem all tokens in hypotheses and references using PorterStemmer', 'run_cli': 'run the CLI module with --hypotheses and --references flags to compute ROUGE scores', 'review_rouge_calculation': 'review the rouge_calculation function that uses the rouge library to compute averaged ROUGE scores'}
```

## File: facebookresearch_eli5/model_code/pos_tag.py

Prompts

```
['run the rouge_calculation function to compute ROUGE scores between hypotheses and references', 'run the open_data function to read aligned hypothesis and reference files line by line', 'run the prepare function to stem all tokens in hypotheses and references using PorterStemmer', 'run the CLI module with --hypotheses and --references flags to compute ROUGE scores', 'review the rouge_calculation function that uses the rouge library to compute averaged ROUGE scores', 'run the pos_tag module with --input, --output, and --dataset-name args to tag POS', 'run open_files to read the first 2000 lines of target and source dataset files', 'run tag_and_write to POS-tag target lines with spaCy and write 6 output files', 'run file_writer to write a list of lines to a file with newline separators', 'review tag_and_write to understand how verbs, nouns, and adjectives are extracted and saved', 'run the CLI script with --input and --output args to process ELI5 JSON data into source and target files', 'create source and target files from questions, documents, and answers for a named dataset split', 'create multitask source and target files combining language modeling, seq2seq, and masking tasks for training', 'create multitask training pairs with language modeling and seq2seq task prefixes from questions, documents, and answers', 'create a masked language modeling pair by replacing 15 percent of tokens in a document with [MASK]']
```

Usage

```
{'run_pos_tag_cli': 'run the pos_tag module with --input, --output, and --dataset-name args to tag POS', 'run_open_files': 'run open_files to read the first 2000 lines of target and source dataset files', 'run_tag_and_write': 'run tag_and_write to POS-tag target lines with spaCy and write 6 output files', 'run_file_writer': 'run file_writer to write a list of lines to a file with newline separators', 'review_tag_and_write': 'review tag_and_write to understand how verbs, nouns, and adjectives are extracted and saved'}
```

## File: facebookresearch_eli5/model_code/process_data_to_source_target.py

Prompts

```
['run the rouge_calculation function to compute ROUGE scores between hypotheses and references', 'run the open_data function to read aligned hypothesis and reference files line by line', 'run the prepare function to stem all tokens in hypotheses and references using PorterStemmer', 'run the CLI module with --hypotheses and --references flags to compute ROUGE scores', 'review the rouge_calculation function that uses the rouge library to compute averaged ROUGE scores', 'run the pos_tag module with --input, --output, and --dataset-name args to tag POS', 'run open_files to read the first 2000 lines of target and source dataset files', 'run tag_and_write to POS-tag target lines with spaCy and write 6 output files', 'run file_writer to write a list of lines to a file with newline separators', 'review tag_and_write to understand how verbs, nouns, and adjectives are extracted and saved', 'run the CLI script with --input and --output args to process ELI5 JSON data into source and target files', 'create source and target files from questions, documents, and answers for a named dataset split', 'create multitask source and target files combining language modeling, seq2seq, and masking tasks for training', 'create multitask training pairs with language modeling and seq2seq task prefixes from questions, documents, and answers', 'create a masked language modeling pair by replacing 15 percent of tokens in a document with [MASK]']
```

Usage

```
{'run_process_data_to_source_target': 'run the CLI script with --input and --output args to process ELI5 JSON data into source and target files', 'create_form_source_target': 'create source and target files from questions, documents, and answers for a named dataset split', 'create_form_multitask_source_target': 'create multitask source and target files combining language modeling, seq2seq, and masking tasks for training', 'create_form_multitask': 'create multitask training pairs with language modeling and seq2seq task prefixes from questions, documents, and answers', 'create_masking_tokens': 'create a masked language modeling pair by replacing 15 percent of tokens in a document with [MASK]'}
```

