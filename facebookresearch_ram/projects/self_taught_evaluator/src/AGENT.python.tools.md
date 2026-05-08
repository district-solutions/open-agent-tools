# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/self_taught_evaluator/src/prepare_dpo_data.py

Prompts

```
['run prepare_dpo_data to extract DPO training data from sampled judgements in a generation directory', 'run pair_sampling to sample a pair of outputs with different judgements from a list', 'run get_input_key to extract the system prompt and user question from a response', 'review prepare_dpo_data to understand how positive and negative examples are classified and balanced', 'refactor pair_sampling to support more than two outputs or custom label matching logic', 'run prepare_positive_data to extract SFT training data from sampled judgements using rejection sampling', 'run rejection_sampling to filter model outputs that match a given true label', 'run parse_response to extract input, output, and metadata from a vLLM response dictionary', 'review prepare_positive_data to understand how SFT data is balanced between model A and model B', 'refactor rejection_sampling to support custom majority voting thresholds for output filtering', 'run a vLLM model to judge pairs of assistant responses from a JSONL input file', 'run the model using pre-prompted inputs from a specified JSONL key instead of composing inputs', 'run the model and save judgment results to a specified output JSONL file path', 'compose vLLM plain string inputs from a list of input and response pair dictionaries', 'review the run function that loads JSONL inputs, generates outputs with vLLM, and parses judgments', 'load a JSONL file and return a list of dictionaries parsed from each line', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'prepare a chat template input string for vLLM inference using a LlamaTokenizer and two model responses', 'parse a model generation string and extract the judgement verdict as model_a, model_b, or tie', 'compute RewardBench evaluation scores from generated judgements and input prompts JSONL files']
```

Usage

```
{'run_prepare_dpo_data': 'run prepare_dpo_data to extract DPO training data from sampled judgements in a generation directory', 'run_pair_sampling': 'run pair_sampling to sample a pair of outputs with different judgements from a list', 'run_get_input_key': 'run get_input_key to extract the system prompt and user question from a response', 'review_prepare_dpo_data': 'review prepare_dpo_data to understand how positive and negative examples are classified and balanced', 'refactor_pair_sampling': 'refactor pair_sampling to support more than two outputs or custom label matching logic'}
```

## File: facebookresearch_ram/projects/self_taught_evaluator/src/prepare_sft_data.py

Prompts

```
['run prepare_dpo_data to extract DPO training data from sampled judgements in a generation directory', 'run pair_sampling to sample a pair of outputs with different judgements from a list', 'run get_input_key to extract the system prompt and user question from a response', 'review prepare_dpo_data to understand how positive and negative examples are classified and balanced', 'refactor pair_sampling to support more than two outputs or custom label matching logic', 'run prepare_positive_data to extract SFT training data from sampled judgements using rejection sampling', 'run rejection_sampling to filter model outputs that match a given true label', 'run parse_response to extract input, output, and metadata from a vLLM response dictionary', 'review prepare_positive_data to understand how SFT data is balanced between model A and model B', 'refactor rejection_sampling to support custom majority voting thresholds for output filtering', 'run a vLLM model to judge pairs of assistant responses from a JSONL input file', 'run the model using pre-prompted inputs from a specified JSONL key instead of composing inputs', 'run the model and save judgment results to a specified output JSONL file path', 'compose vLLM plain string inputs from a list of input and response pair dictionaries', 'review the run function that loads JSONL inputs, generates outputs with vLLM, and parses judgments', 'load a JSONL file and return a list of dictionaries parsed from each line', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'prepare a chat template input string for vLLM inference using a LlamaTokenizer and two model responses', 'parse a model generation string and extract the judgement verdict as model_a, model_b, or tie', 'compute RewardBench evaluation scores from generated judgements and input prompts JSONL files']
```

Usage

```
{'run_prepare_positive_data': 'run prepare_positive_data to extract SFT training data from sampled judgements using rejection sampling', 'run_rejection_sampling': 'run rejection_sampling to filter model outputs that match a given true label', 'run_parse_response': 'run parse_response to extract input, output, and metadata from a vLLM response dictionary', 'review_prepare_positive_data': 'review prepare_positive_data to understand how SFT data is balanced between model A and model B', 'refactor_rejection_sampling': 'refactor rejection_sampling to support custom majority voting thresholds for output filtering'}
```

