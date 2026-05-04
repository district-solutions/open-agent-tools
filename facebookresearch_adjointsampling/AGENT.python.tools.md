# Agent Python Tools

- repo: facebookresearch/adjointsampling
- repo_uri: https://github.com/facebookresearch/adjoint_sampling

## File: facebookresearch_adjointsampling/eval.py

Prompts

```
['run the eval script to generate molecular conformers using SDE integration and evaluate against reference conformers', 'run the eval script with RDKit to generate baseline conformers for comparison against SDE-generated conformers', 'run the eval script with random torsions to create a baseline where samples have torsions set randomly', 'run the eval script with FairChem energy relaxation to refine sampled conformations using the esen_spice model', 'run the eval script with visualization enabled to save PNG images of generated conformers alongside reference conformers']
```

Usage

```
{'run_eval_conformer_generation': 'run the eval script to generate molecular conformers using SDE integration and evaluate against reference conformers', 'run_eval_rdkit_baseline': 'run the eval script with RDKit to generate baseline conformers for comparison against SDE-generated conformers', 'run_eval_random_torsions': 'run the eval script with random torsions to create a baseline where samples have torsions set randomly', 'run_eval_with_relaxation': 'run the eval script with FairChem energy relaxation to refine sampled conformations using the esen_spice model', 'run_eval_visualize_conformers': 'run the eval script with visualization enabled to save PNG images of generated conformers alongside reference conformers'}
```

