# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/abseil-cpp/conanfile.py

Prompts

```
['build the abseil C++ library using the Conan recipe with CMake and disable testing', 'configure the abseil Conan recipe to validate MSVC version is at least 14 on Windows', 'package the abseil library by copying header files, inc files, and compiled static libraries', 'review the AbseilConan class to understand the Conan build lifecycle and dependency settings', 'refactor the package_info method to add or modify linker flags for a different target OS', 'run the script with a YYYYMMDD datestamp to create a new Abseil LTS release', 'replace specific strings in a file using a key-value replacement dictionary', 'strip all content between a begin tag and end tag from a file', 'update the MODULE.bazel version from head to a datestamped LTS version', 'update CMakeLists.txt project version and SOVERSION for the LTS release']
```

Usage

```
{'build_abseil_conan_recipe': 'build the abseil C++ library using the Conan recipe with CMake and disable testing', 'configure_abseil_compiler_check': 'configure the abseil Conan recipe to validate MSVC version is at least 14 on Windows', 'package_abseil_headers_libs': 'package the abseil library by copying header files, inc files, and compiled static libraries', 'review_abseil_conanfile': 'review the AbseilConan class to understand the Conan build lifecycle and dependency settings', 'refactor_abseil_package_info': 'refactor the package_info method to add or modify linker flags for a different target OS'}
```

## File: google-deepmind_actionengine/third_party/abseil-cpp/create_lts.py

Prompts

```
['build the abseil C++ library using the Conan recipe with CMake and disable testing', 'configure the abseil Conan recipe to validate MSVC version is at least 14 on Windows', 'package the abseil library by copying header files, inc files, and compiled static libraries', 'review the AbseilConan class to understand the Conan build lifecycle and dependency settings', 'refactor the package_info method to add or modify linker flags for a different target OS', 'run the script with a YYYYMMDD datestamp to create a new Abseil LTS release', 'replace specific strings in a file using a key-value replacement dictionary', 'strip all content between a begin tag and end tag from a file', 'update the MODULE.bazel version from head to a datestamped LTS version', 'update CMakeLists.txt project version and SOVERSION for the LTS release']
```

Usage

```
{'run_create_lts_release': 'run the script with a YYYYMMDD datestamp to create a new Abseil LTS release', 'replace_strings_in_file': 'replace specific strings in a file using a key-value replacement dictionary', 'strip_content_between_tags': 'strip all content between a begin tag and end tag from a file', 'update_bazel_module_version': 'update the MODULE.bazel version from head to a datestamped LTS version', 'update_cmake_version_and_soversion': 'update CMakeLists.txt project version and SOVERSION for the LTS release'}
```

