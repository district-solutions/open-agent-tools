# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/examples/video_classification/utils/dataset.py

Prompts

```
['create a LocalVideoDataset from a local directory of videos organized by class and split', 'create a LocalVideoDataset instance from argparse arguments with data_dir and split', 'get a label-to-index mapping derived from the directory structure of video classes', 'add dataset command-line arguments for data_dir and split to an argparse parser', 'review the LocalVideoDataset __getitem__ method that reads video bytes and returns label', 'build a multithreaded SPDL pipeline with GPU NVDEC video decoding for video classification', 'create a Demux callable that demuxes video bytes into packets and resolves labels to class indices', 'create an NvdecDecode callable that decodes video packets using GPU NVDEC hardware decoder with frame sampling', 'collate a list of video and label tensors into a batched dictionary with stacked tensors', 'review the build_pipeline function that assembles a split demux/decode SPDL pipeline with distributed sampling']
```

Usage

```
{'create_LocalVideoDataset': 'create a LocalVideoDataset from a local directory of videos organized by class and split', 'create_dataset': 'create a LocalVideoDataset instance from argparse arguments with data_dir and split', 'get_label_to_index': 'get a label-to-index mapping derived from the directory structure of video classes', 'add_dataset_args': 'add dataset command-line arguments for data_dir and split to an argparse parser', 'review_LocalVideoDataset_getitem': 'review the LocalVideoDataset __getitem__ method that reads video bytes and returns label'}
```

## File: facebookresearch_spdl/examples/video_classification/utils/pipeline.py

Prompts

```
['create a LocalVideoDataset from a local directory of videos organized by class and split', 'create a LocalVideoDataset instance from argparse arguments with data_dir and split', 'get a label-to-index mapping derived from the directory structure of video classes', 'add dataset command-line arguments for data_dir and split to an argparse parser', 'review the LocalVideoDataset __getitem__ method that reads video bytes and returns label', 'build a multithreaded SPDL pipeline with GPU NVDEC video decoding for video classification', 'create a Demux callable that demuxes video bytes into packets and resolves labels to class indices', 'create an NvdecDecode callable that decodes video packets using GPU NVDEC hardware decoder with frame sampling', 'collate a list of video and label tensors into a batched dictionary with stacked tensors', 'review the build_pipeline function that assembles a split demux/decode SPDL pipeline with distributed sampling']
```

Usage

```
{'build_pipeline': 'build a multithreaded SPDL pipeline with GPU NVDEC video decoding for video classification', 'create_demux': 'create a Demux callable that demuxes video bytes into packets and resolves labels to class indices', 'create_nvdec_decode': 'create an NvdecDecode callable that decodes video packets using GPU NVDEC hardware decoder with frame sampling', 'collate_batch': 'collate a list of video and label tensors into a batched dictionary with stacked tensors', 'review_build_pipeline': 'review the build_pipeline function that assembles a split demux/decode SPDL pipeline with distributed sampling'}
```

