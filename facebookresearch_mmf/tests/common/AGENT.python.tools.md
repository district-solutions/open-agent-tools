# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tests/common/test_batch_collator.py

Prompts

```
['test the BatchCollator class by calling it with a list of Sample objects', 'create a BatchCollator instance with dataset name and type for collating sample batches', 'test batching multiple Sample objects with torch tensors into a SampleList', 'test that a SampleList has the correct dataset_name and dataset_type attributes set', 'test converting a batch of samples to a SampleList using the BatchCollator callable', 'test the Meter class update_from_report method by creating Reports and verifying loss averages', 'run the TestMeter unittest to validate Meter loss tracking and averaging behavior', 'review the TestMeter unittest class and its test_meter_update_from_report test method', 'create a Meter instance and update it with Report objects containing model scores and losses', 'summarize the test_meter.py unittest that validates Meter loss global_avg and avg calculations', 'test the Report class copy method to verify deep copy isolation of tensor fields', 'test the Report class detach method to verify tensors are detached from the computation graph', 'test the Report class to method to move tensors between cpu and cuda devices', 'test the Report class attribute and bracket notation access for sample and model output fields', 'test the Report class construction with a SampleList and model output dictionary', 'create a Sample object and set attributes using dot notation or bracket notation', 'update a Sample object with a dictionary of key-value pairs including nested dicts', 'pin the memory of a SampleList for faster GPU transfers using pin_memory', 'convert a batch of dictionaries with tensor values into a SampleList with stacked tensors', 'move a SampleList to a specified device like cpu or cuda using to_device']
```

Usage

```
{'test_BatchCollator_call': 'test the BatchCollator class by calling it with a list of Sample objects', 'create_BatchCollator_instance': 'create a BatchCollator instance with dataset name and type for collating sample batches', 'test_Sample_batching': 'test batching multiple Sample objects with torch tensors into a SampleList', 'test_SampleList_dataset_attrs': 'test that a SampleList has the correct dataset_name and dataset_type attributes set', 'test_convert_batch_to_sample_list': 'test converting a batch of samples to a SampleList using the BatchCollator callable'}
```

## File: facebookresearch_mmf/tests/common/test_meter.py

Prompts

```
['test the BatchCollator class by calling it with a list of Sample objects', 'create a BatchCollator instance with dataset name and type for collating sample batches', 'test batching multiple Sample objects with torch tensors into a SampleList', 'test that a SampleList has the correct dataset_name and dataset_type attributes set', 'test converting a batch of samples to a SampleList using the BatchCollator callable', 'test the Meter class update_from_report method by creating Reports and verifying loss averages', 'run the TestMeter unittest to validate Meter loss tracking and averaging behavior', 'review the TestMeter unittest class and its test_meter_update_from_report test method', 'create a Meter instance and update it with Report objects containing model scores and losses', 'summarize the test_meter.py unittest that validates Meter loss global_avg and avg calculations', 'test the Report class copy method to verify deep copy isolation of tensor fields', 'test the Report class detach method to verify tensors are detached from the computation graph', 'test the Report class to method to move tensors between cpu and cuda devices', 'test the Report class attribute and bracket notation access for sample and model output fields', 'test the Report class construction with a SampleList and model output dictionary', 'create a Sample object and set attributes using dot notation or bracket notation', 'update a Sample object with a dictionary of key-value pairs including nested dicts', 'pin the memory of a SampleList for faster GPU transfers using pin_memory', 'convert a batch of dictionaries with tensor values into a SampleList with stacked tensors', 'move a SampleList to a specified device like cpu or cuda using to_device']
```

Usage

```
{'test_Meter_update_from_report': 'test the Meter class update_from_report method by creating Reports and verifying loss averages', 'run_test_meter_unit': 'run the TestMeter unittest to validate Meter loss tracking and averaging behavior', 'review_TestMeter_class': 'review the TestMeter unittest class and its test_meter_update_from_report test method', 'create_Meter_with_Report': 'create a Meter instance and update it with Report objects containing model scores and losses', 'summarize_test_meter': 'summarize the test_meter.py unittest that validates Meter loss global_avg and avg calculations'}
```

