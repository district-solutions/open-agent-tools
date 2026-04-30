# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/datatype_expr/array.py

Prompts

```
['create a DataTypeExprArrNameSpace instance from a polars DataTypeExpr for array type introspection', 'build the inner DataType of an array using DataTypeExprArrNameSpace.inner_dtype()', 'build the array width as an expression using DataTypeExprArrNameSpace.width()', 'build the array shape as an expression using DataTypeExprArrNameSpace.shape()', 'test the DataTypeExprArrNameSpace class and its methods for array datatype introspection', 'create a lazily instantiated DataType expression for use in Polars expressions and lazy contexts', 'test whether a DataType expression matches a given Polars selector', 'build a formatted string representation of a DataType expression for display', 'summarize a DataType expression by materializing it against a schema or DataFrame context', 'refactor a DataType expression to produce default values for its type', 'get the inner DataType of a list DataTypeExpr using the list namespace accessor', 'test the DataTypeExprStructNameSpace class for struct datatype expression operations', 'create a struct field dtype expression by name from a DataTypeExpr struct accessor', "access a struct field's dtype by integer index using the struct namespace __getitem__", "access a struct field's dtype by string name using the struct namespace __getitem__", 'get the field names in a struct as a list using the struct field_names method']
```

Usage

```
{'create_dtype_expr_arr_namespace': 'create a DataTypeExprArrNameSpace instance from a polars DataTypeExpr for array type introspection', 'build_arr_inner_dtype': 'build the inner DataType of an array using DataTypeExprArrNameSpace.inner_dtype()', 'build_arr_width': 'build the array width as an expression using DataTypeExprArrNameSpace.width()', 'build_arr_shape': 'build the array shape as an expression using DataTypeExprArrNameSpace.shape()', 'test_dtype_expr_arr_namespace': 'test the DataTypeExprArrNameSpace class and its methods for array datatype introspection'}
```

## File: pola-rs_polars/py-polars/src/polars/datatype_expr/datatype_expr.py

Prompts

```
['create a DataTypeExprArrNameSpace instance from a polars DataTypeExpr for array type introspection', 'build the inner DataType of an array using DataTypeExprArrNameSpace.inner_dtype()', 'build the array width as an expression using DataTypeExprArrNameSpace.width()', 'build the array shape as an expression using DataTypeExprArrNameSpace.shape()', 'test the DataTypeExprArrNameSpace class and its methods for array datatype introspection', 'create a lazily instantiated DataType expression for use in Polars expressions and lazy contexts', 'test whether a DataType expression matches a given Polars selector', 'build a formatted string representation of a DataType expression for display', 'summarize a DataType expression by materializing it against a schema or DataFrame context', 'refactor a DataType expression to produce default values for its type', 'get the inner DataType of a list DataTypeExpr using the list namespace accessor', 'test the DataTypeExprStructNameSpace class for struct datatype expression operations', 'create a struct field dtype expression by name from a DataTypeExpr struct accessor', "access a struct field's dtype by integer index using the struct namespace __getitem__", "access a struct field's dtype by string name using the struct namespace __getitem__", 'get the field names in a struct as a list using the struct field_names method']
```

Usage

```
{'create_datatype_expr': 'create a lazily instantiated DataType expression for use in Polars expressions and lazy contexts', 'test_datatype_matches': 'test whether a DataType expression matches a given Polars selector', 'build_datatype_display': 'build a formatted string representation of a DataType expression for display', 'summarize_datatype_collect': 'summarize a DataType expression by materializing it against a schema or DataFrame context', 'refactor_datatype_default': 'refactor a DataType expression to produce default values for its type'}
```

## File: pola-rs_polars/py-polars/src/polars/datatype_expr/list.py

Prompts

```
['create a DataTypeExprArrNameSpace instance from a polars DataTypeExpr for array type introspection', 'build the inner DataType of an array using DataTypeExprArrNameSpace.inner_dtype()', 'build the array width as an expression using DataTypeExprArrNameSpace.width()', 'build the array shape as an expression using DataTypeExprArrNameSpace.shape()', 'test the DataTypeExprArrNameSpace class and its methods for array datatype introspection', 'create a lazily instantiated DataType expression for use in Polars expressions and lazy contexts', 'test whether a DataType expression matches a given Polars selector', 'build a formatted string representation of a DataType expression for display', 'summarize a DataType expression by materializing it against a schema or DataFrame context', 'refactor a DataType expression to produce default values for its type', 'get the inner DataType of a list DataTypeExpr using the list namespace accessor', 'test the DataTypeExprStructNameSpace class for struct datatype expression operations', 'create a struct field dtype expression by name from a DataTypeExpr struct accessor', "access a struct field's dtype by integer index using the struct namespace __getitem__", "access a struct field's dtype by string name using the struct namespace __getitem__", 'get the field names in a struct as a list using the struct field_names method']
```

Usage

```
{'get_list_inner_dtype': 'get the inner DataType of a list DataTypeExpr using the list namespace accessor'}
```

## File: pola-rs_polars/py-polars/src/polars/datatype_expr/struct.py

Prompts

```
['create a DataTypeExprArrNameSpace instance from a polars DataTypeExpr for array type introspection', 'build the inner DataType of an array using DataTypeExprArrNameSpace.inner_dtype()', 'build the array width as an expression using DataTypeExprArrNameSpace.width()', 'build the array shape as an expression using DataTypeExprArrNameSpace.shape()', 'test the DataTypeExprArrNameSpace class and its methods for array datatype introspection', 'create a lazily instantiated DataType expression for use in Polars expressions and lazy contexts', 'test whether a DataType expression matches a given Polars selector', 'build a formatted string representation of a DataType expression for display', 'summarize a DataType expression by materializing it against a schema or DataFrame context', 'refactor a DataType expression to produce default values for its type', 'get the inner DataType of a list DataTypeExpr using the list namespace accessor', 'test the DataTypeExprStructNameSpace class for struct datatype expression operations', 'create a struct field dtype expression by name from a DataTypeExpr struct accessor', "access a struct field's dtype by integer index using the struct namespace __getitem__", "access a struct field's dtype by string name using the struct namespace __getitem__", 'get the field names in a struct as a list using the struct field_names method']
```

Usage

```
{'test_struct_namespace': 'test the DataTypeExprStructNameSpace class for struct datatype expression operations', 'create_struct_field_dtype': 'create a struct field dtype expression by name from a DataTypeExpr struct accessor', 'access_struct_field_by_index': "access a struct field's dtype by integer index using the struct namespace __getitem__", 'access_struct_field_by_name': "access a struct field's dtype by string name using the struct namespace __getitem__", 'get_struct_field_names': 'get the field names in a struct as a list using the struct field_names method'}
```

