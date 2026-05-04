# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/test/apps/webui/storage/test_provider.py

Prompts

```
['test the get_storage_provider function to retrieve local, s3, gcs, and azure storage providers by name', 'test the S3StorageProvider upload_file method to upload binary content to an S3 bucket and local directory', 'test the GCSStorageProvider delete_all_files method to remove all blobs from a GCS bucket and local storage', 'test the AzureStorageProvider upload_file method to upload blobs to Azure Blob Storage with mocked clients', 'test that StorageProvider abstract class cannot be instantiated directly while concrete providers can']
```

Usage

```
{'test_get_storage_provider': 'test the get_storage_provider function to retrieve local, s3, gcs, and azure storage providers by name', 'test_upload_file_s3': 'test the S3StorageProvider upload_file method to upload binary content to an S3 bucket and local directory', 'test_delete_all_files_gcs': 'test the GCSStorageProvider delete_all_files method to remove all blobs from a GCS bucket and local storage', 'test_upload_file_azure': 'test the AzureStorageProvider upload_file method to upload blobs to Azure Blob Storage with mocked clients', 'test_class_instantiation': 'test that StorageProvider abstract class cannot be instantiated directly while concrete providers can'}
```

