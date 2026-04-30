# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/integrations/cloudzero/cz_resource_names.py

Prompts

```
['create a CloudZero Resource Name from LiteLLM daily spend data dictionary', 'create a CloudZero Resource Name from individual service, provider, region, account, resource type, and cloud local ID components', 'test whether a CloudZero Resource Name string is valid against the standard format', 'extract all six components from a CloudZero Resource Name string', 'normalize a provider name to standard CloudZero Resource Name format', 'create a CloudZeroStreamer instance with api_key, connection_id, and optional user_timezone for streaming CBF data', 'send a polars DataFrame of CBF data in daily batches to the CloudZero AnyCost API', 'group a polars DataFrame of CBF data by date, converting timestamps to UTC', 'parse an ISO 8601 timestamp string and convert it to UTC datetime', 'convert a CBF row dictionary to CloudZero API format with numeric values as strings', 'transform a polars DataFrame of LiteLLM usage data into CloudZero CBF format', 'create a single CBF record from a LiteLLM daily spend row dictionary', 'parse a date string from daily spend tables into a UTC datetime object', 'filter out records with zero successful_requests from LiteLLM usage data', 'generate a CloudZero Resource Name as resource_id from LiteLLM data row']
```

Usage

```
{'create_czrn_from_litellm_data': 'create a CloudZero Resource Name from LiteLLM daily spend data dictionary', 'create_czrn_from_components': 'create a CloudZero Resource Name from individual service, provider, region, account, resource type, and cloud local ID components', 'test_czrn_is_valid': 'test whether a CloudZero Resource Name string is valid against the standard format', 'extract_czrn_components': 'extract all six components from a CloudZero Resource Name string', 'normalize_czrn_provider': 'normalize a provider name to standard CloudZero Resource Name format'}
```

## File: berriai_litellm/litellm/integrations/cloudzero/cz_stream_api.py

Prompts

```
['create a CloudZero Resource Name from LiteLLM daily spend data dictionary', 'create a CloudZero Resource Name from individual service, provider, region, account, resource type, and cloud local ID components', 'test whether a CloudZero Resource Name string is valid against the standard format', 'extract all six components from a CloudZero Resource Name string', 'normalize a provider name to standard CloudZero Resource Name format', 'create a CloudZeroStreamer instance with api_key, connection_id, and optional user_timezone for streaming CBF data', 'send a polars DataFrame of CBF data in daily batches to the CloudZero AnyCost API', 'group a polars DataFrame of CBF data by date, converting timestamps to UTC', 'parse an ISO 8601 timestamp string and convert it to UTC datetime', 'convert a CBF row dictionary to CloudZero API format with numeric values as strings', 'transform a polars DataFrame of LiteLLM usage data into CloudZero CBF format', 'create a single CBF record from a LiteLLM daily spend row dictionary', 'parse a date string from daily spend tables into a UTC datetime object', 'filter out records with zero successful_requests from LiteLLM usage data', 'generate a CloudZero Resource Name as resource_id from LiteLLM data row']
```

Usage

```
{'create_cloudzero_streamer': 'create a CloudZeroStreamer instance with api_key, connection_id, and optional user_timezone for streaming CBF data', 'send_batched_cbf_data': 'send a polars DataFrame of CBF data in daily batches to the CloudZero AnyCost API', 'group_by_date_cbf': 'group a polars DataFrame of CBF data by date, converting timestamps to UTC', 'parse_convert_timestamp': 'parse an ISO 8601 timestamp string and convert it to UTC datetime', 'convert_cbf_to_api_format': 'convert a CBF row dictionary to CloudZero API format with numeric values as strings'}
```

## File: berriai_litellm/litellm/integrations/cloudzero/transform.py

Prompts

```
['create a CloudZero Resource Name from LiteLLM daily spend data dictionary', 'create a CloudZero Resource Name from individual service, provider, region, account, resource type, and cloud local ID components', 'test whether a CloudZero Resource Name string is valid against the standard format', 'extract all six components from a CloudZero Resource Name string', 'normalize a provider name to standard CloudZero Resource Name format', 'create a CloudZeroStreamer instance with api_key, connection_id, and optional user_timezone for streaming CBF data', 'send a polars DataFrame of CBF data in daily batches to the CloudZero AnyCost API', 'group a polars DataFrame of CBF data by date, converting timestamps to UTC', 'parse an ISO 8601 timestamp string and convert it to UTC datetime', 'convert a CBF row dictionary to CloudZero API format with numeric values as strings', 'transform a polars DataFrame of LiteLLM usage data into CloudZero CBF format', 'create a single CBF record from a LiteLLM daily spend row dictionary', 'parse a date string from daily spend tables into a UTC datetime object', 'filter out records with zero successful_requests from LiteLLM usage data', 'generate a CloudZero Resource Name as resource_id from LiteLLM data row']
```

Usage

```
{'transform_litellm_data_to_cbf': 'transform a polars DataFrame of LiteLLM usage data into CloudZero CBF format', 'create_cbf_record_from_row': 'create a single CBF record from a LiteLLM daily spend row dictionary', 'parse_date_string': 'parse a date string from daily spend tables into a UTC datetime object', 'filter_zero_request_records': 'filter out records with zero successful_requests from LiteLLM usage data', 'generate_czrn_resource_id': 'generate a CloudZero Resource Name as resource_id from LiteLLM data row'}
```

