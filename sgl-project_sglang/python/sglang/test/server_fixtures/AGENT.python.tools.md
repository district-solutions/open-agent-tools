# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/test/server_fixtures/default_fixture.py

Prompts

```
['test the DefaultServerBase class that launches and manages an SGLang server process for integration tests', 'run the openai_api_env context manager to set OpenAI API key and base URL environment variables', 'run popen_launch_server to start an SGLang model server process in a subprocess', 'run kill_process_tree to terminate an SGLang server process and its child processes', 'run flush_cache to send a POST request to the /flush_cache endpoint of the running server', 'test the PDDisaggregationServerBase class and launch prefill, decode, and load balancer servers for disaggregation testing', 'test the PDDisaggregationServerBase class and start a prefill server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and start a decode server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and launch a load balancer for prefill and decode disaggregation endpoints', 'run get_rdma_devices_args to resolve RDMA device arguments from environment variables, auto-detection, or fallback defaults', 'test the EagleServerBase class to launch an SGLang server with EAGLE speculative decoding enabled', 'test the send_request method to send generation requests to the EAGLE server with temperature 0', 'test the send_requests_abort method to simulate client disconnection with a 1-second timeout', 'test the run_decode method to generate text with logprob return and custom sampling parameters', 'test the tearDownClass method to kill the EAGLE server process tree on cleanup', 'test the MMMUServerBase fixture class for launching and managing an SGLang VLM server with MMMU-specific settings', 'run the setUpClass method to launch an SGLang server with multimodal support and configurable mem_fraction_static', 'run the tearDownClass method to gracefully kill the SGLang server process and wait for cleanup', 'build a subclass of MMMUServerBase setting cls.model to launch a specific VLM for MMMU testing', 'review the MMMUServerBase server_args configuration including trust_remote_code, cuda_graph_max_bs, and enable_multimodal flags']
```

Usage

```
{'test_default_server_base': 'test the DefaultServerBase class that launches and manages an SGLang server process for integration tests', 'run_openai_api_env': 'run the openai_api_env context manager to set OpenAI API key and base URL environment variables', 'run_popen_launch_server': 'run popen_launch_server to start an SGLang model server process in a subprocess', 'run_kill_process_tree': 'run kill_process_tree to terminate an SGLang server process and its child processes', 'run_flush_cache': 'run flush_cache to send a POST request to the /flush_cache endpoint of the running server'}
```

## File: sgl-project_sglang/python/sglang/test/server_fixtures/disaggregation_fixture.py

Prompts

```
['test the DefaultServerBase class that launches and manages an SGLang server process for integration tests', 'run the openai_api_env context manager to set OpenAI API key and base URL environment variables', 'run popen_launch_server to start an SGLang model server process in a subprocess', 'run kill_process_tree to terminate an SGLang server process and its child processes', 'run flush_cache to send a POST request to the /flush_cache endpoint of the running server', 'test the PDDisaggregationServerBase class and launch prefill, decode, and load balancer servers for disaggregation testing', 'test the PDDisaggregationServerBase class and start a prefill server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and start a decode server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and launch a load balancer for prefill and decode disaggregation endpoints', 'run get_rdma_devices_args to resolve RDMA device arguments from environment variables, auto-detection, or fallback defaults', 'test the EagleServerBase class to launch an SGLang server with EAGLE speculative decoding enabled', 'test the send_request method to send generation requests to the EAGLE server with temperature 0', 'test the send_requests_abort method to simulate client disconnection with a 1-second timeout', 'test the run_decode method to generate text with logprob return and custom sampling parameters', 'test the tearDownClass method to kill the EAGLE server process tree on cleanup', 'test the MMMUServerBase fixture class for launching and managing an SGLang VLM server with MMMU-specific settings', 'run the setUpClass method to launch an SGLang server with multimodal support and configurable mem_fraction_static', 'run the tearDownClass method to gracefully kill the SGLang server process and wait for cleanup', 'build a subclass of MMMUServerBase setting cls.model to launch a specific VLM for MMMU testing', 'review the MMMUServerBase server_args configuration including trust_remote_code, cuda_graph_max_bs, and enable_multimodal flags']
```

Usage

```
{'test_PDDisaggregationServerBase_launch_all': 'test the PDDisaggregationServerBase class and launch prefill, decode, and load balancer servers for disaggregation testing', 'test_PDDisaggregationServerBase_start_prefill': 'test the PDDisaggregationServerBase class and start a prefill server instance with disaggregation mode enabled', 'test_PDDisaggregationServerBase_start_decode': 'test the PDDisaggregationServerBase class and start a decode server instance with disaggregation mode enabled', 'test_PDDisaggregationServerBase_launch_lb': 'test the PDDisaggregationServerBase class and launch a load balancer for prefill and decode disaggregation endpoints', 'run_get_rdma_devices_args': 'run get_rdma_devices_args to resolve RDMA device arguments from environment variables, auto-detection, or fallback defaults'}
```

