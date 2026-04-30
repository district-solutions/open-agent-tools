# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/io_storages/gcs/models.py

Prompts

```
['get a GCS client from GCSStorageMixin using project credentials and project ID', 'get a streaming bytes response from GCS with range header support and metadata', 'save an annotation as JSON to a GCS bucket via GCSExportStorage', 'iterate over GCS bucket objects with optional prefix and regex filtering', 'export an annotation asynchronously to all configured GCS export storages', 'create a GCS import storage serializer with credentials and bucket configuration', 'create a GCS export storage serializer for exporting labeled data to Google Cloud Storage', 'test the GCS import storage serializer validates connection with provided credentials', 'refactor the GCS import storage serializer to strip google_application_credentials from API responses', 'review the GCS export storage serializer to hide sensitive credentials in serialized output', 'validate a GCS bucket connection using project ID, credentials, and optional prefix', 'generate a presigned HTTPS URL for downloading a GCS blob with configurable TTL', 'iterate through GCS bucket blobs with optional prefix, regex filter, limit, and recursive scanning', 'read a GCS blob as base64-encoded bytes for direct embedding or transmission', 'retrieve metadata properties like size and updated date for a GCS object by URI']
```

Usage

```
{'get_client_gcs_storage': 'get a GCS client from GCSStorageMixin using project credentials and project ID', 'get_bytes_stream_gcs': 'get a streaming bytes response from GCS with range header support and metadata', 'save_annotation_gcs_export': 'save an annotation as JSON to a GCS bucket via GCSExportStorage', 'iter_objects_gcs_import': 'iterate over GCS bucket objects with optional prefix and regex filtering', 'export_annotation_async_gcs': 'export an annotation asynchronously to all configured GCS export storages'}
```

## File: HumanSignal_label-studio/label_studio/io_storages/gcs/serializers.py

Prompts

```
['get a GCS client from GCSStorageMixin using project credentials and project ID', 'get a streaming bytes response from GCS with range header support and metadata', 'save an annotation as JSON to a GCS bucket via GCSExportStorage', 'iterate over GCS bucket objects with optional prefix and regex filtering', 'export an annotation asynchronously to all configured GCS export storages', 'create a GCS import storage serializer with credentials and bucket configuration', 'create a GCS export storage serializer for exporting labeled data to Google Cloud Storage', 'test the GCS import storage serializer validates connection with provided credentials', 'refactor the GCS import storage serializer to strip google_application_credentials from API responses', 'review the GCS export storage serializer to hide sensitive credentials in serialized output', 'validate a GCS bucket connection using project ID, credentials, and optional prefix', 'generate a presigned HTTPS URL for downloading a GCS blob with configurable TTL', 'iterate through GCS bucket blobs with optional prefix, regex filter, limit, and recursive scanning', 'read a GCS blob as base64-encoded bytes for direct embedding or transmission', 'retrieve metadata properties like size and updated date for a GCS object by URI']
```

Usage

```
{'create_gcs_import_storage': 'create a GCS import storage serializer with credentials and bucket configuration', 'create_gcs_export_storage': 'create a GCS export storage serializer for exporting labeled data to Google Cloud Storage', 'test_gcs_import_storage_validation': 'test the GCS import storage serializer validates connection with provided credentials', 'refactor_gcs_import_storage_secure_fields': 'refactor the GCS import storage serializer to strip google_application_credentials from API responses', 'review_gcs_export_storage_representation': 'review the GCS export storage serializer to hide sensitive credentials in serialized output'}
```

## File: HumanSignal_label-studio/label_studio/io_storages/gcs/utils.py

Prompts

```
['get a GCS client from GCSStorageMixin using project credentials and project ID', 'get a streaming bytes response from GCS with range header support and metadata', 'save an annotation as JSON to a GCS bucket via GCSExportStorage', 'iterate over GCS bucket objects with optional prefix and regex filtering', 'export an annotation asynchronously to all configured GCS export storages', 'create a GCS import storage serializer with credentials and bucket configuration', 'create a GCS export storage serializer for exporting labeled data to Google Cloud Storage', 'test the GCS import storage serializer validates connection with provided credentials', 'refactor the GCS import storage serializer to strip google_application_credentials from API responses', 'review the GCS export storage serializer to hide sensitive credentials in serialized output', 'validate a GCS bucket connection using project ID, credentials, and optional prefix', 'generate a presigned HTTPS URL for downloading a GCS blob with configurable TTL', 'iterate through GCS bucket blobs with optional prefix, regex filter, limit, and recursive scanning', 'read a GCS blob as base64-encoded bytes for direct embedding or transmission', 'retrieve metadata properties like size and updated date for a GCS object by URI']
```

Usage

```
{'validate_gcs_connection': 'validate a GCS bucket connection using project ID, credentials, and optional prefix', 'generate_signed_gcs_url': 'generate a presigned HTTPS URL for downloading a GCS blob with configurable TTL', 'iterate_gcs_blobs': 'iterate through GCS bucket blobs with optional prefix, regex filter, limit, and recursive scanning', 'read_gcs_file_base64': 'read a GCS blob as base64-encoded bytes for direct embedding or transmission', 'get_gcs_blob_metadata': 'retrieve metadata properties like size and updated date for a GCS object by URI'}
```

