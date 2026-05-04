# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/wikigraphs/scripts/build_vocab.py

Prompts

```
['run the script to build a wikitext vocabulary from the train dataset and write it to a CSV file', 'run the script to build a graph vocabulary from node and edge tokens and write it to a text file', 'run the script to build a text vocabulary from the graph-to-text paired dataset and write it to a CSV file', 'call get_vocab with a RawDataset to get a sorted list of word count tuples from the training data', 'call write_vocab with a list of word count tuples and an output path to save the vocabulary as CSV', 'run the script to compute BLEU scores on generated text samples from a checkpoint directory', 'run the eval_samples function to evaluate generated samples against ground truth and log BLEU scores', 'run the group_samples function to group generated and ground truth texts by ground truth', 'review the eval_samples function that computes BLEU scores and n-gram precision for generated text', 'review the group_samples function that groups samples by decoded ground truth text', 'run the freebase preprocess script to pair graphs with wikitext for train valid and test subsets', 'pair Freebase graphs with wikitext articles by matching normalized titles and write paired data to output', 'create graph text pairs from Freebase graphs and wikitext articles using the pair_graphs_with_wikitext function', 'normalize Freebase graph titles using normalize_freebase_string to match against wikitext article titles', 'write graph text pairs to a gzip compressed text file using write_pairs_to_gzip_txt_file', 'run the visualize_graph script to generate PDF visualizations of graph-text pairs from a dataset', 'run graph_to_dot to convert a GraphTextPair into a Graphviz dot format string', 'run format_label to normalize, truncate, and HTML-escape a node or edge label for dot output', 'run truncate to shorten a string to a configurable maximum length with ellipsis', 'run the CLI tool with graph_ids and layout flags to visualize specific graphs as PDFs']
```

Usage

```
{'build_wikitext_vocab': 'run the script to build a wikitext vocabulary from the train dataset and write it to a CSV file', 'build_graph_vocab': 'run the script to build a graph vocabulary from node and edge tokens and write it to a text file', 'build_text_vocab': 'run the script to build a text vocabulary from the graph-to-text paired dataset and write it to a CSV file', 'get_vocab': 'call get_vocab with a RawDataset to get a sorted list of word count tuples from the training data', 'write_vocab': 'call write_vocab with a list of word count tuples and an output path to save the vocabulary as CSV'}
```

## File: google-deepmind_deepmind-research/wikigraphs/scripts/compute_blue_score.py

Prompts

```
['run the script to build a wikitext vocabulary from the train dataset and write it to a CSV file', 'run the script to build a graph vocabulary from node and edge tokens and write it to a text file', 'run the script to build a text vocabulary from the graph-to-text paired dataset and write it to a CSV file', 'call get_vocab with a RawDataset to get a sorted list of word count tuples from the training data', 'call write_vocab with a list of word count tuples and an output path to save the vocabulary as CSV', 'run the script to compute BLEU scores on generated text samples from a checkpoint directory', 'run the eval_samples function to evaluate generated samples against ground truth and log BLEU scores', 'run the group_samples function to group generated and ground truth texts by ground truth', 'review the eval_samples function that computes BLEU scores and n-gram precision for generated text', 'review the group_samples function that groups samples by decoded ground truth text', 'run the freebase preprocess script to pair graphs with wikitext for train valid and test subsets', 'pair Freebase graphs with wikitext articles by matching normalized titles and write paired data to output', 'create graph text pairs from Freebase graphs and wikitext articles using the pair_graphs_with_wikitext function', 'normalize Freebase graph titles using normalize_freebase_string to match against wikitext article titles', 'write graph text pairs to a gzip compressed text file using write_pairs_to_gzip_txt_file', 'run the visualize_graph script to generate PDF visualizations of graph-text pairs from a dataset', 'run graph_to_dot to convert a GraphTextPair into a Graphviz dot format string', 'run format_label to normalize, truncate, and HTML-escape a node or edge label for dot output', 'run truncate to shorten a string to a configurable maximum length with ellipsis', 'run the CLI tool with graph_ids and layout flags to visualize specific graphs as PDFs']
```

Usage

```
{'run_compute_bleu': 'run the script to compute BLEU scores on generated text samples from a checkpoint directory', 'run_eval_samples': 'run the eval_samples function to evaluate generated samples against ground truth and log BLEU scores', 'run_group_samples': 'run the group_samples function to group generated and ground truth texts by ground truth', 'review_eval_samples': 'review the eval_samples function that computes BLEU scores and n-gram precision for generated text', 'review_group_samples': 'review the group_samples function that groups samples by decoded ground truth text'}
```

## File: google-deepmind_deepmind-research/wikigraphs/scripts/freebase_preprocess.py

