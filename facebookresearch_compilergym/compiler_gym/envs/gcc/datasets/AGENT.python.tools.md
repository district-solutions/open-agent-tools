# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/envs/gcc/datasets/chstone.py

Prompts

```
['create a CHStoneDataset instance with a gcc binary path and site data base directory', 'list all CHStone benchmark URIs by calling benchmark_uris on a CHStoneDataset instance', 'get a Benchmark object from a parsed BenchmarkUri using benchmark_from_parsed_uri method', 'preprocess a C benchmark source file with GCC -E and return the preprocessed Benchmark', 'check the number of benchmarks in the CHStone dataset using the size property', 'create a CsmithBenchmark by generating random C99 source code from a given uint32 seed value', 'create a CsmithDataset instance configured with a GCC binary path and site data base directory', 'install the Csmith include headers into the dataset site data directory for preprocessing', 'generate a CsmithBenchmark from a parsed BenchmarkUri string by extracting the seed value', 'get a random CsmithBenchmark using a numpy random state generator to produce a seed']
```

Usage

```
{'create_CHStoneDataset': 'create a CHStoneDataset instance with a gcc binary path and site data base directory', 'list_benchmark_uris': 'list all CHStone benchmark URIs by calling benchmark_uris on a CHStoneDataset instance', 'get_benchmark_from_uri': 'get a Benchmark object from a parsed BenchmarkUri using benchmark_from_parsed_uri method', 'preprocess_c_benchmark': 'preprocess a C benchmark source file with GCC -E and return the preprocessed Benchmark', 'check_dataset_size': 'check the number of benchmarks in the CHStone dataset using the size property'}
```

## File: facebookresearch_compilergym/compiler_gym/envs/gcc/datasets/csmith.py

Prompts

```
['create a CHStoneDataset instance with a gcc binary path and site data base directory', 'list all CHStone benchmark URIs by calling benchmark_uris on a CHStoneDataset instance', 'get a Benchmark object from a parsed BenchmarkUri using benchmark_from_parsed_uri method', 'preprocess a C benchmark source file with GCC -E and return the preprocessed Benchmark', 'check the number of benchmarks in the CHStone dataset using the size property', 'create a CsmithBenchmark by generating random C99 source code from a given uint32 seed value', 'create a CsmithDataset instance configured with a GCC binary path and site data base directory', 'install the Csmith include headers into the dataset site data directory for preprocessing', 'generate a CsmithBenchmark from a parsed BenchmarkUri string by extracting the seed value', 'get a random CsmithBenchmark using a numpy random state generator to produce a seed']
```

Usage

```
{'create_CsmithBenchmark_from_seed': 'create a CsmithBenchmark by generating random C99 source code from a given uint32 seed value', 'create_CsmithDataset_for_gcc': 'create a CsmithDataset instance configured with a GCC binary path and site data base directory', 'install_CsmithDataset_headers': 'install the Csmith include headers into the dataset site data directory for preprocessing', 'generate_benchmark_from_parsed_uri': 'generate a CsmithBenchmark from a parsed BenchmarkUri string by extracting the seed value', 'get_random_CsmithBenchmark': 'get a random CsmithBenchmark using a numpy random state generator to produce a seed'}
```

