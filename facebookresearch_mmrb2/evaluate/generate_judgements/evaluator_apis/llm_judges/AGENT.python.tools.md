# Agent Python Tools

- repo: facebookresearch/mmrb2
- repo_uri: https://github.com/facebookresearch/mmrb2

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/llm_judges/api_pairwise_evaluator.py

Prompts

```
['run a pairwise evaluation of two model responses using GPT-4o or Gemini for a given task type', 'generate a text response from an LLM model given a structured prompt list', 'parse JSON from LLM output that may be wrapped in markdown code blocks', 'create a GPT-4o based pairwise evaluator instance for comparing model responses', 'create a Gemini 2.5 Flash based pairwise evaluator instance for comparing model responses', 'get the LLM evaluation prompt for comparing two AI-generated image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI image editing responses using a 4-criteria rubric', 'get the LLM evaluation prompt for comparing two AI interleaved text-and-image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI assistant responses to a visual reasoning question', 'summarize the four evaluation prompt functions and their respective criteria for image gen, edit, interleaved, and reasoning tasks', 'initialize a LocalModelManager with a model name and optional GPU device ID', 'generate a text response from a local VLM model using a text prompt', 'generate a response from a local VLM model using text and image inputs', 'configure model loading with automatic GPU detection or explicit device assignment', 'review the LocalModelManager class for loading and running local VLM models on GPU', 'create a LocalPairwiseEvaluator instance with a specified model name and optional device ID', 'create a Qwen3VL8BPairwiseEvaluator instance for pairwise evaluation using the Qwen3-VL-8B model', 'get the evaluator name property that returns the model name with pairwise evaluator suffix']
```

Usage

```
{'pairwise_evaluate_responses': 'run a pairwise evaluation of two model responses using GPT-4o or Gemini for a given task type', 'generate_response_from_prompt': 'generate a text response from an LLM model given a structured prompt list', 'parse_llm_json_output': 'parse JSON from LLM output that may be wrapped in markdown code blocks', 'create_gpt4o_pairwise_evaluator': 'create a GPT-4o based pairwise evaluator instance for comparing model responses', 'create_gemini_pairwise_evaluator': 'create a Gemini 2.5 Flash based pairwise evaluator instance for comparing model responses'}
```

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/llm_judges/evaluation_prompts.py

Prompts

```
['run a pairwise evaluation of two model responses using GPT-4o or Gemini for a given task type', 'generate a text response from an LLM model given a structured prompt list', 'parse JSON from LLM output that may be wrapped in markdown code blocks', 'create a GPT-4o based pairwise evaluator instance for comparing model responses', 'create a Gemini 2.5 Flash based pairwise evaluator instance for comparing model responses', 'get the LLM evaluation prompt for comparing two AI-generated image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI image editing responses using a 4-criteria rubric', 'get the LLM evaluation prompt for comparing two AI interleaved text-and-image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI assistant responses to a visual reasoning question', 'summarize the four evaluation prompt functions and their respective criteria for image gen, edit, interleaved, and reasoning tasks', 'initialize a LocalModelManager with a model name and optional GPU device ID', 'generate a text response from a local VLM model using a text prompt', 'generate a response from a local VLM model using text and image inputs', 'configure model loading with automatic GPU detection or explicit device assignment', 'review the LocalModelManager class for loading and running local VLM models on GPU', 'create a LocalPairwiseEvaluator instance with a specified model name and optional device ID', 'create a Qwen3VL8BPairwiseEvaluator instance for pairwise evaluation using the Qwen3-VL-8B model', 'get the evaluator name property that returns the model name with pairwise evaluator suffix']
```

Usage

```
{'get_image_gen_prompt': 'get the LLM evaluation prompt for comparing two AI-generated image responses using a 7-criteria rubric', 'get_image_edit_prompt': 'get the LLM evaluation prompt for comparing two AI image editing responses using a 4-criteria rubric', 'get_interleaved_prompt': 'get the LLM evaluation prompt for comparing two AI interleaved text-and-image responses using a 7-criteria rubric', 'get_reasoning_prompt': 'get the LLM evaluation prompt for comparing two AI assistant responses to a visual reasoning question', 'summarize_evaluation_prompts': 'summarize the four evaluation prompt functions and their respective criteria for image gen, edit, interleaved, and reasoning tasks'}
```

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/llm_judges/local_models.py

