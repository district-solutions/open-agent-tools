# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/onedocker/tests/entity/test_opawdl_state.py

Prompts

```
['test the OPAWDLState class __str__ method returns correct JSON with PluginName, CmdArgsList, Timeout, Next, and IsEnd fields', 'test the TestOPAWDLState setUp method creates an OPAWDLState instance with a plugin name and command args list', 'run the unittest TestCase TestOPAWDLState to verify OPAWDLState string serialization behavior', 'review the TestOPAWDLState unittest class and its test__str__ assertion logic', 'summarize the OPAWDLState test file that validates JSON string output of the OPAWDLState entity', 'create an OPAWDLState with a plugin name and command args list for workflow state tracking', 'create an OPAWDLStateInstance wrapping an OPAWDLState with a Status enum like COMPLETED', 'test that OPAWDLStateInstance __str__ returns the expected JSON with opawdl_state and status fields', 'use the Status enum values CREATED, STARTED, FAILED, or COMPLETED to track instance lifecycle', 'serialize an OPAWDLStateInstance to JSON string using the built-in to_json method from DataClassJsonMixin', 'create an OPAWDLWorkflow with a starting state name and a dictionary of named OPAWDLState objects', 'test that OPAWDLWorkflow string representation produces valid JSON with StartAt and States fields', 'summarize an OPAWDLState by calling to_json to get PluginName, CmdArgsList, Timeout, Next, and IsEnd', 'review the OPAWDLWorkflow class to understand how states are serialized to AWS Step Functions JSON format', 'test that OPAWDLWorkflowInstance returns the correct instance_id via get_instance_id method', 'test that str of OPAWDLWorkflowInstance returns the expected JSON representation', 'run the unittest suite for OPAWDLWorkflowInstance to verify instance id and string output', 'review the setUp method that creates test OPAWDLWorkflow and OPAWDLState instances', 'summarize the test coverage for OPAWDLWorkflowInstance including get_instance_id and str methods']
```

Usage

```
{'test_OPAWDLState_str': 'test the OPAWDLState class __str__ method returns correct JSON with PluginName, CmdArgsList, Timeout, Next, and IsEnd fields', 'test_OPAWDLState_setup': 'test the TestOPAWDLState setUp method creates an OPAWDLState instance with a plugin name and command args list', 'run_OPAWDLState_tests': 'run the unittest TestCase TestOPAWDLState to verify OPAWDLState string serialization behavior', 'review_TestOPAWDLState_class': 'review the TestOPAWDLState unittest class and its test__str__ assertion logic', 'summarize_OPAWDLState_test': 'summarize the OPAWDLState test file that validates JSON string output of the OPAWDLState entity'}
```

## File: facebookresearch_fbpcp/onedocker/tests/entity/test_opawdl_state_instance.py

Prompts

```
['test the OPAWDLState class __str__ method returns correct JSON with PluginName, CmdArgsList, Timeout, Next, and IsEnd fields', 'test the TestOPAWDLState setUp method creates an OPAWDLState instance with a plugin name and command args list', 'run the unittest TestCase TestOPAWDLState to verify OPAWDLState string serialization behavior', 'review the TestOPAWDLState unittest class and its test__str__ assertion logic', 'summarize the OPAWDLState test file that validates JSON string output of the OPAWDLState entity', 'create an OPAWDLState with a plugin name and command args list for workflow state tracking', 'create an OPAWDLStateInstance wrapping an OPAWDLState with a Status enum like COMPLETED', 'test that OPAWDLStateInstance __str__ returns the expected JSON with opawdl_state and status fields', 'use the Status enum values CREATED, STARTED, FAILED, or COMPLETED to track instance lifecycle', 'serialize an OPAWDLStateInstance to JSON string using the built-in to_json method from DataClassJsonMixin', 'create an OPAWDLWorkflow with a starting state name and a dictionary of named OPAWDLState objects', 'test that OPAWDLWorkflow string representation produces valid JSON with StartAt and States fields', 'summarize an OPAWDLState by calling to_json to get PluginName, CmdArgsList, Timeout, Next, and IsEnd', 'review the OPAWDLWorkflow class to understand how states are serialized to AWS Step Functions JSON format', 'test that OPAWDLWorkflowInstance returns the correct instance_id via get_instance_id method', 'test that str of OPAWDLWorkflowInstance returns the expected JSON representation', 'run the unittest suite for OPAWDLWorkflowInstance to verify instance id and string output', 'review the setUp method that creates test OPAWDLWorkflow and OPAWDLState instances', 'summarize the test coverage for OPAWDLWorkflowInstance including get_instance_id and str methods']
```

Usage

```
{'create_OPAWDLState': 'create an OPAWDLState with a plugin name and command args list for workflow state tracking', 'create_OPAWDLStateInstance': 'create an OPAWDLStateInstance wrapping an OPAWDLState with a Status enum like COMPLETED', 'test_OPAWDLStateInstance_str': 'test that OPAWDLStateInstance __str__ returns the expected JSON with opawdl_state and status fields', 'use_Status_enum': 'use the Status enum values CREATED, STARTED, FAILED, or COMPLETED to track instance lifecycle', 'serialize_OPAWDLStateInstance_to_json': 'serialize an OPAWDLStateInstance to JSON string using the built-in to_json method from DataClassJsonMixin'}
```

