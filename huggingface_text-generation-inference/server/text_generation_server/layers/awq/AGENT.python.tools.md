# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/layers/awq/conversion_utils.py

Prompts

```
['convert AWQ quantized model weights and zeros to GPTQ format using fast_awq_to_gptq', 'pack a 4-bit integer tensor into a 32-bit packed tensor using the pack function', 'unpack a 32-bit packed tensor back into a 4-bit integer tensor using the unpack function', 'reorder the bit positions of a 4-bit quantized tensor using apply_order with AWQ_PACK_ORDER', 'reverse the AWQ pack order on a quantized tensor using apply_order with REVERSE_AWQ_PACK_ORDER']
```

Usage

```
{'convert_awq_weights_to_gptq_format': 'convert AWQ quantized model weights and zeros to GPTQ format using fast_awq_to_gptq', 'pack_4bit_tensor_to_32bit': 'pack a 4-bit integer tensor into a 32-bit packed tensor using the pack function', 'unpack_32bit_tensor_to_4bit': 'unpack a 32-bit packed tensor back into a 4-bit integer tensor using the unpack function', 'reorder_quantized_tensor_bits': 'reorder the bit positions of a 4-bit quantized tensor using apply_order with AWQ_PACK_ORDER', 'reverse_awq_pack_order': 'reverse the AWQ pack order on a quantized tensor using apply_order with REVERSE_AWQ_PACK_ORDER'}
```

