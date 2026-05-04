# Agent Python Tools

- repo: facebookresearch/deepconf
- repo_uri: https://github.com/facebookresearch/deepconf

## File: facebookresearch_deepconf/examples/example_analyze_online.py

Prompts

```
['run the DeepThinkLLM online results analyzer with output_dir, max_qid, and rids arguments', 'check for missing qid and rid pickle result file combinations in an output directory', 'analyze token usage statistics including total, warmup, and final tokens across DeepThinkLLM results', 'analyze accuracy of different voting methods from DeepThinkLLM evaluation results', 'analyze detailed timing information including generation, processing, and throughput metrics from results', 'run the DeepThinkLLM results analyzer on pickle files in an output directory with specified qid and rid ranges', 'check for missing qid and rid combination files in the DeepThink output directory and report coverage statistics', 'run DeepThinkLLM in offline mode to process a single question from a JSONL dataset', 'prepare a chat template prompt for a DeepSeek model using the tokenizer and system message', 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate multiple voting method results against a ground truth answer and return correctness', 'check if a model answer equals ground truth using LaTeX parsing and math equality', 'run DeepThinkLLM in online mode to process a single question from a JSONL dataset', 'evaluate confidence-based methods including warmup traces and early stopped traces accuracy', 'run the DeepThinkLLM online baseline to process a single question with a fixed trace budget and no early exit', 'check if a model answer equals the ground truth using LaTeX parsing and mathematical equivalence']
```

Usage

```
{'run_deepthink_online_analysis': 'run the DeepThinkLLM online results analyzer with output_dir, max_qid, and rids arguments', 'check_missing_result_files': 'check for missing qid and rid pickle result file combinations in an output directory', 'analyze_token_usage': 'analyze token usage statistics including total, warmup, and final tokens across DeepThinkLLM results', 'analyze_voting_methods': 'analyze accuracy of different voting methods from DeepThinkLLM evaluation results', 'analyze_timing_details': 'analyze detailed timing information including generation, processing, and throughput metrics from results'}
```

## File: facebookresearch_deepconf/examples/example_analyze_online_baseline.py

Prompts

```
['run the DeepThinkLLM online results analyzer with output_dir, max_qid, and rids arguments', 'check for missing qid and rid pickle result file combinations in an output directory', 'analyze token usage statistics including total, warmup, and final tokens across DeepThinkLLM results', 'analyze accuracy of different voting methods from DeepThinkLLM evaluation results', 'analyze detailed timing information including generation, processing, and throughput metrics from results', 'run the DeepThinkLLM results analyzer on pickle files in an output directory with specified qid and rid ranges', 'check for missing qid and rid combination files in the DeepThink output directory and report coverage statistics', 'run DeepThinkLLM in offline mode to process a single question from a JSONL dataset', 'prepare a chat template prompt for a DeepSeek model using the tokenizer and system message', 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate multiple voting method results against a ground truth answer and return correctness', 'check if a model answer equals ground truth using LaTeX parsing and math equality', 'run DeepThinkLLM in online mode to process a single question from a JSONL dataset', 'evaluate confidence-based methods including warmup traces and early stopped traces accuracy', 'run the DeepThinkLLM online baseline to process a single question with a fixed trace budget and no early exit', 'check if a model answer equals the ground truth using LaTeX parsing and mathematical equivalence']
```

Usage

```
{'analyze_deepthink_results': 'run the DeepThinkLLM results analyzer on pickle files in an output directory with specified qid and rid ranges', 'check_missing_files': 'check for missing qid and rid combination files in the DeepThink output directory and report coverage statistics', 'analyze_token_usage': 'analyze token usage statistics including total, warmup, and final tokens across DeepThink result files', 'analyze_timing_details': 'analyze detailed timing information including generation time, processing time, and throughput metrics from DeepThink results', 'analyze_voting_methods': 'analyze accuracy of different voting methods from DeepThink evaluation results and compare performance across methods'}
```

## File: facebookresearch_deepconf/examples/example_offline.py

Prompts

```
['run the DeepThinkLLM online results analyzer with output_dir, max_qid, and rids arguments', 'check for missing qid and rid pickle result file combinations in an output directory', 'analyze token usage statistics including total, warmup, and final tokens across DeepThinkLLM results', 'analyze accuracy of different voting methods from DeepThinkLLM evaluation results', 'analyze detailed timing information including generation, processing, and throughput metrics from results', 'run the DeepThinkLLM results analyzer on pickle files in an output directory with specified qid and rid ranges', 'check for missing qid and rid combination files in the DeepThink output directory and report coverage statistics', 'run DeepThinkLLM in offline mode to process a single question from a JSONL dataset', 'prepare a chat template prompt for a DeepSeek model using the tokenizer and system message', 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate multiple voting method results against a ground truth answer and return correctness', 'check if a model answer equals ground truth using LaTeX parsing and math equality', 'run DeepThinkLLM in online mode to process a single question from a JSONL dataset', 'evaluate confidence-based methods including warmup traces and early stopped traces accuracy', 'run the DeepThinkLLM online baseline to process a single question with a fixed trace budget and no early exit', 'check if a model answer equals the ground truth using LaTeX parsing and mathematical equivalence']
```

