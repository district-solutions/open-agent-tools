# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/semi_supervised/tests/test_label_propagation.py

Prompts

```
['test the LabelPropagation estimator fit method with transduction and verify predicted label assignment', 'test the LabelSpreading estimator closed-form solution against expected label distributions', 'test LabelPropagation and LabelSpreading with sparse CSR and CSC input matrices of various dtypes', 'test that ConvergenceWarning is raised when max_iter is reached without convergence', 'test predict and predict_proba with a custom sparse callable kernel on LabelPropagation and LabelSpreading', 'test SelfTrainingClassifier performs semi-supervised classification with missing labels', 'test SelfTrainingClassifier uses k_best criterion to label top-k most confident unlabeled samples per iteration', 'test SelfTrainingClassifier uses threshold criterion to label samples exceeding confidence threshold', 'test SelfTrainingClassifier verbose output logs iteration progress with number of new labels added', 'test SelfTrainingClassifier passes sample_weight and custom metadata to base estimator via routing']
```

Usage

```
{'test_label_propagation_fit_transduction': 'test the LabelPropagation estimator fit method with transduction and verify predicted label assignment', 'test_label_spreading_closed_form': 'test the LabelSpreading estimator closed-form solution against expected label distributions', 'test_sparse_input_types': 'test LabelPropagation and LabelSpreading with sparse CSR and CSC input matrices of various dtypes', 'test_convergence_warning': 'test that ConvergenceWarning is raised when max_iter is reached without convergence', 'test_predict_sparse_callable_kernel': 'test predict and predict_proba with a custom sparse callable kernel on LabelPropagation and LabelSpreading'}
```

## File: scikit-learn_scikit-learn/sklearn/semi_supervised/tests/test_self_training.py

Prompts

```
['test the LabelPropagation estimator fit method with transduction and verify predicted label assignment', 'test the LabelSpreading estimator closed-form solution against expected label distributions', 'test LabelPropagation and LabelSpreading with sparse CSR and CSC input matrices of various dtypes', 'test that ConvergenceWarning is raised when max_iter is reached without convergence', 'test predict and predict_proba with a custom sparse callable kernel on LabelPropagation and LabelSpreading', 'test SelfTrainingClassifier performs semi-supervised classification with missing labels', 'test SelfTrainingClassifier uses k_best criterion to label top-k most confident unlabeled samples per iteration', 'test SelfTrainingClassifier uses threshold criterion to label samples exceeding confidence threshold', 'test SelfTrainingClassifier verbose output logs iteration progress with number of new labels added', 'test SelfTrainingClassifier passes sample_weight and custom metadata to base estimator via routing']
```

Usage

```
{'test_SelfTrainingClassifier_classification': 'test SelfTrainingClassifier performs semi-supervised classification with missing labels', 'test_SelfTrainingClassifier_k_best': 'test SelfTrainingClassifier uses k_best criterion to label top-k most confident unlabeled samples per iteration', 'test_SelfTrainingClassifier_threshold': 'test SelfTrainingClassifier uses threshold criterion to label samples exceeding confidence threshold', 'test_SelfTrainingClassifier_verbose': 'test SelfTrainingClassifier verbose output logs iteration progress with number of new labels added', 'test_SelfTrainingClassifier_metadata_routing': 'test SelfTrainingClassifier passes sample_weight and custom metadata to base estimator via routing'}
```

