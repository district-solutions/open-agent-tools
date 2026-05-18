# Agent Python Tools

- repo: facebookresearch/mhr
- repo_uri: https://github.com/facebookresearch/mhr

## File: facebookresearch_mhr/tests/test_basic.py

Prompts

```
['test that the mhr module has a valid non-empty __version__ string attribute', 'run the basic import test to verify mhr module version exists and is a string', 'review the test_import function that asserts mhr has a valid __version__ attribute', 'summarize the test_basic module which contains a single import smoke test for mhr', 'refactor the test_import function to add additional assertions for the mhr module', 'test the MHR model forward pass with pose correctives applied and verify output batch dimensions', 'test the MHR model forward pass without loading a pose correctives model and verify output shapes', 'test the MHR model forward pass with pose correctives loaded but disabled at inference time', 'test the MHR model forward pass with both pose correctives and facial expressions disabled', 'build a dummy PyTorch pose correctives model that returns ones tensor for testing MHR forward calls']
```

Usage

```
{'test_import_mhr_version': 'test that the mhr module has a valid non-empty __version__ string attribute', 'run_test_basic_import': 'run the basic import test to verify mhr module version exists and is a string', 'review_test_import_function': 'review the test_import function that asserts mhr has a valid __version__ attribute', 'summarize_test_basic_module': 'summarize the test_basic module which contains a single import smoke test for mhr', 'refactor_test_import_assertions': 'refactor the test_import function to add additional assertions for the mhr module'}
```

## File: facebookresearch_mhr/tests/test_mhr.py

Prompts

```
['test that the mhr module has a valid non-empty __version__ string attribute', 'run the basic import test to verify mhr module version exists and is a string', 'review the test_import function that asserts mhr has a valid __version__ attribute', 'summarize the test_basic module which contains a single import smoke test for mhr', 'refactor the test_import function to add additional assertions for the mhr module', 'test the MHR model forward pass with pose correctives applied and verify output batch dimensions', 'test the MHR model forward pass without loading a pose correctives model and verify output shapes', 'test the MHR model forward pass with pose correctives loaded but disabled at inference time', 'test the MHR model forward pass with both pose correctives and facial expressions disabled', 'build a dummy PyTorch pose correctives model that returns ones tensor for testing MHR forward calls']
```

Usage

```
{'test_MHR_model_with_pose_correctives': 'test the MHR model forward pass with pose correctives applied and verify output batch dimensions', 'test_MHR_model_without_pose_correctives': 'test the MHR model forward pass without loading a pose correctives model and verify output shapes', 'test_MHR_model_without_applying_correctives': 'test the MHR model forward pass with pose correctives loaded but disabled at inference time', 'test_MHR_model_without_correctives_and_face_expr': 'test the MHR model forward pass with both pose correctives and facial expressions disabled', 'build_MHRPoseCorrectivesModelDummy': 'build a dummy PyTorch pose correctives model that returns ones tensor for testing MHR forward calls'}
```

