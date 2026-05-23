# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/structures/base_data_element.py

Prompts

```
['create a BaseDataElement with metainfo dict and keyword arguments for bboxes and scores', 'clone a BaseDataElement to create a deep copy of the current data element', 'convert all tensors in a BaseDataElement to cuda, cpu, npu, or mlu device', 'update a BaseDataElement with metainfo and data fields from another BaseDataElement instance', 'convert a BaseDataElement to a plain dictionary including all metainfo and data fields', 'create an InstanceData object with image metadata like img_shape and pad_shape', 'set data fields like det_labels, det_scores, and bboxes on an InstanceData object', 'index an InstanceData object using a torch tensor to filter instances by score threshold', 'slice an InstanceData object with a boolean tensor mask to select matching instances', 'concatenate a list of InstanceData objects into a single InstanceData with combined fields', 'convert a one-hot encoded tensor to label format using LabelData.onehot_to_label', 'convert a label tensor to one-hot encoding using LabelData.label_to_onehot with num_classes', 'create a LabelData instance for storing label-level annotations or predictions', 'review the LabelData class and its static methods for label and one-hot conversion', 'test the LabelData.onehot_to_label method with a valid one-hot tensor input', 'create a PixelData instance with metainfo and image tensor data fields', 'slice a PixelData object by height and width using tuple indexing', 'set a 2D or 3D tensor attribute on PixelData with automatic channel expansion', 'get the height and width shape tuple from a PixelData instance', 'review the PixelData class for pixel-level annotation data structure design']
```

Usage

```
{'create_BaseDataElement_with_metainfo_and_data': 'create a BaseDataElement with metainfo dict and keyword arguments for bboxes and scores', 'clone_BaseDataElement': 'clone a BaseDataElement to create a deep copy of the current data element', 'convert_BaseDataElement_to_device': 'convert all tensors in a BaseDataElement to cuda, cpu, npu, or mlu device', 'update_BaseDataElement_from_another': 'update a BaseDataElement with metainfo and data fields from another BaseDataElement instance', 'convert_BaseDataElement_to_dict': 'convert a BaseDataElement to a plain dictionary including all metainfo and data fields'}
```

## File: facebookresearch_sapiens/engine/mmengine/structures/instance_data.py

Prompts

```
['create a BaseDataElement with metainfo dict and keyword arguments for bboxes and scores', 'clone a BaseDataElement to create a deep copy of the current data element', 'convert all tensors in a BaseDataElement to cuda, cpu, npu, or mlu device', 'update a BaseDataElement with metainfo and data fields from another BaseDataElement instance', 'convert a BaseDataElement to a plain dictionary including all metainfo and data fields', 'create an InstanceData object with image metadata like img_shape and pad_shape', 'set data fields like det_labels, det_scores, and bboxes on an InstanceData object', 'index an InstanceData object using a torch tensor to filter instances by score threshold', 'slice an InstanceData object with a boolean tensor mask to select matching instances', 'concatenate a list of InstanceData objects into a single InstanceData with combined fields', 'convert a one-hot encoded tensor to label format using LabelData.onehot_to_label', 'convert a label tensor to one-hot encoding using LabelData.label_to_onehot with num_classes', 'create a LabelData instance for storing label-level annotations or predictions', 'review the LabelData class and its static methods for label and one-hot conversion', 'test the LabelData.onehot_to_label method with a valid one-hot tensor input', 'create a PixelData instance with metainfo and image tensor data fields', 'slice a PixelData object by height and width using tuple indexing', 'set a 2D or 3D tensor attribute on PixelData with automatic channel expansion', 'get the height and width shape tuple from a PixelData instance', 'review the PixelData class for pixel-level annotation data structure design']
```

Usage

```
{'create_InstanceData_with_metainfo': 'create an InstanceData object with image metadata like img_shape and pad_shape', 'set_InstanceData_fields': 'set data fields like det_labels, det_scores, and bboxes on an InstanceData object', 'index_InstanceData_with_tensor': 'index an InstanceData object using a torch tensor to filter instances by score threshold', 'slice_InstanceData_by_bool_mask': 'slice an InstanceData object with a boolean tensor mask to select matching instances', 'cat_InstanceData_list': 'concatenate a list of InstanceData objects into a single InstanceData with combined fields'}
```

