# Agent Python Tools

- repo: facebookresearch/paq
- repo_uri: https://github.com/facebookresearch/paq

## File: facebookresearch_paq/paq/download.py

Prompts

```
['download a named PAQ resource like paq.PAQ or models.retrievers.retriever_multi_base_256 using the download function', 'download a single file from an S3 URL to a specified output directory using download_file', 'extract a tar.gz archive file to its parent directory using the untar function', 'decompress a gzip file to a specified output path using the unpack function', 'run the download CLI tool with --name to fetch a PAQ resource by key name', 'load a JSONL file into a list of dictionaries using fast or memory-friendly mode', 'dump a list of dictionaries to a JSONL file with one JSON object per line', 'load a DPR TSV file with passage id, text, and title into a list of dictionaries', 'parse PyTorch vector embeddings from a directory of chunked tensor files into a single tensor', 'convert a PyTorch model to FP16 precision using Apex AMP or native half conversion']
```

Usage

```
{'download_resource_by_key': 'download a named PAQ resource like paq.PAQ or models.retrievers.retriever_multi_base_256 using the download function', 'download_single_file': 'download a single file from an S3 URL to a specified output directory using download_file', 'extract_tar_gz': 'extract a tar.gz archive file to its parent directory using the untar function', 'unpack_gzip_file': 'decompress a gzip file to a specified output path using the unpack function', 'run_download_cli': 'run the download CLI tool with --name to fetch a PAQ resource by key name'}
```

## File: facebookresearch_paq/paq/paq_utils.py

Prompts

```
['download a named PAQ resource like paq.PAQ or models.retrievers.retriever_multi_base_256 using the download function', 'download a single file from an S3 URL to a specified output directory using download_file', 'extract a tar.gz archive file to its parent directory using the untar function', 'decompress a gzip file to a specified output path using the unpack function', 'run the download CLI tool with --name to fetch a PAQ resource by key name', 'load a JSONL file into a list of dictionaries using fast or memory-friendly mode', 'dump a list of dictionaries to a JSONL file with one JSON object per line', 'load a DPR TSV file with passage id, text, and title into a list of dictionaries', 'parse PyTorch vector embeddings from a directory of chunked tensor files into a single tensor', 'convert a PyTorch model to FP16 precision using Apex AMP or native half conversion']
```

Usage

```
{'load_jsonl_file': 'load a JSONL file into a list of dictionaries using fast or memory-friendly mode', 'dump_jsonl_file': 'dump a list of dictionaries to a JSONL file with one JSON object per line', 'load_dpr_tsv': 'load a DPR TSV file with passage id, text, and title into a list of dictionaries', 'parse_vectors_from_directory': 'parse PyTorch vector embeddings from a directory of chunked tensor files into a single tensor', 'convert_model_to_fp16': 'convert a PyTorch model to FP16 precision using Apex AMP or native half conversion'}
```

