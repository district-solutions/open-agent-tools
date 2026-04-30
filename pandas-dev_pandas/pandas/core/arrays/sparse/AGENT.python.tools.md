# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/core/arrays/sparse/accessor.py

Prompts

```
['create a pandas Series with sparse values from a scipy sparse COO matrix', 'convert a pandas Series from sparse values to dense format', 'convert a pandas Series with MultiIndex to a scipy sparse COO matrix', 'create a pandas DataFrame with sparse columns from a scipy sparse matrix', 'convert a pandas DataFrame with sparse columns to dense format', 'convert a pandas DataFrame with sparse columns to a scipy sparse COO matrix', 'get the ratio of non-sparse points to total data points in a sparse Series or DataFrame', 'create a SparseArray from dense data with a specified fill value and kind', 'create a SparseArray from a scipy sparse matrix with a single column', 'build binary arithmetic operations between two SparseArrays with matching or compatible dtypes', 'test SparseArray indexing with integer, slice, and boolean mask indexers', 'summarize SparseArray reduction methods including sum, mean, min, max, all, and any', 'convert a MultiIndexed sparse Series to a scipy.sparse.coo_matrix with specified row and column levels', 'convert a scipy.sparse.coo_matrix to a pandas sparse Series with optional dense index expansion', 'validate that row and column level indices form a partition of the MultiIndex levels', 'extract axis coordinates and labels from a MultiIndexed sparse Series for sparse matrix construction', 'extract values and row/column coordinates (i,j,v triplets) from a MultiIndexed sparse Series for coo_matrix input']
```

Usage

```
{'create_series_from_coo': 'create a pandas Series with sparse values from a scipy sparse COO matrix', 'convert_series_to_dense': 'convert a pandas Series from sparse values to dense format', 'convert_series_to_coo': 'convert a pandas Series with MultiIndex to a scipy sparse COO matrix', 'create_dataframe_from_spmatrix': 'create a pandas DataFrame with sparse columns from a scipy sparse matrix', 'convert_dataframe_to_dense': 'convert a pandas DataFrame with sparse columns to dense format', 'convert_dataframe_to_coo': 'convert a pandas DataFrame with sparse columns to a scipy sparse COO matrix', 'get_sparse_density': 'get the ratio of non-sparse points to total data points in a sparse Series or DataFrame'}
```

## File: pandas-dev_pandas/pandas/core/arrays/sparse/array.py

Prompts

```
['create a pandas Series with sparse values from a scipy sparse COO matrix', 'convert a pandas Series from sparse values to dense format', 'convert a pandas Series with MultiIndex to a scipy sparse COO matrix', 'create a pandas DataFrame with sparse columns from a scipy sparse matrix', 'convert a pandas DataFrame with sparse columns to dense format', 'convert a pandas DataFrame with sparse columns to a scipy sparse COO matrix', 'get the ratio of non-sparse points to total data points in a sparse Series or DataFrame', 'create a SparseArray from dense data with a specified fill value and kind', 'create a SparseArray from a scipy sparse matrix with a single column', 'build binary arithmetic operations between two SparseArrays with matching or compatible dtypes', 'test SparseArray indexing with integer, slice, and boolean mask indexers', 'summarize SparseArray reduction methods including sum, mean, min, max, all, and any', 'convert a MultiIndexed sparse Series to a scipy.sparse.coo_matrix with specified row and column levels', 'convert a scipy.sparse.coo_matrix to a pandas sparse Series with optional dense index expansion', 'validate that row and column level indices form a partition of the MultiIndex levels', 'extract axis coordinates and labels from a MultiIndexed sparse Series for sparse matrix construction', 'extract values and row/column coordinates (i,j,v triplets) from a MultiIndexed sparse Series for coo_matrix input']
```

Usage

```
{'create_sparse_array': 'create a SparseArray from dense data with a specified fill value and kind', 'create_sparse_from_spmatrix': 'create a SparseArray from a scipy sparse matrix with a single column', 'build_sparse_arithmetic': 'build binary arithmetic operations between two SparseArrays with matching or compatible dtypes', 'test_sparse_indexing': 'test SparseArray indexing with integer, slice, and boolean mask indexers', 'summarize_sparse_reductions': 'summarize SparseArray reduction methods including sum, mean, min, max, all, and any'}
```

## File: pandas-dev_pandas/pandas/core/arrays/sparse/scipy_sparse.py

Prompts

```
['create a pandas Series with sparse values from a scipy sparse COO matrix', 'convert a pandas Series from sparse values to dense format', 'convert a pandas Series with MultiIndex to a scipy sparse COO matrix', 'create a pandas DataFrame with sparse columns from a scipy sparse matrix', 'convert a pandas DataFrame with sparse columns to dense format', 'convert a pandas DataFrame with sparse columns to a scipy sparse COO matrix', 'get the ratio of non-sparse points to total data points in a sparse Series or DataFrame', 'create a SparseArray from dense data with a specified fill value and kind', 'create a SparseArray from a scipy sparse matrix with a single column', 'build binary arithmetic operations between two SparseArrays with matching or compatible dtypes', 'test SparseArray indexing with integer, slice, and boolean mask indexers', 'summarize SparseArray reduction methods including sum, mean, min, max, all, and any', 'convert a MultiIndexed sparse Series to a scipy.sparse.coo_matrix with specified row and column levels', 'convert a scipy.sparse.coo_matrix to a pandas sparse Series with optional dense index expansion', 'validate that row and column level indices form a partition of the MultiIndex levels', 'extract axis coordinates and labels from a MultiIndexed sparse Series for sparse matrix construction', 'extract values and row/column coordinates (i,j,v triplets) from a MultiIndexed sparse Series for coo_matrix input']
```

Usage

```
{'convert_sparse_series_to_coo': 'convert a MultiIndexed sparse Series to a scipy.sparse.coo_matrix with specified row and column levels', 'convert_coo_matrix_to_sparse_series': 'convert a scipy.sparse.coo_matrix to a pandas sparse Series with optional dense index expansion', 'validate_index_partition': 'validate that row and column level indices form a partition of the MultiIndex levels', 'extract_axis_coordinates_from_sparse_series': 'extract axis coordinates and labels from a MultiIndexed sparse Series for sparse matrix construction', 'extract_ijv_triplets_from_sparse_series': 'extract values and row/column coordinates (i,j,v triplets) from a MultiIndexed sparse Series for coo_matrix input'}
```

