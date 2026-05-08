# Agent Python Tools

- repo: facebookresearch/pytouch
- repo_uri: https://github.com/facebookresearch/pytouch

## File: facebookresearch_pytouch/pytouch/utils/common_utils.py

Prompts

```
['flip a PyTorch tensor along axis 0 to reverse its order', 'clip a PyTorch tensor values to a minimum threshold using torch.max', 'clip a PyTorch tensor values to a maximum threshold using torch.min', 'normalize a PyTorch tensor to an arbitrary range using min-max normalization', 'convert a pandas DataFrame column of string arrays into a stacked numpy array', 'interpolate a PyTorch tensor image to new row and column dimensions using bilinear interpolation', 'test the interpolate_img function by resizing a sample tensor to specified rows and columns', 'refactor interpolate_img to support batched tensor inputs with shape B x C x H x W', 'review the interpolate_img function for correct permute operations during row and column interpolation', 'summarize the interpolate_img function that resizes a C x H x W tensor to target rows and columns', 'set a random seed for python, numpy, and torch reproducibility', 'print the size and number of classes of a PyTorch dataset', 'freeze all model weights except those in the final fully connected layer', 'extract and clean a state dict from a PyTorch-Lightning checkpoint file', 'choose whether to use the last fully connected layer for score or feature mode', 'choose the Adam optimizer class by name for PyTorch training', 'choose the SGD optimizer class by name for PyTorch training', 'test the choose_optimizer function with Adam and SGD optimizer names', 'refactor choose_optimizer to support additional PyTorch optimizers like Adagrad or RMSprop', 'review the choose_optimizer function and its optimizer selection logic', 'convert an optical flow UV tensor into a color-coded HSV image using OpenCV', 'overlay green arrows on an image to visualize optical flow direction and magnitude', 'normalize a depth map and convert it to a grayscale BGR image for display', 'draw a rotated rectangle patch on the current matplotlib axes at a given center and angle', 'display a list of images on matplotlib subplots with optional titles and colorbars']
```

Usage

```
{'flip_tensor_along_axis': 'flip a PyTorch tensor along axis 0 to reverse its order', 'min_clip_tensor': 'clip a PyTorch tensor values to a minimum threshold using torch.max', 'max_clip_tensor': 'clip a PyTorch tensor values to a maximum threshold using torch.min', 'normalize_tensor_min_max': 'normalize a PyTorch tensor to an arbitrary range using min-max normalization', 'convert_pandas_col_to_numpy': 'convert a pandas DataFrame column of string arrays into a stacked numpy array'}
```

## File: facebookresearch_pytouch/pytouch/utils/data_utils.py

Prompts

```
['flip a PyTorch tensor along axis 0 to reverse its order', 'clip a PyTorch tensor values to a minimum threshold using torch.max', 'clip a PyTorch tensor values to a maximum threshold using torch.min', 'normalize a PyTorch tensor to an arbitrary range using min-max normalization', 'convert a pandas DataFrame column of string arrays into a stacked numpy array', 'interpolate a PyTorch tensor image to new row and column dimensions using bilinear interpolation', 'test the interpolate_img function by resizing a sample tensor to specified rows and columns', 'refactor interpolate_img to support batched tensor inputs with shape B x C x H x W', 'review the interpolate_img function for correct permute operations during row and column interpolation', 'summarize the interpolate_img function that resizes a C x H x W tensor to target rows and columns', 'set a random seed for python, numpy, and torch reproducibility', 'print the size and number of classes of a PyTorch dataset', 'freeze all model weights except those in the final fully connected layer', 'extract and clean a state dict from a PyTorch-Lightning checkpoint file', 'choose whether to use the last fully connected layer for score or feature mode', 'choose the Adam optimizer class by name for PyTorch training', 'choose the SGD optimizer class by name for PyTorch training', 'test the choose_optimizer function with Adam and SGD optimizer names', 'refactor choose_optimizer to support additional PyTorch optimizers like Adagrad or RMSprop', 'review the choose_optimizer function and its optimizer selection logic', 'convert an optical flow UV tensor into a color-coded HSV image using OpenCV', 'overlay green arrows on an image to visualize optical flow direction and magnitude', 'normalize a depth map and convert it to a grayscale BGR image for display', 'draw a rotated rectangle patch on the current matplotlib axes at a given center and angle', 'display a list of images on matplotlib subplots with optional titles and colorbars']
```

