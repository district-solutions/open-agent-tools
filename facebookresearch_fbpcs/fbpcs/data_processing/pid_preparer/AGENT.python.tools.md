# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/data_processing/pid_preparer/preparer.py

Prompts

```
['implement a subclass of UnionPIDDataPreparerService that prepares PID data from input to output path', 'implement a subclass that prepares PID data inside a Docker container using OneDockerService', 'implement an async subclass that prepares PID data in a container and returns a ContainerInstance', 'review the UnionPIDDataPreparerService abstract base class and its three abstract method signatures', 'refactor a UnionPIDDataPreparerService subclass to support custom log paths and storage service injection', 'run the C++ union PID preparer binary on local input and output paths with optional storage service', 'run the union PID preparer inside a Docker container using OneDockerService with configurable timeout and column count', 'run the union PID preparer asynchronously in a container with retry logic for throttling errors', 'review the CppUnionPIDDataPreparerService class that extends UnionPIDDataPreparerService for C++ based PID data preparation', 'summarize the CPP_UNION_PID_PREPARER_PATH constant that defaults to cpp_bin/union_pid_data_preparer from an environment variable']
```

Usage

```
{'implement_prepare': 'implement a subclass of UnionPIDDataPreparerService that prepares PID data from input to output path', 'implement_prepare_on_container': 'implement a subclass that prepares PID data inside a Docker container using OneDockerService', 'implement_prepare_on_container_async': 'implement an async subclass that prepares PID data in a container and returns a ContainerInstance', 'review_abstract_class': 'review the UnionPIDDataPreparerService abstract base class and its three abstract method signatures', 'refactor_prepare_method': 'refactor a UnionPIDDataPreparerService subclass to support custom log paths and storage service injection'}
```

## File: facebookresearch_fbpcs/fbpcs/data_processing/pid_preparer/union_pid_preparer_cpp.py

Prompts

```
['implement a subclass of UnionPIDDataPreparerService that prepares PID data from input to output path', 'implement a subclass that prepares PID data inside a Docker container using OneDockerService', 'implement an async subclass that prepares PID data in a container and returns a ContainerInstance', 'review the UnionPIDDataPreparerService abstract base class and its three abstract method signatures', 'refactor a UnionPIDDataPreparerService subclass to support custom log paths and storage service injection', 'run the C++ union PID preparer binary on local input and output paths with optional storage service', 'run the union PID preparer inside a Docker container using OneDockerService with configurable timeout and column count', 'run the union PID preparer asynchronously in a container with retry logic for throttling errors', 'review the CppUnionPIDDataPreparerService class that extends UnionPIDDataPreparerService for C++ based PID data preparation', 'summarize the CPP_UNION_PID_PREPARER_PATH constant that defaults to cpp_bin/union_pid_data_preparer from an environment variable']
```

Usage

```
{'run_CppUnionPIDDataPreparerService_prepare': 'run the C++ union PID preparer binary on local input and output paths with optional storage service', 'run_CppUnionPIDDataPreparerService_prepare_on_container': 'run the union PID preparer inside a Docker container using OneDockerService with configurable timeout and column count', 'run_CppUnionPIDDataPreparerService_prepare_on_container_async': 'run the union PID preparer asynchronously in a container with retry logic for throttling errors', 'review_CppUnionPIDDataPreparerService': 'review the CppUnionPIDDataPreparerService class that extends UnionPIDDataPreparerService for C++ based PID data preparation', 'summarize_CPP_UNION_PID_PREPARER_PATH': 'summarize the CPP_UNION_PID_PREPARER_PATH constant that defaults to cpp_bin/union_pid_data_preparer from an environment variable'}
```

