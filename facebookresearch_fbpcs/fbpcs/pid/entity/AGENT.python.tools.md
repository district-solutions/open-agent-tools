# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/pid/entity/pid_instance.py

Prompts

```
["use PIDRole.from_str to parse a string like 'PUBLISHER' or 'PARTNER' into a PIDRole enum value", 'access PIDRole.PUBLISHER or PIDRole.PARTNER to get the integer values 0 or 1', 'reference PIDStageStatus enum values like READY, STARTED, COMPLETED, FAILED, or UNKNOWN', 'reference PIDProtocol enum values like UNION_PID, PS3I_M_TO_M, or UNION_PID_MULTIKEY', 'review the PIDRole, PIDStageStatus, and PIDProtocol enums to understand the FBPCS PID entity types']
```

Usage

```
{'parse_pid_role_from_string': "use PIDRole.from_str to parse a string like 'PUBLISHER' or 'PARTNER' into a PIDRole enum value", 'check_pid_role_value': 'access PIDRole.PUBLISHER or PIDRole.PARTNER to get the integer values 0 or 1', 'inspect_pid_stage_status': 'reference PIDStageStatus enum values like READY, STARTED, COMPLETED, FAILED, or UNKNOWN', 'inspect_pid_protocol': 'reference PIDProtocol enum values like UNION_PID, PS3I_M_TO_M, or UNION_PID_MULTIKEY', 'review_pid_entity_enums': 'review the PIDRole, PIDStageStatus, and PIDProtocol enums to understand the FBPCS PID entity types'}
```

