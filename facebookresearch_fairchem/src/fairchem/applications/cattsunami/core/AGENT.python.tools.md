# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/applications/cattsunami/core/autoframe.py

Prompts

```
['create an AutoFrameDissociation instance and call get_neb_frames to generate NEB frames for a dissociation reaction', 'create an AutoFrameTransfer instance and call get_neb_frames to generate NEB frames for a transfer reaction', 'create an AutoFrameDesorption instance and call get_neb_frames to generate NEB frames for a desorption reaction', 'run interpolate_and_correct_frames to unwrap, interpolate, and correct atomic overlap between initial and final NEB frames', 'run is_edge_list_respected to check if an ASE Atoms frame has the expected adsorbate-adsorbate bonding edges', 'create a Reaction object for a dissociation reaction using reaction and adsorbate database paths', 'create a Reaction object for a desorption reaction using reaction and adsorbate database paths', 'create a Reaction object for a transfer reaction using reaction and adsorbate database paths', 'create a Reaction object by specifying a specific reaction ID from the reaction database', 'get the atom index mapping for a desorption reaction using the get_desorption_mapping method']
```

Usage

```
{'create_AutoFrameDissociation_neb_frames': 'create an AutoFrameDissociation instance and call get_neb_frames to generate NEB frames for a dissociation reaction', 'create_AutoFrameTransfer_neb_frames': 'create an AutoFrameTransfer instance and call get_neb_frames to generate NEB frames for a transfer reaction', 'create_AutoFrameDesorption_neb_frames': 'create an AutoFrameDesorption instance and call get_neb_frames to generate NEB frames for a desorption reaction', 'run_interpolate_and_correct_frames': 'run interpolate_and_correct_frames to unwrap, interpolate, and correct atomic overlap between initial and final NEB frames', 'run_is_edge_list_respected': 'run is_edge_list_respected to check if an ASE Atoms frame has the expected adsorbate-adsorbate bonding edges'}
```

## File: facebookresearch_fairchem/src/fairchem/applications/cattsunami/core/reaction.py

Prompts

```
['create an AutoFrameDissociation instance and call get_neb_frames to generate NEB frames for a dissociation reaction', 'create an AutoFrameTransfer instance and call get_neb_frames to generate NEB frames for a transfer reaction', 'create an AutoFrameDesorption instance and call get_neb_frames to generate NEB frames for a desorption reaction', 'run interpolate_and_correct_frames to unwrap, interpolate, and correct atomic overlap between initial and final NEB frames', 'run is_edge_list_respected to check if an ASE Atoms frame has the expected adsorbate-adsorbate bonding edges', 'create a Reaction object for a dissociation reaction using reaction and adsorbate database paths', 'create a Reaction object for a desorption reaction using reaction and adsorbate database paths', 'create a Reaction object for a transfer reaction using reaction and adsorbate database paths', 'create a Reaction object by specifying a specific reaction ID from the reaction database', 'get the atom index mapping for a desorption reaction using the get_desorption_mapping method']
```

Usage

```
{'create_reaction_dissociation': 'create a Reaction object for a dissociation reaction using reaction and adsorbate database paths', 'create_reaction_desorption': 'create a Reaction object for a desorption reaction using reaction and adsorbate database paths', 'create_reaction_transfer': 'create a Reaction object for a transfer reaction using reaction and adsorbate database paths', 'create_reaction_by_id': 'create a Reaction object by specifying a specific reaction ID from the reaction database', 'get_desorption_mapping': 'get the atom index mapping for a desorption reaction using the get_desorption_mapping method'}
```

