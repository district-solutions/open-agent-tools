# Agent Python Tools

- repo: facebookresearch/mmrb2
- repo_uri: https://github.com/facebookresearch/mmrb2

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluate.py

Prompts

```
['run pairwise judgement generation for MMRB2 benchmark using an LLM evaluator on a pairs JSON file', 'run pairwise evaluation on the first N samples using --max_samples to limit processing', 'run pairwise evaluation generating multiple judgements per pair using the --n flag', 'fix relative image paths in content by prepending a base directory to non-absolute paths', 'evaluate multiple prompt response tuples with a pairwise evaluator and return results', 'run pairwise evaluations across multiple GPUs using the multi_gpu_evaluate CLI with an evaluator name and pairs file', 'merge partial JSON result files from multiple worker processes into a single output file', 'run a worker process that evaluates a chunk of pairs on a specific GPU device', 'run the multi GPU evaluation CLI with arguments for evaluator name, task type, pairs path, and output path', 'call multi_gpu_evaluate programmatically to process pairs in parallel with a specified number of GPUs']
```

Usage

```
{'run_pairwise_judgement_evaluation': 'run pairwise judgement generation for MMRB2 benchmark using an LLM evaluator on a pairs JSON file', 'run_evaluation_with_max_samples': 'run pairwise evaluation on the first N samples using --max_samples to limit processing', 'run_evaluation_with_multiple_judgements': 'run pairwise evaluation generating multiple judgements per pair using the --n flag', 'fix_relative_path': 'fix relative image paths in content by prepending a base directory to non-absolute paths', 'evaluate_pairs': 'evaluate multiple prompt response tuples with a pairwise evaluator and return results'}
```

## File: facebookresearch_mmrb2/evaluate/generate_judgements/multi_gpu_evaluate.py

Prompts

```
['run pairwise judgement generation for MMRB2 benchmark using an LLM evaluator on a pairs JSON file', 'run pairwise evaluation on the first N samples using --max_samples to limit processing', 'run pairwise evaluation generating multiple judgements per pair using the --n flag', 'fix relative image paths in content by prepending a base directory to non-absolute paths', 'evaluate multiple prompt response tuples with a pairwise evaluator and return results', 'run pairwise evaluations across multiple GPUs using the multi_gpu_evaluate CLI with an evaluator name and pairs file', 'merge partial JSON result files from multiple worker processes into a single output file', 'run a worker process that evaluates a chunk of pairs on a specific GPU device', 'run the multi GPU evaluation CLI with arguments for evaluator name, task type, pairs path, and output path', 'call multi_gpu_evaluate programmatically to process pairs in parallel with a specified number of GPUs']
```

Usage

```
{'run_multi_gpu_evaluate': 'run pairwise evaluations across multiple GPUs using the multi_gpu_evaluate CLI with an evaluator name and pairs file', 'run_merge_results': 'merge partial JSON result files from multiple worker processes into a single output file', 'run_process_pairs_worker': 'run a worker process that evaluates a chunk of pairs on a specific GPU device', 'run_main_cli': 'run the multi GPU evaluation CLI with arguments for evaluator name, task type, pairs path, and output path', 'run_multi_gpu_evaluate_programmatic': 'call multi_gpu_evaluate programmatically to process pairs in parallel with a specified number of GPUs'}
```

