# Agent Python Tools

- repo: facebookresearch/pytorch-biggraph
- repo_uri: https://github.com/facebookresearch/pytorch-biggraph

## File: facebookresearch_pytorch-biggraph/torchbiggraph/converters/dictionary.py

Prompts

```
['create a Dictionary from a list of words with optional partition count for distributed indexing', 'get the integer index ID for a given word from the Dictionary', 'get the partition number and local index for a word in the Dictionary', 'get the list of words belonging to a specific partition of the Dictionary', 'get the number of words in a specific partition of the Dictionary', 'run the export_to_tsv CLI tool to export PyTorch BigGraph entity embeddings and relation types to TSV files', 'run make_tsv to load a trained model checkpoint and export entity and relation type embeddings to TSV output files', 'run make_tsv_for_entities to export all entity embeddings from each partition of a MultiRelationEmbedder model to a TSV file', 'run make_tsv_for_relation_types to export relation type operator parameters from a trained model to a TSV file', 'run write to output a tab-separated row with string keys and float values to a TSV file', 'convert raw edge list files into partitioned TorchBigGraph entity and edge storage files', 'parse a TorchBigGraph config dictionary into entity schemas, relation schemas, and path strings', 'create a TSVEdgelistReader to read tab-separated edge list files with configurable column indices', 'create a ParquetEdgelistReader to read edge list data from Apache Parquet files', 'collect and filter relation types from edge files into a Dictionary with optional minimum count', 'download a file from a URL to a local directory with a progress bar', 'extract a gzipped file to its uncompressed path and optionally remove the original', 'extract a gzipped tar archive to its parent directory', 'create a callback function that updates a tqdm progress bar during file downloads', 'review the download_url function to understand how it handles URL parsing and file caching']
```

Usage

```
{'create_dictionary': 'create a Dictionary from a list of words with optional partition count for distributed indexing', 'get_id_word': 'get the integer index ID for a given word from the Dictionary', 'get_partition_word': 'get the partition number and local index for a word in the Dictionary', 'get_part_list': 'get the list of words belonging to a specific partition of the Dictionary', 'part_size': 'get the number of words in a specific partition of the Dictionary'}
```

## File: facebookresearch_pytorch-biggraph/torchbiggraph/converters/export_to_tsv.py

Prompts

```
['create a Dictionary from a list of words with optional partition count for distributed indexing', 'get the integer index ID for a given word from the Dictionary', 'get the partition number and local index for a word in the Dictionary', 'get the list of words belonging to a specific partition of the Dictionary', 'get the number of words in a specific partition of the Dictionary', 'run the export_to_tsv CLI tool to export PyTorch BigGraph entity embeddings and relation types to TSV files', 'run make_tsv to load a trained model checkpoint and export entity and relation type embeddings to TSV output files', 'run make_tsv_for_entities to export all entity embeddings from each partition of a MultiRelationEmbedder model to a TSV file', 'run make_tsv_for_relation_types to export relation type operator parameters from a trained model to a TSV file', 'run write to output a tab-separated row with string keys and float values to a TSV file', 'convert raw edge list files into partitioned TorchBigGraph entity and edge storage files', 'parse a TorchBigGraph config dictionary into entity schemas, relation schemas, and path strings', 'create a TSVEdgelistReader to read tab-separated edge list files with configurable column indices', 'create a ParquetEdgelistReader to read edge list data from Apache Parquet files', 'collect and filter relation types from edge files into a Dictionary with optional minimum count', 'download a file from a URL to a local directory with a progress bar', 'extract a gzipped file to its uncompressed path and optionally remove the original', 'extract a gzipped tar archive to its parent directory', 'create a callback function that updates a tqdm progress bar during file downloads', 'review the download_url function to understand how it handles URL parsing and file caching']
```

Usage

```
{'run_export_to_tsv_cli': 'run the export_to_tsv CLI tool to export PyTorch BigGraph entity embeddings and relation types to TSV files', 'run_make_tsv': 'run make_tsv to load a trained model checkpoint and export entity and relation type embeddings to TSV output files', 'run_make_tsv_for_entities': 'run make_tsv_for_entities to export all entity embeddings from each partition of a MultiRelationEmbedder model to a TSV file', 'run_make_tsv_for_relation_types': 'run make_tsv_for_relation_types to export relation type operator parameters from a trained model to a TSV file', 'run_write_tsv_row': 'run write to output a tab-separated row with string keys and float values to a TSV file'}
```

