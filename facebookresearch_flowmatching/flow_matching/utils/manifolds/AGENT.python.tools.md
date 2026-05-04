# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/flow_matching/utils/manifolds/manifold.py

Prompts

```
['build a python module that uses Euclidean expmap to transport a point along a tangent vector', 'build a python module that uses Euclidean logmap to compute the tangent vector between two points', 'build a custom Manifold subclass implementing expmap, logmap, projx, and proju abstract methods', 'test the Euclidean manifold projx method to verify it returns the input point unchanged', 'test the Euclidean manifold proju method to verify it returns the input vector unchanged', 'build a python module to compute the exponential map on a hypersphere manifold using Sphere.expmap', 'build a python module to compute the logarithmic map between two points on a hypersphere using Sphere.logmap', 'build a python module to project arbitrary vectors onto the hypersphere surface using Sphere.projx', 'build a python module to project a tangent vector onto the tangent space of a hypersphere using Sphere.proju', 'build a python module to compute the geodesic distance between two points on a hypersphere using Sphere.dist', 'build a python module that uses FlatTorus expmap to compute exponential map on a flat torus manifold', 'create a function that uses FlatTorus logmap to compute the logarithmic map between two points on a torus', 'test the FlatTorus projx method to project points onto the [0, 2pi] torus subspace', 'review the FlatTorus proju method to understand tangent space projection on the flat torus manifold', 'summarize the FlatTorus class and its manifold operations for flow matching on toroidal geometry', 'build a python module that generates a geodesic curve between two points on a manifold', 'create a callable that returns geodesic points at any time t given start and end points', 'test the geodesic function by computing paths on a Euclidean manifold between two tensors', 'review the geodesic function that uses logmap and expmap to compute manifold geodesics', 'summarize the geodesic API that takes a manifold, start point, and end point to return a path function']
```

Usage

```
{'build_Euclidean_expmap': 'build a python module that uses Euclidean expmap to transport a point along a tangent vector', 'build_Euclidean_logmap': 'build a python module that uses Euclidean logmap to compute the tangent vector between two points', 'build_Manifold_subclass': 'build a custom Manifold subclass implementing expmap, logmap, projx, and proju abstract methods', 'test_Euclidean_projx': 'test the Euclidean manifold projx method to verify it returns the input point unchanged', 'test_Euclidean_proju': 'test the Euclidean manifold proju method to verify it returns the input vector unchanged'}
```

## File: facebookresearch_flowmatching/flow_matching/utils/manifolds/sphere.py

Prompts

```
['build a python module that uses Euclidean expmap to transport a point along a tangent vector', 'build a python module that uses Euclidean logmap to compute the tangent vector between two points', 'build a custom Manifold subclass implementing expmap, logmap, projx, and proju abstract methods', 'test the Euclidean manifold projx method to verify it returns the input point unchanged', 'test the Euclidean manifold proju method to verify it returns the input vector unchanged', 'build a python module to compute the exponential map on a hypersphere manifold using Sphere.expmap', 'build a python module to compute the logarithmic map between two points on a hypersphere using Sphere.logmap', 'build a python module to project arbitrary vectors onto the hypersphere surface using Sphere.projx', 'build a python module to project a tangent vector onto the tangent space of a hypersphere using Sphere.proju', 'build a python module to compute the geodesic distance between two points on a hypersphere using Sphere.dist', 'build a python module that uses FlatTorus expmap to compute exponential map on a flat torus manifold', 'create a function that uses FlatTorus logmap to compute the logarithmic map between two points on a torus', 'test the FlatTorus projx method to project points onto the [0, 2pi] torus subspace', 'review the FlatTorus proju method to understand tangent space projection on the flat torus manifold', 'summarize the FlatTorus class and its manifold operations for flow matching on toroidal geometry', 'build a python module that generates a geodesic curve between two points on a manifold', 'create a callable that returns geodesic points at any time t given start and end points', 'test the geodesic function by computing paths on a Euclidean manifold between two tensors', 'review the geodesic function that uses logmap and expmap to compute manifold geodesics', 'summarize the geodesic API that takes a manifold, start point, and end point to return a path function']
```

Usage

```
{'build_sphere_expmap': 'build a python module to compute the exponential map on a hypersphere manifold using Sphere.expmap', 'build_sphere_logmap': 'build a python module to compute the logarithmic map between two points on a hypersphere using Sphere.logmap', 'build_sphere_projx': 'build a python module to project arbitrary vectors onto the hypersphere surface using Sphere.projx', 'build_sphere_proju': 'build a python module to project a tangent vector onto the tangent space of a hypersphere using Sphere.proju', 'build_sphere_dist': 'build a python module to compute the geodesic distance between two points on a hypersphere using Sphere.dist'}
```

