# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/interfaces/batch_metrics.py

Prompts

```
['implement a concrete subclass of IFLBatchMetrics that provides loss, num_examples, predictions, targets, and model_inputs properties', 'review the IFLBatchMetrics abstract base class and its five abstract properties for the federated learning metrics interface', 'summarize the IFLBatchMetrics interface which encapsulates loss, predictions, targets, and model inputs for FL model forward runs', 'create a subclass of IFLBatchMetrics that returns a torch.Tensor for loss and an int for num_examples', 'test a concrete IFLBatchMetrics implementation to verify all five abstract properties return correct types', 'implement a concrete subclass of IFLDataLoader that provides fl_train_set, fl_eval_set, and fl_test_set methods', 'create a fl_train_set method that returns an iterable of training data samples for federated learning', 'create a fl_eval_set method that returns an iterable of evaluation data samples for federated learning', 'create a fl_test_set method that returns an iterable of test data samples for federated learning', 'review the IFLDataLoader abstract base class and its three abstract methods for data loading in federated learning', 'create Metric objects from keyword arguments using Metric.from_args with named metric values', 'create a list of Metric objects from a nested dictionary using Metric.from_dict', 'convert a list of Metric objects back to a dictionary using Metric.to_dict', 'check if a Metric is compound by inspecting the is_compund property on a Metric instance', 'implement a concrete IFLMetricsReporter subclass with add_batch_metrics, aggregate, report_metrics, and reset methods', 'implement a subclass of IFLModel that overrides all six abstract methods for a custom federated learning model', 'implement the fl_forward method to process a batch and return IFLBatchMetrics with training loss and gradients', 'implement fl_create_training_batch to construct a training batch from dataset kwargs for federated learning rounds', 'implement fl_get_module to return the underlying PyTorch nn.Module for model parameter access and serialization', 'implement fl_cuda to move the model and its buffers to GPU for accelerated federated training']
```

Usage

```
{'implement_IFLBatchMetrics': 'implement a concrete subclass of IFLBatchMetrics that provides loss, num_examples, predictions, targets, and model_inputs properties', 'review_IFLBatchMetrics': 'review the IFLBatchMetrics abstract base class and its five abstract properties for the federated learning metrics interface', 'summarize_IFLBatchMetrics': 'summarize the IFLBatchMetrics interface which encapsulates loss, predictions, targets, and model inputs for FL model forward runs', 'create_IFLBatchMetrics_subclass': 'create a subclass of IFLBatchMetrics that returns a torch.Tensor for loss and an int for num_examples', 'test_IFLBatchMetrics_implementation': 'test a concrete IFLBatchMetrics implementation to verify all five abstract properties return correct types'}
```

## File: facebookresearch_flsim/flsim/interfaces/data_loader.py

Prompts

```
['implement a concrete subclass of IFLBatchMetrics that provides loss, num_examples, predictions, targets, and model_inputs properties', 'review the IFLBatchMetrics abstract base class and its five abstract properties for the federated learning metrics interface', 'summarize the IFLBatchMetrics interface which encapsulates loss, predictions, targets, and model inputs for FL model forward runs', 'create a subclass of IFLBatchMetrics that returns a torch.Tensor for loss and an int for num_examples', 'test a concrete IFLBatchMetrics implementation to verify all five abstract properties return correct types', 'implement a concrete subclass of IFLDataLoader that provides fl_train_set, fl_eval_set, and fl_test_set methods', 'create a fl_train_set method that returns an iterable of training data samples for federated learning', 'create a fl_eval_set method that returns an iterable of evaluation data samples for federated learning', 'create a fl_test_set method that returns an iterable of test data samples for federated learning', 'review the IFLDataLoader abstract base class and its three abstract methods for data loading in federated learning', 'create Metric objects from keyword arguments using Metric.from_args with named metric values', 'create a list of Metric objects from a nested dictionary using Metric.from_dict', 'convert a list of Metric objects back to a dictionary using Metric.to_dict', 'check if a Metric is compound by inspecting the is_compund property on a Metric instance', 'implement a concrete IFLMetricsReporter subclass with add_batch_metrics, aggregate, report_metrics, and reset methods', 'implement a subclass of IFLModel that overrides all six abstract methods for a custom federated learning model', 'implement the fl_forward method to process a batch and return IFLBatchMetrics with training loss and gradients', 'implement fl_create_training_batch to construct a training batch from dataset kwargs for federated learning rounds', 'implement fl_get_module to return the underlying PyTorch nn.Module for model parameter access and serialization', 'implement fl_cuda to move the model and its buffers to GPU for accelerated federated training']
```

Usage

```
{'implement_IFLDataLoader': 'implement a concrete subclass of IFLDataLoader that provides fl_train_set, fl_eval_set, and fl_test_set methods', 'create_fl_train_set': 'create a fl_train_set method that returns an iterable of training data samples for federated learning', 'create_fl_eval_set': 'create a fl_eval_set method that returns an iterable of evaluation data samples for federated learning', 'create_fl_test_set': 'create a fl_test_set method that returns an iterable of test data samples for federated learning', 'review_IFLDataLoader': 'review the IFLDataLoader abstract base class and its three abstract methods for data loading in federated learning'}
```

