# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/otb/otb_creation/create_overthink.py

Prompts

```
['run the script to generate overthinking benchmark questions using Llama-4-Maverick via vLLM', 'run process_num_options to generate domain-balanced questions for a specific mode and option count', 'start a vLLM server with the Llama-4-Maverick model using tensor parallelism across 8 GPUs', 'generate multiple choice questions with 4 options across all domains using the overthinking prompt', 'save generated question responses to a JSON file with output, num_options, mode, and domains', 'run the script to filter LLM benchmark responses using a verifier model and keep only hard questions', 'call an LLM via LiteLLM with a single message and sampling parameters', 'call an LLM in batch mode for multiple messages with configurable temperature and top_p', 'score a verifier LLM response by parsing Final Decision tags into a binary 0 or 1', 'normalize MCQ answer options from lettered keys A through L into a unified options list']
```

Usage

```
{'run_overthink_question_generation': 'run the script to generate overthinking benchmark questions using Llama-4-Maverick via vLLM', 'run_process_num_options': 'run process_num_options to generate domain-balanced questions for a specific mode and option count', 'start_vllm_server': 'start a vLLM server with the Llama-4-Maverick model using tensor parallelism across 8 GPUs', 'generate_mcq_questions': 'generate multiple choice questions with 4 options across all domains using the overthinking prompt', 'save_responses_to_json': 'save generated question responses to a JSON file with output, num_options, mode, and domains'}
```

## File: facebookresearch_ram/projects/otb/otb_creation/filter_overthink.py

Prompts

```
['run the script to generate overthinking benchmark questions using Llama-4-Maverick via vLLM', 'run process_num_options to generate domain-balanced questions for a specific mode and option count', 'start a vLLM server with the Llama-4-Maverick model using tensor parallelism across 8 GPUs', 'generate multiple choice questions with 4 options across all domains using the overthinking prompt', 'save generated question responses to a JSON file with output, num_options, mode, and domains', 'run the script to filter LLM benchmark responses using a verifier model and keep only hard questions', 'call an LLM via LiteLLM with a single message and sampling parameters', 'call an LLM in batch mode for multiple messages with configurable temperature and top_p', 'score a verifier LLM response by parsing Final Decision tags into a binary 0 or 1', 'normalize MCQ answer options from lettered keys A through L into a unified options list']
```

Usage

```
{'run_filter_overthink': 'run the script to filter LLM benchmark responses using a verifier model and keep only hard questions', 'call_llm': 'call an LLM via LiteLLM with a single message and sampling parameters', 'call_llm_mp': 'call an LLM in batch mode for multiple messages with configurable temperature and top_p', 'score_response': 'score a verifier LLM response by parsing Final Decision tags into a binary 0 or 1', 'normalize_mcq_options': 'normalize MCQ answer options from lettered keys A through L into a unified options list'}
```

