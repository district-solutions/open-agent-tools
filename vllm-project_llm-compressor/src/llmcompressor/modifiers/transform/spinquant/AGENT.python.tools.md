# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/transform/spinquant/base.py

Prompts

```
['create a SpinQuantModifier to apply learned rotation transforms for LLM quantization', 'run SpinQuantModifier on_initialize to infer mappings and create transform schemes for R1, R2, R3, R4', 'apply SpinQuantModifier on_start to center embeddings, fuse norms, and apply transform config to a model', 'build a SpinQuantRotation enum with R1, R2, R3, R4 rotation types for offline and online transforms', 'test SpinQuantModifier on_event to handle calibration epoch start and end events', 'create a SpinQuantMapping instance with embedding, attention, and MLP layer patterns for quantization', 'build default SpinQuantMapping with regex patterns for Llama model architecture layers', 'test infer_mapping_from_model to resolve a model architecture to its SpinQuantMapping', 'review the SPINQUANT_MAPPING_REGISTRY dictionary mapping model architectures to SpinQuantMapping', 'summarize the SpinQuantMapping pydantic model fields and their roles in layer rotation mapping', 'create a NormMapping instance with norm regex and linear layer regexes for SpinQuant', 'build a NORM_MAPPING_REGISTRY mapping model architectures to norm-to-linear mappings', 'test infer_norm_mapping_from_model with a PreTrainedModel to get norm mappings', 'refactor NormMapping to support additional field validators beyond linears casting', 'summarize how norm_mappings.py maps norm layers to subsequent linear layers in transformer models']
```

Usage

```
{'create_SpinQuantModifier': 'create a SpinQuantModifier to apply learned rotation transforms for LLM quantization', 'run_SpinQuantModifier_on_initialize': 'run SpinQuantModifier on_initialize to infer mappings and create transform schemes for R1, R2, R3, R4', 'apply_SpinQuantModifier_on_start': 'apply SpinQuantModifier on_start to center embeddings, fuse norms, and apply transform config to a model', 'build_SpinQuantRotation_enum': 'build a SpinQuantRotation enum with R1, R2, R3, R4 rotation types for offline and online transforms', 'test_SpinQuantModifier_on_event': 'test SpinQuantModifier on_event to handle calibration epoch start and end events'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/transform/spinquant/mappings.py

Prompts

```
['create a SpinQuantModifier to apply learned rotation transforms for LLM quantization', 'run SpinQuantModifier on_initialize to infer mappings and create transform schemes for R1, R2, R3, R4', 'apply SpinQuantModifier on_start to center embeddings, fuse norms, and apply transform config to a model', 'build a SpinQuantRotation enum with R1, R2, R3, R4 rotation types for offline and online transforms', 'test SpinQuantModifier on_event to handle calibration epoch start and end events', 'create a SpinQuantMapping instance with embedding, attention, and MLP layer patterns for quantization', 'build default SpinQuantMapping with regex patterns for Llama model architecture layers', 'test infer_mapping_from_model to resolve a model architecture to its SpinQuantMapping', 'review the SPINQUANT_MAPPING_REGISTRY dictionary mapping model architectures to SpinQuantMapping', 'summarize the SpinQuantMapping pydantic model fields and their roles in layer rotation mapping', 'create a NormMapping instance with norm regex and linear layer regexes for SpinQuant', 'build a NORM_MAPPING_REGISTRY mapping model architectures to norm-to-linear mappings', 'test infer_norm_mapping_from_model with a PreTrainedModel to get norm mappings', 'refactor NormMapping to support additional field validators beyond linears casting', 'summarize how norm_mappings.py maps norm layers to subsequent linear layers in transformer models']
```

Usage

```
{'create_SpinQuantMapping': 'create a SpinQuantMapping instance with embedding, attention, and MLP layer patterns for quantization', 'build_default_mappings': 'build default SpinQuantMapping with regex patterns for Llama model architecture layers', 'test_infer_mapping_from_model': 'test infer_mapping_from_model to resolve a model architecture to its SpinQuantMapping', 'review_SPINQUANT_MAPPING_REGISTRY': 'review the SPINQUANT_MAPPING_REGISTRY dictionary mapping model architectures to SpinQuantMapping', 'summarize_SpinQuantMapping': 'summarize the SpinQuantMapping pydantic model fields and their roles in layer rotation mapping'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/transform/spinquant/norm_mappings.py

Prompts

```
['create a SpinQuantModifier to apply learned rotation transforms for LLM quantization', 'run SpinQuantModifier on_initialize to infer mappings and create transform schemes for R1, R2, R3, R4', 'apply SpinQuantModifier on_start to center embeddings, fuse norms, and apply transform config to a model', 'build a SpinQuantRotation enum with R1, R2, R3, R4 rotation types for offline and online transforms', 'test SpinQuantModifier on_event to handle calibration epoch start and end events', 'create a SpinQuantMapping instance with embedding, attention, and MLP layer patterns for quantization', 'build default SpinQuantMapping with regex patterns for Llama model architecture layers', 'test infer_mapping_from_model to resolve a model architecture to its SpinQuantMapping', 'review the SPINQUANT_MAPPING_REGISTRY dictionary mapping model architectures to SpinQuantMapping', 'summarize the SpinQuantMapping pydantic model fields and their roles in layer rotation mapping', 'create a NormMapping instance with norm regex and linear layer regexes for SpinQuant', 'build a NORM_MAPPING_REGISTRY mapping model architectures to norm-to-linear mappings', 'test infer_norm_mapping_from_model with a PreTrainedModel to get norm mappings', 'refactor NormMapping to support additional field validators beyond linears casting', 'summarize how norm_mappings.py maps norm layers to subsequent linear layers in transformer models']
```

Usage

```
{'create_NormMapping': 'create a NormMapping instance with norm regex and linear layer regexes for SpinQuant', 'build_norm_mapping_registry': 'build a NORM_MAPPING_REGISTRY mapping model architectures to norm-to-linear mappings', 'test_infer_norm_mapping': 'test infer_norm_mapping_from_model with a PreTrainedModel to get norm mappings', 'refactor_NormMapping_validator': 'refactor NormMapping to support additional field validators beyond linears casting', 'summarize_norm_mappings': 'summarize how norm_mappings.py maps norm layers to subsequent linear layers in transformer models'}
```

