# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/calculate/_batch.py

Prompts

```
['create an InferenceBatcher instance with a predict unit and max batch size for batching inference requests', 'use the InferenceBatcher as a context manager to automatically shutdown the executor on exit', 'access the batch_predict_unit cached property to get a BatchServerPredictUnit from the InferenceBatcher', 'shutdown the InferenceBatcher executor and optionally wait for pending tasks to complete', 'get a thread pool concurrency backend executor for running ASE calculations concurrently', 'create a FAIRChemCalculator from a pretrained model checkpoint file or available model name', 'run a FormationEnergyCalculator to compute formation energies by wrapping a base ASE calculator', 'calculate energy, forces, and stress properties for an ASE Atoms object using FAIRChemCalculator', 'check an ASE Atoms object for invalid periodic boundary conditions before running calculations', 'review the implemented properties of a FAIRChemCalculator for a specific task name', 'get a pretrained MLIP prediction unit by model name with optional inference settings and device', 'download and return the local checkpoint file path for a named pretrained model from HuggingFace', 'retrieve atomic or form elemental reference energies for a pretrained model from HuggingFace', 'list all available pretrained model names loaded from the pretrained models configuration', 'create a HuggingFace checkpoint dataclass with filename, repo id, subfolder, revision, and reference energy fields', 'create a FairChemModel from a pretrained model name to compute energies and forces on atomistic systems', 'create a FairChemModel from a checkpoint file path to compute energies and forces on atomistic systems', 'run the FairChemModel forward method on a SimState to predict energy, forces, and stress tensors', 'convert a torch-sim SimState object to a batched FairChem AtomicData object for model inference', 'review the FairChemModel init method to understand device, dtype, and stress computation configuration options']
```

Usage

```
{'create_InferenceBatcher': 'create an InferenceBatcher instance with a predict unit and max batch size for batching inference requests', 'use_InferenceBatcher_context_manager': 'use the InferenceBatcher as a context manager to automatically shutdown the executor on exit', 'access_batch_predict_unit': 'access the batch_predict_unit cached property to get a BatchServerPredictUnit from the InferenceBatcher', 'shutdown_InferenceBatcher': 'shutdown the InferenceBatcher executor and optionally wait for pending tasks to complete', 'get_concurrency_backend': 'get a thread pool concurrency backend executor for running ASE calculations concurrently'}
```

## File: facebookresearch_fairchem/src/fairchem/core/calculate/ase_calculator.py

Prompts

```
['create an InferenceBatcher instance with a predict unit and max batch size for batching inference requests', 'use the InferenceBatcher as a context manager to automatically shutdown the executor on exit', 'access the batch_predict_unit cached property to get a BatchServerPredictUnit from the InferenceBatcher', 'shutdown the InferenceBatcher executor and optionally wait for pending tasks to complete', 'get a thread pool concurrency backend executor for running ASE calculations concurrently', 'create a FAIRChemCalculator from a pretrained model checkpoint file or available model name', 'run a FormationEnergyCalculator to compute formation energies by wrapping a base ASE calculator', 'calculate energy, forces, and stress properties for an ASE Atoms object using FAIRChemCalculator', 'check an ASE Atoms object for invalid periodic boundary conditions before running calculations', 'review the implemented properties of a FAIRChemCalculator for a specific task name', 'get a pretrained MLIP prediction unit by model name with optional inference settings and device', 'download and return the local checkpoint file path for a named pretrained model from HuggingFace', 'retrieve atomic or form elemental reference energies for a pretrained model from HuggingFace', 'list all available pretrained model names loaded from the pretrained models configuration', 'create a HuggingFace checkpoint dataclass with filename, repo id, subfolder, revision, and reference energy fields', 'create a FairChemModel from a pretrained model name to compute energies and forces on atomistic systems', 'create a FairChemModel from a checkpoint file path to compute energies and forces on atomistic systems', 'run the FairChemModel forward method on a SimState to predict energy, forces, and stress tensors', 'convert a torch-sim SimState object to a batched FairChem AtomicData object for model inference', 'review the FairChemModel init method to understand device, dtype, and stress computation configuration options']
```

Usage

```
{'create_FAIRChemCalculator_from_checkpoint': 'create a FAIRChemCalculator from a pretrained model checkpoint file or available model name', 'run_formation_energy_calculation': 'run a FormationEnergyCalculator to compute formation energies by wrapping a base ASE calculator', 'calculate_energy_forces_stress': 'calculate energy, forces, and stress properties for an ASE Atoms object using FAIRChemCalculator', 'check_atoms_pbc_validation': 'check an ASE Atoms object for invalid periodic boundary conditions before running calculations', 'review_FAIRChemCalculator_implemented_properties': 'review the implemented properties of a FAIRChemCalculator for a specific task name'}
```

