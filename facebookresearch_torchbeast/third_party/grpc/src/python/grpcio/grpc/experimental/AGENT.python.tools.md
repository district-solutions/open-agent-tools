# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio/grpc/experimental/gevent.py

Prompts

```
['init gRPC to be compatible with gevent by calling init_gevent before creating gRPC objects', 'run a gevent-based application that uses gRPC by calling init_gevent after patching the standard library', 'test that gRPC works with gevent by calling init_gevent and verifying the event loop drives progress', 'review the init_gevent function to understand how it patches gRPC libraries for gevent compatibility', 'summarize the gRPC gevent API and its requirement to call init_gevent before creating gRPC objects', 'create an SSL session cache with LRU replacement policy by calling ssl_session_cache_lru with a capacity', 'build an SSLSessionCache instance to pass as the grpc.ssl_session_cache option to a grpc.Channel', 'test the ssl_session_cache_lru function by creating a cache with a given capacity and verifying it returns an SSLSessionCache', 'review the SSLSessionCache class and its __init__ and __int__ methods for TLS session resumption support', 'summarize the session_cache module which provides gRPC APIs for TLS session resumption via LRU caching']
```

Usage

```
{'init_gevent_for_grpc': 'init gRPC to be compatible with gevent by calling init_gevent before creating gRPC objects', 'run_gevent_with_grpc': 'run a gevent-based application that uses gRPC by calling init_gevent after patching the standard library', 'test_gevent_compatibility': 'test that gRPC works with gevent by calling init_gevent and verifying the event loop drives progress', 'review_gevent_init': 'review the init_gevent function to understand how it patches gRPC libraries for gevent compatibility', 'summarize_gevent_api': 'summarize the gRPC gevent API and its requirement to call init_gevent before creating gRPC objects'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio/grpc/experimental/session_cache.py

Prompts

```
['init gRPC to be compatible with gevent by calling init_gevent before creating gRPC objects', 'run a gevent-based application that uses gRPC by calling init_gevent after patching the standard library', 'test that gRPC works with gevent by calling init_gevent and verifying the event loop drives progress', 'review the init_gevent function to understand how it patches gRPC libraries for gevent compatibility', 'summarize the gRPC gevent API and its requirement to call init_gevent before creating gRPC objects', 'create an SSL session cache with LRU replacement policy by calling ssl_session_cache_lru with a capacity', 'build an SSLSessionCache instance to pass as the grpc.ssl_session_cache option to a grpc.Channel', 'test the ssl_session_cache_lru function by creating a cache with a given capacity and verifying it returns an SSLSessionCache', 'review the SSLSessionCache class and its __init__ and __int__ methods for TLS session resumption support', 'summarize the session_cache module which provides gRPC APIs for TLS session resumption via LRU caching']
```

Usage

```
{'create_ssl_session_cache_lru': 'create an SSL session cache with LRU replacement policy by calling ssl_session_cache_lru with a capacity', 'build_ssl_session_cache_for_channel': 'build an SSLSessionCache instance to pass as the grpc.ssl_session_cache option to a grpc.Channel', 'test_ssl_session_cache_lru': 'test the ssl_session_cache_lru function by creating a cache with a given capacity and verifying it returns an SSLSessionCache', 'review_sslsessioncache_class': 'review the SSLSessionCache class and its __init__ and __int__ methods for TLS session resumption support', 'summarize_ssl_session_cache_module': 'summarize the session_cache module which provides gRPC APIs for TLS session resumption via LRU caching'}
```

