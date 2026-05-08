# Agent Python Tools

- repo: facebookresearch/esm
- repo_uri: https://github.com/facebookresearch/esm

## File: facebookresearch_esm/scripts/extract.py

Prompts

```
['run the extract script to get per-token representations for protein sequences in a FASTA file', 'run the extract script to compute mean representations across tokens for each protein sequence', 'run the extract script to predict contact maps between residue pairs in protein sequences', 'run the extract script to extract beginning-of-sequence representations from a pretrained ESM model', 'run the extract script to pull representations from multiple specified layers of a pretrained ESM model', 'run ESMFold protein structure prediction on a FASTA file and output PDB files to a directory', 'run ESMFold with CPU offloading enabled to reduce GPU memory usage during structure prediction', 'run ESMFold with chunked axial attention to reduce memory from O(L^2) to O(L) for long sequences', 'create batched sequence groups from a list of header-sequence tuples with a max tokens per batch limit', 'enable CPU offloading on an ESM model using FullyShardedDataParallel to wrap each transformer layer']
```

Usage

```
{'run_extract_per_tok_representations': 'run the extract script to get per-token representations for protein sequences in a FASTA file', 'run_extract_mean_representations': 'run the extract script to compute mean representations across tokens for each protein sequence', 'run_extract_contacts': 'run the extract script to predict contact maps between residue pairs in protein sequences', 'run_extract_bos_representations': 'run the extract script to extract beginning-of-sequence representations from a pretrained ESM model', 'run_extract_multi_layer': 'run the extract script to pull representations from multiple specified layers of a pretrained ESM model'}
```

## File: facebookresearch_esm/scripts/fold.py

Prompts

```
['run the extract script to get per-token representations for protein sequences in a FASTA file', 'run the extract script to compute mean representations across tokens for each protein sequence', 'run the extract script to predict contact maps between residue pairs in protein sequences', 'run the extract script to extract beginning-of-sequence representations from a pretrained ESM model', 'run the extract script to pull representations from multiple specified layers of a pretrained ESM model', 'run ESMFold protein structure prediction on a FASTA file and output PDB files to a directory', 'run ESMFold with CPU offloading enabled to reduce GPU memory usage during structure prediction', 'run ESMFold with chunked axial attention to reduce memory from O(L^2) to O(L) for long sequences', 'create batched sequence groups from a list of header-sequence tuples with a max tokens per batch limit', 'enable CPU offloading on an ESM model using FullyShardedDataParallel to wrap each transformer layer']
```

Usage

```
{'run_esmfold_prediction': 'run ESMFold protein structure prediction on a FASTA file and output PDB files to a directory', 'run_cpu_offloading': 'run ESMFold with CPU offloading enabled to reduce GPU memory usage during structure prediction', 'run_chunked_attention': 'run ESMFold with chunked axial attention to reduce memory from O(L^2) to O(L) for long sequences', 'create_batched_sequences': 'create batched sequence groups from a list of header-sequence tuples with a max tokens per batch limit', 'enable_cpu_offloading': 'enable CPU offloading on an ESM model using FullyShardedDataParallel to wrap each transformer layer'}
```

