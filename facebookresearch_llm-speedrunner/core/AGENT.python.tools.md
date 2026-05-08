# Agent Python Tools

- repo: facebookresearch/llm-speedrunner
- repo_uri: https://github.com/facebookresearch/llm-speedrunner

## File: facebookresearch_llm-speedrunner/core/agent.py

Prompts

```
['create an Agent instance with an OpenAI model URL and API key from secrets', 'create an Agent instance with a Gemini model and GEMINI_API_KEY from secrets', 'run the Agent act method with an instruction string to generate an LLM response', 'run the Agent act method with a validator callback to validate and retry LLM responses', 'flush the Agent LLM client logs to a specified file path', 'create a KnowledgeStore initialized with a list of string entries or KnowledgeEntry objects', 'create a KnowledgeStore that loads content from file paths or glob patterns on disk', 'insert a string or KnowledgeEntry object into an existing KnowledgeStore instance', 'search the KnowledgeStore and return all entries formatted as an XML-like knowledge string', 'search the KnowledgeStore and return entries as a list of KnowledgeEntry objects with optional max length', 'create an LLMClient instance to interface with VLLM or OpenAI-compatible LLM servers', 'generate a chat completion response from an LLM using the LLMClient generate method', 'strip thinking tokens from LLM response text using the strip_think_tokens function', 'get an OpenAI or AzureOpenAI client for a given model URL and API key', 'flush LLMClient metrics logs to a JSON file using the flush_logs method', 'extract code blocks from LLM response text using markdown fence pattern matching', 'extract the last JSON dictionary string from text using regex pattern matching', 'validate an LLM response as JSON and optionally check required key types', 'validate and extract code from an LLM response using markdown fence patterns', 'extract code from text in strict mode returning empty string if no code blocks found', 'create a new version directory in the workspace by copying files from a template or parent version', 'view the contents of files in a workspace version directory with optional recursive listing', 'get the top-k best versions ranked by a selection metric from completed experiments', 'view the version history log with optional filtering for good or buggy versions and ancestor depth', 'delete a workspace version directory and recursively remove all its child versions']
```

Usage

```
{'create_agent_with_openai': 'create an Agent instance with an OpenAI model URL and API key from secrets', 'create_agent_with_gemini': 'create an Agent instance with a Gemini model and GEMINI_API_KEY from secrets', 'agent_act_with_instruction': 'run the Agent act method with an instruction string to generate an LLM response', 'agent_act_with_validator': 'run the Agent act method with a validator callback to validate and retry LLM responses', 'agent_flush_logs': 'flush the Agent LLM client logs to a specified file path'}
```

## File: facebookresearch_llm-speedrunner/core/knowledge.py

Prompts

```
['create an Agent instance with an OpenAI model URL and API key from secrets', 'create an Agent instance with a Gemini model and GEMINI_API_KEY from secrets', 'run the Agent act method with an instruction string to generate an LLM response', 'run the Agent act method with a validator callback to validate and retry LLM responses', 'flush the Agent LLM client logs to a specified file path', 'create a KnowledgeStore initialized with a list of string entries or KnowledgeEntry objects', 'create a KnowledgeStore that loads content from file paths or glob patterns on disk', 'insert a string or KnowledgeEntry object into an existing KnowledgeStore instance', 'search the KnowledgeStore and return all entries formatted as an XML-like knowledge string', 'search the KnowledgeStore and return entries as a list of KnowledgeEntry objects with optional max length', 'create an LLMClient instance to interface with VLLM or OpenAI-compatible LLM servers', 'generate a chat completion response from an LLM using the LLMClient generate method', 'strip thinking tokens from LLM response text using the strip_think_tokens function', 'get an OpenAI or AzureOpenAI client for a given model URL and API key', 'flush LLMClient metrics logs to a JSON file using the flush_logs method', 'extract code blocks from LLM response text using markdown fence pattern matching', 'extract the last JSON dictionary string from text using regex pattern matching', 'validate an LLM response as JSON and optionally check required key types', 'validate and extract code from an LLM response using markdown fence patterns', 'extract code from text in strict mode returning empty string if no code blocks found', 'create a new version directory in the workspace by copying files from a template or parent version', 'view the contents of files in a workspace version directory with optional recursive listing', 'get the top-k best versions ranked by a selection metric from completed experiments', 'view the version history log with optional filtering for good or buggy versions and ancestor depth', 'delete a workspace version directory and recursively remove all its child versions']
```

