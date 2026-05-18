# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/scripts/check_npm_package_versions.py

Prompts

```
['run the script to check if deployed npm packages match the source repository versions', 'run the npm version check for the bootstrap-chat package against the npm registry', 'review the run_check function that compares local package versions with npm registry versions', 'refactor the run_check function to support checking additional npm packages beyond bootstrap-chat', 'test the run_check function to verify it correctly detects version mismatches between local and npm packages', 'run the script to sync mephisto-core version across all dependent target files', 'run the script with check mode to verify all target files have the correct mephisto-core version', 'run the run_replace function to replace CURR_MEPHISTO_CORE_PACKAGE_VERSION in target files with the latest version', 'run the script in check mode to validate that all router files are synced to the current mephisto-core version', 'run the script to read and display the current mephisto-core version from packages/mephisto-core/package.json', 'run the script to add copyright headers to all files in a directory recursively', 'run the script with replace_existing to update existing copyright headers in all files', 'run the script with an extension filter to process only specific file types', 'update the copyright header on a single file using _update_copyright_header', 'generate copyright comment lines formatted for a specific file type like py or js']
```

Usage

```
{'run_check_npm_versions': 'run the script to check if deployed npm packages match the source repository versions', 'run_check_bootstrap_chat': 'run the npm version check for the bootstrap-chat package against the npm registry', 'review_run_check': 'review the run_check function that compares local package versions with npm registry versions', 'refactor_run_check': 'refactor the run_check function to support checking additional npm packages beyond bootstrap-chat', 'test_run_check': 'test the run_check function to verify it correctly detects version mismatches between local and npm packages'}
```

## File: facebookresearch_mephisto/scripts/sync_mephisto_core.py

Prompts

```
['run the script to check if deployed npm packages match the source repository versions', 'run the npm version check for the bootstrap-chat package against the npm registry', 'review the run_check function that compares local package versions with npm registry versions', 'refactor the run_check function to support checking additional npm packages beyond bootstrap-chat', 'test the run_check function to verify it correctly detects version mismatches between local and npm packages', 'run the script to sync mephisto-core version across all dependent target files', 'run the script with check mode to verify all target files have the correct mephisto-core version', 'run the run_replace function to replace CURR_MEPHISTO_CORE_PACKAGE_VERSION in target files with the latest version', 'run the script in check mode to validate that all router files are synced to the current mephisto-core version', 'run the script to read and display the current mephisto-core version from packages/mephisto-core/package.json', 'run the script to add copyright headers to all files in a directory recursively', 'run the script with replace_existing to update existing copyright headers in all files', 'run the script with an extension filter to process only specific file types', 'update the copyright header on a single file using _update_copyright_header', 'generate copyright comment lines formatted for a specific file type like py or js']
```

Usage

```
{'run_sync_mephisto_core': 'run the script to sync mephisto-core version across all dependent target files', 'run_check_mephisto_core': 'run the script with check mode to verify all target files have the correct mephisto-core version', 'run_replace_version': 'run the run_replace function to replace CURR_MEPHISTO_CORE_PACKAGE_VERSION in target files with the latest version', 'run_validate_version_sync': 'run the script in check mode to validate that all router files are synced to the current mephisto-core version', 'run_get_core_version': 'run the script to read and display the current mephisto-core version from packages/mephisto-core/package.json'}
```

## File: facebookresearch_mephisto/scripts/update_copyright_headers.py

Prompts

```
['run the script to check if deployed npm packages match the source repository versions', 'run the npm version check for the bootstrap-chat package against the npm registry', 'review the run_check function that compares local package versions with npm registry versions', 'refactor the run_check function to support checking additional npm packages beyond bootstrap-chat', 'test the run_check function to verify it correctly detects version mismatches between local and npm packages', 'run the script to sync mephisto-core version across all dependent target files', 'run the script with check mode to verify all target files have the correct mephisto-core version', 'run the run_replace function to replace CURR_MEPHISTO_CORE_PACKAGE_VERSION in target files with the latest version', 'run the script in check mode to validate that all router files are synced to the current mephisto-core version', 'run the script to read and display the current mephisto-core version from packages/mephisto-core/package.json', 'run the script to add copyright headers to all files in a directory recursively', 'run the script with replace_existing to update existing copyright headers in all files', 'run the script with an extension filter to process only specific file types', 'update the copyright header on a single file using _update_copyright_header', 'generate copyright comment lines formatted for a specific file type like py or js']
```

Usage

```
{'run_update_copyright_headers': 'run the script to add copyright headers to all files in a directory recursively', 'run_replace_existing_copyright': 'run the script with replace_existing to update existing copyright headers in all files', 'run_filter_by_extension': 'run the script with an extension filter to process only specific file types', 'update_single_file_copyright': 'update the copyright header on a single file using _update_copyright_header', 'make_copyright_lines_for_type': 'generate copyright comment lines formatted for a specific file type like py or js'}
```

