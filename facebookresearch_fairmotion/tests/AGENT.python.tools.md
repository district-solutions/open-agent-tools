# Agent Python Tools

- repo: facebookresearch/fairmotion
- repo_uri: https://github.com/facebookresearch/fairmotion

## File: facebookresearch_fairmotion/tests/test_conversions.py

Prompts

```
['test the R2E function converts rotation matrices to Euler angles with batched and single input consistency', 'test the R2Q function converts rotation matrices to quaternions and validates batched input equivalence', 'test the R2A function converts rotation matrices to axis-angle representation with round-trip accuracy', 'test the R2R6D function converts rotation matrices to 6D representation and back with numerical accuracy', 'test the Rp2T function combines rotation and translation into a transformation matrix with round-trip fidelity', 'test loading a BVH motion file and verify Euler angle pose data across all frames', 'test loading multiple BVH files in parallel with custom scale and axis orientation kwargs', 'test saving a motion object to a BVH file and verify round-trip data fidelity', 'test loading ASF and AMC motion files and compare joint pose data against BVH reference', 'test converting string axis labels like x, y, z into skeleton orientation vectors', 'test loading a BVH motion file and inspecting joint transforms by frame index', "test getting a joint's global transform matrix from a specific frame in a motion", 'test extracting rotation and position from a transform matrix using T2Rp conversion', 'test converting a motion object to its matrix representation for serialization', 'test reconstructing a motion object from a matrix representation and skeleton', 'test the TestMotion class cut_motion method that cuts a BVH motion clip from frame 3 to 5', 'test the TestMotion class append_motion method that appends two BVH motion clips together', 'test the TestMotion class stitch method that blends two BVH motions with a specified blend length', 'run the unittest suite for fairmotion motion operations including cut, append, and stitch', 'review the TestMotion assert_ndarray_equal helper that compares two numpy arrays element-wise', 'generate a random normalized 4-element quaternion vector for rotation testing', 'generate a random 3x3 rotation matrix by converting a random quaternion', 'generate a random 4x4 transformation matrix with rotation and translation components', 'test the get_random_Q function returns a normalized quaternion vector', 'test the get_random_T function returns a valid 4x4 transformation matrix']
```

Usage

```
{'test_R2E_conversion': 'test the R2E function converts rotation matrices to Euler angles with batched and single input consistency', 'test_R2Q_conversion': 'test the R2Q function converts rotation matrices to quaternions and validates batched input equivalence', 'test_R2A_conversion': 'test the R2A function converts rotation matrices to axis-angle representation with round-trip accuracy', 'test_R2R6D_conversion': 'test the R2R6D function converts rotation matrices to 6D representation and back with numerical accuracy', 'test_Rp2T_conversion': 'test the Rp2T function combines rotation and translation into a transformation matrix with round-trip fidelity'}
```

## File: facebookresearch_fairmotion/tests/test_data.py

Prompts

```
['test the R2E function converts rotation matrices to Euler angles with batched and single input consistency', 'test the R2Q function converts rotation matrices to quaternions and validates batched input equivalence', 'test the R2A function converts rotation matrices to axis-angle representation with round-trip accuracy', 'test the R2R6D function converts rotation matrices to 6D representation and back with numerical accuracy', 'test the Rp2T function combines rotation and translation into a transformation matrix with round-trip fidelity', 'test loading a BVH motion file and verify Euler angle pose data across all frames', 'test loading multiple BVH files in parallel with custom scale and axis orientation kwargs', 'test saving a motion object to a BVH file and verify round-trip data fidelity', 'test loading ASF and AMC motion files and compare joint pose data against BVH reference', 'test converting string axis labels like x, y, z into skeleton orientation vectors', 'test loading a BVH motion file and inspecting joint transforms by frame index', "test getting a joint's global transform matrix from a specific frame in a motion", 'test extracting rotation and position from a transform matrix using T2Rp conversion', 'test converting a motion object to its matrix representation for serialization', 'test reconstructing a motion object from a matrix representation and skeleton', 'test the TestMotion class cut_motion method that cuts a BVH motion clip from frame 3 to 5', 'test the TestMotion class append_motion method that appends two BVH motion clips together', 'test the TestMotion class stitch method that blends two BVH motions with a specified blend length', 'run the unittest suite for fairmotion motion operations including cut, append, and stitch', 'review the TestMotion assert_ndarray_equal helper that compares two numpy arrays element-wise', 'generate a random normalized 4-element quaternion vector for rotation testing', 'generate a random 3x3 rotation matrix by converting a random quaternion', 'generate a random 4x4 transformation matrix with rotation and translation components', 'test the get_random_Q function returns a normalized quaternion vector', 'test the get_random_T function returns a valid 4x4 transformation matrix']
```

