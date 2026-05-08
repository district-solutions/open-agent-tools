# Agent Python Tools

- repo: facebookresearch/cruxeval
- repo_uri: https://github.com/facebookresearch/cruxeval

## File: facebookresearch_cruxeval/inference/tasks/base.py

Prompts

```
['create a subclass of Task that implements get_prompt and get_reference for a new benchmark', 'implement the get_dataset abstract method to return an iterable of dataset samples', 'implement the get_prompt method to build a prompt string from a dataset document', 'implement the process_results method to evaluate generations against ground truth references', 'implement the postprocess_generation method to clean up LM code generation output', 'create an InputPrediction task instance with chain-of-thought prompting enabled for CRUXEval input prediction', 'get the prompt for a dataset document using direct or chain-of-thought input prediction format', 'postprocess a model generation by stripping the prompt and extracting the answer from bracket tags', 'get the reference tuple of code, input, and output for a dataset document', 'get the test dataset split for the CRUXEval input prediction task', 'create an OutputPrediction task instance with chain-of-thought or phind output mode enabled', 'get a prompt for output prediction given code and input using direct or chain-of-thought style', 'postprocess an LLM generation by stripping the prompt and extracting the answer after ANSWER or == markers', 'get the reference tuple of code, input, and expected output for a dataset document', 'run the output prediction task to evaluate model generations against references from the CRUXEval dataset']
```

Usage

```
{'create_Task_subclass': 'create a subclass of Task that implements get_prompt and get_reference for a new benchmark', 'implement_get_dataset': 'implement the get_dataset abstract method to return an iterable of dataset samples', 'implement_get_prompt': 'implement the get_prompt method to build a prompt string from a dataset document', 'implement_process_results': 'implement the process_results method to evaluate generations against ground truth references', 'implement_postprocess_generation': 'implement the postprocess_generation method to clean up LM code generation output'}
```

## File: facebookresearch_cruxeval/inference/tasks/input_prediction.py

Prompts

```
['create a subclass of Task that implements get_prompt and get_reference for a new benchmark', 'implement the get_dataset abstract method to return an iterable of dataset samples', 'implement the get_prompt method to build a prompt string from a dataset document', 'implement the process_results method to evaluate generations against ground truth references', 'implement the postprocess_generation method to clean up LM code generation output', 'create an InputPrediction task instance with chain-of-thought prompting enabled for CRUXEval input prediction', 'get the prompt for a dataset document using direct or chain-of-thought input prediction format', 'postprocess a model generation by stripping the prompt and extracting the answer from bracket tags', 'get the reference tuple of code, input, and output for a dataset document', 'get the test dataset split for the CRUXEval input prediction task', 'create an OutputPrediction task instance with chain-of-thought or phind output mode enabled', 'get a prompt for output prediction given code and input using direct or chain-of-thought style', 'postprocess an LLM generation by stripping the prompt and extracting the answer after ANSWER or == markers', 'get the reference tuple of code, input, and expected output for a dataset document', 'run the output prediction task to evaluate model generations against references from the CRUXEval dataset']
```

Usage

```
{'create_input_prediction_task': 'create an InputPrediction task instance with chain-of-thought prompting enabled for CRUXEval input prediction', 'get_prompt_for_document': 'get the prompt for a dataset document using direct or chain-of-thought input prediction format', 'postprocess_generation_output': 'postprocess a model generation by stripping the prompt and extracting the answer from bracket tags', 'get_reference_for_document': 'get the reference tuple of code, input, and output for a dataset document', 'get_dataset_for_task': 'get the test dataset split for the CRUXEval input prediction task'}
```

## File: facebookresearch_cruxeval/inference/tasks/output_prediction.py

Prompts

```
['create a subclass of Task that implements get_prompt and get_reference for a new benchmark', 'implement the get_dataset abstract method to return an iterable of dataset samples', 'implement the get_prompt method to build a prompt string from a dataset document', 'implement the process_results method to evaluate generations against ground truth references', 'implement the postprocess_generation method to clean up LM code generation output', 'create an InputPrediction task instance with chain-of-thought prompting enabled for CRUXEval input prediction', 'get the prompt for a dataset document using direct or chain-of-thought input prediction format', 'postprocess a model generation by stripping the prompt and extracting the answer from bracket tags', 'get the reference tuple of code, input, and output for a dataset document', 'get the test dataset split for the CRUXEval input prediction task', 'create an OutputPrediction task instance with chain-of-thought or phind output mode enabled', 'get a prompt for output prediction given code and input using direct or chain-of-thought style', 'postprocess an LLM generation by stripping the prompt and extracting the answer after ANSWER or == markers', 'get the reference tuple of code, input, and expected output for a dataset document', 'run the output prediction task to evaluate model generations against references from the CRUXEval dataset']
```

Usage

```
{'create_output_prediction_task': 'create an OutputPrediction task instance with chain-of-thought or phind output mode enabled', 'get_prompt_for_code_input': 'get a prompt for output prediction given code and input using direct or chain-of-thought style', 'postprocess_llm_generation': 'postprocess an LLM generation by stripping the prompt and extracting the answer after ANSWER or == markers', 'get_reference_for_doc': 'get the reference tuple of code, input, and expected output for a dataset document', 'run_output_prediction_evaluation': 'run the output prediction task to evaluate model generations against references from the CRUXEval dataset'}
```

