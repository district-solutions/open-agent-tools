# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/benchmarks/llm_eval_harness/meta_eval/meta_template/gpqa/utils.py

Prompts

```
['process a HuggingFace datasets Dataset for GPQA benchmark by selecting columns and extracting problem and gold answer fields', 'extract the final prompt text from a GPQA document dictionary using the input_final_prompts key', 'review the process_docs function to understand how it transforms a GPQA dataset by selecting columns and mapping documents', 'refactor the process_docs function to avoid calling dataset.map twice with the same _process_doc function', 'summarize the doc_to_text function which returns the first element of input_final_prompts from a document dict']
```

Usage

```
{'process_docs_dataset': 'process a HuggingFace datasets Dataset for GPQA benchmark by selecting columns and extracting problem and gold answer fields', 'doc_to_text_extract': 'extract the final prompt text from a GPQA document dictionary using the input_final_prompts key', 'review_process_docs': 'review the process_docs function to understand how it transforms a GPQA dataset by selecting columns and mapping documents', 'refactor_process_docs': 'refactor the process_docs function to avoid calling dataset.map twice with the same _process_doc function', 'summarize_doc_to_text': 'summarize the doc_to_text function which returns the first element of input_final_prompts from a document dict'}
```

