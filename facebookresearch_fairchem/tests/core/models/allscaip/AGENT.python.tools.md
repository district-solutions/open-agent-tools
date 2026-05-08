# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/models/allscaip/test_allscaip_calculator.py

Prompts

```
['test that AllScAIP works end-to-end through FAIRChemCalculator by computing energy and forces for a water molecule', 'test that InferenceSettings with max_atoms pads inputs correctly and produces valid results through FAIRChemCalculator with torch.compile', 'test that compile=True without max_atoms raises a ValueError when building inference settings', 'run pretrained_mlip.get_predict_unit to load the AllScAIP model on a CUDA device for inference', 'build InferenceSettings with compile and max_atoms parameters to configure AllScAIPBackbone inference behavior', 'test the AllScAIP model forward pass on GPU with fixed results comparison', 'create sample FCC crystal AtomicData with a given number of atoms for model input', 'build an AllScAIP backbone configuration dictionary with cutoff radius and compile options', 'get an AllScAIPBackbone model instance with specified cutoff and device settings', 'get a full HydraModelV2 with AllScAIP backbone and energy force stress head']
```

Usage

```
{'test_calculator_inference': 'test that AllScAIP works end-to-end through FAIRChemCalculator by computing energy and forces for a water molecule', 'test_calculator_inference_with_max_atoms': 'test that InferenceSettings with max_atoms pads inputs correctly and produces valid results through FAIRChemCalculator with torch.compile', 'test_calculator_inference_max_atoms_required_with_compile': 'test that compile=True without max_atoms raises a ValueError when building inference settings', 'run_allscaip_predict_unit': 'run pretrained_mlip.get_predict_unit to load the AllScAIP model on a CUDA device for inference', 'build_inference_settings': 'build InferenceSettings with compile and max_atoms parameters to configure AllScAIPBackbone inference behavior'}
```

## File: facebookresearch_fairchem/tests/core/models/allscaip/test_allscaip_forward.py

Prompts

```
['test that AllScAIP works end-to-end through FAIRChemCalculator by computing energy and forces for a water molecule', 'test that InferenceSettings with max_atoms pads inputs correctly and produces valid results through FAIRChemCalculator with torch.compile', 'test that compile=True without max_atoms raises a ValueError when building inference settings', 'run pretrained_mlip.get_predict_unit to load the AllScAIP model on a CUDA device for inference', 'build InferenceSettings with compile and max_atoms parameters to configure AllScAIPBackbone inference behavior', 'test the AllScAIP model forward pass on GPU with fixed results comparison', 'create sample FCC crystal AtomicData with a given number of atoms for model input', 'build an AllScAIP backbone configuration dictionary with cutoff radius and compile options', 'get an AllScAIPBackbone model instance with specified cutoff and device settings', 'get a full HydraModelV2 with AllScAIP backbone and energy force stress head']
```

Usage

```
{'test_allscaip_forward': 'test the AllScAIP model forward pass on GPU with fixed results comparison', 'create_sample_data': 'create sample FCC crystal AtomicData with a given number of atoms for model input', 'build_backbone_config': 'build an AllScAIP backbone configuration dictionary with cutoff radius and compile options', 'get_allscaip_backbone': 'get an AllScAIPBackbone model instance with specified cutoff and device settings', 'get_allscaip_full': 'get a full HydraModelV2 with AllScAIP backbone and energy force stress head'}
```