## File: facebookresearch_ram/projects/self_taught_evaluator/src/run_model.py

Prompts

```
['run prepare_dpo_data to extract DPO training data from sampled judgements in a generation directory', 'run pair_sampling to sample a pair of outputs with different judgements from a list', 'run get_input_key to extract the system prompt and user question from a response', 'review prepare_dpo_data to understand how positive and negative examples are classified and balanced', 'refactor pair_sampling to support more than two outputs or custom label matching logic', 'run prepare_positive_data to extract SFT training data from sampled judgements using rejection sampling', 'run rejection_sampling to filter model outputs that match a given true label', 'run parse_response to extract input, output, and metadata from a vLLM response dictionary', 'review prepare_positive_data to understand how SFT data is balanced between model A and model B', 'refactor rejection_sampling to support custom majority voting thresholds for output filtering', 'run a vLLM model to judge pairs of assistant responses from a JSONL input file', 'run the model using pre-prompted inputs from a specified JSONL key instead of composing inputs', 'run the model and save judgment results to a specified output JSONL file path', 'compose vLLM plain string inputs from a list of input and response pair dictionaries', 'review the run function that loads JSONL inputs, generates outputs with vLLM, and parses judgments', 'load a JSONL file and return a list of dictionaries parsed from each line', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'prepare a chat template input string for vLLM inference using a LlamaTokenizer and two model responses', 'parse a model generation string and extract the judgement verdict as model_a, model_b, or tie', 'compute RewardBench evaluation scores from generated judgements and input prompts JSONL files']
```

Usage

```
{'run_model_judge_responses': 'run a vLLM model to judge pairs of assistant responses from a JSONL input file', 'run_model_with_prompted_inputs': 'run the model using pre-prompted inputs from a specified JSONL key instead of composing inputs', 'run_model_save_results': 'run the model and save judgment results to a specified output JSONL file path', 'compose_vllm_inputs': 'compose vLLM plain string inputs from a list of input and response pair dictionaries', 'review_run_function': 'review the run function that loads JSONL inputs, generates outputs with vLLM, and parses judgments'}
```

## File: facebookresearch_ram/projects/self_taught_evaluator/src/utils.py

Prompts

```
['run prepare_dpo_data to extract DPO training data from sampled judgements in a generation directory', 'run pair_sampling to sample a pair of outputs with different judgements from a list', 'run get_input_key to extract the system prompt and user question from a response', 'review prepare_dpo_data to understand how positive and negative examples are classified and balanced', 'refactor pair_sampling to support more than two outputs or custom label matching logic', 'run prepare_positive_data to extract SFT training data from sampled judgements using rejection sampling', 'run rejection_sampling to filter model outputs that match a given true label', 'run parse_response to extract input, output, and metadata from a vLLM response dictionary', 'review prepare_positive_data to understand how SFT data is balanced between model A and model B', 'refactor rejection_sampling to support custom majority voting thresholds for output filtering', 'run a vLLM model to judge pairs of assistant responses from a JSONL input file', 'run the model using pre-prompted inputs from a specified JSONL key instead of composing inputs', 'run the model and save judgment results to a specified output JSONL file path', 'compose vLLM plain string inputs from a list of input and response pair dictionaries', 'review the run function that loads JSONL inputs, generates outputs with vLLM, and parses judgments', 'load a JSONL file and return a list of dictionaries parsed from each line', 'save a list of dictionaries to a JSONL file with one JSON object per line', 'prepare a chat template input string for vLLM inference using a LlamaTokenizer and two model responses', 'parse a model generation string and extract the judgement verdict as model_a, model_b, or tie', 'compute RewardBench evaluation scores from generated judgements and input prompts JSONL files']
```

Usage

```
{'load_jsonl_file': 'load a JSONL file and return a list of dictionaries parsed from each line', 'save_to_jsonl': 'save a list of dictionaries to a JSONL file with one JSON object per line', 'prepare_vllm_input': 'prepare a chat template input string for vLLM inference using a LlamaTokenizer and two model responses', 'parse_judgement': 'parse a model generation string and extract the judgement verdict as model_a, model_b, or tie', 'compute_rewardbench_scores': 'compute RewardBench evaluation scores from generated judgements and input prompts JSONL files'}
```

