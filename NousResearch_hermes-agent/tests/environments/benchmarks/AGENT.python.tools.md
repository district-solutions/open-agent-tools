# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/tests/environments/benchmarks/test_terminalbench2_env_security.py

Prompts

```
['test extracting a safe base64-encoded tar archive with nested directories and files', 'test that base64 tar extraction rejects archive members with path traversal sequences', 'test that base64 tar extraction rejects archive members containing symlinks', 'build a base64-encoded gzip tar archive from a list of directory, file, and symlink entries', 'load the terminalbench2_env module with stubbed dependencies for testing']
```

Usage

```
{'test_extract_base64_tar_allows_safe_files': 'test extracting a safe base64-encoded tar archive with nested directories and files', 'test_extract_base64_tar_rejects_path_traversal': 'test that base64 tar extraction rejects archive members with path traversal sequences', 'test_extract_base64_tar_rejects_symlinks': 'test that base64 tar extraction rejects archive members containing symlinks', 'build_tar_b64': 'build a base64-encoded gzip tar archive from a list of directory, file, and symlink entries', 'load_terminalbench_module': 'load the terminalbench2_env module with stubbed dependencies for testing'}
```

