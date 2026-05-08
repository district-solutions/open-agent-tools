# Agent Python Tools

- repo: facebookresearch/llm-transparency-tool
- repo_uri: https://github.com/facebookresearch/llm-transparency-tool

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/models/test_tlens_model.py

Prompts

```
['run a TransformerLensTransparentLlm model on a list of text prompts and inspect internal activations', 'test the TransformerLensTransparentLlm model_info method to verify name, layers, heads, and vocabulary size', 'test that residual_in of each layer matches the residual_out of the previous layer', 'test that residual output equals residual input plus attention and FFN block outputs', 'test that all internal tensors like logits, neuron activations, and attention matrices have correct shapes', 'load a HookedTransformer model from a HuggingFace model name with optional device and dtype settings', 'get the residual stream activations at the input, mid, or output of a specific transformer layer', 'compute the decomposed feed-forward network output for a specific batch, layer, and position by multiplying activations with W_out', 'compute the decomposed attention output per head and position using value vectors, attention patterns, and the W_O weight matrix', 'implement a subclass of TransparentLlm that loads a model and provides internal activations', 'run inference on sentences using a TransparentLlm subclass and access stored internal state', 'inspect the residual stream at a given layer using residual_in or residual_out methods', 'analyze attention patterns by calling attention_matrix on a specific batch, layer, and head', 'decompose FFN output into per-neuron contributions using decomposed_ffn_out and neuron_activations']
```

Usage

```
{'run_TransformerLensTransparentLlm': 'run a TransformerLensTransparentLlm model on a list of text prompts and inspect internal activations', 'test_model_info': 'test the TransformerLensTransparentLlm model_info method to verify name, layers, heads, and vocabulary size', 'test_residual_in_and_out': 'test that residual_in of each layer matches the residual_out of the previous layer', 'test_residual_plus_block': 'test that residual output equals residual input plus attention and FFN block outputs', 'test_tensor_shapes': 'test that all internal tensors like logits, neuron activations, and attention matrices have correct shapes'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/models/tlens_model.py

Prompts

```
['run a TransformerLensTransparentLlm model on a list of text prompts and inspect internal activations', 'test the TransformerLensTransparentLlm model_info method to verify name, layers, heads, and vocabulary size', 'test that residual_in of each layer matches the residual_out of the previous layer', 'test that residual output equals residual input plus attention and FFN block outputs', 'test that all internal tensors like logits, neuron activations, and attention matrices have correct shapes', 'load a HookedTransformer model from a HuggingFace model name with optional device and dtype settings', 'get the residual stream activations at the input, mid, or output of a specific transformer layer', 'compute the decomposed feed-forward network output for a specific batch, layer, and position by multiplying activations with W_out', 'compute the decomposed attention output per head and position using value vectors, attention patterns, and the W_O weight matrix', 'implement a subclass of TransparentLlm that loads a model and provides internal activations', 'run inference on sentences using a TransparentLlm subclass and access stored internal state', 'inspect the residual stream at a given layer using residual_in or residual_out methods', 'analyze attention patterns by calling attention_matrix on a specific batch, layer, and head', 'decompose FFN output into per-neuron contributions using decomposed_ffn_out and neuron_activations']
```

Usage

```
{'load_hooked_transformer': 'load a HookedTransformer model from a HuggingFace model name with optional device and dtype settings', 'run_TransformerLensTransparentLlm': 'run a list of sentences through the TransformerLensTransparentLlm model to get tokens, logits, and activation cache', 'residual_in_out_TransformerLensTransparentLlm': 'get the residual stream activations at the input, mid, or output of a specific transformer layer', 'decomposed_ffn_out_TransformerLensTransparentLlm': 'compute the decomposed feed-forward network output for a specific batch, layer, and position by multiplying activations with W_out', 'decomposed_attn_TransformerLensTransparentLlm': 'compute the decomposed attention output per head and position using value vectors, attention patterns, and the W_O weight matrix'}
```

## File: facebookresearch_llm-transparency-tool/llm_transparency_tool/models/transparent_llm.py

Prompts

```
['run a TransformerLensTransparentLlm model on a list of text prompts and inspect internal activations', 'test the TransformerLensTransparentLlm model_info method to verify name, layers, heads, and vocabulary size', 'test that residual_in of each layer matches the residual_out of the previous layer', 'test that residual output equals residual input plus attention and FFN block outputs', 'test that all internal tensors like logits, neuron activations, and attention matrices have correct shapes', 'load a HookedTransformer model from a HuggingFace model name with optional device and dtype settings', 'get the residual stream activations at the input, mid, or output of a specific transformer layer', 'compute the decomposed feed-forward network output for a specific batch, layer, and position by multiplying activations with W_out', 'compute the decomposed attention output per head and position using value vectors, attention patterns, and the W_O weight matrix', 'implement a subclass of TransparentLlm that loads a model and provides internal activations', 'run inference on sentences using a TransparentLlm subclass and access stored internal state', 'inspect the residual stream at a given layer using residual_in or residual_out methods', 'analyze attention patterns by calling attention_matrix on a specific batch, layer, and head', 'decompose FFN output into per-neuron contributions using decomposed_ffn_out and neuron_activations']
```

Usage

```
{'implement_TransparentLlm_subclass': 'implement a subclass of TransparentLlm that loads a model and provides internal activations', 'run_inference_with_TransparentLlm': 'run inference on sentences using a TransparentLlm subclass and access stored internal state', 'inspect_residual_stream': 'inspect the residual stream at a given layer using residual_in or residual_out methods', 'analyze_attention_patterns': 'analyze attention patterns by calling attention_matrix on a specific batch, layer, and head', 'decompose_ffn_contributions': 'decompose FFN output into per-neuron contributions using decomposed_ffn_out and neuron_activations'}
```

