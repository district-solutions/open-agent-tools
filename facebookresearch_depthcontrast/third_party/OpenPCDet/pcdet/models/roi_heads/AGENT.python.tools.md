# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/roi_heads/partA2_head.py

Prompts

```
['build a PartA2FCHead ROI head network for 3D object detection using sparse convolutions and RoI-aware pooling', 'create a sparse convolution block with batch norm and ReLU for submanifold, sparse, or inverse conv types', 'run RoI-aware 3D pooling on point cloud features using average pooling for parts and max pooling for RPN features', 'test the PartA2FCHead weight initialization with xavier, kaiming, or normal strategies for conv layers', 'review the PartA2FCHead forward pass that performs RoI pooling, sparse conv, and classification/regression prediction', 'build a PointRCNNHead ROI head for 3D object detection using input channels and model config', 'initialize PointRCNNHead convolutional and regression layer weights using xavier, kaiming, or normal initialization', 'pool 3D point cloud features into ROI regions using GPU-accelerated RoI point pooling with canonical transformation', 'run the PointRCNNHead forward pass to produce classification and regression predictions from batched ROI features', 'review the PointRCNNHead set abstraction modules configuration for radius, sampling, and MLP channel design', 'build a PVRCNNHead ROI head model with input channels and model config for 3D object detection', 'run the PVRCNNHead forward pass to generate RoI classification and regression predictions from batch dict', 'create RoI grid pooled features by pooling point cloud features onto a 3D grid for each RoI', 'review the PVRCNNHead init_weights method to initialize convolutional layers with xavier, kaiming, or normal initialization', 'test the get_dense_grid_points static method to generate dense 3D grid points inside RoI bounding boxes', 'build a RoIHeadTemplate instance with num_class and model_cfg for 3D object detection ROI refinement', 'create fully connected layers with Conv1d, BatchNorm1d, and ReLU for ROI head feature processing', 'run the proposal layer to perform NMS on batch box predictions and extract ROI regions', 'review the assign_targets method that performs canonical transformation and coordinate rotation for ROI targets', 'test the get_loss method to compute combined classification and regression loss for RCNN training']
```

Usage

