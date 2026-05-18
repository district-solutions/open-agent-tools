# Agent Python Tools

- repo: facebookresearch/ocean
- repo_uri: https://github.com/facebookresearch/ocean

## File: facebookresearch_ocean/build/python/build_ocean.py

Prompts

```
['build the Ocean library for the host platform using CMake with default debug and release static configs', 'build the Ocean library for a specific target platform like ios_arm64 or macos_arm64 using the CLI', 'build the Ocean library for Meta Quest using Android ARM64 with Quest extensions enabled', 'build the Ocean library in minimal mode with only base, cv, and math modules compiled', 'show the Ocean build plan and target list without actually running any CMake configure or build steps', 'build all third-party libraries for Ocean across macOS, iOS, Linux, Android, and Windows targets', 'build a specific library like libpng and its transitive dependencies for a given target platform', 'build libraries for multiple platforms at once using OS group names like android or ios', 'show the DAG-based build plan with parallelism info without actually building anything using dry-run', 'list all available optional libraries and their optional groups from the dependencies manifest', 'run the validate_manifest.py script to check dependencies.yaml against the JSON schema', 'run validate_manifest.py to verify all library dependencies reference existing libraries in the manifest', 'run validate_manifest.py to detect circular dependencies between libraries in the manifest', 'run validate_manifest.py to check that git source URLs are properly formatted and have refs', 'run validate_manifest.py with the --verbose flag to show detailed validation output', 'render a dependency graph from dependencies.yaml as a PNG image using graphviz', 'print an ASCII tree visualization of the dependency graph with build levels', 'compute build levels using topological sort to find parallel build order', 'generate a Mermaid diagram format output of the dependency graph', 'output the dependency graph in GraphViz DOT source format']
```

Usage

```
{'build_ocean_for_host': 'build the Ocean library for the host platform using CMake with default debug and release static configs', 'build_ocean_for_target': 'build the Ocean library for a specific target platform like ios_arm64 or macos_arm64 using the CLI', 'build_ocean_quest': 'build the Ocean library for Meta Quest using Android ARM64 with Quest extensions enabled', 'build_ocean_minimal': 'build the Ocean library in minimal mode with only base, cv, and math modules compiled', 'build_ocean_dry_run': 'show the Ocean build plan and target list without actually running any CMake configure or build steps'}
```

## File: facebookresearch_ocean/build/python/build_ocean_3rdparty.py

Prompts

```
['build the Ocean library for the host platform using CMake with default debug and release static configs', 'build the Ocean library for a specific target platform like ios_arm64 or macos_arm64 using the CLI', 'build the Ocean library for Meta Quest using Android ARM64 with Quest extensions enabled', 'build the Ocean library in minimal mode with only base, cv, and math modules compiled', 'show the Ocean build plan and target list without actually running any CMake configure or build steps', 'build all third-party libraries for Ocean across macOS, iOS, Linux, Android, and Windows targets', 'build a specific library like libpng and its transitive dependencies for a given target platform', 'build libraries for multiple platforms at once using OS group names like android or ios', 'show the DAG-based build plan with parallelism info without actually building anything using dry-run', 'list all available optional libraries and their optional groups from the dependencies manifest', 'run the validate_manifest.py script to check dependencies.yaml against the JSON schema', 'run validate_manifest.py to verify all library dependencies reference existing libraries in the manifest', 'run validate_manifest.py to detect circular dependencies between libraries in the manifest', 'run validate_manifest.py to check that git source URLs are properly formatted and have refs', 'run validate_manifest.py with the --verbose flag to show detailed validation output', 'render a dependency graph from dependencies.yaml as a PNG image using graphviz', 'print an ASCII tree visualization of the dependency graph with build levels', 'compute build levels using topological sort to find parallel build order', 'generate a Mermaid diagram format output of the dependency graph', 'output the dependency graph in GraphViz DOT source format']
```

Usage

```
{'build_third_party_libraries': 'build all third-party libraries for Ocean across macOS, iOS, Linux, Android, and Windows targets', 'build_specific_library': 'build a specific library like libpng and its transitive dependencies for a given target platform', 'build_cross_platform_targets': 'build libraries for multiple platforms at once using OS group names like android or ios', 'show_build_plan': 'show the DAG-based build plan with parallelism info without actually building anything using dry-run', 'list_optional_libraries': 'list all available optional libraries and their optional groups from the dependencies manifest'}
```

