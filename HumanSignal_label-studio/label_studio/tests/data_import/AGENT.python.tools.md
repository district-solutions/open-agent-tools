# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/tests/data_import/test_persistent_storage_data.py

Prompts

```
['test the DownloadStorageData API view for secure file downloads from persistent storage', 'test upload file serving through NGINX with X-Accel-Redirect header generation', 'test upload file serving directly via RangedFileResponse streaming without NGINX', 'test content type detection for PDF, MP3, MP4, JPG, and unknown file formats', 'test cross-organization access prevention for avatar file downloads', 'test the JSON streaming reader that parses JSON arrays and objects into task batches with configurable batch sizes', 'test loading tasks from multiple uploaded JSON files using streaming aggregation with file upload IDs', 'test loading tasks for async import streaming from file uploads, URL JSON strings, and inline tasks with batch metadata', 'test the async background streaming import that processes file uploads and updates project import status and task counts', 'test that invalid JSON top-level types like strings and arrays of strings raise ValidationError during streaming import', 'test the check_tasks_max_file_size function to validate file size against TASKS_MAX_FILE_SIZE setting', 'test the load_tasks function to verify SSRF protection blocks unsafe local and ftp URLs', 'test the tasks_from_url function to ensure valid file extensions like .json are accepted', 'test the tasks_from_url function to verify invalid extensions like .exe raise a ValidationError', 'test the tasks_from_url function to ensure files exceeding TASKS_MAX_FILE_SIZE raise a ValidationError']
```

Usage

```
{'test_DownloadStorageData': 'test the DownloadStorageData API view for secure file downloads from persistent storage', 'test_upload_file_nginx_serving': 'test upload file serving through NGINX with X-Accel-Redirect header generation', 'test_upload_file_direct_serving': 'test upload file serving directly via RangedFileResponse streaming without NGINX', 'test_content_type_detection': 'test content type detection for PDF, MP3, MP4, JPG, and unknown file formats', 'test_avatar_user_no_organization_access_returns_403': 'test cross-organization access prevention for avatar file downloads'}
```

## File: HumanSignal_label-studio/label_studio/tests/data_import/test_streaming_import.py

Prompts

```
['test the DownloadStorageData API view for secure file downloads from persistent storage', 'test upload file serving through NGINX with X-Accel-Redirect header generation', 'test upload file serving directly via RangedFileResponse streaming without NGINX', 'test content type detection for PDF, MP3, MP4, JPG, and unknown file formats', 'test cross-organization access prevention for avatar file downloads', 'test the JSON streaming reader that parses JSON arrays and objects into task batches with configurable batch sizes', 'test loading tasks from multiple uploaded JSON files using streaming aggregation with file upload IDs', 'test loading tasks for async import streaming from file uploads, URL JSON strings, and inline tasks with batch metadata', 'test the async background streaming import that processes file uploads and updates project import status and task counts', 'test that invalid JSON top-level types like strings and arrays of strings raise ValidationError during streaming import', 'test the check_tasks_max_file_size function to validate file size against TASKS_MAX_FILE_SIZE setting', 'test the load_tasks function to verify SSRF protection blocks unsafe local and ftp URLs', 'test the tasks_from_url function to ensure valid file extensions like .json are accepted', 'test the tasks_from_url function to verify invalid extensions like .exe raise a ValidationError', 'test the tasks_from_url function to ensure files exceeding TASKS_MAX_FILE_SIZE raise a ValidationError']
```

Usage

```
{'test_json_streaming_reader': 'test the JSON streaming reader that parses JSON arrays and objects into task batches with configurable batch sizes', 'test_end_to_end_streaming': 'test loading tasks from multiple uploaded JSON files using streaming aggregation with file upload IDs', 'test_load_tasks_async_streaming': 'test loading tasks for async import streaming from file uploads, URL JSON strings, and inline tasks with batch metadata', 'test_async_import_background_streaming': 'test the async background streaming import that processes file uploads and updates project import status and task counts', 'test_invalid_json_raises_validation': 'test that invalid JSON top-level types like strings and arrays of strings raise ValidationError during streaming import'}
```

## File: HumanSignal_label-studio/label_studio/tests/data_import/test_uploader.py

Prompts

```
['test the DownloadStorageData API view for secure file downloads from persistent storage', 'test upload file serving through NGINX with X-Accel-Redirect header generation', 'test upload file serving directly via RangedFileResponse streaming without NGINX', 'test content type detection for PDF, MP3, MP4, JPG, and unknown file formats', 'test cross-organization access prevention for avatar file downloads', 'test the JSON streaming reader that parses JSON arrays and objects into task batches with configurable batch sizes', 'test loading tasks from multiple uploaded JSON files using streaming aggregation with file upload IDs', 'test loading tasks for async import streaming from file uploads, URL JSON strings, and inline tasks with batch metadata', 'test the async background streaming import that processes file uploads and updates project import status and task counts', 'test that invalid JSON top-level types like strings and arrays of strings raise ValidationError during streaming import', 'test the check_tasks_max_file_size function to validate file size against TASKS_MAX_FILE_SIZE setting', 'test the load_tasks function to verify SSRF protection blocks unsafe local and ftp URLs', 'test the tasks_from_url function to ensure valid file extensions like .json are accepted', 'test the tasks_from_url function to verify invalid extensions like .exe raise a ValidationError', 'test the tasks_from_url function to ensure files exceeding TASKS_MAX_FILE_SIZE raise a ValidationError']
```

Usage

```
{'test_check_tasks_max_file_size': 'test the check_tasks_max_file_size function to validate file size against TASKS_MAX_FILE_SIZE setting', 'test_load_tasks_ssrf_protection': 'test the load_tasks function to verify SSRF protection blocks unsafe local and ftp URLs', 'test_tasks_from_url_valid_extension': 'test the tasks_from_url function to ensure valid file extensions like .json are accepted', 'test_tasks_from_url_invalid_extension': 'test the tasks_from_url function to verify invalid extensions like .exe raise a ValidationError', 'test_tasks_from_url_file_size_limit': 'test the tasks_from_url function to ensure files exceeding TASKS_MAX_FILE_SIZE raise a ValidationError'}
```

