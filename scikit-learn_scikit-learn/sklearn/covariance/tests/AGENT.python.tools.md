# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/covariance/tests/test_covariance.py

Prompts

```
['test EmpiricalCovariance module to fit covariance from data and compute Mahalanobis distances', 'test LedoitWolf module to compute Ledoit-Wolf shrinkage coefficient and shrunk covariance estimate', 'test OAS module to compute Oracle Approximating Shrinkage covariance estimate', 'test ShrunkCovariance module for consistency with the shrunk_covariance function', 'test EmpiricalCovariance validates input features for mahalanobis distance computation', 'test the EllipticEnvelope class fit, predict, score_samples, decision_function, and mahalanobis methods', 'test that score_samples equals decision_function plus offset_ for EllipticEnvelope', 'create an EllipticEnvelope outlier detector with contamination parameter for robust covariance estimation', 'test that EllipticEnvelope raises NotFittedError when predict or decision_function is called before fit', 'test that EllipticEnvelope score returns accuracy based on inlier prediction ratio', 'test the graphical_lasso function with cd and lars solvers on sparse multivariate normal data', 'test the GraphicalLasso estimator fit and score methods on generated sample data', 'test the GraphicalLassoCV cross-validated estimator with configurable alphas and cv splits', 'test graphical_lasso returns inverse empirical covariance when alpha equals zero', 'test GraphicalLassoCV cv_results_ contains correct alphas, split scores, mean and std fields', 'test the MinCovDet class with the FastMCD algorithm on datasets of various sizes and contamination levels', 'test that fast_mcd raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet.fit raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet does not underestimate the empirical variance on Gaussian data', 'test that MinCovDet raises ValueError with informative message when support covariance is zero']
```

Usage

```
{'test_empirical_covariance_fit': 'test EmpiricalCovariance module to fit covariance from data and compute Mahalanobis distances', 'test_ledoit_wolf_shrinkage': 'test LedoitWolf module to compute Ledoit-Wolf shrinkage coefficient and shrunk covariance estimate', 'test_oas_estimator': 'test OAS module to compute Oracle Approximating Shrinkage covariance estimate', 'test_shrunk_covariance_consistency': 'test ShrunkCovariance module for consistency with the shrunk_covariance function', 'test_empirical_covariance_mahalanobis_validation': 'test EmpiricalCovariance validates input features for mahalanobis distance computation'}
```

## File: scikit-learn_scikit-learn/sklearn/covariance/tests/test_elliptic_envelope.py

Prompts

```
['test EmpiricalCovariance module to fit covariance from data and compute Mahalanobis distances', 'test LedoitWolf module to compute Ledoit-Wolf shrinkage coefficient and shrunk covariance estimate', 'test OAS module to compute Oracle Approximating Shrinkage covariance estimate', 'test ShrunkCovariance module for consistency with the shrunk_covariance function', 'test EmpiricalCovariance validates input features for mahalanobis distance computation', 'test the EllipticEnvelope class fit, predict, score_samples, decision_function, and mahalanobis methods', 'test that score_samples equals decision_function plus offset_ for EllipticEnvelope', 'create an EllipticEnvelope outlier detector with contamination parameter for robust covariance estimation', 'test that EllipticEnvelope raises NotFittedError when predict or decision_function is called before fit', 'test that EllipticEnvelope score returns accuracy based on inlier prediction ratio', 'test the graphical_lasso function with cd and lars solvers on sparse multivariate normal data', 'test the GraphicalLasso estimator fit and score methods on generated sample data', 'test the GraphicalLassoCV cross-validated estimator with configurable alphas and cv splits', 'test graphical_lasso returns inverse empirical covariance when alpha equals zero', 'test GraphicalLassoCV cv_results_ contains correct alphas, split scores, mean and std fields', 'test the MinCovDet class with the FastMCD algorithm on datasets of various sizes and contamination levels', 'test that fast_mcd raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet.fit raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet does not underestimate the empirical variance on Gaussian data', 'test that MinCovDet raises ValueError with informative message when support covariance is zero']
```

Usage

```
{'test_elliptic_envelope': 'test the EllipticEnvelope class fit, predict, score_samples, decision_function, and mahalanobis methods', 'test_score_samples': 'test that score_samples equals decision_function plus offset_ for EllipticEnvelope', 'create_EllipticEnvelope': 'create an EllipticEnvelope outlier detector with contamination parameter for robust covariance estimation', 'test_EllipticEnvelope_not_fitted': 'test that EllipticEnvelope raises NotFittedError when predict or decision_function is called before fit', 'test_EllipticEnvelope_score': 'test that EllipticEnvelope score returns accuracy based on inlier prediction ratio'}
```

