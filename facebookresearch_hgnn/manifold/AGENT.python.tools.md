# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/manifold/EuclideanManifold.py

Prompts

```
['create a EuclideanManifold instance and initialize embedding weights with uniform random values then normalize', 'compute the Euclidean distance between two tensors u and v using the manifold distance method', 'compute the logarithmic map from point x to y or from zero to y on the Euclidean manifold', 'compute the exponential map from zero or point x along vector v and normalize the result', 'clip tensor weights by their norm using the EuclideanManifold normalize method with a max_norm threshold', 'create a LorentzManifold instance with args, logger, and configurable eps and norm_clip parameters', 'compute the Lorentzian scalar product of two batched tensors using the static ldot method', 'convert points from Lorentz model coordinates to Poincare ball coordinates using from_lorentz_to_poincare', 'compute the geodesic distance between two points on the hyperboloid using the distance method', 'compute the exponential map from a point along a tangent vector using exp_map_x or exp_map_zero', 'create a PoincareManifold instance with args and logger for hyperbolic space operations', 'add two vectors in hyperbolic space using the mobius addition operation', 'compute the Poincare distance between two points in hyperbolic space', 'map a tangent space vector to hyperbolic space using the exponential map', 'compute the Riemannian gradient from the Euclidean gradient in the Poincare ball']
```

Usage

```
{'init_embed_EuclideanManifold': 'create a EuclideanManifold instance and initialize embedding weights with uniform random values then normalize', 'distance_EuclideanManifold': 'compute the Euclidean distance between two tensors u and v using the manifold distance method', 'log_map_EuclideanManifold': 'compute the logarithmic map from point x to y or from zero to y on the Euclidean manifold', 'exp_map_EuclideanManifold': 'compute the exponential map from zero or point x along vector v and normalize the result', 'normalize_EuclideanManifold': 'clip tensor weights by their norm using the EuclideanManifold normalize method with a max_norm threshold'}
```

## File: facebookresearch_hgnn/manifold/LorentzManifold.py

Prompts

```
['create a EuclideanManifold instance and initialize embedding weights with uniform random values then normalize', 'compute the Euclidean distance between two tensors u and v using the manifold distance method', 'compute the logarithmic map from point x to y or from zero to y on the Euclidean manifold', 'compute the exponential map from zero or point x along vector v and normalize the result', 'clip tensor weights by their norm using the EuclideanManifold normalize method with a max_norm threshold', 'create a LorentzManifold instance with args, logger, and configurable eps and norm_clip parameters', 'compute the Lorentzian scalar product of two batched tensors using the static ldot method', 'convert points from Lorentz model coordinates to Poincare ball coordinates using from_lorentz_to_poincare', 'compute the geodesic distance between two points on the hyperboloid using the distance method', 'compute the exponential map from a point along a tangent vector using exp_map_x or exp_map_zero', 'create a PoincareManifold instance with args and logger for hyperbolic space operations', 'add two vectors in hyperbolic space using the mobius addition operation', 'compute the Poincare distance between two points in hyperbolic space', 'map a tangent space vector to hyperbolic space using the exponential map', 'compute the Riemannian gradient from the Euclidean gradient in the Poincare ball']
```

Usage

```
{'create_lorentz_manifold': 'create a LorentzManifold instance with args, logger, and configurable eps and norm_clip parameters', 'compute_lorentzian_dot_product': 'compute the Lorentzian scalar product of two batched tensors using the static ldot method', 'convert_lorentz_to_poincare': 'convert points from Lorentz model coordinates to Poincare ball coordinates using from_lorentz_to_poincare', 'compute_geodesic_distance': 'compute the geodesic distance between two points on the hyperboloid using the distance method', 'compute_exponential_map': 'compute the exponential map from a point along a tangent vector using exp_map_x or exp_map_zero'}
```

## File: facebookresearch_hgnn/manifold/PoincareManifold.py

Prompts

```
['create a EuclideanManifold instance and initialize embedding weights with uniform random values then normalize', 'compute the Euclidean distance between two tensors u and v using the manifold distance method', 'compute the logarithmic map from point x to y or from zero to y on the Euclidean manifold', 'compute the exponential map from zero or point x along vector v and normalize the result', 'clip tensor weights by their norm using the EuclideanManifold normalize method with a max_norm threshold', 'create a LorentzManifold instance with args, logger, and configurable eps and norm_clip parameters', 'compute the Lorentzian scalar product of two batched tensors using the static ldot method', 'convert points from Lorentz model coordinates to Poincare ball coordinates using from_lorentz_to_poincare', 'compute the geodesic distance between two points on the hyperboloid using the distance method', 'compute the exponential map from a point along a tangent vector using exp_map_x or exp_map_zero', 'create a PoincareManifold instance with args and logger for hyperbolic space operations', 'add two vectors in hyperbolic space using the mobius addition operation', 'compute the Poincare distance between two points in hyperbolic space', 'map a tangent space vector to hyperbolic space using the exponential map', 'compute the Riemannian gradient from the Euclidean gradient in the Poincare ball']
```

Usage

```
{'init_poincare_manifold': 'create a PoincareManifold instance with args and logger for hyperbolic space operations', 'mob_add_vectors': 'add two vectors in hyperbolic space using the mobius addition operation', 'compute_poincare_distance': 'compute the Poincare distance between two points in hyperbolic space', 'exp_map_tangent_to_hyperbolic': 'map a tangent space vector to hyperbolic space using the exponential map', 'compute_riemannian_gradient': 'compute the Riemannian gradient from the Euclidean gradient in the Poincare ball'}
```

