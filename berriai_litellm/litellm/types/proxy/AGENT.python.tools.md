# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/types/proxy/control_plane_endpoints.py

Prompts

```
['create a WorkerRegistryEntry with worker_id, name, and url fields', 'build a WorkerRegistryEntry instance from a dictionary of worker_id, name, and url', 'test the url_must_be_http validator rejects URLs without http:// or https://', 'review the WorkerRegistryEntry Pydantic model and its url field validator', 'summarize the WorkerRegistryEntry model fields and validation rules', 'review the RedactedDict class that prevents secrets from leaking in logs via redacted str/repr', 'create a RedactedDict instance that suppresses sensitive data in log output', 'test the RedactedDict.copy() method returns a new RedactedDict with copied contents', 'review the SecretFields TypedDict that defines internal secret fields not logged', 'create a SecretFields TypedDict annotation for dict keys like raw_headers', 'create a VantageInitRequest with an API key, integration token, and optional base URL', 'create a VantageExportRequest with optional limit, start time, and end time for data export', 'create a VantageDryRunRequest with an optional record limit for previewing export data', 'create a VantageSettingsUpdate with optional API key, integration token, and base URL fields', 'build a VantageSettingsView response model with masked credentials and configuration status']
```

Usage

```
{'create_WorkerRegistryEntry': 'create a WorkerRegistryEntry with worker_id, name, and url fields', 'build_WorkerRegistryEntry': 'build a WorkerRegistryEntry instance from a dictionary of worker_id, name, and url', 'test_url_must_be_http': 'test the url_must_be_http validator rejects URLs without http:// or https://', 'review_WorkerRegistryEntry': 'review the WorkerRegistryEntry Pydantic model and its url field validator', 'summarize_WorkerRegistryEntry': 'summarize the WorkerRegistryEntry model fields and validation rules'}
```

## File: berriai_litellm/litellm/types/proxy/litellm_pre_call_utils.py

Prompts

```
['create a WorkerRegistryEntry with worker_id, name, and url fields', 'build a WorkerRegistryEntry instance from a dictionary of worker_id, name, and url', 'test the url_must_be_http validator rejects URLs without http:// or https://', 'review the WorkerRegistryEntry Pydantic model and its url field validator', 'summarize the WorkerRegistryEntry model fields and validation rules', 'review the RedactedDict class that prevents secrets from leaking in logs via redacted str/repr', 'create a RedactedDict instance that suppresses sensitive data in log output', 'test the RedactedDict.copy() method returns a new RedactedDict with copied contents', 'review the SecretFields TypedDict that defines internal secret fields not logged', 'create a SecretFields TypedDict annotation for dict keys like raw_headers', 'create a VantageInitRequest with an API key, integration token, and optional base URL', 'create a VantageExportRequest with optional limit, start time, and end time for data export', 'create a VantageDryRunRequest with an optional record limit for previewing export data', 'create a VantageSettingsUpdate with optional API key, integration token, and base URL fields', 'build a VantageSettingsView response model with masked credentials and configuration status']
```

Usage

```
{'review_RedactedDict': 'review the RedactedDict class that prevents secrets from leaking in logs via redacted str/repr', 'create_RedactedDict': 'create a RedactedDict instance that suppresses sensitive data in log output', 'test_RedactedDict_copy': 'test the RedactedDict.copy() method returns a new RedactedDict with copied contents', 'review_SecretFields': 'review the SecretFields TypedDict that defines internal secret fields not logged', 'create_SecretFields': 'create a SecretFields TypedDict annotation for dict keys like raw_headers'}
```

## File: berriai_litellm/litellm/types/proxy/vantage_endpoints.py

Prompts

```
['create a WorkerRegistryEntry with worker_id, name, and url fields', 'build a WorkerRegistryEntry instance from a dictionary of worker_id, name, and url', 'test the url_must_be_http validator rejects URLs without http:// or https://', 'review the WorkerRegistryEntry Pydantic model and its url field validator', 'summarize the WorkerRegistryEntry model fields and validation rules', 'review the RedactedDict class that prevents secrets from leaking in logs via redacted str/repr', 'create a RedactedDict instance that suppresses sensitive data in log output', 'test the RedactedDict.copy() method returns a new RedactedDict with copied contents', 'review the SecretFields TypedDict that defines internal secret fields not logged', 'create a SecretFields TypedDict annotation for dict keys like raw_headers', 'create a VantageInitRequest with an API key, integration token, and optional base URL', 'create a VantageExportRequest with optional limit, start time, and end time for data export', 'create a VantageDryRunRequest with an optional record limit for previewing export data', 'create a VantageSettingsUpdate with optional API key, integration token, and base URL fields', 'build a VantageSettingsView response model with masked credentials and configuration status']
```

Usage

```
{'create_vantage_init_request': 'create a VantageInitRequest with an API key, integration token, and optional base URL', 'create_vantage_export_request': 'create a VantageExportRequest with optional limit, start time, and end time for data export', 'create_vantage_dry_run_request': 'create a VantageDryRunRequest with an optional record limit for previewing export data', 'create_vantage_settings_update': 'create a VantageSettingsUpdate with optional API key, integration token, and base URL fields', 'build_vantage_settings_view': 'build a VantageSettingsView response model with masked credentials and configuration status'}
```