Usage

```
{'interpolate_img': 'interpolate a PyTorch tensor image to new row and column dimensions using bilinear interpolation', 'test_interpolate_img': 'test the interpolate_img function by resizing a sample tensor to specified rows and columns', 'refactor_interpolate_img': 'refactor interpolate_img to support batched tensor inputs with shape B x C x H x W', 'review_interpolate_img': 'review the interpolate_img function for correct permute operations during row and column interpolation', 'summarize_interpolate_img': 'summarize the interpolate_img function that resizes a C x H x W tensor to target rows and columns'}
```

## File: facebookresearch_pytouch/pytouch/utils/model_utils.py

Prompts

```
['flip a PyTorch tensor along axis 0 to reverse its order', 'clip a PyTorch tensor values to a minimum threshold using torch.max', 'clip a PyTorch tensor values to a maximum threshold using torch.min', 'normalize a PyTorch tensor to an arbitrary range using min-max normalization', 'convert a pandas DataFrame column of string arrays into a stacked numpy array', 'interpolate a PyTorch tensor image to new row and column dimensions using bilinear interpolation', 'test the interpolate_img function by resizing a sample tensor to specified rows and columns', 'refactor interpolate_img to support batched tensor inputs with shape B x C x H x W', 'review the interpolate_img function for correct permute operations during row and column interpolation', 'summarize the interpolate_img function that resizes a C x H x W tensor to target rows and columns', 'set a random seed for python, numpy, and torch reproducibility', 'print the size and number of classes of a PyTorch dataset', 'freeze all model weights except those in the final fully connected layer', 'extract and clean a state dict from a PyTorch-Lightning checkpoint file', 'choose whether to use the last fully connected layer for score or feature mode', 'choose the Adam optimizer class by name for PyTorch training', 'choose the SGD optimizer class by name for PyTorch training', 'test the choose_optimizer function with Adam and SGD optimizer names', 'refactor choose_optimizer to support additional PyTorch optimizers like Adagrad or RMSprop', 'review the choose_optimizer function and its optimizer selection logic', 'convert an optical flow UV tensor into a color-coded HSV image using OpenCV', 'overlay green arrows on an image to visualize optical flow direction and magnitude', 'normalize a depth map and convert it to a grayscale BGR image for display', 'draw a rotated rectangle patch on the current matplotlib axes at a given center and angle', 'display a list of images on matplotlib subplots with optional titles and colorbars']
```

Usage

```
{'set_seed': 'set a random seed for python, numpy, and torch reproducibility', 'print_dataset_info': 'print the size and number of classes of a PyTorch dataset', 'freeze_weights': 'freeze all model weights except those in the final fully connected layer', 'convert_state_dict_if_from_pl': 'extract and clean a state dict from a PyTorch-Lightning checkpoint file', 'choose_last_fc_mode': 'choose whether to use the last fully connected layer for score or feature mode'}
```

## File: facebookresearch_pytouch/pytouch/utils/train_utils.py

Prompts

