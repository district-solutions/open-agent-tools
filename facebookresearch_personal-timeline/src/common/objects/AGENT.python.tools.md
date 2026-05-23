# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/common/objects/EntryTypes.py

Prompts

```
['use the EntryType enum PHOTO member to represent a photo entry type', 'use the EntryType enum TRIP member to represent a trip entry type', 'use the EntryType enum ACTIVITY member to represent an activity entry type', 'call the toJson method on an EntryType enum member to get a JSON string', 'iterate over all EntryType enum members to list available entry types', 'create an LLEntry object with type, startTime, and source to represent a timeline entry', 'call toJson on an LLEntry instance to serialize all its attributes to a JSON string', 'call toDict on an LLEntry to get a dictionary with location addresses resolved as strings', 'create an LLEntrySummary with type, startTime, endTime, locations, text summary, photo summary, stats, and objects', 'use LLEntryInvertedIndex to add entries by key and retrieve them later with getEntries', 'run the python script to derive missing attributes on an LLEntry photo object', 'create a DependencyNode to define an attribute derivation rule with dependencies and a function', 'fill missing attributes on an LLEntry object by resolving dependency chains recursively', 'review the AttributeFiller fillRecursive method to understand circular dependency detection and resolution', 'test the isAbsent method to check if a value is None or an empty string', 'create a DataSource object with id, source_name, entry_type, configs dict, and field_mappings list', 'create a DataSourceList from a list of data source entry dictionaries with required entry_type', 'create a SourceConfigs object with input_directory, filetype enum, filename_regex, filetype_configs, and dedup_key', 'create a FieldMapping object with src, target, src_type, target_type, functions list, and default_value', 'use the FileType enum to specify csv, json, or xml file types for import source configuration']
```

Usage

```
{'use_entrytype_photo': 'use the EntryType enum PHOTO member to represent a photo entry type', 'use_entrytype_trip': 'use the EntryType enum TRIP member to represent a trip entry type', 'use_entrytype_activity': 'use the EntryType enum ACTIVITY member to represent an activity entry type', 'call_entrytype_tojson': 'call the toJson method on an EntryType enum member to get a JSON string', 'iterate_entrytype_members': 'iterate over all EntryType enum members to list available entry types'}
```

## File: facebookresearch_personal-timeline/src/common/objects/LLEntry_obj.py

Prompts

```
['use the EntryType enum PHOTO member to represent a photo entry type', 'use the EntryType enum TRIP member to represent a trip entry type', 'use the EntryType enum ACTIVITY member to represent an activity entry type', 'call the toJson method on an EntryType enum member to get a JSON string', 'iterate over all EntryType enum members to list available entry types', 'create an LLEntry object with type, startTime, and source to represent a timeline entry', 'call toJson on an LLEntry instance to serialize all its attributes to a JSON string', 'call toDict on an LLEntry to get a dictionary with location addresses resolved as strings', 'create an LLEntrySummary with type, startTime, endTime, locations, text summary, photo summary, stats, and objects', 'use LLEntryInvertedIndex to add entries by key and retrieve them later with getEntries', 'run the python script to derive missing attributes on an LLEntry photo object', 'create a DependencyNode to define an attribute derivation rule with dependencies and a function', 'fill missing attributes on an LLEntry object by resolving dependency chains recursively', 'review the AttributeFiller fillRecursive method to understand circular dependency detection and resolution', 'test the isAbsent method to check if a value is None or an empty string', 'create a DataSource object with id, source_name, entry_type, configs dict, and field_mappings list', 'create a DataSourceList from a list of data source entry dictionaries with required entry_type', 'create a SourceConfigs object with input_directory, filetype enum, filename_regex, filetype_configs, and dedup_key', 'create a FieldMapping object with src, target, src_type, target_type, functions list, and default_value', 'use the FileType enum to specify csv, json, or xml file types for import source configuration']
```

Usage

```
{'create_LLEntry': 'create an LLEntry object with type, startTime, and source to represent a timeline entry', 'serialize_LLEntry_to_json': 'call toJson on an LLEntry instance to serialize all its attributes to a JSON string', 'convert_LLEntry_to_dict': 'call toDict on an LLEntry to get a dictionary with location addresses resolved as strings', 'create_LLEntrySummary': 'create an LLEntrySummary with type, startTime, endTime, locations, text summary, photo summary, stats, and objects', 'index_entries_with_LLEntryInvertedIndex': 'use LLEntryInvertedIndex to add entries by key and retrieve them later with getEntries'}
```

