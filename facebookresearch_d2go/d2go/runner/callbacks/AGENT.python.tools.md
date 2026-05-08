# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/runner/callbacks/quantization.py

Prompts

```
['create a QuantizationAwareTraining callback to enable quantization-aware training on a PyTorch Lightning model', 'create a PostTrainingQuantization callback to quantize a trained model using validation data for calibration', 'build a QuantizationAwareTraining callback from a D2Go CfgNode config with QAT settings', 'build a PostTrainingQuantization callback from a D2Go CfgNode config with quantization module settings', 'test whether a set of QConfigDicts requires calibration by checking for static quant types']
```

Usage

```
{'run_QAT_callback': 'create a QuantizationAwareTraining callback to enable quantization-aware training on a PyTorch Lightning model', 'run_PTQ_callback': 'create a PostTrainingQuantization callback to quantize a trained model using validation data for calibration', 'build_QAT_from_config': 'build a QuantizationAwareTraining callback from a D2Go CfgNode config with QAT settings', 'build_PTQ_from_config': 'build a PostTrainingQuantization callback from a D2Go CfgNode config with quantization module settings', 'test_requires_calibration': 'test whether a set of QConfigDicts requires calibration by checking for static quant types'}
```

