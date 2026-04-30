# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/eval/llama3_eval.py

Prompts

```
['run the benchmark evaluation for a specified task like mmlu or gsm8k against a model provider', 'analyze saved model responses and print macro and micro average accuracy scores', 'create an AsyncOpenAI client for a given provider such as sgl, oai, or b10', 'extract the multiple-choice answer from an MMLU model completion response', 'extract the final numerical answer from a GSM8K model completion response', 'run the LooGLE long-context QA benchmark against an OpenAI-compatible API and cache responses', 'analyse cached LooGLE benchmark responses using BERTScore F1 scoring', 'fetch an LLM response for a context-question pair and cache it as a pickle file', 'get an AsyncOpenAI client configured with an API URL and optional API key', 'get the LooGLE longdep_qa test dataset for long-context question answering']
```

Usage

```
{'run_benchmark_eval': 'run the benchmark evaluation for a specified task like mmlu or gsm8k against a model provider', 'analyze_evaluation_results': 'analyze saved model responses and print macro and micro average accuracy scores', 'create_openai_client': 'create an AsyncOpenAI client for a given provider such as sgl, oai, or b10', 'extract_mmlu_answer': 'extract the multiple-choice answer from an MMLU model completion response', 'extract_gsm8k_answer': 'extract the final numerical answer from a GSM8K model completion response'}
```

## File: sgl-project_sglang/python/sglang/eval/loogle_eval.py

Prompts

```
['run the benchmark evaluation for a specified task like mmlu or gsm8k against a model provider', 'analyze saved model responses and print macro and micro average accuracy scores', 'create an AsyncOpenAI client for a given provider such as sgl, oai, or b10', 'extract the multiple-choice answer from an MMLU model completion response', 'extract the final numerical answer from a GSM8K model completion response', 'run the LooGLE long-context QA benchmark against an OpenAI-compatible API and cache responses', 'analyse cached LooGLE benchmark responses using BERTScore F1 scoring', 'fetch an LLM response for a context-question pair and cache it as a pickle file', 'get an AsyncOpenAI client configured with an API URL and optional API key', 'get the LooGLE longdep_qa test dataset for long-context question answering']
```

Usage

```
{'run_benchmark_loogle_eval': 'run the LooGLE long-context QA benchmark against an OpenAI-compatible API and cache responses', 'analyse_loogle_eval': 'analyse cached LooGLE benchmark responses using BERTScore F1 scoring', 'fetch_response_loogle_eval': 'fetch an LLM response for a context-question pair and cache it as a pickle file', 'get_client_loogle_eval': 'get an AsyncOpenAI client configured with an API URL and optional API key', 'get_dataset_loogle_eval': 'get the LooGLE longdep_qa test dataset for long-context question answering'}
```

