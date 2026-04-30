# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/service_client/client.py

Prompts

```
['create a conversion job for a document source and return the conversion result with options', 'run batch conversion on multiple document sources with concurrency control and error handling', 'submit many conversion items with controlled in-flight concurrency and retrieve responses', 'submit an async conversion job for a document source and return a job handle for polling', 'test the docling service health endpoint and return the health check response', 'create a ConversionJob handle for an asynchronous docling-serve conversion task using a task_id and handlers', 'poll a ConversionJob for its current task status response with an optional wait interval', 'watch a ConversionJob iterator that yields TaskStatusResponse updates until completion', 'wait for a ConversionJob to finish and fetch the final result with an optional timeout', 'check if a ConversionJob is done by inspecting its done property and terminal task status', 'create a PollingWatcher that polls task status with server-side wait and client-side interval cadence', 'create a WebSocketWatcher that streams task status updates via WebSocket with HTTP polling fallback', 'test the is_terminal_task_status function to check if a task status is success or failure', 'review the StatusWatcher Protocol defining iter_updates and wait_for_terminal method signatures', 'summarize the PollingWatcher.iter_updates method that yields status updates until terminal or timeout']
```

Usage

```
{'create_convert_document': 'create a conversion job for a document source and return the conversion result with options', 'run_convert_all_documents': 'run batch conversion on multiple document sources with concurrency control and error handling', 'submit_and_retrieve_many_tasks': 'submit many conversion items with controlled in-flight concurrency and retrieve responses', 'submit_async_conversion_job': 'submit an async conversion job for a document source and return a job handle for polling', 'test_service_health': 'test the docling service health endpoint and return the health check response'}
```

## File: docling-project_docling/docling/service_client/job.py

Prompts

```
['create a conversion job for a document source and return the conversion result with options', 'run batch conversion on multiple document sources with concurrency control and error handling', 'submit many conversion items with controlled in-flight concurrency and retrieve responses', 'submit an async conversion job for a document source and return a job handle for polling', 'test the docling service health endpoint and return the health check response', 'create a ConversionJob handle for an asynchronous docling-serve conversion task using a task_id and handlers', 'poll a ConversionJob for its current task status response with an optional wait interval', 'watch a ConversionJob iterator that yields TaskStatusResponse updates until completion', 'wait for a ConversionJob to finish and fetch the final result with an optional timeout', 'check if a ConversionJob is done by inspecting its done property and terminal task status', 'create a PollingWatcher that polls task status with server-side wait and client-side interval cadence', 'create a WebSocketWatcher that streams task status updates via WebSocket with HTTP polling fallback', 'test the is_terminal_task_status function to check if a task status is success or failure', 'review the StatusWatcher Protocol defining iter_updates and wait_for_terminal method signatures', 'summarize the PollingWatcher.iter_updates method that yields status updates until terminal or timeout']
```

Usage

```
{'create_conversion_job': 'create a ConversionJob handle for an asynchronous docling-serve conversion task using a task_id and handlers', 'poll_conversion_status': 'poll a ConversionJob for its current task status response with an optional wait interval', 'watch_conversion_progress': 'watch a ConversionJob iterator that yields TaskStatusResponse updates until completion', 'wait_for_conversion_result': 'wait for a ConversionJob to finish and fetch the final result with an optional timeout', 'check_conversion_done': 'check if a ConversionJob is done by inspecting its done property and terminal task status'}
```

## File: docling-project_docling/docling/service_client/watchers.py

Prompts

```
['create a conversion job for a document source and return the conversion result with options', 'run batch conversion on multiple document sources with concurrency control and error handling', 'submit many conversion items with controlled in-flight concurrency and retrieve responses', 'submit an async conversion job for a document source and return a job handle for polling', 'test the docling service health endpoint and return the health check response', 'create a ConversionJob handle for an asynchronous docling-serve conversion task using a task_id and handlers', 'poll a ConversionJob for its current task status response with an optional wait interval', 'watch a ConversionJob iterator that yields TaskStatusResponse updates until completion', 'wait for a ConversionJob to finish and fetch the final result with an optional timeout', 'check if a ConversionJob is done by inspecting its done property and terminal task status', 'create a PollingWatcher that polls task status with server-side wait and client-side interval cadence', 'create a WebSocketWatcher that streams task status updates via WebSocket with HTTP polling fallback', 'test the is_terminal_task_status function to check if a task status is success or failure', 'review the StatusWatcher Protocol defining iter_updates and wait_for_terminal method signatures', 'summarize the PollingWatcher.iter_updates method that yields status updates until terminal or timeout']
```

Usage

```
{'create_PollingWatcher': 'create a PollingWatcher that polls task status with server-side wait and client-side interval cadence', 'create_WebSocketWatcher': 'create a WebSocketWatcher that streams task status updates via WebSocket with HTTP polling fallback', 'test_is_terminal_task_status': 'test the is_terminal_task_status function to check if a task status is success or failure', 'review_StatusWatcher': 'review the StatusWatcher Protocol defining iter_updates and wait_for_terminal method signatures', 'summarize_PollingWatcher_iter_updates': 'summarize the PollingWatcher.iter_updates method that yields status updates until terminal or timeout'}
```