## File: facebookresearch_personal-timeline/src/common/objects/derive_attributes.py

Prompts

```
['use the EntryType enum PHOTO member to represent a photo entry type', 'use the EntryType enum TRIP member to represent a trip entry type', 'use the EntryType enum ACTIVITY member to represent an activity entry type', 'call the toJson method on an EntryType enum member to get a JSON string', 'iterate over all EntryType enum members to list available entry types', 'create an LLEntry object with type, startTime, and source to represent a timeline entry', 'call toJson on an LLEntry instance to serialize all its attributes to a JSON string', 'call toDict on an LLEntry to get a dictionary with location addresses resolved as strings', 'create an LLEntrySummary with type, startTime, endTime, locations, text summary, photo summary, stats, and objects', 'use LLEntryInvertedIndex to add entries by key and retrieve them later with getEntries', 'run the python script to derive missing attributes on an LLEntry photo object', 'create a DependencyNode to define an attribute derivation rule with dependencies and a function', 'fill missing attributes on an LLEntry object by resolving dependency chains recursively', 'review the AttributeFiller fillRecursive method to understand circular dependency detection and resolution', 'test the isAbsent method to check if a value is None or an empty string', 'create a DataSource object with id, source_name, entry_type, configs dict, and field_mappings list', 'create a DataSourceList from a list of data source entry dictionaries with required entry_type', 'create a SourceConfigs object with input_directory, filetype enum, filename_regex, filetype_configs, and dedup_key', 'create a FieldMapping object with src, target, src_type, target_type, functions list, and default_value', 'use the FileType enum to specify csv, json, or xml file types for import source configuration']
```

Usage

```
{'run_derive_attributes': 'run the python script to derive missing attributes on an LLEntry photo object', 'create_dependency_node': 'create a DependencyNode to define an attribute derivation rule with dependencies and a function', 'fill_missing_attributes': 'fill missing attributes on an LLEntry object by resolving dependency chains recursively', 'review_fill_recursive': 'review the AttributeFiller fillRecursive method to understand circular dependency detection and resolution', 'test_is_absent': 'test the isAbsent method to check if a value is None or an empty string'}
```

## File: facebookresearch_personal-timeline/src/common/objects/import_configs.py

Prompts

```
['use the EntryType enum PHOTO member to represent a photo entry type', 'use the EntryType enum TRIP member to represent a trip entry type', 'use the EntryType enum ACTIVITY member to represent an activity entry type', 'call the toJson method on an EntryType enum member to get a JSON string', 'iterate over all EntryType enum members to list available entry types', 'create an LLEntry object with type, startTime, and source to represent a timeline entry', 'call toJson on an LLEntry instance to serialize all its attributes to a JSON string', 'call toDict on an LLEntry to get a dictionary with location addresses resolved as strings', 'create an LLEntrySummary with type, startTime, endTime, locations, text summary, photo summary, stats, and objects', 'use LLEntryInvertedIndex to add entries by key and retrieve them later with getEntries', 'run the python script to derive missing attributes on an LLEntry photo object', 'create a DependencyNode to define an attribute derivation rule with dependencies and a function', 'fill missing attributes on an LLEntry object by resolving dependency chains recursively', 'review the AttributeFiller fillRecursive method to understand circular dependency detection and resolution', 'test the isAbsent method to check if a value is None or an empty string', 'create a DataSource object with id, source_name, entry_type, configs dict, and field_mappings list', 'create a DataSourceList from a list of data source entry dictionaries with required entry_type', 'create a SourceConfigs object with input_directory, filetype enum, filename_regex, filetype_configs, and dedup_key', 'create a FieldMapping object with src, target, src_type, target_type, functions list, and default_value', 'use the FileType enum to specify csv, json, or xml file types for import source configuration']
```

Usage

```
{'create_datasource': 'create a DataSource object with id, source_name, entry_type, configs dict, and field_mappings list', 'create_datasourcelist': 'create a DataSourceList from a list of data source entry dictionaries with required entry_type', 'create_sourceconfigs': 'create a SourceConfigs object with input_directory, filetype enum, filename_regex, filetype_configs, and dedup_key', 'create_fieldmapping': 'create a FieldMapping object with src, target, src_type, target_type, functions list, and default_value', 'use_filetype_enum': 'use the FileType enum to specify csv, json, or xml file types for import source configuration'}
```

