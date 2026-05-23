# Agent Python Tools

- repo: facebookresearch/textlesslib
- repo_uri: https://github.com/facebookresearch/textlesslib

## File: facebookresearch_textlesslib/tools/distributed_transcribe/distributed.py

Prompts

```
['init a distributed process group using gloo backend from torch distributed launch or slurm env vars', 'init a distributed context from slurm environment variables and resolve the leader node address via scontrol', 'init a default non-distributed context when no torch launch or slurm env vars are present', 'check if the current process is the leader by comparing its rank to zero', 'create a frozen dataclass holding rank, local_rank, world_size, is_distributed flag, and launch mode', 'run the transcribe CLI to encode audio waveforms into pseudo-unit tokens using a manifest file', 'run the transcribe CLI with --durations flag to produce token duration streams alongside pseudo-units', 'run the transcribe CLI with --f0s flag to produce fundamental frequency streams from audio', 'run the transcribe CLI with --deduplicate to collapse consecutive repeated pseudo-unit tokens', 'run the transcribe CLI with --preserve_name to include audio file names in transcript output']
```

Usage

```
{'init_distributed_context_gloo': 'init a distributed process group using gloo backend from torch distributed launch or slurm env vars', 'init_distributed_context_slurm': 'init a distributed context from slurm environment variables and resolve the leader node address via scontrol', 'init_distributed_context_non_distributed': 'init a default non-distributed context when no torch launch or slurm env vars are present', 'DistributedContext_is_leader': 'check if the current process is the leader by comparing its rank to zero', 'DistributedContext_dataclass': 'create a frozen dataclass holding rank, local_rank, world_size, is_distributed flag, and launch mode'}
```

## File: facebookresearch_textlesslib/tools/distributed_transcribe/transcribe.py

Prompts

```
['init a distributed process group using gloo backend from torch distributed launch or slurm env vars', 'init a distributed context from slurm environment variables and resolve the leader node address via scontrol', 'init a default non-distributed context when no torch launch or slurm env vars are present', 'check if the current process is the leader by comparing its rank to zero', 'create a frozen dataclass holding rank, local_rank, world_size, is_distributed flag, and launch mode', 'run the transcribe CLI to encode audio waveforms into pseudo-unit tokens using a manifest file', 'run the transcribe CLI with --durations flag to produce token duration streams alongside pseudo-units', 'run the transcribe CLI with --f0s flag to produce fundamental frequency streams from audio', 'run the transcribe CLI with --deduplicate to collapse consecutive repeated pseudo-unit tokens', 'run the transcribe CLI with --preserve_name to include audio file names in transcript output']
```

Usage

```
{'run_distributed_transcribe': 'run the transcribe CLI to encode audio waveforms into pseudo-unit tokens using a manifest file', 'run_transcribe_with_durations': 'run the transcribe CLI with --durations flag to produce token duration streams alongside pseudo-units', 'run_transcribe_with_f0s': 'run the transcribe CLI with --f0s flag to produce fundamental frequency streams from audio', 'run_transcribe_deduplicate': 'run the transcribe CLI with --deduplicate to collapse consecutive repeated pseudo-unit tokens', 'run_transcribe_preserve_name': 'run the transcribe CLI with --preserve_name to include audio file names in transcript output'}
```

