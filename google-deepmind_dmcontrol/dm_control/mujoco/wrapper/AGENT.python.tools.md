# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/mujoco/wrapper/core.py

Prompts

```
['create an MjModel instance from an MJCF or URDF XML string with optional external assets', 'create an MjModel instance by loading and compiling a model XML file from a file path', 'create an MjData instance from an MjModel to hold dynamic simulation state and intermediate results', 'get the 6D linear and angular velocity of a MuJoCo object by ID or name', 'get the contact force wrench as a 2x3 array of forces and torques for a given contact ID', 'test loading a MuJoCo model from an XML file path using core.MjModel.from_xml_path', 'test loading a MuJoCo model from an XML string using core.MjModel.from_xml_string with optional assets dict', 'test creating MjData simulation state from an MjModel and stepping with mujoco.mj_step', 'test saving the last parsed MuJoCo model to an XML file using core.save_last_parsed_model_to_xml', 'test setting and resetting MuJoCo callbacks using core.callback_context as a context manager', 'test the MjbindingsTest class testIndexDict method to verify array_sizes metadata for mjdata and mjmodel fields', 'run the MjbindingsTest parameterized test suite using absltest to validate mjbindings sizes module', 'review the MjbindingsTest class and its parameterized test cases for MuJoCo struct field array size metadata', 'summarize the MjbindingsTest class which tests array_sizes dictionary lookups for mjdata and mjmodel fields', 'refactor the testIndexDict method to add additional parameterized cases for new mjbindings struct fields', 'convert a text string to binary bytes using the default system encoding', 'convert a binary or text string to the native string format using the default encoding', 'get the mujoco library module for use in MuJoCo physics simulation tasks', 'create a numpy ctypes ndpointer type that allows passing None as a NULL pointer', 'review the MJLIB_PATH environment variable constant used to override the MuJoCo shared library path']
```

Usage

```
{'create_MjModel_from_xml_string': 'create an MjModel instance from an MJCF or URDF XML string with optional external assets', 'create_MjModel_from_xml_path': 'create an MjModel instance by loading and compiling a model XML file from a file path', 'create_MjData_from_model': 'create an MjData instance from an MjModel to hold dynamic simulation state and intermediate results', 'get_object_velocity': 'get the 6D linear and angular velocity of a MuJoCo object by ID or name', 'get_contact_force': 'get the contact force wrench as a 2x3 array of forces and torques for a given contact ID'}
```

## File: google-deepmind_dmcontrol/dm_control/mujoco/wrapper/core_test.py

Prompts

```
['create an MjModel instance from an MJCF or URDF XML string with optional external assets', 'create an MjModel instance by loading and compiling a model XML file from a file path', 'create an MjData instance from an MjModel to hold dynamic simulation state and intermediate results', 'get the 6D linear and angular velocity of a MuJoCo object by ID or name', 'get the contact force wrench as a 2x3 array of forces and torques for a given contact ID', 'test loading a MuJoCo model from an XML file path using core.MjModel.from_xml_path', 'test loading a MuJoCo model from an XML string using core.MjModel.from_xml_string with optional assets dict', 'test creating MjData simulation state from an MjModel and stepping with mujoco.mj_step', 'test saving the last parsed MuJoCo model to an XML file using core.save_last_parsed_model_to_xml', 'test setting and resetting MuJoCo callbacks using core.callback_context as a context manager', 'test the MjbindingsTest class testIndexDict method to verify array_sizes metadata for mjdata and mjmodel fields', 'run the MjbindingsTest parameterized test suite using absltest to validate mjbindings sizes module', 'review the MjbindingsTest class and its parameterized test cases for MuJoCo struct field array size metadata', 'summarize the MjbindingsTest class which tests array_sizes dictionary lookups for mjdata and mjmodel fields', 'refactor the testIndexDict method to add additional parameterized cases for new mjbindings struct fields', 'convert a text string to binary bytes using the default system encoding', 'convert a binary or text string to the native string format using the default encoding', 'get the mujoco library module for use in MuJoCo physics simulation tasks', 'create a numpy ctypes ndpointer type that allows passing None as a NULL pointer', 'review the MJLIB_PATH environment variable constant used to override the MuJoCo shared library path']
```

Usage

```
{'test_MjModel_from_xml': 'test loading a MuJoCo model from an XML file path using core.MjModel.from_xml_path', 'test_MjModel_from_xml_string': 'test loading a MuJoCo model from an XML string using core.MjModel.from_xml_string with optional assets dict', 'test_MjData_creation': 'test creating MjData simulation state from an MjModel and stepping with mujoco.mj_step', 'test_save_last_parsed_model_to_xml': 'test saving the last parsed MuJoCo model to an XML file using core.save_last_parsed_model_to_xml', 'test_callback_context': 'test setting and resetting MuJoCo callbacks using core.callback_context as a context manager'}
```

