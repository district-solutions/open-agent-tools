# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/litellm_proxy/skills/code_execution.py

Prompts

```
['create the OpenAI-format tool definition for litellm_code_execution in a sandboxed environment', 'create the Anthropic-format tool definition for litellm_code_execution in a sandboxed environment', 'test if a list of tools contains the litellm_code_execution tool', 'add the litellm_code_execution tool to a tools list if not already present', 'run the CodeExecutionHandler to execute LLM calls with automatic code execution in a sandbox', 'extract skill content from a LiteLLM_SkillsTable ZIP file, preferring SKILL.md over README.md', 'extract all files from a skill ZIP file into a path-to-bytes dictionary for sandboxed code execution', 'inject skill content into the system prompt of OpenAI-style or Anthropic-style message dicts', 'create an OpenAI-style execute_code tool definition with available module hints for skill code execution', 'convert a LiteLLM_SkillsTable skill into an OpenAI-style function tool with parameter metadata', 'create a SkillsSandboxExecutor instance with a custom timeout, backend, and Docker image', 'execute Python code in a sandboxed environment with skill files and optional requirements', 'collect files generated during sandbox execution and return them with base64 content and MIME types', 'get the MIME type for a file based on its extension', 'run Python code inside an llm-sandbox session with support for copying files to and from the runtime', 'create a skill in the LiteLLM database with display title, description, and instructions', 'list skills from the LiteLLM database with a configurable limit and offset', 'get a skill from the LiteLLM database by skill ID', 'delete a skill from the LiteLLM database by skill ID', 'convert a database skill record to an Anthropic-compatible Skill response object']
```

Usage

```
{'create_code_execution_tool': 'create the OpenAI-format tool definition for litellm_code_execution in a sandboxed environment', 'create_anthropic_code_execution_tool': 'create the Anthropic-format tool definition for litellm_code_execution in a sandboxed environment', 'test_has_code_execution_tool': 'test if a list of tools contains the litellm_code_execution tool', 'add_code_execution_tool': 'add the litellm_code_execution tool to a tools list if not already present', 'run_code_execution_handler': 'run the CodeExecutionHandler to execute LLM calls with automatic code execution in a sandbox'}
```

## File: berriai_litellm/litellm/llms/litellm_proxy/skills/prompt_injection.py

Prompts

```
['create the OpenAI-format tool definition for litellm_code_execution in a sandboxed environment', 'create the Anthropic-format tool definition for litellm_code_execution in a sandboxed environment', 'test if a list of tools contains the litellm_code_execution tool', 'add the litellm_code_execution tool to a tools list if not already present', 'run the CodeExecutionHandler to execute LLM calls with automatic code execution in a sandbox', 'extract skill content from a LiteLLM_SkillsTable ZIP file, preferring SKILL.md over README.md', 'extract all files from a skill ZIP file into a path-to-bytes dictionary for sandboxed code execution', 'inject skill content into the system prompt of OpenAI-style or Anthropic-style message dicts', 'create an OpenAI-style execute_code tool definition with available module hints for skill code execution', 'convert a LiteLLM_SkillsTable skill into an OpenAI-style function tool with parameter metadata', 'create a SkillsSandboxExecutor instance with a custom timeout, backend, and Docker image', 'execute Python code in a sandboxed environment with skill files and optional requirements', 'collect files generated during sandbox execution and return them with base64 content and MIME types', 'get the MIME type for a file based on its extension', 'run Python code inside an llm-sandbox session with support for copying files to and from the runtime', 'create a skill in the LiteLLM database with display title, description, and instructions', 'list skills from the LiteLLM database with a configurable limit and offset', 'get a skill from the LiteLLM database by skill ID', 'delete a skill from the LiteLLM database by skill ID', 'convert a database skill record to an Anthropic-compatible Skill response object']
```

Usage

```
{'extract_skill_content_from_zip': 'extract skill content from a LiteLLM_SkillsTable ZIP file, preferring SKILL.md over README.md', 'extract_all_files_for_code_execution': 'extract all files from a skill ZIP file into a path-to-bytes dictionary for sandboxed code execution', 'inject_skill_content_into_system_prompt': 'inject skill content into the system prompt of OpenAI-style or Anthropic-style message dicts', 'create_execute_code_tool_definition': 'create an OpenAI-style execute_code tool definition with available module hints for skill code execution', 'convert_skill_to_openai_tool': 'convert a LiteLLM_SkillsTable skill into an OpenAI-style function tool with parameter metadata'}
```

