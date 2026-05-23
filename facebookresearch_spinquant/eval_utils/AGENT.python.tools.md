# Agent Python Tools

- repo: facebookresearch/spinquant
- repo_uri: https://github.com/facebookresearch/spinquant

## File: facebookresearch_spinquant/eval_utils/gptq_utils.py

Prompts

```
['run GPTQ quantization on a transformer model using a dataloader to collect input statistics layer by layer', 'run round-to-nearest quantization on a transformer model layers without collecting input activation statistics', 'create a GPTQ instance for a linear layer to prepare it for Hessian-based weight quantization', 'run the fasterquant method on a GPTQ instance to quantize layer weights with optional grouping and actorder', 'add a batch of input activations to the GPTQ Hessian matrix for second-order quantization statistics', 'run post-training quantization on a Llama model with weight and activation quantization', 'build a quantized Llama model using GPTQ or RTN weight quantization with configurable bit widths', 'create a model with weight rotation and Hadamard transforms for improved quantization accuracy', 'test the ptq_model function with different quantization bit widths for weights activations and keys', 'export a quantized Llama model to ExecutorCh format with sanitized checkpoint for deployment', 'build a LlamaForCausalLM model from config and run forward pass with input_ids to get logits', 'create a LlamaModel transformer decoder and pass input embeddings to get hidden states', 'test the LlamaForSequenceClassification model by running forward pass with labels to compute classification loss', 'review the LlamaForQuestionAnswering model forward pass that computes start and end span logits for extractive QA', 'refactor the LlamaRotaryEmbedding class to support a new rope_type scaling strategy for longer sequences', 'build a python module to rotate a transformer model using random or hadamard orthogonal matrices', 'create a function that generates a random orthogonal matrix via QR decomposition for a given size', 'test the QKRotationWrapper class to apply hadamard transform and quantize K-cache in attention layers', 'refactor the rotate_model function to load optimized rotation matrices from a checkpoint path', 'review the add_qk_rotation_wrapper_after_function_call_in_forward function to monkeypatch rotation into model forward pass']
```

Usage

```
{'run_gptq_quantization': 'run GPTQ quantization on a transformer model using a dataloader to collect input statistics layer by layer', 'run_rtn_quantization': 'run round-to-nearest quantization on a transformer model layers without collecting input activation statistics', 'create_GPTQ_instance': 'create a GPTQ instance for a linear layer to prepare it for Hessian-based weight quantization', 'run_fasterquant': 'run the fasterquant method on a GPTQ instance to quantize layer weights with optional grouping and actorder', 'add_batch_hessian': 'add a batch of input activations to the GPTQ Hessian matrix for second-order quantization statistics'}
```

## File: facebookresearch_spinquant/eval_utils/main.py

Prompts

```
['run GPTQ quantization on a transformer model using a dataloader to collect input statistics layer by layer', 'run round-to-nearest quantization on a transformer model layers without collecting input activation statistics', 'create a GPTQ instance for a linear layer to prepare it for Hessian-based weight quantization', 'run the fasterquant method on a GPTQ instance to quantize layer weights with optional grouping and actorder', 'add a batch of input activations to the GPTQ Hessian matrix for second-order quantization statistics', 'run post-training quantization on a Llama model with weight and activation quantization', 'build a quantized Llama model using GPTQ or RTN weight quantization with configurable bit widths', 'create a model with weight rotation and Hadamard transforms for improved quantization accuracy', 'test the ptq_model function with different quantization bit widths for weights activations and keys', 'export a quantized Llama model to ExecutorCh format with sanitized checkpoint for deployment', 'build a LlamaForCausalLM model from config and run forward pass with input_ids to get logits', 'create a LlamaModel transformer decoder and pass input embeddings to get hidden states', 'test the LlamaForSequenceClassification model by running forward pass with labels to compute classification loss', 'review the LlamaForQuestionAnswering model forward pass that computes start and end span logits for extractive QA', 'refactor the LlamaRotaryEmbedding class to support a new rope_type scaling strategy for longer sequences', 'build a python module to rotate a transformer model using random or hadamard orthogonal matrices', 'create a function that generates a random orthogonal matrix via QR decomposition for a given size', 'test the QKRotationWrapper class to apply hadamard transform and quantize K-cache in attention layers', 'refactor the rotate_model function to load optimized rotation matrices from a checkpoint path', 'review the add_qk_rotation_wrapper_after_function_call_in_forward function to monkeypatch rotation into model forward pass']
```

Usage

```
{'run_ptq_model': 'run post-training quantization on a Llama model with weight and activation quantization', 'build_quantized_model': 'build a quantized Llama model using GPTQ or RTN weight quantization with configurable bit widths', 'create_rotated_quantized_model': 'create a model with weight rotation and Hadamard transforms for improved quantization accuracy', 'test_ptq_quantization': 'test the ptq_model function with different quantization bit widths for weights activations and keys', 'export_executorch_model': 'export a quantized Llama model to ExecutorCh format with sanitized checkpoint for deployment'}
```

