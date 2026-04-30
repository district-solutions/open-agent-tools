# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/optional-skills/research/drug-discovery/scripts/chembl_target.py

Prompts

```
['search ChEMBL for a drug target by name and retrieve its chembl ID, type, and organism', 'retrieve top active compounds for a ChEMBL target filtered by minimum pChEMBL value', 'filter ChEMBL compounds by assay type binding with a minimum pChEMBL threshold', 'deduplicate molecule results by molecule_chembl_id to return only unique compounds', 'run the chembl_target CLI with a target name, minimum pChEMBL, and result limit', 'run the ro5_screen module to check aspirin, ibuprofen, and paracetamol against Lipinski Ro5 and Veber rules', 'test the fetch function to retrieve molecular properties from PubChem for a given compound name', "test the check function to evaluate a compound's property dict against Ro5 and Veber screening criteria", 'summarize how the ro5_screen module performs batch Lipinski Ro5 and Veber drug-likeness screening via the PubChem API', "review the main function's CLI interface that accepts compound names as arguments or reads them from stdin"]
```

Usage

```
{'search_chembl_target': 'search ChEMBL for a drug target by name and retrieve its chembl ID, type, and organism', 'retrieve_active_compounds': 'retrieve top active compounds for a ChEMBL target filtered by minimum pChEMBL value', 'filter_compounds_by_activity': 'filter ChEMBL compounds by assay type binding with a minimum pChEMBL threshold', 'deduplicate_molecule_results': 'deduplicate molecule results by molecule_chembl_id to return only unique compounds', 'run_chembl_target_cli': 'run the chembl_target CLI with a target name, minimum pChEMBL, and result limit'}
```

## File: NousResearch_hermes-agent/optional-skills/research/drug-discovery/scripts/ro5_screen.py

Prompts

```
['search ChEMBL for a drug target by name and retrieve its chembl ID, type, and organism', 'retrieve top active compounds for a ChEMBL target filtered by minimum pChEMBL value', 'filter ChEMBL compounds by assay type binding with a minimum pChEMBL threshold', 'deduplicate molecule results by molecule_chembl_id to return only unique compounds', 'run the chembl_target CLI with a target name, minimum pChEMBL, and result limit', 'run the ro5_screen module to check aspirin, ibuprofen, and paracetamol against Lipinski Ro5 and Veber rules', 'test the fetch function to retrieve molecular properties from PubChem for a given compound name', "test the check function to evaluate a compound's property dict against Ro5 and Veber screening criteria", 'summarize how the ro5_screen module performs batch Lipinski Ro5 and Veber drug-likeness screening via the PubChem API', "review the main function's CLI interface that accepts compound names as arguments or reads them from stdin"]
```

Usage

```
{'run_ro5_screen_compounds': 'run the ro5_screen module to check aspirin, ibuprofen, and paracetamol against Lipinski Ro5 and Veber rules', 'test_fetch_pubchem_property': 'test the fetch function to retrieve molecular properties from PubChem for a given compound name', 'test_check_ro5_violations': "test the check function to evaluate a compound's property dict against Ro5 and Veber screening criteria", 'summarize_ro5_veber_screening': 'summarize how the ro5_screen module performs batch Lipinski Ro5 and Veber drug-likeness screening via the PubChem API', 'review_main_cli_interface': "review the main function's CLI interface that accepts compound names as arguments or reads them from stdin"}
```

