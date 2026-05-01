# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/litellm/proxy/test_batch_x_litellm_model_encoding.py

Prompts

```
['test that create_batch encodes batch_id with model info when x-litellm-model header is provided', 'test that output_file_id and error_file_id are encoded with model info for completed batches', 'test that create_batch returns raw batch IDs when x-litellm-model header is absent', 'test the full round-trip of encoding a batch_id with model info and decoding it back', 'test batch ID encoding and decoding for various VLLM-style batch ID formats', 'test that ProxyLogging replaces string callbacks with initialized CustomLogger instances in litellm.callbacks', 'test that existing CustomLogger instances in litellm.callbacks are not duplicated during initialization', 'test that unrecognized string callbacks remain in litellm.callbacks without crashing the proxy', 'test that multiple string callbacks are each replaced with their corresponding initialized instances', 'review the FakeCustomLogger test subclass used to mock CustomLogger behavior in proxy callback tests', 'test the encode_file_id_with_model function to encode OpenAI file IDs with a model name', 'test the encode and decode round-trip to verify model and original ID are recovered', 'test the decode functions with plain non-encoded IDs and non-string inputs', 'run encode_file_id_with_model to encode a Vertex AI numeric batch ID with id_type batch', 'run decode_model_from_file_id to extract the model name from an encoded file ID', 'test the PrismaClient _is_engine_alive method to check if the engine process is running using os.kill', 'test the PrismaClient _poll_engine_proc method that triggers attempt_db_reconnect when the engine process dies', 'test the PrismaClient _run_reconnect_cycle method to verify heavy path recreates client when engine is dead and lightweight path uses disconnect connect when alive', 'test the PrismaClient _try_waitpid_watch method that starts a daemon thread for instant cross-platform engine death detection via os.waitpid', 'test the PrismaClient _attempt_reconnect_inside_lock method to verify escalation from lightweight to heavy reconnect after consecutive failures']
```

Usage

```
{'test_batch_id_encoding_with_x_litellm_model': 'test that create_batch encodes batch_id with model info when x-litellm-model header is provided', 'test_batch_output_error_file_id_encoding': 'test that output_file_id and error_file_id are encoded with model info for completed batches', 'test_batch_without_x_litellm_model': 'test that create_batch returns raw batch IDs when x-litellm-model header is absent', 'test_encode_decode_batch_id_roundtrip': 'test the full round-trip of encoding a batch_id with model info and decoding it back', 'test_vllm_style_batch_id_roundtrip': 'test batch ID encoding and decoding for various VLLM-style batch ID formats'}
```

## File: berriai_litellm/tests/litellm/proxy/test_init_litellm_callbacks.py

Prompts

```
['test that create_batch encodes batch_id with model info when x-litellm-model header is provided', 'test that output_file_id and error_file_id are encoded with model info for completed batches', 'test that create_batch returns raw batch IDs when x-litellm-model header is absent', 'test the full round-trip of encoding a batch_id with model info and decoding it back', 'test batch ID encoding and decoding for various VLLM-style batch ID formats', 'test that ProxyLogging replaces string callbacks with initialized CustomLogger instances in litellm.callbacks', 'test that existing CustomLogger instances in litellm.callbacks are not duplicated during initialization', 'test that unrecognized string callbacks remain in litellm.callbacks without crashing the proxy', 'test that multiple string callbacks are each replaced with their corresponding initialized instances', 'review the FakeCustomLogger test subclass used to mock CustomLogger behavior in proxy callback tests', 'test the encode_file_id_with_model function to encode OpenAI file IDs with a model name', 'test the encode and decode round-trip to verify model and original ID are recovered', 'test the decode functions with plain non-encoded IDs and non-string inputs', 'run encode_file_id_with_model to encode a Vertex AI numeric batch ID with id_type batch', 'run decode_model_from_file_id to extract the model name from an encoded file ID', 'test the PrismaClient _is_engine_alive method to check if the engine process is running using os.kill', 'test the PrismaClient _poll_engine_proc method that triggers attempt_db_reconnect when the engine process dies', 'test the PrismaClient _run_reconnect_cycle method to verify heavy path recreates client when engine is dead and lightweight path uses disconnect connect when alive', 'test the PrismaClient _try_waitpid_watch method that starts a daemon thread for instant cross-platform engine death detection via os.waitpid', 'test the PrismaClient _attempt_reconnect_inside_lock method to verify escalation from lightweight to heavy reconnect after consecutive failures']
```

Usage

```
{'test_string_callback_replacement': 'test that ProxyLogging replaces string callbacks with initialized CustomLogger instances in litellm.callbacks', 'test_no_duplicate_instance_callbacks': 'test that existing CustomLogger instances in litellm.callbacks are not duplicated during initialization', 'test_unrecognized_string_callback_handling': 'test that unrecognized string callbacks remain in litellm.callbacks without crashing the proxy', 'test_multiple_string_callback_replacement': 'test that multiple string callbacks are each replaced with their corresponding initialized instances', 'review_FakeCustomLogger': 'review the FakeCustomLogger test subclass used to mock CustomLogger behavior in proxy callback tests'}
```

## File: berriai_litellm/tests/litellm/proxy/test_model_based_routing_files_batches.py