```
{'build_PartA2FCHead': 'build a PartA2FCHead ROI head network for 3D object detection using sparse convolutions and RoI-aware pooling', 'create_post_act_block': 'create a sparse convolution block with batch norm and ReLU for submanifold, sparse, or inverse conv types', 'run_roiaware_pool': 'run RoI-aware 3D pooling on point cloud features using average pooling for parts and max pooling for RPN features', 'test_init_weights': 'test the PartA2FCHead weight initialization with xavier, kaiming, or normal strategies for conv layers', 'review_forward': 'review the PartA2FCHead forward pass that performs RoI pooling, sparse conv, and classification/regression prediction'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/roi_heads/pointrcnn_head.py

Prompts

```
['build a PartA2FCHead ROI head network for 3D object detection using sparse convolutions and RoI-aware pooling', 'create a sparse convolution block with batch norm and ReLU for submanifold, sparse, or inverse conv types', 'run RoI-aware 3D pooling on point cloud features using average pooling for parts and max pooling for RPN features', 'test the PartA2FCHead weight initialization with xavier, kaiming, or normal strategies for conv layers', 'review the PartA2FCHead forward pass that performs RoI pooling, sparse conv, and classification/regression prediction', 'build a PointRCNNHead ROI head for 3D object detection using input channels and model config', 'initialize PointRCNNHead convolutional and regression layer weights using xavier, kaiming, or normal initialization', 'pool 3D point cloud features into ROI regions using GPU-accelerated RoI point pooling with canonical transformation', 'run the PointRCNNHead forward pass to produce classification and regression predictions from batched ROI features', 'review the PointRCNNHead set abstraction modules configuration for radius, sampling, and MLP channel design', 'build a PVRCNNHead ROI head model with input channels and model config for 3D object detection', 'run the PVRCNNHead forward pass to generate RoI classification and regression predictions from batch dict', 'create RoI grid pooled features by pooling point cloud features onto a 3D grid for each RoI', 'review the PVRCNNHead init_weights method to initialize convolutional layers with xavier, kaiming, or normal initialization', 'test the get_dense_grid_points static method to generate dense 3D grid points inside RoI bounding boxes', 'build a RoIHeadTemplate instance with num_class and model_cfg for 3D object detection ROI refinement', 'create fully connected layers with Conv1d, BatchNorm1d, and ReLU for ROI head feature processing', 'run the proposal layer to perform NMS on batch box predictions and extract ROI regions', 'review the assign_targets method that performs canonical transformation and coordinate rotation for ROI targets', 'test the get_loss method to compute combined classification and regression loss for RCNN training']
```

Usage

```
{'build_PointRCNNHead': 'build a PointRCNNHead ROI head for 3D object detection using input channels and model config', 'init_weights_PointRCNNHead': 'initialize PointRCNNHead convolutional and regression layer weights using xavier, kaiming, or normal initialization', 'roipool3d_gpu_PointRCNNHead': 'pool 3D point cloud features into ROI regions using GPU-accelerated RoI point pooling with canonical transformation', 'forward_PointRCNNHead': 'run the PointRCNNHead forward pass to produce classification and regression predictions from batched ROI features', 'review_PointRCNNHead_SA_modules': 'review the PointRCNNHead set abstraction modules configuration for radius, sampling, and MLP channel design'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/roi_heads/pvrcnn_head.py

Prompts

```
['build a PartA2FCHead ROI head network for 3D object detection using sparse convolutions and RoI-aware pooling', 'create a sparse convolution block with batch norm and ReLU for submanifold, sparse, or inverse conv types', 'run RoI-aware 3D pooling on point cloud features using average pooling for parts and max pooling for RPN features', 'test the PartA2FCHead weight initialization with xavier, kaiming, or normal strategies for conv layers', 'review the PartA2FCHead forward pass that performs RoI pooling, sparse conv, and classification/regression prediction', 'build a PointRCNNHead ROI head for 3D object detection using input channels and model config', 'initialize PointRCNNHead convolutional and regression layer weights using xavier, kaiming, or normal initialization', 'pool 3D point cloud features into ROI regions using GPU-accelerated RoI point pooling with canonical transformation', 'run the PointRCNNHead forward pass to produce classification and regression predictions from batched ROI features', 'review the PointRCNNHead set abstraction modules configuration for radius, sampling, and MLP channel design', 'build a PVRCNNHead ROI head model with input channels and model config for 3D object detection', 'run the PVRCNNHead forward pass to generate RoI classification and regression predictions from batch dict', 'create RoI grid pooled features by pooling point cloud features onto a 3D grid for each RoI', 'review the PVRCNNHead init_weights method to initialize convolutional layers with xavier, kaiming, or normal initialization', 'test the get_dense_grid_points static method to generate dense 3D grid points inside RoI bounding boxes', 'build a RoIHeadTemplate instance with num_class and model_cfg for 3D object detection ROI refinement', 'create fully connected layers with Conv1d, BatchNorm1d, and ReLU for ROI head feature processing', 'run the proposal layer to perform NMS on batch box predictions and extract ROI regions', 'review the assign_targets method that performs canonical transformation and coordinate rotation for ROI targets', 'test the get_loss method to compute combined classification and regression loss for RCNN training']
```

Usage

```
{'build_PVRCNNHead': 'build a PVRCNNHead ROI head model with input channels and model config for 3D object detection', 'run_PVRCNNHead_forward': 'run the PVRCNNHead forward pass to generate RoI classification and regression predictions from batch dict', 'create_roi_grid_pool': 'create RoI grid pooled features by pooling point cloud features onto a 3D grid for each RoI', 'review_PVRCNNHead_init_weights': 'review the PVRCNNHead init_weights method to initialize convolutional layers with xavier, kaiming, or normal initialization', 'test_get_dense_grid_points': 'test the get_dense_grid_points static method to generate dense 3D grid points inside RoI bounding boxes'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/models/roi_heads/roi_head_template.py

Prompts

```
['build a PartA2FCHead ROI head network for 3D object detection using sparse convolutions and RoI-aware pooling', 'create a sparse convolution block with batch norm and ReLU for submanifold, sparse, or inverse conv types', 'run RoI-aware 3D pooling on point cloud features using average pooling for parts and max pooling for RPN features', 'test the PartA2FCHead weight initialization with xavier, kaiming, or normal strategies for conv layers', 'review the PartA2FCHead forward pass that performs RoI pooling, sparse conv, and classification/regression prediction', 'build a PointRCNNHead ROI head for 3D object detection using input channels and model config', 'initialize PointRCNNHead convolutional and regression layer weights using xavier, kaiming, or normal initialization', 'pool 3D point cloud features into ROI regions using GPU-accelerated RoI point pooling with canonical transformation', 'run the PointRCNNHead forward pass to produce classification and regression predictions from batched ROI features', 'review the PointRCNNHead set abstraction modules configuration for radius, sampling, and MLP channel design', 'build a PVRCNNHead ROI head model with input channels and model config for 3D object detection', 'run the PVRCNNHead forward pass to generate RoI classification and regression predictions from batch dict', 'create RoI grid pooled features by pooling point cloud features onto a 3D grid for each RoI', 'review the PVRCNNHead init_weights method to initialize convolutional layers with xavier, kaiming, or normal initialization', 'test the get_dense_grid_points static method to generate dense 3D grid points inside RoI bounding boxes', 'build a RoIHeadTemplate instance with num_class and model_cfg for 3D object detection ROI refinement', 'create fully connected layers with Conv1d, BatchNorm1d, and ReLU for ROI head feature processing', 'run the proposal layer to perform NMS on batch box predictions and extract ROI regions', 'review the assign_targets method that performs canonical transformation and coordinate rotation for ROI targets', 'test the get_loss method to compute combined classification and regression loss for RCNN training']
```

Usage

```
{'build_roi_head_template': 'build a RoIHeadTemplate instance with num_class and model_cfg for 3D object detection ROI refinement', 'create_fc_layers': 'create fully connected layers with Conv1d, BatchNorm1d, and ReLU for ROI head feature processing', 'run_proposal_layer': 'run the proposal layer to perform NMS on batch box predictions and extract ROI regions', 'review_assign_targets': 'review the assign_targets method that performs canonical transformation and coordinate rotation for ROI targets', 'test_get_loss': 'test the get_loss method to compute combined classification and regression loss for RCNN training'}
```

