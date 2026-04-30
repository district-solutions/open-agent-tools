# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/scripts/wizard/steps/execution.py

Prompts

```
['run the execution step wizard to configure sandbox mode and safety settings for DeerFlow', 'create an ExecutionStepResult dataclass with sandbox_use, allow_host_bash, include_bash_tool, and include_write_tools fields', 'build a DeerFlow execution configuration using local or container sandbox provider selection', 'test the execution step wizard to verify sandbox mode and tool enablement choices', 'review the execution step function to understand sandbox isolation and bash tool safety controls', 'run the interactive LLM provider selection step and return an LLMStepResult with provider, model, and API key', 'create an LLMStepResult dataclass instance with provider, model_name, api_key, and optional base_url fields', 'test the run_llm_step function that orchestrates interactive LLM provider and model selection via CLI prompts', 'review the LLMStepResult dataclass that stores LLM provider selection results including provider, model, api_key, and base_url', 'summarize the run_llm_step function that handles interactive LLM provider choice, model selection, and API key entry', 'run the interactive web search and fetch provider setup step for DeerFlow configuration', 'create a SearchStepResult dataclass with search and fetch provider configuration values', 'configure a web search provider by selecting from available options and entering the API key', 'configure a web fetch provider by selecting from available options and entering the API key', 'reuse an existing search API key for a web fetch provider to avoid re-entering credentials']
```

Usage

```
{'run_execution_step': 'run the execution step wizard to configure sandbox mode and safety settings for DeerFlow', 'create_execution_step_result': 'create an ExecutionStepResult dataclass with sandbox_use, allow_host_bash, include_bash_tool, and include_write_tools fields', 'build_deerflow_sandbox': 'build a DeerFlow execution configuration using local or container sandbox provider selection', 'test_execution_step': 'test the execution step wizard to verify sandbox mode and tool enablement choices', 'review_execution_step': 'review the execution step function to understand sandbox isolation and bash tool safety controls'}
```

## File: bytedance_deer-flow/scripts/wizard/steps/llm.py

Prompts

```
['run the execution step wizard to configure sandbox mode and safety settings for DeerFlow', 'create an ExecutionStepResult dataclass with sandbox_use, allow_host_bash, include_bash_tool, and include_write_tools fields', 'build a DeerFlow execution configuration using local or container sandbox provider selection', 'test the execution step wizard to verify sandbox mode and tool enablement choices', 'review the execution step function to understand sandbox isolation and bash tool safety controls', 'run the interactive LLM provider selection step and return an LLMStepResult with provider, model, and API key', 'create an LLMStepResult dataclass instance with provider, model_name, api_key, and optional base_url fields', 'test the run_llm_step function that orchestrates interactive LLM provider and model selection via CLI prompts', 'review the LLMStepResult dataclass that stores LLM provider selection results including provider, model, api_key, and base_url', 'summarize the run_llm_step function that handles interactive LLM provider choice, model selection, and API key entry', 'run the interactive web search and fetch provider setup step for DeerFlow configuration', 'create a SearchStepResult dataclass with search and fetch provider configuration values', 'configure a web search provider by selecting from available options and entering the API key', 'configure a web fetch provider by selecting from available options and entering the API key', 'reuse an existing search API key for a web fetch provider to avoid re-entering credentials']
```

Usage

```
{'run_llm_step': 'run the interactive LLM provider selection step and return an LLMStepResult with provider, model, and API key', 'create_LLMStepResult': 'create an LLMStepResult dataclass instance with provider, model_name, api_key, and optional base_url fields', 'test_run_llm_step': 'test the run_llm_step function that orchestrates interactive LLM provider and model selection via CLI prompts', 'review_LLMStepResult': 'review the LLMStepResult dataclass that stores LLM provider selection results including provider, model, api_key, and base_url', 'summarize_run_llm_step': 'summarize the run_llm_step function that handles interactive LLM provider choice, model selection, and API key entry'}
```

## File: bytedance_deer-flow/scripts/wizard/steps/search.py

Prompts

```
['run the execution step wizard to configure sandbox mode and safety settings for DeerFlow', 'create an ExecutionStepResult dataclass with sandbox_use, allow_host_bash, include_bash_tool, and include_write_tools fields', 'build a DeerFlow execution configuration using local or container sandbox provider selection', 'test the execution step wizard to verify sandbox mode and tool enablement choices', 'review the execution step function to understand sandbox isolation and bash tool safety controls', 'run the interactive LLM provider selection step and return an LLMStepResult with provider, model, and API key', 'create an LLMStepResult dataclass instance with provider, model_name, api_key, and optional base_url fields', 'test the run_llm_step function that orchestrates interactive LLM provider and model selection via CLI prompts', 'review the LLMStepResult dataclass that stores LLM provider selection results including provider, model, api_key, and base_url', 'summarize the run_llm_step function that handles interactive LLM provider choice, model selection, and API key entry', 'run the interactive web search and fetch provider setup step for DeerFlow configuration', 'create a SearchStepResult dataclass with search and fetch provider configuration values', 'configure a web search provider by selecting from available options and entering the API key', 'configure a web fetch provider by selecting from available options and entering the API key', 'reuse an existing search API key for a web fetch provider to avoid re-entering credentials']
```

Usage

```
{'run_search_step': 'run the interactive web search and fetch provider setup step for DeerFlow configuration', 'create_SearchStepResult': 'create a SearchStepResult dataclass with search and fetch provider configuration values', 'configure_search_provider': 'configure a web search provider by selecting from available options and entering the API key', 'configure_fetch_provider': 'configure a web fetch provider by selecting from available options and entering the API key', 'reuse_search_api_key': 'reuse an existing search API key for a web fetch provider to avoid re-entering credentials'}
```

