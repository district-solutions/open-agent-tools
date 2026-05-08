# Agent Python Tools

- repo: facebookresearch/blt
- repo_uri: https://github.com/facebookresearch/blt

## File: facebookresearch_blt/bytelatent/preprocess/data_pipeline.py

Prompts

```
['run the Luigi pipeline to shard all datasets in the DATASETS list into 2.5GB chunks', 'run the ShardDataset Luigi wrapper task to shard a specific dataset by name', 'run the ShardDatasetChunk task to split a single chunk file into 2.5GB shards', 'list all chunk JSONL files matching the pattern *.chunk.*.jsonl for a given dataset', 'create a ChunkFile external Luigi task that references an existing data chunk file path', 'create an FSSpecTarget instance with a file path to wrap fsspec for Luigi compatibility', 'create an FSSpecTarget with a custom fsspec AbstractFileSystem like S3 or GCS', 'use FSSpecFileSystem to check if a given path exists on the underlying fsspec filesystem', 'use FSSpecFileSystem to list directory contents at a given path via fsspec', 'open a file through FSSpecTarget using the open method with a read or write mode', 'run parallel SLURM jobs to preprocess entropy data from JSONL shard files into Arrow format', 'submit a PreprocessEntropiesJob to a SLURM executor for processing a single shard file', 'check which shard files have corresponding Arrow complete output files in the output directory', 'chunk a list of items into batches of a specified size for parallel processing', 'review the PreprocessEntropiesJob class that wraps subprocess calls to the preprocess_entropies module', 'run the CLI tool to preprocess entropies from a JSONL input file to a PyArrow output file', 'get the best available ID key name from a document dictionary for sample matching', 'extract the string ID value from a document dictionary using the best available key', 'extract the text content from a document dictionary using the text or content key', 'iterate over documents in a JSONL file using an fsspec filesystem abstraction']
```

Usage

```
{'run_shard_all_datasets': 'run the Luigi pipeline to shard all datasets in the DATASETS list into 2.5GB chunks', 'run_shard_dataset': 'run the ShardDataset Luigi wrapper task to shard a specific dataset by name', 'run_shard_dataset_chunk': 'run the ShardDatasetChunk task to split a single chunk file into 2.5GB shards', 'list_dataset_shards': 'list all chunk JSONL files matching the pattern *.chunk.*.jsonl for a given dataset', 'create_chunk_file_task': 'create a ChunkFile external Luigi task that references an existing data chunk file path'}
```

## File: facebookresearch_blt/bytelatent/preprocess/fsspec_target.py

Prompts

```
['run the Luigi pipeline to shard all datasets in the DATASETS list into 2.5GB chunks', 'run the ShardDataset Luigi wrapper task to shard a specific dataset by name', 'run the ShardDatasetChunk task to split a single chunk file into 2.5GB shards', 'list all chunk JSONL files matching the pattern *.chunk.*.jsonl for a given dataset', 'create a ChunkFile external Luigi task that references an existing data chunk file path', 'create an FSSpecTarget instance with a file path to wrap fsspec for Luigi compatibility', 'create an FSSpecTarget with a custom fsspec AbstractFileSystem like S3 or GCS', 'use FSSpecFileSystem to check if a given path exists on the underlying fsspec filesystem', 'use FSSpecFileSystem to list directory contents at a given path via fsspec', 'open a file through FSSpecTarget using the open method with a read or write mode', 'run parallel SLURM jobs to preprocess entropy data from JSONL shard files into Arrow format', 'submit a PreprocessEntropiesJob to a SLURM executor for processing a single shard file', 'check which shard files have corresponding Arrow complete output files in the output directory', 'chunk a list of items into batches of a specified size for parallel processing', 'review the PreprocessEntropiesJob class that wraps subprocess calls to the preprocess_entropies module', 'run the CLI tool to preprocess entropies from a JSONL input file to a PyArrow output file', 'get the best available ID key name from a document dictionary for sample matching', 'extract the string ID value from a document dictionary using the best available key', 'extract the text content from a document dictionary using the text or content key', 'iterate over documents in a JSONL file using an fsspec filesystem abstraction']
```

Usage

```
{'create_FSSpecTarget_with_path': 'create an FSSpecTarget instance with a file path to wrap fsspec for Luigi compatibility', 'create_FSSpecTarget_with_custom_fs': 'create an FSSpecTarget with a custom fsspec AbstractFileSystem like S3 or GCS', 'use_FSSpecFileSystem_exists': 'use FSSpecFileSystem to check if a given path exists on the underlying fsspec filesystem', 'use_FSSpecFileSystem_listdir': 'use FSSpecFileSystem to list directory contents at a given path via fsspec', 'open_FSSpecTarget_file': 'open a file through FSSpecTarget using the open method with a read or write mode'}
```