## File: facebookresearch_fbpcp/onedocker/tests/entity/test_opawdl_workflow.py

Prompts

```
['test the OPAWDLState class __str__ method returns correct JSON with PluginName, CmdArgsList, Timeout, Next, and IsEnd fields', 'test the TestOPAWDLState setUp method creates an OPAWDLState instance with a plugin name and command args list', 'run the unittest TestCase TestOPAWDLState to verify OPAWDLState string serialization behavior', 'review the TestOPAWDLState unittest class and its test__str__ assertion logic', 'summarize the OPAWDLState test file that validates JSON string output of the OPAWDLState entity', 'create an OPAWDLState with a plugin name and command args list for workflow state tracking', 'create an OPAWDLStateInstance wrapping an OPAWDLState with a Status enum like COMPLETED', 'test that OPAWDLStateInstance __str__ returns the expected JSON with opawdl_state and status fields', 'use the Status enum values CREATED, STARTED, FAILED, or COMPLETED to track instance lifecycle', 'serialize an OPAWDLStateInstance to JSON string using the built-in to_json method from DataClassJsonMixin', 'create an OPAWDLWorkflow with a starting state name and a dictionary of named OPAWDLState objects', 'test that OPAWDLWorkflow string representation produces valid JSON with StartAt and States fields', 'summarize an OPAWDLState by calling to_json to get PluginName, CmdArgsList, Timeout, Next, and IsEnd', 'review the OPAWDLWorkflow class to understand how states are serialized to AWS Step Functions JSON format', 'test that OPAWDLWorkflowInstance returns the correct instance_id via get_instance_id method', 'test that str of OPAWDLWorkflowInstance returns the expected JSON representation', 'run the unittest suite for OPAWDLWorkflowInstance to verify instance id and string output', 'review the setUp method that creates test OPAWDLWorkflow and OPAWDLState instances', 'summarize the test coverage for OPAWDLWorkflowInstance including get_instance_id and str methods']
```

Usage

```
{'create_OPAWDLState': 'create an OPAWDLState with a plugin name and command arguments list for workflow steps', 'create_OPAWDLWorkflow': 'create an OPAWDLWorkflow with a starting state name and a dictionary of named OPAWDLState objects', 'test_OPAWDLWorkflow_str': 'test that OPAWDLWorkflow string representation produces valid JSON with StartAt and States fields', 'summarize_OPAWDLState_json': 'summarize an OPAWDLState by calling to_json to get PluginName, CmdArgsList, Timeout, Next, and IsEnd', 'review_OPAWDLWorkflow_serialization': 'review the OPAWDLWorkflow class to understand how states are serialized to AWS Step Functions JSON format'}
```

## File: facebookresearch_fbpcp/onedocker/tests/entity/test_opawdl_workflow_instance.py

Prompts

```
['test the OPAWDLState class __str__ method returns correct JSON with PluginName, CmdArgsList, Timeout, Next, and IsEnd fields', 'test the TestOPAWDLState setUp method creates an OPAWDLState instance with a plugin name and command args list', 'run the unittest TestCase TestOPAWDLState to verify OPAWDLState string serialization behavior', 'review the TestOPAWDLState unittest class and its test__str__ assertion logic', 'summarize the OPAWDLState test file that validates JSON string output of the OPAWDLState entity', 'create an OPAWDLState with a plugin name and command args list for workflow state tracking', 'create an OPAWDLStateInstance wrapping an OPAWDLState with a Status enum like COMPLETED', 'test that OPAWDLStateInstance __str__ returns the expected JSON with opawdl_state and status fields', 'use the Status enum values CREATED, STARTED, FAILED, or COMPLETED to track instance lifecycle', 'serialize an OPAWDLStateInstance to JSON string using the built-in to_json method from DataClassJsonMixin', 'create an OPAWDLWorkflow with a starting state name and a dictionary of named OPAWDLState objects', 'test that OPAWDLWorkflow string representation produces valid JSON with StartAt and States fields', 'summarize an OPAWDLState by calling to_json to get PluginName, CmdArgsList, Timeout, Next, and IsEnd', 'review the OPAWDLWorkflow class to understand how states are serialized to AWS Step Functions JSON format', 'test that OPAWDLWorkflowInstance returns the correct instance_id via get_instance_id method', 'test that str of OPAWDLWorkflowInstance returns the expected JSON representation', 'run the unittest suite for OPAWDLWorkflowInstance to verify instance id and string output', 'review the setUp method that creates test OPAWDLWorkflow and OPAWDLState instances', 'summarize the test coverage for OPAWDLWorkflowInstance including get_instance_id and str methods']
```

Usage

```
{'test_OPAWDLWorkflowInstance_get_instance_id': 'test that OPAWDLWorkflowInstance returns the correct instance_id via get_instance_id method', 'test_OPAWDLWorkflowInstance_str_representation': 'test that str of OPAWDLWorkflowInstance returns the expected JSON representation', 'run_OPAWDLWorkflowInstance_unit_tests': 'run the unittest suite for OPAWDLWorkflowInstance to verify instance id and string output', 'review_OPAWDLWorkflowInstance_test_setup': 'review the setUp method that creates test OPAWDLWorkflow and OPAWDLState instances', 'summarize_OPAWDLWorkflowInstance_test_coverage': 'summarize the test coverage for OPAWDLWorkflowInstance including get_instance_id and str methods'}
```

