# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/data_handler/exporter_test.py

Prompts

```
['test JsonScenarioExporter.convert_action_args to serialize dict, list, int, string, and non-serializable object arguments into ExportedActionArg', 'test JsonScenarioExporter.convert_action to use resolved_args when available and fall back to original args', 'test JsonScenarioExporter.export_to_json to export a scenario with events and config metadata to a JSON string', 'test JsonScenarioExporter.export_to_json_file to write a scenario trace to a JSON file with config hash in the filename', 'test JsonScenarioImporter.import_from_json to import a JSON trace back into a scenario and verify roundtrip data integrity', 'test JsonScenarioExporter exports scenario to JSON without apps when export_apps is False and HF metadata exists', 'test JsonScenarioExporter exports scenario to JSON with apps included when export_apps is True', 'test JsonScenarioExporter logs a warning when export_apps is False but no HuggingFace metadata is present', 'test JsonScenarioImporter fetches apps from HuggingFace dataset when importing a scenario with HF metadata but no apps', 'test JsonScenarioImporter raises ValueError when HuggingFace dataset fails to load during import', 'import a JSON trace string into a ScenarioImportedFromJson with completed events and world logs', 'import a JSON trace string into a BenchmarkScenarioImportedFromJson for benchmark evaluation', 'map raw action data with typed args to a normalized action dict using app name to class mapping', 'map raw event JSON with optional metadata and action into a normalized event dict', 'map raw event metadata dict containing exception, stack trace, and return value fields']
```

Usage

```
{'convert_action_args': 'test JsonScenarioExporter.convert_action_args to serialize dict, list, int, string, and non-serializable object arguments into ExportedActionArg', 'convert_action': 'test JsonScenarioExporter.convert_action to use resolved_args when available and fall back to original args', 'export_to_json': 'test JsonScenarioExporter.export_to_json to export a scenario with events and config metadata to a JSON string', 'export_to_json_file': 'test JsonScenarioExporter.export_to_json_file to write a scenario trace to a JSON file with config hash in the filename', 'import_from_json': 'test JsonScenarioImporter.import_from_json to import a JSON trace back into a scenario and verify roundtrip data integrity'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/data_handler/hf_metadata_test.py

Prompts

```
['test JsonScenarioExporter.convert_action_args to serialize dict, list, int, string, and non-serializable object arguments into ExportedActionArg', 'test JsonScenarioExporter.convert_action to use resolved_args when available and fall back to original args', 'test JsonScenarioExporter.export_to_json to export a scenario with events and config metadata to a JSON string', 'test JsonScenarioExporter.export_to_json_file to write a scenario trace to a JSON file with config hash in the filename', 'test JsonScenarioImporter.import_from_json to import a JSON trace back into a scenario and verify roundtrip data integrity', 'test JsonScenarioExporter exports scenario to JSON without apps when export_apps is False and HF metadata exists', 'test JsonScenarioExporter exports scenario to JSON with apps included when export_apps is True', 'test JsonScenarioExporter logs a warning when export_apps is False but no HuggingFace metadata is present', 'test JsonScenarioImporter fetches apps from HuggingFace dataset when importing a scenario with HF metadata but no apps', 'test JsonScenarioImporter raises ValueError when HuggingFace dataset fails to load during import', 'import a JSON trace string into a ScenarioImportedFromJson with completed events and world logs', 'import a JSON trace string into a BenchmarkScenarioImportedFromJson for benchmark evaluation', 'map raw action data with typed args to a normalized action dict using app name to class mapping', 'map raw event JSON with optional metadata and action into a normalized event dict', 'map raw event metadata dict containing exception, stack trace, and return value fields']
```

Usage

```
{'test_export_with_hf_metadata_no_apps': 'test JsonScenarioExporter exports scenario to JSON without apps when export_apps is False and HF metadata exists', 'test_export_with_hf_metadata_with_apps': 'test JsonScenarioExporter exports scenario to JSON with apps included when export_apps is True', 'test_export_without_hf_metadata_warning': 'test JsonScenarioExporter logs a warning when export_apps is False but no HuggingFace metadata is present', 'test_import_with_hf_metadata_no_apps': 'test JsonScenarioImporter fetches apps from HuggingFace dataset when importing a scenario with HF metadata but no apps', 'test_import_with_hf_metadata_no_apps_failure': 'test JsonScenarioImporter raises ValueError when HuggingFace dataset fails to load during import'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/data_handler/importer_test.py

Prompts

```
['test JsonScenarioExporter.convert_action_args to serialize dict, list, int, string, and non-serializable object arguments into ExportedActionArg', 'test JsonScenarioExporter.convert_action to use resolved_args when available and fall back to original args', 'test JsonScenarioExporter.export_to_json to export a scenario with events and config metadata to a JSON string', 'test JsonScenarioExporter.export_to_json_file to write a scenario trace to a JSON file with config hash in the filename', 'test JsonScenarioImporter.import_from_json to import a JSON trace back into a scenario and verify roundtrip data integrity', 'test JsonScenarioExporter exports scenario to JSON without apps when export_apps is False and HF metadata exists', 'test JsonScenarioExporter exports scenario to JSON with apps included when export_apps is True', 'test JsonScenarioExporter logs a warning when export_apps is False but no HuggingFace metadata is present', 'test JsonScenarioImporter fetches apps from HuggingFace dataset when importing a scenario with HF metadata but no apps', 'test JsonScenarioImporter raises ValueError when HuggingFace dataset fails to load during import', 'import a JSON trace string into a ScenarioImportedFromJson with completed events and world logs', 'import a JSON trace string into a BenchmarkScenarioImportedFromJson for benchmark evaluation', 'map raw action data with typed args to a normalized action dict using app name to class mapping', 'map raw event JSON with optional metadata and action into a normalized event dict', 'map raw event metadata dict containing exception, stack trace, and return value fields']
```

Usage

```
{'import_json_scenario': 'import a JSON trace string into a ScenarioImportedFromJson with completed events and world logs', 'import_json_to_benchmark': 'import a JSON trace string into a BenchmarkScenarioImportedFromJson for benchmark evaluation', 'map_action': 'map raw action data with typed args to a normalized action dict using app name to class mapping', 'map_event': 'map raw event JSON with optional metadata and action into a normalized event dict', 'map_event_metadata': 'map raw event metadata dict containing exception, stack trace, and return value fields'}
```