## File: scikit-learn_scikit-learn/sklearn/covariance/tests/test_graphical_lasso.py

Prompts

```
['test EmpiricalCovariance module to fit covariance from data and compute Mahalanobis distances', 'test LedoitWolf module to compute Ledoit-Wolf shrinkage coefficient and shrunk covariance estimate', 'test OAS module to compute Oracle Approximating Shrinkage covariance estimate', 'test ShrunkCovariance module for consistency with the shrunk_covariance function', 'test EmpiricalCovariance validates input features for mahalanobis distance computation', 'test the EllipticEnvelope class fit, predict, score_samples, decision_function, and mahalanobis methods', 'test that score_samples equals decision_function plus offset_ for EllipticEnvelope', 'create an EllipticEnvelope outlier detector with contamination parameter for robust covariance estimation', 'test that EllipticEnvelope raises NotFittedError when predict or decision_function is called before fit', 'test that EllipticEnvelope score returns accuracy based on inlier prediction ratio', 'test the graphical_lasso function with cd and lars solvers on sparse multivariate normal data', 'test the GraphicalLasso estimator fit and score methods on generated sample data', 'test the GraphicalLassoCV cross-validated estimator with configurable alphas and cv splits', 'test graphical_lasso returns inverse empirical covariance when alpha equals zero', 'test GraphicalLassoCV cv_results_ contains correct alphas, split scores, mean and std fields', 'test the MinCovDet class with the FastMCD algorithm on datasets of various sizes and contamination levels', 'test that fast_mcd raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet.fit raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet does not underestimate the empirical variance on Gaussian data', 'test that MinCovDet raises ValueError with informative message when support covariance is zero']
```

Usage

```
{'test_graphical_lasso_solver': 'test the graphical_lasso function with cd and lars solvers on sparse multivariate normal data', 'test_graphical_lasso_estimator': 'test the GraphicalLasso estimator fit and score methods on generated sample data', 'test_graphical_lasso_cv': 'test the GraphicalLassoCV cross-validated estimator with configurable alphas and cv splits', 'test_graphical_lasso_alpha_zero': 'test graphical_lasso returns inverse empirical covariance when alpha equals zero', 'test_graphical_lasso_cv_scores': 'test GraphicalLassoCV cv_results_ contains correct alphas, split scores, mean and std fields'}
```

## File: scikit-learn_scikit-learn/sklearn/covariance/tests/test_robust_covariance.py

Prompts

```
['test EmpiricalCovariance module to fit covariance from data and compute Mahalanobis distances', 'test LedoitWolf module to compute Ledoit-Wolf shrinkage coefficient and shrunk covariance estimate', 'test OAS module to compute Oracle Approximating Shrinkage covariance estimate', 'test ShrunkCovariance module for consistency with the shrunk_covariance function', 'test EmpiricalCovariance validates input features for mahalanobis distance computation', 'test the EllipticEnvelope class fit, predict, score_samples, decision_function, and mahalanobis methods', 'test that score_samples equals decision_function plus offset_ for EllipticEnvelope', 'create an EllipticEnvelope outlier detector with contamination parameter for robust covariance estimation', 'test that EllipticEnvelope raises NotFittedError when predict or decision_function is called before fit', 'test that EllipticEnvelope score returns accuracy based on inlier prediction ratio', 'test the graphical_lasso function with cd and lars solvers on sparse multivariate normal data', 'test the GraphicalLasso estimator fit and score methods on generated sample data', 'test the GraphicalLassoCV cross-validated estimator with configurable alphas and cv splits', 'test graphical_lasso returns inverse empirical covariance when alpha equals zero', 'test GraphicalLassoCV cv_results_ contains correct alphas, split scores, mean and std fields', 'test the MinCovDet class with the FastMCD algorithm on datasets of various sizes and contamination levels', 'test that fast_mcd raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet.fit raises ValueError when given a 1D array instead of a 2D array', 'test that MinCovDet does not underestimate the empirical variance on Gaussian data', 'test that MinCovDet raises ValueError with informative message when support covariance is zero']
```

Usage

```
{'test_mcd': 'test the MinCovDet class with the FastMCD algorithm on datasets of various sizes and contamination levels', 'test_fast_mcd_on_invalid_input': 'test that fast_mcd raises ValueError when given a 1D array instead of a 2D array', 'test_mcd_class_on_invalid_input': 'test that MinCovDet.fit raises ValueError when given a 1D array instead of a 2D array', 'test_mincovdet_bias_on_normal': 'test that MinCovDet does not underestimate the empirical variance on Gaussian data', 'test_mcd_support_covariance_is_zero': 'test that MinCovDet raises ValueError with informative message when support covariance is zero'}
```

