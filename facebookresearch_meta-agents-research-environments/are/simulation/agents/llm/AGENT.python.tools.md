# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/agents/llm/llm_engine.py

Prompts

```
['create a ModelConfig Pydantic model with model_name, provider, max_tokens, temperature, and endpoint settings', 'implement a subclass of LLMEngine that overrides chat_completion to return responses and metadata', 'use MockLLMEngine with a list of mock responses to test LLM interactions without a real engine', 'call an LLMEngine instance directly with messages and stop_sequences to get chat completion results', 'handle LLMEngineException with an optional inner_exception to capture and propagate underlying errors', 'create an LLM engine from an LLMEngineConfig using LLMEngineBuilder.create_engine', 'create a Llama API engine by setting LLAMA_API_KEY and using provider llama-api', 'create a local LLM engine using provider local or mock with LiteLLM', 'create a Hugging Face provider engine for providers like groq, openai, or cerebras', 'create a generic LiteLLM engine for any provider not explicitly listed', 'create a MessageRole enum instance with USER, ASSISTANT, SYSTEM, TOOL_CALL, or TOOL_RESPONSE values', 'list all available MessageRole values using the roles classmethod to get a list of role strings', 'create an MMObservation Pydantic model with content string and a list of Attachment objects', 'call the verbose method on an MMObservation instance to get formatted content and attachment MIME and size info', 'use the Observation type alias to accept either a plain string or an MMObservation instance']
```

Usage

```
{'create_model_config': 'create a ModelConfig Pydantic model with model_name, provider, max_tokens, temperature, and endpoint settings', 'implement_llm_engine_subclass': 'implement a subclass of LLMEngine that overrides chat_completion to return responses and metadata', 'use_mock_llm_engine': 'use MockLLMEngine with a list of mock responses to test LLM interactions without a real engine', 'call_llm_engine': 'call an LLMEngine instance directly with messages and stop_sequences to get chat completion results', 'handle_llm_engine_exception': 'handle LLMEngineException with an optional inner_exception to capture and propagate underlying errors'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/agents/llm/llm_engine_builder.py

Prompts

```
['create a ModelConfig Pydantic model with model_name, provider, max_tokens, temperature, and endpoint settings', 'implement a subclass of LLMEngine that overrides chat_completion to return responses and metadata', 'use MockLLMEngine with a list of mock responses to test LLM interactions without a real engine', 'call an LLMEngine instance directly with messages and stop_sequences to get chat completion results', 'handle LLMEngineException with an optional inner_exception to capture and propagate underlying errors', 'create an LLM engine from an LLMEngineConfig using LLMEngineBuilder.create_engine', 'create a Llama API engine by setting LLAMA_API_KEY and using provider llama-api', 'create a local LLM engine using provider local or mock with LiteLLM', 'create a Hugging Face provider engine for providers like groq, openai, or cerebras', 'create a generic LiteLLM engine for any provider not explicitly listed', 'create a MessageRole enum instance with USER, ASSISTANT, SYSTEM, TOOL_CALL, or TOOL_RESPONSE values', 'list all available MessageRole values using the roles classmethod to get a list of role strings', 'create an MMObservation Pydantic model with content string and a list of Attachment objects', 'call the verbose method on an MMObservation instance to get formatted content and attachment MIME and size info', 'use the Observation type alias to accept either a plain string or an MMObservation instance']
```

Usage

```
{'create_llm_engine': 'create an LLM engine from an LLMEngineConfig using LLMEngineBuilder.create_engine', 'create_llama_api_engine': 'create a Llama API engine by setting LLAMA_API_KEY and using provider llama-api', 'create_local_engine': 'create a local LLM engine using provider local or mock with LiteLLM', 'create_hf_provider_engine': 'create a Hugging Face provider engine for providers like groq, openai, or cerebras', 'create_generic_litellm_engine': 'create a generic LiteLLM engine for any provider not explicitly listed'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/agents/llm/types.py

Prompts

```
['create a ModelConfig Pydantic model with model_name, provider, max_tokens, temperature, and endpoint settings', 'implement a subclass of LLMEngine that overrides chat_completion to return responses and metadata', 'use MockLLMEngine with a list of mock responses to test LLM interactions without a real engine', 'call an LLMEngine instance directly with messages and stop_sequences to get chat completion results', 'handle LLMEngineException with an optional inner_exception to capture and propagate underlying errors', 'create an LLM engine from an LLMEngineConfig using LLMEngineBuilder.create_engine', 'create a Llama API engine by setting LLAMA_API_KEY and using provider llama-api', 'create a local LLM engine using provider local or mock with LiteLLM', 'create a Hugging Face provider engine for providers like groq, openai, or cerebras', 'create a generic LiteLLM engine for any provider not explicitly listed', 'create a MessageRole enum instance with USER, ASSISTANT, SYSTEM, TOOL_CALL, or TOOL_RESPONSE values', 'list all available MessageRole values using the roles classmethod to get a list of role strings', 'create an MMObservation Pydantic model with content string and a list of Attachment objects', 'call the verbose method on an MMObservation instance to get formatted content and attachment MIME and size info', 'use the Observation type alias to accept either a plain string or an MMObservation instance']
```

Usage

```
{'create_message_role_enum': 'create a MessageRole enum instance with USER, ASSISTANT, SYSTEM, TOOL_CALL, or TOOL_RESPONSE values', 'list_message_roles': 'list all available MessageRole values using the roles classmethod to get a list of role strings', 'create_mmo_observation': 'create an MMObservation Pydantic model with content string and a list of Attachment objects', 'get_mmo_verbose_output': 'call the verbose method on an MMObservation instance to get formatted content and attachment MIME and size info', 'use_observation_type': 'use the Observation type alias to accept either a plain string or an MMObservation instance'}
```

