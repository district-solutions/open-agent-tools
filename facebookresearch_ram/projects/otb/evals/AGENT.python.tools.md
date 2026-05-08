# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/otb/evals/math_eval.py

Prompts

```
['evaluate model responses against ground truth math answers using math_verify parse and verify', 'parse a math answer string into a normalized form using math_verify parse for comparison', 'verify if a parsed model response matches the parsed ground truth math answer', 'run math evaluation on a row containing answer and response fields to get accuracy score', 'refactor eval_math to support additional response formats or scoring strategies', 'run the eval_overthink function to verify student answers against ground truth using a verifier model', 'start a vLLM verifier server on a given port with a specified model path', 'call the verifier model via LiteLLM with retry logic to get a verification response', 'parse a verifier model response into a binary score of 0 or 1', 'postprocess an LLM response by stripping tags, truncating, and extracting boxed content', 'eval the average thinking tokens in model responses using a tokenizer and model name', 'eval tokens for an o3 model response row that includes pre-computed token counts', 'eval tokens across multiple responses in a single row by averaging think token counts', 'review the eval_tokens function to understand how it splits responses on the closing answer tag', 'refactor eval_tokens to support additional model families beyond o3 with custom token extraction logic', 'run eval_underthink to score model responses against reasoning_gym puzzles using boxed answer extraction', 'extract the first or last boxed LaTeX answer from a model response string', 'format a model response for specific puzzle types like ab or mini_sudoku', 'review the eval_underthink function to understand how it scores responses against reasoning_gym datasets', 'refactor _extract_boxed to support additional LaTeX answer extraction patterns beyond boxed notation']
```

Usage

```
{'eval_math_responses': 'evaluate model responses against ground truth math answers using math_verify parse and verify', 'parse_math_answer': 'parse a math answer string into a normalized form using math_verify parse for comparison', 'verify_math_correctness': 'verify if a parsed model response matches the parsed ground truth math answer', 'run_math_evaluation': 'run math evaluation on a row containing answer and response fields to get accuracy score', 'refactor_eval_math': 'refactor eval_math to support additional response formats or scoring strategies'}
```

## File: facebookresearch_ram/projects/otb/evals/overthink_eval.py

Prompts

```
['evaluate model responses against ground truth math answers using math_verify parse and verify', 'parse a math answer string into a normalized form using math_verify parse for comparison', 'verify if a parsed model response matches the parsed ground truth math answer', 'run math evaluation on a row containing answer and response fields to get accuracy score', 'refactor eval_math to support additional response formats or scoring strategies', 'run the eval_overthink function to verify student answers against ground truth using a verifier model', 'start a vLLM verifier server on a given port with a specified model path', 'call the verifier model via LiteLLM with retry logic to get a verification response', 'parse a verifier model response into a binary score of 0 or 1', 'postprocess an LLM response by stripping tags, truncating, and extracting boxed content', 'eval the average thinking tokens in model responses using a tokenizer and model name', 'eval tokens for an o3 model response row that includes pre-computed token counts', 'eval tokens across multiple responses in a single row by averaging think token counts', 'review the eval_tokens function to understand how it splits responses on the closing answer tag', 'refactor eval_tokens to support additional model families beyond o3 with custom token extraction logic', 'run eval_underthink to score model responses against reasoning_gym puzzles using boxed answer extraction', 'extract the first or last boxed LaTeX answer from a model response string', 'format a model response for specific puzzle types like ab or mini_sudoku', 'review the eval_underthink function to understand how it scores responses against reasoning_gym datasets', 'refactor _extract_boxed to support additional LaTeX answer extraction patterns beyond boxed notation']
```

Usage

```
{'run_eval_overthink': 'run the eval_overthink function to verify student answers against ground truth using a verifier model', 'run_ensure_verifier_server': 'start a vLLM verifier server on a given port with a specified model path', 'run_call_verifier': 'call the verifier model via LiteLLM with retry logic to get a verification response', 'run_score_from_verifier': 'parse a verifier model response into a binary score of 0 or 1', 'run_postprocess_response': 'postprocess an LLM response by stripping tags, truncating, and extracting boxed content'}
```

