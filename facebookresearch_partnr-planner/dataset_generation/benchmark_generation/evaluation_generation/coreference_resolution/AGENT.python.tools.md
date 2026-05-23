# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/dataset_generation/benchmark_generation/evaluation_generation/coreference_resolution/coreference_resolution.py

Prompts

```
['run the CLI to resolve coreferences in a gzipped dataset and save results to a JSON file', 'create a function that resolves coreferences in text using spacy fastcoref and LingMessCoref model', 'build a function that resolves coreferences for all episode instructions in a dataset and returns episode ID to resolved text mapping', 'review the resolve_coreferences function that uses spacy and fastcoref to replace pronouns with their antecedents', 'summarize the main function that loads a gzipped dataset, resolves coreferences, and saves the output as JSON', 'run the coreference resolution script on a source directory of dataset scenes using LingMess', 'resolve coreferences for all episode instructions in a dataset and return episode ID to resolved text mapping', "extract the episode ID integer from an episode object's extra_info field", 'review the coreference resolution script that processes dataset scenes and outputs resolved coref JSON files']
```

Usage

```
{'run_coreference_resolution_cli': 'run the CLI to resolve coreferences in a gzipped dataset and save results to a JSON file', 'resolve_coreferences_function': 'create a function that resolves coreferences in text using spacy fastcoref and LingMessCoref model', 'resolve_coreferences_for_dataset_function': 'build a function that resolves coreferences for all episode instructions in a dataset and returns episode ID to resolved text mapping', 'review_resolve_coreferences': 'review the resolve_coreferences function that uses spacy and fastcoref to replace pronouns with their antecedents', 'summarize_main': 'summarize the main function that loads a gzipped dataset, resolves coreferences, and saves the output as JSON'}
```

## File: facebookresearch_partnr-planner/dataset_generation/benchmark_generation/evaluation_generation/coreference_resolution/resolve_src_dir.py

Prompts

```
['run the CLI to resolve coreferences in a gzipped dataset and save results to a JSON file', 'create a function that resolves coreferences in text using spacy fastcoref and LingMessCoref model', 'build a function that resolves coreferences for all episode instructions in a dataset and returns episode ID to resolved text mapping', 'review the resolve_coreferences function that uses spacy and fastcoref to replace pronouns with their antecedents', 'summarize the main function that loads a gzipped dataset, resolves coreferences, and saves the output as JSON', 'run the coreference resolution script on a source directory of dataset scenes using LingMess', 'resolve coreferences for all episode instructions in a dataset and return episode ID to resolved text mapping', "extract the episode ID integer from an episode object's extra_info field", 'review the coreference resolution script that processes dataset scenes and outputs resolved coref JSON files']
```

Usage

```
{'run_resolve_coref_script': 'run the coreference resolution script on a source directory of dataset scenes using LingMess', 'resolve_coreferences_function': 'resolve coreferences in text using spaCy and the fastcoref LingMess model', 'resolve_coreferences_for_dataset': 'resolve coreferences for all episode instructions in a dataset and return episode ID to resolved text mapping', 'extract_episode_id': "extract the episode ID integer from an episode object's extra_info field", 'review_resolve_src_dir': 'review the coreference resolution script that processes dataset scenes and outputs resolved coref JSON files'}
```

