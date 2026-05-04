# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/boost/libs/pfr/misc/generate_cpp17.py

Prompts

```
['run the script to generate a C++17 Boost.PFR core header with 200 tie_as_tuple specializations', 'run the script with a custom argument to generate tie_as_tuple specializations for a specific number of fields', 'generate C++ workaround_cast expressions from comma-separated index tokens with configurable line formatting', 'count the number of comma-separated index tokens in a given string', 'use the EmptyLinePrinter class to print exactly one empty line across multiple calls', 'run the script to generate C++ test code for Boost.PFR struct field name verification', 'generate C++ aggregate struct definitions with randomized field names avoiding C++ keywords', 'generate BOOST_TEST_EQ checker functions that verify boost::pfr::get_name for each struct field', 'generate test functions that verify boost::pfr::names_as_array returns correct field names as an array', 'generate a random alphanumeric field name that avoids all C++ reserved keywords']
```

Usage

```
{'generate_cpp17_header': 'run the script to generate a C++17 Boost.PFR core header with 200 tie_as_tuple specializations', 'generate_custom_field_count': 'run the script with a custom argument to generate tie_as_tuple specializations for a specific number of fields', 'fold_workaround_cast': 'generate C++ workaround_cast expressions from comma-separated index tokens with configurable line formatting', 'calc_indexes_count': 'count the number of comma-separated index tokens in a given string', 'empty_line_printer': 'use the EmptyLinePrinter class to print exactly one empty line across multiple calls'}
```

## File: google-deepmind_actionengine/third_party/boost/libs/pfr/misc/generate_fields_names_big.cpp.py

Prompts

```
['run the script to generate a C++17 Boost.PFR core header with 200 tie_as_tuple specializations', 'run the script with a custom argument to generate tie_as_tuple specializations for a specific number of fields', 'generate C++ workaround_cast expressions from comma-separated index tokens with configurable line formatting', 'count the number of comma-separated index tokens in a given string', 'use the EmptyLinePrinter class to print exactly one empty line across multiple calls', 'run the script to generate C++ test code for Boost.PFR struct field name verification', 'generate C++ aggregate struct definitions with randomized field names avoiding C++ keywords', 'generate BOOST_TEST_EQ checker functions that verify boost::pfr::get_name for each struct field', 'generate test functions that verify boost::pfr::names_as_array returns correct field names as an array', 'generate a random alphanumeric field name that avoids all C++ reserved keywords']
```

Usage

```
{'generate_cpp_test_code': 'run the script to generate C++ test code for Boost.PFR struct field name verification', 'generate_struct_definitions': 'generate C++ aggregate struct definitions with randomized field names avoiding C++ keywords', 'generate_test_get_name_definitions': 'generate BOOST_TEST_EQ checker functions that verify boost::pfr::get_name for each struct field', 'generate_test_names_as_array_definitions': 'generate test functions that verify boost::pfr::names_as_array returns correct field names as an array', 'generate_random_field_name': 'generate a random alphanumeric field name that avoids all C++ reserved keywords'}
```

