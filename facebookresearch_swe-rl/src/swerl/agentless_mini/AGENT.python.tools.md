# Agent Python Tools

- repo: facebookresearch/swe-rl
- repo_uri: https://github.com/facebookresearch/swe-rl

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/localize.py

Prompts

```
['run file-level localization to find relevant source files for a bug using an LLM', 'run localization on a single SWE-bench bug instance to identify the files that need fixing', 'run the localization pipeline on all SWE-bench instances and write results to a JSONL file', 'run the localize module from the command line with bench and inference arguments', 'review the localize_files function that sends LLM requests with project structure to find relevant files', 'run the repair pipeline to generate patches for SWE-bench instances using localization output', 'process a single localization result to generate model predictions for code repair', 'construct a token-bounded file context from predicted files for model input', 'post process raw model output to extract edited files and new contents from diff commands', 'post process repair output to generate git diffs and validate syntax for selected samples', 'run the majority voting reranker to select best patches from model outputs using regression and reproduction test results', 'normalize all model-generated patches in parallel across multiple output folders using ThreadPoolExecutor', 'load normalized patches and regression/reproduction test results from JSONL files into execution_results for reranking', 'get all unique patches for an instance by normalized_patch or raw patch with optional deduplication', 'select the most frequently occurring patch via majority voting with first-appearance tie-breaking for an instance']
```

Usage

```
{'run_localize_files': 'run file-level localization to find relevant source files for a bug using an LLM', 'run_localize_instance': 'run localization on a single SWE-bench bug instance to identify the files that need fixing', 'run_localize_main': 'run the localization pipeline on all SWE-bench instances and write results to a JSONL file', 'run_localize_cli': 'run the localize module from the command line with bench and inference arguments', 'review_localize_files': 'review the localize_files function that sends LLM requests with project structure to find relevant files'}
```

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/repair.py

Prompts

```
['run file-level localization to find relevant source files for a bug using an LLM', 'run localization on a single SWE-bench bug instance to identify the files that need fixing', 'run the localization pipeline on all SWE-bench instances and write results to a JSONL file', 'run the localize module from the command line with bench and inference arguments', 'review the localize_files function that sends LLM requests with project structure to find relevant files', 'run the repair pipeline to generate patches for SWE-bench instances using localization output', 'process a single localization result to generate model predictions for code repair', 'construct a token-bounded file context from predicted files for model input', 'post process raw model output to extract edited files and new contents from diff commands', 'post process repair output to generate git diffs and validate syntax for selected samples', 'run the majority voting reranker to select best patches from model outputs using regression and reproduction test results', 'normalize all model-generated patches in parallel across multiple output folders using ThreadPoolExecutor', 'load normalized patches and regression/reproduction test results from JSONL files into execution_results for reranking', 'get all unique patches for an instance by normalized_patch or raw patch with optional deduplication', 'select the most frequently occurring patch via majority voting with first-appearance tie-breaking for an instance']
```

Usage

```
{'run_repair_pipeline': 'run the repair pipeline to generate patches for SWE-bench instances using localization output', 'process_loc_instance': 'process a single localization result to generate model predictions for code repair', 'construct_file_context': 'construct a token-bounded file context from predicted files for model input', 'post_process_multifile_repair': 'post process raw model output to extract edited files and new contents from diff commands', 'post_process_repair_output': 'post process repair output to generate git diffs and validate syntax for selected samples'}
```

## File: facebookresearch_swe-rl/src/swerl/agentless_mini/rerank.py

Prompts

```
['run file-level localization to find relevant source files for a bug using an LLM', 'run localization on a single SWE-bench bug instance to identify the files that need fixing', 'run the localization pipeline on all SWE-bench instances and write results to a JSONL file', 'run the localize module from the command line with bench and inference arguments', 'review the localize_files function that sends LLM requests with project structure to find relevant files', 'run the repair pipeline to generate patches for SWE-bench instances using localization output', 'process a single localization result to generate model predictions for code repair', 'construct a token-bounded file context from predicted files for model input', 'post process raw model output to extract edited files and new contents from diff commands', 'post process repair output to generate git diffs and validate syntax for selected samples', 'run the majority voting reranker to select best patches from model outputs using regression and reproduction test results', 'normalize all model-generated patches in parallel across multiple output folders using ThreadPoolExecutor', 'load normalized patches and regression/reproduction test results from JSONL files into execution_results for reranking', 'get all unique patches for an instance by normalized_patch or raw patch with optional deduplication', 'select the most frequently occurring patch via majority voting with first-appearance tie-breaking for an instance']
```

Usage

```
{'run_rerank_majority_voting': 'run the majority voting reranker to select best patches from model outputs using regression and reproduction test results', 'normalize_patches_parallel': 'normalize all model-generated patches in parallel across multiple output folders using ThreadPoolExecutor', 'load_results_with_rankers': 'load normalized patches and regression/reproduction test results from JSONL files into execution_results for reranking', 'get_all_patches_deduplicated': 'get all unique patches for an instance by normalized_patch or raw patch with optional deduplication', 'get_majority_voted_patch': 'select the most frequently occurring patch via majority voting with first-appearance tie-breaking for an instance'}
```

