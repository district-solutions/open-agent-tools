# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/torchbeast/client.py

Prompts

```
['review the Client class that extends torchbeast.rpc.Client for dynamic RPC attribute access', 'review the __getattr__ method that returns a callable wrapping remote RPC calls with numpy conversion', 'refactor the Client class to send available function names during initialization instead of relying on __getattr__', 'test the __getattr__ method to verify it converts arguments to numpy arrays before RPC dispatch', 'summarize the Client class RPC proxy pattern that maps arbitrary attribute access to remote calls', 'create a closable Queue instance that extends the standard library queue.Queue with close support', 'close a Queue instance to stop all producers and consumers and notify all waiting threads', 'check if a Queue instance has been closed by calling the closed method', 'put an item into a closable Queue which raises Closed if the queue is already closed', 'get an item from a closable Queue which raises Closed if the queue is already closed', 'test the Queue class by putting and getting items in a simple single-threaded scenario', 'test the Queue class for thread safety by closing it while a thread waits on get', 'test that calling close on a Queue raises Closed exception on subsequent get calls', 'test the Queue class with a maxsize parameter to limit buffer capacity', 'test that Queue get with a timeout raises Closed when the queue is closed early', 'create a Timings instance to track elapsed time between events by name', 'use the time method to record elapsed time for a named event since last call', 'use the track context manager to automatically time a block of code by name', 'get the mean and standard deviation for a named timing event using the get method', 'print a formatted summary of all timing events sorted by mean duration with percentages']
```

Usage

