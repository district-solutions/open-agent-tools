# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/boost/libs/json/src/boost_json_gdb_printers.py

Prompts

```
['register the Boost.JSON GDB pretty printers for the current objfile so gdb displays values nicely', 'create a GDB pretty printer class that decodes boost::json::storage_ptr internals including shared refs and memory resources', 'create a GDB pretty printer class that displays boost::json::monotonic_resource buffer, block, head, and free fields', 'create a GDB pretty printer class that displays boost::json::value by kind including null, bool, int64, uint64, double, string, array, and object', 'create a GDB pretty printer class that iterates over boost::json::array children and displays size and capacity']
```

Usage

```
{'register_boost_json_pretty_printers': 'register the Boost.JSON GDB pretty printers for the current objfile so gdb displays values nicely', 'create_storage_ptr_printer': 'create a GDB pretty printer class that decodes boost::json::storage_ptr internals including shared refs and memory resources', 'create_monotonic_resource_printer': 'create a GDB pretty printer class that displays boost::json::monotonic_resource buffer, block, head, and free fields', 'create_json_value_printer': 'create a GDB pretty printer class that displays boost::json::value by kind including null, bool, int64, uint64, double, string, array, and object', 'create_json_array_printer': 'create a GDB pretty printer class that iterates over boost::json::array children and displays size and capacity'}
```

