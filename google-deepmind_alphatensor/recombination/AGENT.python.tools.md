# Agent Python Tools

- repo: google-deepmind/alphatensor
- repo_uri: https://github.com/google-deepmind/alphatensor

## File: google-deepmind_alphatensor/recombination/example.py

Prompts

```
['run the alphatensor recombination example to find rank 255 for tensor T_{4,9,10}', 'get the rank-23 factorization matrices u, v, w for the 3x3x3 matrix multiplication tensor', 'recombine base factors to find a lower rank factorization for a target matrix multiplication tensor', 'summarize the alphatensor recombination example that demonstrates finding rank 255 for T_{4,9,10}', 'review the get_3x3x3_factorization function that returns Coppersmith-Winograd rank-23 factorization matrices', 'run recombine to decompose a matrix multiplication tensor using base factors and find the best rank', 'run tensor shape to matrix sizes conversion to get matrix dimensions from a 3D tensor shape', 'run factorization 2D to 3D conversion to reshape factor arrays from 2D to 3D form', 'run block fillings to iterate over all ways to distribute budget items into num_blocks', 'run process additions to compute the nonzero matrix size after adding multiple matrices together', 'test the RecombinationTest class test_example method that verifies recombination.recombine returns rank 255 for a 3x3x3 factorization', 'get the best known rank of a matrix multiplication tensor T_{a, b, c}', 'get the best known rank for a zero-dimension matrix multiplication tensor', 'get the best known rank using the Hopcroft and Kerr formula for dimension 2', 'get the best known rank discovered by AlphaTensor for dimensions 3 through 12', 'get the best known rank with input dimensions automatically sorted before lookup']
```

Usage

```
{'run_recombination_example': 'run the alphatensor recombination example to find rank 255 for tensor T_{4,9,10}', 'get_3x3x3_factorization': 'get the rank-23 factorization matrices u, v, w for the 3x3x3 matrix multiplication tensor', 'recombine_tensor': 'recombine base factors to find a lower rank factorization for a target matrix multiplication tensor', 'summarize_recombination_example': 'summarize the alphatensor recombination example that demonstrates finding rank 255 for T_{4,9,10}', 'review_get_3x3x3_factorization': 'review the get_3x3x3_factorization function that returns Coppersmith-Winograd rank-23 factorization matrices'}
```

## File: google-deepmind_alphatensor/recombination/recombination.py

Prompts

```
['run the alphatensor recombination example to find rank 255 for tensor T_{4,9,10}', 'get the rank-23 factorization matrices u, v, w for the 3x3x3 matrix multiplication tensor', 'recombine base factors to find a lower rank factorization for a target matrix multiplication tensor', 'summarize the alphatensor recombination example that demonstrates finding rank 255 for T_{4,9,10}', 'review the get_3x3x3_factorization function that returns Coppersmith-Winograd rank-23 factorization matrices', 'run recombine to decompose a matrix multiplication tensor using base factors and find the best rank', 'run tensor shape to matrix sizes conversion to get matrix dimensions from a 3D tensor shape', 'run factorization 2D to 3D conversion to reshape factor arrays from 2D to 3D form', 'run block fillings to iterate over all ways to distribute budget items into num_blocks', 'run process additions to compute the nonzero matrix size after adding multiple matrices together', 'test the RecombinationTest class test_example method that verifies recombination.recombine returns rank 255 for a 3x3x3 factorization', 'get the best known rank of a matrix multiplication tensor T_{a, b, c}', 'get the best known rank for a zero-dimension matrix multiplication tensor', 'get the best known rank using the Hopcroft and Kerr formula for dimension 2', 'get the best known rank discovered by AlphaTensor for dimensions 3 through 12', 'get the best known rank with input dimensions automatically sorted before lookup']
```

Usage