```
['flip a PyTorch tensor along axis 0 to reverse its order', 'clip a PyTorch tensor values to a minimum threshold using torch.max', 'clip a PyTorch tensor values to a maximum threshold using torch.min', 'normalize a PyTorch tensor to an arbitrary range using min-max normalization', 'convert a pandas DataFrame column of string arrays into a stacked numpy array', 'interpolate a PyTorch tensor image to new row and column dimensions using bilinear interpolation', 'test the interpolate_img function by resizing a sample tensor to specified rows and columns', 'refactor interpolate_img to support batched tensor inputs with shape B x C x H x W', 'review the interpolate_img function for correct permute operations during row and column interpolation', 'summarize the interpolate_img function that resizes a C x H x W tensor to target rows and columns', 'set a random seed for python, numpy, and torch reproducibility', 'print the size and number of classes of a PyTorch dataset', 'freeze all model weights except those in the final fully connected layer', 'extract and clean a state dict from a PyTorch-Lightning checkpoint file', 'choose whether to use the last fully connected layer for score or feature mode', 'choose the Adam optimizer class by name for PyTorch training', 'choose the SGD optimizer class by name for PyTorch training', 'test the choose_optimizer function with Adam and SGD optimizer names', 'refactor choose_optimizer to support additional PyTorch optimizers like Adagrad or RMSprop', 'review the choose_optimizer function and its optimizer selection logic', 'convert an optical flow UV tensor into a color-coded HSV image using OpenCV', 'overlay green arrows on an image to visualize optical flow direction and magnitude', 'normalize a depth map and convert it to a grayscale BGR image for display', 'draw a rotated rectangle patch on the current matplotlib axes at a given center and angle', 'display a list of images on matplotlib subplots with optional titles and colorbars']
```

Usage

```
{'choose_optimizer_Adam': 'choose the Adam optimizer class by name for PyTorch training', 'choose_optimizer_SGD': 'choose the SGD optimizer class by name for PyTorch training', 'test_choose_optimizer': 'test the choose_optimizer function with Adam and SGD optimizer names', 'refactor_choose_optimizer': 'refactor choose_optimizer to support additional PyTorch optimizers like Adagrad or RMSprop', 'review_choose_optimizer': 'review the choose_optimizer function and its optimizer selection logic'}
```

## File: facebookresearch_pytouch/pytouch/utils/vis_utils.py

Prompts

```
['flip a PyTorch tensor along axis 0 to reverse its order', 'clip a PyTorch tensor values to a minimum threshold using torch.max', 'clip a PyTorch tensor values to a maximum threshold using torch.min', 'normalize a PyTorch tensor to an arbitrary range using min-max normalization', 'convert a pandas DataFrame column of string arrays into a stacked numpy array', 'interpolate a PyTorch tensor image to new row and column dimensions using bilinear interpolation', 'test the interpolate_img function by resizing a sample tensor to specified rows and columns', 'refactor interpolate_img to support batched tensor inputs with shape B x C x H x W', 'review the interpolate_img function for correct permute operations during row and column interpolation', 'summarize the interpolate_img function that resizes a C x H x W tensor to target rows and columns', 'set a random seed for python, numpy, and torch reproducibility', 'print the size and number of classes of a PyTorch dataset', 'freeze all model weights except those in the final fully connected layer', 'extract and clean a state dict from a PyTorch-Lightning checkpoint file', 'choose whether to use the last fully connected layer for score or feature mode', 'choose the Adam optimizer class by name for PyTorch training', 'choose the SGD optimizer class by name for PyTorch training', 'test the choose_optimizer function with Adam and SGD optimizer names', 'refactor choose_optimizer to support additional PyTorch optimizers like Adagrad or RMSprop', 'review the choose_optimizer function and its optimizer selection logic', 'convert an optical flow UV tensor into a color-coded HSV image using OpenCV', 'overlay green arrows on an image to visualize optical flow direction and magnitude', 'normalize a depth map and convert it to a grayscale BGR image for display', 'draw a rotated rectangle patch on the current matplotlib axes at a given center and angle', 'display a list of images on matplotlib subplots with optional titles and colorbars']
```

Usage

```
{'convert_flow_to_color': 'convert an optical flow UV tensor into a color-coded HSV image using OpenCV', 'draw_flow_arrows': 'overlay green arrows on an image to visualize optical flow direction and magnitude', 'convert_depth_to_color': 'normalize a depth map and convert it to a grayscale BGR image for display', 'draw_rotated_rectangle': 'draw a rotated rectangle patch on the current matplotlib axes at a given center and angle', 'visualize_images_with_colormap': 'display a list of images on matplotlib subplots with optional titles and colorbars'}
```

