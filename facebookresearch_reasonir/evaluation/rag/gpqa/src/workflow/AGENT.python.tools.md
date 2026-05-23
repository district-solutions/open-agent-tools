# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/evaluation/rag/gpqa/src/workflow/naive_rag.py

Prompts

```
['run the NaiveRAG pipeline on a dataset by calling run() with a list of question dicts', 'run web search retrieval for all questions using run_search() with Bing or offline_massiveds engine', 'prepare full context prompts by calling prepare_full_context() with data and retrieved search results', 'generate LLM answers for a list of input prompts using llm_generate() with OpenAI-style chat completions', 'build a RAG instruction prompt from a question and documents using get_naive_rag_instruction()']
```

Usage

```
{'run_naive_rag_pipeline': 'run the NaiveRAG pipeline on a dataset by calling run() with a list of question dicts', 'run_search_retrieval': 'run web search retrieval for all questions using run_search() with Bing or offline_massiveds engine', 'prepare_rag_prompts': 'prepare full context prompts by calling prepare_full_context() with data and retrieved search results', 'generate_llm_answers': 'generate LLM answers for a list of input prompts using llm_generate() with OpenAI-style chat completions', 'build_rag_instruction': 'build a RAG instruction prompt from a question and documents using get_naive_rag_instruction()'}
```

