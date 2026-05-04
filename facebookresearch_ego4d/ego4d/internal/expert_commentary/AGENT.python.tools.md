# Agent Python Tools

- repo: facebookresearch/ego4d
- repo_uri: https://github.com/facebookresearch/ego4d

## File: facebookresearch_ego4d/ego4d/internal/expert_commentary/export.py

Prompts

```
['run the export function to export expert commentary data for released takes to a target directory', 'run the check_export function to verify all exported commentary files exist at their destination paths', 'build a pipeline to export expert commentary transcriptions and recordings for released Ego4D takes', 'review the export function that organizes commentaries by take name and generates copy commands', 'refactor the export function to accept takes path and released takes path as CLI arguments', 'extract expert commentary zip files from an input directory into a structured output directory', 'load all raw commentary directory paths from an extracted directory and return them sorted', 'load unique commentary directories deduplicated by user and video name keeping the latest dataset version', 'review the extract_commentaries function to handle bad zip files and merge directories during extraction', 'refactor load_uniq_commentaries to support additional deduplication criteria beyond user_id and video_name', 'run transcribe_commentaries on a folder of webm files using a whisper model and save results to transcriptions.json', 'run run_worker to transcribe a batch of commentary folders with a specified whisper model and device', 'run the CLI module with --commentary_root to schedule distributed whisper transcription jobs via submitit on a SLURM cluster', 'refactor transcribe_commentaries to skip files that already have existing transcriptions in the output JSON', 'review run_worker to replace whisper with whisperX or another transcription model for improved accuracy']
```

Usage

```
{'run_export_commentaries': 'run the export function to export expert commentary data for released takes to a target directory', 'run_check_export': 'run the check_export function to verify all exported commentary files exist at their destination paths', 'build_export_pipeline': 'build a pipeline to export expert commentary transcriptions and recordings for released Ego4D takes', 'review_export_function': 'review the export function that organizes commentaries by take name and generates copy commands', 'refactor_export_for_cli': 'refactor the export function to accept takes path and released takes path as CLI arguments'}
```

## File: facebookresearch_ego4d/ego4d/internal/expert_commentary/extract.py

Prompts

```
['run the export function to export expert commentary data for released takes to a target directory', 'run the check_export function to verify all exported commentary files exist at their destination paths', 'build a pipeline to export expert commentary transcriptions and recordings for released Ego4D takes', 'review the export function that organizes commentaries by take name and generates copy commands', 'refactor the export function to accept takes path and released takes path as CLI arguments', 'extract expert commentary zip files from an input directory into a structured output directory', 'load all raw commentary directory paths from an extracted directory and return them sorted', 'load unique commentary directories deduplicated by user and video name keeping the latest dataset version', 'review the extract_commentaries function to handle bad zip files and merge directories during extraction', 'refactor load_uniq_commentaries to support additional deduplication criteria beyond user_id and video_name', 'run transcribe_commentaries on a folder of webm files using a whisper model and save results to transcriptions.json', 'run run_worker to transcribe a batch of commentary folders with a specified whisper model and device', 'run the CLI module with --commentary_root to schedule distributed whisper transcription jobs via submitit on a SLURM cluster', 'refactor transcribe_commentaries to skip files that already have existing transcriptions in the output JSON', 'review run_worker to replace whisper with whisperX or another transcription model for improved accuracy']
```

Usage

```
{'extract_commentaries': 'extract expert commentary zip files from an input directory into a structured output directory', 'load_all_raw_commentaries': 'load all raw commentary directory paths from an extracted directory and return them sorted', 'load_uniq_commentaries': 'load unique commentary directories deduplicated by user and video name keeping the latest dataset version', 'review_extract_commentaries': 'review the extract_commentaries function to handle bad zip files and merge directories during extraction', 'refactor_load_uniq_commentaries': 'refactor load_uniq_commentaries to support additional deduplication criteria beyond user_id and video_name'}
```

## File: facebookresearch_ego4d/ego4d/internal/expert_commentary/transcribe.py

Prompts

```
['run the export function to export expert commentary data for released takes to a target directory', 'run the check_export function to verify all exported commentary files exist at their destination paths', 'build a pipeline to export expert commentary transcriptions and recordings for released Ego4D takes', 'review the export function that organizes commentaries by take name and generates copy commands', 'refactor the export function to accept takes path and released takes path as CLI arguments', 'extract expert commentary zip files from an input directory into a structured output directory', 'load all raw commentary directory paths from an extracted directory and return them sorted', 'load unique commentary directories deduplicated by user and video name keeping the latest dataset version', 'review the extract_commentaries function to handle bad zip files and merge directories during extraction', 'refactor load_uniq_commentaries to support additional deduplication criteria beyond user_id and video_name', 'run transcribe_commentaries on a folder of webm files using a whisper model and save results to transcriptions.json', 'run run_worker to transcribe a batch of commentary folders with a specified whisper model and device', 'run the CLI module with --commentary_root to schedule distributed whisper transcription jobs via submitit on a SLURM cluster', 'refactor transcribe_commentaries to skip files that already have existing transcriptions in the output JSON', 'review run_worker to replace whisper with whisperX or another transcription model for improved accuracy']
```

Usage

```
{'run_transcribe_commentaries': 'run transcribe_commentaries on a folder of webm files using a whisper model and save results to transcriptions.json', 'run_run_worker': 'run run_worker to transcribe a batch of commentary folders with a specified whisper model and device', 'run_cli_transcription': 'run the CLI module with --commentary_root to schedule distributed whisper transcription jobs via submitit on a SLURM cluster', 'refactor_transcribe_commentaries': 'refactor transcribe_commentaries to skip files that already have existing transcriptions in the output JSON', 'review_run_worker': 'review run_worker to replace whisper with whisperX or another transcription model for improved accuracy'}
```

