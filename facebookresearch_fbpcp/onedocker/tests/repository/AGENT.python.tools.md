# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/onedocker/tests/repository/test_onedocker_package.py

Prompts

```
['test the OneDockerPackageRepository upload method to copy a package to S3 storage', 'test the OneDockerPackageRepository download method to copy a package from S3 storage', 'test the OneDockerPackageRepository get_package_versions method to list available package versions', 'test the OneDockerPackageRepository get_package_info method to retrieve package metadata from S3', 'test the OneDockerPackageRepository archive_package method to move a package to the archived folder', 'test the OneDockerRepositoryService upload method using DEFAULT_PROD_VERSION to skip version checks', 'test the OneDockerRepositoryService get_package_measurements method to retrieve package hash measurements', 'test the LocalOPAWDLWorkflowInstanceRepository create method to persist a new workflow instance to disk', 'test the LocalOPAWDLWorkflowInstanceRepository get method to retrieve a workflow instance by its instance ID', 'test the LocalOPAWDLWorkflowInstanceRepository update method to overwrite an existing workflow instance on disk', 'test the LocalOPAWDLWorkflowInstanceRepository delete method to remove a workflow instance file by instance ID', 'test the LocalOPAWDLWorkflowInstanceRepository exist method to check if a workflow instance ID is present']
```

Usage

```
{'test_upload': 'test the OneDockerPackageRepository upload method to copy a package to S3 storage', 'test_download': 'test the OneDockerPackageRepository download method to copy a package from S3 storage', 'test_get_package_versions': 'test the OneDockerPackageRepository get_package_versions method to list available package versions', 'test_get_package_info': 'test the OneDockerPackageRepository get_package_info method to retrieve package metadata from S3', 'test_archive_package': 'test the OneDockerPackageRepository archive_package method to move a package to the archived folder'}
```

## File: facebookresearch_fbpcp/onedocker/tests/repository/test_onedocker_repository_service.py

Prompts

```
['test the OneDockerPackageRepository upload method to copy a package to S3 storage', 'test the OneDockerPackageRepository download method to copy a package from S3 storage', 'test the OneDockerPackageRepository get_package_versions method to list available package versions', 'test the OneDockerPackageRepository get_package_info method to retrieve package metadata from S3', 'test the OneDockerPackageRepository archive_package method to move a package to the archived folder', 'test the OneDockerRepositoryService upload method using DEFAULT_PROD_VERSION to skip version checks', 'test the OneDockerRepositoryService get_package_measurements method to retrieve package hash measurements', 'test the LocalOPAWDLWorkflowInstanceRepository create method to persist a new workflow instance to disk', 'test the LocalOPAWDLWorkflowInstanceRepository get method to retrieve a workflow instance by its instance ID', 'test the LocalOPAWDLWorkflowInstanceRepository update method to overwrite an existing workflow instance on disk', 'test the LocalOPAWDLWorkflowInstanceRepository delete method to remove a workflow instance file by instance ID', 'test the LocalOPAWDLWorkflowInstanceRepository exist method to check if a workflow instance ID is present']
```

Usage

```
{'test_upload': 'test the OneDockerRepositoryService upload method to upload a package to a specific version', 'test_download': 'test the OneDockerRepositoryService download method to download a package to a destination path', 'test_archive_package': 'test the OneDockerRepositoryService archive_package method to archive a package by path and version', 'test_upload_latest': 'test the OneDockerRepositoryService upload method using DEFAULT_PROD_VERSION to skip version checks', 'test_get_measurements': 'test the OneDockerRepositoryService get_package_measurements method to retrieve package hash measurements'}
```

## File: facebookresearch_fbpcp/onedocker/tests/repository/test_opawdl_workflow_instance_repository_local.py

Prompts

```
['test the OneDockerPackageRepository upload method to copy a package to S3 storage', 'test the OneDockerPackageRepository download method to copy a package from S3 storage', 'test the OneDockerPackageRepository get_package_versions method to list available package versions', 'test the OneDockerPackageRepository get_package_info method to retrieve package metadata from S3', 'test the OneDockerPackageRepository archive_package method to move a package to the archived folder', 'test the OneDockerRepositoryService upload method using DEFAULT_PROD_VERSION to skip version checks', 'test the OneDockerRepositoryService get_package_measurements method to retrieve package hash measurements', 'test the LocalOPAWDLWorkflowInstanceRepository create method to persist a new workflow instance to disk', 'test the LocalOPAWDLWorkflowInstanceRepository get method to retrieve a workflow instance by its instance ID', 'test the LocalOPAWDLWorkflowInstanceRepository update method to overwrite an existing workflow instance on disk', 'test the LocalOPAWDLWorkflowInstanceRepository delete method to remove a workflow instance file by instance ID', 'test the LocalOPAWDLWorkflowInstanceRepository exist method to check if a workflow instance ID is present']
```

Usage

```
{'test_create_workflow_instance': 'test the LocalOPAWDLWorkflowInstanceRepository create method to persist a new workflow instance to disk', 'test_get_workflow_instance': 'test the LocalOPAWDLWorkflowInstanceRepository get method to retrieve a workflow instance by its instance ID', 'test_update_workflow_instance': 'test the LocalOPAWDLWorkflowInstanceRepository update method to overwrite an existing workflow instance on disk', 'test_delete_workflow_instance': 'test the LocalOPAWDLWorkflowInstanceRepository delete method to remove a workflow instance file by instance ID', 'test_exist_workflow_instance': 'test the LocalOPAWDLWorkflowInstanceRepository exist method to check if a workflow instance ID is present'}
```

