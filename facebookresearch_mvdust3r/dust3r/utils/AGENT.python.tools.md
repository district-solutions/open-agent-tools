# Agent Python Tools

- repo: facebookresearch/mvdust3r
- repo_uri: https://github.com/facebookresearch/mvdust3r

## File: facebookresearch_mvdust3r/dust3r/utils/device.py

Prompts

```
['transfer a batch of tensors, dicts, or lists to a specified GPU or CPU device', 'convert PyTorch tensors or nested structures containing tensors to NumPy arrays', 'move a batch of tensors or nested data structures to the CUDA device', 'collate a list of tensors or numpy arrays by concatenating them into a single tensor', 'flatten a nested list of elements into a single flat list', 'create a pixel coordinate grid of shape HxWx2 for numpy or torch tensors', 'apply a homography or projection matrix to transform 3D points with optional normalization', 'convert a depth map and pseudo focal length into a 3D pointmap of absolute coordinates', 'normalize two point clouds together using average distance, median, or sqrt normalization modes', 'find reciprocal nearest neighbor matches between two point sets using a KDTree', 'create a python module that uses imread_cv2 to load an image from a file path and convert BGR to RGB', 'create a function that uses rgb to convert a PyTorch tensor to normalized RGB numpy array', 'create a script that uses _resize_pil_image to resize a PIL image to a specified long edge size', 'create a python module that uses load_images to load images from a folder and preprocess them for DUSt3R', 'create a function that uses ImgNorm to convert a PIL image to a normalized PyTorch tensor', 'freeze all parameters in a PyTorch module to prevent gradient updates during training', 'flip alternating rows of a PyTorch tensor so even and odd indices are swapped', 'interleave two PyTorch tensors along the batch dimension and return both orderings', 'wrap a prediction head to handle mixed portrait and landscape image batches automatically', 'replace invalid entries in a PyTorch tensor with NaN values using a validity mask']
```

Usage

```
{'transfer_tensors_to_device': 'transfer a batch of tensors, dicts, or lists to a specified GPU or CPU device', 'convert_tensors_to_numpy': 'convert PyTorch tensors or nested structures containing tensors to NumPy arrays', 'move_batch_to_cuda': 'move a batch of tensors or nested data structures to the CUDA device', 'collate_tensor_lists': 'collate a list of tensors or numpy arrays by concatenating them into a single tensor', 'flatten_nested_lists': 'flatten a nested list of elements into a single flat list'}
```

## File: facebookresearch_mvdust3r/dust3r/utils/geometry.py

Prompts

```
['transfer a batch of tensors, dicts, or lists to a specified GPU or CPU device', 'convert PyTorch tensors or nested structures containing tensors to NumPy arrays', 'move a batch of tensors or nested data structures to the CUDA device', 'collate a list of tensors or numpy arrays by concatenating them into a single tensor', 'flatten a nested list of elements into a single flat list', 'create a pixel coordinate grid of shape HxWx2 for numpy or torch tensors', 'apply a homography or projection matrix to transform 3D points with optional normalization', 'convert a depth map and pseudo focal length into a 3D pointmap of absolute coordinates', 'normalize two point clouds together using average distance, median, or sqrt normalization modes', 'find reciprocal nearest neighbor matches between two point sets using a KDTree', 'create a python module that uses imread_cv2 to load an image from a file path and convert BGR to RGB', 'create a function that uses rgb to convert a PyTorch tensor to normalized RGB numpy array', 'create a script that uses _resize_pil_image to resize a PIL image to a specified long edge size', 'create a python module that uses load_images to load images from a folder and preprocess them for DUSt3R', 'create a function that uses ImgNorm to convert a PIL image to a normalized PyTorch tensor', 'freeze all parameters in a PyTorch module to prevent gradient updates during training', 'flip alternating rows of a PyTorch tensor so even and odd indices are swapped', 'interleave two PyTorch tensors along the batch dimension and return both orderings', 'wrap a prediction head to handle mixed portrait and landscape image batches automatically', 'replace invalid entries in a PyTorch tensor with NaN values using a validity mask']
```

Usage

```
{'create_xy_grid': 'create a pixel coordinate grid of shape HxWx2 for numpy or torch tensors', 'apply_geometric_transform': 'apply a homography or projection matrix to transform 3D points with optional normalization', 'convert_depthmap_to_pts3d': 'convert a depth map and pseudo focal length into a 3D pointmap of absolute coordinates', 'normalize_pointcloud': 'normalize two point clouds together using average distance, median, or sqrt normalization modes', 'find_reciprocal_matches': 'find reciprocal nearest neighbor matches between two point sets using a KDTree'}
```

