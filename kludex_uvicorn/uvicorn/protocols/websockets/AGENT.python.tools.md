# Agent Python Tools

- repo: kludex/uvicorn
- repo_uri: https://github.com/kludex/uvicorn

## File: kludex_uvicorn/uvicorn/protocols/websockets/websockets_impl.py

Prompts

```
['build a uvicorn websocket server using WebSocketProtocol with ASGI app and server state configuration', 'create a websocket handler that processes ASGI receive and send events for text and binary messages', 'test the WebSocketProtocol class connection lifecycle including handshake, send, receive, and close events', 'refactor the WebSocketProtocol class to support custom subprotocol negotiation and extra response headers', 'review the WebSocketProtocol shutdown method for graceful connection closing and server state cleanup', 'test the WebSocket keepalive ping and pong mechanism with configurable interval and timeout', 'refactor the WebSocket close handling to support clean shutdown with custom close codes and reasons', 'review the WebSocketsSansIOProtocol ASGI integration for handling receive, send, and disconnect events', 'create a WSProtocol instance to handle WebSocket connections with uvicorn config and server state', 'run an ASGI application over a WebSocket connection using WSProtocol scope, receive, and send', 'handle WebSocket events including connect, text message, binary message, close, and ping', 'send WebSocket messages including accept, text, binary, close, and HTTP response to clients', 'receive WebSocket events from the client queue with automatic backpressure flow control']
```

Usage

```
{'build_websocket_server': 'build a uvicorn websocket server using WebSocketProtocol with ASGI app and server state configuration', 'create_websocket_handler': 'create a websocket handler that processes ASGI receive and send events for text and binary messages', 'test_websocket_protocol': 'test the WebSocketProtocol class connection lifecycle including handshake, send, receive, and close events', 'refactor_websocket_protocol': 'refactor the WebSocketProtocol class to support custom subprotocol negotiation and extra response headers', 'review_websocket_shutdown': 'review the WebSocketProtocol shutdown method for graceful connection closing and server state cleanup'}
```

## File: kludex_uvicorn/uvicorn/protocols/websockets/websockets_sansio_impl.py

Prompts

```
['build a uvicorn websocket server using WebSocketProtocol with ASGI app and server state configuration', 'create a websocket handler that processes ASGI receive and send events for text and binary messages', 'test the WebSocketProtocol class connection lifecycle including handshake, send, receive, and close events', 'refactor the WebSocketProtocol class to support custom subprotocol negotiation and extra response headers', 'review the WebSocketProtocol shutdown method for graceful connection closing and server state cleanup', 'test the WebSocket keepalive ping and pong mechanism with configurable interval and timeout', 'refactor the WebSocket close handling to support clean shutdown with custom close codes and reasons', 'review the WebSocketsSansIOProtocol ASGI integration for handling receive, send, and disconnect events', 'create a WSProtocol instance to handle WebSocket connections with uvicorn config and server state', 'run an ASGI application over a WebSocket connection using WSProtocol scope, receive, and send', 'handle WebSocket events including connect, text message, binary message, close, and ping', 'send WebSocket messages including accept, text, binary, close, and HTTP response to clients', 'receive WebSocket events from the client queue with automatic backpressure flow control']
```

Usage

```
{'build_websocket_server': 'build a uvicorn websocket server using WebSocketsSansIOProtocol to handle WebSocket connections with ASGI', 'create_websocket_handler': 'create a WebSocket handler that accepts connections and sends text or binary messages via the send method', 'test_websocket_keepalive': 'test the WebSocket keepalive ping and pong mechanism with configurable interval and timeout', 'refactor_websocket_close': 'refactor the WebSocket close handling to support clean shutdown with custom close codes and reasons', 'review_websocket_asgi': 'review the WebSocketsSansIOProtocol ASGI integration for handling receive, send, and disconnect events'}
```

## File: kludex_uvicorn/uvicorn/protocols/websockets/wsproto_impl.py

Prompts

```
['build a uvicorn websocket server using WebSocketProtocol with ASGI app and server state configuration', 'create a websocket handler that processes ASGI receive and send events for text and binary messages', 'test the WebSocketProtocol class connection lifecycle including handshake, send, receive, and close events', 'refactor the WebSocketProtocol class to support custom subprotocol negotiation and extra response headers', 'review the WebSocketProtocol shutdown method for graceful connection closing and server state cleanup', 'test the WebSocket keepalive ping and pong mechanism with configurable interval and timeout', 'refactor the WebSocket close handling to support clean shutdown with custom close codes and reasons', 'review the WebSocketsSansIOProtocol ASGI integration for handling receive, send, and disconnect events', 'create a WSProtocol instance to handle WebSocket connections with uvicorn config and server state', 'run an ASGI application over a WebSocket connection using WSProtocol scope, receive, and send', 'handle WebSocket events including connect, text message, binary message, close, and ping', 'send WebSocket messages including accept, text, binary, close, and HTTP response to clients', 'receive WebSocket events from the client queue with automatic backpressure flow control']
```

Usage

```
{'create_WSProtocol': 'create a WSProtocol instance to handle WebSocket connections with uvicorn config and server state', 'run_ASGI_websocket': 'run an ASGI application over a WebSocket connection using WSProtocol scope, receive, and send', 'handle_websocket_events': 'handle WebSocket events including connect, text message, binary message, close, and ping', 'send_websocket_messages': 'send WebSocket messages including accept, text, binary, close, and HTTP response to clients', 'receive_websocket_messages': 'receive WebSocket events from the client queue with automatic backpressure flow control'}
```