## File: facebookresearch_ocean/build/python/validate_manifest.py

Prompts

```
['build the Ocean library for the host platform using CMake with default debug and release static configs', 'build the Ocean library for a specific target platform like ios_arm64 or macos_arm64 using the CLI', 'build the Ocean library for Meta Quest using Android ARM64 with Quest extensions enabled', 'build the Ocean library in minimal mode with only base, cv, and math modules compiled', 'show the Ocean build plan and target list without actually running any CMake configure or build steps', 'build all third-party libraries for Ocean across macOS, iOS, Linux, Android, and Windows targets', 'build a specific library like libpng and its transitive dependencies for a given target platform', 'build libraries for multiple platforms at once using OS group names like android or ios', 'show the DAG-based build plan with parallelism info without actually building anything using dry-run', 'list all available optional libraries and their optional groups from the dependencies manifest', 'run the validate_manifest.py script to check dependencies.yaml against the JSON schema', 'run validate_manifest.py to verify all library dependencies reference existing libraries in the manifest', 'run validate_manifest.py to detect circular dependencies between libraries in the manifest', 'run validate_manifest.py to check that git source URLs are properly formatted and have refs', 'run validate_manifest.py with the --verbose flag to show detailed validation output', 'render a dependency graph from dependencies.yaml as a PNG image using graphviz', 'print an ASCII tree visualization of the dependency graph with build levels', 'compute build levels using topological sort to find parallel build order', 'generate a Mermaid diagram format output of the dependency graph', 'output the dependency graph in GraphViz DOT source format']
```

Usage

```
{'validate_dependencies_yaml_against_schema': 'run the validate_manifest.py script to check dependencies.yaml against the JSON schema', 'validate_dependency_references': 'run validate_manifest.py to verify all library dependencies reference existing libraries in the manifest', 'detect_circular_dependencies': 'run validate_manifest.py to detect circular dependencies between libraries in the manifest', 'validate_git_source_urls': 'run validate_manifest.py to check that git source URLs are properly formatted and have refs', 'validate_manifest_verbose': 'run validate_manifest.py with the --verbose flag to show detailed validation output'}
```

## File: facebookresearch_ocean/build/python/visualize_deps.py

Prompts

```
['build the Ocean library for the host platform using CMake with default debug and release static configs', 'build the Ocean library for a specific target platform like ios_arm64 or macos_arm64 using the CLI', 'build the Ocean library for Meta Quest using Android ARM64 with Quest extensions enabled', 'build the Ocean library in minimal mode with only base, cv, and math modules compiled', 'show the Ocean build plan and target list without actually running any CMake configure or build steps', 'build all third-party libraries for Ocean across macOS, iOS, Linux, Android, and Windows targets', 'build a specific library like libpng and its transitive dependencies for a given target platform', 'build libraries for multiple platforms at once using OS group names like android or ios', 'show the DAG-based build plan with parallelism info without actually building anything using dry-run', 'list all available optional libraries and their optional groups from the dependencies manifest', 'run the validate_manifest.py script to check dependencies.yaml against the JSON schema', 'run validate_manifest.py to verify all library dependencies reference existing libraries in the manifest', 'run validate_manifest.py to detect circular dependencies between libraries in the manifest', 'run validate_manifest.py to check that git source URLs are properly formatted and have refs', 'run validate_manifest.py with the --verbose flag to show detailed validation output', 'render a dependency graph from dependencies.yaml as a PNG image using graphviz', 'print an ASCII tree visualization of the dependency graph with build levels', 'compute build levels using topological sort to find parallel build order', 'generate a Mermaid diagram format output of the dependency graph', 'output the dependency graph in GraphViz DOT source format']
```

Usage

```
{'render_dependency_graph_as_png': 'render a dependency graph from dependencies.yaml as a PNG image using graphviz', 'print_ascii_dependency_tree': 'print an ASCII tree visualization of the dependency graph with build levels', 'compute_build_levels': 'compute build levels using topological sort to find parallel build order', 'generate_mermaid_diagram': 'generate a Mermaid diagram format output of the dependency graph', 'output_graphviz_dot': 'output the dependency graph in GraphViz DOT source format'}
```

