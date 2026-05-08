# Agent Python Tools

- repo: facebookresearch/poincare-embeddings
- repo_uri: https://github.com/facebookresearch/poincare-embeddings

## File: facebookresearch_poincare-embeddings/hype/manifolds/euclidean.py

Prompts

```
['create a EuclideanManifold instance with optional max_norm and curvature K parameters', 'compute the squared Euclidean distance between two tensors u and v using the manifold', "normalize tensor vectors in-place using the manifold's max_norm renorm constraint", 'compute the exponential map on the Euclidean manifold with optional learning rate and normalization', 'compute the angle at point u between vectors u and v using the law of cosines', 'create a LorentzManifold instance with custom eps, norm_clip, max_norm, and curvature K parameters', 'compute the Lorentzian scalar product of two tensors using the ldot static method', 'normalize embedding vectors onto the hyperboloid surface using the normalize method', 'compute the geodesic distance between two points on the Lorentz hyperboloid manifold', 'apply the exponential map to update points on the hyperboloid along tangent vectors', 'review the Manifold abstract base class and its geometric operations for Poincare embeddings', 'implement a concrete Manifold subclass that provides the distance method for two points', 'implement a concrete Manifold subclass that provides the expm exponential map method', 'implement a concrete Manifold subclass that provides the logm logarithmic map method', 'use the Manifold norm method to compute the L2 norm of embedding weights', 'create a PoincareManifold instance with curvature K and epsilon for numerical stability', 'compute the Poincare distance between two tensors u and v using the manifold distance method', 'compute the half aperture angle at a point u on the Poincare manifold', 'compute the angle at point u between vectors u and v on the Poincare manifold', 'compute the Riemannian gradient by scaling Euclidean gradient d_p with position p on the manifold']
```

Usage

```
{'create_EuclideanManifold': 'create a EuclideanManifold instance with optional max_norm and curvature K parameters', 'compute_EuclideanManifold_distance': 'compute the squared Euclidean distance between two tensors u and v using the manifold', 'normalize_EuclideanManifold_vectors': "normalize tensor vectors in-place using the manifold's max_norm renorm constraint", 'compute_EuclideanManifold_expm': 'compute the exponential map on the Euclidean manifold with optional learning rate and normalization', 'compute_EuclideanManifold_angle': 'compute the angle at point u between vectors u and v using the law of cosines'}
```

## File: facebookresearch_poincare-embeddings/hype/manifolds/lorentz.py

Prompts

```
['create a EuclideanManifold instance with optional max_norm and curvature K parameters', 'compute the squared Euclidean distance between two tensors u and v using the manifold', "normalize tensor vectors in-place using the manifold's max_norm renorm constraint", 'compute the exponential map on the Euclidean manifold with optional learning rate and normalization', 'compute the angle at point u between vectors u and v using the law of cosines', 'create a LorentzManifold instance with custom eps, norm_clip, max_norm, and curvature K parameters', 'compute the Lorentzian scalar product of two tensors using the ldot static method', 'normalize embedding vectors onto the hyperboloid surface using the normalize method', 'compute the geodesic distance between two points on the Lorentz hyperboloid manifold', 'apply the exponential map to update points on the hyperboloid along tangent vectors', 'review the Manifold abstract base class and its geometric operations for Poincare embeddings', 'implement a concrete Manifold subclass that provides the distance method for two points', 'implement a concrete Manifold subclass that provides the expm exponential map method', 'implement a concrete Manifold subclass that provides the logm logarithmic map method', 'use the Manifold norm method to compute the L2 norm of embedding weights', 'create a PoincareManifold instance with curvature K and epsilon for numerical stability', 'compute the Poincare distance between two tensors u and v using the manifold distance method', 'compute the half aperture angle at a point u on the Poincare manifold', 'compute the angle at point u between vectors u and v on the Poincare manifold', 'compute the Riemannian gradient by scaling Euclidean gradient d_p with position p on the manifold']
```

Usage

```
{'create_lorentz_manifold': 'create a LorentzManifold instance with custom eps, norm_clip, max_norm, and curvature K parameters', 'compute_lorentzian_dot_product': 'compute the Lorentzian scalar product of two tensors using the ldot static method', 'normalize_hyperboloid_vectors': 'normalize embedding vectors onto the hyperboloid surface using the normalize method', 'compute_hyperboloid_distance': 'compute the geodesic distance between two points on the Lorentz hyperboloid manifold', 'apply_exponential_map': 'apply the exponential map to update points on the hyperboloid along tangent vectors'}
```