## File: berriai_litellm/litellm/llms/litellm_proxy/skills/sandbox_executor.py

Prompts

```
['create the OpenAI-format tool definition for litellm_code_execution in a sandboxed environment', 'create the Anthropic-format tool definition for litellm_code_execution in a sandboxed environment', 'test if a list of tools contains the litellm_code_execution tool', 'add the litellm_code_execution tool to a tools list if not already present', 'run the CodeExecutionHandler to execute LLM calls with automatic code execution in a sandbox', 'extract skill content from a LiteLLM_SkillsTable ZIP file, preferring SKILL.md over README.md', 'extract all files from a skill ZIP file into a path-to-bytes dictionary for sandboxed code execution', 'inject skill content into the system prompt of OpenAI-style or Anthropic-style message dicts', 'create an OpenAI-style execute_code tool definition with available module hints for skill code execution', 'convert a LiteLLM_SkillsTable skill into an OpenAI-style function tool with parameter metadata', 'create a SkillsSandboxExecutor instance with a custom timeout, backend, and Docker image', 'execute Python code in a sandboxed environment with skill files and optional requirements', 'collect files generated during sandbox execution and return them with base64 content and MIME types', 'get the MIME type for a file based on its extension', 'run Python code inside an llm-sandbox session with support for copying files to and from the runtime', 'create a skill in the LiteLLM database with display title, description, and instructions', 'list skills from the LiteLLM database with a configurable limit and offset', 'get a skill from the LiteLLM database by skill ID', 'delete a skill from the LiteLLM database by skill ID', 'convert a database skill record to an Anthropic-compatible Skill response object']
```

Usage

```
{'create_skills_sandbox_executor': 'create a SkillsSandboxExecutor instance with a custom timeout, backend, and Docker image', 'execute_code_in_sandbox': 'execute Python code in a sandboxed environment with skill files and optional requirements', 'collect_generated_files': 'collect files generated during sandbox execution and return them with base64 content and MIME types', 'get_mime_type': 'get the MIME type for a file based on its extension', 'run_code_with_sandbox_session': 'run Python code inside an llm-sandbox session with support for copying files to and from the runtime'}
```

## File: berriai_litellm/litellm/llms/litellm_proxy/skills/transformation.py

Prompts

```
['create the OpenAI-format tool definition for litellm_code_execution in a sandboxed environment', 'create the Anthropic-format tool definition for litellm_code_execution in a sandboxed environment', 'test if a list of tools contains the litellm_code_execution tool', 'add the litellm_code_execution tool to a tools list if not already present', 'run the CodeExecutionHandler to execute LLM calls with automatic code execution in a sandbox', 'extract skill content from a LiteLLM_SkillsTable ZIP file, preferring SKILL.md over README.md', 'extract all files from a skill ZIP file into a path-to-bytes dictionary for sandboxed code execution', 'inject skill content into the system prompt of OpenAI-style or Anthropic-style message dicts', 'create an OpenAI-style execute_code tool definition with available module hints for skill code execution', 'convert a LiteLLM_SkillsTable skill into an OpenAI-style function tool with parameter metadata', 'create a SkillsSandboxExecutor instance with a custom timeout, backend, and Docker image', 'execute Python code in a sandboxed environment with skill files and optional requirements', 'collect files generated during sandbox execution and return them with base64 content and MIME types', 'get the MIME type for a file based on its extension', 'run Python code inside an llm-sandbox session with support for copying files to and from the runtime', 'create a skill in the LiteLLM database with display title, description, and instructions', 'list skills from the LiteLLM database with a configurable limit and offset', 'get a skill from the LiteLLM database by skill ID', 'delete a skill from the LiteLLM database by skill ID', 'convert a database skill record to an Anthropic-compatible Skill response object']
```

Usage

```
{'create_skill_handler': 'create a skill in the LiteLLM database with display title, description, and instructions', 'list_skills_handler': 'list skills from the LiteLLM database with a configurable limit and offset', 'get_skill_handler': 'get a skill from the LiteLLM database by skill ID', 'delete_skill_handler': 'delete a skill from the LiteLLM database by skill ID', '_db_skill_to_response': 'convert a database skill record to an Anthropic-compatible Skill response object'}
```

