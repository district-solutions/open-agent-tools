# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/tests/theseus_tests/embodied/motionmodel/test_double_integrator.py

Prompts

```
['test GPCostWeight computes correct sqrt weights for given Q_inv and dt parameters', 'test GPCostWeight copy and deepcopy preserve name and tensor values correctly', 'test GPCostWeight stores Qc_inv and dt as Variable types from inputs', 'test GPMotionModel error vector matches expected position and velocity difference formulas', 'test GPMotionModel jacobians match numeric jacobian computed via finite differences', 'test the Nonholonomic cost function with SE2 pose and velocity vectors using check_jacobians', 'test the Nonholonomic cost function with Vector3 pose representation and validate jacobians', 'test the HingeCost function with configurable limits and threshold values for vector constraints', 'test the HingeCost jacobian output shapes and error tensor dimensions for batch processing', 'test the HingeCost numerical jacobian accuracy with check_jacobians utility and tolerance 1e-5', 'test the QuasiStaticPushingPlanar cost function error computation against expected SE2 values', 'test the QuasiStaticPushingPlanar jacobian computation using numeric jacobian verification', 'create a QuasiStaticPushingPlanar cost function with four SE2 variables and a c_square hyperparameter', 'review the QuasiStaticPushingPlanar SE2 cost function for planar pushing motion model', 'summarize the numeric jacobian test for QuasiStaticPushingPlanar across multiple batch sizes']
```

Usage

```
{'test_GPCostWeight_weights': 'test GPCostWeight computes correct sqrt weights for given Q_inv and dt parameters', 'test_GPCostWeight_copy': 'test GPCostWeight copy and deepcopy preserve name and tensor values correctly', 'test_GPCostWeight_variable_type': 'test GPCostWeight stores Qc_inv and dt as Variable types from inputs', 'test_GPMotionModel_error': 'test GPMotionModel error vector matches expected position and velocity difference formulas', 'test_GPMotionModel_jacobians': 'test GPMotionModel jacobians match numeric jacobian computed via finite differences'}
```

## File: facebookresearch_theseus/tests/theseus_tests/embodied/motionmodel/test_misc.py

Prompts

```
['test GPCostWeight computes correct sqrt weights for given Q_inv and dt parameters', 'test GPCostWeight copy and deepcopy preserve name and tensor values correctly', 'test GPCostWeight stores Qc_inv and dt as Variable types from inputs', 'test GPMotionModel error vector matches expected position and velocity difference formulas', 'test GPMotionModel jacobians match numeric jacobian computed via finite differences', 'test the Nonholonomic cost function with SE2 pose and velocity vectors using check_jacobians', 'test the Nonholonomic cost function with Vector3 pose representation and validate jacobians', 'test the HingeCost function with configurable limits and threshold values for vector constraints', 'test the HingeCost jacobian output shapes and error tensor dimensions for batch processing', 'test the HingeCost numerical jacobian accuracy with check_jacobians utility and tolerance 1e-5', 'test the QuasiStaticPushingPlanar cost function error computation against expected SE2 values', 'test the QuasiStaticPushingPlanar jacobian computation using numeric jacobian verification', 'create a QuasiStaticPushingPlanar cost function with four SE2 variables and a c_square hyperparameter', 'review the QuasiStaticPushingPlanar SE2 cost function for planar pushing motion model', 'summarize the numeric jacobian test for QuasiStaticPushingPlanar across multiple batch sizes']
```

Usage

```
{'test_nonholonomic_cost_function': 'test the Nonholonomic cost function with SE2 pose and velocity vectors using check_jacobians', 'test_nonholonomic_vector3_pose': 'test the Nonholonomic cost function with Vector3 pose representation and validate jacobians', 'test_hinge_cost_function': 'test the HingeCost function with configurable limits and threshold values for vector constraints', 'test_hinge_cost_jacobian_shapes': 'test the HingeCost jacobian output shapes and error tensor dimensions for batch processing', 'test_hinge_cost_numerical_accuracy': 'test the HingeCost numerical jacobian accuracy with check_jacobians utility and tolerance 1e-5'}
```

## File: facebookresearch_theseus/tests/theseus_tests/embodied/motionmodel/test_quasi_static_pushing_planar.py

Prompts

```
['test GPCostWeight computes correct sqrt weights for given Q_inv and dt parameters', 'test GPCostWeight copy and deepcopy preserve name and tensor values correctly', 'test GPCostWeight stores Qc_inv and dt as Variable types from inputs', 'test GPMotionModel error vector matches expected position and velocity difference formulas', 'test GPMotionModel jacobians match numeric jacobian computed via finite differences', 'test the Nonholonomic cost function with SE2 pose and velocity vectors using check_jacobians', 'test the Nonholonomic cost function with Vector3 pose representation and validate jacobians', 'test the HingeCost function with configurable limits and threshold values for vector constraints', 'test the HingeCost jacobian output shapes and error tensor dimensions for batch processing', 'test the HingeCost numerical jacobian accuracy with check_jacobians utility and tolerance 1e-5', 'test the QuasiStaticPushingPlanar cost function error computation against expected SE2 values', 'test the QuasiStaticPushingPlanar jacobian computation using numeric jacobian verification', 'create a QuasiStaticPushingPlanar cost function with four SE2 variables and a c_square hyperparameter', 'review the QuasiStaticPushingPlanar SE2 cost function for planar pushing motion model', 'summarize the numeric jacobian test for QuasiStaticPushingPlanar across multiple batch sizes']
```

Usage

```
{'test_quasi_static_pushing_planar_error': 'test the QuasiStaticPushingPlanar cost function error computation against expected SE2 values', 'test_quasi_static_pushing_planar_jacobians': 'test the QuasiStaticPushingPlanar jacobian computation using numeric jacobian verification', 'create_quasi_static_pushing_planar_cost_fn': 'create a QuasiStaticPushingPlanar cost function with four SE2 variables and a c_square hyperparameter', 'review_SE2_cost_function': 'review the QuasiStaticPushingPlanar SE2 cost function for planar pushing motion model', 'summarize_numeric_jacobian_test': 'summarize the numeric jacobian test for QuasiStaticPushingPlanar across multiple batch sizes'}
```