## File: facebookresearch_ram/projects/otb/evals/token_eval.py

Prompts

```
['evaluate model responses against ground truth math answers using math_verify parse and verify', 'parse a math answer string into a normalized form using math_verify parse for comparison', 'verify if a parsed model response matches the parsed ground truth math answer', 'run math evaluation on a row containing answer and response fields to get accuracy score', 'refactor eval_math to support additional response formats or scoring strategies', 'run the eval_overthink function to verify student answers against ground truth using a verifier model', 'start a vLLM verifier server on a given port with a specified model path', 'call the verifier model via LiteLLM with retry logic to get a verification response', 'parse a verifier model response into a binary score of 0 or 1', 'postprocess an LLM response by stripping tags, truncating, and extracting boxed content', 'eval the average thinking tokens in model responses using a tokenizer and model name', 'eval tokens for an o3 model response row that includes pre-computed token counts', 'eval tokens across multiple responses in a single row by averaging think token counts', 'review the eval_tokens function to understand how it splits responses on the closing answer tag', 'refactor eval_tokens to support additional model families beyond o3 with custom token extraction logic', 'run eval_underthink to score model responses against reasoning_gym puzzles using boxed answer extraction', 'extract the first or last boxed LaTeX answer from a model response string', 'format a model response for specific puzzle types like ab or mini_sudoku', 'review the eval_underthink function to understand how it scores responses against reasoning_gym datasets', 'refactor _extract_boxed to support additional LaTeX answer extraction patterns beyond boxed notation']
```

Usage

```
{'eval_tokens': 'eval the average thinking tokens in model responses using a tokenizer and model name', 'eval_tokens_o3_model': 'eval tokens for an o3 model response row that includes pre-computed token counts', 'eval_tokens_multi_response': 'eval tokens across multiple responses in a single row by averaging think token counts', 'review_eval_tokens': 'review the eval_tokens function to understand how it splits responses on the closing answer tag', 'refactor_eval_tokens': 'refactor eval_tokens to support additional model families beyond o3 with custom token extraction logic'}
```

## File: facebookresearch_ram/projects/otb/evals/underthink_eval.py

Prompts

```
['evaluate model responses against ground truth math answers using math_verify parse and verify', 'parse a math answer string into a normalized form using math_verify parse for comparison', 'verify if a parsed model response matches the parsed ground truth math answer', 'run math evaluation on a row containing answer and response fields to get accuracy score', 'refactor eval_math to support additional response formats or scoring strategies', 'run the eval_overthink function to verify student answers against ground truth using a verifier model', 'start a vLLM verifier server on a given port with a specified model path', 'call the verifier model via LiteLLM with retry logic to get a verification response', 'parse a verifier model response into a binary score of 0 or 1', 'postprocess an LLM response by stripping tags, truncating, and extracting boxed content', 'eval the average thinking tokens in model responses using a tokenizer and model name', 'eval tokens for an o3 model response row that includes pre-computed token counts', 'eval tokens across multiple responses in a single row by averaging think token counts', 'review the eval_tokens function to understand how it splits responses on the closing answer tag', 'refactor eval_tokens to support additional model families beyond o3 with custom token extraction logic', 'run eval_underthink to score model responses against reasoning_gym puzzles using boxed answer extraction', 'extract the first or last boxed LaTeX answer from a model response string', 'format a model response for specific puzzle types like ab or mini_sudoku', 'review the eval_underthink function to understand how it scores responses against reasoning_gym datasets', 'refactor _extract_boxed to support additional LaTeX answer extraction patterns beyond boxed notation']
```

Usage

```
{'eval_underthink': 'run eval_underthink to score model responses against reasoning_gym puzzles using boxed answer extraction', 'extract_boxed': 'extract the first or last boxed LaTeX answer from a model response string', 'conditional_format_answer': 'format a model response for specific puzzle types like ab or mini_sudoku', 'review_eval_underthink': 'review the eval_underthink function to understand how it scores responses against reasoning_gym datasets', 'refactor_extract_boxed': 'refactor _extract_boxed to support additional LaTeX answer extraction patterns beyond boxed notation'}
```

