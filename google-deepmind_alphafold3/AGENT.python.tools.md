# Agent Python Tools

- repo: google-deepmind/alphafold3
- repo_uri: https://github.com/google-deepmind/alphafold3

## File: google-deepmind_alphafold3/run_alphafold.py

Prompts

```
['run the data pipeline and model inference on a fold input to predict protein structures', 'create a ModelRunner instance to load AlphaFold 3 model parameters and run jitted inference on a GPU', 'run the full featurisation and inference pipeline to predict 3D structures for multiple random seeds', 'build an AlphaFold 3 model config with custom diffusion samples, recycles, and flash attention settings', 'write inference results including mmCIF files, confidence scores, embeddings, and distograms to an output directory', 'test the AlphaFold 3 model configuration serialization against a golden JSON file', 'test the AlphaFold 3 featurisation pipeline and compare output against golden data', 'test writing a fold input JSON file using run_alphafold write_fold_input_json', 'test running only the data pipeline without the model using process_fold_input', 'test replacing DB_DIR placeholders with actual database directory paths using replace_db_dir', 'run AlphaFold 3 end-to-end inference on a protein-ligand input JSON and validate output structure', 'test AlphaFold 3 model inference using a pre-featurised example and extract embeddings', 'test that process_fold_input runs only inference when no data pipeline config is provided', 'test AlphaFold 3 inference with parameterized bucket sizes and random seeds', 'calculate RMSD between predicted and ground truth structure coordinates with optional masking']
```

Usage

```
{'run_process_fold_input': 'run the data pipeline and model inference on a fold input to predict protein structures', 'create_model_runner': 'create a ModelRunner instance to load AlphaFold 3 model parameters and run jitted inference on a GPU', 'run_predict_structure': 'run the full featurisation and inference pipeline to predict 3D structures for multiple random seeds', 'build_make_model_config': 'build an AlphaFold 3 model config with custom diffusion samples, recycles, and flash attention settings', 'run_write_outputs': 'write inference results including mmCIF files, confidence scores, embeddings, and distograms to an output directory'}
```

## File: google-deepmind_alphafold3/run_alphafold_data_test.py

Prompts

```
['run the data pipeline and model inference on a fold input to predict protein structures', 'create a ModelRunner instance to load AlphaFold 3 model parameters and run jitted inference on a GPU', 'run the full featurisation and inference pipeline to predict 3D structures for multiple random seeds', 'build an AlphaFold 3 model config with custom diffusion samples, recycles, and flash attention settings', 'write inference results including mmCIF files, confidence scores, embeddings, and distograms to an output directory', 'test the AlphaFold 3 model configuration serialization against a golden JSON file', 'test the AlphaFold 3 featurisation pipeline and compare output against golden data', 'test writing a fold input JSON file using run_alphafold write_fold_input_json', 'test running only the data pipeline without the model using process_fold_input', 'test replacing DB_DIR placeholders with actual database directory paths using replace_db_dir', 'run AlphaFold 3 end-to-end inference on a protein-ligand input JSON and validate output structure', 'test AlphaFold 3 model inference using a pre-featurised example and extract embeddings', 'test that process_fold_input runs only inference when no data pipeline config is provided', 'test AlphaFold 3 inference with parameterized bucket sizes and random seeds', 'calculate RMSD between predicted and ground truth structure coordinates with optional masking']
```

Usage

```
{'test_data_pipeline_config': 'test the AlphaFold 3 model configuration serialization against a golden JSON file', 'test_featurisation': 'test the AlphaFold 3 featurisation pipeline and compare output against golden data', 'test_write_input_json': 'test writing a fold input JSON file using run_alphafold write_fold_input_json', 'test_process_fold_input': 'test running only the data pipeline without the model using process_fold_input', 'test_replace_db_dir': 'test replacing DB_DIR placeholders with actual database directory paths using replace_db_dir'}
```

## File: google-deepmind_alphafold3/run_alphafold_test.py

Prompts

```
['run the data pipeline and model inference on a fold input to predict protein structures', 'create a ModelRunner instance to load AlphaFold 3 model parameters and run jitted inference on a GPU', 'run the full featurisation and inference pipeline to predict 3D structures for multiple random seeds', 'build an AlphaFold 3 model config with custom diffusion samples, recycles, and flash attention settings', 'write inference results including mmCIF files, confidence scores, embeddings, and distograms to an output directory', 'test the AlphaFold 3 model configuration serialization against a golden JSON file', 'test the AlphaFold 3 featurisation pipeline and compare output against golden data', 'test writing a fold input JSON file using run_alphafold write_fold_input_json', 'test running only the data pipeline without the model using process_fold_input', 'test replacing DB_DIR placeholders with actual database directory paths using replace_db_dir', 'run AlphaFold 3 end-to-end inference on a protein-ligand input JSON and validate output structure', 'test AlphaFold 3 model inference using a pre-featurised example and extract embeddings', 'test that process_fold_input runs only inference when no data pipeline config is provided', 'test AlphaFold 3 inference with parameterized bucket sizes and random seeds', 'calculate RMSD between predicted and ground truth structure coordinates with optional masking']
```

Usage

```
{'run_alphafold_inference': 'run AlphaFold 3 end-to-end inference on a protein-ligand input JSON and validate output structure', 'test_model_inference_featurised': 'test AlphaFold 3 model inference using a pre-featurised example and extract embeddings', 'test_process_fold_input_only_inference': 'test that process_fold_input runs only inference when no data pipeline config is provided', 'test_inference_parameterized': 'test AlphaFold 3 inference with parameterized bucket sizes and random seeds', 'calculate_rmsd_from_coords': 'calculate RMSD between predicted and ground truth structure coordinates with optional masking'}
```

