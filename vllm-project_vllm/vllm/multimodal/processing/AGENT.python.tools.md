# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/multimodal/processing/context.py

Prompts

```
['create a TimingContext to record and aggregate execution times for multi-modal processing stages', 'run InputProcessingContext.get_hf_processor to load a HuggingFace processor with merged config kwargs', 'build a call to InputProcessingContext.call_hf_processor to invoke a HuggingFace processor on multimodal data', 'test BaseProcessingInfo.parse_mm_data to parse and validate multimodal data items from a MultiModalDataDict', 'review BaseProcessingInfo.validate_num_items to enforce per-modality item count limits in a prompt', 'build dummy processor inputs for profiling multi-modal models with configurable sequence length and modality counts', 'generate dummy multimodal data with maximum placeholder tokens for profiling multi-modal models', 'generate dummy text input corresponding to specified multi-modal counts for model profiling', 'create dummy audio arrays with configurable length, count, and override options for model profiling', 'create dummy RGB images with configurable width, height, and override options for model profiling', 'create a ProcessorInputs dataclass instance with prompt, multimodal data items, and optional UUID items', 'build multimodal input hashes for a model by calling ProcessorInputs.get_mm_hashes with a model ID', 'test ProcessorInputs.get_mm_hashes returns per-modality hash lists from data items and UUID items', 'refactor MultiModalHasher.hash_kwargs to serialize multimodal items and compute deterministic hashes', 'summarize MultiModalHasher.iter_item_to_bytes recursive serialization of nested structures to byte streams', 'build a BaseMultiModalProcessor subclass to process multi-modal inputs for a vLLM model', 'create a PromptInsertion to insert placeholder tokens into a prompt at a specified target location', 'create a PromptReplacement to replace prompt tokens with multi-modal feature placeholder tokens', 'apply multi-modal prompt updates to a token sequence, inserting or replacing placeholder tokens', 'find multi-modal placeholder feature ranges within a processed token sequence']
```

Usage

```
{'create_TimingContext': 'create a TimingContext to record and aggregate execution times for multi-modal processing stages', 'run_InputProcessingContext_get_hf_processor': 'run InputProcessingContext.get_hf_processor to load a HuggingFace processor with merged config kwargs', 'build_InputProcessingContext_call_hf_processor': 'build a call to InputProcessingContext.call_hf_processor to invoke a HuggingFace processor on multimodal data', 'test_BaseProcessingInfo_parse_mm_data': 'test BaseProcessingInfo.parse_mm_data to parse and validate multimodal data items from a MultiModalDataDict', 'review_BaseProcessingInfo_validate_num_items': 'review BaseProcessingInfo.validate_num_items to enforce per-modality item count limits in a prompt'}
```

## File: vllm-project_vllm/vllm/multimodal/processing/dummy_inputs.py

Prompts

```
['create a TimingContext to record and aggregate execution times for multi-modal processing stages', 'run InputProcessingContext.get_hf_processor to load a HuggingFace processor with merged config kwargs', 'build a call to InputProcessingContext.call_hf_processor to invoke a HuggingFace processor on multimodal data', 'test BaseProcessingInfo.parse_mm_data to parse and validate multimodal data items from a MultiModalDataDict', 'review BaseProcessingInfo.validate_num_items to enforce per-modality item count limits in a prompt', 'build dummy processor inputs for profiling multi-modal models with configurable sequence length and modality counts', 'generate dummy multimodal data with maximum placeholder tokens for profiling multi-modal models', 'generate dummy text input corresponding to specified multi-modal counts for model profiling', 'create dummy audio arrays with configurable length, count, and override options for model profiling', 'create dummy RGB images with configurable width, height, and override options for model profiling', 'create a ProcessorInputs dataclass instance with prompt, multimodal data items, and optional UUID items', 'build multimodal input hashes for a model by calling ProcessorInputs.get_mm_hashes with a model ID', 'test ProcessorInputs.get_mm_hashes returns per-modality hash lists from data items and UUID items', 'refactor MultiModalHasher.hash_kwargs to serialize multimodal items and compute deterministic hashes', 'summarize MultiModalHasher.iter_item_to_bytes recursive serialization of nested structures to byte streams', 'build a BaseMultiModalProcessor subclass to process multi-modal inputs for a vLLM model', 'create a PromptInsertion to insert placeholder tokens into a prompt at a specified target location', 'create a PromptReplacement to replace prompt tokens with multi-modal feature placeholder tokens', 'apply multi-modal prompt updates to a token sequence, inserting or replacing placeholder tokens', 'find multi-modal placeholder feature ranges within a processed token sequence']
```

Usage

```
{'build_dummy_processor_inputs': 'build dummy processor inputs for profiling multi-modal models with configurable sequence length and modality counts', 'generate_dummy_mm_data': 'generate dummy multimodal data with maximum placeholder tokens for profiling multi-modal models', 'generate_dummy_text': 'generate dummy text input corresponding to specified multi-modal counts for model profiling', 'create_dummy_audios': 'create dummy audio arrays with configurable length, count, and override options for model profiling', 'create_dummy_images': 'create dummy RGB images with configurable width, height, and override options for model profiling'}
```

