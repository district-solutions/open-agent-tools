# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/apps/utils/cached_remote_filesystem.py

Prompts

```
['create a CachedRemoteFileSystem instance wrapping an fsspec filesystem with a remote URI for global caching', 'find all files below a path using cached data from the CachedRemoteFileSystem to avoid redundant API calls', 'list directory contents with cached file stats using the ls method on CachedRemoteFileSystem', 'get file info using cached stats for size and mode via the info method on CachedRemoteFileSystem', 'open a remote file with per-file locking to prevent concurrent download race conditions using CachedRemoteFileSystem', 'create a FallbackFileSystem wrapping an underlying filesystem with a base root directory', 'set a fallback root directory to populate placeholder files and lazy-load stats from backup', 'open a file for reading that triggers lazy loading from the fallback backup location', 'read the contents of a file that auto-loads from fallback if it is a zero-byte placeholder', 'list directory contents and update file stats from the fallback registry for unloaded files', 'get the global RemoteFsCache singleton instance for caching remote filesystem listings and file stats', 'get or create a cache entry for a remote URI by scanning the remote filesystem once', 'get a WholeFileCacheFileSystem wrapper for a remote URI to cache file content locally', 'get cached file stats including size and mode for a relative path in the remote filesystem', 'get statistics about the cache contents including file count and cached stats count per URI']
```

Usage

```
{'create_cached_remote_filesystem': 'create a CachedRemoteFileSystem instance wrapping an fsspec filesystem with a remote URI for global caching', 'find_cached_files': 'find all files below a path using cached data from the CachedRemoteFileSystem to avoid redundant API calls', 'ls_directory_cached': 'list directory contents with cached file stats using the ls method on CachedRemoteFileSystem', 'get_file_info_cached': 'get file info using cached stats for size and mode via the info method on CachedRemoteFileSystem', 'open_file_with_locking': 'open a remote file with per-file locking to prevent concurrent download race conditions using CachedRemoteFileSystem'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/apps/utils/fallback_file_system.py

Prompts

```
['create a CachedRemoteFileSystem instance wrapping an fsspec filesystem with a remote URI for global caching', 'find all files below a path using cached data from the CachedRemoteFileSystem to avoid redundant API calls', 'list directory contents with cached file stats using the ls method on CachedRemoteFileSystem', 'get file info using cached stats for size and mode via the info method on CachedRemoteFileSystem', 'open a remote file with per-file locking to prevent concurrent download race conditions using CachedRemoteFileSystem', 'create a FallbackFileSystem wrapping an underlying filesystem with a base root directory', 'set a fallback root directory to populate placeholder files and lazy-load stats from backup', 'open a file for reading that triggers lazy loading from the fallback backup location', 'read the contents of a file that auto-loads from fallback if it is a zero-byte placeholder', 'list directory contents and update file stats from the fallback registry for unloaded files', 'get the global RemoteFsCache singleton instance for caching remote filesystem listings and file stats', 'get or create a cache entry for a remote URI by scanning the remote filesystem once', 'get a WholeFileCacheFileSystem wrapper for a remote URI to cache file content locally', 'get cached file stats including size and mode for a relative path in the remote filesystem', 'get statistics about the cache contents including file count and cached stats count per URI']
```

Usage

```
{'create_fallback_filesystem': 'create a FallbackFileSystem wrapping an underlying filesystem with a base root directory', 'set_fallback_root': 'set a fallback root directory to populate placeholder files and lazy-load stats from backup', 'open_file_with_fallback': 'open a file for reading that triggers lazy loading from the fallback backup location', 'cat_file_with_fallback': 'read the contents of a file that auto-loads from fallback if it is a zero-byte placeholder', 'ls_with_fallback_stats': 'list directory contents and update file stats from the fallback registry for unloaded files'}
```

## File: facebookresearch_meta-agents-research-environments/are/simulation/apps/utils/remote_fs_cache.py

Prompts

```
['create a CachedRemoteFileSystem instance wrapping an fsspec filesystem with a remote URI for global caching', 'find all files below a path using cached data from the CachedRemoteFileSystem to avoid redundant API calls', 'list directory contents with cached file stats using the ls method on CachedRemoteFileSystem', 'get file info using cached stats for size and mode via the info method on CachedRemoteFileSystem', 'open a remote file with per-file locking to prevent concurrent download race conditions using CachedRemoteFileSystem', 'create a FallbackFileSystem wrapping an underlying filesystem with a base root directory', 'set a fallback root directory to populate placeholder files and lazy-load stats from backup', 'open a file for reading that triggers lazy loading from the fallback backup location', 'read the contents of a file that auto-loads from fallback if it is a zero-byte placeholder', 'list directory contents and update file stats from the fallback registry for unloaded files', 'get the global RemoteFsCache singleton instance for caching remote filesystem listings and file stats', 'get or create a cache entry for a remote URI by scanning the remote filesystem once', 'get a WholeFileCacheFileSystem wrapper for a remote URI to cache file content locally', 'get cached file stats including size and mode for a relative path in the remote filesystem', 'get statistics about the cache contents including file count and cached stats count per URI']
```

Usage

```
{'get_remote_fs_cache': 'get the global RemoteFsCache singleton instance for caching remote filesystem listings and file stats', 'get_or_create_fs_entry': 'get or create a cache entry for a remote URI by scanning the remote filesystem once', 'get_cached_filesystem': 'get a WholeFileCacheFileSystem wrapper for a remote URI to cache file content locally', 'get_file_stats': 'get cached file stats including size and mode for a relative path in the remote filesystem', 'get_cache_stats': 'get statistics about the cache contents including file count and cached stats count per URI'}
```