## File: facebookresearch_mmf/tests/common/test_report.py

Prompts

```
['test the BatchCollator class by calling it with a list of Sample objects', 'create a BatchCollator instance with dataset name and type for collating sample batches', 'test batching multiple Sample objects with torch tensors into a SampleList', 'test that a SampleList has the correct dataset_name and dataset_type attributes set', 'test converting a batch of samples to a SampleList using the BatchCollator callable', 'test the Meter class update_from_report method by creating Reports and verifying loss averages', 'run the TestMeter unittest to validate Meter loss tracking and averaging behavior', 'review the TestMeter unittest class and its test_meter_update_from_report test method', 'create a Meter instance and update it with Report objects containing model scores and losses', 'summarize the test_meter.py unittest that validates Meter loss global_avg and avg calculations', 'test the Report class copy method to verify deep copy isolation of tensor fields', 'test the Report class detach method to verify tensors are detached from the computation graph', 'test the Report class to method to move tensors between cpu and cuda devices', 'test the Report class attribute and bracket notation access for sample and model output fields', 'test the Report class construction with a SampleList and model output dictionary', 'create a Sample object and set attributes using dot notation or bracket notation', 'update a Sample object with a dictionary of key-value pairs including nested dicts', 'pin the memory of a SampleList for faster GPU transfers using pin_memory', 'convert a batch of dictionaries with tensor values into a SampleList with stacked tensors', 'move a SampleList to a specified device like cpu or cuda using to_device']
```

Usage

```
{'test_report_copy': 'test the Report class copy method to verify deep copy isolation of tensor fields', 'test_report_detach': 'test the Report class detach method to verify tensors are detached from the computation graph', 'test_report_to_device': 'test the Report class to method to move tensors between cpu and cuda devices', 'test_report_field_access': 'test the Report class attribute and bracket notation access for sample and model output fields', 'test_report_construction': 'test the Report class construction with a SampleList and model output dictionary'}
```

## File: facebookresearch_mmf/tests/common/test_sample.py

Prompts

```
['test the BatchCollator class by calling it with a list of Sample objects', 'create a BatchCollator instance with dataset name and type for collating sample batches', 'test batching multiple Sample objects with torch tensors into a SampleList', 'test that a SampleList has the correct dataset_name and dataset_type attributes set', 'test converting a batch of samples to a SampleList using the BatchCollator callable', 'test the Meter class update_from_report method by creating Reports and verifying loss averages', 'run the TestMeter unittest to validate Meter loss tracking and averaging behavior', 'review the TestMeter unittest class and its test_meter_update_from_report test method', 'create a Meter instance and update it with Report objects containing model scores and losses', 'summarize the test_meter.py unittest that validates Meter loss global_avg and avg calculations', 'test the Report class copy method to verify deep copy isolation of tensor fields', 'test the Report class detach method to verify tensors are detached from the computation graph', 'test the Report class to method to move tensors between cpu and cuda devices', 'test the Report class attribute and bracket notation access for sample and model output fields', 'test the Report class construction with a SampleList and model output dictionary', 'create a Sample object and set attributes using dot notation or bracket notation', 'update a Sample object with a dictionary of key-value pairs including nested dicts', 'pin the memory of a SampleList for faster GPU transfers using pin_memory', 'convert a batch of dictionaries with tensor values into a SampleList with stacked tensors', 'move a SampleList to a specified device like cpu or cuda using to_device']
```

Usage

```
{'create_sample_object': 'create a Sample object and set attributes using dot notation or bracket notation', 'update_sample_with_dict': 'update a Sample object with a dictionary of key-value pairs including nested dicts', 'pin_sample_list_memory': 'pin the memory of a SampleList for faster GPU transfers using pin_memory', 'convert_batch_to_sample_list': 'convert a batch of dictionaries with tensor values into a SampleList with stacked tensors', 'move_sample_list_to_device': 'move a SampleList to a specified device like cpu or cuda using to_device'}
```

