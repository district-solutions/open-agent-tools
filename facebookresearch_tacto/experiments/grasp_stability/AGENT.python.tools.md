# Agent Python Tools

- repo: facebookresearch/tacto
- repo_uri: https://github.com/facebookresearch/tacto

## File: facebookresearch_tacto/experiments/grasp_stability/draw.py

Prompts

```
['run the draw script to plot grasp stability test accuracy across sensor modalities', 'load cross-validation accuracy and variance from grasp experiment h5 log files', 'summarize the load function that computes mean and variance of test accuracy across folds', 'review the draw script that compares vision and tactile sensor performance for grasp stability', 'refactor the load function to support configurable cross-validation fold counts per sample size', 'run the grasp data collection script to simulate robot grasping and collect tactile and vision sensor data', 'create a Camera class that captures RGB and depth images from a PyBullet simulation using OpenGL rendering', 'create a Log class that batches and saves grasp sensor data including tactile color, depth, vision, and force readings to HDF5 files', 'use the get_forces function to retrieve normal and lateral friction contact forces between two PyBullet bodies', 'use the get_object_pose function to get the world position and orientation of a simulated object and reset it if it falls out of bounds', 'initialize a Robot instance with a pybullet robotID and set up arm and gripper joints', 'move the robot end-effector to a target position and orientation with optional gripper width', 'get the current world position and orientation of the robot end-effector', 'set the robot gripper to a target opening width in meters', 'get the current joint angles of the robot arm joints', 'create a PyTorch Dataset that loads tactile and vision grasp data from HDF5 files with transforms', 'create a torchvision transform that adds configurable Gaussian noise to tensors for data augmentation', 'build a multi-modal ResNet-18 model that fuses tactile and vision embeddings for grasp stability classification', 'train a grasp stability model with K-fold cross-validation using Adam optimizer and cross-entropy loss', 'run K-fold cross-validation experiments for different sensor field combinations and log accuracy results']
```

Usage

```
{'run_draw_plot': 'run the draw script to plot grasp stability test accuracy across sensor modalities', 'load_grasp_accuracy': 'load cross-validation accuracy and variance from grasp experiment h5 log files', 'summarize_load_function': 'summarize the load function that computes mean and variance of test accuracy across folds', 'review_draw_script': 'review the draw script that compares vision and tactile sensor performance for grasp stability', 'refactor_load_function': 'refactor the load function to support configurable cross-validation fold counts per sample size'}
```

## File: facebookresearch_tacto/experiments/grasp_stability/grasp_data_collection.py

Prompts

```
['run the draw script to plot grasp stability test accuracy across sensor modalities', 'load cross-validation accuracy and variance from grasp experiment h5 log files', 'summarize the load function that computes mean and variance of test accuracy across folds', 'review the draw script that compares vision and tactile sensor performance for grasp stability', 'refactor the load function to support configurable cross-validation fold counts per sample size', 'run the grasp data collection script to simulate robot grasping and collect tactile and vision sensor data', 'create a Camera class that captures RGB and depth images from a PyBullet simulation using OpenGL rendering', 'create a Log class that batches and saves grasp sensor data including tactile color, depth, vision, and force readings to HDF5 files', 'use the get_forces function to retrieve normal and lateral friction contact forces between two PyBullet bodies', 'use the get_object_pose function to get the world position and orientation of a simulated object and reset it if it falls out of bounds', 'initialize a Robot instance with a pybullet robotID and set up arm and gripper joints', 'move the robot end-effector to a target position and orientation with optional gripper width', 'get the current world position and orientation of the robot end-effector', 'set the robot gripper to a target opening width in meters', 'get the current joint angles of the robot arm joints', 'create a PyTorch Dataset that loads tactile and vision grasp data from HDF5 files with transforms', 'create a torchvision transform that adds configurable Gaussian noise to tensors for data augmentation', 'build a multi-modal ResNet-18 model that fuses tactile and vision embeddings for grasp stability classification', 'train a grasp stability model with K-fold cross-validation using Adam optimizer and cross-entropy loss', 'run K-fold cross-validation experiments for different sensor field combinations and log accuracy results']
```

Usage

```
{'run_grasp_data_collection': 'run the grasp data collection script to simulate robot grasping and collect tactile and vision sensor data', 'create_Camera_class': 'create a Camera class that captures RGB and depth images from a PyBullet simulation using OpenGL rendering', 'create_Log_class': 'create a Log class that batches and saves grasp sensor data including tactile color, depth, vision, and force readings to HDF5 files', 'use_get_forces_function': 'use the get_forces function to retrieve normal and lateral friction contact forces between two PyBullet bodies', 'use_get_object_pose_function': 'use the get_object_pose function to get the world position and orientation of a simulated object and reset it if it falls out of bounds'}
```

