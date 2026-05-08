# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/ram/data.py

Prompts

```
['create a Dataset by importing any JSONL file or directory of JSONL files using ImportAnyJSONL', 'export dataset examples to sharded JSONL files with source and target keys using ExportSrcTgtJSONLData', 'export dataset examples wrapped with a HuggingFace tokenizer chat template for vLLM inference using ExportVLLMGenerationData', 'load a prompt template from a file and apply it to dataset examples using load_prompt_template', 'import instruction data from a JSONL file with INST tokens and split into input and label using ImportInstructionData', 'download a file from a URL to a directory with SHA256 checksum verification and auto-extraction', 'wrap a text prompt with a HuggingFace tokenizer chat template including optional system prompt', 'load data from a JSONL file into a list of dicts or save a list of dicts to JSONL', 'generate a deterministic UUID v5 hash from a string for mapping prompts or sequences to unique IDs', 'extract the winner label from an LLM judge generation string using bracket notation like [[A]] or [[B]]']
```

Usage

```
{'create_dataset_from_jsonl': 'create a Dataset by importing any JSONL file or directory of JSONL files using ImportAnyJSONL', 'export_src_tgt_jsonl': 'export dataset examples to sharded JSONL files with source and target keys using ExportSrcTgtJSONLData', 'export_vllm_generation_data': 'export dataset examples wrapped with a HuggingFace tokenizer chat template for vLLM inference using ExportVLLMGenerationData', 'load_prompt_template': 'load a prompt template from a file and apply it to dataset examples using load_prompt_template', 'import_instruction_data': 'import instruction data from a JSONL file with INST tokens and split into input and label using ImportInstructionData'}
```

## File: facebookresearch_ram/ram/data_utils.py

Prompts

```
['create a Dataset by importing any JSONL file or directory of JSONL files using ImportAnyJSONL', 'export dataset examples to sharded JSONL files with source and target keys using ExportSrcTgtJSONLData', 'export dataset examples wrapped with a HuggingFace tokenizer chat template for vLLM inference using ExportVLLMGenerationData', 'load a prompt template from a file and apply it to dataset examples using load_prompt_template', 'import instruction data from a JSONL file with INST tokens and split into input and label using ImportInstructionData', 'download a file from a URL to a directory with SHA256 checksum verification and auto-extraction', 'wrap a text prompt with a HuggingFace tokenizer chat template including optional system prompt', 'load data from a JSONL file into a list of dicts or save a list of dicts to JSONL', 'generate a deterministic UUID v5 hash from a string for mapping prompts or sequences to unique IDs', 'extract the winner label from an LLM judge generation string using bracket notation like [[A]] or [[B]]']
```

Usage

```
{'download_file_with_checksum': 'download a file from a URL to a directory with SHA256 checksum verification and auto-extraction', 'wrap_text_with_chat_template': 'wrap a text prompt with a HuggingFace tokenizer chat template including optional system prompt', 'load_and_save_jsonl': 'load data from a JSONL file into a list of dicts or save a list of dicts to JSONL', 'map_str_to_uuid': 'generate a deterministic UUID v5 hash from a string for mapping prompts or sequences to unique IDs', 'extract_winner_llm_judge_pairv2': 'extract the winner label from an LLM judge generation string using bracket notation like [[A]] or [[B]]'}
```

