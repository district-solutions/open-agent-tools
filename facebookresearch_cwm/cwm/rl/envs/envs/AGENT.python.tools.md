# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/rl/envs/envs/lcb.py

Prompts

```
['create a LiveCodeBench code generation environment with official or custom prompt format and max attempts', 'create a LiveCodeBench think environment that extracts reasoning and code answers from model output', 'run a step in the LCB code generation environment to execute code and get test feedback', 'generate formatted feedback from public test case results showing passed and failed tests', 'shorten Python backtrace filenames for brevity and portability by removing test runner frames', 'create a MathThinkDialogEnv instance with a tokenizer to solve single-turn math reasoning problems with think and answer tags', 'create a MathThinkCWMDialogEnv with think mode enabled to use Qwen-style prompt format for step-by-step math reasoning', "extract reasoning text and boxed answer from a model's response using regex pattern matching on think and answer tags", 'evaluate a math prediction against ground truth using both CWM comparison and math_verify comparison methods', 'run a math reasoning episode through the environment with multiple attempts and tool execution support', 'create a git patch string from Python code for a new test_issue.py file', 'evaluate a test script against a SWE-RL episode to verify issue reproduction', 'create a SWERLConfig dataclass to configure context size, timeouts, and thinking mode for the environment', 'start a SWERLToolEnv episode with issue description and repository arguments to initialize the dialog', 'step through a SWERLToolEnv episode by applying tool calls and collecting feedback from the modal backend', 'create a SWERLConfig dataclass to configure context size, max turns, session timeout, and reward settings for the SWE-RL environment', 'start a SWERLToolEnv episode by calling start with episode_args containing instance_id, issue, patch, docker_url, and repo_root_path', 'step the SWERLToolEnv environment by passing a tokenized action list and receiving a transition with tool results and budget feedback', 'eval a predicted patch against an episode using eval_instance to run tests and return pass or fail outcomes', 'create a SimilaritiesRewardFn reward function that computes edit distance based rewards between predicted and oracle patches']
```

Usage

```
{'create_LCBCodeGenEnv': 'create a LiveCodeBench code generation environment with official or custom prompt format and max attempts', 'create_LCBCWMThinkEnv': 'create a LiveCodeBench think environment that extracts reasoning and code answers from model output', 'run_LCBCodeGenEnv_step': 'run a step in the LCB code generation environment to execute code and get test feedback', 'generate_code_exec_feedback': 'generate formatted feedback from public test case results showing passed and failed tests', 'shorten_backtrace_filenames': 'shorten Python backtrace filenames for brevity and portability by removing test runner frames'}
```

## File: facebookresearch_cwm/cwm/rl/envs/envs/math_think_dialog.py

Prompts

```
['create a LiveCodeBench code generation environment with official or custom prompt format and max attempts', 'create a LiveCodeBench think environment that extracts reasoning and code answers from model output', 'run a step in the LCB code generation environment to execute code and get test feedback', 'generate formatted feedback from public test case results showing passed and failed tests', 'shorten Python backtrace filenames for brevity and portability by removing test runner frames', 'create a MathThinkDialogEnv instance with a tokenizer to solve single-turn math reasoning problems with think and answer tags', 'create a MathThinkCWMDialogEnv with think mode enabled to use Qwen-style prompt format for step-by-step math reasoning', "extract reasoning text and boxed answer from a model's response using regex pattern matching on think and answer tags", 'evaluate a math prediction against ground truth using both CWM comparison and math_verify comparison methods', 'run a math reasoning episode through the environment with multiple attempts and tool execution support', 'create a git patch string from Python code for a new test_issue.py file', 'evaluate a test script against a SWE-RL episode to verify issue reproduction', 'create a SWERLConfig dataclass to configure context size, timeouts, and thinking mode for the environment', 'start a SWERLToolEnv episode with issue description and repository arguments to initialize the dialog', 'step through a SWERLToolEnv episode by applying tool calls and collecting feedback from the modal backend', 'create a SWERLConfig dataclass to configure context size, max turns, session timeout, and reward settings for the SWE-RL environment', 'start a SWERLToolEnv episode by calling start with episode_args containing instance_id, issue, patch, docker_url, and repo_root_path', 'step the SWERLToolEnv environment by passing a tokenized action list and receiving a transition with tool results and budget feedback', 'eval a predicted patch against an episode using eval_instance to run tests and return pass or fail outcomes', 'create a SimilaritiesRewardFn reward function that computes edit distance based rewards between predicted and oracle patches']
```

Usage

```
{'create_math_think_dialog_env': 'create a MathThinkDialogEnv instance with a tokenizer to solve single-turn math reasoning problems with think and answer tags', 'create_math_think_cwm_dialog_env': 'create a MathThinkCWMDialogEnv with think mode enabled to use Qwen-style prompt format for step-by-step math reasoning', 'extract_reasoning_and_answer': "extract reasoning text and boxed answer from a model's response using regex pattern matching on think and answer tags", 'evaluate_math_prediction': 'evaluate a math prediction against ground truth using both CWM comparison and math_verify comparison methods', 'run_math_reasoning_episode': 'run a math reasoning episode through the environment with multiple attempts and tool execution support'}
```

