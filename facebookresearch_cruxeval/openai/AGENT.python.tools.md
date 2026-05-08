# Agent Python Tools

- repo: facebookresearch/cruxeval
- repo_uri: https://github.com/facebookresearch/cruxeval

## File: facebookresearch_cruxeval/openai/openai_prompt.py

Prompts

```
['call the OpenAI chat completions API with a system prompt, user prompt, temperature, and model', 'batch prompt a list of queries using direct output format and extract answers via double equals', 'batch prompt a list of queries using chain of thought output format and extract answers', 'batch prompt a list of queries using direct input format and extract function predictions', 'batch prompt a list of queries using chain of thought input format and extract function predictions', 'run the OpenAI batch prompt evaluation on the CRUXEval dataset with a specified model and temperature', 'run the OpenAI chain-of-thought input mode evaluation on the CRUXEval dataset with GPT models', 'run the OpenAI direct output mode evaluation on the CRUXEval dataset without chain-of-thought', 'get the save directory path for model generations based on mode, model, cot, and temperature', 'run the OpenAI evaluation across all model, mode, cot, and temperature combinations using itertools product']
```

Usage

```
{'call_openai_api': 'call the OpenAI chat completions API with a system prompt, user prompt, temperature, and model', 'batch_prompt_direct_output': 'batch prompt a list of queries using direct output format and extract answers via double equals', 'batch_prompt_cot_output': 'batch prompt a list of queries using chain of thought output format and extract answers', 'batch_prompt_direct_input': 'batch prompt a list of queries using direct input format and extract function predictions', 'batch_prompt_cot_input': 'batch prompt a list of queries using chain of thought input format and extract function predictions'}
```

## File: facebookresearch_cruxeval/openai/openai_run.py

Prompts

```
['call the OpenAI chat completions API with a system prompt, user prompt, temperature, and model', 'batch prompt a list of queries using direct output format and extract answers via double equals', 'batch prompt a list of queries using chain of thought output format and extract answers', 'batch prompt a list of queries using direct input format and extract function predictions', 'batch prompt a list of queries using chain of thought input format and extract function predictions', 'run the OpenAI batch prompt evaluation on the CRUXEval dataset with a specified model and temperature', 'run the OpenAI chain-of-thought input mode evaluation on the CRUXEval dataset with GPT models', 'run the OpenAI direct output mode evaluation on the CRUXEval dataset without chain-of-thought', 'get the save directory path for model generations based on mode, model, cot, and temperature', 'run the OpenAI evaluation across all model, mode, cot, and temperature combinations using itertools product']
```

Usage

```
{'run_openai_batch': 'run the OpenAI batch prompt evaluation on the CRUXEval dataset with a specified model and temperature', 'run_openai_cot_input': 'run the OpenAI chain-of-thought input mode evaluation on the CRUXEval dataset with GPT models', 'run_openai_direct_output': 'run the OpenAI direct output mode evaluation on the CRUXEval dataset without chain-of-thought', 'get_save_dir_path': 'get the save directory path for model generations based on mode, model, cot, and temperature', 'run_openai_all_combinations': 'run the OpenAI evaluation across all model, mode, cot, and temperature combinations using itertools product'}
```

