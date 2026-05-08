# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/models/uma/common/rotation.py

Prompts

```
['compute Euler angles from a PyTorch edge distance vector tensor for 3D rotation initialization', 'compute a Wigner-D rotation matrix for a given angular momentum level and Euler angles', 'convert Euler angle tensors into a block-diagonal Wigner-D matrix across a range of lmax values', 'apply a numerically stable arccos operation with safe gradient clipping for PyTorch autograd', 'apply a numerically stable atan2 operation with safe gradient clipping for PyTorch autograd', 'create a RotMatWignerCudaGraph instance to lazily capture CUDA graphs for Wigner matrix computation', 'call get_rotmat_and_wigner on RotMatWignerCudaGraph with edge distance vectors and Jd buffers to get Wigner matrices', 'capture rotation matrix and Wigner D-matrix computation as a CUDA graphed callable for faster inference', 'compute Wigner D-matrices and their inverses from edge distance vectors and Jd buffers inside a CUDA graph region', 'compute Euler angles alpha, beta, gamma and a north pole mask from 3D edge distance vectors', 'build a python module to sample N points on a sphere using the Fibonacci spiral algorithm with density weighting', 'build a python module to sample N random points on a unit sphere using rejection sampling', 'test the CalcSpherePoints function to verify it returns weighted 3D points on a unit sphere', 'test the CalcSpherePointsRandom function to verify it returns random points normalized to a unit sphere', 'refactor CalcSpherePoints to support configurable Gaussian bandwidth instead of hardcoded 0.5 * 0.3', 'create a CoefficientMapping module to map spherical harmonic coefficients between degree l and order m representations', 'build a coefficient index mask for spherical harmonics with specific maximum degree l and order m values', 'create an SO3 grid module to transform irreps to and from 2D spherical grid representations', 'test the SO3 to_grid method to convert an irreps embedding tensor into a spherical grid representation', 'test the SO3 from_grid method to convert a spherical grid tensor back into an irreps embedding']
```

Usage

