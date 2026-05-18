# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/mvfst/build/fbcode_builder/getdeps/test/expr_test.py

Prompts

```
['test parse_expr with an equality expression like foo=bar against a context dictionary', 'test parse_expr with a not expression like not(foo=bar) to negate evaluation', 'test parse_expr with an all expression requiring all conditions to evaluate true', 'test parse_expr with an any expression requiring at least one condition to evaluate true', 'test parse_expr raises an exception for invalid variables or malformed expressions', 'test ManifestParser with a minimal manifest containing only the name field', 'test ManifestParser get_section_as_args with conditional dependencies that activate based on context variables', 'test ManifestParser get_section_as_dict to retrieve cmake defines with cascading conditional sections', 'test load_all_manifests to parse and return all manifests from a given directory', 'test patch_loader with duplicate manifests to verify duplicate manifest detection raises an exception', 'create a HostType instance that auto-probes the current operating system and returns platform details', 'test the HostType.from_tuple_string method by parsing a platform tuple string like linux-fedora-38', 'test the HostType.as_tuple_string method to serialize platform info into a hyphenated string format', 'test the HostType is_windows is_darwin and is_linux methods to check platform type', 'review the PlatformTest test_create method that validates HostType round-trip serialization via tuple strings', 'test find_existing_win32_subst_for_path returns None when no subst mapping matches the given path', 'test find_existing_win32_subst_for_path returns the drive letter when an exact path match exists in the subst mapping', 'test find_existing_win32_subst_for_path returns an arbitrary drive letter when multiple mappings match the same path', 'test find_existing_win32_subst_for_path performs case-insensitive matching on drive letters and path components', 'run the Win32SubstTest unittest class to verify all five test methods for Windows subst path lookup']
```

Usage

```
{'test_parse_expr_equal': 'test parse_expr with an equality expression like foo=bar against a context dictionary', 'test_parse_expr_not': 'test parse_expr with a not expression like not(foo=bar) to negate evaluation', 'test_parse_expr_all': 'test parse_expr with an all expression requiring all conditions to evaluate true', 'test_parse_expr_any': 'test parse_expr with an any expression requiring at least one condition to evaluate true', 'test_parse_expr_invalid': 'test parse_expr raises an exception for invalid variables or malformed expressions'}
```

## File: facebookresearch_mvfst-rl/third-party/mvfst/build/fbcode_builder/getdeps/test/manifest_test.py

Prompts

```
['test parse_expr with an equality expression like foo=bar against a context dictionary', 'test parse_expr with a not expression like not(foo=bar) to negate evaluation', 'test parse_expr with an all expression requiring all conditions to evaluate true', 'test parse_expr with an any expression requiring at least one condition to evaluate true', 'test parse_expr raises an exception for invalid variables or malformed expressions', 'test ManifestParser with a minimal manifest containing only the name field', 'test ManifestParser get_section_as_args with conditional dependencies that activate based on context variables', 'test ManifestParser get_section_as_dict to retrieve cmake defines with cascading conditional sections', 'test load_all_manifests to parse and return all manifests from a given directory', 'test patch_loader with duplicate manifests to verify duplicate manifest detection raises an exception', 'create a HostType instance that auto-probes the current operating system and returns platform details', 'test the HostType.from_tuple_string method by parsing a platform tuple string like linux-fedora-38', 'test the HostType.as_tuple_string method to serialize platform info into a hyphenated string format', 'test the HostType is_windows is_darwin and is_linux methods to check platform type', 'review the PlatformTest test_create method that validates HostType round-trip serialization via tuple strings', 'test find_existing_win32_subst_for_path returns None when no subst mapping matches the given path', 'test find_existing_win32_subst_for_path returns the drive letter when an exact path match exists in the subst mapping', 'test find_existing_win32_subst_for_path returns an arbitrary drive letter when multiple mappings match the same path', 'test find_existing_win32_subst_for_path performs case-insensitive matching on drive letters and path components', 'run the Win32SubstTest unittest class to verify all five test methods for Windows subst path lookup']
```

Usage

```
{'test_ManifestParser_minimal': 'test ManifestParser with a minimal manifest containing only the name field', 'test_ManifestParser_conditional_dependencies': 'test ManifestParser get_section_as_args with conditional dependencies that activate based on context variables', 'test_ManifestParser_cmake_defines': 'test ManifestParser get_section_as_dict to retrieve cmake defines with cascading conditional sections', 'test_load_all_manifests': 'test load_all_manifests to parse and return all manifests from a given directory', 'test_patch_loader_duplicate_detection': 'test patch_loader with duplicate manifests to verify duplicate manifest detection raises an exception'}
```

## File: facebookresearch_mvfst-rl/third-party/mvfst/build/fbcode_builder/getdeps/test/platform_test.py

