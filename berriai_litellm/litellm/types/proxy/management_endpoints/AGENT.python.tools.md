# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/types/proxy/management_endpoints/internal_user_endpoints.py

Prompts

```
['create a UserListResponse model with users list, total count, page, page_size, and total_pages fields', 'create a BulkUpdateUserRequest with either individual user updates or all_users flag with bulk updates', 'validate BulkUpdateUserRequest ensuring users and all_users are mutually exclusive with proper user_updates', 'create a UserUpdateResult with user_id, user_email, success boolean, optional error message, and updated_user dict', 'create a BulkUpdateUserResponse with results list, total_requested, successful_updates, and failed_updates counts', 'create a SCIMUser model with userName, name, displayName, active status, emails, and groups for user provisioning', 'create a SCIMGroup model with displayName and optional members for group provisioning', 'build a SCIMPatchOp with add, remove, or replace operations to update SCIM user or group resources', 'create a SCIMServiceProviderConfig indicating supported patch, bulk, filter, and other SCIM features', 'create a SCIMListResponse with totalResults, startIndex, itemsPerPage, and a list of SCIMUser or SCIMGroup resources']
```

Usage

```
{'create_user_list_response': 'create a UserListResponse model with users list, total count, page, page_size, and total_pages fields', 'create_bulk_update_user_request': 'create a BulkUpdateUserRequest with either individual user updates or all_users flag with bulk updates', 'validate_bulk_update_request': 'validate BulkUpdateUserRequest ensuring users and all_users are mutually exclusive with proper user_updates', 'create_user_update_result': 'create a UserUpdateResult with user_id, user_email, success boolean, optional error message, and updated_user dict', 'create_bulk_update_user_response': 'create a BulkUpdateUserResponse with results list, total_requested, successful_updates, and failed_updates counts'}
```

## File: berriai_litellm/litellm/types/proxy/management_endpoints/scim_v2.py

Prompts

```
['create a UserListResponse model with users list, total count, page, page_size, and total_pages fields', 'create a BulkUpdateUserRequest with either individual user updates or all_users flag with bulk updates', 'validate BulkUpdateUserRequest ensuring users and all_users are mutually exclusive with proper user_updates', 'create a UserUpdateResult with user_id, user_email, success boolean, optional error message, and updated_user dict', 'create a BulkUpdateUserResponse with results list, total_requested, successful_updates, and failed_updates counts', 'create a SCIMUser model with userName, name, displayName, active status, emails, and groups for user provisioning', 'create a SCIMGroup model with displayName and optional members for group provisioning', 'build a SCIMPatchOp with add, remove, or replace operations to update SCIM user or group resources', 'create a SCIMServiceProviderConfig indicating supported patch, bulk, filter, and other SCIM features', 'create a SCIMListResponse with totalResults, startIndex, itemsPerPage, and a list of SCIMUser or SCIMGroup resources']
```

Usage

```
{'create_scim_user': 'create a SCIMUser model with userName, name, displayName, active status, emails, and groups for user provisioning', 'create_scim_group': 'create a SCIMGroup model with displayName and optional members for group provisioning', 'build_scim_patch_op': 'build a SCIMPatchOp with add, remove, or replace operations to update SCIM user or group resources', 'create_scim_service_provider_config': 'create a SCIMServiceProviderConfig indicating supported patch, bulk, filter, and other SCIM features', 'create_scim_list_response': 'create a SCIMListResponse with totalResults, startIndex, itemsPerPage, and a list of SCIMUser or SCIMGroup resources'}
```