Prompts

```
['run the script to build a wikitext vocabulary from the train dataset and write it to a CSV file', 'run the script to build a graph vocabulary from node and edge tokens and write it to a text file', 'run the script to build a text vocabulary from the graph-to-text paired dataset and write it to a CSV file', 'call get_vocab with a RawDataset to get a sorted list of word count tuples from the training data', 'call write_vocab with a list of word count tuples and an output path to save the vocabulary as CSV', 'run the script to compute BLEU scores on generated text samples from a checkpoint directory', 'run the eval_samples function to evaluate generated samples against ground truth and log BLEU scores', 'run the group_samples function to group generated and ground truth texts by ground truth', 'review the eval_samples function that computes BLEU scores and n-gram precision for generated text', 'review the group_samples function that groups samples by decoded ground truth text', 'run the freebase preprocess script to pair graphs with wikitext for train valid and test subsets', 'pair Freebase graphs with wikitext articles by matching normalized titles and write paired data to output', 'create graph text pairs from Freebase graphs and wikitext articles using the pair_graphs_with_wikitext function', 'normalize Freebase graph titles using normalize_freebase_string to match against wikitext article titles', 'write graph text pairs to a gzip compressed text file using write_pairs_to_gzip_txt_file', 'run the visualize_graph script to generate PDF visualizations of graph-text pairs from a dataset', 'run graph_to_dot to convert a GraphTextPair into a Graphviz dot format string', 'run format_label to normalize, truncate, and HTML-escape a node or edge label for dot output', 'run truncate to shorten a string to a configurable maximum length with ellipsis', 'run the CLI tool with graph_ids and layout flags to visualize specific graphs as PDFs']
```

Usage

```
{'run_freebase_preprocess': 'run the freebase preprocess script to pair graphs with wikitext for train valid and test subsets', 'pair_graphs_with_wikitext': 'pair Freebase graphs with wikitext articles by matching normalized titles and write paired data to output', 'create_graph_text_pairs': 'create graph text pairs from Freebase graphs and wikitext articles using the pair_graphs_with_wikitext function', 'normalize_freebase_titles': 'normalize Freebase graph titles using normalize_freebase_string to match against wikitext article titles', 'write_pairs_to_gzip': 'write graph text pairs to a gzip compressed text file using write_pairs_to_gzip_txt_file'}
```

## File: google-deepmind_deepmind-research/wikigraphs/scripts/visualize_graph.py

Prompts

```
['run the script to build a wikitext vocabulary from the train dataset and write it to a CSV file', 'run the script to build a graph vocabulary from node and edge tokens and write it to a text file', 'run the script to build a text vocabulary from the graph-to-text paired dataset and write it to a CSV file', 'call get_vocab with a RawDataset to get a sorted list of word count tuples from the training data', 'call write_vocab with a list of word count tuples and an output path to save the vocabulary as CSV', 'run the script to compute BLEU scores on generated text samples from a checkpoint directory', 'run the eval_samples function to evaluate generated samples against ground truth and log BLEU scores', 'run the group_samples function to group generated and ground truth texts by ground truth', 'review the eval_samples function that computes BLEU scores and n-gram precision for generated text', 'review the group_samples function that groups samples by decoded ground truth text', 'run the freebase preprocess script to pair graphs with wikitext for train valid and test subsets', 'pair Freebase graphs with wikitext articles by matching normalized titles and write paired data to output', 'create graph text pairs from Freebase graphs and wikitext articles using the pair_graphs_with_wikitext function', 'normalize Freebase graph titles using normalize_freebase_string to match against wikitext article titles', 'write graph text pairs to a gzip compressed text file using write_pairs_to_gzip_txt_file', 'run the visualize_graph script to generate PDF visualizations of graph-text pairs from a dataset', 'run graph_to_dot to convert a GraphTextPair into a Graphviz dot format string', 'run format_label to normalize, truncate, and HTML-escape a node or edge label for dot output', 'run truncate to shorten a string to a configurable maximum length with ellipsis', 'run the CLI tool with graph_ids and layout flags to visualize specific graphs as PDFs']
```

Usage

```
{'run_visualize_graph': 'run the visualize_graph script to generate PDF visualizations of graph-text pairs from a dataset', 'run_graph_to_dot': 'run graph_to_dot to convert a GraphTextPair into a Graphviz dot format string', 'run_format_label': 'run format_label to normalize, truncate, and HTML-escape a node or edge label for dot output', 'run_truncate': 'run truncate to shorten a string to a configurable maximum length with ellipsis', 'run_visualize_graph_cli': 'run the CLI tool with graph_ids and layout flags to visualize specific graphs as PDFs'}
```