Prompts

```
['test that create_batch encodes batch_id with model info when x-litellm-model header is provided', 'test that output_file_id and error_file_id are encoded with model info for completed batches', 'test that create_batch returns raw batch IDs when x-litellm-model header is absent', 'test the full round-trip of encoding a batch_id with model info and decoding it back', 'test batch ID encoding and decoding for various VLLM-style batch ID formats', 'test that ProxyLogging replaces string callbacks with initialized CustomLogger instances in litellm.callbacks', 'test that existing CustomLogger instances in litellm.callbacks are not duplicated during initialization', 'test that unrecognized string callbacks remain in litellm.callbacks without crashing the proxy', 'test that multiple string callbacks are each replaced with their corresponding initialized instances', 'review the FakeCustomLogger test subclass used to mock CustomLogger behavior in proxy callback tests', 'test the encode_file_id_with_model function to encode OpenAI file IDs with a model name', 'test the encode and decode round-trip to verify model and original ID are recovered', 'test the decode functions with plain non-encoded IDs and non-string inputs', 'run encode_file_id_with_model to encode a Vertex AI numeric batch ID with id_type batch', 'run decode_model_from_file_id to extract the model name from an encoded file ID', 'test the PrismaClient _is_engine_alive method to check if the engine process is running using os.kill', 'test the PrismaClient _poll_engine_proc method that triggers attempt_db_reconnect when the engine process dies', 'test the PrismaClient _run_reconnect_cycle method to verify heavy path recreates client when engine is dead and lightweight path uses disconnect connect when alive', 'test the PrismaClient _try_waitpid_watch method that starts a daemon thread for instant cross-platform engine death detection via os.waitpid', 'test the PrismaClient _attempt_reconnect_inside_lock method to verify escalation from lightweight to heavy reconnect after consecutive failures']
```

Usage

```
{'test_encode_file_id_with_model': 'test the encode_file_id_with_model function to encode OpenAI file IDs with a model name', 'test_roundtrip_encode_decode': 'test the encode and decode round-trip to verify model and original ID are recovered', 'test_decode_edge_cases': 'test the decode functions with plain non-encoded IDs and non-string inputs', 'run_encode_file_id_with_model': 'run encode_file_id_with_model to encode a Vertex AI numeric batch ID with id_type batch', 'run_decode_model_from_file_id': 'run decode_model_from_file_id to extract the model name from an encoded file ID'}
```

## File: berriai_litellm/tests/litellm/proxy/test_prisma_engine_watchdog.py

Prompts

```
['test that create_batch encodes batch_id with model info when x-litellm-model header is provided', 'test that output_file_id and error_file_id are encoded with model info for completed batches', 'test that create_batch returns raw batch IDs when x-litellm-model header is absent', 'test the full round-trip of encoding a batch_id with model info and decoding it back', 'test batch ID encoding and decoding for various VLLM-style batch ID formats', 'test that ProxyLogging replaces string callbacks with initialized CustomLogger instances in litellm.callbacks', 'test that existing CustomLogger instances in litellm.callbacks are not duplicated during initialization', 'test that unrecognized string callbacks remain in litellm.callbacks without crashing the proxy', 'test that multiple string callbacks are each replaced with their corresponding initialized instances', 'review the FakeCustomLogger test subclass used to mock CustomLogger behavior in proxy callback tests', 'test the encode_file_id_with_model function to encode OpenAI file IDs with a model name', 'test the encode and decode round-trip to verify model and original ID are recovered', 'test the decode functions with plain non-encoded IDs and non-string inputs', 'run encode_file_id_with_model to encode a Vertex AI numeric batch ID with id_type batch', 'run decode_model_from_file_id to extract the model name from an encoded file ID', 'test the PrismaClient _is_engine_alive method to check if the engine process is running using os.kill', 'test the PrismaClient _poll_engine_proc method that triggers attempt_db_reconnect when the engine process dies', 'test the PrismaClient _run_reconnect_cycle method to verify heavy path recreates client when engine is dead and lightweight path uses disconnect connect when alive', 'test the PrismaClient _try_waitpid_watch method that starts a daemon thread for instant cross-platform engine death detection via os.waitpid', 'test the PrismaClient _attempt_reconnect_inside_lock method to verify escalation from lightweight to heavy reconnect after consecutive failures']
```

Usage

```
{'test_prisma_engine_watchdog_liveness': 'test the PrismaClient _is_engine_alive method to check if the engine process is running using os.kill', 'test_prisma_engine_polling_reconnect': 'test the PrismaClient _poll_engine_proc method that triggers attempt_db_reconnect when the engine process dies', 'test_prisma_reconnect_cycle_branching': 'test the PrismaClient _run_reconnect_cycle method to verify heavy path recreates client when engine is dead and lightweight path uses disconnect connect when alive', 'test_prisma_waitpid_thread_detection': 'test the PrismaClient _try_waitpid_watch method that starts a daemon thread for instant cross-platform engine death detection via os.waitpid', 'test_prisma_reconnect_escalation': 'test the PrismaClient _attempt_reconnect_inside_lock method to verify escalation from lightweight to heavy reconnect after consecutive failures'}
```