## File: facebookresearch_poincare-embeddings/hype/manifolds/manifold.py

Prompts

```
['create a EuclideanManifold instance with optional max_norm and curvature K parameters', 'compute the squared Euclidean distance between two tensors u and v using the manifold', "normalize tensor vectors in-place using the manifold's max_norm renorm constraint", 'compute the exponential map on the Euclidean manifold with optional learning rate and normalization', 'compute the angle at point u between vectors u and v using the law of cosines', 'create a LorentzManifold instance with custom eps, norm_clip, max_norm, and curvature K parameters', 'compute the Lorentzian scalar product of two tensors using the ldot static method', 'normalize embedding vectors onto the hyperboloid surface using the normalize method', 'compute the geodesic distance between two points on the Lorentz hyperboloid manifold', 'apply the exponential map to update points on the hyperboloid along tangent vectors', 'review the Manifold abstract base class and its geometric operations for Poincare embeddings', 'implement a concrete Manifold subclass that provides the distance method for two points', 'implement a concrete Manifold subclass that provides the expm exponential map method', 'implement a concrete Manifold subclass that provides the logm logarithmic map method', 'use the Manifold norm method to compute the L2 norm of embedding weights', 'create a PoincareManifold instance with curvature K and epsilon for numerical stability', 'compute the Poincare distance between two tensors u and v using the manifold distance method', 'compute the half aperture angle at a point u on the Poincare manifold', 'compute the angle at point u between vectors u and v on the Poincare manifold', 'compute the Riemannian gradient by scaling Euclidean gradient d_p with position p on the manifold']
```

Usage

```
{'review_Manifold_class': 'review the Manifold abstract base class and its geometric operations for Poincare embeddings', 'implement_Manifold_distance': 'implement a concrete Manifold subclass that provides the distance method for two points', 'implement_Manifold_expm': 'implement a concrete Manifold subclass that provides the expm exponential map method', 'implement_Manifold_logm': 'implement a concrete Manifold subclass that provides the logm logarithmic map method', 'use_Manifold_norm': 'use the Manifold norm method to compute the L2 norm of embedding weights'}
```

## File: facebookresearch_poincare-embeddings/hype/manifolds/poincare.py

Prompts

```
['create a EuclideanManifold instance with optional max_norm and curvature K parameters', 'compute the squared Euclidean distance between two tensors u and v using the manifold', "normalize tensor vectors in-place using the manifold's max_norm renorm constraint", 'compute the exponential map on the Euclidean manifold with optional learning rate and normalization', 'compute the angle at point u between vectors u and v using the law of cosines', 'create a LorentzManifold instance with custom eps, norm_clip, max_norm, and curvature K parameters', 'compute the Lorentzian scalar product of two tensors using the ldot static method', 'normalize embedding vectors onto the hyperboloid surface using the normalize method', 'compute the geodesic distance between two points on the Lorentz hyperboloid manifold', 'apply the exponential map to update points on the hyperboloid along tangent vectors', 'review the Manifold abstract base class and its geometric operations for Poincare embeddings', 'implement a concrete Manifold subclass that provides the distance method for two points', 'implement a concrete Manifold subclass that provides the expm exponential map method', 'implement a concrete Manifold subclass that provides the logm logarithmic map method', 'use the Manifold norm method to compute the L2 norm of embedding weights', 'create a PoincareManifold instance with curvature K and epsilon for numerical stability', 'compute the Poincare distance between two tensors u and v using the manifold distance method', 'compute the half aperture angle at a point u on the Poincare manifold', 'compute the angle at point u between vectors u and v on the Poincare manifold', 'compute the Riemannian gradient by scaling Euclidean gradient d_p with position p on the manifold']
```

Usage

```
{'create_poincare_manifold': 'create a PoincareManifold instance with curvature K and epsilon for numerical stability', 'compute_poincare_distance': 'compute the Poincare distance between two tensors u and v using the manifold distance method', 'compute_half_aperture': 'compute the half aperture angle at a point u on the Poincare manifold', 'compute_angle_at_u': 'compute the angle at point u between vectors u and v on the Poincare manifold', 'compute_rgrad': 'compute the Riemannian gradient by scaling Euclidean gradient d_p with position p on the manifold'}
```