## File: sgl-project_sglang/python/sglang/test/server_fixtures/eagle_fixture.py

Prompts

```
['test the DefaultServerBase class that launches and manages an SGLang server process for integration tests', 'run the openai_api_env context manager to set OpenAI API key and base URL environment variables', 'run popen_launch_server to start an SGLang model server process in a subprocess', 'run kill_process_tree to terminate an SGLang server process and its child processes', 'run flush_cache to send a POST request to the /flush_cache endpoint of the running server', 'test the PDDisaggregationServerBase class and launch prefill, decode, and load balancer servers for disaggregation testing', 'test the PDDisaggregationServerBase class and start a prefill server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and start a decode server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and launch a load balancer for prefill and decode disaggregation endpoints', 'run get_rdma_devices_args to resolve RDMA device arguments from environment variables, auto-detection, or fallback defaults', 'test the EagleServerBase class to launch an SGLang server with EAGLE speculative decoding enabled', 'test the send_request method to send generation requests to the EAGLE server with temperature 0', 'test the send_requests_abort method to simulate client disconnection with a 1-second timeout', 'test the run_decode method to generate text with logprob return and custom sampling parameters', 'test the tearDownClass method to kill the EAGLE server process tree on cleanup', 'test the MMMUServerBase fixture class for launching and managing an SGLang VLM server with MMMU-specific settings', 'run the setUpClass method to launch an SGLang server with multimodal support and configurable mem_fraction_static', 'run the tearDownClass method to gracefully kill the SGLang server process and wait for cleanup', 'build a subclass of MMMUServerBase setting cls.model to launch a specific VLM for MMMU testing', 'review the MMMUServerBase server_args configuration including trust_remote_code, cuda_graph_max_bs, and enable_multimodal flags']
```

Usage

```
{'test_eagle_server_launch': 'test the EagleServerBase class to launch an SGLang server with EAGLE speculative decoding enabled', 'test_eagle_send_request': 'test the send_request method to send generation requests to the EAGLE server with temperature 0', 'test_eagle_send_requests_abort': 'test the send_requests_abort method to simulate client disconnection with a 1-second timeout', 'test_eagle_run_decode': 'test the run_decode method to generate text with logprob return and custom sampling parameters', 'test_eagle_server_teardown': 'test the tearDownClass method to kill the EAGLE server process tree on cleanup'}
```

## File: sgl-project_sglang/python/sglang/test/server_fixtures/mmmu_fixture.py

Prompts

```
['test the DefaultServerBase class that launches and manages an SGLang server process for integration tests', 'run the openai_api_env context manager to set OpenAI API key and base URL environment variables', 'run popen_launch_server to start an SGLang model server process in a subprocess', 'run kill_process_tree to terminate an SGLang server process and its child processes', 'run flush_cache to send a POST request to the /flush_cache endpoint of the running server', 'test the PDDisaggregationServerBase class and launch prefill, decode, and load balancer servers for disaggregation testing', 'test the PDDisaggregationServerBase class and start a prefill server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and start a decode server instance with disaggregation mode enabled', 'test the PDDisaggregationServerBase class and launch a load balancer for prefill and decode disaggregation endpoints', 'run get_rdma_devices_args to resolve RDMA device arguments from environment variables, auto-detection, or fallback defaults', 'test the EagleServerBase class to launch an SGLang server with EAGLE speculative decoding enabled', 'test the send_request method to send generation requests to the EAGLE server with temperature 0', 'test the send_requests_abort method to simulate client disconnection with a 1-second timeout', 'test the run_decode method to generate text with logprob return and custom sampling parameters', 'test the tearDownClass method to kill the EAGLE server process tree on cleanup', 'test the MMMUServerBase fixture class for launching and managing an SGLang VLM server with MMMU-specific settings', 'run the setUpClass method to launch an SGLang server with multimodal support and configurable mem_fraction_static', 'run the tearDownClass method to gracefully kill the SGLang server process and wait for cleanup', 'build a subclass of MMMUServerBase setting cls.model to launch a specific VLM for MMMU testing', 'review the MMMUServerBase server_args configuration including trust_remote_code, cuda_graph_max_bs, and enable_multimodal flags']
```

Usage

```
{'test_MMMUServerBase': 'test the MMMUServerBase fixture class for launching and managing an SGLang VLM server with MMMU-specific settings', 'run_MMMUServerBase_setUpClass': 'run the setUpClass method to launch an SGLang server with multimodal support and configurable mem_fraction_static', 'run_MMMUServerBase_tearDownClass': 'run the tearDownClass method to gracefully kill the SGLang server process and wait for cleanup', 'build_MMMUServerBase_subclass': 'build a subclass of MMMUServerBase setting cls.model to launch a specific VLM for MMMU testing', 'review_MMMUServerBase_server_args': 'review the MMMUServerBase server_args configuration including trust_remote_code, cuda_graph_max_bs, and enable_multimodal flags'}
```

