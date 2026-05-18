# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/interop_matrix/client_matrix.py

Prompts

```
['get the github repository URL for a given gRPC language like go or java', 'get the list of known release tags for a given gRPC language', 'get the list of valid runtimes for a given language and release version', 'check whether a docker interop image should be built for a given language', 'create a ReleaseInfo object with patch files, runtimes, and testcases file for a release', 'build all interop docker images for a specified language across releases and runtimes', 'add extra files like commit logs to an existing docker image with a label', 'clone and checkout a gRPC git repo at a specific release tag for building', 'apply a git patch file to a checked out release tag for interop test compatibility', 'push built docker images to Google Container Registry using gcloud docker push']
```

Usage

```
{'get_github_repo': 'get the github repository URL for a given gRPC language like go or java', 'get_release_tags': 'get the list of known release tags for a given gRPC language', 'get_runtimes_for_lang_release': 'get the list of valid runtimes for a given language and release version', 'should_build_docker_interop_image': 'check whether a docker interop image should be built for a given language', 'create_ReleaseInfo': 'create a ReleaseInfo object with patch files, runtimes, and testcases file for a release'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/interop_matrix/create_matrix_images.py

Prompts

```
['get the github repository URL for a given gRPC language like go or java', 'get the list of known release tags for a given gRPC language', 'get the list of valid runtimes for a given language and release version', 'check whether a docker interop image should be built for a given language', 'create a ReleaseInfo object with patch files, runtimes, and testcases file for a release', 'build all interop docker images for a specified language across releases and runtimes', 'add extra files like commit logs to an existing docker image with a label', 'clone and checkout a gRPC git repo at a specific release tag for building', 'apply a git patch file to a checked out release tag for interop test compatibility', 'push built docker images to Google Container Registry using gcloud docker push']
```

Usage

```
{'build_docker_images_for_lang': 'build all interop docker images for a specified language across releases and runtimes', 'add_files_to_image': 'add extra files like commit logs to an existing docker image with a label', 'checkout_grpc_stack': 'clone and checkout a gRPC git repo at a specific release tag for building', 'apply_patches_on_git_tag': 'apply a git patch file to a checked out release tag for interop test compatibility', 'upload_images_to_gcr': 'push built docker images to Google Container Registry using gcloud docker push'}
```

