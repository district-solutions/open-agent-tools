# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/benchmark/conanfile.py

Prompts

```
['build the Google Benchmark library using Conan and CMake with configurable LTO and exception options', 'configure CMake definitions for the Google Benchmark library including testing, LTO, and libc++ settings', 'package the built Google Benchmark library and copy the LICENSE file to the licenses directory', 'configure Conan options for Windows builds by removing fPIC and validating Visual Studio version compatibility', 'collect platform-specific linker libraries for Linux pthread, Windows shlwapi, or SunOS kstat', 'download a specific version of MinGW compiler for a given architecture and threading model', 'find the 7zip executable on the system via PATH or Windows registry', 'unpack a MinGW builds archive to a specified location using 7zip', 'download and parse MinGW builds repository files to get available versions and configurations', 'find an executable file in the system PATH and return matching paths']
```

Usage

```
{'build_googlebenchmark': 'build the Google Benchmark library using Conan and CMake with configurable LTO and exception options', 'configure_cmake_benchmark': 'configure CMake definitions for the Google Benchmark library including testing, LTO, and libc++ settings', 'package_googlebenchmark': 'package the built Google Benchmark library and copy the LICENSE file to the licenses directory', 'config_options_windows': 'configure Conan options for Windows builds by removing fPIC and validating Visual Studio version compatibility', 'collect_libs_platform': 'collect platform-specific linker libraries for Linux pthread, Windows shlwapi, or SunOS kstat'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/benchmark/mingw.py

Prompts

```
['build the Google Benchmark library using Conan and CMake with configurable LTO and exception options', 'configure CMake definitions for the Google Benchmark library including testing, LTO, and libc++ settings', 'package the built Google Benchmark library and copy the LICENSE file to the licenses directory', 'configure Conan options for Windows builds by removing fPIC and validating Visual Studio version compatibility', 'collect platform-specific linker libraries for Linux pthread, Windows shlwapi, or SunOS kstat', 'download a specific version of MinGW compiler for a given architecture and threading model', 'find the 7zip executable on the system via PATH or Windows registry', 'unpack a MinGW builds archive to a specified location using 7zip', 'download and parse MinGW builds repository files to get available versions and configurations', 'find an executable file in the system PATH and return matching paths']
```

Usage

```
{'download_mingw': 'download a specific version of MinGW compiler for a given architecture and threading model', 'find_7zip': 'find the 7zip executable on the system via PATH or Windows registry', 'unpack_archive': 'unpack a MinGW builds archive to a specified location using 7zip', 'parse_repository': 'download and parse MinGW builds repository files to get available versions and configurations', 'find_in_path': 'find an executable file in the system PATH and return matching paths'}
```

