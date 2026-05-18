# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/libcxx/utils/libcxx/sym_check/diff.py

Prompts

```
['run diff on two symbol lists to find added, removed, and changed symbols', 'find symbols added between an old and new symbol list', 'find symbols removed between an old and new symbol list', 'find symbols that changed between an old and new symbol list', 'generate a human-readable report of added, removed, and changed symbols with ABI breakage summary', 'extract symbols from a shared library using readelf or nm and return a filtered unique list', 'create an NMExtractor instance to extract symbols from a library using the nm command line tool', 'create a ReadElfExtractor instance to extract symbols from a library using the readelf command line tool', 'review the NMExtractor _extract_sym method that parses nm output lines into symbol dictionaries with name type and size', 'review the ReadElfExtractor process_syms method that parses readelf dynamic symbol table output into symbol dictionaries', 'find and report all symbols matching a list of regex patterns and return a count and report', 'find all symbols in a list that match a given regex pattern and return matching entries', 'run symbol matching against a list of regex patterns and generate a detailed match report', 'test the find_matching_symbols function with a sample symbol list and regex pattern', 'refactor find_and_report_matching to support case-insensitive regex matching and additional symbol attributes', 'demangle a C++ mangled symbol name using c++filt via demangle_symbol', 'filter a list of symbols into stdlib and non-stdlib categories using filter_stdlib_symbols', 'check if a symbol name belongs to the C++ standard library using is_stdlib_symbol_name', 'write a sorted list of symbols to a file or stdout using write_syms']
```

Usage

