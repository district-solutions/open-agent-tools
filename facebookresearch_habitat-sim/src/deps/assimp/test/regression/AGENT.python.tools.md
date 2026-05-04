# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/assimp/test/regression/ai_regression_ui.py

Prompts

```
['run the ASSIMP regression test suite using the RegDialog run_reg method', 'update the regression test database by calling reg_update with the assimp executable path', 'show the ASSIMP library version by opening a VersionDialog from the RegDialog UI', 'configure the ASSIMP binary path using the SetupDialog to set a new executable location', 'open the regression test output log file with the system default editor via open_log', 'run gen_db.py with assimp binary to generate regression test database from model files', 'run process_dir to recursively generate assimp dump records for all model files in a directory', 'run make_zip to compress regression database directory into a deflated ZIP archive', 'run extract_zip to unzip the regression database archive into the database directory', 'run gen_db.py with --preview flag to preview file extensions without generating dumps', 'run the regression suite result checker to compare failures against the whitelist', 'create a function that reads a semicolon-delimited CSV file and returns a dictionary', 'create a function that prints a PASSED status message and returns exit code 0', 'create a function that prints a FAILED status message and returns exit code -1', 'review the run function that compares regression failures against a whitelisted set', 'recursively process a directory of 3D model files and compare assimp dump output against expected results', 'report test results and write failure details to a CSV file in the results directory', 'recursively delete a folder and all its files and subdirectories using os.walk', 'set an environment variable to configure the assimp binary path for the regression test runner', 'compute an SDBM hash from a file path and postprocessing config string', 'test the hashing function with a sample file path and postprocessing value', 'review the hashing function SDBM algorithm for cross-platform consistency', 'refactor the hashing function to use hashlib while preserving cross-platform persistence', 'summarize the hashing function used by gen_db and run regression test scripts']
```

Usage

