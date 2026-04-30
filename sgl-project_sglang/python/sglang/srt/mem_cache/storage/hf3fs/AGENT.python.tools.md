# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/hf3fs/hf3fs_client.py

Prompts

```
['create a mock HF3FS client for CI testing with a storage file, size, bytes per page, and entry count', 'test batch reading torch tensors from offsets into a mock HF3FS storage file', 'test batch writing torch tensors from offsets into a mock HF3FS storage file', 'test closing the mock HF3FS client and cleaning up its file descriptor', 'test flushing data from the mock HF3FS client to disk via os.fsync', 'create an Hf3fsUsrBioClient instance with path, size, bytes_per_page, entries, and client_timeout parameters', 'test the Hf3fsUsrBioClient close method to deregister the file descriptor and release shared memory', 'test the Hf3fsUsrBioClient flush method to fsync the underlying file', 'run the HF3FS metadata server on a specified host and port with optional persistence', 'build a FastAPI server that manages page allocation and key metadata for multiple ranks', 'test the HTTP client that performs remote rank metadata operations against the server', 'create an in-memory local metadata client for single-rank page allocation without a server', 'review the RankMetadata class that manages page indices, key lookups, and eviction per rank', 'create an HF3FS storage client using the factory function with configurable path, size, and timeout parameters', 'build a HiCacheHF3FS backend instance for storing KV cache pages in HF3FS files with metadata support', 'create a HiCacheHF3FS instance from environment configuration JSON with optional MLA model support', 'test the batch_get_v1 method to read multiple KV cache pages from HF3FS storage by keys', 'refactor the batch_set_v1 method to write multiple KV cache pages to HF3FS storage with page allocation', 'test the test_rw_shm function that writes and reads tensors from shared memory', 'run hf3fs_utils.write_shm to write a list of torch tensors into a shared memory buffer', 'run hf3fs_utils.read_shm to read tensors from a shared memory buffer into a list of torch tensors', 'review the test_rw_shm function that validates roundtrip write and read of bfloat16 tensors via shared memory', 'summarize the hf3fs_utils cpp extension module providing write_shm and read_shm for tensor shared memory I/O']
```

Usage

