# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/io_storages/azure_blob/models.py

Prompts

```
['build an Azure Blob import storage model to list and retrieve objects from a container with optional prefix and regex filtering', 'test an Azure Blob Storage connection by validating container existence and verifying prefix path contains blobs', 'create an Azure Blob export storage that serializes and uploads annotation data to a blob container', 'run async export of an annotation to all linked Azure Blob export storages on the project', 'generate a presigned SAS URL for an Azure Blob with configurable read permission and TTL', 'create an Azure Blob import storage serializer with presign support and secure field masking', 'validate Azure Blob import storage connection using serializer validate method', 'create an Azure Blob export storage serializer with secure field redaction', 'test Azure Blob import serializer validation with missing or partial credentials', 'review Azure Blob import serializer to_representation to ensure secure fields are excluded', 'build an Azure Blob Storage client and container from account name and key', 'create a streaming response downloader with unified HTTP range handling for Azure blobs', 'test a glob or regex pattern against Azure Blob Storage container keys', 'summarize the blob metadata retrieval for a given container and object key', 'review the Azure blob streaming response with range parsing and metadata generation']
```

Usage

```
{'build_azure_blob_import_storage': 'build an Azure Blob import storage model to list and retrieve objects from a container with optional prefix and regex filtering', 'test_azure_blob_connection': 'test an Azure Blob Storage connection by validating container existence and verifying prefix path contains blobs', 'create_azure_blob_export_storage': 'create an Azure Blob export storage that serializes and uploads annotation data to a blob container', 'run_azure_blob_export_annotation': 'run async export of an annotation to all linked Azure Blob export storages on the project', 'generate_presigned_blob_url': 'generate a presigned SAS URL for an Azure Blob with configurable read permission and TTL'}
```

## File: HumanSignal_label-studio/label_studio/io_storages/azure_blob/serializers.py

Prompts

```
['build an Azure Blob import storage model to list and retrieve objects from a container with optional prefix and regex filtering', 'test an Azure Blob Storage connection by validating container existence and verifying prefix path contains blobs', 'create an Azure Blob export storage that serializes and uploads annotation data to a blob container', 'run async export of an annotation to all linked Azure Blob export storages on the project', 'generate a presigned SAS URL for an Azure Blob with configurable read permission and TTL', 'create an Azure Blob import storage serializer with presign support and secure field masking', 'validate Azure Blob import storage connection using serializer validate method', 'create an Azure Blob export storage serializer with secure field redaction', 'test Azure Blob import serializer validation with missing or partial credentials', 'review Azure Blob import serializer to_representation to ensure secure fields are excluded', 'build an Azure Blob Storage client and container from account name and key', 'create a streaming response downloader with unified HTTP range handling for Azure blobs', 'test a glob or regex pattern against Azure Blob Storage container keys', 'summarize the blob metadata retrieval for a given container and object key', 'review the Azure blob streaming response with range parsing and metadata generation']
```

Usage

```
{'create_AzureBlobImportStorageSerializer': 'create an Azure Blob import storage serializer with presign support and secure field masking', 'validate_azure_import_connection': 'validate Azure Blob import storage connection using serializer validate method', 'create_AzureBlobExportStorageSerializer': 'create an Azure Blob export storage serializer with secure field redaction', 'test_AzureBlobImportStorageSerializer_validate': 'test Azure Blob import serializer validation with missing or partial credentials', 'review_AzureBlobImportStorageSerializer_to_representation': 'review Azure Blob import serializer to_representation to ensure secure fields are excluded'}
```

## File: HumanSignal_label-studio/label_studio/io_storages/azure_blob/utils.py

Prompts

```
['build an Azure Blob import storage model to list and retrieve objects from a container with optional prefix and regex filtering', 'test an Azure Blob Storage connection by validating container existence and verifying prefix path contains blobs', 'create an Azure Blob export storage that serializes and uploads annotation data to a blob container', 'run async export of an annotation to all linked Azure Blob export storages on the project', 'generate a presigned SAS URL for an Azure Blob with configurable read permission and TTL', 'create an Azure Blob import storage serializer with presign support and secure field masking', 'validate Azure Blob import storage connection using serializer validate method', 'create an Azure Blob export storage serializer with secure field redaction', 'test Azure Blob import serializer validation with missing or partial credentials', 'review Azure Blob import serializer to_representation to ensure secure fields are excluded', 'build an Azure Blob Storage client and container from account name and key', 'create a streaming response downloader with unified HTTP range handling for Azure blobs', 'test a glob or regex pattern against Azure Blob Storage container keys', 'summarize the blob metadata retrieval for a given container and object key', 'review the Azure blob streaming response with range parsing and metadata generation']
```

Usage

```
{'build_azure_blob_client': 'build an Azure Blob Storage client and container from account name and key', 'create_download_stream_response': 'create a streaming response downloader with unified HTTP range handling for Azure blobs', 'test_validate_pattern': 'test a glob or regex pattern against Azure Blob Storage container keys', 'summarize_get_blob_metadata': 'summarize the blob metadata retrieval for a given container and object key', 'review_download_stream_response': 'review the Azure blob streaming response with range parsing and metadata generation'}
```

