# Agent Python Tools

- repo: huggingface/trl
- repo_uri: https://github.com/huggingface/trl.git

## File: huggingface_trl/trl/experimental/merge_model_callback.py

Prompts

```
['create a linear merge configuration for two models with specified weights using MergeConfig', 'create a TIES merge configuration for two models with density parameters using MergeConfig', 'create a SLERP merge configuration for spherical linear interpolation of two models', 'merge two models using mergekit with a MergeConfiguration and output path', 'upload a merged model folder to a Hugging Face Hub repository', 'create a DPO data collator that pads tokenized inputs to the maximum batch length for DPO training', 'create a ChatML data collator that formats message lists into padded input_ids, attention_mask, and labels for chat models', 'create a static frozen reference copy of a model with optional shared layers for DPO or KTO training', 'prepare a model for PEFT training by enabling gradient checkpointing, handling QLoRA, and wrapping with get_peft_model', 'truncate sequences in a dataset to a specified maximum length using PyArrow batch operations']
```

Usage

```
{'create_merge_config_linear': 'create a linear merge configuration for two models with specified weights using MergeConfig', 'create_merge_config_ties': 'create a TIES merge configuration for two models with density parameters using MergeConfig', 'create_merge_config_slerp': 'create a SLERP merge configuration for spherical linear interpolation of two models', 'merge_models': 'merge two models using mergekit with a MergeConfiguration and output path', 'upload_model_to_hf': 'upload a merged model folder to a Hugging Face Hub repository'}
```

## File: huggingface_trl/trl/experimental/utils.py

Prompts

```
['create a linear merge configuration for two models with specified weights using MergeConfig', 'create a TIES merge configuration for two models with density parameters using MergeConfig', 'create a SLERP merge configuration for spherical linear interpolation of two models', 'merge two models using mergekit with a MergeConfiguration and output path', 'upload a merged model folder to a Hugging Face Hub repository', 'create a DPO data collator that pads tokenized inputs to the maximum batch length for DPO training', 'create a ChatML data collator that formats message lists into padded input_ids, attention_mask, and labels for chat models', 'create a static frozen reference copy of a model with optional shared layers for DPO or KTO training', 'prepare a model for PEFT training by enabling gradient checkpointing, handling QLoRA, and wrapping with get_peft_model', 'truncate sequences in a dataset to a specified maximum length using PyArrow batch operations']
```

Usage

```
{'create_DPODataCollatorWithPadding': 'create a DPO data collator that pads tokenized inputs to the maximum batch length for DPO training', 'create_DataCollatorForChatML': 'create a ChatML data collator that formats message lists into padded input_ids, attention_mask, and labels for chat models', 'create_create_reference_model': 'create a static frozen reference copy of a model with optional shared layers for DPO or KTO training', 'create_prepare_peft_model': 'prepare a model for PEFT training by enabling gradient checkpointing, handling QLoRA, and wrapping with get_peft_model', 'create_truncate_dataset': 'truncate sequences in a dataset to a specified maximum length using PyArrow batch operations'}
```