```
{'diff_symbol_lists': 'run diff on two symbol lists to find added, removed, and changed symbols', 'added_symbols_function': 'find symbols added between an old and new symbol list', 'removed_symbols_function': 'find symbols removed between an old and new symbol list', 'changed_symbols_function': 'find symbols that changed between an old and new symbol list', 'report_diff_function': 'generate a human-readable report of added, removed, and changed symbols with ABI breakage summary'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/libcxx/utils/libcxx/sym_check/extract.py

Prompts

```
['run diff on two symbol lists to find added, removed, and changed symbols', 'find symbols added between an old and new symbol list', 'find symbols removed between an old and new symbol list', 'find symbols that changed between an old and new symbol list', 'generate a human-readable report of added, removed, and changed symbols with ABI breakage summary', 'extract symbols from a shared library using readelf or nm and return a filtered unique list', 'create an NMExtractor instance to extract symbols from a library using the nm command line tool', 'create a ReadElfExtractor instance to extract symbols from a library using the readelf command line tool', 'review the NMExtractor _extract_sym method that parses nm output lines into symbol dictionaries with name type and size', 'review the ReadElfExtractor process_syms method that parses readelf dynamic symbol table output into symbol dictionaries', 'find and report all symbols matching a list of regex patterns and return a count and report', 'find all symbols in a list that match a given regex pattern and return matching entries', 'run symbol matching against a list of regex patterns and generate a detailed match report', 'test the find_matching_symbols function with a sample symbol list and regex pattern', 'refactor find_and_report_matching to support case-insensitive regex matching and additional symbol attributes', 'demangle a C++ mangled symbol name using c++filt via demangle_symbol', 'filter a list of symbols into stdlib and non-stdlib categories using filter_stdlib_symbols', 'check if a symbol name belongs to the C++ standard library using is_stdlib_symbol_name', 'write a sorted list of symbols to a file or stdout using write_syms']
```

Usage

```
{'extract_symbols_from_library': 'extract symbols from a shared library using readelf or nm and return a filtered unique list', 'create_NMExtractor_for_nm': 'create an NMExtractor instance to extract symbols from a library using the nm command line tool', 'create_ReadElfExtractor_for_readelf': 'create a ReadElfExtractor instance to extract symbols from a library using the readelf command line tool', 'review_NMExtractor_extract_sym': 'review the NMExtractor _extract_sym method that parses nm output lines into symbol dictionaries with name type and size', 'review_ReadElfExtractor_process_syms': 'review the ReadElfExtractor process_syms method that parses readelf dynamic symbol table output into symbol dictionaries'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/libcxx/utils/libcxx/sym_check/match.py

Prompts

```
['run diff on two symbol lists to find added, removed, and changed symbols', 'find symbols added between an old and new symbol list', 'find symbols removed between an old and new symbol list', 'find symbols that changed between an old and new symbol list', 'generate a human-readable report of added, removed, and changed symbols with ABI breakage summary', 'extract symbols from a shared library using readelf or nm and return a filtered unique list', 'create an NMExtractor instance to extract symbols from a library using the nm command line tool', 'create a ReadElfExtractor instance to extract symbols from a library using the readelf command line tool', 'review the NMExtractor _extract_sym method that parses nm output lines into symbol dictionaries with name type and size', 'review the ReadElfExtractor process_syms method that parses readelf dynamic symbol table output into symbol dictionaries', 'find and report all symbols matching a list of regex patterns and return a count and report', 'find all symbols in a list that match a given regex pattern and return matching entries', 'run symbol matching against a list of regex patterns and generate a detailed match report', 'test the find_matching_symbols function with a sample symbol list and regex pattern', 'refactor find_and_report_matching to support case-insensitive regex matching and additional symbol attributes', 'demangle a C++ mangled symbol name using c++filt via demangle_symbol', 'filter a list of symbols into stdlib and non-stdlib categories using filter_stdlib_symbols', 'check if a symbol name belongs to the C++ standard library using is_stdlib_symbol_name', 'write a sorted list of symbols to a file or stdout using write_syms']
```

Usage

```
{'find_and_report_matching': 'find and report all symbols matching a list of regex patterns and return a count and report', 'find_matching_symbols': 'find all symbols in a list that match a given regex pattern and return matching entries', 'run_symbol_matching': 'run symbol matching against a list of regex patterns and generate a detailed match report', 'test_find_matching_symbols': 'test the find_matching_symbols function with a sample symbol list and regex pattern', 'refactor_find_and_report_matching': 'refactor find_and_report_matching to support case-insensitive regex matching and additional symbol attributes'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/libcxx/utils/libcxx/sym_check/util.py

Prompts

```
['run diff on two symbol lists to find added, removed, and changed symbols', 'find symbols added between an old and new symbol list', 'find symbols removed between an old and new symbol list', 'find symbols that changed between an old and new symbol list', 'generate a human-readable report of added, removed, and changed symbols with ABI breakage summary', 'extract symbols from a shared library using readelf or nm and return a filtered unique list', 'create an NMExtractor instance to extract symbols from a library using the nm command line tool', 'create a ReadElfExtractor instance to extract symbols from a library using the readelf command line tool', 'review the NMExtractor _extract_sym method that parses nm output lines into symbol dictionaries with name type and size', 'review the ReadElfExtractor process_syms method that parses readelf dynamic symbol table output into symbol dictionaries', 'find and report all symbols matching a list of regex patterns and return a count and report', 'find all symbols in a list that match a given regex pattern and return matching entries', 'run symbol matching against a list of regex patterns and generate a detailed match report', 'test the find_matching_symbols function with a sample symbol list and regex pattern', 'refactor find_and_report_matching to support case-insensitive regex matching and additional symbol attributes', 'demangle a C++ mangled symbol name using c++filt via demangle_symbol', 'filter a list of symbols into stdlib and non-stdlib categories using filter_stdlib_symbols', 'check if a symbol name belongs to the C++ standard library using is_stdlib_symbol_name', 'write a sorted list of symbols to a file or stdout using write_syms']
```

Usage

```
{'extract_symbols_from_library': 'extract symbols from an ELF or Mach-O binary library file using extract_or_load', 'demangle_cpp_symbol': 'demangle a C++ mangled symbol name using c++filt via demangle_symbol', 'filter_stdlib_symbols': 'filter a list of symbols into stdlib and non-stdlib categories using filter_stdlib_symbols', 'check_stdlib_symbol': 'check if a symbol name belongs to the C++ standard library using is_stdlib_symbol_name', 'write_symbols_to_file': 'write a sorted list of symbols to a file or stdout using write_syms'}
```

