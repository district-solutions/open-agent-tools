# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/utils/tests/integration_test.py

Prompts

```
['test the S3 file write and read round-trip using abstract_file_ctx context managers', 'run the integration test that writes to S3 and reads back to verify content', 'review the abstract_file_writer_ctx usage for writing data to S3 paths', 'review the abstract_file_reader_path usage for reading text from S3 paths', 'refactor the test_s3_file_helper to add assertions for different file content types', 'test the abstract_file_reader_path function to handle local and S3 paths correctly', 'test the abstract_file_writer_ctx function to write to local and S3 paths', 'run the TestAbstractFileCtx unittest class to verify abstract file context functionality', 'test the BufferedS3Reader seek method to move the cursor to a given index in buffered S3 data', 'test the BufferedS3Reader read method to read characters from the current cursor position in S3 data', 'test the BufferedS3Reader copy_to_local method to write buffered S3 data to a temporary local file', 'test the BufferedS3Writer context manager to write buffered data to S3 on exit', 'test the BufferedS3Writer write method to append data to the internal buffer before flushing to S3', 'test the colored function returns ANSI color codes when output is a TTY', 'test the colored function returns plain text when output is not a TTY', 'run the TestColor unit test suite to verify color utility behavior', 'review the TestColor class and its mocked termcolor test methods', 'refactor the test_colored_not_tty method to remove the early return and restore assertions', 'test ConfigYamlDict.from_file to load and parse a valid YAML config file into a dictionary', 'test ConfigYamlDict.from_file raises ConfigYamlFileParsingError when given an invalid YAML file', 'test ConfigYamlDict key access raises ConfigYamlFieldNotFoundError for missing keys', 'test ConfigYamlDict.from_dict converts a plain dictionary into a ConfigYamlDict instance', 'test ConfigYamlDict setitem recursively converts nested dicts to ConfigYamlDict instances']
```

Usage

```
{'test_s3_file_helper': 'test the S3 file write and read round-trip using abstract_file_ctx context managers', 'run_integration_test': 'run the integration test that writes to S3 and reads back to verify content', 'review_abstract_file_writer_ctx': 'review the abstract_file_writer_ctx usage for writing data to S3 paths', 'review_abstract_file_reader_path': 'review the abstract_file_reader_path usage for reading text from S3 paths', 'refactor_test_s3_file_helper': 'refactor the test_s3_file_helper to add assertions for different file content types'}
```

## File: facebookresearch_fbpcs/fbpcs/utils/tests/test_abstract_file_ctx.py

Prompts

```
['test the S3 file write and read round-trip using abstract_file_ctx context managers', 'run the integration test that writes to S3 and reads back to verify content', 'review the abstract_file_writer_ctx usage for writing data to S3 paths', 'review the abstract_file_reader_path usage for reading text from S3 paths', 'refactor the test_s3_file_helper to add assertions for different file content types', 'test the abstract_file_reader_path function to handle local and S3 paths correctly', 'test the abstract_file_writer_ctx function to write to local and S3 paths', 'run the TestAbstractFileCtx unittest class to verify abstract file context functionality', 'test the BufferedS3Reader seek method to move the cursor to a given index in buffered S3 data', 'test the BufferedS3Reader read method to read characters from the current cursor position in S3 data', 'test the BufferedS3Reader copy_to_local method to write buffered S3 data to a temporary local file', 'test the BufferedS3Writer context manager to write buffered data to S3 on exit', 'test the BufferedS3Writer write method to append data to the internal buffer before flushing to S3', 'test the colored function returns ANSI color codes when output is a TTY', 'test the colored function returns plain text when output is not a TTY', 'run the TestColor unit test suite to verify color utility behavior', 'review the TestColor class and its mocked termcolor test methods', 'refactor the test_colored_not_tty method to remove the early return and restore assertions', 'test ConfigYamlDict.from_file to load and parse a valid YAML config file into a dictionary', 'test ConfigYamlDict.from_file raises ConfigYamlFileParsingError when given an invalid YAML file', 'test ConfigYamlDict key access raises ConfigYamlFieldNotFoundError for missing keys', 'test ConfigYamlDict.from_dict converts a plain dictionary into a ConfigYamlDict instance', 'test ConfigYamlDict setitem recursively converts nested dicts to ConfigYamlDict instances']
```

