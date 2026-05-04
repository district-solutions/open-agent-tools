# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/utils/data/data_utils.py

Prompts

```
['batchify a list or iterable into fixed-size batches with optional drop_last support', 'batchify an iterable into batches and drop the last incomplete batch using drop_last', 'merge a list of dictionaries containing torch tensors into a single stacked dictionary', 'merge_dicts a batch of sample dictionaries to concatenate tensor values by key', 'generate a stable hash integer modulo a given base using md5 and current time', 'create a DummyImageDataset with random images for a specified number of classes and images per class', 'create a DummyImageDataset with multi-channel images by setting num_channels to 3 for RGB data', 'use get_dataset to serialize the DummyImageDataset data and labels into a BytesIO stream', 'use __getitem__ to retrieve a single image tensor and its label by index from the dataset', 'use __len__ to get the total number of images in the DummyImageDataset', 'create a mock FL data provider with a specified number of users and examples per user', 'create a FakeUserData instance with a custom batch generator, number of batches, and batch size', 'create a FakeDataProvider with a batch generator for a given number of users and batches', "iterate over the training data batches yielded by a FakeUserData instance's train_data method", 'get a specific training user by index from a FakeDataProvider using get_train_user']
```

Usage

```
{'batchify_iterable': 'batchify a list or iterable into fixed-size batches with optional drop_last support', 'batchify_drop_last': 'batchify an iterable into batches and drop the last incomplete batch using drop_last', 'merge_dicts_tensors': 'merge a list of dictionaries containing torch tensors into a single stacked dictionary', 'merge_dicts_batch': 'merge_dicts a batch of sample dictionaries to concatenate tensor values by key', 'stable_hash_generate': 'generate a stable hash integer modulo a given base using md5 and current time'}
```

## File: facebookresearch_flsim/flsim/utils/data/dummy_image_dataset.py

Prompts

```
['batchify a list or iterable into fixed-size batches with optional drop_last support', 'batchify an iterable into batches and drop the last incomplete batch using drop_last', 'merge a list of dictionaries containing torch tensors into a single stacked dictionary', 'merge_dicts a batch of sample dictionaries to concatenate tensor values by key', 'generate a stable hash integer modulo a given base using md5 and current time', 'create a DummyImageDataset with random images for a specified number of classes and images per class', 'create a DummyImageDataset with multi-channel images by setting num_channels to 3 for RGB data', 'use get_dataset to serialize the DummyImageDataset data and labels into a BytesIO stream', 'use __getitem__ to retrieve a single image tensor and its label by index from the dataset', 'use __len__ to get the total number of images in the DummyImageDataset', 'create a mock FL data provider with a specified number of users and examples per user', 'create a FakeUserData instance with a custom batch generator, number of batches, and batch size', 'create a FakeDataProvider with a batch generator for a given number of users and batches', "iterate over the training data batches yielded by a FakeUserData instance's train_data method", 'get a specific training user by index from a FakeDataProvider using get_train_user']
```

Usage

```
{'create_DummyImageDataset': 'create a DummyImageDataset with random images for a specified number of classes and images per class', 'create_DummyImageDataset_multichannel': 'create a DummyImageDataset with multi-channel images by setting num_channels to 3 for RGB data', 'use_get_dataset': 'use get_dataset to serialize the DummyImageDataset data and labels into a BytesIO stream', 'use_getitem': 'use __getitem__ to retrieve a single image tensor and its label by index from the dataset', 'use_len': 'use __len__ to get the total number of images in the DummyImageDataset'}
```

## File: facebookresearch_flsim/flsim/utils/data/fake_data_utils.py

Prompts

```
['batchify a list or iterable into fixed-size batches with optional drop_last support', 'batchify an iterable into batches and drop the last incomplete batch using drop_last', 'merge a list of dictionaries containing torch tensors into a single stacked dictionary', 'merge_dicts a batch of sample dictionaries to concatenate tensor values by key', 'generate a stable hash integer modulo a given base using md5 and current time', 'create a DummyImageDataset with random images for a specified number of classes and images per class', 'create a DummyImageDataset with multi-channel images by setting num_channels to 3 for RGB data', 'use get_dataset to serialize the DummyImageDataset data and labels into a BytesIO stream', 'use __getitem__ to retrieve a single image tensor and its label by index from the dataset', 'use __len__ to get the total number of images in the DummyImageDataset', 'create a mock FL data provider with a specified number of users and examples per user', 'create a FakeUserData instance with a custom batch generator, number of batches, and batch size', 'create a FakeDataProvider with a batch generator for a given number of users and batches', "iterate over the training data batches yielded by a FakeUserData instance's train_data method", 'get a specific training user by index from a FakeDataProvider using get_train_user']
```

Usage

```
{'create_mock_data_provider': 'create a mock FL data provider with a specified number of users and examples per user', 'create_fake_user_data': 'create a FakeUserData instance with a custom batch generator, number of batches, and batch size', 'create_fake_data_provider': 'create a FakeDataProvider with a batch generator for a given number of users and batches', 'iterate_fake_user_train_data': "iterate over the training data batches yielded by a FakeUserData instance's train_data method", 'get_train_user_from_provider': 'get a specific training user by index from a FakeDataProvider using get_train_user'}
```

