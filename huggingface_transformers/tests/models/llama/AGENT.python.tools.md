# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/llama/test_modeling_llama.py

Prompts

```
['test the LlamaForCausalLM model generates expected text for a french revolution prompt', 'test the LlamaForCausalLM model outputs correct logits in bfloat16 precision on various accelerators', 'test the LlamaForCausalLM model outputs correct logits in float16 precision on various accelerators', 'test the LlamaForCausalLM model with torch compile and static cache produces expected text completions', 'test exporting LlamaForCausalLM with static cache to TorchExportableModuleForDecoderOnlyLM and generating text', 'test the LlamaTokenizer by encoding text to tokens and decoding back to original text', 'test loading a Llama tokenizer from a tiktoken model file using AutoTokenizer or LlamaTokenizer', 'test that BPE tokenization preserves spaces around punctuation in Llama 3 tokenizer', 'test loading a pretrained Llama tokenizer from Hugging Face model hub', 'test Llama tokenizer integration with expected token outputs and decoded text']
```

Usage

```
{'test_llama_generation': 'test the LlamaForCausalLM model generates expected text for a french revolution prompt', 'test_model_logits_bf16': 'test the LlamaForCausalLM model outputs correct logits in bfloat16 precision on various accelerators', 'test_model_logits_fp16': 'test the LlamaForCausalLM model outputs correct logits in float16 precision on various accelerators', 'test_compile_static_cache': 'test the LlamaForCausalLM model with torch compile and static cache produces expected text completions', 'test_export_static_cache': 'test exporting LlamaForCausalLM with static cache to TorchExportableModuleForDecoderOnlyLM and generating text'}
```

## File: huggingface_transformers/tests/models/llama/test_tokenization_llama.py

Prompts

```
['test the LlamaForCausalLM model generates expected text for a french revolution prompt', 'test the LlamaForCausalLM model outputs correct logits in bfloat16 precision on various accelerators', 'test the LlamaForCausalLM model outputs correct logits in float16 precision on various accelerators', 'test the LlamaForCausalLM model with torch compile and static cache produces expected text completions', 'test exporting LlamaForCausalLM with static cache to TorchExportableModuleForDecoderOnlyLM and generating text', 'test the LlamaTokenizer by encoding text to tokens and decoding back to original text', 'test loading a Llama tokenizer from a tiktoken model file using AutoTokenizer or LlamaTokenizer', 'test that BPE tokenization preserves spaces around punctuation in Llama 3 tokenizer', 'test loading a pretrained Llama tokenizer from Hugging Face model hub', 'test Llama tokenizer integration with expected token outputs and decoded text']
```

Usage

```
{'test_llama_tokenizer_encode_decode': 'test the LlamaTokenizer by encoding text to tokens and decoding back to original text', 'test_load_tiktoken_tokenizer': 'test loading a Llama tokenizer from a tiktoken model file using AutoTokenizer or LlamaTokenizer', 'test_bpe_space_preservation': 'test that BPE tokenization preserves spaces around punctuation in Llama 3 tokenizer', 'test_tokenizer_from_pretrained': 'test loading a pretrained Llama tokenizer from Hugging Face model hub', 'test_tokenizer_integration': 'test Llama tokenizer integration with expected token outputs and decoded text'}
```

