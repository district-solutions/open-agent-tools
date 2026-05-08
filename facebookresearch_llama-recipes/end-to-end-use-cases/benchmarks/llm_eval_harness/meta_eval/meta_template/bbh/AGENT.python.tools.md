# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/llm_eval_harness/meta_eval/meta_template/bbh/utils.py

Prompts

```
['extract the first final prompt string from a BBH document dictionary using doc_to_text', 'process a HuggingFace datasets Dataset to extract problem and answer columns for BBH evaluation', 'summarize the doc_to_text function that extracts input_final_prompts from a document dict', 'review the process_docs function that selects columns and maps documents for BBH benchmark datasets', 'refactor the process_docs function to avoid calling dataset.map twice with the same _process_doc']
```

Usage

```
{'extract_prompt_from_doc': 'extract the first final prompt string from a BBH document dictionary using doc_to_text', 'process_bbh_dataset': 'process a HuggingFace datasets Dataset to extract problem and answer columns for BBH evaluation', 'summarize_doc_to_text': 'summarize the doc_to_text function that extracts input_final_prompts from a document dict', 'review_process_docs': 'review the process_docs function that selects columns and maps documents for BBH benchmark datasets', 'refactor_process_docs': 'refactor the process_docs function to avoid calling dataset.map twice with the same _process_doc'}
```