Usage

```
{'test_abstract_file_reader_path': 'test the abstract_file_reader_path function to handle local and S3 paths correctly', 'test_abstract_file_writer_ctx': 'test the abstract_file_writer_ctx function to write to local and S3 paths', 'run_TestAbstractFileCtx': 'run the TestAbstractFileCtx unittest class to verify abstract file context functionality', 'review_abstract_file_reader_path': 'review the abstract_file_reader_path function that returns local paths or copies S3 files locally', 'review_abstract_file_writer_ctx': 'review the abstract_file_writer_ctx function that returns a writer context manager for local or S3 paths'}
```

## File: facebookresearch_fbpcs/fbpcs/utils/tests/test_buffered_s3_file_handler.py

Prompts

```
['test the S3 file write and read round-trip using abstract_file_ctx context managers', 'run the integration test that writes to S3 and reads back to verify content', 'review the abstract_file_writer_ctx usage for writing data to S3 paths', 'review the abstract_file_reader_path usage for reading text from S3 paths', 'refactor the test_s3_file_helper to add assertions for different file content types', 'test the abstract_file_reader_path function to handle local and S3 paths correctly', 'test the abstract_file_writer_ctx function to write to local and S3 paths', 'run the TestAbstractFileCtx unittest class to verify abstract file context functionality', 'test the BufferedS3Reader seek method to move the cursor to a given index in buffered S3 data', 'test the BufferedS3Reader read method to read characters from the current cursor position in S3 data', 'test the BufferedS3Reader copy_to_local method to write buffered S3 data to a temporary local file', 'test the BufferedS3Writer context manager to write buffered data to S3 on exit', 'test the BufferedS3Writer write method to append data to the internal buffer before flushing to S3', 'test the colored function returns ANSI color codes when output is a TTY', 'test the colored function returns plain text when output is not a TTY', 'run the TestColor unit test suite to verify color utility behavior', 'review the TestColor class and its mocked termcolor test methods', 'refactor the test_colored_not_tty method to remove the early return and restore assertions', 'test ConfigYamlDict.from_file to load and parse a valid YAML config file into a dictionary', 'test ConfigYamlDict.from_file raises ConfigYamlFileParsingError when given an invalid YAML file', 'test ConfigYamlDict key access raises ConfigYamlFieldNotFoundError for missing keys', 'test ConfigYamlDict.from_dict converts a plain dictionary into a ConfigYamlDict instance', 'test ConfigYamlDict setitem recursively converts nested dicts to ConfigYamlDict instances']
```

Usage

```
{'test_BufferedS3Reader_seek': 'test the BufferedS3Reader seek method to move the cursor to a given index in buffered S3 data', 'test_BufferedS3Reader_read': 'test the BufferedS3Reader read method to read characters from the current cursor position in S3 data', 'test_BufferedS3Reader_copy_to_local': 'test the BufferedS3Reader copy_to_local method to write buffered S3 data to a temporary local file', 'test_BufferedS3Writer_context_manager': 'test the BufferedS3Writer context manager to write buffered data to S3 on exit', 'test_BufferedS3Writer_write': 'test the BufferedS3Writer write method to append data to the internal buffer before flushing to S3'}
```

## File: facebookresearch_fbpcs/fbpcs/utils/tests/test_color.py

Prompts

