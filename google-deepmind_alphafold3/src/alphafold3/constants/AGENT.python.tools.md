# Agent Python Tools

- repo: google-deepmind/alphafold3
- repo_uri: https://github.com/google-deepmind/alphafold3

## File: google-deepmind_alphafold3/src/alphafold3/constants/chemical_components.py

Prompts

```
['create a Ccd instance with a custom user CCD string to override default chemical components', 'lookup a chemical component by residue name using component_name_to_info and return its ComponentInfo', 'get the element type symbol for a given residue and atom name using type_symbol', 'convert an mmCIF mapping to a ComponentInfo dataclass using mmcif_to_info', 'iterate over all chemical component keys in a Ccd instance using its Mapping interface', 'check if a given chain type string is a standard protein, DNA, or RNA polymer', 'guess whether a chain is protein, RNA, or DNA based on a list of residue names', 'convert a non-standard residue name to the closest standard protein, RNA, or DNA residue name', 'review the mmCIF chain type constants like PROTEIN_CHAIN, DNA_CHAIN, and RNA_CHAIN for entity classification', 'review the mmCIF bond type constants like COVALENT_BOND, HYDROGEN_BOND, and DISULFIDE_BRIDGE', 'use letters_three_to_one to convert a CCD residue name like CYS to its single letter code C', 'reference PROTEIN_TYPES to get the tuple of 20 standard amino acid three-letter codes', 'use PROTEIN_TYPES_ONE_LETTER_TO_INT to convert a single letter amino acid code to its integer index', 'use PROTEIN_COMMON_ONE_TO_THREE to map a single letter amino acid code to its three-letter CCD name', 'use POLYMER_TYPES_ORDER to get the integer index of any protein or nucleic acid residue type']
```

Usage

```
{'create_Ccd_with_user_ccd': 'create a Ccd instance with a custom user CCD string to override default chemical components', 'lookup_component_info': 'lookup a chemical component by residue name using component_name_to_info and return its ComponentInfo', 'get_element_type_symbol': 'get the element type symbol for a given residue and atom name using type_symbol', 'convert_mmcif_to_info': 'convert an mmCIF mapping to a ComponentInfo dataclass using mmcif_to_info', 'iterate_ccd_entries': 'iterate over all chemical component keys in a Ccd instance using its Mapping interface'}
```

## File: google-deepmind_alphafold3/src/alphafold3/constants/mmcif_names.py

Prompts

```
['create a Ccd instance with a custom user CCD string to override default chemical components', 'lookup a chemical component by residue name using component_name_to_info and return its ComponentInfo', 'get the element type symbol for a given residue and atom name using type_symbol', 'convert an mmCIF mapping to a ComponentInfo dataclass using mmcif_to_info', 'iterate over all chemical component keys in a Ccd instance using its Mapping interface', 'check if a given chain type string is a standard protein, DNA, or RNA polymer', 'guess whether a chain is protein, RNA, or DNA based on a list of residue names', 'convert a non-standard residue name to the closest standard protein, RNA, or DNA residue name', 'review the mmCIF chain type constants like PROTEIN_CHAIN, DNA_CHAIN, and RNA_CHAIN for entity classification', 'review the mmCIF bond type constants like COVALENT_BOND, HYDROGEN_BOND, and DISULFIDE_BRIDGE', 'use letters_three_to_one to convert a CCD residue name like CYS to its single letter code C', 'reference PROTEIN_TYPES to get the tuple of 20 standard amino acid three-letter codes', 'use PROTEIN_TYPES_ONE_LETTER_TO_INT to convert a single letter amino acid code to its integer index', 'use PROTEIN_COMMON_ONE_TO_THREE to map a single letter amino acid code to its three-letter CCD name', 'use POLYMER_TYPES_ORDER to get the integer index of any protein or nucleic acid residue type']
```

Usage

```
{'is_standard_polymer_type': 'check if a given chain type string is a standard protein, DNA, or RNA polymer', 'guess_polymer_type': 'guess whether a chain is protein, RNA, or DNA based on a list of residue names', 'fix_non_standard_polymer_res': 'convert a non-standard residue name to the closest standard protein, RNA, or DNA residue name', 'review_mmcif_chain_constants': 'review the mmCIF chain type constants like PROTEIN_CHAIN, DNA_CHAIN, and RNA_CHAIN for entity classification', 'review_mmcif_bond_constants': 'review the mmCIF bond type constants like COVALENT_BOND, HYDROGEN_BOND, and DISULFIDE_BRIDGE'}
```

## File: google-deepmind_alphafold3/src/alphafold3/constants/residue_names.py

Prompts

```
['create a Ccd instance with a custom user CCD string to override default chemical components', 'lookup a chemical component by residue name using component_name_to_info and return its ComponentInfo', 'get the element type symbol for a given residue and atom name using type_symbol', 'convert an mmCIF mapping to a ComponentInfo dataclass using mmcif_to_info', 'iterate over all chemical component keys in a Ccd instance using its Mapping interface', 'check if a given chain type string is a standard protein, DNA, or RNA polymer', 'guess whether a chain is protein, RNA, or DNA based on a list of residue names', 'convert a non-standard residue name to the closest standard protein, RNA, or DNA residue name', 'review the mmCIF chain type constants like PROTEIN_CHAIN, DNA_CHAIN, and RNA_CHAIN for entity classification', 'review the mmCIF bond type constants like COVALENT_BOND, HYDROGEN_BOND, and DISULFIDE_BRIDGE', 'use letters_three_to_one to convert a CCD residue name like CYS to its single letter code C', 'reference PROTEIN_TYPES to get the tuple of 20 standard amino acid three-letter codes', 'use PROTEIN_TYPES_ONE_LETTER_TO_INT to convert a single letter amino acid code to its integer index', 'use PROTEIN_COMMON_ONE_TO_THREE to map a single letter amino acid code to its three-letter CCD name', 'use POLYMER_TYPES_ORDER to get the integer index of any protein or nucleic acid residue type']
```

Usage

```
{'convert_ccd_residue_to_one_letter': 'use letters_three_to_one to convert a CCD residue name like CYS to its single letter code C', 'lookup_standard_protein_types': 'reference PROTEIN_TYPES to get the tuple of 20 standard amino acid three-letter codes', 'map_one_letter_to_int': 'use PROTEIN_TYPES_ONE_LETTER_TO_INT to convert a single letter amino acid code to its integer index', 'convert_one_to_three_letter': 'use PROTEIN_COMMON_ONE_TO_THREE to map a single letter amino acid code to its three-letter CCD name', 'check_polymer_type_order': 'use POLYMER_TYPES_ORDER to get the integer index of any protein or nucleic acid residue type'}
```

