# Agent Python Tools

- repo: facebookresearch/ocean
- repo_uri: https://github.com/facebookresearch/ocean

## File: facebookresearch_ocean/build/python/builders/cmake.py

Prompts

```
['configure a CMake project by running cmake with generator, build type, and dependency paths', 'build a CMake project in parallel using cmake --build with configurable job count', 'install built CMake artifacts to a target directory with optional post-install file copying', 'build a CMake configure command list with generator, cross-compilation, and user-specified options', 'run a subprocess command with logging, quiet mode, and configurable output verbosity levels', 'build a header-only library by copying include directory to install location without compilation', 'install header-only library headers by copying source include directory to the install destination', 'configure a HeaderOnlyBuilder instance which requires no setup for header-only libraries', 'review the HeaderOnlyBuilder install method that copies headers and handles missing include directories', 'refactor the HeaderOnlyBuilder to customize the include_subdir build option for non-standard header paths', 'install pre-built shared libraries and headers from a source directory to the install directory', 'configure an ImportedSharedBuilder instance with no-op setup for pre-built shared libraries', 'build an ImportedSharedBuilder instance with no-op logic since libraries are pre-built binaries', 'map an Arch enum value to its corresponding Android ABI string like arm64-v8a or armeabi-v7a', 'copy shared library files using the android_abi placeholder to resolve the correct ABI subdirectory']
```

Usage

```
{'configure_cmake_project': 'configure a CMake project by running cmake with generator, build type, and dependency paths', 'build_cmake_project': 'build a CMake project in parallel using cmake --build with configurable job count', 'install_cmake_artifacts': 'install built CMake artifacts to a target directory with optional post-install file copying', 'build_configure_command': 'build a CMake configure command list with generator, cross-compilation, and user-specified options', 'run_cmake_command': 'run a subprocess command with logging, quiet mode, and configurable output verbosity levels'}
```

## File: facebookresearch_ocean/build/python/builders/header_only.py

Prompts

```
['configure a CMake project by running cmake with generator, build type, and dependency paths', 'build a CMake project in parallel using cmake --build with configurable job count', 'install built CMake artifacts to a target directory with optional post-install file copying', 'build a CMake configure command list with generator, cross-compilation, and user-specified options', 'run a subprocess command with logging, quiet mode, and configurable output verbosity levels', 'build a header-only library by copying include directory to install location without compilation', 'install header-only library headers by copying source include directory to the install destination', 'configure a HeaderOnlyBuilder instance which requires no setup for header-only libraries', 'review the HeaderOnlyBuilder install method that copies headers and handles missing include directories', 'refactor the HeaderOnlyBuilder to customize the include_subdir build option for non-standard header paths', 'install pre-built shared libraries and headers from a source directory to the install directory', 'configure an ImportedSharedBuilder instance with no-op setup for pre-built shared libraries', 'build an ImportedSharedBuilder instance with no-op logic since libraries are pre-built binaries', 'map an Arch enum value to its corresponding Android ABI string like arm64-v8a or armeabi-v7a', 'copy shared library files using the android_abi placeholder to resolve the correct ABI subdirectory']
```

Usage

```
{'build_header_only_library': 'build a header-only library by copying include directory to install location without compilation', 'install_header_only_headers': 'install header-only library headers by copying source include directory to the install destination', 'configure_header_only_builder': 'configure a HeaderOnlyBuilder instance which requires no setup for header-only libraries', 'review_HeaderOnlyBuilder_install': 'review the HeaderOnlyBuilder install method that copies headers and handles missing include directories', 'refactor_HeaderOnlyBuilder_include_subdir': 'refactor the HeaderOnlyBuilder to customize the include_subdir build option for non-standard header paths'}
```

## File: facebookresearch_ocean/build/python/builders/imported_shared.py

Prompts

```
['configure a CMake project by running cmake with generator, build type, and dependency paths', 'build a CMake project in parallel using cmake --build with configurable job count', 'install built CMake artifacts to a target directory with optional post-install file copying', 'build a CMake configure command list with generator, cross-compilation, and user-specified options', 'run a subprocess command with logging, quiet mode, and configurable output verbosity levels', 'build a header-only library by copying include directory to install location without compilation', 'install header-only library headers by copying source include directory to the install destination', 'configure a HeaderOnlyBuilder instance which requires no setup for header-only libraries', 'review the HeaderOnlyBuilder install method that copies headers and handles missing include directories', 'refactor the HeaderOnlyBuilder to customize the include_subdir build option for non-standard header paths', 'install pre-built shared libraries and headers from a source directory to the install directory', 'configure an ImportedSharedBuilder instance with no-op setup for pre-built shared libraries', 'build an ImportedSharedBuilder instance with no-op logic since libraries are pre-built binaries', 'map an Arch enum value to its corresponding Android ABI string like arm64-v8a or armeabi-v7a', 'copy shared library files using the android_abi placeholder to resolve the correct ABI subdirectory']
```

Usage

```
{'install_imported_shared_libraries': 'install pre-built shared libraries and headers from a source directory to the install directory', 'configure_imported_shared_builder': 'configure an ImportedSharedBuilder instance with no-op setup for pre-built shared libraries', 'build_imported_shared_builder': 'build an ImportedSharedBuilder instance with no-op logic since libraries are pre-built binaries', 'map_android_abi': 'map an Arch enum value to its corresponding Android ABI string like arm64-v8a or armeabi-v7a', 'copy_shared_libs_with_abi_placeholder': 'copy shared library files using the android_abi placeholder to resolve the correct ABI subdirectory'}
```