Usage

```
{'create_knowledge_store_from_entries': 'create a KnowledgeStore initialized with a list of string entries or KnowledgeEntry objects', 'create_knowledge_store_from_files': 'create a KnowledgeStore that loads content from file paths or glob patterns on disk', 'insert_knowledge_entry': 'insert a string or KnowledgeEntry object into an existing KnowledgeStore instance', 'search_knowledge_store_as_string': 'search the KnowledgeStore and return all entries formatted as an XML-like knowledge string', 'search_knowledge_store_as_list': 'search the KnowledgeStore and return entries as a list of KnowledgeEntry objects with optional max length'}
```

## File: facebookresearch_llm-speedrunner/core/llm_client.py

Prompts

```
['create an Agent instance with an OpenAI model URL and API key from secrets', 'create an Agent instance with a Gemini model and GEMINI_API_KEY from secrets', 'run the Agent act method with an instruction string to generate an LLM response', 'run the Agent act method with a validator callback to validate and retry LLM responses', 'flush the Agent LLM client logs to a specified file path', 'create a KnowledgeStore initialized with a list of string entries or KnowledgeEntry objects', 'create a KnowledgeStore that loads content from file paths or glob patterns on disk', 'insert a string or KnowledgeEntry object into an existing KnowledgeStore instance', 'search the KnowledgeStore and return all entries formatted as an XML-like knowledge string', 'search the KnowledgeStore and return entries as a list of KnowledgeEntry objects with optional max length', 'create an LLMClient instance to interface with VLLM or OpenAI-compatible LLM servers', 'generate a chat completion response from an LLM using the LLMClient generate method', 'strip thinking tokens from LLM response text using the strip_think_tokens function', 'get an OpenAI or AzureOpenAI client for a given model URL and API key', 'flush LLMClient metrics logs to a JSON file using the flush_logs method', 'extract code blocks from LLM response text using markdown fence pattern matching', 'extract the last JSON dictionary string from text using regex pattern matching', 'validate an LLM response as JSON and optionally check required key types', 'validate and extract code from an LLM response using markdown fence patterns', 'extract code from text in strict mode returning empty string if no code blocks found', 'create a new version directory in the workspace by copying files from a template or parent version', 'view the contents of files in a workspace version directory with optional recursive listing', 'get the top-k best versions ranked by a selection metric from completed experiments', 'view the version history log with optional filtering for good or buggy versions and ancestor depth', 'delete a workspace version directory and recursively remove all its child versions']
```

Usage

```
{'create_LLMClient': 'create an LLMClient instance to interface with VLLM or OpenAI-compatible LLM servers', 'generate_completion': 'generate a chat completion response from an LLM using the LLMClient generate method', 'strip_think_tokens': 'strip thinking tokens from LLM response text using the strip_think_tokens function', 'get_model_client': 'get an OpenAI or AzureOpenAI client for a given model URL and API key', 'flush_logs': 'flush LLMClient metrics logs to a JSON file using the flush_logs method'}
```

## File: facebookresearch_llm-speedrunner/core/validators.py

Prompts

