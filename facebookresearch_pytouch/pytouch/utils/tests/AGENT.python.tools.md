# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/pytouch/utils/tests/common_utils_test.py

Prompts

```
['test the flip function that reverses tensor batch order along the first dimension', 'test the min_clip function that gets maximum values along rows or columns of a tensor', 'test the max_clip function that gets minimum values along rows or columns of a tensor', 'test the normalize function that scales tensor values to a specified range like 0 to 1 or 0 to 255', 'test the pandas_col_to_numpy function that converts a pandas DataFrame column to a numpy array', 'test interpolate_img with a 3x3 tensor keeping the same dimensions', 'test interpolate_img to upscale a 3x3 tensor to a 6x6 tensor', 'test interpolate_img to downscale a 6x6 tensor to a 3x3 tensor', 'test interpolate_img raises RuntimeError when given an empty tensor', 'run the DataUtilsTest unittest suite to validate all interpolate_img test cases', 'test that choose_optimizer returns optim.Adam when given the string Adam', 'test that choose_optimizer returns optim.SGD when given the string SGD', 'test that choose_optimizer raises NotImplementedError for an unrecognized optimizer string', 'run the unittest suite for train_utils choose_optimizer function', 'review the TrainUtilsTest class and its optimizer selection test cases']
```

Usage

```
{'test_flip': 'test the flip function that reverses tensor batch order along the first dimension', 'test_min_clip': 'test the min_clip function that gets maximum values along rows or columns of a tensor', 'test_max_clip': 'test the max_clip function that gets minimum values along rows or columns of a tensor', 'test_normalize': 'test the normalize function that scales tensor values to a specified range like 0 to 1 or 0 to 255', 'test_pandas_col_to_numpy': 'test the pandas_col_to_numpy function that converts a pandas DataFrame column to a numpy array'}
```

## File: facebookresearch_pytouch/pytouch/utils/tests/data_utils_test.py

Prompts

```
['test the flip function that reverses tensor batch order along the first dimension', 'test the min_clip function that gets maximum values along rows or columns of a tensor', 'test the max_clip function that gets minimum values along rows or columns of a tensor', 'test the normalize function that scales tensor values to a specified range like 0 to 1 or 0 to 255', 'test the pandas_col_to_numpy function that converts a pandas DataFrame column to a numpy array', 'test interpolate_img with a 3x3 tensor keeping the same dimensions', 'test interpolate_img to upscale a 3x3 tensor to a 6x6 tensor', 'test interpolate_img to downscale a 6x6 tensor to a 3x3 tensor', 'test interpolate_img raises RuntimeError when given an empty tensor', 'run the DataUtilsTest unittest suite to validate all interpolate_img test cases', 'test that choose_optimizer returns optim.Adam when given the string Adam', 'test that choose_optimizer returns optim.SGD when given the string SGD', 'test that choose_optimizer raises NotImplementedError for an unrecognized optimizer string', 'run the unittest suite for train_utils choose_optimizer function', 'review the TrainUtilsTest class and its optimizer selection test cases']
```

Usage

```
{'test_interpolate_img_same_dimension': 'test interpolate_img with a 3x3 tensor keeping the same dimensions', 'test_interpolate_img_upscale': 'test interpolate_img to upscale a 3x3 tensor to a 6x6 tensor', 'test_interpolate_img_downscale': 'test interpolate_img to downscale a 6x6 tensor to a 3x3 tensor', 'test_interpolate_img_empty': 'test interpolate_img raises RuntimeError when given an empty tensor', 'run_data_utils_test': 'run the DataUtilsTest unittest suite to validate all interpolate_img test cases'}
```

## File: facebookresearch_pytouch/pytouch/utils/tests/train_utils_test.py

Prompts

```
['test the flip function that reverses tensor batch order along the first dimension', 'test the min_clip function that gets maximum values along rows or columns of a tensor', 'test the max_clip function that gets minimum values along rows or columns of a tensor', 'test the normalize function that scales tensor values to a specified range like 0 to 1 or 0 to 255', 'test the pandas_col_to_numpy function that converts a pandas DataFrame column to a numpy array', 'test interpolate_img with a 3x3 tensor keeping the same dimensions', 'test interpolate_img to upscale a 3x3 tensor to a 6x6 tensor', 'test interpolate_img to downscale a 6x6 tensor to a 3x3 tensor', 'test interpolate_img raises RuntimeError when given an empty tensor', 'run the DataUtilsTest unittest suite to validate all interpolate_img test cases', 'test that choose_optimizer returns optim.Adam when given the string Adam', 'test that choose_optimizer returns optim.SGD when given the string SGD', 'test that choose_optimizer raises NotImplementedError for an unrecognized optimizer string', 'run the unittest suite for train_utils choose_optimizer function', 'review the TrainUtilsTest class and its optimizer selection test cases']
```

Usage

```
{'test_choose_optimizer_adam': 'test that choose_optimizer returns optim.Adam when given the string Adam', 'test_choose_optimizer_sgd': 'test that choose_optimizer returns optim.SGD when given the string SGD', 'test_choose_optimizer_invalid': 'test that choose_optimizer raises NotImplementedError for an unrecognized optimizer string', 'run_train_utils_test': 'run the unittest suite for train_utils choose_optimizer function', 'review_trainutils_test': 'review the TrainUtilsTest class and its optimizer selection test cases'}
```

