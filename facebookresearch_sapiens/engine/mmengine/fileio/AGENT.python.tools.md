# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/fileio/file_client.py

Prompts

```
['create a FileClient instance with a specified backend like disk, memcached, lmdb, petrel, or http', 'read binary data from a file path using FileClient get method and return bytes or memoryview', 'read text data from a file path using FileClient get_text method with utf-8 encoding', 'write binary data to a file path using FileClient put method in write binary mode', 'scan a directory and list files or subdirectories using FileClient list_dir_or_file with optional suffix filter', 'get a file backend instance for local, s3, or petrel storage based on uri prefix', 'read bytes from a file path using the appropriate storage backend automatically', 'read text content from a file path with configurable encoding via unified I/O', 'write bytes to a file path on local disk or remote storage backend', 'load or dump json, yaml, or pickle data from files across multiple storage backends', 'parse a text file into a list of strings using list_from_file with optional prefix and offset', 'parse a text file from S3 or disk into a list using list_from_file with backend_args', 'parse a whitespace-delimited text file into a dictionary using dict_from_file with key_type conversion', 'parse a text file from S3 into a dictionary using dict_from_file with backend_args', 'review the list_from_file function for offset, max_num, and prefix parameter handling']
```

Usage

```
{'create_file_client_backend': 'create a FileClient instance with a specified backend like disk, memcached, lmdb, petrel, or http', 'read_binary_file': 'read binary data from a file path using FileClient get method and return bytes or memoryview', 'read_text_file': 'read text data from a file path using FileClient get_text method with utf-8 encoding', 'write_binary_file': 'write binary data to a file path using FileClient put method in write binary mode', 'list_directory': 'scan a directory and list files or subdirectories using FileClient list_dir_or_file with optional suffix filter'}
```

## File: facebookresearch_sapiens/engine/mmengine/fileio/io.py

Prompts

```
['create a FileClient instance with a specified backend like disk, memcached, lmdb, petrel, or http', 'read binary data from a file path using FileClient get method and return bytes or memoryview', 'read text data from a file path using FileClient get_text method with utf-8 encoding', 'write binary data to a file path using FileClient put method in write binary mode', 'scan a directory and list files or subdirectories using FileClient list_dir_or_file with optional suffix filter', 'get a file backend instance for local, s3, or petrel storage based on uri prefix', 'read bytes from a file path using the appropriate storage backend automatically', 'read text content from a file path with configurable encoding via unified I/O', 'write bytes to a file path on local disk or remote storage backend', 'load or dump json, yaml, or pickle data from files across multiple storage backends', 'parse a text file into a list of strings using list_from_file with optional prefix and offset', 'parse a text file from S3 or disk into a list using list_from_file with backend_args', 'parse a whitespace-delimited text file into a dictionary using dict_from_file with key_type conversion', 'parse a text file from S3 into a dictionary using dict_from_file with backend_args', 'review the list_from_file function for offset, max_num, and prefix parameter handling']
```

Usage

```
{'get_file_backend': 'get a file backend instance for local, s3, or petrel storage based on uri prefix', 'get_bytes': 'read bytes from a file path using the appropriate storage backend automatically', 'get_text': 'read text content from a file path with configurable encoding via unified I/O', 'put_bytes': 'write bytes to a file path on local disk or remote storage backend', 'load_dump': 'load or dump json, yaml, or pickle data from files across multiple storage backends'}
```

## File: facebookresearch_sapiens/engine/mmengine/fileio/parse.py

Prompts

```
['create a FileClient instance with a specified backend like disk, memcached, lmdb, petrel, or http', 'read binary data from a file path using FileClient get method and return bytes or memoryview', 'read text data from a file path using FileClient get_text method with utf-8 encoding', 'write binary data to a file path using FileClient put method in write binary mode', 'scan a directory and list files or subdirectories using FileClient list_dir_or_file with optional suffix filter', 'get a file backend instance for local, s3, or petrel storage based on uri prefix', 'read bytes from a file path using the appropriate storage backend automatically', 'read text content from a file path with configurable encoding via unified I/O', 'write bytes to a file path on local disk or remote storage backend', 'load or dump json, yaml, or pickle data from files across multiple storage backends', 'parse a text file into a list of strings using list_from_file with optional prefix and offset', 'parse a text file from S3 or disk into a list using list_from_file with backend_args', 'parse a whitespace-delimited text file into a dictionary using dict_from_file with key_type conversion', 'parse a text file from S3 into a dictionary using dict_from_file with backend_args', 'review the list_from_file function for offset, max_num, and prefix parameter handling']
```

Usage

```
{'parse_list_from_file': 'parse a text file into a list of strings using list_from_file with optional prefix and offset', 'parse_list_with_backend': 'parse a text file from S3 or disk into a list using list_from_file with backend_args', 'parse_dict_from_file': 'parse a whitespace-delimited text file into a dictionary using dict_from_file with key_type conversion', 'parse_dict_from_s3': 'parse a text file from S3 into a dictionary using dict_from_file with backend_args', 'review_list_from_file': 'review the list_from_file function for offset, max_num, and prefix parameter handling'}
```

