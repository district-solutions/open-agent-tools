# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/libs/libcommon/tests/fixtures/datasets.py

Prompts

```
['create a HuggingFace Dataset fixture from a pandas DataFrame with a specific dtype using the value helper', 'create a HuggingFace Dataset fixture from a dict with an optional FeatureType using the other helper', 'test all 35+ dataset fixture types returned by the datasets_fixtures pytest session fixture', 'review the dataset fixtures for Audio, Image, and Pdf feature types and their expected asset URL paths', 'summarize the datasets_fixtures mapping that covers null, bool, int, float, string, array, translation, audio, image, and pdf types', 'create a MockFileSystem instance with a local root directory for testing fsspec operations', 'create a TmpDirFileSystem subclass that uses a temporary directory as the mock root', 'test fsspec code using the mock_fsspec pytest fixture to register mock and tmp protocols', 'test file operations using the mockfs pytest fixture that returns a MockFileSystem with a temp dir', 'test file operations using the tmpfs pytest fixture that patches TmpDirFileSystem with a temp dir']
```

Usage

```
{'create_dataset_fixture_with_value_type': 'create a HuggingFace Dataset fixture from a pandas DataFrame with a specific dtype using the value helper', 'create_dataset_fixture_with_feature_type': 'create a HuggingFace Dataset fixture from a dict with an optional FeatureType using the other helper', 'test_datasets_fixtures_pytest_fixture': 'test all 35+ dataset fixture types returned by the datasets_fixtures pytest session fixture', 'review_dataset_fixture_audio_image_pdf': 'review the dataset fixtures for Audio, Image, and Pdf feature types and their expected asset URL paths', 'summarize_datasets_fixtures_mapping': 'summarize the datasets_fixtures mapping that covers null, bool, int, float, string, array, translation, audio, image, and pdf types'}
```

## File: huggingface_dataset-viewer/libs/libcommon/tests/fixtures/fsspec.py

Prompts

```
['create a HuggingFace Dataset fixture from a pandas DataFrame with a specific dtype using the value helper', 'create a HuggingFace Dataset fixture from a dict with an optional FeatureType using the other helper', 'test all 35+ dataset fixture types returned by the datasets_fixtures pytest session fixture', 'review the dataset fixtures for Audio, Image, and Pdf feature types and their expected asset URL paths', 'summarize the datasets_fixtures mapping that covers null, bool, int, float, string, array, translation, audio, image, and pdf types', 'create a MockFileSystem instance with a local root directory for testing fsspec operations', 'create a TmpDirFileSystem subclass that uses a temporary directory as the mock root', 'test fsspec code using the mock_fsspec pytest fixture to register mock and tmp protocols', 'test file operations using the mockfs pytest fixture that returns a MockFileSystem with a temp dir', 'test file operations using the tmpfs pytest fixture that patches TmpDirFileSystem with a temp dir']
```

Usage

```
{'create_MockFileSystem': 'create a MockFileSystem instance with a local root directory for testing fsspec operations', 'create_TmpDirFileSystem': 'create a TmpDirFileSystem subclass that uses a temporary directory as the mock root', 'test_mock_fsspec_fixture': 'test fsspec code using the mock_fsspec pytest fixture to register mock and tmp protocols', 'test_mockfs_fixture': 'test file operations using the mockfs pytest fixture that returns a MockFileSystem with a temp dir', 'test_tmpfs_fixture': 'test file operations using the tmpfs pytest fixture that patches TmpDirFileSystem with a temp dir'}
```

