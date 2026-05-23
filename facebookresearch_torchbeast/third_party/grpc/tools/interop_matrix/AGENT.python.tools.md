# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/interop_matrix/client_matrix.py

Prompts

```
['get the github repository URL for a given gRPC language like go or java', 'get the list of known release tags for a given gRPC language', 'get the list of valid runtimes for a given language and release version', 'check if a docker interop image should be built for a given language', 'create a ReleaseInfo object with patch files, runtimes, and testcases file for a release', 'build interop docker images for a gRPC language across all releases and runtimes', 'build interop docker images for a specific gRPC release across all runtimes', 'add extra files and labels to an existing docker image by repackaging it', 'clone and checkout a gRPC language repo at a specific release tag', 'apply a git patch file to a checked out gRPC release tag']
```

Usage

```
{'get_github_repo': 'get the github repository URL for a given gRPC language like go or java', 'get_release_tags': 'get the list of known release tags for a given gRPC language', 'get_runtimes_for_lang_release': 'get the list of valid runtimes for a given language and release version', 'should_build_docker_interop_image_from_release_tag': 'check if a docker interop image should be built for a given language', 'ReleaseInfo': 'create a ReleaseInfo object with patch files, runtimes, and testcases file for a release'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/interop_matrix/create_matrix_images.py

Prompts

```
['get the github repository URL for a given gRPC language like go or java', 'get the list of known release tags for a given gRPC language', 'get the list of valid runtimes for a given language and release version', 'check if a docker interop image should be built for a given language', 'create a ReleaseInfo object with patch files, runtimes, and testcases file for a release', 'build interop docker images for a gRPC language across all releases and runtimes', 'build interop docker images for a specific gRPC release across all runtimes', 'add extra files and labels to an existing docker image by repackaging it', 'clone and checkout a gRPC language repo at a specific release tag', 'apply a git patch file to a checked out gRPC release tag']
```

Usage

```
{'build_docker_images_for_lang': 'build interop docker images for a gRPC language across all releases and runtimes', 'build_docker_images_for_release': 'build interop docker images for a specific gRPC release across all runtimes', 'add_files_to_image': 'add extra files and labels to an existing docker image by repackaging it', 'checkout_grpc_stack': 'clone and checkout a gRPC language repo at a specific release tag', 'apply_patches_on_git_tag': 'apply a git patch file to a checked out gRPC release tag'}
```

