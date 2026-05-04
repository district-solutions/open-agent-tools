# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/utils/telemetry/instrumentors.py

Prompts

```
['instrument a FastAPI app with OpenTelemetry tracing using the Instrumentor class', 'instrument Redis operations with OpenTelemetry spans using the redis_request_hook callback', 'instrument SQLAlchemy database engine queries with OpenTelemetry tracing', 'instrument HTTPX async and sync HTTP client requests with OpenTelemetry request and response hooks', 'instrument aiohttp HTTP client traces with OpenTelemetry spans for request start, end, and exception events', 'setup the OpenTelemetry logging handler with OTLP exporter configuration and basic auth headers', 'build a MeterProvider that sends OpenTelemetry metrics to an OTLP collector via gRPC or HTTP', 'setup OTel metrics middleware on a FastAPI app to track HTTP request counters and durations', 'create a counter instrument to track total HTTP server requests with method, route, and status code attributes', 'create a histogram instrument to measure HTTP request duration in milliseconds', 'create observable gauges to report total registered users, active users, and users active today', 'setup OpenTelemetry tracing and metrics for a FastAPI app with a SQLAlchemy engine', 'instrument a FastAPI app and database engine with OpenTelemetry using the Instrumentor class', 'setup OpenTelemetry metrics for a FastAPI app with a given resource configuration', 'create an OTLP gRPC span exporter for sending OpenTelemetry traces to a collector endpoint', 'create an OTLP HTTP span exporter with basic auth headers for sending OpenTelemetry traces']
```

Usage

```
{'instrument_fastapi_telemetry': 'instrument a FastAPI app with OpenTelemetry tracing using the Instrumentor class', 'instrument_redis_requests': 'instrument Redis operations with OpenTelemetry spans using the redis_request_hook callback', 'instrument_sqlalchemy_queries': 'instrument SQLAlchemy database engine queries with OpenTelemetry tracing', 'instrument_httpx_client': 'instrument HTTPX async and sync HTTP client requests with OpenTelemetry request and response hooks', 'instrument_aiohttp_client': 'instrument aiohttp HTTP client traces with OpenTelemetry spans for request start, end, and exception events'}
```

## File: open-webui_open-webui/backend/open_webui/utils/telemetry/logs.py

Prompts

```
['instrument a FastAPI app with OpenTelemetry tracing using the Instrumentor class', 'instrument Redis operations with OpenTelemetry spans using the redis_request_hook callback', 'instrument SQLAlchemy database engine queries with OpenTelemetry tracing', 'instrument HTTPX async and sync HTTP client requests with OpenTelemetry request and response hooks', 'instrument aiohttp HTTP client traces with OpenTelemetry spans for request start, end, and exception events', 'setup the OpenTelemetry logging handler with OTLP exporter configuration and basic auth headers', 'build a MeterProvider that sends OpenTelemetry metrics to an OTLP collector via gRPC or HTTP', 'setup OTel metrics middleware on a FastAPI app to track HTTP request counters and durations', 'create a counter instrument to track total HTTP server requests with method, route, and status code attributes', 'create a histogram instrument to measure HTTP request duration in milliseconds', 'create observable gauges to report total registered users, active users, and users active today', 'setup OpenTelemetry tracing and metrics for a FastAPI app with a SQLAlchemy engine', 'instrument a FastAPI app and database engine with OpenTelemetry using the Instrumentor class', 'setup OpenTelemetry metrics for a FastAPI app with a given resource configuration', 'create an OTLP gRPC span exporter for sending OpenTelemetry traces to a collector endpoint', 'create an OTLP HTTP span exporter with basic auth headers for sending OpenTelemetry traces']
```

Usage

```
{'setup_logging': 'setup the OpenTelemetry logging handler with OTLP exporter configuration and basic auth headers'}
```

## File: open-webui_open-webui/backend/open_webui/utils/telemetry/metrics.py

Prompts

