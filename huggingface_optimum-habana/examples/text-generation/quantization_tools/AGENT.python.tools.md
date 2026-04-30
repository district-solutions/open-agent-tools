# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/examples/text-generation/quantization_tools/pt2e.py

Prompts

```
['prepare a llama model for PT2E quantization calibration by exporting and inserting observers', 'load a pre-quantized PT2E model from a .pt2 file for inference on HPU', 'convert a calibrated PT2E model and save it as a .pt2 file after calibration', 'configure PT2E quantization with int8 or fp8 data types using the PT2EConfig dataclass', 'review the qdtype_dict mapping quantization keys like int8 and fp8 to torch dtype values', 'run the unify_measurements CLI tool to merge measurement JSON files across GPU card groups into unified outputs', 'call unify_measurements to merge multiple measurement JSON files by taking per-tensor maximum values across a card group', 'call find_measurement_path to locate a measurement JSON file matching a given card name and group size', 'call parse_args to build an argparse parser accepting measurements directory, card groups, and output path arguments', 'run the script to convert unified measurement JSON files into numpy NPZ archives for quantization calibration']
```

Usage

```
{'prepare_pt2e_model_for_calibration': 'prepare a llama model for PT2E quantization calibration by exporting and inserting observers', 'load_pt2e_quantized_model': 'load a pre-quantized PT2E model from a .pt2 file for inference on HPU', 'save_pt2e_quantized_model': 'convert a calibrated PT2E model and save it as a .pt2 file after calibration', 'configure_pt2e_quantization': 'configure PT2E quantization with int8 or fp8 data types using the PT2EConfig dataclass', 'review_qdtype_dict': 'review the qdtype_dict mapping quantization keys like int8 and fp8 to torch dtype values'}
```

## File: huggingface_optimum-habana/examples/text-generation/quantization_tools/unify_measurements.py

Prompts

```
['prepare a llama model for PT2E quantization calibration by exporting and inserting observers', 'load a pre-quantized PT2E model from a .pt2 file for inference on HPU', 'convert a calibrated PT2E model and save it as a .pt2 file after calibration', 'configure PT2E quantization with int8 or fp8 data types using the PT2EConfig dataclass', 'review the qdtype_dict mapping quantization keys like int8 and fp8 to torch dtype values', 'run the unify_measurements CLI tool to merge measurement JSON files across GPU card groups into unified outputs', 'call unify_measurements to merge multiple measurement JSON files by taking per-tensor maximum values across a card group', 'call find_measurement_path to locate a measurement JSON file matching a given card name and group size', 'call parse_args to build an argparse parser accepting measurements directory, card groups, and output path arguments', 'run the script to convert unified measurement JSON files into numpy NPZ archives for quantization calibration']
```

Usage

```
{'run_unify_measurements_cli': 'run the unify_measurements CLI tool to merge measurement JSON files across GPU card groups into unified outputs', 'unify_measurements_function': 'call unify_measurements to merge multiple measurement JSON files by taking per-tensor maximum values across a card group', 'find_measurement_path_function': 'call find_measurement_path to locate a measurement JSON file matching a given card name and group size', 'parse_args_function': 'call parse_args to build an argparse parser accepting measurements directory, card groups, and output path arguments', 'convert_measurements_to_npz': 'run the script to convert unified measurement JSON files into numpy NPZ archives for quantization calibration'}
```