```
{'run_recombine': 'run recombine to decompose a matrix multiplication tensor using base factors and find the best rank', 'run_tensor_shape_to_matrix_sizes': 'run tensor shape to matrix sizes conversion to get matrix dimensions from a 3D tensor shape', 'run_factorization_2d_to_3d': 'run factorization 2D to 3D conversion to reshape factor arrays from 2D to 3D form', 'run_block_fillings': 'run block fillings to iterate over all ways to distribute budget items into num_blocks', 'run_process_additions': 'run process additions to compute the nonzero matrix size after adding multiple matrices together'}
```

## File: google-deepmind_alphatensor/recombination/recombination_test.py

Prompts

```
['run the alphatensor recombination example to find rank 255 for tensor T_{4,9,10}', 'get the rank-23 factorization matrices u, v, w for the 3x3x3 matrix multiplication tensor', 'recombine base factors to find a lower rank factorization for a target matrix multiplication tensor', 'summarize the alphatensor recombination example that demonstrates finding rank 255 for T_{4,9,10}', 'review the get_3x3x3_factorization function that returns Coppersmith-Winograd rank-23 factorization matrices', 'run recombine to decompose a matrix multiplication tensor using base factors and find the best rank', 'run tensor shape to matrix sizes conversion to get matrix dimensions from a 3D tensor shape', 'run factorization 2D to 3D conversion to reshape factor arrays from 2D to 3D form', 'run block fillings to iterate over all ways to distribute budget items into num_blocks', 'run process additions to compute the nonzero matrix size after adding multiple matrices together', 'test the RecombinationTest class test_example method that verifies recombination.recombine returns rank 255 for a 3x3x3 factorization', 'get the best known rank of a matrix multiplication tensor T_{a, b, c}', 'get the best known rank for a zero-dimension matrix multiplication tensor', 'get the best known rank using the Hopcroft and Kerr formula for dimension 2', 'get the best known rank discovered by AlphaTensor for dimensions 3 through 12', 'get the best known rank with input dimensions automatically sorted before lookup']
```

Usage

```
{'test_RecombinationTest_test_example': 'test the RecombinationTest class test_example method that verifies recombination.recombine returns rank 255 for a 3x3x3 factorization'}
```

## File: google-deepmind_alphatensor/recombination/sota.py

Prompts

```
['run the alphatensor recombination example to find rank 255 for tensor T_{4,9,10}', 'get the rank-23 factorization matrices u, v, w for the 3x3x3 matrix multiplication tensor', 'recombine base factors to find a lower rank factorization for a target matrix multiplication tensor', 'summarize the alphatensor recombination example that demonstrates finding rank 255 for T_{4,9,10}', 'review the get_3x3x3_factorization function that returns Coppersmith-Winograd rank-23 factorization matrices', 'run recombine to decompose a matrix multiplication tensor using base factors and find the best rank', 'run tensor shape to matrix sizes conversion to get matrix dimensions from a 3D tensor shape', 'run factorization 2D to 3D conversion to reshape factor arrays from 2D to 3D form', 'run block fillings to iterate over all ways to distribute budget items into num_blocks', 'run process additions to compute the nonzero matrix size after adding multiple matrices together', 'test the RecombinationTest class test_example method that verifies recombination.recombine returns rank 255 for a 3x3x3 factorization', 'get the best known rank of a matrix multiplication tensor T_{a, b, c}', 'get the best known rank for a zero-dimension matrix multiplication tensor', 'get the best known rank using the Hopcroft and Kerr formula for dimension 2', 'get the best known rank discovered by AlphaTensor for dimensions 3 through 12', 'get the best known rank with input dimensions automatically sorted before lookup']
```

Usage

```
{'get_sota_rank': 'get the best known rank of a matrix multiplication tensor T_{a, b, c}', 'get_sota_rank_zero': 'get the best known rank for a zero-dimension matrix multiplication tensor', 'get_sota_rank_hopcroft_kerr': 'get the best known rank using the Hopcroft and Kerr formula for dimension 2', 'get_sota_rank_alphatensor': 'get the best known rank discovered by AlphaTensor for dimensions 3 through 12', 'get_sota_rank_sorted': 'get the best known rank with input dimensions automatically sorted before lookup'}
```

