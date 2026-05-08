# Agent Python Tools

- repo: facebookresearch/co3d
- repo_uri: https://github.com/facebookresearch/co3d

## File: facebookresearch_co3d/co3d/dataset/check_checksum.py

Prompts

```
['run the CLI to verify SHA256 checksums of CO3D dataset zip files in a download folder', 'run the main function to validate all zip file checksums against expected SHA256 hashes', 'run sha256_file to compute the SHA256 hash digest of a single file path', 'run get_expected_sha256s to load expected checksums from a JSON file for full or single-sequence subsets', 'run check_co3d_sha256 to verify a single zip file checksum against expected values with optional assertion', 'load a list of FrameAnnotation dataclasses from a JSON file using load_dataclass with the appropriate type annotation', 'dump a FrameAnnotation or SequenceAnnotation dataclass to a JSON file using dump_dataclass with json.dump', 'load a gzipped JSON file containing FrameAnnotation dataclasses using load_dataclass_jgzip with the target class type', 'dump a list of FrameAnnotation dataclasses to a gzipped JSON file using dump_dataclass_jgzip', 'create a FrameAnnotation dataclass with sequence_name, frame_number, frame_timestamp, and an ImageAnnotation image field', 'run the download_dataset function to download and unpack CO3D dataset files with parallel workers', 'run build_arg_parser to create an ArgumentParser for downloading the CO3D dataset with configurable options', 'run _download_category_file to download a single CO3D category file with optional SHA256 checksum validation', 'run _download_metadata_file to download a CO3D dataset metadata file to a specified folder', 'run _download_with_progress_bar to download a file from a URL with a tqdm progress bar', 'redact the first image and point cloud fields from a FrameData object for CO3D evaluation', 'check that a FrameData evaluation batch is correctly redacted for TEST or DEV sequence sets', 'create a deep copy of FrameData with zeroed image, depth, mask, and foreground probability tensors', 'validate that TEST sequence set FrameData has the first image and all depth maps redacted', 'validate that DEV sequence set FrameData has no redacted fields']
```

Usage

```
{'run_check_co3d_sha256': 'run the CLI to verify SHA256 checksums of CO3D dataset zip files in a download folder', 'run_main_checksum_validation': 'run the main function to validate all zip file checksums against expected SHA256 hashes', 'run_sha256_file_hash': 'run sha256_file to compute the SHA256 hash digest of a single file path', 'run_get_expected_sha256s': 'run get_expected_sha256s to load expected checksums from a JSON file for full or single-sequence subsets', 'run_check_single_file': 'run check_co3d_sha256 to verify a single zip file checksum against expected values with optional assertion'}
```

## File: facebookresearch_co3d/co3d/dataset/data_types.py

Prompts

```
['run the CLI to verify SHA256 checksums of CO3D dataset zip files in a download folder', 'run the main function to validate all zip file checksums against expected SHA256 hashes', 'run sha256_file to compute the SHA256 hash digest of a single file path', 'run get_expected_sha256s to load expected checksums from a JSON file for full or single-sequence subsets', 'run check_co3d_sha256 to verify a single zip file checksum against expected values with optional assertion', 'load a list of FrameAnnotation dataclasses from a JSON file using load_dataclass with the appropriate type annotation', 'dump a FrameAnnotation or SequenceAnnotation dataclass to a JSON file using dump_dataclass with json.dump', 'load a gzipped JSON file containing FrameAnnotation dataclasses using load_dataclass_jgzip with the target class type', 'dump a list of FrameAnnotation dataclasses to a gzipped JSON file using dump_dataclass_jgzip', 'create a FrameAnnotation dataclass with sequence_name, frame_number, frame_timestamp, and an ImageAnnotation image field', 'run the download_dataset function to download and unpack CO3D dataset files with parallel workers', 'run build_arg_parser to create an ArgumentParser for downloading the CO3D dataset with configurable options', 'run _download_category_file to download a single CO3D category file with optional SHA256 checksum validation', 'run _download_metadata_file to download a CO3D dataset metadata file to a specified folder', 'run _download_with_progress_bar to download a file from a URL with a tqdm progress bar', 'redact the first image and point cloud fields from a FrameData object for CO3D evaluation', 'check that a FrameData evaluation batch is correctly redacted for TEST or DEV sequence sets', 'create a deep copy of FrameData with zeroed image, depth, mask, and foreground probability tensors', 'validate that TEST sequence set FrameData has the first image and all depth maps redacted', 'validate that DEV sequence set FrameData has no redacted fields']
```

Usage

```
{'load_dataclass_from_json': 'load a list of FrameAnnotation dataclasses from a JSON file using load_dataclass with the appropriate type annotation', 'dump_dataclass_to_json': 'dump a FrameAnnotation or SequenceAnnotation dataclass to a JSON file using dump_dataclass with json.dump', 'load_dataclass_jgzip': 'load a gzipped JSON file containing FrameAnnotation dataclasses using load_dataclass_jgzip with the target class type', 'dump_dataclass_jgzip': 'dump a list of FrameAnnotation dataclasses to a gzipped JSON file using dump_dataclass_jgzip', 'create_FrameAnnotation_dataclass': 'create a FrameAnnotation dataclass with sequence_name, frame_number, frame_timestamp, and an ImageAnnotation image field'}
```