```
{'create_Hf3fsMockClient': 'create a mock HF3FS client for CI testing with a storage file, size, bytes per page, and entry count', 'test_batch_read': 'test batch reading torch tensors from offsets into a mock HF3FS storage file', 'test_batch_write': 'test batch writing torch tensors from offsets into a mock HF3FS storage file', 'test_Hf3fsMockClient_close': 'test closing the mock HF3FS client and cleaning up its file descriptor', 'test_Hf3fsMockClient_flush': 'test flushing data from the mock HF3FS client to disk via os.fsync'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/hf3fs/hf3fs_usrbio_client.py

Prompts

```
['create a mock HF3FS client for CI testing with a storage file, size, bytes per page, and entry count', 'test batch reading torch tensors from offsets into a mock HF3FS storage file', 'test batch writing torch tensors from offsets into a mock HF3FS storage file', 'test closing the mock HF3FS client and cleaning up its file descriptor', 'test flushing data from the mock HF3FS client to disk via os.fsync', 'create an Hf3fsUsrBioClient instance with path, size, bytes_per_page, entries, and client_timeout parameters', 'test the Hf3fsUsrBioClient close method to deregister the file descriptor and release shared memory', 'test the Hf3fsUsrBioClient flush method to fsync the underlying file', 'run the HF3FS metadata server on a specified host and port with optional persistence', 'build a FastAPI server that manages page allocation and key metadata for multiple ranks', 'test the HTTP client that performs remote rank metadata operations against the server', 'create an in-memory local metadata client for single-rank page allocation without a server', 'review the RankMetadata class that manages page indices, key lookups, and eviction per rank', 'create an HF3FS storage client using the factory function with configurable path, size, and timeout parameters', 'build a HiCacheHF3FS backend instance for storing KV cache pages in HF3FS files with metadata support', 'create a HiCacheHF3FS instance from environment configuration JSON with optional MLA model support', 'test the batch_get_v1 method to read multiple KV cache pages from HF3FS storage by keys', 'refactor the batch_set_v1 method to write multiple KV cache pages to HF3FS storage with page allocation', 'test the test_rw_shm function that writes and reads tensors from shared memory', 'run hf3fs_utils.write_shm to write a list of torch tensors into a shared memory buffer', 'run hf3fs_utils.read_shm to read tensors from a shared memory buffer into a list of torch tensors', 'review the test_rw_shm function that validates roundtrip write and read of bfloat16 tensors via shared memory', 'summarize the hf3fs_utils cpp extension module providing write_shm and read_shm for tensor shared memory I/O']
```

Usage

```
{'create_Hf3fsUsrBioClient': 'create an Hf3fsUsrBioClient instance with path, size, bytes_per_page, entries, and client_timeout parameters', 'test_batch_read': 'test batch_read with a list of offsets and torch tensors to read data via iouring', 'test_batch_write': 'test batch_write with a list of offsets and torch tensors to write data via iouring', 'test_Hf3fsUsrBioClient_close': 'test the Hf3fsUsrBioClient close method to deregister the file descriptor and release shared memory', 'test_Hf3fsUsrBioClient_flush': 'test the Hf3fsUsrBioClient flush method to fsync the underlying file'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/hf3fs/mini_3fs_metadata_server.py

Prompts

```
['create a mock HF3FS client for CI testing with a storage file, size, bytes per page, and entry count', 'test batch reading torch tensors from offsets into a mock HF3FS storage file', 'test batch writing torch tensors from offsets into a mock HF3FS storage file', 'test closing the mock HF3FS client and cleaning up its file descriptor', 'test flushing data from the mock HF3FS client to disk via os.fsync', 'create an Hf3fsUsrBioClient instance with path, size, bytes_per_page, entries, and client_timeout parameters', 'test the Hf3fsUsrBioClient close method to deregister the file descriptor and release shared memory', 'test the Hf3fsUsrBioClient flush method to fsync the underlying file', 'run the HF3FS metadata server on a specified host and port with optional persistence', 'build a FastAPI server that manages page allocation and key metadata for multiple ranks', 'test the HTTP client that performs remote rank metadata operations against the server', 'create an in-memory local metadata client for single-rank page allocation without a server', 'review the RankMetadata class that manages page indices, key lookups, and eviction per rank', 'create an HF3FS storage client using the factory function with configurable path, size, and timeout parameters', 'build a HiCacheHF3FS backend instance for storing KV cache pages in HF3FS files with metadata support', 'create a HiCacheHF3FS instance from environment configuration JSON with optional MLA model support', 'test the batch_get_v1 method to read multiple KV cache pages from HF3FS storage by keys', 'refactor the batch_set_v1 method to write multiple KV cache pages to HF3FS storage with page allocation', 'test the test_rw_shm function that writes and reads tensors from shared memory', 'run hf3fs_utils.write_shm to write a list of torch tensors into a shared memory buffer', 'run hf3fs_utils.read_shm to read tensors from a shared memory buffer into a list of torch tensors', 'review the test_rw_shm function that validates roundtrip write and read of bfloat16 tensors via shared memory', 'summarize the hf3fs_utils cpp extension module providing write_shm and read_shm for tensor shared memory I/O']
```

Usage

```
{'run_metadata_server': 'run the HF3FS metadata server on a specified host and port with optional persistence', 'build_Hf3fsMetadataServer': 'build a FastAPI server that manages page allocation and key metadata for multiple ranks', 'test_Hf3fsGlobalMetadataClient': 'test the HTTP client that performs remote rank metadata operations against the server', 'create_Hf3fsLocalMetadataClient': 'create an in-memory local metadata client for single-rank page allocation without a server', 'review_RankMetadata': 'review the RankMetadata class that manages page indices, key lookups, and eviction per rank'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/hf3fs/storage_hf3fs.py

Prompts

```
['create a mock HF3FS client for CI testing with a storage file, size, bytes per page, and entry count', 'test batch reading torch tensors from offsets into a mock HF3FS storage file', 'test batch writing torch tensors from offsets into a mock HF3FS storage file', 'test closing the mock HF3FS client and cleaning up its file descriptor', 'test flushing data from the mock HF3FS client to disk via os.fsync', 'create an Hf3fsUsrBioClient instance with path, size, bytes_per_page, entries, and client_timeout parameters', 'test the Hf3fsUsrBioClient close method to deregister the file descriptor and release shared memory', 'test the Hf3fsUsrBioClient flush method to fsync the underlying file', 'run the HF3FS metadata server on a specified host and port with optional persistence', 'build a FastAPI server that manages page allocation and key metadata for multiple ranks', 'test the HTTP client that performs remote rank metadata operations against the server', 'create an in-memory local metadata client for single-rank page allocation without a server', 'review the RankMetadata class that manages page indices, key lookups, and eviction per rank', 'create an HF3FS storage client using the factory function with configurable path, size, and timeout parameters', 'build a HiCacheHF3FS backend instance for storing KV cache pages in HF3FS files with metadata support', 'create a HiCacheHF3FS instance from environment configuration JSON with optional MLA model support', 'test the batch_get_v1 method to read multiple KV cache pages from HF3FS storage by keys', 'refactor the batch_set_v1 method to write multiple KV cache pages to HF3FS storage with page allocation', 'test the test_rw_shm function that writes and reads tensors from shared memory', 'run hf3fs_utils.write_shm to write a list of torch tensors into a shared memory buffer', 'run hf3fs_utils.read_shm to read tensors from a shared memory buffer into a list of torch tensors', 'review the test_rw_shm function that validates roundtrip write and read of bfloat16 tensors via shared memory', 'summarize the hf3fs_utils cpp extension module providing write_shm and read_shm for tensor shared memory I/O']
```

Usage

```
{'create_hf3fs_client': 'create an HF3FS storage client using the factory function with configurable path, size, and timeout parameters', 'build_HiCacheHF3FS': 'build a HiCacheHF3FS backend instance for storing KV cache pages in HF3FS files with metadata support', 'create_HiCacheHF3FS_from_config': 'create a HiCacheHF3FS instance from environment configuration JSON with optional MLA model support', 'test_batch_get_v1': 'test the batch_get_v1 method to read multiple KV cache pages from HF3FS storage by keys', 'refactor_batch_set_v1': 'refactor the batch_set_v1 method to write multiple KV cache pages to HF3FS storage with page allocation'}
```

## File: sgl-project_sglang/python/sglang/srt/mem_cache/storage/hf3fs/test_hf3fs_utils.py

Prompts

```
['create a mock HF3FS client for CI testing with a storage file, size, bytes per page, and entry count', 'test batch reading torch tensors from offsets into a mock HF3FS storage file', 'test batch writing torch tensors from offsets into a mock HF3FS storage file', 'test closing the mock HF3FS client and cleaning up its file descriptor', 'test flushing data from the mock HF3FS client to disk via os.fsync', 'create an Hf3fsUsrBioClient instance with path, size, bytes_per_page, entries, and client_timeout parameters', 'test the Hf3fsUsrBioClient close method to deregister the file descriptor and release shared memory', 'test the Hf3fsUsrBioClient flush method to fsync the underlying file', 'run the HF3FS metadata server on a specified host and port with optional persistence', 'build a FastAPI server that manages page allocation and key metadata for multiple ranks', 'test the HTTP client that performs remote rank metadata operations against the server', 'create an in-memory local metadata client for single-rank page allocation without a server', 'review the RankMetadata class that manages page indices, key lookups, and eviction per rank', 'create an HF3FS storage client using the factory function with configurable path, size, and timeout parameters', 'build a HiCacheHF3FS backend instance for storing KV cache pages in HF3FS files with metadata support', 'create a HiCacheHF3FS instance from environment configuration JSON with optional MLA model support', 'test the batch_get_v1 method to read multiple KV cache pages from HF3FS storage by keys', 'refactor the batch_set_v1 method to write multiple KV cache pages to HF3FS storage with page allocation', 'test the test_rw_shm function that writes and reads tensors from shared memory', 'run hf3fs_utils.write_shm to write a list of torch tensors into a shared memory buffer', 'run hf3fs_utils.read_shm to read tensors from a shared memory buffer into a list of torch tensors', 'review the test_rw_shm function that validates roundtrip write and read of bfloat16 tensors via shared memory', 'summarize the hf3fs_utils cpp extension module providing write_shm and read_shm for tensor shared memory I/O']
```

Usage

```
{'test_rw_shm': 'test the test_rw_shm function that writes and reads tensors from shared memory', 'run_write_shm': 'run hf3fs_utils.write_shm to write a list of torch tensors into a shared memory buffer', 'run_read_shm': 'run hf3fs_utils.read_shm to read tensors from a shared memory buffer into a list of torch tensors', 'review_test_rw_shm': 'review the test_rw_shm function that validates roundtrip write and read of bfloat16 tensors via shared memory', 'summarize_hf3fs_utils': 'summarize the hf3fs_utils cpp extension module providing write_shm and read_shm for tensor shared memory I/O'}
```

