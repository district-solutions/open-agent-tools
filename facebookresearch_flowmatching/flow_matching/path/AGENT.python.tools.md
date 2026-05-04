# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/flow_matching/path/affine.py

Prompts

```
['build a python module that creates an AffineProbPath with a scheduler and samples conditional paths', 'build a python module that creates a CondOTProbPath for conditional optimal transport probability paths', 'test the AffineProbPath sample method to verify it returns correct PathSample with x_t and dx_t', 'test the target_to_velocity method to convert x_1 representation to velocity using scheduler parameters', 'test the epsilon_to_velocity method to convert noise representation to velocity using scheduler parameters', 'create a GeodesicProbPath instance with a ConvexScheduler and Manifold for Riemannian flow matching', 'sample from a GeodesicProbPath given source x_0, target x_1, and time tensor t', 'review the GeodesicProbPath class and its geodesic interpolation using exp and log maps on a manifold', 'test the GeodesicProbPath sample method to verify it returns a PathSample with correct x_t and dx_t', 'build a Riemannian flow matching training loop using GeodesicProbPath with a FlatTorus or Sphere manifold', 'build a MixtureDiscreteProbPath instance with a ConvexScheduler for discrete probability path sampling', 'create discrete path samples by calling sample on MixtureDiscreteProbPath with source and target tensors', 'test the posterior_to_velocity method to convert factorized posterior logits to velocity tensors', 'review the MixtureDiscreteProbPath class and its discrete probability path sampling logic', 'refactor the posterior_to_velocity method to support custom scheduler output formats', 'implement a subclass of ProbPath that overrides the abstract sample method for flow matching', 'call ProbPath sample method with x_0, x_1, and t tensors to get a PathSample', 'use assert_sample_shape to validate that time tensor shape matches batch size of x_0 and x_1', 'review the ProbPath abstract class design for flow matching probability path transformations', 'refactor a ProbPath subclass sample method to return PathSample with x_t and dx_t tensors']
```

Usage

```
{'build_affine_prob_path': 'build a python module that creates an AffineProbPath with a scheduler and samples conditional paths', 'build_cond_ot_prob_path': 'build a python module that creates a CondOTProbPath for conditional optimal transport probability paths', 'test_sample_method': 'test the AffineProbPath sample method to verify it returns correct PathSample with x_t and dx_t', 'test_target_to_velocity': 'test the target_to_velocity method to convert x_1 representation to velocity using scheduler parameters', 'test_epsilon_to_velocity': 'test the epsilon_to_velocity method to convert noise representation to velocity using scheduler parameters'}
```

## File: facebookresearch_flowmatching/flow_matching/path/geodesic.py

Prompts

```
['build a python module that creates an AffineProbPath with a scheduler and samples conditional paths', 'build a python module that creates a CondOTProbPath for conditional optimal transport probability paths', 'test the AffineProbPath sample method to verify it returns correct PathSample with x_t and dx_t', 'test the target_to_velocity method to convert x_1 representation to velocity using scheduler parameters', 'test the epsilon_to_velocity method to convert noise representation to velocity using scheduler parameters', 'create a GeodesicProbPath instance with a ConvexScheduler and Manifold for Riemannian flow matching', 'sample from a GeodesicProbPath given source x_0, target x_1, and time tensor t', 'review the GeodesicProbPath class and its geodesic interpolation using exp and log maps on a manifold', 'test the GeodesicProbPath sample method to verify it returns a PathSample with correct x_t and dx_t', 'build a Riemannian flow matching training loop using GeodesicProbPath with a FlatTorus or Sphere manifold', 'build a MixtureDiscreteProbPath instance with a ConvexScheduler for discrete probability path sampling', 'create discrete path samples by calling sample on MixtureDiscreteProbPath with source and target tensors', 'test the posterior_to_velocity method to convert factorized posterior logits to velocity tensors', 'review the MixtureDiscreteProbPath class and its discrete probability path sampling logic', 'refactor the posterior_to_velocity method to support custom scheduler output formats', 'implement a subclass of ProbPath that overrides the abstract sample method for flow matching', 'call ProbPath sample method with x_0, x_1, and t tensors to get a PathSample', 'use assert_sample_shape to validate that time tensor shape matches batch size of x_0 and x_1', 'review the ProbPath abstract class design for flow matching probability path transformations', 'refactor a ProbPath subclass sample method to return PathSample with x_t and dx_t tensors']
```

Usage

```
{'create_geodesic_prob_path': 'create a GeodesicProbPath instance with a ConvexScheduler and Manifold for Riemannian flow matching', 'sample_geodesic_path': 'sample from a GeodesicProbPath given source x_0, target x_1, and time tensor t', 'review_geodesic_prob_path_class': 'review the GeodesicProbPath class and its geodesic interpolation using exp and log maps on a manifold', 'test_geodesic_sample_method': 'test the GeodesicProbPath sample method to verify it returns a PathSample with correct x_t and dx_t', 'build_riemannian_flow_matching': 'build a Riemannian flow matching training loop using GeodesicProbPath with a FlatTorus or Sphere manifold'}
```