## File: vllm-project_vllm/vllm/multimodal/processing/inputs.py

Prompts

```
['create a TimingContext to record and aggregate execution times for multi-modal processing stages', 'run InputProcessingContext.get_hf_processor to load a HuggingFace processor with merged config kwargs', 'build a call to InputProcessingContext.call_hf_processor to invoke a HuggingFace processor on multimodal data', 'test BaseProcessingInfo.parse_mm_data to parse and validate multimodal data items from a MultiModalDataDict', 'review BaseProcessingInfo.validate_num_items to enforce per-modality item count limits in a prompt', 'build dummy processor inputs for profiling multi-modal models with configurable sequence length and modality counts', 'generate dummy multimodal data with maximum placeholder tokens for profiling multi-modal models', 'generate dummy text input corresponding to specified multi-modal counts for model profiling', 'create dummy audio arrays with configurable length, count, and override options for model profiling', 'create dummy RGB images with configurable width, height, and override options for model profiling', 'create a ProcessorInputs dataclass instance with prompt, multimodal data items, and optional UUID items', 'build multimodal input hashes for a model by calling ProcessorInputs.get_mm_hashes with a model ID', 'test ProcessorInputs.get_mm_hashes returns per-modality hash lists from data items and UUID items', 'refactor MultiModalHasher.hash_kwargs to serialize multimodal items and compute deterministic hashes', 'summarize MultiModalHasher.iter_item_to_bytes recursive serialization of nested structures to byte streams', 'build a BaseMultiModalProcessor subclass to process multi-modal inputs for a vLLM model', 'create a PromptInsertion to insert placeholder tokens into a prompt at a specified target location', 'create a PromptReplacement to replace prompt tokens with multi-modal feature placeholder tokens', 'apply multi-modal prompt updates to a token sequence, inserting or replacing placeholder tokens', 'find multi-modal placeholder feature ranges within a processed token sequence']
```

Usage

```
{'create_dataclass_ProcessorInputs': 'create a ProcessorInputs dataclass instance with prompt, multimodal data items, and optional UUID items', 'build_mm_hashes_ProcessorInputs': 'build multimodal input hashes for a model by calling ProcessorInputs.get_mm_hashes with a model ID', 'test_get_mm_hashes_ProcessorInputs': 'test ProcessorInputs.get_mm_hashes returns per-modality hash lists from data items and UUID items', 'refactor_hash_kwargs_MultiModalHasher': 'refactor MultiModalHasher.hash_kwargs to serialize multimodal items and compute deterministic hashes', 'summarize_iter_item_to_bytes_MultiModalHasher': 'summarize MultiModalHasher.iter_item_to_bytes recursive serialization of nested structures to byte streams'}
```

## File: vllm-project_vllm/vllm/multimodal/processing/processor.py

Prompts

```
['create a TimingContext to record and aggregate execution times for multi-modal processing stages', 'run InputProcessingContext.get_hf_processor to load a HuggingFace processor with merged config kwargs', 'build a call to InputProcessingContext.call_hf_processor to invoke a HuggingFace processor on multimodal data', 'test BaseProcessingInfo.parse_mm_data to parse and validate multimodal data items from a MultiModalDataDict', 'review BaseProcessingInfo.validate_num_items to enforce per-modality item count limits in a prompt', 'build dummy processor inputs for profiling multi-modal models with configurable sequence length and modality counts', 'generate dummy multimodal data with maximum placeholder tokens for profiling multi-modal models', 'generate dummy text input corresponding to specified multi-modal counts for model profiling', 'create dummy audio arrays with configurable length, count, and override options for model profiling', 'create dummy RGB images with configurable width, height, and override options for model profiling', 'create a ProcessorInputs dataclass instance with prompt, multimodal data items, and optional UUID items', 'build multimodal input hashes for a model by calling ProcessorInputs.get_mm_hashes with a model ID', 'test ProcessorInputs.get_mm_hashes returns per-modality hash lists from data items and UUID items', 'refactor MultiModalHasher.hash_kwargs to serialize multimodal items and compute deterministic hashes', 'summarize MultiModalHasher.iter_item_to_bytes recursive serialization of nested structures to byte streams', 'build a BaseMultiModalProcessor subclass to process multi-modal inputs for a vLLM model', 'create a PromptInsertion to insert placeholder tokens into a prompt at a specified target location', 'create a PromptReplacement to replace prompt tokens with multi-modal feature placeholder tokens', 'apply multi-modal prompt updates to a token sequence, inserting or replacing placeholder tokens', 'find multi-modal placeholder feature ranges within a processed token sequence']
```

Usage

```
{'build_multimodal_processor': 'build a BaseMultiModalProcessor subclass to process multi-modal inputs for a vLLM model', 'create_prompt_insertion': 'create a PromptInsertion to insert placeholder tokens into a prompt at a specified target location', 'create_prompt_replacement': 'create a PromptReplacement to replace prompt tokens with multi-modal feature placeholder tokens', 'apply_prompt_updates': 'apply multi-modal prompt updates to a token sequence, inserting or replacing placeholder tokens', 'find_mm_placeholders': 'find multi-modal placeholder feature ranges within a processed token sequence'}
```

