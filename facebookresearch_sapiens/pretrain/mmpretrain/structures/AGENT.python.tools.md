# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/structures/data_sample.py

Prompts

```
['create a DataSample with image shape and num_classes metainfo fields', 'set the ground truth label on a DataSample instance with a single or multi label', 'set the predicted score tensor on a DataSample and auto infer num_classes', 'set a mask tensor on a DataSample for masked image modeling tasks', 'review the DataSample class repr method to understand metainfo and data field output', 'create a MultiTaskDataSample instance to hold multi-task learning data fields', 'access the tasks property of a MultiTaskDataSample to retrieve its data fields', 'instantiate a MultiTaskDataSample subclass of BaseDataElement for multi-task data handling', 'extend MultiTaskDataSample to add custom properties for multi-task learning pipelines', 'review the MultiTaskDataSample class and its tasks property that returns _data_fields', 'convert numpy arrays, sequences, or integers to a 1D PyTorch label tensor', 'convert numpy arrays, sequences, or tensors to a 1D PyTorch float score tensor', 'concatenate a list of label tensors into one tensor with split indices', 'convert a concatenated batch label tensor to one-hot format using split indices', 'convert a single label value to a one-hot encoded tensor for a given number of classes']
```

Usage

```
{'create_data_sample_with_metainfo': 'create a DataSample with image shape and num_classes metainfo fields', 'set_gt_label': 'set the ground truth label on a DataSample instance with a single or multi label', 'set_pred_score': 'set the predicted score tensor on a DataSample and auto infer num_classes', 'set_mask': 'set a mask tensor on a DataSample for masked image modeling tasks', 'review_data_sample_repr': 'review the DataSample class repr method to understand metainfo and data field output'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/structures/multi_task_data_sample.py

Prompts

```
['create a DataSample with image shape and num_classes metainfo fields', 'set the ground truth label on a DataSample instance with a single or multi label', 'set the predicted score tensor on a DataSample and auto infer num_classes', 'set a mask tensor on a DataSample for masked image modeling tasks', 'review the DataSample class repr method to understand metainfo and data field output', 'create a MultiTaskDataSample instance to hold multi-task learning data fields', 'access the tasks property of a MultiTaskDataSample to retrieve its data fields', 'instantiate a MultiTaskDataSample subclass of BaseDataElement for multi-task data handling', 'extend MultiTaskDataSample to add custom properties for multi-task learning pipelines', 'review the MultiTaskDataSample class and its tasks property that returns _data_fields', 'convert numpy arrays, sequences, or integers to a 1D PyTorch label tensor', 'convert numpy arrays, sequences, or tensors to a 1D PyTorch float score tensor', 'concatenate a list of label tensors into one tensor with split indices', 'convert a concatenated batch label tensor to one-hot format using split indices', 'convert a single label value to a one-hot encoded tensor for a given number of classes']
```

Usage

```
{'create_MultiTaskDataSample': 'create a MultiTaskDataSample instance to hold multi-task learning data fields', 'access_MultiTaskDataSample_tasks': 'access the tasks property of a MultiTaskDataSample to retrieve its data fields', 'instantiate_MultiTaskDataSample': 'instantiate a MultiTaskDataSample subclass of BaseDataElement for multi-task data handling', 'extend_MultiTaskDataSample': 'extend MultiTaskDataSample to add custom properties for multi-task learning pipelines', 'review_MultiTaskDataSample': 'review the MultiTaskDataSample class and its tasks property that returns _data_fields'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/structures/utils.py

Prompts

```
['create a DataSample with image shape and num_classes metainfo fields', 'set the ground truth label on a DataSample instance with a single or multi label', 'set the predicted score tensor on a DataSample and auto infer num_classes', 'set a mask tensor on a DataSample for masked image modeling tasks', 'review the DataSample class repr method to understand metainfo and data field output', 'create a MultiTaskDataSample instance to hold multi-task learning data fields', 'access the tasks property of a MultiTaskDataSample to retrieve its data fields', 'instantiate a MultiTaskDataSample subclass of BaseDataElement for multi-task data handling', 'extend MultiTaskDataSample to add custom properties for multi-task learning pipelines', 'review the MultiTaskDataSample class and its tasks property that returns _data_fields', 'convert numpy arrays, sequences, or integers to a 1D PyTorch label tensor', 'convert numpy arrays, sequences, or tensors to a 1D PyTorch float score tensor', 'concatenate a list of label tensors into one tensor with split indices', 'convert a concatenated batch label tensor to one-hot format using split indices', 'convert a single label value to a one-hot encoded tensor for a given number of classes']
```

Usage

```
{'format_label_tensor': 'convert numpy arrays, sequences, or integers to a 1D PyTorch label tensor', 'format_score_tensor': 'convert numpy arrays, sequences, or tensors to a 1D PyTorch float score tensor', 'cat_batch_labels': 'concatenate a list of label tensors into one tensor with split indices', 'batch_label_to_onehot': 'convert a concatenated batch label tensor to one-hot format using split indices', 'label_to_onehot': 'convert a single label value to a one-hot encoded tensor for a given number of classes'}
```

