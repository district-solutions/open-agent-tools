# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/core/arrays/arrow/_arrow_utils.py

Prompts

```
['convert a primitive pyarrow.Array to a numpy array and boolean validity mask with specified dtype', 'handle a null-typed pyarrow.Array by returning empty data and all-false mask', 'extract data from an arrow buffer using offset and length for numpy frombuffer conversion', 'decode a pyarrow validity bitmask into a boolean numpy array using BooleanArray.from_buffers', 'convert a pyarrow.Array to numpy data and a boolean mask where False means missing', 'create a list accessor that returns the length of each list in a pandas Series with arrow list dtype', 'create a list accessor that indexes or slices lists in a pandas Series by integer or slice', 'create a list accessor that flattens list values in a pandas Series into separate rows', 'create a struct accessor that returns the dtype of each child field of a pandas Series with arrow struct dtype', 'create a struct accessor that extracts a child field of a pandas Series with arrow struct dtype as a Series', 'create an ArrowExtensionArray backed by a PyArrow ChunkedArray from scalar sequences or pyarrow arrays', 'test the ArrowExtensionArray __getitem__ method for integer, slice, and boolean array indexing', 'build an ArrowExtensionArray from a sequence of scalars with a specified pyarrow dtype', 'test the ArrowExtensionArray arithmetic methods for add, sub, mul, truediv, floordiv, and pow operations', 'summarize the ArrowExtensionArray _reduce method for any, all, min, max, sum, mean, median, prod, std, var, sem, kurt, and skew', 'create an ArrowPeriodType pyarrow extension type with a given frequency string', 'create an ArrowIntervalType pyarrow extension type with a subtype and closed boundary', 'test the patch_pyarrow function that blocks unsafe py_extension_type deserialization in older pyarrow versions', 'summarize the ArrowPeriodType class that extends pyarrow.ExtensionType for pandas period data', 'summarize the ArrowIntervalType class that extends pyarrow.ExtensionType for pandas interval data']
```

Usage

```
{'convert_pyarrow_array_to_numpy_and_mask': 'convert a primitive pyarrow.Array to a numpy array and boolean validity mask with specified dtype', 'handle_null_pyarrow_array': 'handle a null-typed pyarrow.Array by returning empty data and all-false mask', 'extract_data_from_arrow_buffer': 'extract data from an arrow buffer using offset and length for numpy frombuffer conversion', 'decode_validity_bitmask': 'decode a pyarrow validity bitmask into a boolean numpy array using BooleanArray.from_buffers', 'convert_pyarrow_array_with_mask': 'convert a pyarrow.Array to numpy data and a boolean mask where False means missing'}
```

## File: pandas-dev_pandas/pandas/core/arrays/arrow/accessors.py

Prompts

```
['convert a primitive pyarrow.Array to a numpy array and boolean validity mask with specified dtype', 'handle a null-typed pyarrow.Array by returning empty data and all-false mask', 'extract data from an arrow buffer using offset and length for numpy frombuffer conversion', 'decode a pyarrow validity bitmask into a boolean numpy array using BooleanArray.from_buffers', 'convert a pyarrow.Array to numpy data and a boolean mask where False means missing', 'create a list accessor that returns the length of each list in a pandas Series with arrow list dtype', 'create a list accessor that indexes or slices lists in a pandas Series by integer or slice', 'create a list accessor that flattens list values in a pandas Series into separate rows', 'create a struct accessor that returns the dtype of each child field of a pandas Series with arrow struct dtype', 'create a struct accessor that extracts a child field of a pandas Series with arrow struct dtype as a Series', 'create an ArrowExtensionArray backed by a PyArrow ChunkedArray from scalar sequences or pyarrow arrays', 'test the ArrowExtensionArray __getitem__ method for integer, slice, and boolean array indexing', 'build an ArrowExtensionArray from a sequence of scalars with a specified pyarrow dtype', 'test the ArrowExtensionArray arithmetic methods for add, sub, mul, truediv, floordiv, and pow operations', 'summarize the ArrowExtensionArray _reduce method for any, all, min, max, sum, mean, median, prod, std, var, sem, kurt, and skew', 'create an ArrowPeriodType pyarrow extension type with a given frequency string', 'create an ArrowIntervalType pyarrow extension type with a subtype and closed boundary', 'test the patch_pyarrow function that blocks unsafe py_extension_type deserialization in older pyarrow versions', 'summarize the ArrowPeriodType class that extends pyarrow.ExtensionType for pandas period data', 'summarize the ArrowIntervalType class that extends pyarrow.ExtensionType for pandas interval data']
```

Usage

```
{'create_list_accessor_len': 'create a list accessor that returns the length of each list in a pandas Series with arrow list dtype', 'create_list_accessor_getitem': 'create a list accessor that indexes or slices lists in a pandas Series by integer or slice', 'create_list_accessor_flatten': 'create a list accessor that flattens list values in a pandas Series into separate rows', 'create_struct_accessor_dtypes': 'create a struct accessor that returns the dtype of each child field of a pandas Series with arrow struct dtype', 'create_struct_accessor_field': 'create a struct accessor that extracts a child field of a pandas Series with arrow struct dtype as a Series'}
```

## File: pandas-dev_pandas/pandas/core/arrays/arrow/array.py

Prompts