## File: google-deepmind_dmcontrol/dm_control/mujoco/wrapper/mjbindings_test.py

Prompts

```
['create an MjModel instance from an MJCF or URDF XML string with optional external assets', 'create an MjModel instance by loading and compiling a model XML file from a file path', 'create an MjData instance from an MjModel to hold dynamic simulation state and intermediate results', 'get the 6D linear and angular velocity of a MuJoCo object by ID or name', 'get the contact force wrench as a 2x3 array of forces and torques for a given contact ID', 'test loading a MuJoCo model from an XML file path using core.MjModel.from_xml_path', 'test loading a MuJoCo model from an XML string using core.MjModel.from_xml_string with optional assets dict', 'test creating MjData simulation state from an MjModel and stepping with mujoco.mj_step', 'test saving the last parsed MuJoCo model to an XML file using core.save_last_parsed_model_to_xml', 'test setting and resetting MuJoCo callbacks using core.callback_context as a context manager', 'test the MjbindingsTest class testIndexDict method to verify array_sizes metadata for mjdata and mjmodel fields', 'run the MjbindingsTest parameterized test suite using absltest to validate mjbindings sizes module', 'review the MjbindingsTest class and its parameterized test cases for MuJoCo struct field array size metadata', 'summarize the MjbindingsTest class which tests array_sizes dictionary lookups for mjdata and mjmodel fields', 'refactor the testIndexDict method to add additional parameterized cases for new mjbindings struct fields', 'convert a text string to binary bytes using the default system encoding', 'convert a binary or text string to the native string format using the default encoding', 'get the mujoco library module for use in MuJoCo physics simulation tasks', 'create a numpy ctypes ndpointer type that allows passing None as a NULL pointer', 'review the MJLIB_PATH environment variable constant used to override the MuJoCo shared library path']
```

Usage

```
{'test_MjbindingsTest_testIndexDict': 'test the MjbindingsTest class testIndexDict method to verify array_sizes metadata for mjdata and mjmodel fields', 'run_MjbindingsTest': 'run the MjbindingsTest parameterized test suite using absltest to validate mjbindings sizes module', 'review_MjbindingsTest': 'review the MjbindingsTest class and its parameterized test cases for MuJoCo struct field array size metadata', 'summarize_MjbindingsTest': 'summarize the MjbindingsTest class which tests array_sizes dictionary lookups for mjdata and mjmodel fields', 'refactor_MjbindingsTest_testIndexDict': 'refactor the testIndexDict method to add additional parameterized cases for new mjbindings struct fields'}
```

## File: google-deepmind_dmcontrol/dm_control/mujoco/wrapper/util.py

Prompts

```
['create an MjModel instance from an MJCF or URDF XML string with optional external assets', 'create an MjModel instance by loading and compiling a model XML file from a file path', 'create an MjData instance from an MjModel to hold dynamic simulation state and intermediate results', 'get the 6D linear and angular velocity of a MuJoCo object by ID or name', 'get the contact force wrench as a 2x3 array of forces and torques for a given contact ID', 'test loading a MuJoCo model from an XML file path using core.MjModel.from_xml_path', 'test loading a MuJoCo model from an XML string using core.MjModel.from_xml_string with optional assets dict', 'test creating MjData simulation state from an MjModel and stepping with mujoco.mj_step', 'test saving the last parsed MuJoCo model to an XML file using core.save_last_parsed_model_to_xml', 'test setting and resetting MuJoCo callbacks using core.callback_context as a context manager', 'test the MjbindingsTest class testIndexDict method to verify array_sizes metadata for mjdata and mjmodel fields', 'run the MjbindingsTest parameterized test suite using absltest to validate mjbindings sizes module', 'review the MjbindingsTest class and its parameterized test cases for MuJoCo struct field array size metadata', 'summarize the MjbindingsTest class which tests array_sizes dictionary lookups for mjdata and mjmodel fields', 'refactor the testIndexDict method to add additional parameterized cases for new mjbindings struct fields', 'convert a text string to binary bytes using the default system encoding', 'convert a binary or text string to the native string format using the default encoding', 'get the mujoco library module for use in MuJoCo physics simulation tasks', 'create a numpy ctypes ndpointer type that allows passing None as a NULL pointer', 'review the MJLIB_PATH environment variable constant used to override the MuJoCo shared library path']
```

Usage

```
{'to_binary_string': 'convert a text string to binary bytes using the default system encoding', 'to_native_string': 'convert a binary or text string to the native string format using the default encoding', 'get_mjlib': 'get the mujoco library module for use in MuJoCo physics simulation tasks', 'ndptr': 'create a numpy ctypes ndpointer type that allows passing None as a NULL pointer', 'ENV_MJLIB_PATH': 'review the MJLIB_PATH environment variable constant used to override the MuJoCo shared library path'}
```

