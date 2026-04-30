# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/environments/hermes_swe_env/hermes_swe_env.py

Prompts

```
['run the HermesSweEnv CLI with serve command, openai base_url, model_name, and dataset_name args', 'build a HermesSweEnvConfig with terminal, file, web toolsets and modal terminal backend for SWE-bench tasks', 'test the HermesSweEnv compute_reward method by running test_code in a Modal sandbox and checking exit codes', 'format a SWE task prompt from a dataset item with prompt field and test code for the agent loop', 'log SWE training metrics including avg_reward and pass_rate to Weights & Biases via wandb_log']
```

Usage

```
{'run_hermes_swe_env_cli': 'run the HermesSweEnv CLI with serve command, openai base_url, model_name, and dataset_name args', 'build_swe_env_config': 'build a HermesSweEnvConfig with terminal, file, web toolsets and modal terminal backend for SWE-bench tasks', 'test_swe_reward': 'test the HermesSweEnv compute_reward method by running test_code in a Modal sandbox and checking exit codes', 'format_swe_prompt': 'format a SWE task prompt from a dataset item with prompt field and test code for the agent loop', 'log_swe_metrics': 'log SWE training metrics including avg_reward and pass_rate to Weights & Biases via wandb_log'}
```

