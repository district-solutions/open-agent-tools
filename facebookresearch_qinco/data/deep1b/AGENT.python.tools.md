# Agent Python Tools

- repo: facebookresearch/qinco
- repo_uri: https://github.com/facebookresearch/qinco

## File: facebookresearch_qinco/data/deep1b/fbin_to_fvecs.py

Prompts

```
['run the script to convert an fbin binary file to fvecs format by passing input and output file paths as arguments', 'use xbin_mmap to memory-map an fbin competition format file and return a numpy memmap array with optional row limit', 'use xbin_mmap to read the n and d header values from an fbin file and validate its size', 'run the script to write fvecs output in batches of 8192 vectors with dimension prepended to each vector', 'use xbin_mmap with the maxn parameter to memory-map only the first N rows of a large fbin file']
```

Usage

```
{'convert_fbin_to_fvecs': 'run the script to convert an fbin binary file to fvecs format by passing input and output file paths as arguments', 'mmap_fbin_file': 'use xbin_mmap to memory-map an fbin competition format file and return a numpy memmap array with optional row limit', 'read_fbin_header': 'use xbin_mmap to read the n and d header values from an fbin file and validate its size', 'batch_write_fvecs': 'run the script to write fvecs output in batches of 8192 vectors with dimension prepended to each vector', 'limit_mmap_rows': 'use xbin_mmap with the maxn parameter to memory-map only the first N rows of a large fbin file'}
```