Usage

```
{'test_bvh_load_motion': 'test loading a BVH motion file and verify Euler angle pose data across all frames', 'test_bvh_load_parallel': 'test loading multiple BVH files in parallel with custom scale and axis orientation kwargs', 'test_bvh_save_motion': 'test saving a motion object to a BVH file and verify round-trip data fidelity', 'test_asfamc_load_motion': 'test loading ASF and AMC motion files and compare joint pose data against BVH reference', 'test_utils_str_to_axis': 'test converting string axis labels like x, y, z into skeleton orientation vectors'}
```

## File: facebookresearch_fairmotion/tests/test_motion.py

Prompts

```
['test the R2E function converts rotation matrices to Euler angles with batched and single input consistency', 'test the R2Q function converts rotation matrices to quaternions and validates batched input equivalence', 'test the R2A function converts rotation matrices to axis-angle representation with round-trip accuracy', 'test the R2R6D function converts rotation matrices to 6D representation and back with numerical accuracy', 'test the Rp2T function combines rotation and translation into a transformation matrix with round-trip fidelity', 'test loading a BVH motion file and verify Euler angle pose data across all frames', 'test loading multiple BVH files in parallel with custom scale and axis orientation kwargs', 'test saving a motion object to a BVH file and verify round-trip data fidelity', 'test loading ASF and AMC motion files and compare joint pose data against BVH reference', 'test converting string axis labels like x, y, z into skeleton orientation vectors', 'test loading a BVH motion file and inspecting joint transforms by frame index', "test getting a joint's global transform matrix from a specific frame in a motion", 'test extracting rotation and position from a transform matrix using T2Rp conversion', 'test converting a motion object to its matrix representation for serialization', 'test reconstructing a motion object from a matrix representation and skeleton', 'test the TestMotion class cut_motion method that cuts a BVH motion clip from frame 3 to 5', 'test the TestMotion class append_motion method that appends two BVH motion clips together', 'test the TestMotion class stitch method that blends two BVH motions with a specified blend length', 'run the unittest suite for fairmotion motion operations including cut, append, and stitch', 'review the TestMotion assert_ndarray_equal helper that compares two numpy arrays element-wise', 'generate a random normalized 4-element quaternion vector for rotation testing', 'generate a random 3x3 rotation matrix by converting a random quaternion', 'generate a random 4x4 transformation matrix with rotation and translation components', 'test the get_random_Q function returns a normalized quaternion vector', 'test the get_random_T function returns a valid 4x4 transformation matrix']
```

Usage

```
{'test_motion_bvh_load': 'test loading a BVH motion file and inspecting joint transforms by frame index', 'test_motion_get_transform': "test getting a joint's global transform matrix from a specific frame in a motion", 'test_conversions_T2Rp': 'test extracting rotation and position from a transform matrix using T2Rp conversion', 'test_motion_to_matrix': 'test converting a motion object to its matrix representation for serialization', 'test_motion_from_matrix': 'test reconstructing a motion object from a matrix representation and skeleton'}
```

## File: facebookresearch_fairmotion/tests/test_operations.py

Prompts

