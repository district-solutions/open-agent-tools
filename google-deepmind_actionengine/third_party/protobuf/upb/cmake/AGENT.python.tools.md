# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/protobuf/upb/cmake/staleness_test.py

Prompts

```
['run the staleness test to check if generated files match their targets', 'run the staleness test with --fix flag to copy generated files over stale targets', 'create a Config object from a file list for staleness test validation', 'check whether each target file matches its corresponding generated file and report errors', 'test the TestFilesMatch unittest class to verify all generated files are up to date', 'run _GetFilePairs with a Config object to generate a list of FilePair objects mapping target to generated files', 'run _GetMissingAndStaleFiles with file pairs to return separate lists of missing and stale file pairs']
```

Usage

```
{'run_staleness_test': 'run the staleness test to check if generated files match their targets', 'fix_stale_files': 'run the staleness test with --fix flag to copy generated files over stale targets', 'create_config': 'create a Config object from a file list for staleness test validation', 'check_files_match': 'check whether each target file matches its corresponding generated file and report errors', 'test_testfilesmatch': 'test the TestFilesMatch unittest class to verify all generated files are up to date'}
```

## File: google-deepmind_actionengine/third_party/protobuf/upb/cmake/staleness_test_lib.py

Prompts

```
['run the staleness test to check if generated files match their targets', 'run the staleness test with --fix flag to copy generated files over stale targets', 'create a Config object from a file list for staleness test validation', 'check whether each target file matches its corresponding generated file and report errors', 'test the TestFilesMatch unittest class to verify all generated files are up to date', 'run _GetFilePairs with a Config object to generate a list of FilePair objects mapping target to generated files', 'run _GetMissingAndStaleFiles with file pairs to return separate lists of missing and stale file pairs']
```

Usage

```
{'fix_stale_files': 'run FixFiles with a Config object to overwrite missing or out-of-date target files with generated ones', 'check_files_match': 'run CheckFilesMatch with a Config object to verify target files match their generated counterparts and get diff errors', 'create_config': 'create a Config object from a file list containing filenames, pattern, package name, and target name', 'get_file_pairs': 'run _GetFilePairs with a Config object to generate a list of FilePair objects mapping target to generated files', 'detect_missing_stale': 'run _GetMissingAndStaleFiles with file pairs to return separate lists of missing and stale file pairs'}
```