## File: facebookresearch_fairchem/src/fairchem/core/calculate/pretrained_mlip.py

Prompts

```
['create an InferenceBatcher instance with a predict unit and max batch size for batching inference requests', 'use the InferenceBatcher as a context manager to automatically shutdown the executor on exit', 'access the batch_predict_unit cached property to get a BatchServerPredictUnit from the InferenceBatcher', 'shutdown the InferenceBatcher executor and optionally wait for pending tasks to complete', 'get a thread pool concurrency backend executor for running ASE calculations concurrently', 'create a FAIRChemCalculator from a pretrained model checkpoint file or available model name', 'run a FormationEnergyCalculator to compute formation energies by wrapping a base ASE calculator', 'calculate energy, forces, and stress properties for an ASE Atoms object using FAIRChemCalculator', 'check an ASE Atoms object for invalid periodic boundary conditions before running calculations', 'review the implemented properties of a FAIRChemCalculator for a specific task name', 'get a pretrained MLIP prediction unit by model name with optional inference settings and device', 'download and return the local checkpoint file path for a named pretrained model from HuggingFace', 'retrieve atomic or form elemental reference energies for a pretrained model from HuggingFace', 'list all available pretrained model names loaded from the pretrained models configuration', 'create a HuggingFace checkpoint dataclass with filename, repo id, subfolder, revision, and reference energy fields', 'create a FairChemModel from a pretrained model name to compute energies and forces on atomistic systems', 'create a FairChemModel from a checkpoint file path to compute energies and forces on atomistic systems', 'run the FairChemModel forward method on a SimState to predict energy, forces, and stress tensors', 'convert a torch-sim SimState object to a batched FairChem AtomicData object for model inference', 'review the FairChemModel init method to understand device, dtype, and stress computation configuration options']
```

Usage

```
{'get_predict_unit': 'get a pretrained MLIP prediction unit by model name with optional inference settings and device', 'pretrained_checkpoint_path_from_name': 'download and return the local checkpoint file path for a named pretrained model from HuggingFace', 'get_reference_energies': 'retrieve atomic or form elemental reference energies for a pretrained model from HuggingFace', 'available_models': 'list all available pretrained model names loaded from the pretrained models configuration', 'HuggingFaceCheckpoint': 'create a HuggingFace checkpoint dataclass with filename, repo id, subfolder, revision, and reference energy fields'}
```

## File: facebookresearch_fairchem/src/fairchem/core/calculate/torchsim_interface.py

Prompts

```
['create an InferenceBatcher instance with a predict unit and max batch size for batching inference requests', 'use the InferenceBatcher as a context manager to automatically shutdown the executor on exit', 'access the batch_predict_unit cached property to get a BatchServerPredictUnit from the InferenceBatcher', 'shutdown the InferenceBatcher executor and optionally wait for pending tasks to complete', 'get a thread pool concurrency backend executor for running ASE calculations concurrently', 'create a FAIRChemCalculator from a pretrained model checkpoint file or available model name', 'run a FormationEnergyCalculator to compute formation energies by wrapping a base ASE calculator', 'calculate energy, forces, and stress properties for an ASE Atoms object using FAIRChemCalculator', 'check an ASE Atoms object for invalid periodic boundary conditions before running calculations', 'review the implemented properties of a FAIRChemCalculator for a specific task name', 'get a pretrained MLIP prediction unit by model name with optional inference settings and device', 'download and return the local checkpoint file path for a named pretrained model from HuggingFace', 'retrieve atomic or form elemental reference energies for a pretrained model from HuggingFace', 'list all available pretrained model names loaded from the pretrained models configuration', 'create a HuggingFace checkpoint dataclass with filename, repo id, subfolder, revision, and reference energy fields', 'create a FairChemModel from a pretrained model name to compute energies and forces on atomistic systems', 'create a FairChemModel from a checkpoint file path to compute energies and forces on atomistic systems', 'run the FairChemModel forward method on a SimState to predict energy, forces, and stress tensors', 'convert a torch-sim SimState object to a batched FairChem AtomicData object for model inference', 'review the FairChemModel init method to understand device, dtype, and stress computation configuration options']
```

Usage

```
{'create_FairChemModel_from_pretrained': 'create a FairChemModel from a pretrained model name to compute energies and forces on atomistic systems', 'create_FairChemModel_from_checkpoint': 'create a FairChemModel from a checkpoint file path to compute energies and forces on atomistic systems', 'run_FairChemModel_forward': 'run the FairChemModel forward method on a SimState to predict energy, forces, and stress tensors', 'convert_simstate_to_atomicdata': 'convert a torch-sim SimState object to a batched FairChem AtomicData object for model inference', 'review_FairChemModel_init': 'review the FairChemModel init method to understand device, dtype, and stress computation configuration options'}
```