## File: facebookresearch_flowmatching/flow_matching/utils/manifolds/torus.py

Prompts

```
['build a python module that uses Euclidean expmap to transport a point along a tangent vector', 'build a python module that uses Euclidean logmap to compute the tangent vector between two points', 'build a custom Manifold subclass implementing expmap, logmap, projx, and proju abstract methods', 'test the Euclidean manifold projx method to verify it returns the input point unchanged', 'test the Euclidean manifold proju method to verify it returns the input vector unchanged', 'build a python module to compute the exponential map on a hypersphere manifold using Sphere.expmap', 'build a python module to compute the logarithmic map between two points on a hypersphere using Sphere.logmap', 'build a python module to project arbitrary vectors onto the hypersphere surface using Sphere.projx', 'build a python module to project a tangent vector onto the tangent space of a hypersphere using Sphere.proju', 'build a python module to compute the geodesic distance between two points on a hypersphere using Sphere.dist', 'build a python module that uses FlatTorus expmap to compute exponential map on a flat torus manifold', 'create a function that uses FlatTorus logmap to compute the logarithmic map between two points on a torus', 'test the FlatTorus projx method to project points onto the [0, 2pi] torus subspace', 'review the FlatTorus proju method to understand tangent space projection on the flat torus manifold', 'summarize the FlatTorus class and its manifold operations for flow matching on toroidal geometry', 'build a python module that generates a geodesic curve between two points on a manifold', 'create a callable that returns geodesic points at any time t given start and end points', 'test the geodesic function by computing paths on a Euclidean manifold between two tensors', 'review the geodesic function that uses logmap and expmap to compute manifold geodesics', 'summarize the geodesic API that takes a manifold, start point, and end point to return a path function']
```

Usage

```
{'build_flat_torus_expmap': 'build a python module that uses FlatTorus expmap to compute exponential map on a flat torus manifold', 'create_flat_torus_logmap': 'create a function that uses FlatTorus logmap to compute the logarithmic map between two points on a torus', 'test_flat_torus_projx': 'test the FlatTorus projx method to project points onto the [0, 2pi] torus subspace', 'review_flat_torus_proju': 'review the FlatTorus proju method to understand tangent space projection on the flat torus manifold', 'summarize_flat_torus_class': 'summarize the FlatTorus class and its manifold operations for flow matching on toroidal geometry'}
```

## File: facebookresearch_flowmatching/flow_matching/utils/manifolds/utils.py

Prompts

```
['build a python module that uses Euclidean expmap to transport a point along a tangent vector', 'build a python module that uses Euclidean logmap to compute the tangent vector between two points', 'build a custom Manifold subclass implementing expmap, logmap, projx, and proju abstract methods', 'test the Euclidean manifold projx method to verify it returns the input point unchanged', 'test the Euclidean manifold proju method to verify it returns the input vector unchanged', 'build a python module to compute the exponential map on a hypersphere manifold using Sphere.expmap', 'build a python module to compute the logarithmic map between two points on a hypersphere using Sphere.logmap', 'build a python module to project arbitrary vectors onto the hypersphere surface using Sphere.projx', 'build a python module to project a tangent vector onto the tangent space of a hypersphere using Sphere.proju', 'build a python module to compute the geodesic distance between two points on a hypersphere using Sphere.dist', 'build a python module that uses FlatTorus expmap to compute exponential map on a flat torus manifold', 'create a function that uses FlatTorus logmap to compute the logarithmic map between two points on a torus', 'test the FlatTorus projx method to project points onto the [0, 2pi] torus subspace', 'review the FlatTorus proju method to understand tangent space projection on the flat torus manifold', 'summarize the FlatTorus class and its manifold operations for flow matching on toroidal geometry', 'build a python module that generates a geodesic curve between two points on a manifold', 'create a callable that returns geodesic points at any time t given start and end points', 'test the geodesic function by computing paths on a Euclidean manifold between two tensors', 'review the geodesic function that uses logmap and expmap to compute manifold geodesics', 'summarize the geodesic API that takes a manifold, start point, and end point to return a path function']
```

Usage

```
{'build_geodesic_path': 'build a python module that generates a geodesic curve between two points on a manifold', 'create_geodesic_callable': 'create a callable that returns geodesic points at any time t given start and end points', 'test_geodesic_function': 'test the geodesic function by computing paths on a Euclidean manifold between two tensors', 'review_geodesic_implementation': 'review the geodesic function that uses logmap and expmap to compute manifold geodesics', 'summarize_geodesic_api': 'summarize the geodesic API that takes a manifold, start point, and end point to return a path function'}
```