## File: facebookresearch_spinquant/eval_utils/modeling_llama.py

Prompts

```
['run GPTQ quantization on a transformer model using a dataloader to collect input statistics layer by layer', 'run round-to-nearest quantization on a transformer model layers without collecting input activation statistics', 'create a GPTQ instance for a linear layer to prepare it for Hessian-based weight quantization', 'run the fasterquant method on a GPTQ instance to quantize layer weights with optional grouping and actorder', 'add a batch of input activations to the GPTQ Hessian matrix for second-order quantization statistics', 'run post-training quantization on a Llama model with weight and activation quantization', 'build a quantized Llama model using GPTQ or RTN weight quantization with configurable bit widths', 'create a model with weight rotation and Hadamard transforms for improved quantization accuracy', 'test the ptq_model function with different quantization bit widths for weights activations and keys', 'export a quantized Llama model to ExecutorCh format with sanitized checkpoint for deployment', 'build a LlamaForCausalLM model from config and run forward pass with input_ids to get logits', 'create a LlamaModel transformer decoder and pass input embeddings to get hidden states', 'test the LlamaForSequenceClassification model by running forward pass with labels to compute classification loss', 'review the LlamaForQuestionAnswering model forward pass that computes start and end span logits for extractive QA', 'refactor the LlamaRotaryEmbedding class to support a new rope_type scaling strategy for longer sequences', 'build a python module to rotate a transformer model using random or hadamard orthogonal matrices', 'create a function that generates a random orthogonal matrix via QR decomposition for a given size', 'test the QKRotationWrapper class to apply hadamard transform and quantize K-cache in attention layers', 'refactor the rotate_model function to load optimized rotation matrices from a checkpoint path', 'review the add_qk_rotation_wrapper_after_function_call_in_forward function to monkeypatch rotation into model forward pass']
```

Usage

```
{'build_LlamaForCausalLM': 'build a LlamaForCausalLM model from config and run forward pass with input_ids to get logits', 'create_LlamaModel': 'create a LlamaModel transformer decoder and pass input embeddings to get hidden states', 'test_LlamaForSequenceClassification': 'test the LlamaForSequenceClassification model by running forward pass with labels to compute classification loss', 'review_LlamaForQuestionAnswering': 'review the LlamaForQuestionAnswering model forward pass that computes start and end span logits for extractive QA', 'refactor_LlamaRotaryEmbedding': 'refactor the LlamaRotaryEmbedding class to support a new rope_type scaling strategy for longer sequences'}
```

## File: facebookresearch_spinquant/eval_utils/rotation_utils.py

Prompts

```
['run GPTQ quantization on a transformer model using a dataloader to collect input statistics layer by layer', 'run round-to-nearest quantization on a transformer model layers without collecting input activation statistics', 'create a GPTQ instance for a linear layer to prepare it for Hessian-based weight quantization', 'run the fasterquant method on a GPTQ instance to quantize layer weights with optional grouping and actorder', 'add a batch of input activations to the GPTQ Hessian matrix for second-order quantization statistics', 'run post-training quantization on a Llama model with weight and activation quantization', 'build a quantized Llama model using GPTQ or RTN weight quantization with configurable bit widths', 'create a model with weight rotation and Hadamard transforms for improved quantization accuracy', 'test the ptq_model function with different quantization bit widths for weights activations and keys', 'export a quantized Llama model to ExecutorCh format with sanitized checkpoint for deployment', 'build a LlamaForCausalLM model from config and run forward pass with input_ids to get logits', 'create a LlamaModel transformer decoder and pass input embeddings to get hidden states', 'test the LlamaForSequenceClassification model by running forward pass with labels to compute classification loss', 'review the LlamaForQuestionAnswering model forward pass that computes start and end span logits for extractive QA', 'refactor the LlamaRotaryEmbedding class to support a new rope_type scaling strategy for longer sequences', 'build a python module to rotate a transformer model using random or hadamard orthogonal matrices', 'create a function that generates a random orthogonal matrix via QR decomposition for a given size', 'test the QKRotationWrapper class to apply hadamard transform and quantize K-cache in attention layers', 'refactor the rotate_model function to load optimized rotation matrices from a checkpoint path', 'review the add_qk_rotation_wrapper_after_function_call_in_forward function to monkeypatch rotation into model forward pass']
```

Usage

```
{'build_rotate_model': 'build a python module to rotate a transformer model using random or hadamard orthogonal matrices', 'create_orthogonal_matrix': 'create a function that generates a random orthogonal matrix via QR decomposition for a given size', 'test_QKRotationWrapper': 'test the QKRotationWrapper class to apply hadamard transform and quantize K-cache in attention layers', 'refactor_rotate_model': 'refactor the rotate_model function to load optimized rotation matrices from a checkpoint path', 'review_add_qk_rotation_wrapper': 'review the add_qk_rotation_wrapper_after_function_call_in_forward function to monkeypatch rotation into model forward pass'}
```

