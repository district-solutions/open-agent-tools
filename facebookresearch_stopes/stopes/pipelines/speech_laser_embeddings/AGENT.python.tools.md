# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/pipelines/speech_laser_embeddings/speech_laser_embeddings.py

Prompts

```
['run the speech laser embeddings pipeline to encode audio files from TSV manifests into embeddings', 'create a ComputeEmbedding job that encodes a single audio manifest file using a LASER checkpoint', 'schedule multiple ComputeEmbedding jobs across language directories using a Hydra launcher for batch processing', 'get the appropriate LASER checkpoint file name for a given language code like en or ru', 'split TSV manifest files into numbered chunks for parallel processing across language directories', 'split TSV files into chunks for parallel processing across multiple language directions', 'check if all chunk files exist for a given TSV file and number of chunks', 'split TSV files by comma-separated language directions like hr-en,ro-en,es-en into numbered chunks', 'split TSV files in a data directory into 16 chunks with residue in the last chunk', 'check if chunk files named stem_0.tsv through stem_N.tsv exist in the TSV file parent directory']
```

Usage

```
{'run_speech_laser_embeddings_pipeline': 'run the speech laser embeddings pipeline to encode audio files from TSV manifests into embeddings', 'create_compute_embedding_job': 'create a ComputeEmbedding job that encodes a single audio manifest file using a LASER checkpoint', 'schedule_embedding_jobs': 'schedule multiple ComputeEmbedding jobs across language directories using a Hydra launcher for batch processing', 'get_checkpoint_file_by_lang': 'get the appropriate LASER checkpoint file name for a given language code like en or ru', 'split_tsv_files_for_chunks': 'split TSV manifest files into numbered chunks for parallel processing across language directories'}
```

## File: facebookresearch_stopes/stopes/pipelines/speech_laser_embeddings/utils.py

Prompts

```
['run the speech laser embeddings pipeline to encode audio files from TSV manifests into embeddings', 'create a ComputeEmbedding job that encodes a single audio manifest file using a LASER checkpoint', 'schedule multiple ComputeEmbedding jobs across language directories using a Hydra launcher for batch processing', 'get the appropriate LASER checkpoint file name for a given language code like en or ru', 'split TSV manifest files into numbered chunks for parallel processing across language directories', 'split TSV files into chunks for parallel processing across multiple language directions', 'check if all chunk files exist for a given TSV file and number of chunks', 'split TSV files by comma-separated language directions like hr-en,ro-en,es-en into numbered chunks', 'split TSV files in a data directory into 16 chunks with residue in the last chunk', 'check if chunk files named stem_0.tsv through stem_N.tsv exist in the TSV file parent directory']
```

Usage

```
{'split_tsv_files': 'split TSV files into chunks for parallel processing across multiple language directions', 'chunk_files_exist': 'check if all chunk files exist for a given TSV file and number of chunks', 'split_tsv_files_lang_dirs': 'split TSV files by comma-separated language directions like hr-en,ro-en,es-en into numbered chunks', 'split_tsv_files_data_dir': 'split TSV files in a data directory into 16 chunks with residue in the last chunk', 'chunk_files_exist_path': 'check if chunk files named stem_0.tsv through stem_N.tsv exist in the TSV file parent directory'}
```

