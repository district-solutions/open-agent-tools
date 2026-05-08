# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/calculate/test_ase_calculator.py

Prompts

```
['test the FAIRChemCalculator to compute energy and forces for bulk, slab, and molecular systems', 'test the FormationEnergyCalculator wrapper to compute formation energies from element reference values', 'test creating a FAIRChemCalculator from a pretrained model checkpoint with a specific task name', 'test structure relaxation using BFGS optimizer with a FAIRChemCalculator on a slab system', 'test molecular dynamics simulation using Langevin dynamics with a FAIRChemCalculator on a molecule', 'test InferenceBatcher initialization with custom thread pool concurrency options and max workers', 'test InferenceBatcher initialization with Ray actor options like num_cpus for distributed inference', 'test InferenceBatcher context manager enter and exit to verify executor shutdown after use', 'test batched predictions on AtomicData objects and verify energy and forces output shapes', 'test that batched predictions via executor map match serial FAIRChemCalculator results within tolerance', 'test FairChemModel initialization with oc20 or omol task names and a checkpoint path', 'test batching multiple bulk or molecule systems through FairChemModel for energy and force predictions', 'test stress tensor computation with FairChemModel using a conservative model and compute_stress flag', 'test converting a torch_sim SimState to an AtomicData batch for periodic or molecular systems', 'test FairChemModel handling of charge and spin extras on molecular systems via system_extras_map']
```

Usage

```
{'test_FAIRChemCalculator_energy_forces': 'test the FAIRChemCalculator to compute energy and forces for bulk, slab, and molecular systems', 'test_FormationEnergyCalculator_wrapper': 'test the FormationEnergyCalculator wrapper to compute formation energies from element reference values', 'test_calculator_from_checkpoint': 'test creating a FAIRChemCalculator from a pretrained model checkpoint with a specific task name', 'test_structure_relaxation_BFGS': 'test structure relaxation using BFGS optimizer with a FAIRChemCalculator on a slab system', 'test_molecular_dynamics_Langevin': 'test molecular dynamics simulation using Langevin dynamics with a FAIRChemCalculator on a molecule'}
```

## File: facebookresearch_fairchem/tests/core/calculate/test_batcher.py

Prompts

```
['test the FAIRChemCalculator to compute energy and forces for bulk, slab, and molecular systems', 'test the FormationEnergyCalculator wrapper to compute formation energies from element reference values', 'test creating a FAIRChemCalculator from a pretrained model checkpoint with a specific task name', 'test structure relaxation using BFGS optimizer with a FAIRChemCalculator on a slab system', 'test molecular dynamics simulation using Langevin dynamics with a FAIRChemCalculator on a molecule', 'test InferenceBatcher initialization with custom thread pool concurrency options and max workers', 'test InferenceBatcher initialization with Ray actor options like num_cpus for distributed inference', 'test InferenceBatcher context manager enter and exit to verify executor shutdown after use', 'test batched predictions on AtomicData objects and verify energy and forces output shapes', 'test that batched predictions via executor map match serial FAIRChemCalculator results within tolerance', 'test FairChemModel initialization with oc20 or omol task names and a checkpoint path', 'test batching multiple bulk or molecule systems through FairChemModel for energy and force predictions', 'test stress tensor computation with FairChemModel using a conservative model and compute_stress flag', 'test converting a torch_sim SimState to an AtomicData batch for periodic or molecular systems', 'test FairChemModel handling of charge and spin extras on molecular systems via system_extras_map']
```

Usage

```
{'test_InferenceBatcher_thread_concurrency': 'test InferenceBatcher initialization with custom thread pool concurrency options and max workers', 'test_InferenceBatcher_ray_actor': 'test InferenceBatcher initialization with Ray actor options like num_cpus for distributed inference', 'test_InferenceBatcher_context_manager': 'test InferenceBatcher context manager enter and exit to verify executor shutdown after use', 'test_batched_atomic_data_predictions': 'test batched predictions on AtomicData objects and verify energy and forces output shapes', 'test_batch_vs_serial_consistency': 'test that batched predictions via executor map match serial FAIRChemCalculator results within tolerance'}
```

## File: facebookresearch_fairchem/tests/core/calculate/test_torchsim_interface.py

Prompts

```
['test the FAIRChemCalculator to compute energy and forces for bulk, slab, and molecular systems', 'test the FormationEnergyCalculator wrapper to compute formation energies from element reference values', 'test creating a FAIRChemCalculator from a pretrained model checkpoint with a specific task name', 'test structure relaxation using BFGS optimizer with a FAIRChemCalculator on a slab system', 'test molecular dynamics simulation using Langevin dynamics with a FAIRChemCalculator on a molecule', 'test InferenceBatcher initialization with custom thread pool concurrency options and max workers', 'test InferenceBatcher initialization with Ray actor options like num_cpus for distributed inference', 'test InferenceBatcher context manager enter and exit to verify executor shutdown after use', 'test batched predictions on AtomicData objects and verify energy and forces output shapes', 'test that batched predictions via executor map match serial FAIRChemCalculator results within tolerance', 'test FairChemModel initialization with oc20 or omol task names and a checkpoint path', 'test batching multiple bulk or molecule systems through FairChemModel for energy and force predictions', 'test stress tensor computation with FairChemModel using a conservative model and compute_stress flag', 'test converting a torch_sim SimState to an AtomicData batch for periodic or molecular systems', 'test FairChemModel handling of charge and spin extras on molecular systems via system_extras_map']
```

Usage

```
{'test_FairChemModel_initialization': 'test FairChemModel initialization with oc20 or omol task names and a checkpoint path', 'test_FairChemModel_homogeneous_batching': 'test batching multiple bulk or molecule systems through FairChemModel for energy and force predictions', 'test_FairChemModel_stress_computation': 'test stress tensor computation with FairChemModel using a conservative model and compute_stress flag', 'test_simstate_to_atomicdata_batch': 'test converting a torch_sim SimState to an AtomicData batch for periodic or molecular systems', 'test_FairChemModel_charge_spin': 'test FairChemModel handling of charge and spin extras on molecular systems via system_extras_map'}
```

