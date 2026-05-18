# Agent Python Tools

- repo: facebookresearch/meta-ot
- repo_uri: https://github.com/facebookresearch/meta-ot

## File: facebookresearch_meta-ot/meta_ot/conjugate.py

Prompts

```
['build a Solver dataclass to perform conjugate minimization with JAX-based gradient descent and line search', 'create a Solver instance and call solve with D_params and y to compute conjugate dual values', 'test the Solver solve_debug method to iteratively minimize the conjugate objective with verbose output', 'refactor the Solver to use unit_box projection by setting projection_name to unit_box', 'summarize the ConjStatus namedtuple which holds val, grad, and num_iter from conjugate optimization', 'create an MNISTPairSampler dataclass to sample paired MNIST digit distributions for optimal transport', 'create a WorldPairSampler dataclass to sample paired world population supply and demand distributions', 'create an ImageSampler class to load, normalize, and sample pixel values from an RGB image file', 'create an ImagePairSampler class to sample pairs of ImageSampler instances and their normalized image batches', 'create a USPSPairSampler dataclass to sample paired USPS handwritten digit distributions for optimal transport', 'build an ICNN model with configurable hidden dimensions and leaky_relu activation for optimal transport', 'build a ResNet18 model for encoding image pairs into bottleneck features for MetaICNN', 'build a MetaICNN that uses ResNet18 to predict ICNN parameters from image pairs', 'build a PotentialMLP that concatenates two inputs and passes them through a ReLU MLP', 'build a LatentGaussianEnc that maps density inputs to Gaussian mean and covariance parameters', 'convert spherical coordinates (theta, phi) to 3D Euclidean xyz coordinates using JAX', 'convert 3D Euclidean xyz coordinates to spherical (theta, phi) coordinates using JAX', 'create a SphereDist cost function that computes pairwise arccos distance between vectors for optimal transport', 'create a RunningAverageMeter to track smoothed averages of values with configurable momentum decay', 'create a Gaussian namedtuple with mean and cov fields for representing Gaussian distributions']
```

Usage

```
{'build_solver_conjugate_minimization': 'build a Solver dataclass to perform conjugate minimization with JAX-based gradient descent and line search', 'create_solver_solve': 'create a Solver instance and call solve with D_params and y to compute conjugate dual values', 'test_solver_solve_debug': 'test the Solver solve_debug method to iteratively minimize the conjugate objective with verbose output', 'refactor_solver_projection_fn': 'refactor the Solver to use unit_box projection by setting projection_name to unit_box', 'summarize_conjstatus_namedtuple': 'summarize the ConjStatus namedtuple which holds val, grad, and num_iter from conjugate optimization'}
```

## File: facebookresearch_meta-ot/meta_ot/data.py

Prompts

```
['build a Solver dataclass to perform conjugate minimization with JAX-based gradient descent and line search', 'create a Solver instance and call solve with D_params and y to compute conjugate dual values', 'test the Solver solve_debug method to iteratively minimize the conjugate objective with verbose output', 'refactor the Solver to use unit_box projection by setting projection_name to unit_box', 'summarize the ConjStatus namedtuple which holds val, grad, and num_iter from conjugate optimization', 'create an MNISTPairSampler dataclass to sample paired MNIST digit distributions for optimal transport', 'create a WorldPairSampler dataclass to sample paired world population supply and demand distributions', 'create an ImageSampler class to load, normalize, and sample pixel values from an RGB image file', 'create an ImagePairSampler class to sample pairs of ImageSampler instances and their normalized image batches', 'create a USPSPairSampler dataclass to sample paired USPS handwritten digit distributions for optimal transport', 'build an ICNN model with configurable hidden dimensions and leaky_relu activation for optimal transport', 'build a ResNet18 model for encoding image pairs into bottleneck features for MetaICNN', 'build a MetaICNN that uses ResNet18 to predict ICNN parameters from image pairs', 'build a PotentialMLP that concatenates two inputs and passes them through a ReLU MLP', 'build a LatentGaussianEnc that maps density inputs to Gaussian mean and covariance parameters', 'convert spherical coordinates (theta, phi) to 3D Euclidean xyz coordinates using JAX', 'convert 3D Euclidean xyz coordinates to spherical (theta, phi) coordinates using JAX', 'create a SphereDist cost function that computes pairwise arccos distance between vectors for optimal transport', 'create a RunningAverageMeter to track smoothed averages of values with configurable momentum decay', 'create a Gaussian namedtuple with mean and cov fields for representing Gaussian distributions']
```

Usage

```
{'create_MNISTPairSampler': 'create an MNISTPairSampler dataclass to sample paired MNIST digit distributions for optimal transport', 'create_WorldPairSampler': 'create a WorldPairSampler dataclass to sample paired world population supply and demand distributions', 'create_ImageSampler': 'create an ImageSampler class to load, normalize, and sample pixel values from an RGB image file', 'create_ImagePairSampler': 'create an ImagePairSampler class to sample pairs of ImageSampler instances and their normalized image batches', 'create_USPSPairSampler': 'create a USPSPairSampler dataclass to sample paired USPS handwritten digit distributions for optimal transport'}
```