```
['convert a primitive pyarrow.Array to a numpy array and boolean validity mask with specified dtype', 'handle a null-typed pyarrow.Array by returning empty data and all-false mask', 'extract data from an arrow buffer using offset and length for numpy frombuffer conversion', 'decode a pyarrow validity bitmask into a boolean numpy array using BooleanArray.from_buffers', 'convert a pyarrow.Array to numpy data and a boolean mask where False means missing', 'create a list accessor that returns the length of each list in a pandas Series with arrow list dtype', 'create a list accessor that indexes or slices lists in a pandas Series by integer or slice', 'create a list accessor that flattens list values in a pandas Series into separate rows', 'create a struct accessor that returns the dtype of each child field of a pandas Series with arrow struct dtype', 'create a struct accessor that extracts a child field of a pandas Series with arrow struct dtype as a Series', 'create an ArrowExtensionArray backed by a PyArrow ChunkedArray from scalar sequences or pyarrow arrays', 'test the ArrowExtensionArray __getitem__ method for integer, slice, and boolean array indexing', 'build an ArrowExtensionArray from a sequence of scalars with a specified pyarrow dtype', 'test the ArrowExtensionArray arithmetic methods for add, sub, mul, truediv, floordiv, and pow operations', 'summarize the ArrowExtensionArray _reduce method for any, all, min, max, sum, mean, median, prod, std, var, sem, kurt, and skew', 'create an ArrowPeriodType pyarrow extension type with a given frequency string', 'create an ArrowIntervalType pyarrow extension type with a subtype and closed boundary', 'test the patch_pyarrow function that blocks unsafe py_extension_type deserialization in older pyarrow versions', 'summarize the ArrowPeriodType class that extends pyarrow.ExtensionType for pandas period data', 'summarize the ArrowIntervalType class that extends pyarrow.ExtensionType for pandas interval data']
```

Usage

```
{'create_ArrowExtensionArray': 'create an ArrowExtensionArray backed by a PyArrow ChunkedArray from scalar sequences or pyarrow arrays', 'test_ArrowExtensionArray_getitem': 'test the ArrowExtensionArray __getitem__ method for integer, slice, and boolean array indexing', 'build_ArrowExtensionArray_from_sequence': 'build an ArrowExtensionArray from a sequence of scalars with a specified pyarrow dtype', 'test_ArrowExtensionArray_arithmetic': 'test the ArrowExtensionArray arithmetic methods for add, sub, mul, truediv, floordiv, and pow operations', 'summarize_ArrowExtensionArray_reduce': 'summarize the ArrowExtensionArray _reduce method for any, all, min, max, sum, mean, median, prod, std, var, sem, kurt, and skew'}
```

## File: pandas-dev_pandas/pandas/core/arrays/arrow/extension_types.py

Prompts

```
['convert a primitive pyarrow.Array to a numpy array and boolean validity mask with specified dtype', 'handle a null-typed pyarrow.Array by returning empty data and all-false mask', 'extract data from an arrow buffer using offset and length for numpy frombuffer conversion', 'decode a pyarrow validity bitmask into a boolean numpy array using BooleanArray.from_buffers', 'convert a pyarrow.Array to numpy data and a boolean mask where False means missing', 'create a list accessor that returns the length of each list in a pandas Series with arrow list dtype', 'create a list accessor that indexes or slices lists in a pandas Series by integer or slice', 'create a list accessor that flattens list values in a pandas Series into separate rows', 'create a struct accessor that returns the dtype of each child field of a pandas Series with arrow struct dtype', 'create a struct accessor that extracts a child field of a pandas Series with arrow struct dtype as a Series', 'create an ArrowExtensionArray backed by a PyArrow ChunkedArray from scalar sequences or pyarrow arrays', 'test the ArrowExtensionArray __getitem__ method for integer, slice, and boolean array indexing', 'build an ArrowExtensionArray from a sequence of scalars with a specified pyarrow dtype', 'test the ArrowExtensionArray arithmetic methods for add, sub, mul, truediv, floordiv, and pow operations', 'summarize the ArrowExtensionArray _reduce method for any, all, min, max, sum, mean, median, prod, std, var, sem, kurt, and skew', 'create an ArrowPeriodType pyarrow extension type with a given frequency string', 'create an ArrowIntervalType pyarrow extension type with a subtype and closed boundary', 'test the patch_pyarrow function that blocks unsafe py_extension_type deserialization in older pyarrow versions', 'summarize the ArrowPeriodType class that extends pyarrow.ExtensionType for pandas period data', 'summarize the ArrowIntervalType class that extends pyarrow.ExtensionType for pandas interval data']
```

Usage

```
{'create_ArrowPeriodType': 'create an ArrowPeriodType pyarrow extension type with a given frequency string', 'create_ArrowIntervalType': 'create an ArrowIntervalType pyarrow extension type with a subtype and closed boundary', 'test_patch_pyarrow': 'test the patch_pyarrow function that blocks unsafe py_extension_type deserialization in older pyarrow versions', 'summarize_ArrowPeriodType': 'summarize the ArrowPeriodType class that extends pyarrow.ExtensionType for pandas period data', 'summarize_ArrowIntervalType': 'summarize the ArrowIntervalType class that extends pyarrow.ExtensionType for pandas interval data'}
```

