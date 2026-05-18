# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/shared/gaia2_adapter_base.py

Prompts

```
['run an HTTP adapter server that connects to a backend and listens on a configurable port', 'create a client handler with standard routes for health, messages, SSE events, and notify endpoints', 'create an AdapterState instance to manage message buffering and SSE client connections', 'write an AgentUserInterface event entry to the events.jsonl log file', 'handle an SSE stream connection that broadcasts agent responses to connected clients', 'render an agent system prompt from a scenario JSON and template file', 'render an agent prompt using a custom exec tool name like terminal for Hermes', 'render an agent prompt and write it to an output file path', 'build an exec-approvals JSON config for unrestricted Gaia2 agent execution', 'run the render agent prompt CLI with a scenario path and optional output paths', 'run the MITM HTTP CONNECT TLS proxy on a specified port with CA cert and key', 'run the TLS proxy with a pre-generated host key for certificate signing', 'run the TLS proxy routing upstream connections through an HTTP CONNECT proxy', 'review the TLS proxy health check endpoint that responds to GET /healthz requests', 'review the per-host certificate generation using OpenSSL with faketime for signing']
```

Usage

```
{'run_adapter_http_server': 'run an HTTP adapter server that connects to a backend and listens on a configurable port', 'create_client_handler_routes': 'create a client handler with standard routes for health, messages, SSE events, and notify endpoints', 'create_adapter_state_buffer': 'create an AdapterState instance to manage message buffering and SSE client connections', 'write_aui_event_jsonl': 'write an AgentUserInterface event entry to the events.jsonl log file', 'handle_sse_stream': 'handle an SSE stream connection that broadcasts agent responses to connected clients'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/shared/render_agent_prompt.py

Prompts

```
['run an HTTP adapter server that connects to a backend and listens on a configurable port', 'create a client handler with standard routes for health, messages, SSE events, and notify endpoints', 'create an AdapterState instance to manage message buffering and SSE client connections', 'write an AgentUserInterface event entry to the events.jsonl log file', 'handle an SSE stream connection that broadcasts agent responses to connected clients', 'render an agent system prompt from a scenario JSON and template file', 'render an agent prompt using a custom exec tool name like terminal for Hermes', 'render an agent prompt and write it to an output file path', 'build an exec-approvals JSON config for unrestricted Gaia2 agent execution', 'run the render agent prompt CLI with a scenario path and optional output paths', 'run the MITM HTTP CONNECT TLS proxy on a specified port with CA cert and key', 'run the TLS proxy with a pre-generated host key for certificate signing', 'run the TLS proxy routing upstream connections through an HTTP CONNECT proxy', 'review the TLS proxy health check endpoint that responds to GET /healthz requests', 'review the per-host certificate generation using OpenSSL with faketime for signing']
```

Usage

```
{'render_agent_prompt_from_scenario': 'render an agent system prompt from a scenario JSON and template file', 'render_prompt_with_custom_exec_tool': 'render an agent prompt using a custom exec tool name like terminal for Hermes', 'render_prompt_to_file': 'render an agent prompt and write it to an output file path', 'build_exec_approvals': 'build an exec-approvals JSON config for unrestricted Gaia2 agent execution', 'run_render_cli': 'run the render agent prompt CLI with a scenario path and optional output paths'}
```

## File: facebookresearch_meta-agents-research-environments/gaia2-cli/shared/tls_proxy.py

Prompts

```
['run an HTTP adapter server that connects to a backend and listens on a configurable port', 'create a client handler with standard routes for health, messages, SSE events, and notify endpoints', 'create an AdapterState instance to manage message buffering and SSE client connections', 'write an AgentUserInterface event entry to the events.jsonl log file', 'handle an SSE stream connection that broadcasts agent responses to connected clients', 'render an agent system prompt from a scenario JSON and template file', 'render an agent prompt using a custom exec tool name like terminal for Hermes', 'render an agent prompt and write it to an output file path', 'build an exec-approvals JSON config for unrestricted Gaia2 agent execution', 'run the render agent prompt CLI with a scenario path and optional output paths', 'run the MITM HTTP CONNECT TLS proxy on a specified port with CA cert and key', 'run the TLS proxy with a pre-generated host key for certificate signing', 'run the TLS proxy routing upstream connections through an HTTP CONNECT proxy', 'review the TLS proxy health check endpoint that responds to GET /healthz requests', 'review the per-host certificate generation using OpenSSL with faketime for signing']
```

Usage

```
{'run_tls_proxy': 'run the MITM HTTP CONNECT TLS proxy on a specified port with CA cert and key', 'run_tls_proxy_with_host_key': 'run the TLS proxy with a pre-generated host key for certificate signing', 'run_tls_proxy_with_upstream_proxy': 'run the TLS proxy routing upstream connections through an HTTP CONNECT proxy', 'review_tls_proxy_health_check': 'review the TLS proxy health check endpoint that responds to GET /healthz requests', 'review_tls_proxy_cert_generation': 'review the per-host certificate generation using OpenSSL with faketime for signing'}
```