## File: facebookresearch_co3d/co3d/dataset/download_dataset_impl.py

Prompts

```
['run the CLI to verify SHA256 checksums of CO3D dataset zip files in a download folder', 'run the main function to validate all zip file checksums against expected SHA256 hashes', 'run sha256_file to compute the SHA256 hash digest of a single file path', 'run get_expected_sha256s to load expected checksums from a JSON file for full or single-sequence subsets', 'run check_co3d_sha256 to verify a single zip file checksum against expected values with optional assertion', 'load a list of FrameAnnotation dataclasses from a JSON file using load_dataclass with the appropriate type annotation', 'dump a FrameAnnotation or SequenceAnnotation dataclass to a JSON file using dump_dataclass with json.dump', 'load a gzipped JSON file containing FrameAnnotation dataclasses using load_dataclass_jgzip with the target class type', 'dump a list of FrameAnnotation dataclasses to a gzipped JSON file using dump_dataclass_jgzip', 'create a FrameAnnotation dataclass with sequence_name, frame_number, frame_timestamp, and an ImageAnnotation image field', 'run the download_dataset function to download and unpack CO3D dataset files with parallel workers', 'run build_arg_parser to create an ArgumentParser for downloading the CO3D dataset with configurable options', 'run _download_category_file to download a single CO3D category file with optional SHA256 checksum validation', 'run _download_metadata_file to download a CO3D dataset metadata file to a specified folder', 'run _download_with_progress_bar to download a file from a URL with a tqdm progress bar', 'redact the first image and point cloud fields from a FrameData object for CO3D evaluation', 'check that a FrameData evaluation batch is correctly redacted for TEST or DEV sequence sets', 'create a deep copy of FrameData with zeroed image, depth, mask, and foreground probability tensors', 'validate that TEST sequence set FrameData has the first image and all depth maps redacted', 'validate that DEV sequence set FrameData has no redacted fields']
```

Usage

```
{'run_download_dataset': 'run the download_dataset function to download and unpack CO3D dataset files with parallel workers', 'run_build_arg_parser': 'run build_arg_parser to create an ArgumentParser for downloading the CO3D dataset with configurable options', 'run_download_category_file': 'run _download_category_file to download a single CO3D category file with optional SHA256 checksum validation', 'run_download_metadata_file': 'run _download_metadata_file to download a CO3D dataset metadata file to a specified folder', 'run_download_with_progress_bar': 'run _download_with_progress_bar to download a file from a URL with a tqdm progress bar'}
```

## File: facebookresearch_co3d/co3d/dataset/utils.py

Prompts

```
['run the CLI to verify SHA256 checksums of CO3D dataset zip files in a download folder', 'run the main function to validate all zip file checksums against expected SHA256 hashes', 'run sha256_file to compute the SHA256 hash digest of a single file path', 'run get_expected_sha256s to load expected checksums from a JSON file for full or single-sequence subsets', 'run check_co3d_sha256 to verify a single zip file checksum against expected values with optional assertion', 'load a list of FrameAnnotation dataclasses from a JSON file using load_dataclass with the appropriate type annotation', 'dump a FrameAnnotation or SequenceAnnotation dataclass to a JSON file using dump_dataclass with json.dump', 'load a gzipped JSON file containing FrameAnnotation dataclasses using load_dataclass_jgzip with the target class type', 'dump a list of FrameAnnotation dataclasses to a gzipped JSON file using dump_dataclass_jgzip', 'create a FrameAnnotation dataclass with sequence_name, frame_number, frame_timestamp, and an ImageAnnotation image field', 'run the download_dataset function to download and unpack CO3D dataset files with parallel workers', 'run build_arg_parser to create an ArgumentParser for downloading the CO3D dataset with configurable options', 'run _download_category_file to download a single CO3D category file with optional SHA256 checksum validation', 'run _download_metadata_file to download a CO3D dataset metadata file to a specified folder', 'run _download_with_progress_bar to download a file from a URL with a tqdm progress bar', 'redact the first image and point cloud fields from a FrameData object for CO3D evaluation', 'check that a FrameData evaluation batch is correctly redacted for TEST or DEV sequence sets', 'create a deep copy of FrameData with zeroed image, depth, mask, and foreground probability tensors', 'validate that TEST sequence set FrameData has the first image and all depth maps redacted', 'validate that DEV sequence set FrameData has no redacted fields']
```

Usage

```
{'redact_eval_frame_data': 'redact the first image and point cloud fields from a FrameData object for CO3D evaluation', 'check_valid_eval_frame_data': 'check that a FrameData evaluation batch is correctly redacted for TEST or DEV sequence sets', 'create_frame_data_redaction': 'create a deep copy of FrameData with zeroed image, depth, mask, and foreground probability tensors', 'validate_test_redaction': 'validate that TEST sequence set FrameData has the first image and all depth maps redacted', 'validate_dev_redaction': 'validate that DEV sequence set FrameData has no redacted fields'}
```

