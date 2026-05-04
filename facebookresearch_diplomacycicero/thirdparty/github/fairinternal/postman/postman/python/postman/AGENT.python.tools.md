# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/postman/python/postman/asyncclient.py

Prompts

```
['create an AsyncClient instance and call connect with a 60 second deadline to get a Streams object', 'use a Streams object to call any remote method by name with arbitrary arguments via dynamic attribute access', 'close a Streams connection by calling the close method on the Streams object', 'review the AsyncClient class that extends postman.rpc.AsyncClient and wraps connect to return a Streams proxy', 'review the Streams class that proxies remote method calls through __getattr__ to the underlying raw stream', 'build a Python module to bind a function to a named RPC endpoint with batching and threading', 'run the Postman Server to start all bound worker threads for processing RPC requests', 'stop the Postman Server and close all computation queues gracefully', 'review the Server wait method that joins all worker threads after server shutdown', 'refactor the Server bind method to support dynamic thread pool sizing for batch processing']
```

Usage

```
{'connect_async_client': 'create an AsyncClient instance and call connect with a 60 second deadline to get a Streams object', 'call_remote_method_via_streams': 'use a Streams object to call any remote method by name with arbitrary arguments via dynamic attribute access', 'close_streams_connection': 'close a Streams connection by calling the close method on the Streams object', 'review_asyncclient_class': 'review the AsyncClient class that extends postman.rpc.AsyncClient and wraps connect to return a Streams proxy', 'review_streams_class': 'review the Streams class that proxies remote method calls through __getattr__ to the underlying raw stream'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/postman/python/postman/server.py

Prompts

```
['create an AsyncClient instance and call connect with a 60 second deadline to get a Streams object', 'use a Streams object to call any remote method by name with arbitrary arguments via dynamic attribute access', 'close a Streams connection by calling the close method on the Streams object', 'review the AsyncClient class that extends postman.rpc.AsyncClient and wraps connect to return a Streams proxy', 'review the Streams class that proxies remote method calls through __getattr__ to the underlying raw stream', 'build a Python module to bind a function to a named RPC endpoint with batching and threading', 'run the Postman Server to start all bound worker threads for processing RPC requests', 'stop the Postman Server and close all computation queues gracefully', 'review the Server wait method that joins all worker threads after server shutdown', 'refactor the Server bind method to support dynamic thread pool sizing for batch processing']
```

Usage

```
{'build_server_bind': 'build a Python module to bind a function to a named RPC endpoint with batching and threading', 'run_server': 'run the Postman Server to start all bound worker threads for processing RPC requests', 'stop_server': 'stop the Postman Server and close all computation queues gracefully', 'review_server_wait': 'review the Server wait method that joins all worker threads after server shutdown', 'refactor_server_bind': 'refactor the Server bind method to support dynamic thread pool sizing for batch processing'}
```

