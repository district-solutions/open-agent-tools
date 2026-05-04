# Agent Python Tools

- repo: facebookresearch/ava-256
- repo_uri: https://github.com/facebookresearch/ava-256

## File: facebookresearch_ava-256/data/ava_dataset.py

Prompts

```
['create a MultiCaptureDataset from a list of MugsyCapture identifiers and directory paths', 'create a SingleCaptureDataset for one Mugsy capture with optional camera filtering', 'use none_collate_fn as a DataLoader collate function to filter None samples from batches', 'get cross-capture texture normalization mean and standard deviation from a MultiCaptureDataset', 'fetch camera image, mesh vertices, average texture, and head pose for a frame and camera', 'create a MugsyCapture instance with date, time, and subject ID to get a formatted folder name', 'use the MugsyCapture folder_name method to generate a capture directory path string', 'load a framelist CSV and neutral texture and vertex arrays from zipped dataset files', 'use getitem to look up a segment, frame, and camera by index from a framelist and camera list', 'review the MugsyCapture class and its folder_name method for Mugsy capture identifier handling']
```

Usage

```
{'create_MultiCaptureDataset': 'create a MultiCaptureDataset from a list of MugsyCapture identifiers and directory paths', 'create_SingleCaptureDataset': 'create a SingleCaptureDataset for one Mugsy capture with optional camera filtering', 'use_none_collate_fn': 'use none_collate_fn as a DataLoader collate function to filter None samples from batches', 'get_texture_norm_stats': 'get cross-capture texture normalization mean and standard deviation from a MultiCaptureDataset', 'fetch_data_from_disk': 'fetch camera image, mesh vertices, average texture, and head pose for a frame and camera'}
```

## File: facebookresearch_ava-256/data/utils.py

Prompts

```
['create a MultiCaptureDataset from a list of MugsyCapture identifiers and directory paths', 'create a SingleCaptureDataset for one Mugsy capture with optional camera filtering', 'use none_collate_fn as a DataLoader collate function to filter None samples from batches', 'get cross-capture texture normalization mean and standard deviation from a MultiCaptureDataset', 'fetch camera image, mesh vertices, average texture, and head pose for a frame and camera', 'create a MugsyCapture instance with date, time, and subject ID to get a formatted folder name', 'use the MugsyCapture folder_name method to generate a capture directory path string', 'load a framelist CSV and neutral texture and vertex arrays from zipped dataset files', 'use getitem to look up a segment, frame, and camera by index from a framelist and camera list', 'review the MugsyCapture class and its folder_name method for Mugsy capture identifier handling']
```

Usage

```
{'create_MugsyCapture': 'create a MugsyCapture instance with date, time, and subject ID to get a formatted folder name', 'use_MugsyCapture_folder_name': 'use the MugsyCapture folder_name method to generate a capture directory path string', 'load_get_framelist_neuttex_and_neutvert': 'load a framelist CSV and neutral texture and vertex arrays from zipped dataset files', 'use_getitem': 'use getitem to look up a segment, frame, and camera by index from a framelist and camera list', 'review_MugsyCapture_class': 'review the MugsyCapture class and its folder_name method for Mugsy capture identifier handling'}
```