## File: facebookresearch_pytorch-biggraph/torchbiggraph/converters/importers.py

Prompts

```
['create a Dictionary from a list of words with optional partition count for distributed indexing', 'get the integer index ID for a given word from the Dictionary', 'get the partition number and local index for a word in the Dictionary', 'get the list of words belonging to a specific partition of the Dictionary', 'get the number of words in a specific partition of the Dictionary', 'run the export_to_tsv CLI tool to export PyTorch BigGraph entity embeddings and relation types to TSV files', 'run make_tsv to load a trained model checkpoint and export entity and relation type embeddings to TSV output files', 'run make_tsv_for_entities to export all entity embeddings from each partition of a MultiRelationEmbedder model to a TSV file', 'run make_tsv_for_relation_types to export relation type operator parameters from a trained model to a TSV file', 'run write to output a tab-separated row with string keys and float values to a TSV file', 'convert raw edge list files into partitioned TorchBigGraph entity and edge storage files', 'parse a TorchBigGraph config dictionary into entity schemas, relation schemas, and path strings', 'create a TSVEdgelistReader to read tab-separated edge list files with configurable column indices', 'create a ParquetEdgelistReader to read edge list data from Apache Parquet files', 'collect and filter relation types from edge files into a Dictionary with optional minimum count', 'download a file from a URL to a local directory with a progress bar', 'extract a gzipped file to its uncompressed path and optionally remove the original', 'extract a gzipped tar archive to its parent directory', 'create a callback function that updates a tqdm progress bar during file downloads', 'review the download_url function to understand how it handles URL parsing and file caching']
```

Usage

```
{'convert_input_data': 'convert raw edge list files into partitioned TorchBigGraph entity and edge storage files', 'parse_config_partial': 'parse a TorchBigGraph config dictionary into entity schemas, relation schemas, and path strings', 'create_TSVEdgelistReader': 'create a TSVEdgelistReader to read tab-separated edge list files with configurable column indices', 'create_ParquetEdgelistReader': 'create a ParquetEdgelistReader to read edge list data from Apache Parquet files', 'collect_relation_types': 'collect and filter relation types from edge files into a Dictionary with optional minimum count'}
```

## File: facebookresearch_pytorch-biggraph/torchbiggraph/converters/utils.py

Prompts

```
['create a Dictionary from a list of words with optional partition count for distributed indexing', 'get the integer index ID for a given word from the Dictionary', 'get the partition number and local index for a word in the Dictionary', 'get the list of words belonging to a specific partition of the Dictionary', 'get the number of words in a specific partition of the Dictionary', 'run the export_to_tsv CLI tool to export PyTorch BigGraph entity embeddings and relation types to TSV files', 'run make_tsv to load a trained model checkpoint and export entity and relation type embeddings to TSV output files', 'run make_tsv_for_entities to export all entity embeddings from each partition of a MultiRelationEmbedder model to a TSV file', 'run make_tsv_for_relation_types to export relation type operator parameters from a trained model to a TSV file', 'run write to output a tab-separated row with string keys and float values to a TSV file', 'convert raw edge list files into partitioned TorchBigGraph entity and edge storage files', 'parse a TorchBigGraph config dictionary into entity schemas, relation schemas, and path strings', 'create a TSVEdgelistReader to read tab-separated edge list files with configurable column indices', 'create a ParquetEdgelistReader to read edge list data from Apache Parquet files', 'collect and filter relation types from edge files into a Dictionary with optional minimum count', 'download a file from a URL to a local directory with a progress bar', 'extract a gzipped file to its uncompressed path and optionally remove the original', 'extract a gzipped tar archive to its parent directory', 'create a callback function that updates a tqdm progress bar during file downloads', 'review the download_url function to understand how it handles URL parsing and file caching']
```

Usage

```
{'download_file_from_url': 'download a file from a URL to a local directory with a progress bar', 'extract_gzip_file': 'extract a gzipped file to its uncompressed path and optionally remove the original', 'extract_tar_archive': 'extract a gzipped tar archive to its parent directory', 'create_progress_bar_callback': 'create a callback function that updates a tqdm progress bar during file downloads', 'review_download_url_function': 'review the download_url function to understand how it handles URL parsing and file caching'}
```