## File: facebookresearch_flsim/flsim/interfaces/metrics_reporter.py

Prompts

```
['implement a concrete subclass of IFLBatchMetrics that provides loss, num_examples, predictions, targets, and model_inputs properties', 'review the IFLBatchMetrics abstract base class and its five abstract properties for the federated learning metrics interface', 'summarize the IFLBatchMetrics interface which encapsulates loss, predictions, targets, and model inputs for FL model forward runs', 'create a subclass of IFLBatchMetrics that returns a torch.Tensor for loss and an int for num_examples', 'test a concrete IFLBatchMetrics implementation to verify all five abstract properties return correct types', 'implement a concrete subclass of IFLDataLoader that provides fl_train_set, fl_eval_set, and fl_test_set methods', 'create a fl_train_set method that returns an iterable of training data samples for federated learning', 'create a fl_eval_set method that returns an iterable of evaluation data samples for federated learning', 'create a fl_test_set method that returns an iterable of test data samples for federated learning', 'review the IFLDataLoader abstract base class and its three abstract methods for data loading in federated learning', 'create Metric objects from keyword arguments using Metric.from_args with named metric values', 'create a list of Metric objects from a nested dictionary using Metric.from_dict', 'convert a list of Metric objects back to a dictionary using Metric.to_dict', 'check if a Metric is compound by inspecting the is_compund property on a Metric instance', 'implement a concrete IFLMetricsReporter subclass with add_batch_metrics, aggregate, report_metrics, and reset methods', 'implement a subclass of IFLModel that overrides all six abstract methods for a custom federated learning model', 'implement the fl_forward method to process a batch and return IFLBatchMetrics with training loss and gradients', 'implement fl_create_training_batch to construct a training batch from dataset kwargs for federated learning rounds', 'implement fl_get_module to return the underlying PyTorch nn.Module for model parameter access and serialization', 'implement fl_cuda to move the model and its buffers to GPU for accelerated federated training']
```

Usage

```
{'create_metric_from_kwargs': 'create Metric objects from keyword arguments using Metric.from_args with named metric values', 'create_metric_from_dict': 'create a list of Metric objects from a nested dictionary using Metric.from_dict', 'convert_metrics_to_dict': 'convert a list of Metric objects back to a dictionary using Metric.to_dict', 'check_metric_is_compound': 'check if a Metric is compound by inspecting the is_compund property on a Metric instance', 'implement_metrics_reporter': 'implement a concrete IFLMetricsReporter subclass with add_batch_metrics, aggregate, report_metrics, and reset methods'}
```

## File: facebookresearch_flsim/flsim/interfaces/model.py

Prompts

```
['implement a concrete subclass of IFLBatchMetrics that provides loss, num_examples, predictions, targets, and model_inputs properties', 'review the IFLBatchMetrics abstract base class and its five abstract properties for the federated learning metrics interface', 'summarize the IFLBatchMetrics interface which encapsulates loss, predictions, targets, and model inputs for FL model forward runs', 'create a subclass of IFLBatchMetrics that returns a torch.Tensor for loss and an int for num_examples', 'test a concrete IFLBatchMetrics implementation to verify all five abstract properties return correct types', 'implement a concrete subclass of IFLDataLoader that provides fl_train_set, fl_eval_set, and fl_test_set methods', 'create a fl_train_set method that returns an iterable of training data samples for federated learning', 'create a fl_eval_set method that returns an iterable of evaluation data samples for federated learning', 'create a fl_test_set method that returns an iterable of test data samples for federated learning', 'review the IFLDataLoader abstract base class and its three abstract methods for data loading in federated learning', 'create Metric objects from keyword arguments using Metric.from_args with named metric values', 'create a list of Metric objects from a nested dictionary using Metric.from_dict', 'convert a list of Metric objects back to a dictionary using Metric.to_dict', 'check if a Metric is compound by inspecting the is_compund property on a Metric instance', 'implement a concrete IFLMetricsReporter subclass with add_batch_metrics, aggregate, report_metrics, and reset methods', 'implement a subclass of IFLModel that overrides all six abstract methods for a custom federated learning model', 'implement the fl_forward method to process a batch and return IFLBatchMetrics with training loss and gradients', 'implement fl_create_training_batch to construct a training batch from dataset kwargs for federated learning rounds', 'implement fl_get_module to return the underlying PyTorch nn.Module for model parameter access and serialization', 'implement fl_cuda to move the model and its buffers to GPU for accelerated federated training']
```

Usage

```
{'implement_IFLModel_subclass': 'implement a subclass of IFLModel that overrides all six abstract methods for a custom federated learning model', 'implement_fl_forward': 'implement the fl_forward method to process a batch and return IFLBatchMetrics with training loss and gradients', 'implement_fl_create_training_batch': 'implement fl_create_training_batch to construct a training batch from dataset kwargs for federated learning rounds', 'implement_fl_get_module': 'implement fl_get_module to return the underlying PyTorch nn.Module for model parameter access and serialization', 'implement_fl_cuda': 'implement fl_cuda to move the model and its buffers to GPU for accelerated federated training'}
```

