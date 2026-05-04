# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/boost/libs/url/extra/gdb/boost_url_printers.py

Prompts

```
['register GDB pretty printers for Boost URL types by appending the lookup function to gdb pretty_printers', 'lookup and return the appropriate GDB pretty printer for a given gdb.Value based on its resolved typename', 'decode a percent-encoded URL string using urllib.parse.unquote to return the human-readable decoded string', 'create a boost::core::basic_string_view from a gdb.Value C string pointer and length using malloc and gdb.execute', 'iterate and yield all URL component parts like scheme host port path query and fragment as gdb pretty printer children']
```

Usage

```
{'register_boost_url_printers': 'register GDB pretty printers for Boost URL types by appending the lookup function to gdb pretty_printers', 'lookup_function': 'lookup and return the appropriate GDB pretty printer for a given gdb.Value based on its resolved typename', 'utils_pct_decode': 'decode a percent-encoded URL string using urllib.parse.unquote to return the human-readable decoded string', 'utils_make_string_view': 'create a boost::core::basic_string_view from a gdb.Value C string pointer and length using malloc and gdb.execute', 'UrlImplPrinter_children': 'iterate and yield all URL component parts like scheme host port path query and fragment as gdb pretty printer children'}
```