```
['test the R2E function converts rotation matrices to Euler angles with batched and single input consistency', 'test the R2Q function converts rotation matrices to quaternions and validates batched input equivalence', 'test the R2A function converts rotation matrices to axis-angle representation with round-trip accuracy', 'test the R2R6D function converts rotation matrices to 6D representation and back with numerical accuracy', 'test the Rp2T function combines rotation and translation into a transformation matrix with round-trip fidelity', 'test loading a BVH motion file and verify Euler angle pose data across all frames', 'test loading multiple BVH files in parallel with custom scale and axis orientation kwargs', 'test saving a motion object to a BVH file and verify round-trip data fidelity', 'test loading ASF and AMC motion files and compare joint pose data against BVH reference', 'test converting string axis labels like x, y, z into skeleton orientation vectors', 'test loading a BVH motion file and inspecting joint transforms by frame index', "test getting a joint's global transform matrix from a specific frame in a motion", 'test extracting rotation and position from a transform matrix using T2Rp conversion', 'test converting a motion object to its matrix representation for serialization', 'test reconstructing a motion object from a matrix representation and skeleton', 'test the TestMotion class cut_motion method that cuts a BVH motion clip from frame 3 to 5', 'test the TestMotion class append_motion method that appends two BVH motion clips together', 'test the TestMotion class stitch method that blends two BVH motions with a specified blend length', 'run the unittest suite for fairmotion motion operations including cut, append, and stitch', 'review the TestMotion assert_ndarray_equal helper that compares two numpy arrays element-wise', 'generate a random normalized 4-element quaternion vector for rotation testing', 'generate a random 3x3 rotation matrix by converting a random quaternion', 'generate a random 4x4 transformation matrix with rotation and translation components', 'test the get_random_Q function returns a normalized quaternion vector', 'test the get_random_T function returns a valid 4x4 transformation matrix']
```

Usage

```
{'test_cut_motion': 'test the TestMotion class cut_motion method that cuts a BVH motion clip from frame 3 to 5', 'test_append_motion': 'test the TestMotion class append_motion method that appends two BVH motion clips together', 'test_stitch_motion': 'test the TestMotion class stitch method that blends two BVH motions with a specified blend length', 'run_motion_ops_tests': 'run the unittest suite for fairmotion motion operations including cut, append, and stitch', 'review_assert_ndarray_equal': 'review the TestMotion assert_ndarray_equal helper that compares two numpy arrays element-wise'}
```

## File: facebookresearch_fairmotion/tests/utils.py

Prompts

```
['test the R2E function converts rotation matrices to Euler angles with batched and single input consistency', 'test the R2Q function converts rotation matrices to quaternions and validates batched input equivalence', 'test the R2A function converts rotation matrices to axis-angle representation with round-trip accuracy', 'test the R2R6D function converts rotation matrices to 6D representation and back with numerical accuracy', 'test the Rp2T function combines rotation and translation into a transformation matrix with round-trip fidelity', 'test loading a BVH motion file and verify Euler angle pose data across all frames', 'test loading multiple BVH files in parallel with custom scale and axis orientation kwargs', 'test saving a motion object to a BVH file and verify round-trip data fidelity', 'test loading ASF and AMC motion files and compare joint pose data against BVH reference', 'test converting string axis labels like x, y, z into skeleton orientation vectors', 'test loading a BVH motion file and inspecting joint transforms by frame index', "test getting a joint's global transform matrix from a specific frame in a motion", 'test extracting rotation and position from a transform matrix using T2Rp conversion', 'test converting a motion object to its matrix representation for serialization', 'test reconstructing a motion object from a matrix representation and skeleton', 'test the TestMotion class cut_motion method that cuts a BVH motion clip from frame 3 to 5', 'test the TestMotion class append_motion method that appends two BVH motion clips together', 'test the TestMotion class stitch method that blends two BVH motions with a specified blend length', 'run the unittest suite for fairmotion motion operations including cut, append, and stitch', 'review the TestMotion assert_ndarray_equal helper that compares two numpy arrays element-wise', 'generate a random normalized 4-element quaternion vector for rotation testing', 'generate a random 3x3 rotation matrix by converting a random quaternion', 'generate a random 4x4 transformation matrix with rotation and translation components', 'test the get_random_Q function returns a normalized quaternion vector', 'test the get_random_T function returns a valid 4x4 transformation matrix']
```

Usage

```
{'get_random_Q': 'generate a random normalized 4-element quaternion vector for rotation testing', 'get_random_R': 'generate a random 3x3 rotation matrix by converting a random quaternion', 'get_random_T': 'generate a random 4x4 transformation matrix with rotation and translation components', 'test_get_random_Q': 'test the get_random_Q function returns a normalized quaternion vector', 'test_get_random_T': 'test the get_random_T function returns a valid 4x4 transformation matrix'}
```