## File: facebookresearch_meta-ot/meta_ot/models.py

Prompts

```
['build a Solver dataclass to perform conjugate minimization with JAX-based gradient descent and line search', 'create a Solver instance and call solve with D_params and y to compute conjugate dual values', 'test the Solver solve_debug method to iteratively minimize the conjugate objective with verbose output', 'refactor the Solver to use unit_box projection by setting projection_name to unit_box', 'summarize the ConjStatus namedtuple which holds val, grad, and num_iter from conjugate optimization', 'create an MNISTPairSampler dataclass to sample paired MNIST digit distributions for optimal transport', 'create a WorldPairSampler dataclass to sample paired world population supply and demand distributions', 'create an ImageSampler class to load, normalize, and sample pixel values from an RGB image file', 'create an ImagePairSampler class to sample pairs of ImageSampler instances and their normalized image batches', 'create a USPSPairSampler dataclass to sample paired USPS handwritten digit distributions for optimal transport', 'build an ICNN model with configurable hidden dimensions and leaky_relu activation for optimal transport', 'build a ResNet18 model for encoding image pairs into bottleneck features for MetaICNN', 'build a MetaICNN that uses ResNet18 to predict ICNN parameters from image pairs', 'build a PotentialMLP that concatenates two inputs and passes them through a ReLU MLP', 'build a LatentGaussianEnc that maps density inputs to Gaussian mean and covariance parameters', 'convert spherical coordinates (theta, phi) to 3D Euclidean xyz coordinates using JAX', 'convert 3D Euclidean xyz coordinates to spherical (theta, phi) coordinates using JAX', 'create a SphereDist cost function that computes pairwise arccos distance between vectors for optimal transport', 'create a RunningAverageMeter to track smoothed averages of values with configurable momentum decay', 'create a Gaussian namedtuple with mean and cov fields for representing Gaussian distributions']
```

Usage

```
{'build_icnn_potential': 'build an ICNN model with configurable hidden dimensions and leaky_relu activation for optimal transport', 'build_resnet18_encoder': 'build a ResNet18 model for encoding image pairs into bottleneck features for MetaICNN', 'build_metaicnn_model': 'build a MetaICNN that uses ResNet18 to predict ICNN parameters from image pairs', 'build_potential_mlp': 'build a PotentialMLP that concatenates two inputs and passes them through a ReLU MLP', 'build_latent_gaussian_encoder': 'build a LatentGaussianEnc that maps density inputs to Gaussian mean and covariance parameters'}
```

## File: facebookresearch_meta-ot/meta_ot/utils.py

Prompts

```
['build a Solver dataclass to perform conjugate minimization with JAX-based gradient descent and line search', 'create a Solver instance and call solve with D_params and y to compute conjugate dual values', 'test the Solver solve_debug method to iteratively minimize the conjugate objective with verbose output', 'refactor the Solver to use unit_box projection by setting projection_name to unit_box', 'summarize the ConjStatus namedtuple which holds val, grad, and num_iter from conjugate optimization', 'create an MNISTPairSampler dataclass to sample paired MNIST digit distributions for optimal transport', 'create a WorldPairSampler dataclass to sample paired world population supply and demand distributions', 'create an ImageSampler class to load, normalize, and sample pixel values from an RGB image file', 'create an ImagePairSampler class to sample pairs of ImageSampler instances and their normalized image batches', 'create a USPSPairSampler dataclass to sample paired USPS handwritten digit distributions for optimal transport', 'build an ICNN model with configurable hidden dimensions and leaky_relu activation for optimal transport', 'build a ResNet18 model for encoding image pairs into bottleneck features for MetaICNN', 'build a MetaICNN that uses ResNet18 to predict ICNN parameters from image pairs', 'build a PotentialMLP that concatenates two inputs and passes them through a ReLU MLP', 'build a LatentGaussianEnc that maps density inputs to Gaussian mean and covariance parameters', 'convert spherical coordinates (theta, phi) to 3D Euclidean xyz coordinates using JAX', 'convert 3D Euclidean xyz coordinates to spherical (theta, phi) coordinates using JAX', 'create a SphereDist cost function that computes pairwise arccos distance between vectors for optimal transport', 'create a RunningAverageMeter to track smoothed averages of values with configurable momentum decay', 'create a Gaussian namedtuple with mean and cov fields for representing Gaussian distributions']
```

Usage

```
{'convert_spherical_to_euclidean': 'convert spherical coordinates (theta, phi) to 3D Euclidean xyz coordinates using JAX', 'convert_euclidean_to_spherical': 'convert 3D Euclidean xyz coordinates to spherical (theta, phi) coordinates using JAX', 'create_spheredist_cost_fn': 'create a SphereDist cost function that computes pairwise arccos distance between vectors for optimal transport', 'use_runningaverage_meter': 'create a RunningAverageMeter to track smoothed averages of values with configurable momentum decay', 'create_gaussian_namedtuple': 'create a Gaussian namedtuple with mean and cov fields for representing Gaussian distributions'}
```

