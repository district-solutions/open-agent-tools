# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/offline_inference/disaggregated-prefill-v1/decode_example.py

Prompts

```
['run the main function to perform disaggregated prefill inference with Llama-3.2-1B-Instruct', 'read prompts line-by-line from output.txt and return them as a list of strings', 'create a SamplingParams object with temperature 0, top_p 0.95, and max_tokens 10', 'build an LLM instance with KVTransferConfig for disaggregated prefill using ExampleConnector', 'generate text outputs from prompts using llm.generate with SamplingParams', 'create an LLM instance with KVTransferConfig for disaggregated prefill using ExampleConnector', 'run llm.generate with prompts and sampling_params to produce disaggregated prefill outputs', 'summarize the read_prompts function that generates context-padded prompts for disaggregated prefill testing']
```

Usage

```
{'run_main_disaggregated_prefill': 'run the main function to perform disaggregated prefill inference with Llama-3.2-1B-Instruct', 'read_prompts_from_file': 'read prompts line-by-line from output.txt and return them as a list of strings', 'create_sampling_params': 'create a SamplingParams object with temperature 0, top_p 0.95, and max_tokens 10', 'build_llm_with_kv_transfer': 'build an LLM instance with KVTransferConfig for disaggregated prefill using ExampleConnector', 'generate_text_outputs': 'generate text outputs from prompts using llm.generate with SamplingParams'}
```

## File: vllm-project_vllm/examples/offline_inference/disaggregated-prefill-v1/prefill_example.py

Prompts

```
['run the main function to perform disaggregated prefill inference with Llama-3.2-1B-Instruct', 'read prompts line-by-line from output.txt and return them as a list of strings', 'create a SamplingParams object with temperature 0, top_p 0.95, and max_tokens 10', 'build an LLM instance with KVTransferConfig for disaggregated prefill using ExampleConnector', 'generate text outputs from prompts using llm.generate with SamplingParams', 'create an LLM instance with KVTransferConfig for disaggregated prefill using ExampleConnector', 'run llm.generate with prompts and sampling_params to produce disaggregated prefill outputs', 'summarize the read_prompts function that generates context-padded prompts for disaggregated prefill testing']
```

Usage

```
{'run_main_disaggregated_prefill': 'run the main function to execute disaggregated prefill inference with vLLM', 'create_sampling_params': 'create SamplingParams with temperature 0, top_p 0.95, and max_tokens 1 for deterministic generation', 'create_llm_disaggregated': 'create an LLM instance with KVTransferConfig for disaggregated prefill using ExampleConnector', 'run_llm_generate': 'run llm.generate with prompts and sampling_params to produce disaggregated prefill outputs', 'summarize_read_prompts': 'summarize the read_prompts function that generates context-padded prompts for disaggregated prefill testing'}
```