## File: facebookresearch_flowmatching/flow_matching/path/mixture.py

Prompts

```
['build a python module that creates an AffineProbPath with a scheduler and samples conditional paths', 'build a python module that creates a CondOTProbPath for conditional optimal transport probability paths', 'test the AffineProbPath sample method to verify it returns correct PathSample with x_t and dx_t', 'test the target_to_velocity method to convert x_1 representation to velocity using scheduler parameters', 'test the epsilon_to_velocity method to convert noise representation to velocity using scheduler parameters', 'create a GeodesicProbPath instance with a ConvexScheduler and Manifold for Riemannian flow matching', 'sample from a GeodesicProbPath given source x_0, target x_1, and time tensor t', 'review the GeodesicProbPath class and its geodesic interpolation using exp and log maps on a manifold', 'test the GeodesicProbPath sample method to verify it returns a PathSample with correct x_t and dx_t', 'build a Riemannian flow matching training loop using GeodesicProbPath with a FlatTorus or Sphere manifold', 'build a MixtureDiscreteProbPath instance with a ConvexScheduler for discrete probability path sampling', 'create discrete path samples by calling sample on MixtureDiscreteProbPath with source and target tensors', 'test the posterior_to_velocity method to convert factorized posterior logits to velocity tensors', 'review the MixtureDiscreteProbPath class and its discrete probability path sampling logic', 'refactor the posterior_to_velocity method to support custom scheduler output formats', 'implement a subclass of ProbPath that overrides the abstract sample method for flow matching', 'call ProbPath sample method with x_0, x_1, and t tensors to get a PathSample', 'use assert_sample_shape to validate that time tensor shape matches batch size of x_0 and x_1', 'review the ProbPath abstract class design for flow matching probability path transformations', 'refactor a ProbPath subclass sample method to return PathSample with x_t and dx_t tensors']
```

Usage

```
{'build_MixtureDiscreteProbPath': 'build a MixtureDiscreteProbPath instance with a ConvexScheduler for discrete probability path sampling', 'create_sample_discrete_path': 'create discrete path samples by calling sample on MixtureDiscreteProbPath with source and target tensors', 'test_posterior_to_velocity': 'test the posterior_to_velocity method to convert factorized posterior logits to velocity tensors', 'review_MixtureDiscreteProbPath_class': 'review the MixtureDiscreteProbPath class and its discrete probability path sampling logic', 'refactor_posterior_to_velocity': 'refactor the posterior_to_velocity method to support custom scheduler output formats'}
```

## File: facebookresearch_flowmatching/flow_matching/path/path.py

Prompts

```
['build a python module that creates an AffineProbPath with a scheduler and samples conditional paths', 'build a python module that creates a CondOTProbPath for conditional optimal transport probability paths', 'test the AffineProbPath sample method to verify it returns correct PathSample with x_t and dx_t', 'test the target_to_velocity method to convert x_1 representation to velocity using scheduler parameters', 'test the epsilon_to_velocity method to convert noise representation to velocity using scheduler parameters', 'create a GeodesicProbPath instance with a ConvexScheduler and Manifold for Riemannian flow matching', 'sample from a GeodesicProbPath given source x_0, target x_1, and time tensor t', 'review the GeodesicProbPath class and its geodesic interpolation using exp and log maps on a manifold', 'test the GeodesicProbPath sample method to verify it returns a PathSample with correct x_t and dx_t', 'build a Riemannian flow matching training loop using GeodesicProbPath with a FlatTorus or Sphere manifold', 'build a MixtureDiscreteProbPath instance with a ConvexScheduler for discrete probability path sampling', 'create discrete path samples by calling sample on MixtureDiscreteProbPath with source and target tensors', 'test the posterior_to_velocity method to convert factorized posterior logits to velocity tensors', 'review the MixtureDiscreteProbPath class and its discrete probability path sampling logic', 'refactor the posterior_to_velocity method to support custom scheduler output formats', 'implement a subclass of ProbPath that overrides the abstract sample method for flow matching', 'call ProbPath sample method with x_0, x_1, and t tensors to get a PathSample', 'use assert_sample_shape to validate that time tensor shape matches batch size of x_0 and x_1', 'review the ProbPath abstract class design for flow matching probability path transformations', 'refactor a ProbPath subclass sample method to return PathSample with x_t and dx_t tensors']
```

Usage

```
{'implement_probpath_subclass': 'implement a subclass of ProbPath that overrides the abstract sample method for flow matching', 'sample_conditional_path': 'call ProbPath sample method with x_0, x_1, and t tensors to get a PathSample', 'validate_sample_shapes': 'use assert_sample_shape to validate that time tensor shape matches batch size of x_0 and x_1', 'review_probpath_abstraction': 'review the ProbPath abstract class design for flow matching probability path transformations', 'refactor_probpath_sample': 'refactor a ProbPath subclass sample method to return PathSample with x_t and dx_t tensors'}
```

