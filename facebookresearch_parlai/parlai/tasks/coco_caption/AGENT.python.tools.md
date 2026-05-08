# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/coco_caption/agents.py

Prompts

```
['run the DefaultTeacher to load and serve MSCOCO image captioning examples for training or evaluation', 'create a V2014Teacher instance to load MSCOCO 2014 image captioning data with Karpathy splits', 'create a V2017Teacher instance to load MSCOCO 2017 image captioning data with official splits', 'review the load_candidates function that loads caption candidates from COCO annotation JSON files', 'test the DefaultTeacher next_example method to verify async image loading and example retrieval', 'build the COCO 2014 caption dataset by downloading and extracting dataset_coco.tgz to the data path', 'build the COCO 2014 image dataset by downloading train, val, and test 2014 zip files', 'check if the COCO 2014 caption or image data has already been built using build_data.built', 'remove an older version of the COCO 2014 data directory using build_data.remove_dir', 'mark the COCO 2014 caption or image data as built using build_data.mark_done', 'build the COCO 2015 caption annotation data by downloading image_info_test2015.zip to the datapath directory', 'build the COCO 2015 image data by downloading test2015.zip to the COCO-IMG-2015 directory', 'review the build function that downloads and marks COCO 2015 caption data as done', 'review the buildImage function that downloads and marks COCO 2015 image data as done', 'summarize the RESOURCES list containing DownloadableFile entries for test2015.zip and image_info_test2015.zip', 'build the COCO 2017 caption annotation dataset by downloading and extracting annotation files', 'build the COCO 2017 image dataset by downloading train, val, and test image archives', 'download COCO 2017 dataset resources including images and annotations using predefined DownloadableFile entries', 'refactor the build function to support versioned downloads of COCO 2017 caption annotations']
```

Usage

```
{'run_coco_caption_teacher': 'run the DefaultTeacher to load and serve MSCOCO image captioning examples for training or evaluation', 'create_v2014_teacher': 'create a V2014Teacher instance to load MSCOCO 2014 image captioning data with Karpathy splits', 'create_v2017_teacher': 'create a V2017Teacher instance to load MSCOCO 2017 image captioning data with official splits', 'review_load_candidates': 'review the load_candidates function that loads caption candidates from COCO annotation JSON files', 'test_next_example': 'test the DefaultTeacher next_example method to verify async image loading and example retrieval'}
```

## File: facebookresearch_parlai/parlai/tasks/coco_caption/build_2014.py

Prompts

```
['run the DefaultTeacher to load and serve MSCOCO image captioning examples for training or evaluation', 'create a V2014Teacher instance to load MSCOCO 2014 image captioning data with Karpathy splits', 'create a V2017Teacher instance to load MSCOCO 2017 image captioning data with official splits', 'review the load_candidates function that loads caption candidates from COCO annotation JSON files', 'test the DefaultTeacher next_example method to verify async image loading and example retrieval', 'build the COCO 2014 caption dataset by downloading and extracting dataset_coco.tgz to the data path', 'build the COCO 2014 image dataset by downloading train, val, and test 2014 zip files', 'check if the COCO 2014 caption or image data has already been built using build_data.built', 'remove an older version of the COCO 2014 data directory using build_data.remove_dir', 'mark the COCO 2014 caption or image data as built using build_data.mark_done', 'build the COCO 2015 caption annotation data by downloading image_info_test2015.zip to the datapath directory', 'build the COCO 2015 image data by downloading test2015.zip to the COCO-IMG-2015 directory', 'review the build function that downloads and marks COCO 2015 caption data as done', 'review the buildImage function that downloads and marks COCO 2015 image data as done', 'summarize the RESOURCES list containing DownloadableFile entries for test2015.zip and image_info_test2015.zip', 'build the COCO 2017 caption annotation dataset by downloading and extracting annotation files', 'build the COCO 2017 image dataset by downloading train, val, and test image archives', 'download COCO 2017 dataset resources including images and annotations using predefined DownloadableFile entries', 'refactor the build function to support versioned downloads of COCO 2017 caption annotations']
```

Usage

```
{'build_coco_caption_data': 'build the COCO 2014 caption dataset by downloading and extracting dataset_coco.tgz to the data path', 'build_coco_images': 'build the COCO 2014 image dataset by downloading train, val, and test 2014 zip files', 'check_data_built': 'check if the COCO 2014 caption or image data has already been built using build_data.built', 'remove_outdated_data': 'remove an older version of the COCO 2014 data directory using build_data.remove_dir', 'mark_data_done': 'mark the COCO 2014 caption or image data as built using build_data.mark_done'}
```