## File: facebookresearch_blt/bytelatent/preprocess/parallel_entropies.py

Prompts

```
['run the Luigi pipeline to shard all datasets in the DATASETS list into 2.5GB chunks', 'run the ShardDataset Luigi wrapper task to shard a specific dataset by name', 'run the ShardDatasetChunk task to split a single chunk file into 2.5GB shards', 'list all chunk JSONL files matching the pattern *.chunk.*.jsonl for a given dataset', 'create a ChunkFile external Luigi task that references an existing data chunk file path', 'create an FSSpecTarget instance with a file path to wrap fsspec for Luigi compatibility', 'create an FSSpecTarget with a custom fsspec AbstractFileSystem like S3 or GCS', 'use FSSpecFileSystem to check if a given path exists on the underlying fsspec filesystem', 'use FSSpecFileSystem to list directory contents at a given path via fsspec', 'open a file through FSSpecTarget using the open method with a read or write mode', 'run parallel SLURM jobs to preprocess entropy data from JSONL shard files into Arrow format', 'submit a PreprocessEntropiesJob to a SLURM executor for processing a single shard file', 'check which shard files have corresponding Arrow complete output files in the output directory', 'chunk a list of items into batches of a specified size for parallel processing', 'review the PreprocessEntropiesJob class that wraps subprocess calls to the preprocess_entropies module', 'run the CLI tool to preprocess entropies from a JSONL input file to a PyArrow output file', 'get the best available ID key name from a document dictionary for sample matching', 'extract the string ID value from a document dictionary using the best available key', 'extract the text content from a document dictionary using the text or content key', 'iterate over documents in a JSONL file using an fsspec filesystem abstraction']
```

Usage

```
{'run_parallel_entropy_preprocessing': 'run parallel SLURM jobs to preprocess entropy data from JSONL shard files into Arrow format', 'submit_preprocess_entropies_job': 'submit a PreprocessEntropiesJob to a SLURM executor for processing a single shard file', 'check_entropy_output_files': 'check which shard files have corresponding Arrow complete output files in the output directory', 'chunk_items_for_batching': 'chunk a list of items into batches of a specified size for parallel processing', 'review_preprocess_entropies_job_class': 'review the PreprocessEntropiesJob class that wraps subprocess calls to the preprocess_entropies module'}
```

## File: facebookresearch_blt/bytelatent/preprocess/preprocess_entropies.py

Prompts

```
['run the Luigi pipeline to shard all datasets in the DATASETS list into 2.5GB chunks', 'run the ShardDataset Luigi wrapper task to shard a specific dataset by name', 'run the ShardDatasetChunk task to split a single chunk file into 2.5GB shards', 'list all chunk JSONL files matching the pattern *.chunk.*.jsonl for a given dataset', 'create a ChunkFile external Luigi task that references an existing data chunk file path', 'create an FSSpecTarget instance with a file path to wrap fsspec for Luigi compatibility', 'create an FSSpecTarget with a custom fsspec AbstractFileSystem like S3 or GCS', 'use FSSpecFileSystem to check if a given path exists on the underlying fsspec filesystem', 'use FSSpecFileSystem to list directory contents at a given path via fsspec', 'open a file through FSSpecTarget using the open method with a read or write mode', 'run parallel SLURM jobs to preprocess entropy data from JSONL shard files into Arrow format', 'submit a PreprocessEntropiesJob to a SLURM executor for processing a single shard file', 'check which shard files have corresponding Arrow complete output files in the output directory', 'chunk a list of items into batches of a specified size for parallel processing', 'review the PreprocessEntropiesJob class that wraps subprocess calls to the preprocess_entropies module', 'run the CLI tool to preprocess entropies from a JSONL input file to a PyArrow output file', 'get the best available ID key name from a document dictionary for sample matching', 'extract the string ID value from a document dictionary using the best available key', 'extract the text content from a document dictionary using the text or content key', 'iterate over documents in a JSONL file using an fsspec filesystem abstraction']
```

Usage

```
{'run_preprocess_entropies': 'run the CLI tool to preprocess entropies from a JSONL input file to a PyArrow output file', 'get_id_key': 'get the best available ID key name from a document dictionary for sample matching', 'get_id_from_doc': 'extract the string ID value from a document dictionary using the best available key', 'get_text': 'extract the text content from a document dictionary using the text or content key', 'jsonl_file_iterator': 'iterate over documents in a JSONL file using an fsspec filesystem abstraction'}
```

