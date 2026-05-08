# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/demo/ocpapi/client/client.py

Prompts

```
['fetch the list of models supported in the OCP API using the client', 'fetch the list of bulk materials supported in the OCP API using the client', 'fetch the list of adsorbates supported in the OCP API using the client', 'submit adsorbate slab relaxation jobs to the OCP API using a specified model', 'fetch relaxation results for a given system ID from the OCP API', 'convert an Atoms dataclass to an ASE Atoms object with fixed sub-surface atom constraints', 'convert an AdsorbateSlabRelaxationResult to an ASE Atoms object with energy and forces via SinglePointCalculator', 'create an AdsorbateSlabRelaxationsRequest dataclass with adsorbate configs, bulk, slab, and model fields', 'check the Status enum values for relaxation results including SUCCESS, FAILED_RELAXATION, and NOT_AVAILABLE', 'parse an AdsorbateSlabConfigs response containing adsorbate placement structures and the parent slab', 'get the results UI URL for a given API host and system ID', 'build a python module to generate a visualization URL from an API host and system ID', 'test the get_results_ui_url function with a known API host and system ID', 'refactor the get_results_ui_url function to support additional API to UI host mappings', 'review the get_results_ui_url function and its API to UI host mapping logic']
```

Usage

```
{'get_supported_models': 'fetch the list of models supported in the OCP API using the client', 'get_bulk_materials': 'fetch the list of bulk materials supported in the OCP API using the client', 'get_adsorbates': 'fetch the list of adsorbates supported in the OCP API using the client', 'submit_adsorbate_slab_relaxations': 'submit adsorbate slab relaxation jobs to the OCP API using a specified model', 'get_relaxation_results': 'fetch relaxation results for a given system ID from the OCP API'}
```

## File: facebookresearch_fairchem/src/fairchem/demo/ocpapi/client/models.py

Prompts

```
['fetch the list of models supported in the OCP API using the client', 'fetch the list of bulk materials supported in the OCP API using the client', 'fetch the list of adsorbates supported in the OCP API using the client', 'submit adsorbate slab relaxation jobs to the OCP API using a specified model', 'fetch relaxation results for a given system ID from the OCP API', 'convert an Atoms dataclass to an ASE Atoms object with fixed sub-surface atom constraints', 'convert an AdsorbateSlabRelaxationResult to an ASE Atoms object with energy and forces via SinglePointCalculator', 'create an AdsorbateSlabRelaxationsRequest dataclass with adsorbate configs, bulk, slab, and model fields', 'check the Status enum values for relaxation results including SUCCESS, FAILED_RELAXATION, and NOT_AVAILABLE', 'parse an AdsorbateSlabConfigs response containing adsorbate placement structures and the parent slab', 'get the results UI URL for a given API host and system ID', 'build a python module to generate a visualization URL from an API host and system ID', 'test the get_results_ui_url function with a known API host and system ID', 'refactor the get_results_ui_url function to support additional API to UI host mappings', 'review the get_results_ui_url function and its API to UI host mapping logic']
```

Usage

```
{'convert_atoms_to_ase': 'convert an Atoms dataclass to an ASE Atoms object with fixed sub-surface atom constraints', 'convert_relaxation_result_to_ase': 'convert an AdsorbateSlabRelaxationResult to an ASE Atoms object with energy and forces via SinglePointCalculator', 'create_adsorbate_slab_relaxation_request': 'create an AdsorbateSlabRelaxationsRequest dataclass with adsorbate configs, bulk, slab, and model fields', 'check_relaxation_status': 'check the Status enum values for relaxation results including SUCCESS, FAILED_RELAXATION, and NOT_AVAILABLE', 'parse_adsorbate_slab_configs': 'parse an AdsorbateSlabConfigs response containing adsorbate placement structures and the parent slab'}
```

## File: facebookresearch_fairchem/src/fairchem/demo/ocpapi/client/ui.py

Prompts

```
['fetch the list of models supported in the OCP API using the client', 'fetch the list of bulk materials supported in the OCP API using the client', 'fetch the list of adsorbates supported in the OCP API using the client', 'submit adsorbate slab relaxation jobs to the OCP API using a specified model', 'fetch relaxation results for a given system ID from the OCP API', 'convert an Atoms dataclass to an ASE Atoms object with fixed sub-surface atom constraints', 'convert an AdsorbateSlabRelaxationResult to an ASE Atoms object with energy and forces via SinglePointCalculator', 'create an AdsorbateSlabRelaxationsRequest dataclass with adsorbate configs, bulk, slab, and model fields', 'check the Status enum values for relaxation results including SUCCESS, FAILED_RELAXATION, and NOT_AVAILABLE', 'parse an AdsorbateSlabConfigs response containing adsorbate placement structures and the parent slab', 'get the results UI URL for a given API host and system ID', 'build a python module to generate a visualization URL from an API host and system ID', 'test the get_results_ui_url function with a known API host and system ID', 'refactor the get_results_ui_url function to support additional API to UI host mappings', 'review the get_results_ui_url function and its API to UI host mapping logic']
```

Usage

```
{'get_results_ui_url': 'get the results UI URL for a given API host and system ID', 'build_get_results_ui_url': 'build a python module to generate a visualization URL from an API host and system ID', 'test_get_results_ui_url': 'test the get_results_ui_url function with a known API host and system ID', 'refactor_get_results_ui_url': 'refactor the get_results_ui_url function to support additional API to UI host mappings', 'review_get_results_ui_url': 'review the get_results_ui_url function and its API to UI host mapping logic'}
```

