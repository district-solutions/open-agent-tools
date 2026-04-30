# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/io_storages/s3/models.py

Prompts

```
['create an S3 import storage instance with bucket, prefix, and AWS credentials for reading data files', 'create an S3 export storage instance with bucket and prefix for writing annotation data', 'test the S3 storage connection by validating bucket access with prefix and region configuration', 'iterate over S3 storage objects filtered by prefix, delimiter, and regex pattern', 'build an S3 export pipeline that saves annotation data to S3 on post-save and deletes on pre-delete', 'build an S3 import storage serializer that validates bucket names and AWS credentials for importing data', 'build an S3 export storage serializer that validates bucket names and AWS credentials for exporting data', 'test the S3StorageSerializerMixin validate_bucket method for correct and invalid bucket name formats', 'test the S3StorageSerializerMixin validate method for S3 connection validation with correct and incorrect credentials', 'review the S3StorageSerializerMixin to_representation method that strips secure fields from serialized output', 'create boto3 S3 client and resource session with AWS credentials and optional custom endpoint', 'build a presigned URL for an S3 object with configurable expiration and content-type override', 'test if S3 bucket objects match a glob or regex pattern', 'get metadata dictionary for an S3 object without the body or response metadata', 'review decorator that wraps methods to catch exceptions from untrusted S3 domains and raise S3StorageError']
```

Usage

```
{'create_s3_import_storage': 'create an S3 import storage instance with bucket, prefix, and AWS credentials for reading data files', 'create_s3_export_storage': 'create an S3 export storage instance with bucket and prefix for writing annotation data', 'test_s3_connection': 'test the S3 storage connection by validating bucket access with prefix and region configuration', 'run_s3_iter_objects': 'iterate over S3 storage objects filtered by prefix, delimiter, and regex pattern', 'build_s3_annotation_export': 'build an S3 export pipeline that saves annotation data to S3 on post-save and deletes on pre-delete'}
```

## File: HumanSignal_label-studio/label_studio/io_storages/s3/serializers.py

Prompts

```
['create an S3 import storage instance with bucket, prefix, and AWS credentials for reading data files', 'create an S3 export storage instance with bucket and prefix for writing annotation data', 'test the S3 storage connection by validating bucket access with prefix and region configuration', 'iterate over S3 storage objects filtered by prefix, delimiter, and regex pattern', 'build an S3 export pipeline that saves annotation data to S3 on post-save and deletes on pre-delete', 'build an S3 import storage serializer that validates bucket names and AWS credentials for importing data', 'build an S3 export storage serializer that validates bucket names and AWS credentials for exporting data', 'test the S3StorageSerializerMixin validate_bucket method for correct and invalid bucket name formats', 'test the S3StorageSerializerMixin validate method for S3 connection validation with correct and incorrect credentials', 'review the S3StorageSerializerMixin to_representation method that strips secure fields from serialized output', 'create boto3 S3 client and resource session with AWS credentials and optional custom endpoint', 'build a presigned URL for an S3 object with configurable expiration and content-type override', 'test if S3 bucket objects match a glob or regex pattern', 'get metadata dictionary for an S3 object without the body or response metadata', 'review decorator that wraps methods to catch exceptions from untrusted S3 domains and raise S3StorageError']
```

Usage

```
{'build_s3_import_storage_serializer': 'build an S3 import storage serializer that validates bucket names and AWS credentials for importing data', 'build_s3_export_storage_serializer': 'build an S3 export storage serializer that validates bucket names and AWS credentials for exporting data', 'test_validate_bucket': 'test the S3StorageSerializerMixin validate_bucket method for correct and invalid bucket name formats', 'test_validate_connection': 'test the S3StorageSerializerMixin validate method for S3 connection validation with correct and incorrect credentials', 'review_to_representation': 'review the S3StorageSerializerMixin to_representation method that strips secure fields from serialized output'}
```

## File: HumanSignal_label-studio/label_studio/io_storages/s3/utils.py

Prompts

```
['create an S3 import storage instance with bucket, prefix, and AWS credentials for reading data files', 'create an S3 export storage instance with bucket and prefix for writing annotation data', 'test the S3 storage connection by validating bucket access with prefix and region configuration', 'iterate over S3 storage objects filtered by prefix, delimiter, and regex pattern', 'build an S3 export pipeline that saves annotation data to S3 on post-save and deletes on pre-delete', 'build an S3 import storage serializer that validates bucket names and AWS credentials for importing data', 'build an S3 export storage serializer that validates bucket names and AWS credentials for exporting data', 'test the S3StorageSerializerMixin validate_bucket method for correct and invalid bucket name formats', 'test the S3StorageSerializerMixin validate method for S3 connection validation with correct and incorrect credentials', 'review the S3StorageSerializerMixin to_representation method that strips secure fields from serialized output', 'create boto3 S3 client and resource session with AWS credentials and optional custom endpoint', 'build a presigned URL for an S3 object with configurable expiration and content-type override', 'test if S3 bucket objects match a glob or regex pattern', 'get metadata dictionary for an S3 object without the body or response metadata', 'review decorator that wraps methods to catch exceptions from untrusted S3 domains and raise S3StorageError']
```

Usage

```
{'create_s3_client_and_resource': 'create boto3 S3 client and resource session with AWS credentials and optional custom endpoint', 'build_presigned_s3_url': 'build a presigned URL for an S3 object with configurable expiration and content-type override', 'test_s3_pattern_match': 'test if S3 bucket objects match a glob or regex pattern', 'get_s3_blob_metadata': 'get metadata dictionary for an S3 object without the body or response metadata', 'review_s3_storage_error_decorator': 'review decorator that wraps methods to catch exceptions from untrusted S3 domains and raise S3StorageError'}
```