```
{'init_edge_rot_euler_angles': 'compute Euler angles from a PyTorch edge distance vector tensor for 3D rotation initialization', 'wigner_D': 'compute a Wigner-D rotation matrix for a given angular momentum level and Euler angles', 'eulers_to_wigner': 'convert Euler angle tensors into a block-diagonal Wigner-D matrix across a range of lmax values', 'Safeacos': 'apply a numerically stable arccos operation with safe gradient clipping for PyTorch autograd', 'Safeatan2': 'apply a numerically stable atan2 operation with safe gradient clipping for PyTorch autograd'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/uma/common/rotation_cuda_graph.py

Prompts

```
['compute Euler angles from a PyTorch edge distance vector tensor for 3D rotation initialization', 'compute a Wigner-D rotation matrix for a given angular momentum level and Euler angles', 'convert Euler angle tensors into a block-diagonal Wigner-D matrix across a range of lmax values', 'apply a numerically stable arccos operation with safe gradient clipping for PyTorch autograd', 'apply a numerically stable atan2 operation with safe gradient clipping for PyTorch autograd', 'create a RotMatWignerCudaGraph instance to lazily capture CUDA graphs for Wigner matrix computation', 'call get_rotmat_and_wigner on RotMatWignerCudaGraph with edge distance vectors and Jd buffers to get Wigner matrices', 'capture rotation matrix and Wigner D-matrix computation as a CUDA graphed callable for faster inference', 'compute Wigner D-matrices and their inverses from edge distance vectors and Jd buffers inside a CUDA graph region', 'compute Euler angles alpha, beta, gamma and a north pole mask from 3D edge distance vectors', 'build a python module to sample N points on a sphere using the Fibonacci spiral algorithm with density weighting', 'build a python module to sample N random points on a unit sphere using rejection sampling', 'test the CalcSpherePoints function to verify it returns weighted 3D points on a unit sphere', 'test the CalcSpherePointsRandom function to verify it returns random points normalized to a unit sphere', 'refactor CalcSpherePoints to support configurable Gaussian bandwidth instead of hardcoded 0.5 * 0.3', 'create a CoefficientMapping module to map spherical harmonic coefficients between degree l and order m representations', 'build a coefficient index mask for spherical harmonics with specific maximum degree l and order m values', 'create an SO3 grid module to transform irreps to and from 2D spherical grid representations', 'test the SO3 to_grid method to convert an irreps embedding tensor into a spherical grid representation', 'test the SO3 from_grid method to convert a spherical grid tensor back into an irreps embedding']
```

Usage

```
{'create_RotMatWignerCudaGraph': 'create a RotMatWignerCudaGraph instance to lazily capture CUDA graphs for Wigner matrix computation', 'get_rotmat_and_wigner': 'call get_rotmat_and_wigner on RotMatWignerCudaGraph with edge distance vectors and Jd buffers to get Wigner matrices', 'capture_rotmat_and_wigner_with_make_graph_callable': 'capture rotation matrix and Wigner D-matrix computation as a CUDA graphed callable for faster inference', 'edge_rot_and_wigner_graph_capture_region': 'compute Wigner D-matrices and their inverses from edge distance vectors and Jd buffers inside a CUDA graph region', 'init_edge_rot_euler_angles_wigner_cuda_graph': 'compute Euler angles alpha, beta, gamma and a north pole mask from 3D edge distance vectors'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/uma/common/sampling.py

Prompts

```
['compute Euler angles from a PyTorch edge distance vector tensor for 3D rotation initialization', 'compute a Wigner-D rotation matrix for a given angular momentum level and Euler angles', 'convert Euler angle tensors into a block-diagonal Wigner-D matrix across a range of lmax values', 'apply a numerically stable arccos operation with safe gradient clipping for PyTorch autograd', 'apply a numerically stable atan2 operation with safe gradient clipping for PyTorch autograd', 'create a RotMatWignerCudaGraph instance to lazily capture CUDA graphs for Wigner matrix computation', 'call get_rotmat_and_wigner on RotMatWignerCudaGraph with edge distance vectors and Jd buffers to get Wigner matrices', 'capture rotation matrix and Wigner D-matrix computation as a CUDA graphed callable for faster inference', 'compute Wigner D-matrices and their inverses from edge distance vectors and Jd buffers inside a CUDA graph region', 'compute Euler angles alpha, beta, gamma and a north pole mask from 3D edge distance vectors', 'build a python module to sample N points on a sphere using the Fibonacci spiral algorithm with density weighting', 'build a python module to sample N random points on a unit sphere using rejection sampling', 'test the CalcSpherePoints function to verify it returns weighted 3D points on a unit sphere', 'test the CalcSpherePointsRandom function to verify it returns random points normalized to a unit sphere', 'refactor CalcSpherePoints to support configurable Gaussian bandwidth instead of hardcoded 0.5 * 0.3', 'create a CoefficientMapping module to map spherical harmonic coefficients between degree l and order m representations', 'build a coefficient index mask for spherical harmonics with specific maximum degree l and order m values', 'create an SO3 grid module to transform irreps to and from 2D spherical grid representations', 'test the SO3 to_grid method to convert an irreps embedding tensor into a spherical grid representation', 'test the SO3 from_grid method to convert a spherical grid tensor back into an irreps embedding']
```

Usage

```
{'build_sphere_points_fibonacci': 'build a python module to sample N points on a sphere using the Fibonacci spiral algorithm with density weighting', 'build_sphere_points_random': 'build a python module to sample N random points on a unit sphere using rejection sampling', 'test_CalcSpherePoints': 'test the CalcSpherePoints function to verify it returns weighted 3D points on a unit sphere', 'test_CalcSpherePointsRandom': 'test the CalcSpherePointsRandom function to verify it returns random points normalized to a unit sphere', 'refactor_CalcSpherePoints': 'refactor CalcSpherePoints to support configurable Gaussian bandwidth instead of hardcoded 0.5 * 0.3'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/uma/common/so3.py

Prompts

```
['compute Euler angles from a PyTorch edge distance vector tensor for 3D rotation initialization', 'compute a Wigner-D rotation matrix for a given angular momentum level and Euler angles', 'convert Euler angle tensors into a block-diagonal Wigner-D matrix across a range of lmax values', 'apply a numerically stable arccos operation with safe gradient clipping for PyTorch autograd', 'apply a numerically stable atan2 operation with safe gradient clipping for PyTorch autograd', 'create a RotMatWignerCudaGraph instance to lazily capture CUDA graphs for Wigner matrix computation', 'call get_rotmat_and_wigner on RotMatWignerCudaGraph with edge distance vectors and Jd buffers to get Wigner matrices', 'capture rotation matrix and Wigner D-matrix computation as a CUDA graphed callable for faster inference', 'compute Wigner D-matrices and their inverses from edge distance vectors and Jd buffers inside a CUDA graph region', 'compute Euler angles alpha, beta, gamma and a north pole mask from 3D edge distance vectors', 'build a python module to sample N points on a sphere using the Fibonacci spiral algorithm with density weighting', 'build a python module to sample N random points on a unit sphere using rejection sampling', 'test the CalcSpherePoints function to verify it returns weighted 3D points on a unit sphere', 'test the CalcSpherePointsRandom function to verify it returns random points normalized to a unit sphere', 'refactor CalcSpherePoints to support configurable Gaussian bandwidth instead of hardcoded 0.5 * 0.3', 'create a CoefficientMapping module to map spherical harmonic coefficients between degree l and order m representations', 'build a coefficient index mask for spherical harmonics with specific maximum degree l and order m values', 'create an SO3 grid module to transform irreps to and from 2D spherical grid representations', 'test the SO3 to_grid method to convert an irreps embedding tensor into a spherical grid representation', 'test the SO3 from_grid method to convert a spherical grid tensor back into an irreps embedding']
```

Usage

```
{'create_CoefficientMapping': 'create a CoefficientMapping module to map spherical harmonic coefficients between degree l and order m representations', 'build_CoefficientMapping_coefficient_idx': 'build a coefficient index mask for spherical harmonics with specific maximum degree l and order m values', 'create_SO3_Grid': 'create an SO3 grid module to transform irreps to and from 2D spherical grid representations', 'test_SO3_Grid_to_grid': 'test the SO3 to_grid method to convert an irreps embedding tensor into a spherical grid representation', 'test_SO3_Grid_from_grid': 'test the SO3 from_grid method to convert a spherical grid tensor back into an irreps embedding'}
```

