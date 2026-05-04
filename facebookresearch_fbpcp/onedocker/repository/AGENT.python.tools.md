# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/onedocker/repository/onedocker_package.py

Prompts

```
['upload a package to the repository by copying it from a source path to the repository', 'download a package from the repository by copying it to a specified destination path', 'get a list of all available versions for a given package name in the repository', 'get package metadata including last modified date and size for a specific package version', 'archive a package by copying it from the repository to the archived directory', 'get the sha256 measurements and metadata for a docker package by name and version', 'generate package metadata including sha256 measurements for a docker package from a source file', 'create a subclass of OPAWDLWorkflowInstanceRepository that persists an OPAWDLWorkflowInstance to storage', 'get an OPAWDLWorkflowInstance by its instance_id from the repository implementation', 'update an existing OPAWDLWorkflowInstance in the repository with new field values', 'delete an OPAWDLWorkflowInstance from the repository by its instance_id', 'check whether an OPAWDLWorkflowInstance with a given instance_id exists in the repository', 'check if a workflow instance exists in the local repository by its instance ID']
```

Usage

```
{'upload_package': 'upload a package to the repository by copying it from a source path to the repository', 'download_package': 'download a package from the repository by copying it to a specified destination path', 'get_package_versions': 'get a list of all available versions for a given package name in the repository', 'get_package_info': 'get package metadata including last modified date and size for a specific package version', 'archive_package': 'archive a package by copying it from the repository to the archived directory'}
```

## File: facebookresearch_fbpcp/onedocker/repository/onedocker_repository_service.py

Prompts

```
['upload a package to the repository by copying it from a source path to the repository', 'download a package from the repository by copying it to a specified destination path', 'get a list of all available versions for a given package name in the repository', 'get package metadata including last modified date and size for a specific package version', 'archive a package by copying it from the repository to the archived directory', 'get the sha256 measurements and metadata for a docker package by name and version', 'generate package metadata including sha256 measurements for a docker package from a source file', 'create a subclass of OPAWDLWorkflowInstanceRepository that persists an OPAWDLWorkflowInstance to storage', 'get an OPAWDLWorkflowInstance by its instance_id from the repository implementation', 'update an existing OPAWDLWorkflowInstance in the repository with new field values', 'delete an OPAWDLWorkflowInstance from the repository by its instance_id', 'check whether an OPAWDLWorkflowInstance with a given instance_id exists in the repository', 'check if a workflow instance exists in the local repository by its instance ID']
```

Usage

```
{'upload_package': 'upload a docker package with name, version, and source path to the repository', 'download_package': 'download a docker package by name and version to a specified destination path', 'archive_package': 'archive a docker package by name and version from the repository', 'get_package_measurements': 'get the sha256 measurements and metadata for a docker package by name and version', 'generate_metadata': 'generate package metadata including sha256 measurements for a docker package from a source file'}
```

## File: facebookresearch_fbpcp/onedocker/repository/opawdl_workflow_instance_repository.py

Prompts

```
['upload a package to the repository by copying it from a source path to the repository', 'download a package from the repository by copying it to a specified destination path', 'get a list of all available versions for a given package name in the repository', 'get package metadata including last modified date and size for a specific package version', 'archive a package by copying it from the repository to the archived directory', 'get the sha256 measurements and metadata for a docker package by name and version', 'generate package metadata including sha256 measurements for a docker package from a source file', 'create a subclass of OPAWDLWorkflowInstanceRepository that persists an OPAWDLWorkflowInstance to storage', 'get an OPAWDLWorkflowInstance by its instance_id from the repository implementation', 'update an existing OPAWDLWorkflowInstance in the repository with new field values', 'delete an OPAWDLWorkflowInstance from the repository by its instance_id', 'check whether an OPAWDLWorkflowInstance with a given instance_id exists in the repository', 'check if a workflow instance exists in the local repository by its instance ID']
```

Usage

```
{'create_workflow_instance': 'create a subclass of OPAWDLWorkflowInstanceRepository that persists an OPAWDLWorkflowInstance to storage', 'get_workflow_instance': 'get an OPAWDLWorkflowInstance by its instance_id from the repository implementation', 'update_workflow_instance': 'update an existing OPAWDLWorkflowInstance in the repository with new field values', 'delete_workflow_instance': 'delete an OPAWDLWorkflowInstance from the repository by its instance_id', 'check_workflow_instance_exists': 'check whether an OPAWDLWorkflowInstance with a given instance_id exists in the repository'}
```

## File: facebookresearch_fbpcp/onedocker/repository/opawdl_workflow_instance_repository_local.py

Prompts

```
['upload a package to the repository by copying it from a source path to the repository', 'download a package from the repository by copying it to a specified destination path', 'get a list of all available versions for a given package name in the repository', 'get package metadata including last modified date and size for a specific package version', 'archive a package by copying it from the repository to the archived directory', 'get the sha256 measurements and metadata for a docker package by name and version', 'generate package metadata including sha256 measurements for a docker package from a source file', 'create a subclass of OPAWDLWorkflowInstanceRepository that persists an OPAWDLWorkflowInstance to storage', 'get an OPAWDLWorkflowInstance by its instance_id from the repository implementation', 'update an existing OPAWDLWorkflowInstance in the repository with new field values', 'delete an OPAWDLWorkflowInstance from the repository by its instance_id', 'check whether an OPAWDLWorkflowInstance with a given instance_id exists in the repository', 'check if a workflow instance exists in the local repository by its instance ID']
```

Usage

```
{'create_workflow_instance': 'create a LocalOPAWDLWorkflowInstanceRepository to persist OPAWDL workflow instances to the local filesystem', 'check_instance_exists': 'check if a workflow instance exists in the local repository by its instance ID', 'get_workflow_instance': 'get an OPAWDL workflow instance from the local repository by reading its JSON file', 'update_workflow_instance': 'update an existing OPAWDL workflow instance by overwriting its JSON file on disk', 'delete_workflow_instance': 'delete an OPAWDL workflow instance from the local repository by removing its file'}
```

