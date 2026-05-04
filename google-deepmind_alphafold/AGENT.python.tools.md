# Agent Python Tools

- repo: google-deepmind/alphafold
- repo_uri: https://github.com/google-deepmind/alphafold

## File: google-deepmind_alphafold/conftest.py

Prompts

```
['run pytest tests that require absl flags to be parsed before test execution', 'run AlphaFold protein structure prediction on a FASTA file with monomer or multimer model preset', 'predict protein structure from a FASTA sequence using AlphaFold model runners and save results to output directory', 'save a predicted protein structure as an mmCIF file with model name and file ID metadata', 'save per-residue pLDDT confidence scores as a JSON file for a given AlphaFold model prediction', 'save predicted aligned error matrix and max PAE value as a JSON file for model confidence analysis', 'test the RunAlphafoldTest end to end prediction pipeline with mocked data pipeline and model runner', 'run the predict_structure function with a FASTA file and mocked model runners to generate PDB outputs', 'test the ModelsToRelax ALL mode to verify relaxed PDB and CIF files are generated with relax metrics', 'test the ModelsToRelax NONE mode to verify only unrelaxed PDB and CIF output files are produced', 'verify that the pLDDT confidence score is correctly written to the B-factor column of the PDB file']
```

Usage

```
{'run_pytest_with_absl_flags': 'run pytest tests that require absl flags to be parsed before test execution'}
```

## File: google-deepmind_alphafold/run_alphafold.py

Prompts

```
['run pytest tests that require absl flags to be parsed before test execution', 'run AlphaFold protein structure prediction on a FASTA file with monomer or multimer model preset', 'predict protein structure from a FASTA sequence using AlphaFold model runners and save results to output directory', 'save a predicted protein structure as an mmCIF file with model name and file ID metadata', 'save per-residue pLDDT confidence scores as a JSON file for a given AlphaFold model prediction', 'save predicted aligned error matrix and max PAE value as a JSON file for model confidence analysis', 'test the RunAlphafoldTest end to end prediction pipeline with mocked data pipeline and model runner', 'run the predict_structure function with a FASTA file and mocked model runners to generate PDB outputs', 'test the ModelsToRelax ALL mode to verify relaxed PDB and CIF files are generated with relax metrics', 'test the ModelsToRelax NONE mode to verify only unrelaxed PDB and CIF output files are produced', 'verify that the pLDDT confidence score is correctly written to the B-factor column of the PDB file']
```

Usage

```
{'run_alphafold_prediction': 'run AlphaFold protein structure prediction on a FASTA file with monomer or multimer model preset', 'predict_structure': 'predict protein structure from a FASTA sequence using AlphaFold model runners and save results to output directory', 'save_mmcif_file': 'save a predicted protein structure as an mmCIF file with model name and file ID metadata', 'save_confidence_json': 'save per-residue pLDDT confidence scores as a JSON file for a given AlphaFold model prediction', 'save_pae_json': 'save predicted aligned error matrix and max PAE value as a JSON file for model confidence analysis'}
```

## File: google-deepmind_alphafold/run_alphafold_test.py

Prompts

```
['run pytest tests that require absl flags to be parsed before test execution', 'run AlphaFold protein structure prediction on a FASTA file with monomer or multimer model preset', 'predict protein structure from a FASTA sequence using AlphaFold model runners and save results to output directory', 'save a predicted protein structure as an mmCIF file with model name and file ID metadata', 'save per-residue pLDDT confidence scores as a JSON file for a given AlphaFold model prediction', 'save predicted aligned error matrix and max PAE value as a JSON file for model confidence analysis', 'test the RunAlphafoldTest end to end prediction pipeline with mocked data pipeline and model runner', 'run the predict_structure function with a FASTA file and mocked model runners to generate PDB outputs', 'test the ModelsToRelax ALL mode to verify relaxed PDB and CIF files are generated with relax metrics', 'test the ModelsToRelax NONE mode to verify only unrelaxed PDB and CIF output files are produced', 'verify that the pLDDT confidence score is correctly written to the B-factor column of the PDB file']
```

Usage

```
{'test_end_to_end': 'test the RunAlphafoldTest end to end prediction pipeline with mocked data pipeline and model runner', 'run_predict_structure': 'run the predict_structure function with a FASTA file and mocked model runners to generate PDB outputs', 'test_models_to_relax_all': 'test the ModelsToRelax ALL mode to verify relaxed PDB and CIF files are generated with relax metrics', 'test_models_to_relax_none': 'test the ModelsToRelax NONE mode to verify only unrelaxed PDB and CIF output files are produced', 'verify_plddt_bfactor': 'verify that the pLDDT confidence score is correctly written to the B-factor column of the PDB file'}
```

