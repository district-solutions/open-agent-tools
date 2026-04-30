# Agent Python Tools

- repo: kludex/uvicorn
- repo_uri: https://github.com/kludex/uvicorn

## File: kludex_uvicorn/uvicorn/middleware/message_logger.py

Prompts

```
['create an ASGI message with body-type content replaced by placeholders to avoid logging sensitive data', 'test the message_with_placeholders function with body, bytes, text, and headers attributes', 'review the message_with_placeholders function that sanitizes ASGI messages for logging', 'create a MessageLoggerMiddleware wrapping an ASGI app to log receive, send, started, and completed events', 'summarize the MessageLoggerMiddleware class that instruments ASGI receive/send with trace-level logging', 'create a ProxyHeadersMiddleware instance to handle X-Forwarded-Proto and X-Forwarded-For headers from trusted proxies', 'configure _TrustedHosts with a list of trusted IP addresses, CIDR networks, or wildcard to enable proxy header processing', 'parse a forwarded host value string into a tuple of host and port supporting IPv4, IPv6, and bracketed IPv6 formats', 'check if a client host string is in the trusted hosts set using IP address, CIDR network, or literal matching', 'extract the trusted client address from an X-Forwarded-For header by finding the first untrusted host in the forwarded list', 'build a WSGI environ dict from an ASGI HTTP scope, request message, and body stream', 'create a WSGI middleware that wraps a WSGI app for use in an ASGI server', 'create a WSGI responder that bridges ASGI requests to a WSGI application via thread pool', 'run a WSGI application in a thread pool executor and stream response chunks back over ASGI', 'review the WSGI middleware for deprecated native uvicorn implementation and a2wsgi migration']
```

Usage

```
{'create_message_with_placeholders': 'create an ASGI message with body-type content replaced by placeholders to avoid logging sensitive data', 'test_message_with_placeholders': 'test the message_with_placeholders function with body, bytes, text, and headers attributes', 'review_message_with_placeholders': 'review the message_with_placeholders function that sanitizes ASGI messages for logging', 'create_message_logger_middleware': 'create a MessageLoggerMiddleware wrapping an ASGI app to log receive, send, started, and completed events', 'summarize_message_logger_middleware': 'summarize the MessageLoggerMiddleware class that instruments ASGI receive/send with trace-level logging'}
```

## File: kludex_uvicorn/uvicorn/middleware/proxy_headers.py

Prompts

```
['create an ASGI message with body-type content replaced by placeholders to avoid logging sensitive data', 'test the message_with_placeholders function with body, bytes, text, and headers attributes', 'review the message_with_placeholders function that sanitizes ASGI messages for logging', 'create a MessageLoggerMiddleware wrapping an ASGI app to log receive, send, started, and completed events', 'summarize the MessageLoggerMiddleware class that instruments ASGI receive/send with trace-level logging', 'create a ProxyHeadersMiddleware instance to handle X-Forwarded-Proto and X-Forwarded-For headers from trusted proxies', 'configure _TrustedHosts with a list of trusted IP addresses, CIDR networks, or wildcard to enable proxy header processing', 'parse a forwarded host value string into a tuple of host and port supporting IPv4, IPv6, and bracketed IPv6 formats', 'check if a client host string is in the trusted hosts set using IP address, CIDR network, or literal matching', 'extract the trusted client address from an X-Forwarded-For header by finding the first untrusted host in the forwarded list', 'build a WSGI environ dict from an ASGI HTTP scope, request message, and body stream', 'create a WSGI middleware that wraps a WSGI app for use in an ASGI server', 'create a WSGI responder that bridges ASGI requests to a WSGI application via thread pool', 'run a WSGI application in a thread pool executor and stream response chunks back over ASGI', 'review the WSGI middleware for deprecated native uvicorn implementation and a2wsgi migration']
```

Usage

```
{'create_ProxyHeadersMiddleware': 'create a ProxyHeadersMiddleware instance to handle X-Forwarded-Proto and X-Forwarded-For headers from trusted proxies', 'configure_trusted_hosts': 'configure _TrustedHosts with a list of trusted IP addresses, CIDR networks, or wildcard to enable proxy header processing', 'parse_host_port': 'parse a forwarded host value string into a tuple of host and port supporting IPv4, IPv6, and bracketed IPv6 formats', 'check_trusted_host': 'check if a client host string is in the trusted hosts set using IP address, CIDR network, or literal matching', 'extract_client_address': 'extract the trusted client address from an X-Forwarded-For header by finding the first untrusted host in the forwarded list'}
```

## File: kludex_uvicorn/uvicorn/middleware/wsgi.py

Prompts

```
['create an ASGI message with body-type content replaced by placeholders to avoid logging sensitive data', 'test the message_with_placeholders function with body, bytes, text, and headers attributes', 'review the message_with_placeholders function that sanitizes ASGI messages for logging', 'create a MessageLoggerMiddleware wrapping an ASGI app to log receive, send, started, and completed events', 'summarize the MessageLoggerMiddleware class that instruments ASGI receive/send with trace-level logging', 'create a ProxyHeadersMiddleware instance to handle X-Forwarded-Proto and X-Forwarded-For headers from trusted proxies', 'configure _TrustedHosts with a list of trusted IP addresses, CIDR networks, or wildcard to enable proxy header processing', 'parse a forwarded host value string into a tuple of host and port supporting IPv4, IPv6, and bracketed IPv6 formats', 'check if a client host string is in the trusted hosts set using IP address, CIDR network, or literal matching', 'extract the trusted client address from an X-Forwarded-For header by finding the first untrusted host in the forwarded list', 'build a WSGI environ dict from an ASGI HTTP scope, request message, and body stream', 'create a WSGI middleware that wraps a WSGI app for use in an ASGI server', 'create a WSGI responder that bridges ASGI requests to a WSGI application via thread pool', 'run a WSGI application in a thread pool executor and stream response chunks back over ASGI', 'review the WSGI middleware for deprecated native uvicorn implementation and a2wsgi migration']
```

Usage

```
{'build_environ': 'build a WSGI environ dict from an ASGI HTTP scope, request message, and body stream', 'create_wsgi_middleware': 'create a WSGI middleware that wraps a WSGI app for use in an ASGI server', 'create_wsgi_responder': 'create a WSGI responder that bridges ASGI requests to a WSGI application via thread pool', 'run_wsgi_app': 'run a WSGI application in a thread pool executor and stream response chunks back over ASGI', 'review_wsgi_middleware': 'review the WSGI middleware for deprecated native uvicorn implementation and a2wsgi migration'}
```

