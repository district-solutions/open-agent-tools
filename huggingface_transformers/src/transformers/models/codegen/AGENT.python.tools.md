# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/codegen/modeling_codegen.py

Prompts

```
['create a CodeGenForCausalLM model with a config for autoregressive code generation', 'build a CodeGenModel transformer with embedding layers and stacked CodeGenBlocks', 'run CodeGenAttention forward pass with QKV projection, rotary embeddings, and causal masking', 'test CodeGenMLP forward pass with fc_in, activation, fc_out, and dropout', 'review CodeGenBlock forward pass with layer norm, attention, and MLP residual connections', 'create a CodeGenTokenizer instance from a pretrained Salesforce CodeGen model for byte-level BPE tokenization', 'test tokenizing text strings into input_ids with the CodeGenTokenizer using byte-level BPE encoding', 'review the CodeGenTokenizer decode method that converts token_ids back to readable strings with optional truncation', 'summarize the CodeGenTokenizer truncate method that cuts generated code at terminal symbols like print, def, or comments', 'build a code completion pipeline using CodeGenTokenizer to encode prompts, decode model output, and truncate at code boundaries']
```

Usage

```
{'create_codegen_causal_lm': 'create a CodeGenForCausalLM model with a config for autoregressive code generation', 'build_codegen_model': 'build a CodeGenModel transformer with embedding layers and stacked CodeGenBlocks', 'run_codegen_attention': 'run CodeGenAttention forward pass with QKV projection, rotary embeddings, and causal masking', 'test_codegen_mlp': 'test CodeGenMLP forward pass with fc_in, activation, fc_out, and dropout', 'review_codegen_block': 'review CodeGenBlock forward pass with layer norm, attention, and MLP residual connections'}
```

## File: huggingface_transformers/src/transformers/models/codegen/tokenization_codegen.py

Prompts

```
['create a CodeGenForCausalLM model with a config for autoregressive code generation', 'build a CodeGenModel transformer with embedding layers and stacked CodeGenBlocks', 'run CodeGenAttention forward pass with QKV projection, rotary embeddings, and causal masking', 'test CodeGenMLP forward pass with fc_in, activation, fc_out, and dropout', 'review CodeGenBlock forward pass with layer norm, attention, and MLP residual connections', 'create a CodeGenTokenizer instance from a pretrained Salesforce CodeGen model for byte-level BPE tokenization', 'test tokenizing text strings into input_ids with the CodeGenTokenizer using byte-level BPE encoding', 'review the CodeGenTokenizer decode method that converts token_ids back to readable strings with optional truncation', 'summarize the CodeGenTokenizer truncate method that cuts generated code at terminal symbols like print, def, or comments', 'build a code completion pipeline using CodeGenTokenizer to encode prompts, decode model output, and truncate at code boundaries']
```

Usage

```
{'create_codegen_tokenizer': 'create a CodeGenTokenizer instance from a pretrained Salesforce CodeGen model for byte-level BPE tokenization', 'test_tokenize_text': 'test tokenizing text strings into input_ids with the CodeGenTokenizer using byte-level BPE encoding', 'review_decode_output': 'review the CodeGenTokenizer decode method that converts token_ids back to readable strings with optional truncation', 'summarize_truncate_method': 'summarize the CodeGenTokenizer truncate method that cuts generated code at terminal symbols like print, def, or comments', 'build_code_completion_pipeline': 'build a code completion pipeline using CodeGenTokenizer to encode prompts, decode model output, and truncate at code boundaries'}
```

