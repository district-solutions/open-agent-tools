# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/applications/AdsorbML/adsorbml/scripts/dense_eval.py

Prompts

```
['run the dense evaluation script to compute AdsorbML hybrid ML+DFT success rates for top-k configurations', 'run the dense evaluation script with --ml-success to compute validated ML-only success rates', 'compute AdsorbML hybrid success rates at varying top-k values comparing ML+DFT energies to ground truth DFT', 'compute validated ML success rates where ML energies must be within 0.1 eV of DFT energy', 'filter ML data by setting missing systems or configs to high energy values for failure case evaluation', 'run the script to process ML relaxation trajectories and group them by adsorbate-surface system', 'run the min_diff function to compare atom positions between initial and final structures with PBC', 'run the process_mlrs function on a single trajectory to detect anomalies and extract relaxed energy', 'refactor the process_mlrs function to use a custom anomaly detection strategy instead of DetectTrajAnomaly', 'review the parse_args function to add new CLI arguments for filtering trajectory results', 'check if a VASP DFT calculation converged electronically by parsing the OSZICAR file', 'count the total SCF and ionic steps from VASP OSZICAR output files in a directory', 'review the converged_oszicar function to understand how it checks VASP electronic convergence using NELM and EDIFF thresholds', 'refactor the converged_oszicar function to support custom convergence criteria or additional VASP output formats', 'summarize the count_scf function that aggregates SCF and ionic step counts across all OSZICAR files in a path']
```

Usage

```
{'run_dense_eval_hybrid': 'run the dense evaluation script to compute AdsorbML hybrid ML+DFT success rates for top-k configurations', 'run_dense_eval_ml_only': 'run the dense evaluation script with --ml-success to compute validated ML-only success rates', 'compute_hybrid_success': 'compute AdsorbML hybrid success rates at varying top-k values comparing ML+DFT energies to ground truth DFT', 'compute_valid_ml_success': 'compute validated ML success rates where ML energies must be within 0.1 eV of DFT energy', 'filter_ml_data': 'filter ML data by setting missing systems or configs to high energy values for failure case evaluation'}
```

## File: facebookresearch_fairchem/src/fairchem/applications/AdsorbML/adsorbml/scripts/process_mlrs.py

Prompts

```
['run the dense evaluation script to compute AdsorbML hybrid ML+DFT success rates for top-k configurations', 'run the dense evaluation script with --ml-success to compute validated ML-only success rates', 'compute AdsorbML hybrid success rates at varying top-k values comparing ML+DFT energies to ground truth DFT', 'compute validated ML success rates where ML energies must be within 0.1 eV of DFT energy', 'filter ML data by setting missing systems or configs to high energy values for failure case evaluation', 'run the script to process ML relaxation trajectories and group them by adsorbate-surface system', 'run the min_diff function to compare atom positions between initial and final structures with PBC', 'run the process_mlrs function on a single trajectory to detect anomalies and extract relaxed energy', 'refactor the process_mlrs function to use a custom anomaly detection strategy instead of DetectTrajAnomaly', 'review the parse_args function to add new CLI arguments for filtering trajectory results', 'check if a VASP DFT calculation converged electronically by parsing the OSZICAR file', 'count the total SCF and ionic steps from VASP OSZICAR output files in a directory', 'review the converged_oszicar function to understand how it checks VASP electronic convergence using NELM and EDIFF thresholds', 'refactor the converged_oszicar function to support custom convergence criteria or additional VASP output formats', 'summarize the count_scf function that aggregates SCF and ionic step counts across all OSZICAR files in a path']
```

Usage

```
{'run_process_mlrs': 'run the script to process ML relaxation trajectories and group them by adsorbate-surface system', 'run_min_diff': 'run the min_diff function to compare atom positions between initial and final structures with PBC', 'run_process_mlrs_single': 'run the process_mlrs function on a single trajectory to detect anomalies and extract relaxed energy', 'refactor_process_mlrs': 'refactor the process_mlrs function to use a custom anomaly detection strategy instead of DetectTrajAnomaly', 'review_parse_args': 'review the parse_args function to add new CLI arguments for filtering trajectory results'}
```

## File: facebookresearch_fairchem/src/fairchem/applications/AdsorbML/adsorbml/scripts/utils.py

Prompts

```
['run the dense evaluation script to compute AdsorbML hybrid ML+DFT success rates for top-k configurations', 'run the dense evaluation script with --ml-success to compute validated ML-only success rates', 'compute AdsorbML hybrid success rates at varying top-k values comparing ML+DFT energies to ground truth DFT', 'compute validated ML success rates where ML energies must be within 0.1 eV of DFT energy', 'filter ML data by setting missing systems or configs to high energy values for failure case evaluation', 'run the script to process ML relaxation trajectories and group them by adsorbate-surface system', 'run the min_diff function to compare atom positions between initial and final structures with PBC', 'run the process_mlrs function on a single trajectory to detect anomalies and extract relaxed energy', 'refactor the process_mlrs function to use a custom anomaly detection strategy instead of DetectTrajAnomaly', 'review the parse_args function to add new CLI arguments for filtering trajectory results', 'check if a VASP DFT calculation converged electronically by parsing the OSZICAR file', 'count the total SCF and ionic steps from VASP OSZICAR output files in a directory', 'review the converged_oszicar function to understand how it checks VASP electronic convergence using NELM and EDIFF thresholds', 'refactor the converged_oszicar function to support custom convergence criteria or additional VASP output formats', 'summarize the count_scf function that aggregates SCF and ionic step counts across all OSZICAR files in a path']
```

Usage

```
{'check_vasp_electronic_convergence': 'check if a VASP DFT calculation converged electronically by parsing the OSZICAR file', 'count_vasp_scf_steps': 'count the total SCF and ionic steps from VASP OSZICAR output files in a directory', 'review_converged_oszicar': 'review the converged_oszicar function to understand how it checks VASP electronic convergence using NELM and EDIFF thresholds', 'refactor_converged_oszicar': 'refactor the converged_oszicar function to support custom convergence criteria or additional VASP output formats', 'summarize_count_scf': 'summarize the count_scf function that aggregates SCF and ionic step counts across all OSZICAR files in a path'}
```