```
{'run_regression_test_suite': 'run the ASSIMP regression test suite using the RegDialog run_reg method', 'update_regression_database': 'update the regression test database by calling reg_update with the assimp executable path', 'show_assimp_version': 'show the ASSIMP library version by opening a VersionDialog from the RegDialog UI', 'setup_assimp_executable_path': 'configure the ASSIMP binary path using the SetupDialog to set a new executable location', 'open_regression_log': 'open the regression test output log file with the system default editor via open_log'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/test/regression/gen_db.py

Prompts

```
['run the ASSIMP regression test suite using the RegDialog run_reg method', 'update the regression test database by calling reg_update with the assimp executable path', 'show the ASSIMP library version by opening a VersionDialog from the RegDialog UI', 'configure the ASSIMP binary path using the SetupDialog to set a new executable location', 'open the regression test output log file with the system default editor via open_log', 'run gen_db.py with assimp binary to generate regression test database from model files', 'run process_dir to recursively generate assimp dump records for all model files in a directory', 'run make_zip to compress regression database directory into a deflated ZIP archive', 'run extract_zip to unzip the regression database archive into the database directory', 'run gen_db.py with --preview flag to preview file extensions without generating dumps', 'run the regression suite result checker to compare failures against the whitelist', 'create a function that reads a semicolon-delimited CSV file and returns a dictionary', 'create a function that prints a PASSED status message and returns exit code 0', 'create a function that prints a FAILED status message and returns exit code -1', 'review the run function that compares regression failures against a whitelisted set', 'recursively process a directory of 3D model files and compare assimp dump output against expected results', 'report test results and write failure details to a CSV file in the results directory', 'recursively delete a folder and all its files and subdirectories using os.walk', 'set an environment variable to configure the assimp binary path for the regression test runner', 'compute an SDBM hash from a file path and postprocessing config string', 'test the hashing function with a sample file path and postprocessing value', 'review the hashing function SDBM algorithm for cross-platform consistency', 'refactor the hashing function to use hashlib while preserving cross-platform persistence', 'summarize the hashing function used by gen_db and run regression test scripts']
```

Usage

```
{'gen_regression_database': 'run gen_db.py with assimp binary to generate regression test database from model files', 'process_dir_recursive_dumps': 'run process_dir to recursively generate assimp dump records for all model files in a directory', 'make_zip_database': 'run make_zip to compress regression database directory into a deflated ZIP archive', 'extract_zip_database': 'run extract_zip to unzip the regression database archive into the database directory', 'preview_extensions': 'run gen_db.py with --preview flag to preview file extensions without generating dumps'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/test/regression/result_checker.py

Prompts

```
['run the ASSIMP regression test suite using the RegDialog run_reg method', 'update the regression test database by calling reg_update with the assimp executable path', 'show the ASSIMP library version by opening a VersionDialog from the RegDialog UI', 'configure the ASSIMP binary path using the SetupDialog to set a new executable location', 'open the regression test output log file with the system default editor via open_log', 'run gen_db.py with assimp binary to generate regression test database from model files', 'run process_dir to recursively generate assimp dump records for all model files in a directory', 'run make_zip to compress regression database directory into a deflated ZIP archive', 'run extract_zip to unzip the regression database archive into the database directory', 'run gen_db.py with --preview flag to preview file extensions without generating dumps', 'run the regression suite result checker to compare failures against the whitelist', 'create a function that reads a semicolon-delimited CSV file and returns a dictionary', 'create a function that prints a PASSED status message and returns exit code 0', 'create a function that prints a FAILED status message and returns exit code -1', 'review the run function that compares regression failures against a whitelisted set', 'recursively process a directory of 3D model files and compare assimp dump output against expected results', 'report test results and write failure details to a CSV file in the results directory', 'recursively delete a folder and all its files and subdirectories using os.walk', 'set an environment variable to configure the assimp binary path for the regression test runner', 'compute an SDBM hash from a file path and postprocessing config string', 'test the hashing function with a sample file path and postprocessing value', 'review the hashing function SDBM algorithm for cross-platform consistency', 'refactor the hashing function to use hashlib while preserving cross-platform persistence', 'summarize the hashing function used by gen_db and run regression test scripts']
```

Usage

```
{'run_regression_checker': 'run the regression suite result checker to compare failures against the whitelist', 'read_results_csv': 'create a function that reads a semicolon-delimited CSV file and returns a dictionary', 'passed_message': 'create a function that prints a PASSED status message and returns exit code 0', 'failed_message': 'create a function that prints a FAILED status message and returns exit code -1', 'review_run_function': 'review the run function that compares regression failures against a whitelisted set'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/test/regression/run.py

Prompts

```
['run the ASSIMP regression test suite using the RegDialog run_reg method', 'update the regression test database by calling reg_update with the assimp executable path', 'show the ASSIMP library version by opening a VersionDialog from the RegDialog UI', 'configure the ASSIMP binary path using the SetupDialog to set a new executable location', 'open the regression test output log file with the system default editor via open_log', 'run gen_db.py with assimp binary to generate regression test database from model files', 'run process_dir to recursively generate assimp dump records for all model files in a directory', 'run make_zip to compress regression database directory into a deflated ZIP archive', 'run extract_zip to unzip the regression database archive into the database directory', 'run gen_db.py with --preview flag to preview file extensions without generating dumps', 'run the regression suite result checker to compare failures against the whitelist', 'create a function that reads a semicolon-delimited CSV file and returns a dictionary', 'create a function that prints a PASSED status message and returns exit code 0', 'create a function that prints a FAILED status message and returns exit code -1', 'review the run function that compares regression failures against a whitelisted set', 'recursively process a directory of 3D model files and compare assimp dump output against expected results', 'report test results and write failure details to a CSV file in the results directory', 'recursively delete a folder and all its files and subdirectories using os.walk', 'set an environment variable to configure the assimp binary path for the regression test runner', 'compute an SDBM hash from a file path and postprocessing config string', 'test the hashing function with a sample file path and postprocessing value', 'review the hashing function SDBM algorithm for cross-platform consistency', 'refactor the hashing function to use hashlib while preserving cross-platform persistence', 'summarize the hashing function used by gen_db and run regression test scripts']
```

Usage

```
{'run_regression_test_suite': 'run the assimp regression test suite against model directories using a zip database of expected dumps', 'process_dir_recurse': 'recursively process a directory of 3D model files and compare assimp dump output against expected results', 'results_report_failures': 'report test results and write failure details to a CSV file in the results directory', 'del_folder_with_contents': 'recursively delete a folder and all its files and subdirectories using os.walk', 'setEnvVar_assimp_path': 'set an environment variable to configure the assimp binary path for the regression test runner'}
```

## File: facebookresearch_habitat-sim/src/deps/assimp/test/regression/utils.py

Prompts

```
['run the ASSIMP regression test suite using the RegDialog run_reg method', 'update the regression test database by calling reg_update with the assimp executable path', 'show the ASSIMP library version by opening a VersionDialog from the RegDialog UI', 'configure the ASSIMP binary path using the SetupDialog to set a new executable location', 'open the regression test output log file with the system default editor via open_log', 'run gen_db.py with assimp binary to generate regression test database from model files', 'run process_dir to recursively generate assimp dump records for all model files in a directory', 'run make_zip to compress regression database directory into a deflated ZIP archive', 'run extract_zip to unzip the regression database archive into the database directory', 'run gen_db.py with --preview flag to preview file extensions without generating dumps', 'run the regression suite result checker to compare failures against the whitelist', 'create a function that reads a semicolon-delimited CSV file and returns a dictionary', 'create a function that prints a PASSED status message and returns exit code 0', 'create a function that prints a FAILED status message and returns exit code -1', 'review the run function that compares regression failures against a whitelisted set', 'recursively process a directory of 3D model files and compare assimp dump output against expected results', 'report test results and write failure details to a CSV file in the results directory', 'recursively delete a folder and all its files and subdirectories using os.walk', 'set an environment variable to configure the assimp binary path for the regression test runner', 'compute an SDBM hash from a file path and postprocessing config string', 'test the hashing function with a sample file path and postprocessing value', 'review the hashing function SDBM algorithm for cross-platform consistency', 'refactor the hashing function to use hashlib while preserving cross-platform persistence', 'summarize the hashing function used by gen_db and run regression test scripts']
```

Usage

```
{'hash_file_and_config': 'compute an SDBM hash from a file path and postprocessing config string', 'test_hashing_function': 'test the hashing function with a sample file path and postprocessing value', 'review_hashing_implementation': 'review the hashing function SDBM algorithm for cross-platform consistency', 'refactor_hashing_to_modern_hash': 'refactor the hashing function to use hashlib while preserving cross-platform persistence', 'summarize_hashing_usage': 'summarize the hashing function used by gen_db and run regression test scripts'}
```