## File: facebookresearch_mvdust3r/dust3r/utils/image.py

Prompts

```
['transfer a batch of tensors, dicts, or lists to a specified GPU or CPU device', 'convert PyTorch tensors or nested structures containing tensors to NumPy arrays', 'move a batch of tensors or nested data structures to the CUDA device', 'collate a list of tensors or numpy arrays by concatenating them into a single tensor', 'flatten a nested list of elements into a single flat list', 'create a pixel coordinate grid of shape HxWx2 for numpy or torch tensors', 'apply a homography or projection matrix to transform 3D points with optional normalization', 'convert a depth map and pseudo focal length into a 3D pointmap of absolute coordinates', 'normalize two point clouds together using average distance, median, or sqrt normalization modes', 'find reciprocal nearest neighbor matches between two point sets using a KDTree', 'create a python module that uses imread_cv2 to load an image from a file path and convert BGR to RGB', 'create a function that uses rgb to convert a PyTorch tensor to normalized RGB numpy array', 'create a script that uses _resize_pil_image to resize a PIL image to a specified long edge size', 'create a python module that uses load_images to load images from a folder and preprocess them for DUSt3R', 'create a function that uses ImgNorm to convert a PIL image to a normalized PyTorch tensor', 'freeze all parameters in a PyTorch module to prevent gradient updates during training', 'flip alternating rows of a PyTorch tensor so even and odd indices are swapped', 'interleave two PyTorch tensors along the batch dimension and return both orderings', 'wrap a prediction head to handle mixed portrait and landscape image batches automatically', 'replace invalid entries in a PyTorch tensor with NaN values using a validity mask']
```

Usage

```
{'load_image_with_cv2': 'create a python module that uses imread_cv2 to load an image from a file path and convert BGR to RGB', 'convert_tensor_to_rgb': 'create a function that uses rgb to convert a PyTorch tensor to normalized RGB numpy array', 'resize_pil_image': 'create a script that uses _resize_pil_image to resize a PIL image to a specified long edge size', 'load_and_preprocess_images': 'create a python module that uses load_images to load images from a folder and preprocess them for DUSt3R', 'normalize_image_tensor': 'create a function that uses ImgNorm to convert a PIL image to a normalized PyTorch tensor'}
```

## File: facebookresearch_mvdust3r/dust3r/utils/misc.py

Prompts

```
['transfer a batch of tensors, dicts, or lists to a specified GPU or CPU device', 'convert PyTorch tensors or nested structures containing tensors to NumPy arrays', 'move a batch of tensors or nested data structures to the CUDA device', 'collate a list of tensors or numpy arrays by concatenating them into a single tensor', 'flatten a nested list of elements into a single flat list', 'create a pixel coordinate grid of shape HxWx2 for numpy or torch tensors', 'apply a homography or projection matrix to transform 3D points with optional normalization', 'convert a depth map and pseudo focal length into a 3D pointmap of absolute coordinates', 'normalize two point clouds together using average distance, median, or sqrt normalization modes', 'find reciprocal nearest neighbor matches between two point sets using a KDTree', 'create a python module that uses imread_cv2 to load an image from a file path and convert BGR to RGB', 'create a function that uses rgb to convert a PyTorch tensor to normalized RGB numpy array', 'create a script that uses _resize_pil_image to resize a PIL image to a specified long edge size', 'create a python module that uses load_images to load images from a folder and preprocess them for DUSt3R', 'create a function that uses ImgNorm to convert a PIL image to a normalized PyTorch tensor', 'freeze all parameters in a PyTorch module to prevent gradient updates during training', 'flip alternating rows of a PyTorch tensor so even and odd indices are swapped', 'interleave two PyTorch tensors along the batch dimension and return both orderings', 'wrap a prediction head to handle mixed portrait and landscape image batches automatically', 'replace invalid entries in a PyTorch tensor with NaN values using a validity mask']
```

Usage

```
{'freeze_model_parameters': 'freeze all parameters in a PyTorch module to prevent gradient updates during training', 'flip_tensor_pairs': 'flip alternating rows of a PyTorch tensor so even and odd indices are swapped', 'interleave_two_tensors': 'interleave two PyTorch tensors along the batch dimension and return both orderings', 'transpose_head_to_landscape': 'wrap a prediction head to handle mixed portrait and landscape image batches automatically', 'mask_invalid_to_nans': 'replace invalid entries in a PyTorch tensor with NaN values using a validity mask'}
```

