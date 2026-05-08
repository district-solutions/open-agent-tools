# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/applications/cattsunami/tests/test_autoframe_desorption.py

Prompts

```
['test the AutoFrameDesorption class get_neb_frames method to generate Nudged Elastic Band frames for desorption reactions', 'test the Reaction class initialization with desorption reaction database path and adsorbate database path', 'test the OCPCalculator class initialized with an EquiformerV2 model checkpoint for energy and force calculations', 'review the AutoFrameDesorption class and its get_neb_frames method for generating NEB frame sets from reactant systems', 'run the test_autoframe_desorption pytest module to validate AutoFrameDesorption overall functionality with reactant systems and energies', 'test the AutoFrameDissociation class to generate NEB frames for dissociation reactions using an OCP calculator', 'test the interpolate_and_correct_frames function to interpolate between reactant and product frames with edge list correction', 'test the is_edge_list_respected function to verify reactant connectivity against a reaction edge list', 'test the get_ads_syms function to extract chemical symbols from tagged adsorbate atoms in an ASE structure', 'test the AutoFrameTransfer class to generate NEB frames for a chemical reaction using an OCP calculator', 'run interpolate_and_correct_frames to generate interpolated frames between two reaction endpoints with atom mapping', 'test the get_neb_frames method to produce NEB frame sets with specified frame counts and force convergence', 'review the get_ads_syms function that extracts chemical symbols from tagged adsorbate atoms in an ASE atoms object', 'test the Reaction class by loading a dissociation reaction from its database ID', 'test the Reaction class by loading a dissociation reaction from its string representation', 'test the Reaction class by loading a random dissociation reaction and verifying atom types', 'create a Reaction object by specifying the reaction database path and a specific reaction ID', 'create a Reaction object by specifying the reaction database path and a reaction string like *OH -> *O + *H']
```

Usage

```
{'test_AutoFrameDesorption_get_neb_frames': 'test the AutoFrameDesorption class get_neb_frames method to generate Nudged Elastic Band frames for desorption reactions', 'test_Reaction_initialization': 'test the Reaction class initialization with desorption reaction database path and adsorbate database path', 'test_OCPCalculator_with_checkpoint': 'test the OCPCalculator class initialized with an EquiformerV2 model checkpoint for energy and force calculations', 'review_AutoFrameDesorption_class': 'review the AutoFrameDesorption class and its get_neb_frames method for generating NEB frame sets from reactant systems', 'run_test_autoframe_desorption': 'run the test_autoframe_desorption pytest module to validate AutoFrameDesorption overall functionality with reactant systems and energies'}
```

## File: facebookresearch_fairchem/tests/applications/cattsunami/tests/test_autoframe_dissociation.py

Prompts

```
['test the AutoFrameDesorption class get_neb_frames method to generate Nudged Elastic Band frames for desorption reactions', 'test the Reaction class initialization with desorption reaction database path and adsorbate database path', 'test the OCPCalculator class initialized with an EquiformerV2 model checkpoint for energy and force calculations', 'review the AutoFrameDesorption class and its get_neb_frames method for generating NEB frame sets from reactant systems', 'run the test_autoframe_desorption pytest module to validate AutoFrameDesorption overall functionality with reactant systems and energies', 'test the AutoFrameDissociation class to generate NEB frames for dissociation reactions using an OCP calculator', 'test the interpolate_and_correct_frames function to interpolate between reactant and product frames with edge list correction', 'test the is_edge_list_respected function to verify reactant connectivity against a reaction edge list', 'test the get_ads_syms function to extract chemical symbols from tagged adsorbate atoms in an ASE structure', 'test the AutoFrameTransfer class to generate NEB frames for a chemical reaction using an OCP calculator', 'run interpolate_and_correct_frames to generate interpolated frames between two reaction endpoints with atom mapping', 'test the get_neb_frames method to produce NEB frame sets with specified frame counts and force convergence', 'review the get_ads_syms function that extracts chemical symbols from tagged adsorbate atoms in an ASE atoms object', 'test the Reaction class by loading a dissociation reaction from its database ID', 'test the Reaction class by loading a dissociation reaction from its string representation', 'test the Reaction class by loading a random dissociation reaction and verifying atom types', 'create a Reaction object by specifying the reaction database path and a specific reaction ID', 'create a Reaction object by specifying the reaction database path and a reaction string like *OH -> *O + *H']
```

Usage

```
{'test_AutoFrameDissociation_get_neb_frames': 'test the AutoFrameDissociation class to generate NEB frames for dissociation reactions using an OCP calculator', 'test_interpolate_and_correct_frames': 'test the interpolate_and_correct_frames function to interpolate between reactant and product frames with edge list correction', 'test_is_edge_list_respected': 'test the is_edge_list_respected function to verify reactant connectivity against a reaction edge list', 'test_Reaction_initialization': 'test the Reaction class to load dissociation reaction data from a database path and adsorbate pickle', 'test_get_ads_syms': 'test the get_ads_syms function to extract chemical symbols from tagged adsorbate atoms in an ASE structure'}
```