## File: facebookresearch_parlai/parlai/tasks/coco_caption/build_2015.py

Prompts

```
['run the DefaultTeacher to load and serve MSCOCO image captioning examples for training or evaluation', 'create a V2014Teacher instance to load MSCOCO 2014 image captioning data with Karpathy splits', 'create a V2017Teacher instance to load MSCOCO 2017 image captioning data with official splits', 'review the load_candidates function that loads caption candidates from COCO annotation JSON files', 'test the DefaultTeacher next_example method to verify async image loading and example retrieval', 'build the COCO 2014 caption dataset by downloading and extracting dataset_coco.tgz to the data path', 'build the COCO 2014 image dataset by downloading train, val, and test 2014 zip files', 'check if the COCO 2014 caption or image data has already been built using build_data.built', 'remove an older version of the COCO 2014 data directory using build_data.remove_dir', 'mark the COCO 2014 caption or image data as built using build_data.mark_done', 'build the COCO 2015 caption annotation data by downloading image_info_test2015.zip to the datapath directory', 'build the COCO 2015 image data by downloading test2015.zip to the COCO-IMG-2015 directory', 'review the build function that downloads and marks COCO 2015 caption data as done', 'review the buildImage function that downloads and marks COCO 2015 image data as done', 'summarize the RESOURCES list containing DownloadableFile entries for test2015.zip and image_info_test2015.zip', 'build the COCO 2017 caption annotation dataset by downloading and extracting annotation files', 'build the COCO 2017 image dataset by downloading train, val, and test image archives', 'download COCO 2017 dataset resources including images and annotations using predefined DownloadableFile entries', 'refactor the build function to support versioned downloads of COCO 2017 caption annotations']
```

Usage

```
{'build_coco_2015_caption_data': 'build the COCO 2015 caption annotation data by downloading image_info_test2015.zip to the datapath directory', 'build_coco_2015_image_data': 'build the COCO 2015 image data by downloading test2015.zip to the COCO-IMG-2015 directory', 'review_build_function': 'review the build function that downloads and marks COCO 2015 caption data as done', 'review_buildImage_function': 'review the buildImage function that downloads and marks COCO 2015 image data as done', 'summarize_resources_list': 'summarize the RESOURCES list containing DownloadableFile entries for test2015.zip and image_info_test2015.zip'}
```

## File: facebookresearch_parlai/parlai/tasks/coco_caption/build_2017.py

Prompts

```
['run the DefaultTeacher to load and serve MSCOCO image captioning examples for training or evaluation', 'create a V2014Teacher instance to load MSCOCO 2014 image captioning data with Karpathy splits', 'create a V2017Teacher instance to load MSCOCO 2017 image captioning data with official splits', 'review the load_candidates function that loads caption candidates from COCO annotation JSON files', 'test the DefaultTeacher next_example method to verify async image loading and example retrieval', 'build the COCO 2014 caption dataset by downloading and extracting dataset_coco.tgz to the data path', 'build the COCO 2014 image dataset by downloading train, val, and test 2014 zip files', 'check if the COCO 2014 caption or image data has already been built using build_data.built', 'remove an older version of the COCO 2014 data directory using build_data.remove_dir', 'mark the COCO 2014 caption or image data as built using build_data.mark_done', 'build the COCO 2015 caption annotation data by downloading image_info_test2015.zip to the datapath directory', 'build the COCO 2015 image data by downloading test2015.zip to the COCO-IMG-2015 directory', 'review the build function that downloads and marks COCO 2015 caption data as done', 'review the buildImage function that downloads and marks COCO 2015 image data as done', 'summarize the RESOURCES list containing DownloadableFile entries for test2015.zip and image_info_test2015.zip', 'build the COCO 2017 caption annotation dataset by downloading and extracting annotation files', 'build the COCO 2017 image dataset by downloading train, val, and test image archives', 'download COCO 2017 dataset resources including images and annotations using predefined DownloadableFile entries', 'refactor the build function to support versioned downloads of COCO 2017 caption annotations']
```

Usage

```
{'build_coco_2017_caption_data': 'build the COCO 2017 caption annotation dataset by downloading and extracting annotation files', 'build_coco_2017_images': 'build the COCO 2017 image dataset by downloading train, val, and test image archives', 'download_coco_resources': 'download COCO 2017 dataset resources including images and annotations using predefined DownloadableFile entries', 'review_buildImage_function': 'review the buildImage function that downloads COCO 2017 image data to the specified datapath', 'refactor_build_function': 'refactor the build function to support versioned downloads of COCO 2017 caption annotations'}
```

