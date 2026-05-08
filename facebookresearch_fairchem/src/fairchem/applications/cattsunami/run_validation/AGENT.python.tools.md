# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/applications/cattsunami/run_validation/run_validation.py

Prompts

```
['run a validation of the ML NEB model on a set of NEB calculations using DyNEB and BFGS optimization', 'get the percent success and convergence for the ML NEB model with single points performed on transition states', 'get the percent success and convergence for the ML NEB model using just ML energy and force calls', 'process ML NEB results to extract barrier height, reaction energy, convergence status, and transition state index', 'get a single point energy and forces calculation on atoms using VASP with specified INCAR flags']
```

Usage

```
{'run_validation_ml_neb': 'run a validation of the ML NEB model on a set of NEB calculations using DyNEB and BFGS optimization', 'get_results_sp': 'get the percent success and convergence for the ML NEB model with single points performed on transition states', 'get_results_ml': 'get the percent success and convergence for the ML NEB model using just ML energy and force calls', 'parse_neb_info': 'process ML NEB results to extract barrier height, reaction energy, convergence status, and transition state index', 'get_single_point': 'get a single point energy and forces calculation on atoms using VASP with specified INCAR flags'}
```

