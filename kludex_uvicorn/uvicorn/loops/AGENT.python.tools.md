# Agent Python Tools

- repo: kludex/uvicorn
- repo_uri: https://github.com/kludex/uvicorn

## File: kludex_uvicorn/uvicorn/loops/asyncio.py

Prompts

```
['create an asyncio event loop factory that returns ProactorEventLoop on Windows or SelectorEventLoop otherwise', 'summarize the asyncio_loop_factory function that selects the appropriate asyncio event loop class based on platform', 'create a uvloop event loop factory function that returns uvloop.new_event_loop', 'run the uvloop_loop_factory to get a callable that creates uvloop event loops', 'test the uvloop_loop_factory returns a callable that creates asyncio.AbstractEventLoop instances', 'summarize the uvloop_loop_factory function that wraps uvloop.new_event_loop as a factory', 'review the uvloop_loop_factory function for subprocess support and event loop creation']
```

Usage

```
{'create_asyncio_loop_factory': 'create an asyncio event loop factory that returns ProactorEventLoop on Windows or SelectorEventLoop otherwise', 'summarize_asyncio_loop_factory': 'summarize the asyncio_loop_factory function that selects the appropriate asyncio event loop class based on platform'}
```

## File: kludex_uvicorn/uvicorn/loops/uvloop.py

Prompts

```
['create an asyncio event loop factory that returns ProactorEventLoop on Windows or SelectorEventLoop otherwise', 'summarize the asyncio_loop_factory function that selects the appropriate asyncio event loop class based on platform', 'create a uvloop event loop factory function that returns uvloop.new_event_loop', 'run the uvloop_loop_factory to get a callable that creates uvloop event loops', 'test the uvloop_loop_factory returns a callable that creates asyncio.AbstractEventLoop instances', 'summarize the uvloop_loop_factory function that wraps uvloop.new_event_loop as a factory', 'review the uvloop_loop_factory function for subprocess support and event loop creation']
```

Usage

```
{'create_uvloop_loop_factory': 'create a uvloop event loop factory function that returns uvloop.new_event_loop', 'run_uvloop_loop_factory': 'run the uvloop_loop_factory to get a callable that creates uvloop event loops', 'test_uvloop_loop_factory': 'test the uvloop_loop_factory returns a callable that creates asyncio.AbstractEventLoop instances', 'summarize_uvloop_loop_factory': 'summarize the uvloop_loop_factory function that wraps uvloop.new_event_loop as a factory', 'review_uvloop_loop_factory': 'review the uvloop_loop_factory function for subprocess support and event loop creation'}
```