Usage

```
{'run_deepthink_offline': 'run DeepThinkLLM in offline mode to process a single question from a JSONL dataset', 'prepare_prompt_deepseek': 'prepare a chat template prompt for a DeepSeek model using the tokenizer and system message', 'prepare_prompt_gpt': 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate_voting_results': 'evaluate multiple voting method results against a ground truth answer and return correctness', 'equal_func_answer': 'check if a model answer equals ground truth using LaTeX parsing and math equality'}
```

## File: facebookresearch_deepconf/examples/example_online.py

Prompts

```
['run the DeepThinkLLM online results analyzer with output_dir, max_qid, and rids arguments', 'check for missing qid and rid pickle result file combinations in an output directory', 'analyze token usage statistics including total, warmup, and final tokens across DeepThinkLLM results', 'analyze accuracy of different voting methods from DeepThinkLLM evaluation results', 'analyze detailed timing information including generation, processing, and throughput metrics from results', 'run the DeepThinkLLM results analyzer on pickle files in an output directory with specified qid and rid ranges', 'check for missing qid and rid combination files in the DeepThink output directory and report coverage statistics', 'run DeepThinkLLM in offline mode to process a single question from a JSONL dataset', 'prepare a chat template prompt for a DeepSeek model using the tokenizer and system message', 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate multiple voting method results against a ground truth answer and return correctness', 'check if a model answer equals ground truth using LaTeX parsing and math equality', 'run DeepThinkLLM in online mode to process a single question from a JSONL dataset', 'evaluate confidence-based methods including warmup traces and early stopped traces accuracy', 'run the DeepThinkLLM online baseline to process a single question with a fixed trace budget and no early exit', 'check if a model answer equals the ground truth using LaTeX parsing and mathematical equivalence']
```

Usage

```
{'run_deepthink_online': 'run DeepThinkLLM in online mode to process a single question from a JSONL dataset', 'prepare_prompt_deepseek': 'prepare a chat template prompt for a DeepSeek model using the tokenizer and question', 'prepare_prompt_gpt': 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate_voting_results': 'evaluate voting results against ground truth and return correctness with confidence scores', 'evaluate_confidence_methods': 'evaluate confidence-based methods including warmup traces and early stopped traces accuracy'}
```

## File: facebookresearch_deepconf/examples/example_online_baseline.py

Prompts

```
['run the DeepThinkLLM online results analyzer with output_dir, max_qid, and rids arguments', 'check for missing qid and rid pickle result file combinations in an output directory', 'analyze token usage statistics including total, warmup, and final tokens across DeepThinkLLM results', 'analyze accuracy of different voting methods from DeepThinkLLM evaluation results', 'analyze detailed timing information including generation, processing, and throughput metrics from results', 'run the DeepThinkLLM results analyzer on pickle files in an output directory with specified qid and rid ranges', 'check for missing qid and rid combination files in the DeepThink output directory and report coverage statistics', 'run DeepThinkLLM in offline mode to process a single question from a JSONL dataset', 'prepare a chat template prompt for a DeepSeek model using the tokenizer and system message', 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate multiple voting method results against a ground truth answer and return correctness', 'check if a model answer equals ground truth using LaTeX parsing and math equality', 'run DeepThinkLLM in online mode to process a single question from a JSONL dataset', 'evaluate confidence-based methods including warmup traces and early stopped traces accuracy', 'run the DeepThinkLLM online baseline to process a single question with a fixed trace budget and no early exit', 'check if a model answer equals the ground truth using LaTeX parsing and mathematical equivalence']
```

Usage

```
{'run_deepthink_online_baseline': 'run the DeepThinkLLM online baseline to process a single question with a fixed trace budget and no early exit', 'prepare_prompt_deepseek': 'prepare a chat template prompt for a DeepSeek model given a question and tokenizer', 'prepare_prompt_gpt': 'prepare a chat template prompt for a GPT model with configurable reasoning effort', 'evaluate_voting_results': 'evaluate multiple voting method results against a ground truth answer and return correctness for each method', 'equal_func_answer_check': 'check if a model answer equals the ground truth using LaTeX parsing and mathematical equivalence'}
```

