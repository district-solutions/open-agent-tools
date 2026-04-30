# Agent Python Tools

- repo: huggingface/diffusers
- repo_uri: https://github.com/huggingface/diffusers

## File: huggingface_diffusers/tests/quantization/bnb/test_4bit.py

Prompts

```
['test that SD3Transformer2DModel loaded with nf4 BitsAndBytesConfig has correct 4-bit quantized linear layers', 'test that a 4-bit quantized model achieves the expected memory footprint reduction ratio versus fp16', 'test saving and reloading a 4-bit quantized SD3Transformer2DModel and verify parameters and outputs match', 'test training a 4-bit quantized model by adding LoRA adapters and verifying gradients are non-zero', 'test torch compile support for a 4-bit quantized pipeline using PipelineQuantizationConfig with bitsandbytes backend', 'test the BnB8bitBasicTests class to verify 8-bit quantization memory footprint and parameter count for SD3 models', 'test the BnB8bitTrainingTests class to verify training with LoRA adapters on 8-bit quantized SD3 models', 'test the BaseBnb8bitSerializationTests class to verify saving and loading 8-bit quantized models preserves outputs', 'test the SlowBnb8bitFluxTests class to verify 8-bit quantized FLUX pipeline quality and LoRA loading', 'test the Bnb8BitCompileTests class to verify torch.compile compatibility with 8-bit quantized models']
```

Usage

```
{'test_4bit_quantization_basic': 'test that SD3Transformer2DModel loaded with nf4 BitsAndBytesConfig has correct 4-bit quantized linear layers', 'test_4bit_memory_footprint': 'test that a 4-bit quantized model achieves the expected memory footprint reduction ratio versus fp16', 'test_4bit_serialization': 'test saving and reloading a 4-bit quantized SD3Transformer2DModel and verify parameters and outputs match', 'test_4bit_training_with_lora': 'test training a 4-bit quantized model by adding LoRA adapters and verifying gradients are non-zero', 'test_4bit_torch_compile': 'test torch compile support for a 4-bit quantized pipeline using PipelineQuantizationConfig with bitsandbytes backend'}
```

## File: huggingface_diffusers/tests/quantization/bnb/test_mixed_int8.py

Prompts

```
['test that SD3Transformer2DModel loaded with nf4 BitsAndBytesConfig has correct 4-bit quantized linear layers', 'test that a 4-bit quantized model achieves the expected memory footprint reduction ratio versus fp16', 'test saving and reloading a 4-bit quantized SD3Transformer2DModel and verify parameters and outputs match', 'test training a 4-bit quantized model by adding LoRA adapters and verifying gradients are non-zero', 'test torch compile support for a 4-bit quantized pipeline using PipelineQuantizationConfig with bitsandbytes backend', 'test the BnB8bitBasicTests class to verify 8-bit quantization memory footprint and parameter count for SD3 models', 'test the BnB8bitTrainingTests class to verify training with LoRA adapters on 8-bit quantized SD3 models', 'test the BaseBnb8bitSerializationTests class to verify saving and loading 8-bit quantized models preserves outputs', 'test the SlowBnb8bitFluxTests class to verify 8-bit quantized FLUX pipeline quality and LoRA loading', 'test the Bnb8BitCompileTests class to verify torch.compile compatibility with 8-bit quantized models']
```

Usage

```
{'test_8bit_quantization_basic': 'test the BnB8bitBasicTests class to verify 8-bit quantization memory footprint and parameter count for SD3 models', 'test_8bit_quantization_training': 'test the BnB8bitTrainingTests class to verify training with LoRA adapters on 8-bit quantized SD3 models', 'test_8bit_quantization_serialization': 'test the BaseBnb8bitSerializationTests class to verify saving and loading 8-bit quantized models preserves outputs', 'test_8bit_quantization_flux': 'test the SlowBnb8bitFluxTests class to verify 8-bit quantized FLUX pipeline quality and LoRA loading', 'test_8bit_quantization_compile': 'test the Bnb8BitCompileTests class to verify torch.compile compatibility with 8-bit quantized models'}
```

