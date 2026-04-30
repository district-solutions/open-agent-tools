# Agent Python Tools

- repo: kludex/uvicorn
- repo_uri: https://github.com/kludex/uvicorn

## File: kludex_uvicorn/uvicorn/protocols/http/flow_control.py

Prompts

```
['create a FlowControl instance with an asyncio transport to manage read and write pausing', 'test the FlowControl drain method waits for the writable event before returning', 'refactor the FlowControl pause_reading and resume_reading methods to toggle transport state', 'review the FlowControl class and its pause_writing, resume_writing, and drain methods for correctness', "summarize the service_unavailable ASGI app that sends a 503 response with body 'Service Unavailable'", 'build an HTTP/1.1 server protocol using H11Protocol to handle ASGI requests over asyncio transports', 'create a RequestResponseCycle to manage the full lifecycle of an HTTP request and response in uvicorn', 'test H11Protocol websocket upgrade handling by verifying _should_upgrade and handle_websocket_upgrade methods', 'refactor H11Protocol keep-alive timeout management to support configurable timeout periods', 'review H11Protocol error handling for invalid HTTP requests, connection loss, and 400 response generation', 'build an HTTP protocol using HttpToolsProtocol to handle ASGI requests with httptools parser', 'create a RequestResponseCycle to manage an ASGI HTTP request-response lifecycle', 'test websocket upgrade handling in HttpToolsProtocol when upgrade header is present', 'refactor _get_status_line to generate HTTP status response lines from status codes', 'review the RequestResponseCycle.send method for ASGI message handling and response writing']
```

Usage

```
{'create_FlowControl': 'create a FlowControl instance with an asyncio transport to manage read and write pausing', 'test_FlowControl_drain': 'test the FlowControl drain method waits for the writable event before returning', 'refactor_FlowControl_pause_resume': 'refactor the FlowControl pause_reading and resume_reading methods to toggle transport state', 'review_FlowControl_flow_control': 'review the FlowControl class and its pause_writing, resume_writing, and drain methods for correctness', 'summarize_service_unavailable': "summarize the service_unavailable ASGI app that sends a 503 response with body 'Service Unavailable'"}
```

## File: kludex_uvicorn/uvicorn/protocols/http/h11_impl.py

Prompts

```
['create a FlowControl instance with an asyncio transport to manage read and write pausing', 'test the FlowControl drain method waits for the writable event before returning', 'refactor the FlowControl pause_reading and resume_reading methods to toggle transport state', 'review the FlowControl class and its pause_writing, resume_writing, and drain methods for correctness', "summarize the service_unavailable ASGI app that sends a 503 response with body 'Service Unavailable'", 'build an HTTP/1.1 server protocol using H11Protocol to handle ASGI requests over asyncio transports', 'create a RequestResponseCycle to manage the full lifecycle of an HTTP request and response in uvicorn', 'test H11Protocol websocket upgrade handling by verifying _should_upgrade and handle_websocket_upgrade methods', 'refactor H11Protocol keep-alive timeout management to support configurable timeout periods', 'review H11Protocol error handling for invalid HTTP requests, connection loss, and 400 response generation', 'build an HTTP protocol using HttpToolsProtocol to handle ASGI requests with httptools parser', 'create a RequestResponseCycle to manage an ASGI HTTP request-response lifecycle', 'test websocket upgrade handling in HttpToolsProtocol when upgrade header is present', 'refactor _get_status_line to generate HTTP status response lines from status codes', 'review the RequestResponseCycle.send method for ASGI message handling and response writing']
```

Usage

```
{'build_http_server_protocol': 'build an HTTP/1.1 server protocol using H11Protocol to handle ASGI requests over asyncio transports', 'create_request_response_cycle': 'create a RequestResponseCycle to manage the full lifecycle of an HTTP request and response in uvicorn', 'test_h11_websocket_upgrade': 'test H11Protocol websocket upgrade handling by verifying _should_upgrade and handle_websocket_upgrade methods', 'refactor_h11_keepalive_timeout': 'refactor H11Protocol keep-alive timeout management to support configurable timeout periods', 'review_h11_protocol_error_handling': 'review H11Protocol error handling for invalid HTTP requests, connection loss, and 400 response generation'}
```

## File: kludex_uvicorn/uvicorn/protocols/http/httptools_impl.py

Prompts

```
['create a FlowControl instance with an asyncio transport to manage read and write pausing', 'test the FlowControl drain method waits for the writable event before returning', 'refactor the FlowControl pause_reading and resume_reading methods to toggle transport state', 'review the FlowControl class and its pause_writing, resume_writing, and drain methods for correctness', "summarize the service_unavailable ASGI app that sends a 503 response with body 'Service Unavailable'", 'build an HTTP/1.1 server protocol using H11Protocol to handle ASGI requests over asyncio transports', 'create a RequestResponseCycle to manage the full lifecycle of an HTTP request and response in uvicorn', 'test H11Protocol websocket upgrade handling by verifying _should_upgrade and handle_websocket_upgrade methods', 'refactor H11Protocol keep-alive timeout management to support configurable timeout periods', 'review H11Protocol error handling for invalid HTTP requests, connection loss, and 400 response generation', 'build an HTTP protocol using HttpToolsProtocol to handle ASGI requests with httptools parser', 'create a RequestResponseCycle to manage an ASGI HTTP request-response lifecycle', 'test websocket upgrade handling in HttpToolsProtocol when upgrade header is present', 'refactor _get_status_line to generate HTTP status response lines from status codes', 'review the RequestResponseCycle.send method for ASGI message handling and response writing']
```

Usage

```
{'build_http_protocol': 'build an HTTP protocol using HttpToolsProtocol to handle ASGI requests with httptools parser', 'create_request_cycle': 'create a RequestResponseCycle to manage an ASGI HTTP request-response lifecycle', 'test_websocket_upgrade': 'test websocket upgrade handling in HttpToolsProtocol when upgrade header is present', 'refactor_status_line': 'refactor _get_status_line to generate HTTP status response lines from status codes', 'review_send_method': 'review the RequestResponseCycle.send method for ASGI message handling and response writing'}
```

