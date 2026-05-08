# Agent Python Tools

- repo: facebookresearch/qinco
- repo_uri: https://github.com/facebookresearch/qinco

## File: facebookresearch_qinco/qinco_v1/data/deep1b/fbin_to_fvecs.py

Prompts

```
['run the python script to convert an fbin binary file to fvecs format by passing input and output file paths as CLI arguments', 'run the xbin_mmap function to memory map a binary competition file and return a numpy memmap array of shape n by d', 'create an fvecs output file from an fbin input file by writing vectors in batches of 8192 with dimension prefixes', 'review the xbin_mmap function to understand how it validates file size against the expected n times d times dtype itemsize formula', 'refactor the fbin to fvecs conversion script to use a configurable batch size instead of the hardcoded 8192 value']
```

Usage

```
{'run_fbin_to_fvecs_conversion': 'run the python script to convert an fbin binary file to fvecs format by passing input and output file paths as CLI arguments', 'run_xbin_mmap_memory_map': 'run the xbin_mmap function to memory map a binary competition file and return a numpy memmap array of shape n by d', 'create_fvecs_from_fbin': 'create an fvecs output file from an fbin input file by writing vectors in batches of 8192 with dimension prefixes', 'review_xbin_mmap_validation': 'review the xbin_mmap function to understand how it validates file size against the expected n times d times dtype itemsize formula', 'refactor_batch_size': 'refactor the fbin to fvecs conversion script to use a configurable batch size instead of the hardcoded 8192 value'}
```

