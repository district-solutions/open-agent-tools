# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/configs/models/encoders/flux_2.py

Prompts

```
['build FLUX.2 text messages from a list of prompts by cleaning [IMG] placeholders and wrapping each with a system message', 'create a Flux2MistralTextArchConfig dataclass with stacked params mapping for qkv_proj and tokenizer kwargs for max_length 512', 'create a Flux2MistralTextConfig dataclass with default Flux2MistralTextArchConfig and prefix flux_2_mistral', 'test build_flux2_text_messages returns a list of message dicts with system and user roles for each prompt', 'review the Flux2MistralTextArchConfig dataclass stacked_params_mapping and __post_init__ tokenizer_kwargs setup', 'create a T5ArchConfig dataclass instance with T5 encoder architecture defaults', 'create a T5Config dataclass instance wrapping T5ArchConfig with parallel folding settings', 'build FSDP shard conditions using transformer layer, embeddings, and final layernorm predicates', 'build tokenizer kwargs dict with max_length padding, truncation, and attention mask from T5ArchConfig', 'run T5Config.add_cli_args to register T5 encoder CLI arguments on an argparse parser']
```

Usage

```
{'build_flux2_text_messages': 'build FLUX.2 text messages from a list of prompts by cleaning [IMG] placeholders and wrapping each with a system message', 'create_Flux2MistralTextArchConfig': 'create a Flux2MistralTextArchConfig dataclass with stacked params mapping for qkv_proj and tokenizer kwargs for max_length 512', 'create_Flux2MistralTextConfig': 'create a Flux2MistralTextConfig dataclass with default Flux2MistralTextArchConfig and prefix flux_2_mistral', 'test_build_flux2_text_messages': 'test build_flux2_text_messages returns a list of message dicts with system and user roles for each prompt', 'review_Flux2MistralTextArchConfig': 'review the Flux2MistralTextArchConfig dataclass stacked_params_mapping and __post_init__ tokenizer_kwargs setup'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/configs/models/encoders/t5.py

Prompts

```
['build FLUX.2 text messages from a list of prompts by cleaning [IMG] placeholders and wrapping each with a system message', 'create a Flux2MistralTextArchConfig dataclass with stacked params mapping for qkv_proj and tokenizer kwargs for max_length 512', 'create a Flux2MistralTextConfig dataclass with default Flux2MistralTextArchConfig and prefix flux_2_mistral', 'test build_flux2_text_messages returns a list of message dicts with system and user roles for each prompt', 'review the Flux2MistralTextArchConfig dataclass stacked_params_mapping and __post_init__ tokenizer_kwargs setup', 'create a T5ArchConfig dataclass instance with T5 encoder architecture defaults', 'create a T5Config dataclass instance wrapping T5ArchConfig with parallel folding settings', 'build FSDP shard conditions using transformer layer, embeddings, and final layernorm predicates', 'build tokenizer kwargs dict with max_length padding, truncation, and attention mask from T5ArchConfig', 'run T5Config.add_cli_args to register T5 encoder CLI arguments on an argparse parser']
```

Usage

```
{'create_T5ArchConfig': 'create a T5ArchConfig dataclass instance with T5 encoder architecture defaults', 'create_T5Config': 'create a T5Config dataclass instance wrapping T5ArchConfig with parallel folding settings', 'build_T5_shard_conditions': 'build FSDP shard conditions using transformer layer, embeddings, and final layernorm predicates', 'build_tokenizer_kwargs': 'build tokenizer kwargs dict with max_length padding, truncation, and attention mask from T5ArchConfig', 'run_T5_cli_args': 'run T5Config.add_cli_args to register T5 encoder CLI arguments on an argparse parser'}
```

