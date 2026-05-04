# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/interop_matrix/client_matrix.py

Prompts

```
['get the github repository URL for a given gRPC language like go, java, or node', 'get the list of known release tags for a given gRPC language such as cxx or python', 'get the list of valid runtimes for a specific language release like go v1.17.0', 'check whether a docker interop image should be built for a given language like cxx', 'create a ReleaseInfo object with optional patch files, runtimes, and testcases file for a gRPC release', 'build all interop docker images for a given language across releases and runtimes', 'build a docker image jobspec for a specific language runtime and release tag', 'add extra files like commit logs to an existing docker image with a label', 'checkout a gRPC git repository at a specific release tag for building interop images', 'apply a git patch file to a checked out release tag for interop test compatibility']
```

Usage

```
{'get_github_repo': 'get the github repository URL for a given gRPC language like go, java, or node', 'get_release_tags': 'get the list of known release tags for a given gRPC language such as cxx or python', 'get_runtimes_for_lang_release': 'get the list of valid runtimes for a specific language release like go v1.17.0', 'should_build_docker_interop_image_from_release_tag': 'check whether a docker interop image should be built for a given language like cxx', 'ReleaseInfo': 'create a ReleaseInfo object with optional patch files, runtimes, and testcases file for a gRPC release'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/interop_matrix/create_matrix_images.py

Prompts

```
['get the github repository URL for a given gRPC language like go, java, or node', 'get the list of known release tags for a given gRPC language such as cxx or python', 'get the list of valid runtimes for a specific language release like go v1.17.0', 'check whether a docker interop image should be built for a given language like cxx', 'create a ReleaseInfo object with optional patch files, runtimes, and testcases file for a gRPC release', 'build all interop docker images for a given language across releases and runtimes', 'build a docker image jobspec for a specific language runtime and release tag', 'add extra files like commit logs to an existing docker image with a label', 'checkout a gRPC git repository at a specific release tag for building interop images', 'apply a git patch file to a checked out release tag for interop test compatibility']
```

Usage

```
{'build_docker_images_for_lang': 'build all interop docker images for a given language across releases and runtimes', 'build_docker_image_jobspec': 'build a docker image jobspec for a specific language runtime and release tag', 'add_files_to_image': 'add extra files like commit logs to an existing docker image with a label', 'checkout_grpc_stack': 'checkout a gRPC git repository at a specific release tag for building interop images', 'apply_patches_on_git_tag': 'apply a git patch file to a checked out release tag for interop test compatibility'}
```