## File: facebookresearch_fairchem/tests/applications/cattsunami/tests/test_autoframe_transfer.py

Prompts

```
['test the AutoFrameDesorption class get_neb_frames method to generate Nudged Elastic Band frames for desorption reactions', 'test the Reaction class initialization with desorption reaction database path and adsorbate database path', 'test the OCPCalculator class initialized with an EquiformerV2 model checkpoint for energy and force calculations', 'review the AutoFrameDesorption class and its get_neb_frames method for generating NEB frame sets from reactant systems', 'run the test_autoframe_desorption pytest module to validate AutoFrameDesorption overall functionality with reactant systems and energies', 'test the AutoFrameDissociation class to generate NEB frames for dissociation reactions using an OCP calculator', 'test the interpolate_and_correct_frames function to interpolate between reactant and product frames with edge list correction', 'test the is_edge_list_respected function to verify reactant connectivity against a reaction edge list', 'test the get_ads_syms function to extract chemical symbols from tagged adsorbate atoms in an ASE structure', 'test the AutoFrameTransfer class to generate NEB frames for a chemical reaction using an OCP calculator', 'run interpolate_and_correct_frames to generate interpolated frames between two reaction endpoints with atom mapping', 'test the get_neb_frames method to produce NEB frame sets with specified frame counts and force convergence', 'review the get_ads_syms function that extracts chemical symbols from tagged adsorbate atoms in an ASE atoms object', 'test the Reaction class by loading a dissociation reaction from its database ID', 'test the Reaction class by loading a dissociation reaction from its string representation', 'test the Reaction class by loading a random dissociation reaction and verifying atom types', 'create a Reaction object by specifying the reaction database path and a specific reaction ID', 'create a Reaction object by specifying the reaction database path and a reaction string like *OH -> *O + *H']
```

Usage

```
{'test_AutoFrameTransfer': 'test the AutoFrameTransfer class to generate NEB frames for a chemical reaction using an OCP calculator', 'run_interpolate_and_correct_frames': 'run interpolate_and_correct_frames to generate interpolated frames between two reaction endpoints with atom mapping', 'test_get_neb_frames': 'test the get_neb_frames method to produce NEB frame sets with specified frame counts and force convergence', 'review_get_ads_syms': 'review the get_ads_syms function that extracts chemical symbols from tagged adsorbate atoms in an ASE atoms object', 'test_Reaction_initialization': 'test the Reaction class initialization with a reaction database path, reaction ID, and adsorbate database path'}
```

## File: facebookresearch_fairchem/tests/applications/cattsunami/tests/test_reaction.py

Prompts

```
['test the AutoFrameDesorption class get_neb_frames method to generate Nudged Elastic Band frames for desorption reactions', 'test the Reaction class initialization with desorption reaction database path and adsorbate database path', 'test the OCPCalculator class initialized with an EquiformerV2 model checkpoint for energy and force calculations', 'review the AutoFrameDesorption class and its get_neb_frames method for generating NEB frame sets from reactant systems', 'run the test_autoframe_desorption pytest module to validate AutoFrameDesorption overall functionality with reactant systems and energies', 'test the AutoFrameDissociation class to generate NEB frames for dissociation reactions using an OCP calculator', 'test the interpolate_and_correct_frames function to interpolate between reactant and product frames with edge list correction', 'test the is_edge_list_respected function to verify reactant connectivity against a reaction edge list', 'test the get_ads_syms function to extract chemical symbols from tagged adsorbate atoms in an ASE structure', 'test the AutoFrameTransfer class to generate NEB frames for a chemical reaction using an OCP calculator', 'run interpolate_and_correct_frames to generate interpolated frames between two reaction endpoints with atom mapping', 'test the get_neb_frames method to produce NEB frame sets with specified frame counts and force convergence', 'review the get_ads_syms function that extracts chemical symbols from tagged adsorbate atoms in an ASE atoms object', 'test the Reaction class by loading a dissociation reaction from its database ID', 'test the Reaction class by loading a dissociation reaction from its string representation', 'test the Reaction class by loading a random dissociation reaction and verifying atom types', 'create a Reaction object by specifying the reaction database path and a specific reaction ID', 'create a Reaction object by specifying the reaction database path and a reaction string like *OH -> *O + *H']
```

Usage

```
{'test_Reaction_loading_from_id': 'test the Reaction class by loading a dissociation reaction from its database ID', 'test_Reaction_loading_from_str': 'test the Reaction class by loading a dissociation reaction from its string representation', 'test_Reaction_loading_from_random': 'test the Reaction class by loading a random dissociation reaction and verifying atom types', 'create_Reaction_from_id': 'create a Reaction object by specifying the reaction database path and a specific reaction ID', 'create_Reaction_from_str': 'create a Reaction object by specifying the reaction database path and a reaction string like *OH -> *O + *H'}
```