```
['instrument a FastAPI app with OpenTelemetry tracing using the Instrumentor class', 'instrument Redis operations with OpenTelemetry spans using the redis_request_hook callback', 'instrument SQLAlchemy database engine queries with OpenTelemetry tracing', 'instrument HTTPX async and sync HTTP client requests with OpenTelemetry request and response hooks', 'instrument aiohttp HTTP client traces with OpenTelemetry spans for request start, end, and exception events', 'setup the OpenTelemetry logging handler with OTLP exporter configuration and basic auth headers', 'build a MeterProvider that sends OpenTelemetry metrics to an OTLP collector via gRPC or HTTP', 'setup OTel metrics middleware on a FastAPI app to track HTTP request counters and durations', 'create a counter instrument to track total HTTP server requests with method, route, and status code attributes', 'create a histogram instrument to measure HTTP request duration in milliseconds', 'create observable gauges to report total registered users, active users, and users active today', 'setup OpenTelemetry tracing and metrics for a FastAPI app with a SQLAlchemy engine', 'instrument a FastAPI app and database engine with OpenTelemetry using the Instrumentor class', 'setup OpenTelemetry metrics for a FastAPI app with a given resource configuration', 'create an OTLP gRPC span exporter for sending OpenTelemetry traces to a collector endpoint', 'create an OTLP HTTP span exporter with basic auth headers for sending OpenTelemetry traces']
```

Usage

```
{'build_meter_provider': 'build a MeterProvider that sends OpenTelemetry metrics to an OTLP collector via gRPC or HTTP', 'setup_metrics': 'setup OTel metrics middleware on a FastAPI app to track HTTP request counters and durations', 'create_http_request_counter': 'create a counter instrument to track total HTTP server requests with method, route, and status code attributes', 'create_duration_histogram': 'create a histogram instrument to measure HTTP request duration in milliseconds', 'create_user_gauges': 'create observable gauges to report total registered users, active users, and users active today'}
```

## File: open-webui_open-webui/backend/open_webui/utils/telemetry/setup.py

Prompts

```
['instrument a FastAPI app with OpenTelemetry tracing using the Instrumentor class', 'instrument Redis operations with OpenTelemetry spans using the redis_request_hook callback', 'instrument SQLAlchemy database engine queries with OpenTelemetry tracing', 'instrument HTTPX async and sync HTTP client requests with OpenTelemetry request and response hooks', 'instrument aiohttp HTTP client traces with OpenTelemetry spans for request start, end, and exception events', 'setup the OpenTelemetry logging handler with OTLP exporter configuration and basic auth headers', 'build a MeterProvider that sends OpenTelemetry metrics to an OTLP collector via gRPC or HTTP', 'setup OTel metrics middleware on a FastAPI app to track HTTP request counters and durations', 'create a counter instrument to track total HTTP server requests with method, route, and status code attributes', 'create a histogram instrument to measure HTTP request duration in milliseconds', 'create observable gauges to report total registered users, active users, and users active today', 'setup OpenTelemetry tracing and metrics for a FastAPI app with a SQLAlchemy engine', 'instrument a FastAPI app and database engine with OpenTelemetry using the Instrumentor class', 'setup OpenTelemetry metrics for a FastAPI app with a given resource configuration', 'create an OTLP gRPC span exporter for sending OpenTelemetry traces to a collector endpoint', 'create an OTLP HTTP span exporter with basic auth headers for sending OpenTelemetry traces']
```

Usage

```
{'setup_open_webui_telemetry': 'setup OpenTelemetry tracing and metrics for a FastAPI app with a SQLAlchemy engine', 'instrument_open_webui_app': 'instrument a FastAPI app and database engine with OpenTelemetry using the Instrumentor class', 'setup_open_webui_metrics': 'setup OpenTelemetry metrics for a FastAPI app with a given resource configuration', 'create_otlp_grpc_exporter': 'create an OTLP gRPC span exporter for sending OpenTelemetry traces to a collector endpoint', 'create_otlp_http_exporter': 'create an OTLP HTTP span exporter with basic auth headers for sending OpenTelemetry traces'}
```

