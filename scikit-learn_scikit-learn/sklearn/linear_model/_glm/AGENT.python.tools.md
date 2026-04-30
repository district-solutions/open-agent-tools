# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/linear_model/_glm/_newton_solver.py

Prompts

```
['create a NewtonSolver instance to optimize GLM coefficients with custom loss and regularization', 'run NewtonSolver.solve to find optimal coefficients for a generalized linear model', 'build a NewtonCholeskySolver with Cholesky-based inner solve for GLM optimization', 'run NewtonCholeskySolver.inner_solve to compute the Newton step using Cholesky decomposition', 'review NewtonSolver.line_search backtracking line search with Armijo sufficient decrease condition', 'create a TweedieRegressor GLM with configurable power, link, and alpha to model Normal, Poisson, Gamma, or Inverse Gaussian distributions', 'create a PoissonRegressor GLM with log link for modeling count data with L2 regularization', 'create a GammaRegressor GLM with log link for modeling positive continuous data with L2 regularization', 'fit a Generalized Linear Model using lbfgs or newton-cholesky solver with sample weights and L2 regularization', 'predict using a fitted GLM by computing the linear predictor and applying the inverse link function']
```

Usage

```
{'create_NewtonSolver': 'create a NewtonSolver instance to optimize GLM coefficients with custom loss and regularization', 'run_NewtonSolver_solve': 'run NewtonSolver.solve to find optimal coefficients for a generalized linear model', 'build_NewtonCholeskySolver': 'build a NewtonCholeskySolver with Cholesky-based inner solve for GLM optimization', 'run_NewtonCholeskySolver_inner_solve': 'run NewtonCholeskySolver.inner_solve to compute the Newton step using Cholesky decomposition', 'review_NewtonSolver_line_search': 'review NewtonSolver.line_search backtracking line search with Armijo sufficient decrease condition'}
```

## File: scikit-learn_scikit-learn/sklearn/linear_model/_glm/glm.py

Prompts

```
['create a NewtonSolver instance to optimize GLM coefficients with custom loss and regularization', 'run NewtonSolver.solve to find optimal coefficients for a generalized linear model', 'build a NewtonCholeskySolver with Cholesky-based inner solve for GLM optimization', 'run NewtonCholeskySolver.inner_solve to compute the Newton step using Cholesky decomposition', 'review NewtonSolver.line_search backtracking line search with Armijo sufficient decrease condition', 'create a TweedieRegressor GLM with configurable power, link, and alpha to model Normal, Poisson, Gamma, or Inverse Gaussian distributions', 'create a PoissonRegressor GLM with log link for modeling count data with L2 regularization', 'create a GammaRegressor GLM with log link for modeling positive continuous data with L2 regularization', 'fit a Generalized Linear Model using lbfgs or newton-cholesky solver with sample weights and L2 regularization', 'predict using a fitted GLM by computing the linear predictor and applying the inverse link function']
```

Usage

```
{'create_TweedieRegressor': 'create a TweedieRegressor GLM with configurable power, link, and alpha to model Normal, Poisson, Gamma, or Inverse Gaussian distributions', 'create_PoissonRegressor': 'create a PoissonRegressor GLM with log link for modeling count data with L2 regularization', 'create_GammaRegressor': 'create a GammaRegressor GLM with log link for modeling positive continuous data with L2 regularization', 'fit_GLM_model': 'fit a Generalized Linear Model using lbfgs or newton-cholesky solver with sample weights and L2 regularization', 'predict_GLM_model': 'predict using a fitted GLM by computing the linear predictor and applying the inverse link function'}
```