```
['test the S3 file write and read round-trip using abstract_file_ctx context managers', 'run the integration test that writes to S3 and reads back to verify content', 'review the abstract_file_writer_ctx usage for writing data to S3 paths', 'review the abstract_file_reader_path usage for reading text from S3 paths', 'refactor the test_s3_file_helper to add assertions for different file content types', 'test the abstract_file_reader_path function to handle local and S3 paths correctly', 'test the abstract_file_writer_ctx function to write to local and S3 paths', 'run the TestAbstractFileCtx unittest class to verify abstract file context functionality', 'test the BufferedS3Reader seek method to move the cursor to a given index in buffered S3 data', 'test the BufferedS3Reader read method to read characters from the current cursor position in S3 data', 'test the BufferedS3Reader copy_to_local method to write buffered S3 data to a temporary local file', 'test the BufferedS3Writer context manager to write buffered data to S3 on exit', 'test the BufferedS3Writer write method to append data to the internal buffer before flushing to S3', 'test the colored function returns ANSI color codes when output is a TTY', 'test the colored function returns plain text when output is not a TTY', 'run the TestColor unit test suite to verify color utility behavior', 'review the TestColor class and its mocked termcolor test methods', 'refactor the test_colored_not_tty method to remove the early return and restore assertions', 'test ConfigYamlDict.from_file to load and parse a valid YAML config file into a dictionary', 'test ConfigYamlDict.from_file raises ConfigYamlFileParsingError when given an invalid YAML file', 'test ConfigYamlDict key access raises ConfigYamlFieldNotFoundError for missing keys', 'test ConfigYamlDict.from_dict converts a plain dictionary into a ConfigYamlDict instance', 'test ConfigYamlDict setitem recursively converts nested dicts to ConfigYamlDict instances']
```

Usage

```
{'test_colored_tty': 'test the colored function returns ANSI color codes when output is a TTY', 'test_colored_not_tty': 'test the colored function returns plain text when output is not a TTY', 'run_test_color_suite': 'run the TestColor unit test suite to verify color utility behavior', 'review_test_color_class': 'review the TestColor class and its mocked termcolor test methods', 'refactor_test_colored_not_tty': 'refactor the test_colored_not_tty method to remove the early return and restore assertions'}
```

## File: facebookresearch_fbpcs/fbpcs/utils/tests/test_config_yaml_dict.py

Prompts

```
['test the S3 file write and read round-trip using abstract_file_ctx context managers', 'run the integration test that writes to S3 and reads back to verify content', 'review the abstract_file_writer_ctx usage for writing data to S3 paths', 'review the abstract_file_reader_path usage for reading text from S3 paths', 'refactor the test_s3_file_helper to add assertions for different file content types', 'test the abstract_file_reader_path function to handle local and S3 paths correctly', 'test the abstract_file_writer_ctx function to write to local and S3 paths', 'run the TestAbstractFileCtx unittest class to verify abstract file context functionality', 'test the BufferedS3Reader seek method to move the cursor to a given index in buffered S3 data', 'test the BufferedS3Reader read method to read characters from the current cursor position in S3 data', 'test the BufferedS3Reader copy_to_local method to write buffered S3 data to a temporary local file', 'test the BufferedS3Writer context manager to write buffered data to S3 on exit', 'test the BufferedS3Writer write method to append data to the internal buffer before flushing to S3', 'test the colored function returns ANSI color codes when output is a TTY', 'test the colored function returns plain text when output is not a TTY', 'run the TestColor unit test suite to verify color utility behavior', 'review the TestColor class and its mocked termcolor test methods', 'refactor the test_colored_not_tty method to remove the early return and restore assertions', 'test ConfigYamlDict.from_file to load and parse a valid YAML config file into a dictionary', 'test ConfigYamlDict.from_file raises ConfigYamlFileParsingError when given an invalid YAML file', 'test ConfigYamlDict key access raises ConfigYamlFieldNotFoundError for missing keys', 'test ConfigYamlDict.from_dict converts a plain dictionary into a ConfigYamlDict instance', 'test ConfigYamlDict setitem recursively converts nested dicts to ConfigYamlDict instances']
```

Usage

```
{'test_ConfigYamlDict_from_file': 'test ConfigYamlDict.from_file to load and parse a valid YAML config file into a dictionary', 'test_ConfigYamlDict_invalid_yaml': 'test ConfigYamlDict.from_file raises ConfigYamlFileParsingError when given an invalid YAML file', 'test_ConfigYamlDict_getitem': 'test ConfigYamlDict key access raises ConfigYamlFieldNotFoundError for missing keys', 'test_ConfigYamlDict_from_dict': 'test ConfigYamlDict.from_dict converts a plain dictionary into a ConfigYamlDict instance', 'test_ConfigYamlDict_setitem': 'test ConfigYamlDict setitem recursively converts nested dicts to ConfigYamlDict instances'}
```

