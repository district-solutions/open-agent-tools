# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/demo/ocpapi/tests/unit/client/test_client.py

Prompts

```
['get the list of available ML models from the OCP API using the Client', 'get the list of supported bulk materials from the OCP API using the Client', 'generate slab structures from a bulk material by passing a bulk ID or Bulk object to the Client', 'submit an adsorbate-slab relaxation job to the OCP API with adsorbate, configs, bulk, slab, and model', 'retrieve relaxation results for a system by system_id with optional config_ids and fields filters', 'This file is a unit test module (test_models.py) containing only unittest.TestCase subclasses for testing JSON serialization/deserialization of OCP API client data models. It has no standalone callable functions, CLI entry points, or externally usable APIs. All classes are test fixtures that require pytest/unittest to run.', 'test the Model data model JSON serialization and deserialization round-trip', 'test the Atoms model conversion to ASE Atoms objects with constraints', 'test the AdsorbateSlabRelaxationsRequest model JSON serialization with all fields', 'test the AdsorbateSlabRelaxationResult conversion to ASE Atoms with energy and forces', 'test the Slab model JSON serialization including nested atoms and metadata', 'test the get_results_ui_url function with prod and unknown host cases', 'run the TestUI unit test class to verify get_results_ui_url behavior', 'review the TestUI class and its test_get_results_ui_url test method', 'refactor the TestUI class to add more test cases for get_results_ui_url', 'summarize the TestUI class which tests get_results_ui_url for prod and unknown hosts']
```

Usage

```
{'get_models': 'get the list of available ML models from the OCP API using the Client', 'get_bulks': 'get the list of supported bulk materials from the OCP API using the Client', 'get_slabs': 'generate slab structures from a bulk material by passing a bulk ID or Bulk object to the Client', 'submit_adsorbate_slab_relaxations': 'submit an adsorbate-slab relaxation job to the OCP API with adsorbate, configs, bulk, slab, and model', 'get_adsorbate_slab_relaxations_results': 'retrieve relaxation results for a system by system_id with optional config_ids and fields filters'}
```

## File: facebookresearch_fairchem/tests/demo/ocpapi/tests/unit/client/test_models.py

Prompts

```
['get the list of available ML models from the OCP API using the Client', 'get the list of supported bulk materials from the OCP API using the Client', 'generate slab structures from a bulk material by passing a bulk ID or Bulk object to the Client', 'submit an adsorbate-slab relaxation job to the OCP API with adsorbate, configs, bulk, slab, and model', 'retrieve relaxation results for a system by system_id with optional config_ids and fields filters', 'This file is a unit test module (test_models.py) containing only unittest.TestCase subclasses for testing JSON serialization/deserialization of OCP API client data models. It has no standalone callable functions, CLI entry points, or externally usable APIs. All classes are test fixtures that require pytest/unittest to run.', 'test the Model data model JSON serialization and deserialization round-trip', 'test the Atoms model conversion to ASE Atoms objects with constraints', 'test the AdsorbateSlabRelaxationsRequest model JSON serialization with all fields', 'test the AdsorbateSlabRelaxationResult conversion to ASE Atoms with energy and forces', 'test the Slab model JSON serialization including nested atoms and metadata', 'test the get_results_ui_url function with prod and unknown host cases', 'run the TestUI unit test class to verify get_results_ui_url behavior', 'review the TestUI class and its test_get_results_ui_url test method', 'refactor the TestUI class to add more test cases for get_results_ui_url', 'summarize the TestUI class which tests get_results_ui_url for prod and unknown hosts']
```

Usage

```
{'note': 'This file is a unit test module (test_models.py) containing only unittest.TestCase subclasses for testing JSON serialization/deserialization of OCP API client data models. It has no standalone callable functions, CLI entry points, or externally usable APIs. All classes are test fixtures that require pytest/unittest to run.', 'test_Model_serde': 'test the Model data model JSON serialization and deserialization round-trip', 'test_Atoms_to_ase_atoms': 'test the Atoms model conversion to ASE Atoms objects with constraints', 'test_AdsorbateSlabRelaxationsRequest_serde': 'test the AdsorbateSlabRelaxationsRequest model JSON serialization with all fields', 'test_AdsorbateSlabRelaxationResult_to_ase': 'test the AdsorbateSlabRelaxationResult conversion to ASE Atoms with energy and forces', 'test_Slab_serde': 'test the Slab model JSON serialization including nested atoms and metadata'}
```

## File: facebookresearch_fairchem/tests/demo/ocpapi/tests/unit/client/test_ui.py

Prompts

```
['get the list of available ML models from the OCP API using the Client', 'get the list of supported bulk materials from the OCP API using the Client', 'generate slab structures from a bulk material by passing a bulk ID or Bulk object to the Client', 'submit an adsorbate-slab relaxation job to the OCP API with adsorbate, configs, bulk, slab, and model', 'retrieve relaxation results for a system by system_id with optional config_ids and fields filters', 'This file is a unit test module (test_models.py) containing only unittest.TestCase subclasses for testing JSON serialization/deserialization of OCP API client data models. It has no standalone callable functions, CLI entry points, or externally usable APIs. All classes are test fixtures that require pytest/unittest to run.', 'test the Model data model JSON serialization and deserialization round-trip', 'test the Atoms model conversion to ASE Atoms objects with constraints', 'test the AdsorbateSlabRelaxationsRequest model JSON serialization with all fields', 'test the AdsorbateSlabRelaxationResult conversion to ASE Atoms with energy and forces', 'test the Slab model JSON serialization including nested atoms and metadata', 'test the get_results_ui_url function with prod and unknown host cases', 'run the TestUI unit test class to verify get_results_ui_url behavior', 'review the TestUI class and its test_get_results_ui_url test method', 'refactor the TestUI class to add more test cases for get_results_ui_url', 'summarize the TestUI class which tests get_results_ui_url for prod and unknown hosts']
```

Usage

```
{'test_get_results_ui_url': 'test the get_results_ui_url function with prod and unknown host cases', 'run_test_ui': 'run the TestUI unit test class to verify get_results_ui_url behavior', 'review_test_ui': 'review the TestUI class and its test_get_results_ui_url test method', 'refactor_test_ui': 'refactor the TestUI class to add more test cases for get_results_ui_url', 'summarize_test_ui': 'summarize the TestUI class which tests get_results_ui_url for prod and unknown hosts'}
```

