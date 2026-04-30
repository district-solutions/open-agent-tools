# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/io_storages/s3/tests/test_resolve_s3_url.py

Prompts

```
['test resolve_s3_url adds ResponseContentType=image/jpeg for .jpg files', 'test resolve_s3_url adds ResponseContentType=image/png for .png files', 'test resolve_s3_url adds ResponseContentType=video/mp4 for .mp4 files', 'test resolve_s3_url omits ResponseContentType for unknown file extensions', 'test resolve_s3_url returns base64 blob when presign is false']
```

Usage

```
{'test_resolve_s3_url_jpeg_content_type': 'test resolve_s3_url adds ResponseContentType=image/jpeg for .jpg files', 'test_resolve_s3_url_png_content_type': 'test resolve_s3_url adds ResponseContentType=image/png for .png files', 'test_resolve_s3_url_mp4_content_type': 'test resolve_s3_url adds ResponseContentType=video/mp4 for .mp4 files', 'test_resolve_s3_url_unknown_extension': 'test resolve_s3_url omits ResponseContentType for unknown file extensions', 'test_resolve_s3_url_presign_false': 'test resolve_s3_url returns base64 blob when presign is false'}
```

