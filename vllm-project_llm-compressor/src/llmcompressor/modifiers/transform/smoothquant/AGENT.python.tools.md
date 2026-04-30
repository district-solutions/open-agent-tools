# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/transform/smoothquant/base.py

Prompts

```
['create a SmoothQuantModifier with smoothing strength and calibration dataset for one-shot quantization', 'run SmoothQuantModifier on a model with calibration data to collect activation ranges via forward hooks', 'resolve SmoothQuant mappings from model architecture or user-specified regex patterns into SmoothQuantMapping objects', 'apply SmoothQuant smoothing to activations and balance weights in-place after calibration completes', 'summarize the SmoothQuantModifier class that implements channel-wise smoothing for easier quantization', 'review the SmoothQuantMapping dataclass that stores activation-to-weight layer mappings for smoothing', 'review the SmoothQuantScale dataclass that tracks per-channel min and max values during calibration', 'retrieve smoothquant layer mappings for a specified model architecture from the registry', 'summarize the smoothquant layer mapping registry containing architecture-to-mapping associations', 'summarize the default smoothquant layer mappings for balance and smooth layer patterns', 'review the LayerMap namedtuple defining balance_layers and smooth_layers for smoothquant', 'review the handle_mapping_resolution_errors decorator for smoothquant mapping error handling']
```

Usage

```
{'create_smoothquant_modifier': 'create a SmoothQuantModifier with smoothing strength and calibration dataset for one-shot quantization', 'run_smoothquant_calibration': 'run SmoothQuantModifier on a model with calibration data to collect activation ranges via forward hooks', 'resolve_smoothquant_mappings': 'resolve SmoothQuant mappings from model architecture or user-specified regex patterns into SmoothQuantMapping objects', 'apply_smoothquant_smoothing': 'apply SmoothQuant smoothing to activations and balance weights in-place after calibration completes', 'summarize_smoothquant_modifier': 'summarize the SmoothQuantModifier class that implements channel-wise smoothing for easier quantization', 'review_smoothquant_mapping': 'review the SmoothQuantMapping dataclass that stores activation-to-weight layer mappings for smoothing', 'review_smoothquant_scale': 'review the SmoothQuantScale dataclass that tracks per-channel min and max values during calibration'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modifiers/transform/smoothquant/utils.py

Prompts

```
['create a SmoothQuantModifier with smoothing strength and calibration dataset for one-shot quantization', 'run SmoothQuantModifier on a model with calibration data to collect activation ranges via forward hooks', 'resolve SmoothQuant mappings from model architecture or user-specified regex patterns into SmoothQuantMapping objects', 'apply SmoothQuant smoothing to activations and balance weights in-place after calibration completes', 'summarize the SmoothQuantModifier class that implements channel-wise smoothing for easier quantization', 'review the SmoothQuantMapping dataclass that stores activation-to-weight layer mappings for smoothing', 'review the SmoothQuantScale dataclass that tracks per-channel min and max values during calibration', 'retrieve smoothquant layer mappings for a specified model architecture from the registry', 'summarize the smoothquant layer mapping registry containing architecture-to-mapping associations', 'summarize the default smoothquant layer mappings for balance and smooth layer patterns', 'review the LayerMap namedtuple defining balance_layers and smooth_layers for smoothquant', 'review the handle_mapping_resolution_errors decorator for smoothquant mapping error handling']
```

Usage

```
{'get_layer_mappings_from_architecture': 'retrieve smoothquant layer mappings for a specified model architecture from the registry', 'summarize_MAPPINGS_REGISTRY': 'summarize the smoothquant layer mapping registry containing architecture-to-mapping associations', 'summarize_DEFAULT_SMOOTHQUANT_MAPPINGS': 'summarize the default smoothquant layer mappings for balance and smooth layer patterns', 'review_LayerMap': 'review the LayerMap namedtuple defining balance_layers and smooth_layers for smoothquant', 'review_handle_mapping_resolution_errors': 'review the handle_mapping_resolution_errors decorator for smoothquant mapping error handling'}
```