Prompts

```
['test parse_expr with an equality expression like foo=bar against a context dictionary', 'test parse_expr with a not expression like not(foo=bar) to negate evaluation', 'test parse_expr with an all expression requiring all conditions to evaluate true', 'test parse_expr with an any expression requiring at least one condition to evaluate true', 'test parse_expr raises an exception for invalid variables or malformed expressions', 'test ManifestParser with a minimal manifest containing only the name field', 'test ManifestParser get_section_as_args with conditional dependencies that activate based on context variables', 'test ManifestParser get_section_as_dict to retrieve cmake defines with cascading conditional sections', 'test load_all_manifests to parse and return all manifests from a given directory', 'test patch_loader with duplicate manifests to verify duplicate manifest detection raises an exception', 'create a HostType instance that auto-probes the current operating system and returns platform details', 'test the HostType.from_tuple_string method by parsing a platform tuple string like linux-fedora-38', 'test the HostType.as_tuple_string method to serialize platform info into a hyphenated string format', 'test the HostType is_windows is_darwin and is_linux methods to check platform type', 'review the PlatformTest test_create method that validates HostType round-trip serialization via tuple strings', 'test find_existing_win32_subst_for_path returns None when no subst mapping matches the given path', 'test find_existing_win32_subst_for_path returns the drive letter when an exact path match exists in the subst mapping', 'test find_existing_win32_subst_for_path returns an arbitrary drive letter when multiple mappings match the same path', 'test find_existing_win32_subst_for_path performs case-insensitive matching on drive letters and path components', 'run the Win32SubstTest unittest class to verify all five test methods for Windows subst path lookup']
```

Usage

```
{'create_HostType_auto_probe': 'create a HostType instance that auto-probes the current operating system and returns platform details', 'test_HostType_from_tuple_string': 'test the HostType.from_tuple_string method by parsing a platform tuple string like linux-fedora-38', 'test_HostType_as_tuple_string': 'test the HostType.as_tuple_string method to serialize platform info into a hyphenated string format', 'test_HostType_is_methods': 'test the HostType is_windows is_darwin and is_linux methods to check platform type', 'review_PlatformTest_test_create': 'review the PlatformTest test_create method that validates HostType round-trip serialization via tuple strings'}
```

## File: facebookresearch_mvfst-rl/third-party/mvfst/build/fbcode_builder/getdeps/test/scratch_test.py

Prompts

```
['test parse_expr with an equality expression like foo=bar against a context dictionary', 'test parse_expr with a not expression like not(foo=bar) to negate evaluation', 'test parse_expr with an all expression requiring all conditions to evaluate true', 'test parse_expr with an any expression requiring at least one condition to evaluate true', 'test parse_expr raises an exception for invalid variables or malformed expressions', 'test ManifestParser with a minimal manifest containing only the name field', 'test ManifestParser get_section_as_args with conditional dependencies that activate based on context variables', 'test ManifestParser get_section_as_dict to retrieve cmake defines with cascading conditional sections', 'test load_all_manifests to parse and return all manifests from a given directory', 'test patch_loader with duplicate manifests to verify duplicate manifest detection raises an exception', 'create a HostType instance that auto-probes the current operating system and returns platform details', 'test the HostType.from_tuple_string method by parsing a platform tuple string like linux-fedora-38', 'test the HostType.as_tuple_string method to serialize platform info into a hyphenated string format', 'test the HostType is_windows is_darwin and is_linux methods to check platform type', 'review the PlatformTest test_create method that validates HostType round-trip serialization via tuple strings', 'test find_existing_win32_subst_for_path returns None when no subst mapping matches the given path', 'test find_existing_win32_subst_for_path returns the drive letter when an exact path match exists in the subst mapping', 'test find_existing_win32_subst_for_path returns an arbitrary drive letter when multiple mappings match the same path', 'test find_existing_win32_subst_for_path performs case-insensitive matching on drive letters and path components', 'run the Win32SubstTest unittest class to verify all five test methods for Windows subst path lookup']
```

Usage

```
{'test_find_existing_win32_subst_for_path_no_match': 'test find_existing_win32_subst_for_path returns None when no subst mapping matches the given path', 'test_find_existing_win32_subst_for_path_exact_match': 'test find_existing_win32_subst_for_path returns the drive letter when an exact path match exists in the subst mapping', 'test_find_existing_win32_subst_for_path_multiple_matches': 'test find_existing_win32_subst_for_path returns an arbitrary drive letter when multiple mappings match the same path', 'test_find_existing_win32_subst_for_path_case_insensitive': 'test find_existing_win32_subst_for_path performs case-insensitive matching on drive letters and path components', 'run_Win32SubstTest': 'run the Win32SubstTest unittest class to verify all five test methods for Windows subst path lookup'}
```

