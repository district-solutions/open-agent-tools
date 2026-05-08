# Agent Python Tools

- repo: facebookresearch/pycls
- repo_uri: https://github.com/facebookresearch/pycls

## File: facebookresearch_pycls/dev/model_zoo_tables.py

Prompts

```
['run the python module to generate all MODEL_ZOO.md tables for RegNetX, RegNetY, ResNet, ResNeXt, and EfficientNet model families', 'build a MODEL_ZOO.md table for a given model family like RegNetX using timing and error JSON data', 'create a single HTML table row for a model with its config URL, FLOPs, params, and download link', 'get model data including FLOPs, params, activations, batch size, inference time, training time, and top-1 error for a named model', 'review the HTML table template structure used for generating MODEL_ZOO.md tables with model complexity and performance metrics', 'test the complexity of a single PyCLS model by loading its config and measuring network parameters', 'test the inference timing of a PyCLS model by running warmup and measurement iterations on GPUs', 'test the top1 and top5 error rates of a PyCLS model using pretrained weights from the model zoo', 'generate complexity test data for all YAML config files in the PyCLS configs directory', 'load previously saved model test data from a JSON file for complexity, timing, or error tests']
```

Usage

```
{'run_model_zoo_tables': 'run the python module to generate all MODEL_ZOO.md tables for RegNetX, RegNetY, ResNet, ResNeXt, and EfficientNet model families', 'build_model_zoo_table': 'build a MODEL_ZOO.md table for a given model family like RegNetX using timing and error JSON data', 'create_model_zoo_table_row': 'create a single HTML table row for a model with its config URL, FLOPs, params, and download link', 'get_model_data': 'get model data including FLOPs, params, activations, batch size, inference time, training time, and top-1 error for a named model', 'review_TABLE_TEMPLATE': 'review the HTML table template structure used for generating MODEL_ZOO.md tables with model complexity and performance metrics'}
```

## File: facebookresearch_pycls/dev/test_models.py

Prompts

```
['run the python module to generate all MODEL_ZOO.md tables for RegNetX, RegNetY, ResNet, ResNeXt, and EfficientNet model families', 'build a MODEL_ZOO.md table for a given model family like RegNetX using timing and error JSON data', 'create a single HTML table row for a model with its config URL, FLOPs, params, and download link', 'get model data including FLOPs, params, activations, batch size, inference time, training time, and top-1 error for a named model', 'review the HTML table template structure used for generating MODEL_ZOO.md tables with model complexity and performance metrics', 'test the complexity of a single PyCLS model by loading its config and measuring network parameters', 'test the inference timing of a PyCLS model by running warmup and measurement iterations on GPUs', 'test the top1 and top5 error rates of a PyCLS model using pretrained weights from the model zoo', 'generate complexity test data for all YAML config files in the PyCLS configs directory', 'load previously saved model test data from a JSON file for complexity, timing, or error tests']
```

Usage

```
{'test_model_complexity': 'test the complexity of a single PyCLS model by loading its config and measuring network parameters', 'test_model_timing': 'test the inference timing of a PyCLS model by running warmup and measurement iterations on GPUs', 'test_model_error': 'test the top1 and top5 error rates of a PyCLS model using pretrained weights from the model zoo', 'generate_complexity_tests': 'generate complexity test data for all YAML config files in the PyCLS configs directory', 'load_test_data': 'load previously saved model test data from a JSON file for complexity, timing, or error tests'}
```

