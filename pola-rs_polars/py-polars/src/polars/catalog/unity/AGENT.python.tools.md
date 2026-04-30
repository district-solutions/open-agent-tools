# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/catalog/unity/client.py

Prompts

```
['create a Unity catalog client and list available catalogs', 'list namespaces (schemas) under a specified Unity catalog', 'list tables available under a specified Unity catalog namespace', 'scan a Unity catalog table into a Polars LazyFrame with auto credentials', 'write a Polars DataFrame to a Unity catalog table in delta format', 'create a CatalogInfo dataclass instance with catalog name, properties, and optional storage location', 'create a NamespaceInfo dataclass instance with schema name, properties, and optional storage location', 'create a TableInfo dataclass instance with table name, type, columns, and data source format', 'create a ColumnInfo dataclass instance with column name, type_json, and position for a catalog table', 'test the TableInfo.get_polars_schema method that converts catalog columns to a native polars Schema']
```

Usage

```
{'create_catalog_manage_unity': 'create a Unity catalog client and list available catalogs', 'list_namespaces_from_catalog': 'list namespaces (schemas) under a specified Unity catalog', 'list_tables_in_namespace': 'list tables available under a specified Unity catalog namespace', 'scan_table_to_lazyframe': 'scan a Unity catalog table into a Polars LazyFrame with auto credentials', 'write_dataframe_to_catalog': 'write a Polars DataFrame to a Unity catalog table in delta format'}
```

## File: pola-rs_polars/py-polars/src/polars/catalog/unity/models.py

Prompts

```
['create a Unity catalog client and list available catalogs', 'list namespaces (schemas) under a specified Unity catalog', 'list tables available under a specified Unity catalog namespace', 'scan a Unity catalog table into a Polars LazyFrame with auto credentials', 'write a Polars DataFrame to a Unity catalog table in delta format', 'create a CatalogInfo dataclass instance with catalog name, properties, and optional storage location', 'create a NamespaceInfo dataclass instance with schema name, properties, and optional storage location', 'create a TableInfo dataclass instance with table name, type, columns, and data source format', 'create a ColumnInfo dataclass instance with column name, type_json, and position for a catalog table', 'test the TableInfo.get_polars_schema method that converts catalog columns to a native polars Schema']
```

Usage

```
{'create_CatalogInfo': 'create a CatalogInfo dataclass instance with catalog name, properties, and optional storage location', 'create_NamespaceInfo': 'create a NamespaceInfo dataclass instance with schema name, properties, and optional storage location', 'create_TableInfo': 'create a TableInfo dataclass instance with table name, type, columns, and data source format', 'create_ColumnInfo': 'create a ColumnInfo dataclass instance with column name, type_json, and position for a catalog table', 'test_TableInfo_get_polars_schema': 'test the TableInfo.get_polars_schema method that converts catalog columns to a native polars Schema'}
```

