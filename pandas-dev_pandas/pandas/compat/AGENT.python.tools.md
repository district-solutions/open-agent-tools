# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/compat/_optional.py

Prompts

```
['test the import_optional_dependency function to import a module with a minimum version check', 'build a call to import_optional_dependency with errors=ignore to gracefully handle missing optional dependencies', 'review the get_version function that extracts and sanitizes the __version__ attribute from a module', 'summarize the import_optional_dependency function and its errors modes: raise, warn, and ignore', 'review the VERSIONS and INSTALL_MAPPING dictionaries that define minimum versions and PyPI name mappings', 'test the Unpickler class find_class method to remap deprecated pandas class locations during unpickling', 'run the loads function to unpickle pandas objects with backward compatibility for pandas <= 1.3.5', 'create a context manager that temporarily patches pickle.loads with the pandas compatibility unpickler', 'review the _class_locations_map dictionary that maps deprecated pandas class paths to their new locations', 'test the load_reduce method to handle BaseOffset and PeriodArray unpickling with __new__ fallback', 'test the HAS_PYARROW constant to check if pyarrow meets the minimum version requirement', 'test the pa_version_under14p0 flag to determine if the installed pyarrow version is below 14.0.0', 'test the pa_version_under22p0 flag to determine if the installed pyarrow version is below 22.0.0', 'run _safe_fill_null to safely fill null values in a pyarrow array with a fallback for Windows + pyarrow 21', 'review _safe_fill_null for handling duration types and chunked arrays with a Windows pyarrow 21 bug workaround']
```

Usage

```
{'test_import_optional_dependency': 'test the import_optional_dependency function to import a module with a minimum version check', 'build_import_optional_dependency': 'build a call to import_optional_dependency with errors=ignore to gracefully handle missing optional dependencies', 'review_get_version': 'review the get_version function that extracts and sanitizes the __version__ attribute from a module', 'summarize_import_optional_dependency': 'summarize the import_optional_dependency function and its errors modes: raise, warn, and ignore', 'review_version_mapping': 'review the VERSIONS and INSTALL_MAPPING dictionaries that define minimum versions and PyPI name mappings'}
```

## File: pandas-dev_pandas/pandas/compat/pickle_compat.py

Prompts

```
['test the import_optional_dependency function to import a module with a minimum version check', 'build a call to import_optional_dependency with errors=ignore to gracefully handle missing optional dependencies', 'review the get_version function that extracts and sanitizes the __version__ attribute from a module', 'summarize the import_optional_dependency function and its errors modes: raise, warn, and ignore', 'review the VERSIONS and INSTALL_MAPPING dictionaries that define minimum versions and PyPI name mappings', 'test the Unpickler class find_class method to remap deprecated pandas class locations during unpickling', 'run the loads function to unpickle pandas objects with backward compatibility for pandas <= 1.3.5', 'create a context manager that temporarily patches pickle.loads with the pandas compatibility unpickler', 'review the _class_locations_map dictionary that maps deprecated pandas class paths to their new locations', 'test the load_reduce method to handle BaseOffset and PeriodArray unpickling with __new__ fallback', 'test the HAS_PYARROW constant to check if pyarrow meets the minimum version requirement', 'test the pa_version_under14p0 flag to determine if the installed pyarrow version is below 14.0.0', 'test the pa_version_under22p0 flag to determine if the installed pyarrow version is below 22.0.0', 'run _safe_fill_null to safely fill null values in a pyarrow array with a fallback for Windows + pyarrow 21', 'review _safe_fill_null for handling duration types and chunked arrays with a Windows pyarrow 21 bug workaround']
```

Usage

```
{'test_unpickler_find_class': 'test the Unpickler class find_class method to remap deprecated pandas class locations during unpickling', 'run_pickle_compat_loads': 'run the loads function to unpickle pandas objects with backward compatibility for pandas <= 1.3.5', 'create_patch_pickle_context': 'create a context manager that temporarily patches pickle.loads with the pandas compatibility unpickler', 'review_class_locations_map': 'review the _class_locations_map dictionary that maps deprecated pandas class paths to their new locations', 'test_load_reduce_compat': 'test the load_reduce method to handle BaseOffset and PeriodArray unpickling with __new__ fallback'}
```

## File: pandas-dev_pandas/pandas/compat/pyarrow.py

Prompts

```
['test the import_optional_dependency function to import a module with a minimum version check', 'build a call to import_optional_dependency with errors=ignore to gracefully handle missing optional dependencies', 'review the get_version function that extracts and sanitizes the __version__ attribute from a module', 'summarize the import_optional_dependency function and its errors modes: raise, warn, and ignore', 'review the VERSIONS and INSTALL_MAPPING dictionaries that define minimum versions and PyPI name mappings', 'test the Unpickler class find_class method to remap deprecated pandas class locations during unpickling', 'run the loads function to unpickle pandas objects with backward compatibility for pandas <= 1.3.5', 'create a context manager that temporarily patches pickle.loads with the pandas compatibility unpickler', 'review the _class_locations_map dictionary that maps deprecated pandas class paths to their new locations', 'test the load_reduce method to handle BaseOffset and PeriodArray unpickling with __new__ fallback', 'test the HAS_PYARROW constant to check if pyarrow meets the minimum version requirement', 'test the pa_version_under14p0 flag to determine if the installed pyarrow version is below 14.0.0', 'test the pa_version_under22p0 flag to determine if the installed pyarrow version is below 22.0.0', 'run _safe_fill_null to safely fill null values in a pyarrow array with a fallback for Windows + pyarrow 21', 'review _safe_fill_null for handling duration types and chunked arrays with a Windows pyarrow 21 bug workaround']
```

Usage

```
{'test_HAS_PYARROW': 'test the HAS_PYARROW constant to check if pyarrow meets the minimum version requirement', 'test_pa_version_under14p0': 'test the pa_version_under14p0 flag to determine if the installed pyarrow version is below 14.0.0', 'test_pa_version_under22p0': 'test the pa_version_under22p0 flag to determine if the installed pyarrow version is below 22.0.0', 'run__safe_fill_null': 'run _safe_fill_null to safely fill null values in a pyarrow array with a fallback for Windows + pyarrow 21', 'review__safe_fill_null': 'review _safe_fill_null for handling duration types and chunked arrays with a Windows pyarrow 21 bug workaround'}
```

