# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/contribution_stats.py

Prompts

```
['run the contribution stats script to print git blame line counts by author email', 'create a function that checks if a file is text by scanning for null bytes', 'create a function that determines if a file should be skipped based on dotfiles or config extensions', 'create a function that returns all git tracked files using git ls-files', 'refactor the main function to export contribution stats as JSON instead of printing to stdout', 'build the Open WebUI frontend by running npm install and npm run build via the hatch build hook', 'review the CustomBuildHook initialize method to understand how it runs npm install and npm run build', 'refactor the CustomBuildHook initialize method to support a custom npm registry or proxy settings', 'summarize the CustomBuildHook class that extends BuildHookInterface to build the frontend during hatch builds', 'test the CustomBuildHook initialize method to verify it raises RuntimeError when npm is not found']
```

Usage

```
{'run_contribution_stats': 'run the contribution stats script to print git blame line counts by author email', 'create_is_text_file': 'create a function that checks if a file is text by scanning for null bytes', 'create_should_skip_file': 'create a function that determines if a file should be skipped based on dotfiles or config extensions', 'create_get_tracked_files': 'create a function that returns all git tracked files using git ls-files', 'refactor_main': 'refactor the main function to export contribution stats as JSON instead of printing to stdout'}
```

## File: open-webui_open-webui/hatch_build.py

Prompts

```
['run the contribution stats script to print git blame line counts by author email', 'create a function that checks if a file is text by scanning for null bytes', 'create a function that determines if a file should be skipped based on dotfiles or config extensions', 'create a function that returns all git tracked files using git ls-files', 'refactor the main function to export contribution stats as JSON instead of printing to stdout', 'build the Open WebUI frontend by running npm install and npm run build via the hatch build hook', 'review the CustomBuildHook initialize method to understand how it runs npm install and npm run build', 'refactor the CustomBuildHook initialize method to support a custom npm registry or proxy settings', 'summarize the CustomBuildHook class that extends BuildHookInterface to build the frontend during hatch builds', 'test the CustomBuildHook initialize method to verify it raises RuntimeError when npm is not found']
```

Usage

```
{'build_frontend_with_hatch_hook': 'build the Open WebUI frontend by running npm install and npm run build via the hatch build hook', 'review_CustomBuildHook_initialize': 'review the CustomBuildHook initialize method to understand how it runs npm install and npm run build', 'refactor_CustomBuildHook_npm_commands': 'refactor the CustomBuildHook initialize method to support a custom npm registry or proxy settings', 'summarize_CustomBuildHook': 'summarize the CustomBuildHook class that extends BuildHookInterface to build the frontend during hatch builds', 'test_CustomBuildHook_npm_missing': 'test the CustomBuildHook initialize method to verify it raises RuntimeError when npm is not found'}
```