## File: facebookresearch_cwm/cwm/rl/envs/envs/swerl_testgen_tool.py

Prompts

```
['create a LiveCodeBench code generation environment with official or custom prompt format and max attempts', 'create a LiveCodeBench think environment that extracts reasoning and code answers from model output', 'run a step in the LCB code generation environment to execute code and get test feedback', 'generate formatted feedback from public test case results showing passed and failed tests', 'shorten Python backtrace filenames for brevity and portability by removing test runner frames', 'create a MathThinkDialogEnv instance with a tokenizer to solve single-turn math reasoning problems with think and answer tags', 'create a MathThinkCWMDialogEnv with think mode enabled to use Qwen-style prompt format for step-by-step math reasoning', "extract reasoning text and boxed answer from a model's response using regex pattern matching on think and answer tags", 'evaluate a math prediction against ground truth using both CWM comparison and math_verify comparison methods', 'run a math reasoning episode through the environment with multiple attempts and tool execution support', 'create a git patch string from Python code for a new test_issue.py file', 'evaluate a test script against a SWE-RL episode to verify issue reproduction', 'create a SWERLConfig dataclass to configure context size, timeouts, and thinking mode for the environment', 'start a SWERLToolEnv episode with issue description and repository arguments to initialize the dialog', 'step through a SWERLToolEnv episode by applying tool calls and collecting feedback from the modal backend', 'create a SWERLConfig dataclass to configure context size, max turns, session timeout, and reward settings for the SWE-RL environment', 'start a SWERLToolEnv episode by calling start with episode_args containing instance_id, issue, patch, docker_url, and repo_root_path', 'step the SWERLToolEnv environment by passing a tokenized action list and receiving a transition with tool results and budget feedback', 'eval a predicted patch against an episode using eval_instance to run tests and return pass or fail outcomes', 'create a SimilaritiesRewardFn reward function that computes edit distance based rewards between predicted and oracle patches']
```

Usage

```
{'create_patch_from_code': 'create a git patch string from Python code for a new test_issue.py file', 'eval_instance': 'evaluate a test script against a SWE-RL episode to verify issue reproduction', 'SWERLConfig': 'create a SWERLConfig dataclass to configure context size, timeouts, and thinking mode for the environment', 'SWERLToolEnv_start': 'start a SWERLToolEnv episode with issue description and repository arguments to initialize the dialog', 'SWERLToolEnv_step': 'step through a SWERLToolEnv episode by applying tool calls and collecting feedback from the modal backend'}
```

## File: facebookresearch_cwm/cwm/rl/envs/envs/swerl_tool.py

Prompts

```
['create a LiveCodeBench code generation environment with official or custom prompt format and max attempts', 'create a LiveCodeBench think environment that extracts reasoning and code answers from model output', 'run a step in the LCB code generation environment to execute code and get test feedback', 'generate formatted feedback from public test case results showing passed and failed tests', 'shorten Python backtrace filenames for brevity and portability by removing test runner frames', 'create a MathThinkDialogEnv instance with a tokenizer to solve single-turn math reasoning problems with think and answer tags', 'create a MathThinkCWMDialogEnv with think mode enabled to use Qwen-style prompt format for step-by-step math reasoning', "extract reasoning text and boxed answer from a model's response using regex pattern matching on think and answer tags", 'evaluate a math prediction against ground truth using both CWM comparison and math_verify comparison methods', 'run a math reasoning episode through the environment with multiple attempts and tool execution support', 'create a git patch string from Python code for a new test_issue.py file', 'evaluate a test script against a SWE-RL episode to verify issue reproduction', 'create a SWERLConfig dataclass to configure context size, timeouts, and thinking mode for the environment', 'start a SWERLToolEnv episode with issue description and repository arguments to initialize the dialog', 'step through a SWERLToolEnv episode by applying tool calls and collecting feedback from the modal backend', 'create a SWERLConfig dataclass to configure context size, max turns, session timeout, and reward settings for the SWE-RL environment', 'start a SWERLToolEnv episode by calling start with episode_args containing instance_id, issue, patch, docker_url, and repo_root_path', 'step the SWERLToolEnv environment by passing a tokenized action list and receiving a transition with tool results and budget feedback', 'eval a predicted patch against an episode using eval_instance to run tests and return pass or fail outcomes', 'create a SimilaritiesRewardFn reward function that computes edit distance based rewards between predicted and oracle patches']
```

Usage

```
{'create_SWERLConfig': 'create a SWERLConfig dataclass to configure context size, max turns, session timeout, and reward settings for the SWE-RL environment', 'start_SWERLToolEnv': 'start a SWERLToolEnv episode by calling start with episode_args containing instance_id, issue, patch, docker_url, and repo_root_path', 'step_SWERLToolEnv': 'step the SWERLToolEnv environment by passing a tokenized action list and receiving a transition with tool results and budget feedback', 'eval_eval_instance': 'eval a predicted patch against an episode using eval_instance to run tests and return pass or fail outcomes', 'create_SimilaritiesRewardFn': 'create a SimilaritiesRewardFn reward function that computes edit distance based rewards between predicted and oracle patches'}
```

