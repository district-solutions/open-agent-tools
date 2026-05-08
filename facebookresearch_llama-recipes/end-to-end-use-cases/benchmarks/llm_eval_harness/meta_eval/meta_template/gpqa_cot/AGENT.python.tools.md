# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/llm_eval_harness/meta_eval/meta_template/gpqa_cot/utils.py

Prompts

```
['process a HuggingFace datasets.Dataset to extract problem and gold answer columns for GPQA evaluation', 'extract the first final prompt string from a GPQA document dictionary', 'review the process_docs function that selects columns, renames is_correct, and maps documents for GPQA', 'refactor the process_docs function to avoid calling dataset.map twice with the same _process_doc', 'summarize the doc_to_text function that returns the first input_final_prompts entry from a document']
```

Usage

```
{'process_docs_dataset': 'process a HuggingFace datasets.Dataset to extract problem and gold answer columns for GPQA evaluation', 'doc_to_text_extract_prompt': 'extract the first final prompt string from a GPQA document dictionary', 'review_process_docs': 'review the process_docs function that selects columns, renames is_correct, and maps documents for GPQA', 'refactor_process_docs': 'refactor the process_docs function to avoid calling dataset.map twice with the same _process_doc', 'summarize_doc_to_text': 'summarize the doc_to_text function that returns the first input_final_prompts entry from a document'}
```

