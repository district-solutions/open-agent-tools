# Agent Python Tools

- repo: facebookresearch/flowmatching
- repo_uri: https://github.com/facebookresearch/flow_matching

## File: facebookresearch_flowmatching/tests/solver/test_discrete_solver.py

Prompts

```
['test the MixtureDiscreteEulerSolver initialization with model, path, vocabulary size, and source distribution', 'test the MixtureDiscreteEulerSolver sample method with step size and time grid parameters', 'test the MixtureDiscreteEulerSolver sample method with divergence-free term as scalar or callable', 'test the MixtureDiscreteEulerSolver sample method using a linspace time grid with return intermediates', 'test the DummyModel forward method that returns stacked zero and one tensors', 'test the ODESolver sample method with euler, dopri5, midpoint, and heun3 integration methods', 'test the ODESolver compute_likelihood method with exact and approximate divergence options', 'test the ODESolver sample method with enable_grad to verify gradient flow through the solver', 'test the ConstantVelocityModel forward method with a learnable constant velocity parameter', 'create a RiemannianODESolver with a Sphere manifold and a velocity model', 'sample from the solver using Euler integration with a given step size and time grid', 'sample from the solver using RK4 integration over a specified time grid', 'sample from the solver and return intermediate states at each time grid point', 'sample from the solver with gradient tracking enabled for backpropagation through the ODE solve']
```

Usage

```
{'test_MixtureDiscreteEulerSolver_init': 'test the MixtureDiscreteEulerSolver initialization with model, path, vocabulary size, and source distribution', 'test_MixtureDiscreteEulerSolver_sample': 'test the MixtureDiscreteEulerSolver sample method with step size and time grid parameters', 'test_MixtureDiscreteEulerSolver_sample_div_free': 'test the MixtureDiscreteEulerSolver sample method with divergence-free term as scalar or callable', 'test_MixtureDiscreteEulerSolver_sample_time_grid': 'test the MixtureDiscreteEulerSolver sample method using a linspace time grid with return intermediates', 'test_DummyModel_forward': 'test the DummyModel forward method that returns stacked zero and one tensors'}
```

## File: facebookresearch_flowmatching/tests/solver/test_ode_solver.py

Prompts

```
['test the MixtureDiscreteEulerSolver initialization with model, path, vocabulary size, and source distribution', 'test the MixtureDiscreteEulerSolver sample method with step size and time grid parameters', 'test the MixtureDiscreteEulerSolver sample method with divergence-free term as scalar or callable', 'test the MixtureDiscreteEulerSolver sample method using a linspace time grid with return intermediates', 'test the DummyModel forward method that returns stacked zero and one tensors', 'test the ODESolver sample method with euler, dopri5, midpoint, and heun3 integration methods', 'test the ODESolver compute_likelihood method with exact and approximate divergence options', 'test the ODESolver sample method with enable_grad to verify gradient flow through the solver', 'test the ConstantVelocityModel forward method with a learnable constant velocity parameter', 'create a RiemannianODESolver with a Sphere manifold and a velocity model', 'sample from the solver using Euler integration with a given step size and time grid', 'sample from the solver using RK4 integration over a specified time grid', 'sample from the solver and return intermediate states at each time grid point', 'sample from the solver with gradient tracking enabled for backpropagation through the ODE solve']
```

Usage

```
{'test_ODESolver_sample': 'test the ODESolver sample method with euler, dopri5, midpoint, and heun3 integration methods', 'test_ODESolver_compute_likelihood': 'test the ODESolver compute_likelihood method with exact and approximate divergence options', 'test_ODESolver_gradients': 'test the ODESolver sample method with enable_grad to verify gradient flow through the solver', 'test_DummyModel_forward': 'test the DummyModel forward method that returns a polynomial velocity field of 3t squared', 'test_ConstantVelocityModel_forward': 'test the ConstantVelocityModel forward method with a learnable constant velocity parameter'}
```

## File: facebookresearch_flowmatching/tests/solver/test_riemannian_ode_solver.py

Prompts

```
['test the MixtureDiscreteEulerSolver initialization with model, path, vocabulary size, and source distribution', 'test the MixtureDiscreteEulerSolver sample method with step size and time grid parameters', 'test the MixtureDiscreteEulerSolver sample method with divergence-free term as scalar or callable', 'test the MixtureDiscreteEulerSolver sample method using a linspace time grid with return intermediates', 'test the DummyModel forward method that returns stacked zero and one tensors', 'test the ODESolver sample method with euler, dopri5, midpoint, and heun3 integration methods', 'test the ODESolver compute_likelihood method with exact and approximate divergence options', 'test the ODESolver sample method with enable_grad to verify gradient flow through the solver', 'test the ConstantVelocityModel forward method with a learnable constant velocity parameter', 'create a RiemannianODESolver with a Sphere manifold and a velocity model', 'sample from the solver using Euler integration with a given step size and time grid', 'sample from the solver using RK4 integration over a specified time grid', 'sample from the solver and return intermediate states at each time grid point', 'sample from the solver with gradient tracking enabled for backpropagation through the ODE solve']
```

Usage

```
{'create_riemannian_ode_solver': 'create a RiemannianODESolver with a Sphere manifold and a velocity model', 'sample_euler_integration': 'sample from the solver using Euler integration with a given step size and time grid', 'sample_rk4_integration': 'sample from the solver using RK4 integration over a specified time grid', 'sample_return_intermediates': 'sample from the solver and return intermediate states at each time grid point', 'sample_with_gradient': 'sample from the solver with gradient tracking enabled for backpropagation through the ODE solve'}
```

