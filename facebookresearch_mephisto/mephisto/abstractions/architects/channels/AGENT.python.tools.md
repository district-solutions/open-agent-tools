# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/architects/channels/websocket_channel.py

Prompts

```
['create a WebsocketChannel instance with a channel_id, callbacks, and socket_url for websocket communication', 'open a WebsocketChannel to start the socket handling thread and begin receiving messages', 'close a WebsocketChannel to clean up threads and surrounding resources', 'enqueue a Packet to send through an open WebsocketChannel connection', 'check if a WebsocketChannel is alive or closed using is_alive and is_closed methods']
```

Usage

```
{'create_websocket_channel': 'create a WebsocketChannel instance with a channel_id, callbacks, and socket_url for websocket communication', 'open_websocket_channel': 'open a WebsocketChannel to start the socket handling thread and begin receiving messages', 'close_websocket_channel': 'close a WebsocketChannel to clean up threads and surrounding resources', 'enqueue_send_packet': 'enqueue a Packet to send through an open WebsocketChannel connection', 'check_websocket_channel_status': 'check if a WebsocketChannel is alive or closed using is_alive and is_closed methods'}
```

