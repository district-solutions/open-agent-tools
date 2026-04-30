# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/data_export/tests/test_api.py

Prompts

```
['test the ExportConvertAPI POST endpoint to convert an export snapshot to CSV format', 'test the convert endpoint returns 400 when conversion to the same format is already in progress', 'test the convert endpoint allows retry when a previous conversion attempt has failed', 'test the async_convert function converts an export snapshot to the specified format and saves the result file', 'test the set_convert_background_failure callback marks a ConvertedFormat as FAILED with traceback']
```

Usage

```
{'test_export_convert_api': 'test the ExportConvertAPI POST endpoint to convert an export snapshot to CSV format', 'test_convert_export_already_started': 'test the convert endpoint returns 400 when conversion to the same format is already in progress', 'test_convert_export_previous_failed': 'test the convert endpoint allows retry when a previous conversion attempt has failed', 'test_async_convert_function': 'test the async_convert function converts an export snapshot to the specified format and saves the result file', 'test_set_convert_background_failure': 'test the set_convert_background_failure callback marks a ConvertedFormat as FAILED with traceback'}
```

