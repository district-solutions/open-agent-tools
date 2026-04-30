# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/gitlab/gitlab_client.py

Prompts

```
['build a GitLab client to initialize with a project path, access token, and optional tag or branch', 'create a function to fetch file content from a GitLab repository at a specific tag or branch', 'test the connection to a GitLab project using authentication credentials', 'list files in a GitLab repository directory filtered by extension with optional recursive traversal', 'get metadata about a file in a GitLab repository including content type, size, and last modified date', 'create a GitLabPromptManager with gitlab_config to load and render .prompt templates from a GitLab repository', 'build a GitLabPromptCache to load all .prompt files from a GitLab repo into memory for fast access', 'run render_template on a GitLabTemplateManager to render a Jinja2 prompt template with variables', 'test the pre_call_hook method of GitLabPromptManager to inject prompt messages and model parameters into an LLM call', 'summarize a GitLabPromptTemplate by extracting its content, model, temperature, and max_tokens metadata']
```

Usage

```
{'build_gitlab_client': 'build a GitLab client to initialize with a project path, access token, and optional tag or branch', 'create_gitlab_file_content': 'create a function to fetch file content from a GitLab repository at a specific tag or branch', 'test_gitlab_connection': 'test the connection to a GitLab project using authentication credentials', 'list_gitlab_files': 'list files in a GitLab repository directory filtered by extension with optional recursive traversal', 'get_gitlab_file_metadata': 'get metadata about a file in a GitLab repository including content type, size, and last modified date'}
```

## File: berriai_litellm/litellm/integrations/gitlab/gitlab_prompt_manager.py

Prompts

```
['build a GitLab client to initialize with a project path, access token, and optional tag or branch', 'create a function to fetch file content from a GitLab repository at a specific tag or branch', 'test the connection to a GitLab project using authentication credentials', 'list files in a GitLab repository directory filtered by extension with optional recursive traversal', 'get metadata about a file in a GitLab repository including content type, size, and last modified date', 'create a GitLabPromptManager with gitlab_config to load and render .prompt templates from a GitLab repository', 'build a GitLabPromptCache to load all .prompt files from a GitLab repo into memory for fast access', 'run render_template on a GitLabTemplateManager to render a Jinja2 prompt template with variables', 'test the pre_call_hook method of GitLabPromptManager to inject prompt messages and model parameters into an LLM call', 'summarize a GitLabPromptTemplate by extracting its content, model, temperature, and max_tokens metadata']
```

Usage

```
{'create_gitlab_prompt_manager': 'create a GitLabPromptManager with gitlab_config to load and render .prompt templates from a GitLab repository', 'build_gitlab_prompt_cache': 'build a GitLabPromptCache to load all .prompt files from a GitLab repo into memory for fast access', 'run_render_template': 'run render_template on a GitLabTemplateManager to render a Jinja2 prompt template with variables', 'test_pre_call_hook': 'test the pre_call_hook method of GitLabPromptManager to inject prompt messages and model parameters into an LLM call', 'summarize_gitlab_prompt_template': 'summarize a GitLabPromptTemplate by extracting its content, model, temperature, and max_tokens metadata'}
```