## File: facebookresearch_tacto/experiments/grasp_stability/robot.py

Prompts

```
['run the draw script to plot grasp stability test accuracy across sensor modalities', 'load cross-validation accuracy and variance from grasp experiment h5 log files', 'summarize the load function that computes mean and variance of test accuracy across folds', 'review the draw script that compares vision and tactile sensor performance for grasp stability', 'refactor the load function to support configurable cross-validation fold counts per sample size', 'run the grasp data collection script to simulate robot grasping and collect tactile and vision sensor data', 'create a Camera class that captures RGB and depth images from a PyBullet simulation using OpenGL rendering', 'create a Log class that batches and saves grasp sensor data including tactile color, depth, vision, and force readings to HDF5 files', 'use the get_forces function to retrieve normal and lateral friction contact forces between two PyBullet bodies', 'use the get_object_pose function to get the world position and orientation of a simulated object and reset it if it falls out of bounds', 'initialize a Robot instance with a pybullet robotID and set up arm and gripper joints', 'move the robot end-effector to a target position and orientation with optional gripper width', 'get the current world position and orientation of the robot end-effector', 'set the robot gripper to a target opening width in meters', 'get the current joint angles of the robot arm joints', 'create a PyTorch Dataset that loads tactile and vision grasp data from HDF5 files with transforms', 'create a torchvision transform that adds configurable Gaussian noise to tensors for data augmentation', 'build a multi-modal ResNet-18 model that fuses tactile and vision embeddings for grasp stability classification', 'train a grasp stability model with K-fold cross-validation using Adam optimizer and cross-entropy loss', 'run K-fold cross-validation experiments for different sensor field combinations and log accuracy results']
```

Usage

```
{'init_robot_Robot': 'initialize a Robot instance with a pybullet robotID and set up arm and gripper joints', 'go_Robot': 'move the robot end-effector to a target position and orientation with optional gripper width', 'get_ee_pose_Robot': 'get the current world position and orientation of the robot end-effector', 'gripper_control_Robot': 'set the robot gripper to a target opening width in meters', 'get_joint_angles_Robot': 'get the current joint angles of the robot arm joints'}
```

## File: facebookresearch_tacto/experiments/grasp_stability/train.py

Prompts

```
['run the draw script to plot grasp stability test accuracy across sensor modalities', 'load cross-validation accuracy and variance from grasp experiment h5 log files', 'summarize the load function that computes mean and variance of test accuracy across folds', 'review the draw script that compares vision and tactile sensor performance for grasp stability', 'refactor the load function to support configurable cross-validation fold counts per sample size', 'run the grasp data collection script to simulate robot grasping and collect tactile and vision sensor data', 'create a Camera class that captures RGB and depth images from a PyBullet simulation using OpenGL rendering', 'create a Log class that batches and saves grasp sensor data including tactile color, depth, vision, and force readings to HDF5 files', 'use the get_forces function to retrieve normal and lateral friction contact forces between two PyBullet bodies', 'use the get_object_pose function to get the world position and orientation of a simulated object and reset it if it falls out of bounds', 'initialize a Robot instance with a pybullet robotID and set up arm and gripper joints', 'move the robot end-effector to a target position and orientation with optional gripper width', 'get the current world position and orientation of the robot end-effector', 'set the robot gripper to a target opening width in meters', 'get the current joint angles of the robot arm joints', 'create a PyTorch Dataset that loads tactile and vision grasp data from HDF5 files with transforms', 'create a torchvision transform that adds configurable Gaussian noise to tensors for data augmentation', 'build a multi-modal ResNet-18 model that fuses tactile and vision embeddings for grasp stability classification', 'train a grasp stability model with K-fold cross-validation using Adam optimizer and cross-entropy loss', 'run K-fold cross-validation experiments for different sensor field combinations and log accuracy results']
```

Usage

```
{'run_GraspingDataset': 'create a PyTorch Dataset that loads tactile and vision grasp data from HDF5 files with transforms', 'run_AddGaussianNoise': 'create a torchvision transform that adds configurable Gaussian noise to tensors for data augmentation', 'run_Model': 'build a multi-modal ResNet-18 model that fuses tactile and vision embeddings for grasp stability classification', 'run_Learning': 'train a grasp stability model with K-fold cross-validation using Adam optimizer and cross-entropy loss', 'run_test': 'run K-fold cross-validation experiments for different sensor field combinations and log accuracy results'}
```