## File: facebookresearch_sapiens/engine/mmengine/structures/label_data.py

Prompts

```
['create a BaseDataElement with metainfo dict and keyword arguments for bboxes and scores', 'clone a BaseDataElement to create a deep copy of the current data element', 'convert all tensors in a BaseDataElement to cuda, cpu, npu, or mlu device', 'update a BaseDataElement with metainfo and data fields from another BaseDataElement instance', 'convert a BaseDataElement to a plain dictionary including all metainfo and data fields', 'create an InstanceData object with image metadata like img_shape and pad_shape', 'set data fields like det_labels, det_scores, and bboxes on an InstanceData object', 'index an InstanceData object using a torch tensor to filter instances by score threshold', 'slice an InstanceData object with a boolean tensor mask to select matching instances', 'concatenate a list of InstanceData objects into a single InstanceData with combined fields', 'convert a one-hot encoded tensor to label format using LabelData.onehot_to_label', 'convert a label tensor to one-hot encoding using LabelData.label_to_onehot with num_classes', 'create a LabelData instance for storing label-level annotations or predictions', 'review the LabelData class and its static methods for label and one-hot conversion', 'test the LabelData.onehot_to_label method with a valid one-hot tensor input', 'create a PixelData instance with metainfo and image tensor data fields', 'slice a PixelData object by height and width using tuple indexing', 'set a 2D or 3D tensor attribute on PixelData with automatic channel expansion', 'get the height and width shape tuple from a PixelData instance', 'review the PixelData class for pixel-level annotation data structure design']
```

Usage

```
{'convert_onehot_to_label': 'convert a one-hot encoded tensor to label format using LabelData.onehot_to_label', 'convert_label_to_onehot': 'convert a label tensor to one-hot encoding using LabelData.label_to_onehot with num_classes', 'create_label_data_instance': 'create a LabelData instance for storing label-level annotations or predictions', 'review_LabelData_class': 'review the LabelData class and its static methods for label and one-hot conversion', 'test_onehot_to_label': 'test the LabelData.onehot_to_label method with a valid one-hot tensor input'}
```

## File: facebookresearch_sapiens/engine/mmengine/structures/pixel_data.py

Prompts

```
['create a BaseDataElement with metainfo dict and keyword arguments for bboxes and scores', 'clone a BaseDataElement to create a deep copy of the current data element', 'convert all tensors in a BaseDataElement to cuda, cpu, npu, or mlu device', 'update a BaseDataElement with metainfo and data fields from another BaseDataElement instance', 'convert a BaseDataElement to a plain dictionary including all metainfo and data fields', 'create an InstanceData object with image metadata like img_shape and pad_shape', 'set data fields like det_labels, det_scores, and bboxes on an InstanceData object', 'index an InstanceData object using a torch tensor to filter instances by score threshold', 'slice an InstanceData object with a boolean tensor mask to select matching instances', 'concatenate a list of InstanceData objects into a single InstanceData with combined fields', 'convert a one-hot encoded tensor to label format using LabelData.onehot_to_label', 'convert a label tensor to one-hot encoding using LabelData.label_to_onehot with num_classes', 'create a LabelData instance for storing label-level annotations or predictions', 'review the LabelData class and its static methods for label and one-hot conversion', 'test the LabelData.onehot_to_label method with a valid one-hot tensor input', 'create a PixelData instance with metainfo and image tensor data fields', 'slice a PixelData object by height and width using tuple indexing', 'set a 2D or 3D tensor attribute on PixelData with automatic channel expansion', 'get the height and width shape tuple from a PixelData instance', 'review the PixelData class for pixel-level annotation data structure design']
```

Usage

```
{'create_pixel_data_instance': 'create a PixelData instance with metainfo and image tensor data fields', 'slice_pixel_data': 'slice a PixelData object by height and width using tuple indexing', 'set_pixel_data_attribute': 'set a 2D or 3D tensor attribute on PixelData with automatic channel expansion', 'get_pixel_data_shape': 'get the height and width shape tuple from a PixelData instance', 'review_pixel_data_class': 'review the PixelData class for pixel-level annotation data structure design'}
```

