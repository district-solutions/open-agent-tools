# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/io/xml/test_to_xml.py

Prompts

```
['test the DataFrame.to_xml method to write XML output to a file path', 'test the DataFrame.to_xml method with index=False to exclude index from XML output', 'test the DataFrame.to_xml method with attr_cols to place columns as XML attributes', 'test the DataFrame.to_xml method with namespaces and prefix for namespaced XML output', 'test the DataFrame.to_xml method with a stylesheet parameter to apply XSLT transformation', 'test reading XML data from a file path into a pandas DataFrame', 'test parsing XML with an XPath expression to select specific nodes', 'test reading namespaced XML using a namespaces dictionary with XPath', 'test streaming large XML files using iterparse for memory-efficient parsing', 'test applying an XSLT stylesheet to transform XML before parsing into a DataFrame', 'test read_xml with dtype parameter to keep a column as string type', 'test read_xml with dtype set to string for all columns', 'test read_xml with names and dtype mapping for custom column types', 'test read_xml with dtype Int64 to preserve NA values for missing numeric data', 'test read_xml with dtype float for numeric column conversion']
```

Usage

```
{'test_to_xml_file_output': 'test the DataFrame.to_xml method to write XML output to a file path', 'test_to_xml_index_false': 'test the DataFrame.to_xml method with index=False to exclude index from XML output', 'test_to_xml_attr_cols': 'test the DataFrame.to_xml method with attr_cols to place columns as XML attributes', 'test_to_xml_namespaces_prefix': 'test the DataFrame.to_xml method with namespaces and prefix for namespaced XML output', 'test_to_xml_stylesheet': 'test the DataFrame.to_xml method with a stylesheet parameter to apply XSLT transformation'}
```

## File: pandas-dev_pandas/pandas/tests/io/xml/test_xml.py

Prompts

```
['test the DataFrame.to_xml method to write XML output to a file path', 'test the DataFrame.to_xml method with index=False to exclude index from XML output', 'test the DataFrame.to_xml method with attr_cols to place columns as XML attributes', 'test the DataFrame.to_xml method with namespaces and prefix for namespaced XML output', 'test the DataFrame.to_xml method with a stylesheet parameter to apply XSLT transformation', 'test reading XML data from a file path into a pandas DataFrame', 'test parsing XML with an XPath expression to select specific nodes', 'test reading namespaced XML using a namespaces dictionary with XPath', 'test streaming large XML files using iterparse for memory-efficient parsing', 'test applying an XSLT stylesheet to transform XML before parsing into a DataFrame', 'test read_xml with dtype parameter to keep a column as string type', 'test read_xml with dtype set to string for all columns', 'test read_xml with names and dtype mapping for custom column types', 'test read_xml with dtype Int64 to preserve NA values for missing numeric data', 'test read_xml with dtype float for numeric column conversion']
```

Usage

```
{'test_read_xml_basic': 'test reading XML data from a file path into a pandas DataFrame', 'test_read_xml_xpath': 'test parsing XML with an XPath expression to select specific nodes', 'test_read_xml_namespaces': 'test reading namespaced XML using a namespaces dictionary with XPath', 'test_read_xml_iterparse': 'test streaming large XML files using iterparse for memory-efficient parsing', 'test_read_xml_stylesheet': 'test applying an XSLT stylesheet to transform XML before parsing into a DataFrame'}
```

## File: pandas-dev_pandas/pandas/tests/io/xml/test_xml_dtypes.py

Prompts

```
['test the DataFrame.to_xml method to write XML output to a file path', 'test the DataFrame.to_xml method with index=False to exclude index from XML output', 'test the DataFrame.to_xml method with attr_cols to place columns as XML attributes', 'test the DataFrame.to_xml method with namespaces and prefix for namespaced XML output', 'test the DataFrame.to_xml method with a stylesheet parameter to apply XSLT transformation', 'test reading XML data from a file path into a pandas DataFrame', 'test parsing XML with an XPath expression to select specific nodes', 'test reading namespaced XML using a namespaces dictionary with XPath', 'test streaming large XML files using iterparse for memory-efficient parsing', 'test applying an XSLT stylesheet to transform XML before parsing into a DataFrame', 'test read_xml with dtype parameter to keep a column as string type', 'test read_xml with dtype set to string for all columns', 'test read_xml with names and dtype mapping for custom column types', 'test read_xml with dtype Int64 to preserve NA values for missing numeric data', 'test read_xml with dtype float for numeric column conversion']
```

Usage

```
{'test_dtype_single_str': 'test read_xml with dtype parameter to keep a column as string type', 'test_dtypes_all_str': 'test read_xml with dtype set to string for all columns', 'test_dtypes_with_names': 'test read_xml with names and dtype mapping for custom column types', 'test_dtype_nullable_int': 'test read_xml with dtype Int64 to preserve NA values for missing numeric data', 'test_dtype_float': 'test read_xml with dtype float for numeric column conversion'}
```

