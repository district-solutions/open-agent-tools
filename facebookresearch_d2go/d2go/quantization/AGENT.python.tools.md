# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/quantization/fx.py

Prompts

```
['get the FX graph preparation function for quantization or QAT based on the is_qat flag', 'get the quantization conversion function choosing between eager mode and FX graph mode from config', 'get the eager mode preparation function for standard quantization or QAT based on config and is_qat flag', 'review the get_prepare_fx_fn function to understand how it selects between prepare_fx and prepare_qat_fx', 'review the get_convert_fn function to understand how it selects between convert and convert_fx based on EAGER_MODE', 'convert a QConfig to its learnable counterpart using convert_to_learnable_qconfig', 'setup optimizer param groups with zero weight decay for learnable QAT scale and zero_point params', 'enable learning observers and sync scale and zero_point tensors across distributed processes', 'enable or disable fake quantization on learnable QAT modules using apply on the model', 'check that a model uses learnable fake quant ops when qat method is learnable', 'calibrate a model and convert it to a quantized int8 PyTorch model using post-training quantization', 'prepare an fp32 model for quantization-aware training by inserting fake quant and observer modules', 'convert a fake quant model with fp32 operators into a real quantized model with int8 operators', 'prepare an fp32 model for fake quantization in either QAT or PTQ mode using eager or FX graph', 'load non-QAT checkpoint weights into a QAT model by remapping state dict keys and ignoring observer keys', 'create a qconfig from a D2Go quantization config using set_backend_and_create_qconfig', 'get a QConfig for a given backend like qnnpack using holistic_get_qconfig', 'parse an extended backend string like qnnpack@symmetric using _smart_parse_extended_backend', 'validate that a backend string is a supported PyTorch native backend using validate_native_backend', 'decode an extended backend string to its native backend name using smart_decode_backend']
```

Usage

```
{'get_prepare_fx_fn': 'get the FX graph preparation function for quantization or QAT based on the is_qat flag', 'get_convert_fn': 'get the quantization conversion function choosing between eager mode and FX graph mode from config', 'get_prepare_fn': 'get the eager mode preparation function for standard quantization or QAT based on config and is_qat flag', 'review_get_prepare_fx_fn': 'review the get_prepare_fx_fn function to understand how it selects between prepare_fx and prepare_qat_fx', 'review_get_convert_fn': 'review the get_convert_fn function to understand how it selects between convert and convert_fx based on EAGER_MODE'}
```

## File: facebookresearch_d2go/d2go/quantization/learnable_qat.py

Prompts

```
['get the FX graph preparation function for quantization or QAT based on the is_qat flag', 'get the quantization conversion function choosing between eager mode and FX graph mode from config', 'get the eager mode preparation function for standard quantization or QAT based on config and is_qat flag', 'review the get_prepare_fx_fn function to understand how it selects between prepare_fx and prepare_qat_fx', 'review the get_convert_fn function to understand how it selects between convert and convert_fx based on EAGER_MODE', 'convert a QConfig to its learnable counterpart using convert_to_learnable_qconfig', 'setup optimizer param groups with zero weight decay for learnable QAT scale and zero_point params', 'enable learning observers and sync scale and zero_point tensors across distributed processes', 'enable or disable fake quantization on learnable QAT modules using apply on the model', 'check that a model uses learnable fake quant ops when qat method is learnable', 'calibrate a model and convert it to a quantized int8 PyTorch model using post-training quantization', 'prepare an fp32 model for quantization-aware training by inserting fake quant and observer modules', 'convert a fake quant model with fp32 operators into a real quantized model with int8 operators', 'prepare an fp32 model for fake quantization in either QAT or PTQ mode using eager or FX graph', 'load non-QAT checkpoint weights into a QAT model by remapping state dict keys and ignoring observer keys', 'create a qconfig from a D2Go quantization config using set_backend_and_create_qconfig', 'get a QConfig for a given backend like qnnpack using holistic_get_qconfig', 'parse an extended backend string like qnnpack@symmetric using _smart_parse_extended_backend', 'validate that a backend string is a supported PyTorch native backend using validate_native_backend', 'decode an extended backend string to its native backend name using smart_decode_backend']
```

Usage

```
{'convert_qconfig_to_learnable': 'convert a QConfig to its learnable counterpart using convert_to_learnable_qconfig', 'setup_optimizer_param_groups': 'setup optimizer param groups with zero weight decay for learnable QAT scale and zero_point params', 'enable_learnable_observer': 'enable learning observers and sync scale and zero_point tensors across distributed processes', 'toggle_fake_quant': 'enable or disable fake quantization on learnable QAT modules using apply on the model', 'check_learnable_fake_quant': 'check that a model uses learnable fake quant ops when qat method is learnable'}
```

