# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/enterprise/litellm_enterprise/proxy/management_endpoints/test_internal_user_endpoints.py

Prompts

```
['test the available users endpoint when max_users is set and user count is within the limit', 'test the available users endpoint when premium_user_data is None or max_users is not configured', 'test the bug where total_users_remaining can be negative when user count exceeds max_users', 'test the available users endpoint returns 500 error when prisma_client is None and database is not connected', 'review the TestAvailableEnterpriseUsers test class and its four async test methods for the internal user endpoints', 'create a new project with budget models and metadata using new_project endpoint', 'update an existing project budget models and metadata using update_project endpoint', 'delete a project by project_id using the delete_project endpoint', 'get project info by project_id using the project_info endpoint', 'list all projects with created_at and updated_at timestamps using list_projects endpoint']
```

Usage

```
{'test_available_users_with_max_users': 'test the available users endpoint when max_users is set and user count is within the limit', 'test_available_users_without_max_users': 'test the available users endpoint when premium_user_data is None or max_users is not configured', 'test_available_users_negative_remaining_bug': 'test the bug where total_users_remaining can be negative when user count exceeds max_users', 'test_available_users_no_database_connection': 'test the available users endpoint returns 500 error when prisma_client is None and database is not connected', 'review_TestAvailableEnterpriseUsers_class': 'review the TestAvailableEnterpriseUsers test class and its four async test methods for the internal user endpoints'}
```

## File: berriai_litellm/tests/enterprise/litellm_enterprise/proxy/management_endpoints/test_project_endpoints_prisma.py

Prompts

```
['test the available users endpoint when max_users is set and user count is within the limit', 'test the available users endpoint when premium_user_data is None or max_users is not configured', 'test the bug where total_users_remaining can be negative when user count exceeds max_users', 'test the available users endpoint returns 500 error when prisma_client is None and database is not connected', 'review the TestAvailableEnterpriseUsers test class and its four async test methods for the internal user endpoints', 'create a new project with budget models and metadata using new_project endpoint', 'update an existing project budget models and metadata using update_project endpoint', 'delete a project by project_id using the delete_project endpoint', 'get project info by project_id using the project_info endpoint', 'list all projects with created_at and updated_at timestamps using list_projects endpoint']
```

Usage

```
{'create_project': 'create a new project with budget models and metadata using new_project endpoint', 'update_project': 'update an existing project budget models and metadata using update_project endpoint', 'delete_project': 'delete a project by project_id using the delete_project endpoint', 'get_project_info': 'get project info by project_id using the project_info endpoint', 'list_projects': 'list all projects with created_at and updated_at timestamps using list_projects endpoint'}
```