```
{'review_Client_class': 'review the Client class that extends torchbeast.rpc.Client for dynamic RPC attribute access', 'review___getattr__': 'review the __getattr__ method that returns a callable wrapping remote RPC calls with numpy conversion', 'refactor_Client_class': 'refactor the Client class to send available function names during initialization instead of relying on __getattr__', 'test___getattr__': 'test the __getattr__ method to verify it converts arguments to numpy arrays before RPC dispatch', 'summarize_Client_class': 'summarize the Client class RPC proxy pattern that maps arbitrary attribute access to remote calls'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/torchbeast/queue.py

Prompts

```
['review the Client class that extends torchbeast.rpc.Client for dynamic RPC attribute access', 'review the __getattr__ method that returns a callable wrapping remote RPC calls with numpy conversion', 'refactor the Client class to send available function names during initialization instead of relying on __getattr__', 'test the __getattr__ method to verify it converts arguments to numpy arrays before RPC dispatch', 'summarize the Client class RPC proxy pattern that maps arbitrary attribute access to remote calls', 'create a closable Queue instance that extends the standard library queue.Queue with close support', 'close a Queue instance to stop all producers and consumers and notify all waiting threads', 'check if a Queue instance has been closed by calling the closed method', 'put an item into a closable Queue which raises Closed if the queue is already closed', 'get an item from a closable Queue which raises Closed if the queue is already closed', 'test the Queue class by putting and getting items in a simple single-threaded scenario', 'test the Queue class for thread safety by closing it while a thread waits on get', 'test that calling close on a Queue raises Closed exception on subsequent get calls', 'test the Queue class with a maxsize parameter to limit buffer capacity', 'test that Queue get with a timeout raises Closed when the queue is closed early', 'create a Timings instance to track elapsed time between events by name', 'use the time method to record elapsed time for a named event since last call', 'use the track context manager to automatically time a block of code by name', 'get the mean and standard deviation for a named timing event using the get method', 'print a formatted summary of all timing events sorted by mean duration with percentages']
```

Usage

```
{'create_closable_queue': 'create a closable Queue instance that extends the standard library queue.Queue with close support', 'close_queue': 'close a Queue instance to stop all producers and consumers and notify all waiting threads', 'check_queue_closed': 'check if a Queue instance has been closed by calling the closed method', 'put_item_in_queue': 'put an item into a closable Queue which raises Closed if the queue is already closed', 'get_item_from_queue': 'get an item from a closable Queue which raises Closed if the queue is already closed'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/torchbeast/queue_test.py

Prompts

```
['review the Client class that extends torchbeast.rpc.Client for dynamic RPC attribute access', 'review the __getattr__ method that returns a callable wrapping remote RPC calls with numpy conversion', 'refactor the Client class to send available function names during initialization instead of relying on __getattr__', 'test the __getattr__ method to verify it converts arguments to numpy arrays before RPC dispatch', 'summarize the Client class RPC proxy pattern that maps arbitrary attribute access to remote calls', 'create a closable Queue instance that extends the standard library queue.Queue with close support', 'close a Queue instance to stop all producers and consumers and notify all waiting threads', 'check if a Queue instance has been closed by calling the closed method', 'put an item into a closable Queue which raises Closed if the queue is already closed', 'get an item from a closable Queue which raises Closed if the queue is already closed', 'test the Queue class by putting and getting items in a simple single-threaded scenario', 'test the Queue class for thread safety by closing it while a thread waits on get', 'test that calling close on a Queue raises Closed exception on subsequent get calls', 'test the Queue class with a maxsize parameter to limit buffer capacity', 'test that Queue get with a timeout raises Closed when the queue is closed early', 'create a Timings instance to track elapsed time between events by name', 'use the time method to record elapsed time for a named event since last call', 'use the track context manager to automatically time a block of code by name', 'get the mean and standard deviation for a named timing event using the get method', 'print a formatted summary of all timing events sorted by mean duration with percentages']
```

Usage

```
{'test_queue_simple': 'test the Queue class by putting and getting items in a simple single-threaded scenario', 'test_queue_thread_safety': 'test the Queue class for thread safety by closing it while a thread waits on get', 'test_queue_close': 'test that calling close on a Queue raises Closed exception on subsequent get calls', 'test_queue_maxsize': 'test the Queue class with a maxsize parameter to limit buffer capacity', 'test_queue_timeout': 'test that Queue get with a timeout raises Closed when the queue is closed early'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/torchbeast/timings.py

Prompts

```
['review the Client class that extends torchbeast.rpc.Client for dynamic RPC attribute access', 'review the __getattr__ method that returns a callable wrapping remote RPC calls with numpy conversion', 'refactor the Client class to send available function names during initialization instead of relying on __getattr__', 'test the __getattr__ method to verify it converts arguments to numpy arrays before RPC dispatch', 'summarize the Client class RPC proxy pattern that maps arbitrary attribute access to remote calls', 'create a closable Queue instance that extends the standard library queue.Queue with close support', 'close a Queue instance to stop all producers and consumers and notify all waiting threads', 'check if a Queue instance has been closed by calling the closed method', 'put an item into a closable Queue which raises Closed if the queue is already closed', 'get an item from a closable Queue which raises Closed if the queue is already closed', 'test the Queue class by putting and getting items in a simple single-threaded scenario', 'test the Queue class for thread safety by closing it while a thread waits on get', 'test that calling close on a Queue raises Closed exception on subsequent get calls', 'test the Queue class with a maxsize parameter to limit buffer capacity', 'test that Queue get with a timeout raises Closed when the queue is closed early', 'create a Timings instance to track elapsed time between events by name', 'use the time method to record elapsed time for a named event since last call', 'use the track context manager to automatically time a block of code by name', 'get the mean and standard deviation for a named timing event using the get method', 'print a formatted summary of all timing events sorted by mean duration with percentages']
```

Usage

```
{'create_timings_instance': 'create a Timings instance to track elapsed time between events by name', 'use_timings_time': 'use the time method to record elapsed time for a named event since last call', 'use_timings_track': 'use the track context manager to automatically time a block of code by name', 'get_timings_stats': 'get the mean and standard deviation for a named timing event using the get method', 'print_timings_summary': 'print a formatted summary of all timing events sorted by mean duration with percentages'}
```

