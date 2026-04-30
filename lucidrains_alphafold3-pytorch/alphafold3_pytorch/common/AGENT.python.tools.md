# Agent Python Tools

- repo: lucidrains/alphafold3-pytorch
- repo_uri: https://github.com/lucidrains/alphafold3-pytorch

## File: lucidrains_alphafold3-pytorch/alphafold3_pytorch/common/biomolecule.py

Prompts

```
['create a Biomolecule object from an mmCIF string given a file ID and optional chain filters', 'convert a Biomolecule instance back to a valid mmCIF string with optional gapless polymer sequencing', 'crop a Biomolecule to contiguous polymer residues using per-chain contiguous crop masks', 'crop a Biomolecule to residues near a reference atom within a specified distance threshold', 'merge two Biomolecule instances by concatenating their atom positions, masks, and metadata arrays', 'add AlphaFold metadata including license, citation, model info, and pLDDT metrics to an mmCIF dictionary', 'create mmCIF metadata dictionary with ModelCIF conformation, authors, and software version from an existing cif mapping', 'run mmCIF metadata insertion with coevolution MSA, template search, and modeling protocol steps', 'summarize the mmCIF metadata module that adds AlphaFold3 model metadata to mmCIF files', 'review the add_metadata_to_mmcif function that enriches mmCIF data with ModelCIF-compliant metadata fields']
```

Usage

```
{'create_biomolecule_from_mmcif': 'create a Biomolecule object from an mmCIF string given a file ID and optional chain filters', 'convert_biomolecule_to_mmcif': 'convert a Biomolecule instance back to a valid mmCIF string with optional gapless polymer sequencing', 'crop_biomolecule_contiguously': 'crop a Biomolecule to contiguous polymer residues using per-chain contiguous crop masks', 'crop_biomolecule_spatially': 'crop a Biomolecule to residues near a reference atom within a specified distance threshold', 'merge_two_biomolecules': 'merge two Biomolecule instances by concatenating their atom positions, masks, and metadata arrays'}
```

## File: lucidrains_alphafold3-pytorch/alphafold3_pytorch/common/mmcif_metadata.py

Prompts

```
['create a Biomolecule object from an mmCIF string given a file ID and optional chain filters', 'convert a Biomolecule instance back to a valid mmCIF string with optional gapless polymer sequencing', 'crop a Biomolecule to contiguous polymer residues using per-chain contiguous crop masks', 'crop a Biomolecule to residues near a reference atom within a specified distance threshold', 'merge two Biomolecule instances by concatenating their atom positions, masks, and metadata arrays', 'add AlphaFold metadata including license, citation, model info, and pLDDT metrics to an mmCIF dictionary', 'create mmCIF metadata dictionary with ModelCIF conformation, authors, and software version from an existing cif mapping', 'run mmCIF metadata insertion with coevolution MSA, template search, and modeling protocol steps', 'summarize the mmCIF metadata module that adds AlphaFold3 model metadata to mmCIF files', 'review the add_metadata_to_mmcif function that enriches mmCIF data with ModelCIF-compliant metadata fields']
```

Usage

```
{'add_metadata_to_mmcif': 'add AlphaFold metadata including license, citation, model info, and pLDDT metrics to an mmCIF dictionary', 'create_mmcif_metadata': 'create mmCIF metadata dictionary with ModelCIF conformation, authors, and software version from an existing cif mapping', 'run_mmcif_metadata_pipeline': 'run mmCIF metadata insertion with coevolution MSA, template search, and modeling protocol steps', 'summarize_mmcif_metadata': 'summarize the mmCIF metadata module that adds AlphaFold3 model metadata to mmCIF files', 'review_mmcif_metadata': 'review the add_metadata_to_mmcif function that enriches mmCIF data with ModelCIF-compliant metadata fields'}
```

