# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/protobuf/src/google/protobuf/util/python/field_mask_util.py

Prompts

```
['merge fields from a source protobuf message to a destination message using a FieldMask and MergeOptions', 'create a MergeOptions instance to control replace_message_fields and replace_repeated_fields behavior during merge', 'build a protobuf message merge pipeline that selectively copies fields using a FieldMask between two messages', 'review the MergeOptions configuration to decide whether message fields and repeated fields should be replaced or merged', 'test the MergeMessageTo method by merging a source message into a destination message with a specified FieldMask', 'test merging a protobuf source message into a destination using a field mask with default options', 'test MergeMessageTo with hypothesis-generated random timestamp and field mask inputs to verify masked field merging', 'test merging repeated fields with replace_repeated_fields option to control append versus replace behavior', 'test merging nested message fields with replace_message_fields option to control full replacement versus partial merge', 'test merging nested message fields via dotted paths and verify map key field mask behavior']
```

Usage

```
{'merge_message_to': 'merge fields from a source protobuf message to a destination message using a FieldMask and MergeOptions', 'create_merge_options': 'create a MergeOptions instance to control replace_message_fields and replace_repeated_fields behavior during merge', 'build_field_mask_merge': 'build a protobuf message merge pipeline that selectively copies fields using a FieldMask between two messages', 'review_merge_options_config': 'review the MergeOptions configuration to decide whether message fields and repeated fields should be replaced or merged', 'test_merge_message_to': 'test the MergeMessageTo method by merging a source message into a destination message with a specified FieldMask'}
```

## File: google-deepmind_actionengine/third_party/protobuf/src/google/protobuf/util/python/field_mask_util_test.py

Prompts

```
['merge fields from a source protobuf message to a destination message using a FieldMask and MergeOptions', 'create a MergeOptions instance to control replace_message_fields and replace_repeated_fields behavior during merge', 'build a protobuf message merge pipeline that selectively copies fields using a FieldMask between two messages', 'review the MergeOptions configuration to decide whether message fields and repeated fields should be replaced or merged', 'test the MergeMessageTo method by merging a source message into a destination message with a specified FieldMask', 'test merging a protobuf source message into a destination using a field mask with default options', 'test MergeMessageTo with hypothesis-generated random timestamp and field mask inputs to verify masked field merging', 'test merging repeated fields with replace_repeated_fields option to control append versus replace behavior', 'test merging nested message fields with replace_message_fields option to control full replacement versus partial merge', 'test merging nested message fields via dotted paths and verify map key field mask behavior']
```

Usage

```
{'test_merge_message_to_simple': 'test merging a protobuf source message into a destination using a field mask with default options', 'test_merge_message_to_hypothesis': 'test MergeMessageTo with hypothesis-generated random timestamp and field mask inputs to verify masked field merging', 'test_merge_repeated_fields': 'test merging repeated fields with replace_repeated_fields option to control append versus replace behavior', 'test_merge_message_fields': 'test merging nested message fields with replace_message_fields option to control full replacement versus partial merge', 'test_nested_and_map_fields': 'test merging nested message fields via dotted paths and verify map key field mask behavior'}
```

