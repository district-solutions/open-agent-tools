# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/svm/tests/test_bounds.py

Prompts

```
['test the l1_min_c function with different X containers, loss types, and intercept settings', 'test that l1_min_c raises ValueError for ill-posed inputs', 'test that bounded_rand_int_wrap generates values within range without seeding', 'test that set_seed_wrap produces deterministic bounded_rand_int_wrap results', 'test that bounded_rand_int_wrap follows a uniform distribution using Kolmogorov-Smirnov tests', 'test the SVM SVC class with sparse input matrices across linear, poly, rbf, and sigmoid kernels', 'test the SVM LinearSVC class with sparse input matrices and verify coefficient equality', 'test the SVM decision_function method with sparse CSR input matrices', 'test the SVM OneClassSVM class with sparse input matrices and various kernels', 'test SVM class weights and sample weights with sparse LIL and CSR input matrices', 'test the svm.SVC classifier with linear and rbf kernels on iris dataset', 'test the svm.SVR regressor with linear and rbf kernels on diabetes dataset', 'test the svm.LinearSVC with various penalty, loss, and dual parameter combinations', 'test the svm.OneClassSVM for novelty detection on toy and generated datasets', 'test weighted SVM training with sample_weight across SVC, SVR, and LinearSVC']
```

Usage

```
{'test_l1_min_c': 'test the l1_min_c function with different X containers, loss types, and intercept settings', 'test_ill_posed_min_c': 'test that l1_min_c raises ValueError for ill-posed inputs', 'test_newrand_default': 'test that bounded_rand_int_wrap generates values within range without seeding', 'test_newrand_set_seed': 'test that set_seed_wrap produces deterministic bounded_rand_int_wrap results', 'test_newrand_bounded_rand_int': 'test that bounded_rand_int_wrap follows a uniform distribution using Kolmogorov-Smirnov tests'}
```

## File: scikit-learn_scikit-learn/sklearn/svm/tests/test_sparse.py

Prompts

```
['test the l1_min_c function with different X containers, loss types, and intercept settings', 'test that l1_min_c raises ValueError for ill-posed inputs', 'test that bounded_rand_int_wrap generates values within range without seeding', 'test that set_seed_wrap produces deterministic bounded_rand_int_wrap results', 'test that bounded_rand_int_wrap follows a uniform distribution using Kolmogorov-Smirnov tests', 'test the SVM SVC class with sparse input matrices across linear, poly, rbf, and sigmoid kernels', 'test the SVM LinearSVC class with sparse input matrices and verify coefficient equality', 'test the SVM decision_function method with sparse CSR input matrices', 'test the SVM OneClassSVM class with sparse input matrices and various kernels', 'test SVM class weights and sample weights with sparse LIL and CSR input matrices', 'test the svm.SVC classifier with linear and rbf kernels on iris dataset', 'test the svm.SVR regressor with linear and rbf kernels on diabetes dataset', 'test the svm.LinearSVC with various penalty, loss, and dual parameter combinations', 'test the svm.OneClassSVM for novelty detection on toy and generated datasets', 'test weighted SVM training with sample_weight across SVC, SVR, and LinearSVC']
```

Usage

```
{'test_svc_sparse': 'test the SVM SVC class with sparse input matrices across linear, poly, rbf, and sigmoid kernels', 'test_linearsvc_sparse': 'test the SVM LinearSVC class with sparse input matrices and verify coefficient equality', 'test_sparse_decision_function': 'test the SVM decision_function method with sparse CSR input matrices', 'test_sparse_oneclasssvm': 'test the SVM OneClassSVM class with sparse input matrices and various kernels', 'test_weight_sparse': 'test SVM class weights and sample weights with sparse LIL and CSR input matrices'}
```

## File: scikit-learn_scikit-learn/sklearn/svm/tests/test_svm.py

Prompts

```
['test the l1_min_c function with different X containers, loss types, and intercept settings', 'test that l1_min_c raises ValueError for ill-posed inputs', 'test that bounded_rand_int_wrap generates values within range without seeding', 'test that set_seed_wrap produces deterministic bounded_rand_int_wrap results', 'test that bounded_rand_int_wrap follows a uniform distribution using Kolmogorov-Smirnov tests', 'test the SVM SVC class with sparse input matrices across linear, poly, rbf, and sigmoid kernels', 'test the SVM LinearSVC class with sparse input matrices and verify coefficient equality', 'test the SVM decision_function method with sparse CSR input matrices', 'test the SVM OneClassSVM class with sparse input matrices and various kernels', 'test SVM class weights and sample weights with sparse LIL and CSR input matrices', 'test the svm.SVC classifier with linear and rbf kernels on iris dataset', 'test the svm.SVR regressor with linear and rbf kernels on diabetes dataset', 'test the svm.LinearSVC with various penalty, loss, and dual parameter combinations', 'test the svm.OneClassSVM for novelty detection on toy and generated datasets', 'test weighted SVM training with sample_weight across SVC, SVR, and LinearSVC']
```

Usage

```
{'test_svc_classification': 'test the svm.SVC classifier with linear and rbf kernels on iris dataset', 'test_svr_regression': 'test the svm.SVR regressor with linear and rbf kernels on diabetes dataset', 'test_linearsvc_parameters': 'test the svm.LinearSVC with various penalty, loss, and dual parameter combinations', 'test_oneclass_svm': 'test the svm.OneClassSVM for novelty detection on toy and generated datasets', 'test_sample_weight_svm': 'test weighted SVM training with sample_weight across SVC, SVR, and LinearSVC'}
```