## File: facebookresearch_d2go/d2go/quantization/modeling.py

Prompts

```
['get the FX graph preparation function for quantization or QAT based on the is_qat flag', 'get the quantization conversion function choosing between eager mode and FX graph mode from config', 'get the eager mode preparation function for standard quantization or QAT based on config and is_qat flag', 'review the get_prepare_fx_fn function to understand how it selects between prepare_fx and prepare_qat_fx', 'review the get_convert_fn function to understand how it selects between convert and convert_fx based on EAGER_MODE', 'convert a QConfig to its learnable counterpart using convert_to_learnable_qconfig', 'setup optimizer param groups with zero weight decay for learnable QAT scale and zero_point params', 'enable learning observers and sync scale and zero_point tensors across distributed processes', 'enable or disable fake quantization on learnable QAT modules using apply on the model', 'check that a model uses learnable fake quant ops when qat method is learnable', 'calibrate a model and convert it to a quantized int8 PyTorch model using post-training quantization', 'prepare an fp32 model for quantization-aware training by inserting fake quant and observer modules', 'convert a fake quant model with fp32 operators into a real quantized model with int8 operators', 'prepare an fp32 model for fake quantization in either QAT or PTQ mode using eager or FX graph', 'load non-QAT checkpoint weights into a QAT model by remapping state dict keys and ignoring observer keys', 'create a qconfig from a D2Go quantization config using set_backend_and_create_qconfig', 'get a QConfig for a given backend like qnnpack using holistic_get_qconfig', 'parse an extended backend string like qnnpack@symmetric using _smart_parse_extended_backend', 'validate that a backend string is a supported PyTorch native backend using validate_native_backend', 'decode an extended backend string to its native backend name using smart_decode_backend']
```

Usage

```
{'post_training_quantize': 'calibrate a model and convert it to a quantized int8 PyTorch model using post-training quantization', 'setup_qat_model': 'prepare an fp32 model for quantization-aware training by inserting fake quant and observer modules', 'convert_to_quantized_model': 'convert a fake quant model with fp32 operators into a real quantized model with int8 operators', 'prepare_fake_quant_model': 'prepare an fp32 model for fake quantization in either QAT or PTQ mode using eager or FX graph', 'QATCheckpointer': 'load non-QAT checkpoint weights into a QAT model by remapping state dict keys and ignoring observer keys'}
```

## File: facebookresearch_d2go/d2go/quantization/qconfig.py

Prompts

```
['get the FX graph preparation function for quantization or QAT based on the is_qat flag', 'get the quantization conversion function choosing between eager mode and FX graph mode from config', 'get the eager mode preparation function for standard quantization or QAT based on config and is_qat flag', 'review the get_prepare_fx_fn function to understand how it selects between prepare_fx and prepare_qat_fx', 'review the get_convert_fn function to understand how it selects between convert and convert_fx based on EAGER_MODE', 'convert a QConfig to its learnable counterpart using convert_to_learnable_qconfig', 'setup optimizer param groups with zero weight decay for learnable QAT scale and zero_point params', 'enable learning observers and sync scale and zero_point tensors across distributed processes', 'enable or disable fake quantization on learnable QAT modules using apply on the model', 'check that a model uses learnable fake quant ops when qat method is learnable', 'calibrate a model and convert it to a quantized int8 PyTorch model using post-training quantization', 'prepare an fp32 model for quantization-aware training by inserting fake quant and observer modules', 'convert a fake quant model with fp32 operators into a real quantized model with int8 operators', 'prepare an fp32 model for fake quantization in either QAT or PTQ mode using eager or FX graph', 'load non-QAT checkpoint weights into a QAT model by remapping state dict keys and ignoring observer keys', 'create a qconfig from a D2Go quantization config using set_backend_and_create_qconfig', 'get a QConfig for a given backend like qnnpack using holistic_get_qconfig', 'parse an extended backend string like qnnpack@symmetric using _smart_parse_extended_backend', 'validate that a backend string is a supported PyTorch native backend using validate_native_backend', 'decode an extended backend string to its native backend name using smart_decode_backend']
```

Usage

```
{'create_qconfig_from_cfg': 'create a qconfig from a D2Go quantization config using set_backend_and_create_qconfig', 'get_qconfig_for_backend': 'get a QConfig for a given backend like qnnpack using holistic_get_qconfig', 'parse_extended_backend': 'parse an extended backend string like qnnpack@symmetric using _smart_parse_extended_backend', 'validate_quantization_backend': 'validate that a backend string is a supported PyTorch native backend using validate_native_backend', 'decode_extended_backend': 'decode an extended backend string to its native backend name using smart_decode_backend'}
```