```
['create an Agent instance with an OpenAI model URL and API key from secrets', 'create an Agent instance with a Gemini model and GEMINI_API_KEY from secrets', 'run the Agent act method with an instruction string to generate an LLM response', 'run the Agent act method with a validator callback to validate and retry LLM responses', 'flush the Agent LLM client logs to a specified file path', 'create a KnowledgeStore initialized with a list of string entries or KnowledgeEntry objects', 'create a KnowledgeStore that loads content from file paths or glob patterns on disk', 'insert a string or KnowledgeEntry object into an existing KnowledgeStore instance', 'search the KnowledgeStore and return all entries formatted as an XML-like knowledge string', 'search the KnowledgeStore and return entries as a list of KnowledgeEntry objects with optional max length', 'create an LLMClient instance to interface with VLLM or OpenAI-compatible LLM servers', 'generate a chat completion response from an LLM using the LLMClient generate method', 'strip thinking tokens from LLM response text using the strip_think_tokens function', 'get an OpenAI or AzureOpenAI client for a given model URL and API key', 'flush LLMClient metrics logs to a JSON file using the flush_logs method', 'extract code blocks from LLM response text using markdown fence pattern matching', 'extract the last JSON dictionary string from text using regex pattern matching', 'validate an LLM response as JSON and optionally check required key types', 'validate and extract code from an LLM response using markdown fence patterns', 'extract code from text in strict mode returning empty string if no code blocks found', 'create a new version directory in the workspace by copying files from a template or parent version', 'view the contents of files in a workspace version directory with optional recursive listing', 'get the top-k best versions ranked by a selection metric from completed experiments', 'view the version history log with optional filtering for good or buggy versions and ancestor depth', 'delete a workspace version directory and recursively remove all its child versions']
```

Usage

```
{'extract_code_from_text': 'extract code blocks from LLM response text using markdown fence pattern matching', 'extract_last_json_dict': 'extract the last JSON dictionary string from text using regex pattern matching', 'validate_json_response': 'validate an LLM response as JSON and optionally check required key types', 'validate_code_response': 'validate and extract code from an LLM response using markdown fence patterns', 'extract_code_strict_mode': 'extract code from text in strict mode returning empty string if no code blocks found'}
```

## File: facebookresearch_llm-speedrunner/core/workspace.py

Prompts

```
['create an Agent instance with an OpenAI model URL and API key from secrets', 'create an Agent instance with a Gemini model and GEMINI_API_KEY from secrets', 'run the Agent act method with an instruction string to generate an LLM response', 'run the Agent act method with a validator callback to validate and retry LLM responses', 'flush the Agent LLM client logs to a specified file path', 'create a KnowledgeStore initialized with a list of string entries or KnowledgeEntry objects', 'create a KnowledgeStore that loads content from file paths or glob patterns on disk', 'insert a string or KnowledgeEntry object into an existing KnowledgeStore instance', 'search the KnowledgeStore and return all entries formatted as an XML-like knowledge string', 'search the KnowledgeStore and return entries as a list of KnowledgeEntry objects with optional max length', 'create an LLMClient instance to interface with VLLM or OpenAI-compatible LLM servers', 'generate a chat completion response from an LLM using the LLMClient generate method', 'strip thinking tokens from LLM response text using the strip_think_tokens function', 'get an OpenAI or AzureOpenAI client for a given model URL and API key', 'flush LLMClient metrics logs to a JSON file using the flush_logs method', 'extract code blocks from LLM response text using markdown fence pattern matching', 'extract the last JSON dictionary string from text using regex pattern matching', 'validate an LLM response as JSON and optionally check required key types', 'validate and extract code from an LLM response using markdown fence patterns', 'extract code from text in strict mode returning empty string if no code blocks found', 'create a new version directory in the workspace by copying files from a template or parent version', 'view the contents of files in a workspace version directory with optional recursive listing', 'get the top-k best versions ranked by a selection metric from completed experiments', 'view the version history log with optional filtering for good or buggy versions and ancestor depth', 'delete a workspace version directory and recursively remove all its child versions']
```

Usage

```
{'create_workspace_version': 'create a new version directory in the workspace by copying files from a template or parent version', 'view_workspace_files': 'view the contents of files in a workspace version directory with optional recursive listing', 'get_top_k_versions': 'get the top-k best versions ranked by a selection metric from completed experiments', 'view_version_history': 'view the version history log with optional filtering for good or buggy versions and ancestor depth', 'delete_workspace_version': 'delete a workspace version directory and recursively remove all its child versions'}
```

