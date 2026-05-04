# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/src/data/parse/data_process.py

Prompts

```
['run the CLI to extract high-quality docstrings from all Python files in a directory to JSONL', 'extract file, class, and function docstrings from a single Python file using AST parsing', 'check if a docstring meets quality criteria for file, class, or function types in English', 'gather all Python files recursively from a given top-level directory', 'add parent node references to an AST tree to distinguish top-level functions from class methods', 'build a GitHubRepoDownloader instance from a YAML config file containing GitHub search criteria and authentication token', 'build a GitHub search query string from config search criteria including owners, dates, language, stars, and forks', 'clone a GitHub repository using GitPython and save repository metadata as YAML alongside the cloned code', 'run the downloader to search GitHub repositories matching config criteria and clone up to max_repos repositories', 'load and parse a YAML config file with search criteria, output directory, and GitHub token for repository downloading', "generate a hierarchical dictionary of a project's directory structure using ProjectStructureGenerator", 'format a project structure dictionary into a human-readable tree text with indentation', 'check if a file or directory path should be ignored based on configured patterns', 'generate a project structure dictionary limited to a specified maximum traversal depth', 'run the repo_tree CLI to output a project directory tree as text or JSON']
```

Usage

```
{'process_python_repos_for_docstrings': 'run the CLI to extract high-quality docstrings from all Python files in a directory to JSONL', 'extract_docstrings_from_file': 'extract file, class, and function docstrings from a single Python file using AST parsing', 'check_docstring_quality': 'check if a docstring meets quality criteria for file, class, or function types in English', 'gather_python_files': 'gather all Python files recursively from a given top-level directory', 'add_parent_references': 'add parent node references to an AST tree to distinguish top-level functions from class methods'}
```

## File: facebookresearch_docagent/src/data/parse/downloader.py

Prompts

```
['run the CLI to extract high-quality docstrings from all Python files in a directory to JSONL', 'extract file, class, and function docstrings from a single Python file using AST parsing', 'check if a docstring meets quality criteria for file, class, or function types in English', 'gather all Python files recursively from a given top-level directory', 'add parent node references to an AST tree to distinguish top-level functions from class methods', 'build a GitHubRepoDownloader instance from a YAML config file containing GitHub search criteria and authentication token', 'build a GitHub search query string from config search criteria including owners, dates, language, stars, and forks', 'clone a GitHub repository using GitPython and save repository metadata as YAML alongside the cloned code', 'run the downloader to search GitHub repositories matching config criteria and clone up to max_repos repositories', 'load and parse a YAML config file with search criteria, output directory, and GitHub token for repository downloading', "generate a hierarchical dictionary of a project's directory structure using ProjectStructureGenerator", 'format a project structure dictionary into a human-readable tree text with indentation', 'check if a file or directory path should be ignored based on configured patterns', 'generate a project structure dictionary limited to a specified maximum traversal depth', 'run the repo_tree CLI to output a project directory tree as text or JSON']
```

Usage

```
{'build_GitHubRepoDownloader': 'build a GitHubRepoDownloader instance from a YAML config file containing GitHub search criteria and authentication token', 'build_query_GitHubRepoDownloader': 'build a GitHub search query string from config search criteria including owners, dates, language, stars, and forks', 'clone_repository_GitHubRepoDownloader': 'clone a GitHub repository using GitPython and save repository metadata as YAML alongside the cloned code', 'run_GitHubRepoDownloader': 'run the downloader to search GitHub repositories matching config criteria and clone up to max_repos repositories', 'load_config_GitHubRepoDownloader': 'load and parse a YAML config file with search criteria, output directory, and GitHub token for repository downloading'}
```

## File: facebookresearch_docagent/src/data/parse/repo_tree.py

Prompts

```
['run the CLI to extract high-quality docstrings from all Python files in a directory to JSONL', 'extract file, class, and function docstrings from a single Python file using AST parsing', 'check if a docstring meets quality criteria for file, class, or function types in English', 'gather all Python files recursively from a given top-level directory', 'add parent node references to an AST tree to distinguish top-level functions from class methods', 'build a GitHubRepoDownloader instance from a YAML config file containing GitHub search criteria and authentication token', 'build a GitHub search query string from config search criteria including owners, dates, language, stars, and forks', 'clone a GitHub repository using GitPython and save repository metadata as YAML alongside the cloned code', 'run the downloader to search GitHub repositories matching config criteria and clone up to max_repos repositories', 'load and parse a YAML config file with search criteria, output directory, and GitHub token for repository downloading', "generate a hierarchical dictionary of a project's directory structure using ProjectStructureGenerator", 'format a project structure dictionary into a human-readable tree text with indentation', 'check if a file or directory path should be ignored based on configured patterns', 'generate a project structure dictionary limited to a specified maximum traversal depth', 'run the repo_tree CLI to output a project directory tree as text or JSON']
```

Usage

```
{'generate_project_structure': "generate a hierarchical dictionary of a project's directory structure using ProjectStructureGenerator", 'format_project_tree': 'format a project structure dictionary into a human-readable tree text with indentation', 'check_ignore_pattern': 'check if a file or directory path should be ignored based on configured patterns', 'generate_structure_with_depth': 'generate a project structure dictionary limited to a specified maximum traversal depth', 'run_repo_tree_cli': 'run the repo_tree CLI to output a project directory tree as text or JSON'}
```

