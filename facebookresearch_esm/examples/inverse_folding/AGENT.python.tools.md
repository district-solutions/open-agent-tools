# Agent Python Tools

- repo: facebookresearch/esm
- repo_uri: https://github.com/facebookresearch/esm

## File: facebookresearch_esm/examples/inverse_folding/sample_sequences.py

Prompts

```
['run sample_sequences.py to sample protein sequences from a single chain PDB structure file', 'run sample_sequences.py with --multichain-backbone to sample sequences using all chain backbones for conditioning', 'run sample_sequences.py with --temperature to control sampling diversity for protein sequence generation', 'run sample_sequences.py with --num-samples to generate multiple sampled sequences from a protein structure', 'run sample_sequences.py with --chain to target a specific chain ID in a multi-chain PDB structure', 'run the script to score variant sequences against a single chain backbone from a PDB structure', 'run the script to score variant sequences using all chain backbones from a protein complex', 'run the script to compute log likelihood and perplexity of a native sequence from a structure file', 'run the script to score all sequences from a FASTA file against a given protein structure', 'run the script with the nogpu flag to score sequences on CPU instead of GPU']
```

Usage

```
{'run_sample_sequences_singlechain': 'run sample_sequences.py to sample protein sequences from a single chain PDB structure file', 'run_sample_sequences_multichain': 'run sample_sequences.py with --multichain-backbone to sample sequences using all chain backbones for conditioning', 'run_sample_sequences_custom_temperature': 'run sample_sequences.py with --temperature to control sampling diversity for protein sequence generation', 'run_sample_sequences_batch': 'run sample_sequences.py with --num-samples to generate multiple sampled sequences from a protein structure', 'run_sample_sequences_chain': 'run sample_sequences.py with --chain to target a specific chain ID in a multi-chain PDB structure'}
```

## File: facebookresearch_esm/examples/inverse_folding/score_log_likelihoods.py

Prompts

```
['run sample_sequences.py to sample protein sequences from a single chain PDB structure file', 'run sample_sequences.py with --multichain-backbone to sample sequences using all chain backbones for conditioning', 'run sample_sequences.py with --temperature to control sampling diversity for protein sequence generation', 'run sample_sequences.py with --num-samples to generate multiple sampled sequences from a protein structure', 'run sample_sequences.py with --chain to target a specific chain ID in a multi-chain PDB structure', 'run the script to score variant sequences against a single chain backbone from a PDB structure', 'run the script to score variant sequences using all chain backbones from a protein complex', 'run the script to compute log likelihood and perplexity of a native sequence from a structure file', 'run the script to score all sequences from a FASTA file against a given protein structure', 'run the script with the nogpu flag to score sequences on CPU instead of GPU']
```

Usage

```
{'run_score_singlechain': 'run the script to score variant sequences against a single chain backbone from a PDB structure', 'run_score_multichain': 'run the script to score variant sequences using all chain backbones from a protein complex', 'run_score_native_sequence': 'run the script to compute log likelihood and perplexity of a native sequence from a structure file', 'run_score_fasta_variants': 'run the script to score all sequences from a FASTA file against a given protein structure', 'run_score_no_gpu': 'run the script with the nogpu flag to score sequences on CPU instead of GPU'}
```

