# Agent Python Tools

- repo: google-deepmind/alphagenome
- repo_uri: https://github.com/google-deepmind/alphagenome

## File: google-deepmind_alphagenome/src/alphagenome/interpretation/ism.py

Prompts

```
['create all possible single nucleotide variants for a given genomic interval and sequence', 'build a position-by-base ISM matrix from variant scores and variant list for a genomic interval', 'generate a list of single nucleotide variants skipping N bases for a genomic interval', 'compute the relative effect of variants compared to per-position average scores', 'validate that all positions in an interval are covered by exactly 3 alternative base variants', 'test ism_variants generates all single nucleotide variants for a genomic interval and sequence', 'test ism_variants with skip_n flag to skip N bases in the sequence', 'test ism_matrix constructs a position base matrix from variant scores and variants', 'test ism_matrix with an interval subset to filter variants within a genomic range', 'test ism_matrix raises ValueError for out of bounds interval or use require_fully_filled']
```

Usage

```
{'create_ism_variants': 'create all possible single nucleotide variants for a given genomic interval and sequence', 'build_ism_matrix': 'build a position-by-base ISM matrix from variant scores and variant list for a genomic interval', 'generate_variant_list': 'generate a list of single nucleotide variants skipping N bases for a genomic interval', 'compute_relative_effect': 'compute the relative effect of variants compared to per-position average scores', 'validate_variant_coverage': 'validate that all positions in an interval are covered by exactly 3 alternative base variants'}
```

## File: google-deepmind_alphagenome/src/alphagenome/interpretation/ism_test.py

Prompts

```
['create all possible single nucleotide variants for a given genomic interval and sequence', 'build a position-by-base ISM matrix from variant scores and variant list for a genomic interval', 'generate a list of single nucleotide variants skipping N bases for a genomic interval', 'compute the relative effect of variants compared to per-position average scores', 'validate that all positions in an interval are covered by exactly 3 alternative base variants', 'test ism_variants generates all single nucleotide variants for a genomic interval and sequence', 'test ism_variants with skip_n flag to skip N bases in the sequence', 'test ism_matrix constructs a position base matrix from variant scores and variants', 'test ism_matrix with an interval subset to filter variants within a genomic range', 'test ism_matrix raises ValueError for out of bounds interval or use require_fully_filled']
```

Usage

```
{'test_ism_variants': 'test ism_variants generates all single nucleotide variants for a genomic interval and sequence', 'test_ism_variants_skip_n': 'test ism_variants with skip_n flag to skip N bases in the sequence', 'test_ism_matrix': 'test ism_matrix constructs a position base matrix from variant scores and variants', 'test_ism_matrix_subset': 'test ism_matrix with an interval subset to filter variants within a genomic range', 'test_ism_matrix_missing_variants': 'test ism_matrix raises ValueError for out of bounds interval or use require_fully_filled'}
```

