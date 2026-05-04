# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/boost/libs/outcome/include/boost/outcome/experimental/status-code/status_code_gdb.py

Prompts

```
['build a gdb RegexpCollectionPrettyPrinter that registers StatusCodePrinter for system_error2::status_code types', 'register the system_error2 status_code pretty printer with gdb for the current objfile', 'review the StatusCodePrinter children method that yields domain, value, and strerror message fields', 'review the StatusCodePrinter to_string method that formats posix and generic error codes with os.strerror', 'summarize the synthesise_gdb_value_from_string function that creates a synthetic gdb.Value from a string']
```

Usage

```
{'build_pretty_printer': 'build a gdb RegexpCollectionPrettyPrinter that registers StatusCodePrinter for system_error2::status_code types', 'register_printers': 'register the system_error2 status_code pretty printer with gdb for the current objfile', 'review_StatusCodePrinter_children': 'review the StatusCodePrinter children method that yields domain, value, and strerror message fields', 'review_StatusCodePrinter_to_string': 'review the StatusCodePrinter to_string method that formats posix and generic error codes with os.strerror', 'summarize_synthesise_gdb_value_from_string': 'summarize the synthesise_gdb_value_from_string function that creates a synthetic gdb.Value from a string'}
```