Prompts

```
['run a pairwise evaluation of two model responses using GPT-4o or Gemini for a given task type', 'generate a text response from an LLM model given a structured prompt list', 'parse JSON from LLM output that may be wrapped in markdown code blocks', 'create a GPT-4o based pairwise evaluator instance for comparing model responses', 'create a Gemini 2.5 Flash based pairwise evaluator instance for comparing model responses', 'get the LLM evaluation prompt for comparing two AI-generated image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI image editing responses using a 4-criteria rubric', 'get the LLM evaluation prompt for comparing two AI interleaved text-and-image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI assistant responses to a visual reasoning question', 'summarize the four evaluation prompt functions and their respective criteria for image gen, edit, interleaved, and reasoning tasks', 'initialize a LocalModelManager with a model name and optional GPU device ID', 'generate a text response from a local VLM model using a text prompt', 'generate a response from a local VLM model using text and image inputs', 'configure model loading with automatic GPU detection or explicit device assignment', 'review the LocalModelManager class for loading and running local VLM models on GPU', 'create a LocalPairwiseEvaluator instance with a specified model name and optional device ID', 'create a Qwen3VL8BPairwiseEvaluator instance for pairwise evaluation using the Qwen3-VL-8B model', 'get the evaluator name property that returns the model name with pairwise evaluator suffix']
```

Usage

```
{'init_local_model_manager': 'initialize a LocalModelManager with a model name and optional GPU device ID', 'generate_response_with_text_prompt': 'generate a text response from a local VLM model using a text prompt', 'generate_response_with_image_prompt': 'generate a response from a local VLM model using text and image inputs', 'configure_model_loading': 'configure model loading with automatic GPU detection or explicit device assignment', 'review_local_model_manager': 'review the LocalModelManager class for loading and running local VLM models on GPU'}
```

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/llm_judges/local_pairwise_evaluator.py

Prompts

```
['run a pairwise evaluation of two model responses using GPT-4o or Gemini for a given task type', 'generate a text response from an LLM model given a structured prompt list', 'parse JSON from LLM output that may be wrapped in markdown code blocks', 'create a GPT-4o based pairwise evaluator instance for comparing model responses', 'create a Gemini 2.5 Flash based pairwise evaluator instance for comparing model responses', 'get the LLM evaluation prompt for comparing two AI-generated image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI image editing responses using a 4-criteria rubric', 'get the LLM evaluation prompt for comparing two AI interleaved text-and-image responses using a 7-criteria rubric', 'get the LLM evaluation prompt for comparing two AI assistant responses to a visual reasoning question', 'summarize the four evaluation prompt functions and their respective criteria for image gen, edit, interleaved, and reasoning tasks', 'initialize a LocalModelManager with a model name and optional GPU device ID', 'generate a text response from a local VLM model using a text prompt', 'generate a response from a local VLM model using text and image inputs', 'configure model loading with automatic GPU detection or explicit device assignment', 'review the LocalModelManager class for loading and running local VLM models on GPU', 'create a LocalPairwiseEvaluator instance with a specified model name and optional device ID', 'create a Qwen3VL8BPairwiseEvaluator instance for pairwise evaluation using the Qwen3-VL-8B model', 'get the evaluator name property that returns the model name with pairwise evaluator suffix']
```

Usage

```
{'pairwise_evaluate_responses': 'run a pairwise evaluation of two model responses using a local VLM for image or reasoning tasks', 'parse_llm_json_output': 'parse JSON from LLM output that may be wrapped in markdown code blocks', 'create_local_pairwise_evaluator': 'create a LocalPairwiseEvaluator instance with a specified model name and optional device ID', 'create_qwen3vl8b_evaluator': 'create a Qwen3VL8BPairwiseEvaluator instance for pairwise evaluation using the Qwen3-VL-8B model', 'get_evaluator_name': 'get the evaluator name property that returns the model name with pairwise evaluator suffix'}
```

