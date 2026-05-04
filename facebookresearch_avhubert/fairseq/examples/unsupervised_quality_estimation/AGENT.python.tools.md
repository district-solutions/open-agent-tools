# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/unsupervised_quality_estimation/meteor.py

Prompts

```
['run the meteor quality estimation tool on translation files with configurable repeat times and language', 'read translation files and group segments by repeat count into a dictionary structure', 'generate temporary reference and machine translation input files from grouped translations for meteor scoring', 'run the meteor java jar to score machine translations against references with custom parameters', 'parse meteor output files and compute average scores across all segment combinations']
```

Usage

```
{'run_meteor_quality_estimation': 'run the meteor quality estimation tool on translation files with configurable repeat times and language', 'read_translations_from_file': 'read translation files and group segments by repeat count into a dictionary structure', 'generate_meteor_input_files': 'generate temporary reference and machine translation input files from grouped translations for meteor scoring', 'run_meteor_jar_scoring': 'run the meteor java jar to score machine translations against references with custom parameters', 'parse_meteor_output_scores': 'parse meteor output files and compute average scores across all segment combinations'}
```

