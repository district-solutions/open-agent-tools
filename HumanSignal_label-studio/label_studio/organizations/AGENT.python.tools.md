# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/organizations/api.py

Prompts

```
['build a Django REST API endpoint to list organizations the authenticated user has access to', 'create a paginated API endpoint to retrieve organization members with optional project contribution details', 'retrieve details for a specific organization member by user ID within a given organization', 'soft delete an organization member from the current active organization with permission checks', 'reset the invitation token and generate a new invite URL for an organization', 'create an organization with a title, created_by user, and optional legacy API token settings', 'destroy an organization by deleting its projects, SAML config, and the organization record', 'test the OrganizationMixin.active_members cached property returns self.members', 'review the OrganizationMixin.active_members cached property and its usage pattern', 'test the OrganizationMemberMixin.has_permission method checks user active_organization_id', 'refactor the OrganizationMemberMixin.has_permission method to support additional permission checks', 'review the OrganizationMixin class and its cached_property pattern for Django models', 'add a user to an organization and create an OrganizationMember record', 'find the organization associated with a given user', 'soft delete an organization member by marking deleted_at and cleaning up user state', 'list projects belonging to an organization sorted by creation date with task counts', 'get an OrganizationMemberSerializer with annotations count and project contribution info', 'list OrganizationMemberSerializer entries with user and project data for an organization', 'serialize an OrganizationIdSerializer with id, title, contact_info, and created_at fields', 'handle an OrganizationInviteSerializer with token and invite_url fields', 'review the python function organization_people_list that renders the organizations people list HTML template', 'create the python view function simple_view that renders the organizations people list HTML template', 'test the python function organization_people_list renders the correct HTML template', 'refactor the python function simple_view to render a different template', 'summarize the python function organization_people_list that renders an HTML template for listing organization people']
```

Usage

```
{'build_list_organizations': 'build a Django REST API endpoint to list organizations the authenticated user has access to', 'create_organization_members_list': 'create a paginated API endpoint to retrieve organization members with optional project contribution details', 'retrieve_organization_member': 'retrieve details for a specific organization member by user ID within a given organization', 'delete_organization_member': 'soft delete an organization member from the current active organization with permission checks', 'reset_organization_invite_token': 'reset the invitation token and generate a new invite URL for an organization'}
```

## File: HumanSignal_label-studio/label_studio/organizations/functions.py

Prompts

```
['build a Django REST API endpoint to list organizations the authenticated user has access to', 'create a paginated API endpoint to retrieve organization members with optional project contribution details', 'retrieve details for a specific organization member by user ID within a given organization', 'soft delete an organization member from the current active organization with permission checks', 'reset the invitation token and generate a new invite URL for an organization', 'create an organization with a title, created_by user, and optional legacy API token settings', 'destroy an organization by deleting its projects, SAML config, and the organization record', 'test the OrganizationMixin.active_members cached property returns self.members', 'review the OrganizationMixin.active_members cached property and its usage pattern', 'test the OrganizationMemberMixin.has_permission method checks user active_organization_id', 'refactor the OrganizationMemberMixin.has_permission method to support additional permission checks', 'review the OrganizationMixin class and its cached_property pattern for Django models', 'add a user to an organization and create an OrganizationMember record', 'find the organization associated with a given user', 'soft delete an organization member by marking deleted_at and cleaning up user state', 'list projects belonging to an organization sorted by creation date with task counts', 'get an OrganizationMemberSerializer with annotations count and project contribution info', 'list OrganizationMemberSerializer entries with user and project data for an organization', 'serialize an OrganizationIdSerializer with id, title, contact_info, and created_at fields', 'handle an OrganizationInviteSerializer with token and invite_url fields', 'review the python function organization_people_list that renders the organizations people list HTML template', 'create the python view function simple_view that renders the organizations people list HTML template', 'test the python function organization_people_list renders the correct HTML template', 'refactor the python function simple_view to render a different template', 'summarize the python function organization_people_list that renders an HTML template for listing organization people']
```

Usage

```
{'create_organization': 'create an organization with a title, created_by user, and optional legacy API token settings', 'destroy_organization': 'destroy an organization by deleting its projects, SAML config, and the organization record'}
```

## File: HumanSignal_label-studio/label_studio/organizations/mixins.py

Prompts

```
['build a Django REST API endpoint to list organizations the authenticated user has access to', 'create a paginated API endpoint to retrieve organization members with optional project contribution details', 'retrieve details for a specific organization member by user ID within a given organization', 'soft delete an organization member from the current active organization with permission checks', 'reset the invitation token and generate a new invite URL for an organization', 'create an organization with a title, created_by user, and optional legacy API token settings', 'destroy an organization by deleting its projects, SAML config, and the organization record', 'test the OrganizationMixin.active_members cached property returns self.members', 'review the OrganizationMixin.active_members cached property and its usage pattern', 'test the OrganizationMemberMixin.has_permission method checks user active_organization_id', 'refactor the OrganizationMemberMixin.has_permission method to support additional permission checks', 'review the OrganizationMixin class and its cached_property pattern for Django models', 'add a user to an organization and create an OrganizationMember record', 'find the organization associated with a given user', 'soft delete an organization member by marking deleted_at and cleaning up user state', 'list projects belonging to an organization sorted by creation date with task counts', 'get an OrganizationMemberSerializer with annotations count and project contribution info', 'list OrganizationMemberSerializer entries with user and project data for an organization', 'serialize an OrganizationIdSerializer with id, title, contact_info, and created_at fields', 'handle an OrganizationInviteSerializer with token and invite_url fields', 'review the python function organization_people_list that renders the organizations people list HTML template', 'create the python view function simple_view that renders the organizations people list HTML template', 'test the python function organization_people_list renders the correct HTML template', 'refactor the python function simple_view to render a different template', 'summarize the python function organization_people_list that renders an HTML template for listing organization people']
```

Usage

```
{'test_OrganizationMixin_active_members': 'test the OrganizationMixin.active_members cached property returns self.members', 'review_OrganizationMixin_active_members': 'review the OrganizationMixin.active_members cached property and its usage pattern', 'test_OrganizationMemberMixin_has_permission': 'test the OrganizationMemberMixin.has_permission method checks user active_organization_id', 'refactor_OrganizationMemberMixin_has_permission': 'refactor the OrganizationMemberMixin.has_permission method to support additional permission checks', 'review_OrganizationMixin': 'review the OrganizationMixin class and its cached_property pattern for Django models'}
```

## File: HumanSignal_label-studio/label_studio/organizations/models.py

Prompts

```
['build a Django REST API endpoint to list organizations the authenticated user has access to', 'create a paginated API endpoint to retrieve organization members with optional project contribution details', 'retrieve details for a specific organization member by user ID within a given organization', 'soft delete an organization member from the current active organization with permission checks', 'reset the invitation token and generate a new invite URL for an organization', 'create an organization with a title, created_by user, and optional legacy API token settings', 'destroy an organization by deleting its projects, SAML config, and the organization record', 'test the OrganizationMixin.active_members cached property returns self.members', 'review the OrganizationMixin.active_members cached property and its usage pattern', 'test the OrganizationMemberMixin.has_permission method checks user active_organization_id', 'refactor the OrganizationMemberMixin.has_permission method to support additional permission checks', 'review the OrganizationMixin class and its cached_property pattern for Django models', 'add a user to an organization and create an OrganizationMember record', 'find the organization associated with a given user', 'soft delete an organization member by marking deleted_at and cleaning up user state', 'list projects belonging to an organization sorted by creation date with task counts', 'get an OrganizationMemberSerializer with annotations count and project contribution info', 'list OrganizationMemberSerializer entries with user and project data for an organization', 'serialize an OrganizationIdSerializer with id, title, contact_info, and created_at fields', 'handle an OrganizationInviteSerializer with token and invite_url fields', 'review the python function organization_people_list that renders the organizations people list HTML template', 'create the python view function simple_view that renders the organizations people list HTML template', 'test the python function organization_people_list renders the correct HTML template', 'refactor the python function simple_view to render a different template', 'summarize the python function organization_people_list that renders an HTML template for listing organization people']
```

Usage

```
{'create_organization': 'create an organization with a given title and created_by user', 'add_user_to_organization': 'add a user to an organization and create an OrganizationMember record', 'find_organization_by_user': 'find the organization associated with a given user', 'soft_delete_organization_member': 'soft delete an organization member by marking deleted_at and cleaning up user state', 'list_projects_sorted_by_created_at': 'list projects belonging to an organization sorted by creation date with task counts'}
```

## File: HumanSignal_label-studio/label_studio/organizations/serializers.py

Prompts

```
['build a Django REST API endpoint to list organizations the authenticated user has access to', 'create a paginated API endpoint to retrieve organization members with optional project contribution details', 'retrieve details for a specific organization member by user ID within a given organization', 'soft delete an organization member from the current active organization with permission checks', 'reset the invitation token and generate a new invite URL for an organization', 'create an organization with a title, created_by user, and optional legacy API token settings', 'destroy an organization by deleting its projects, SAML config, and the organization record', 'test the OrganizationMixin.active_members cached property returns self.members', 'review the OrganizationMixin.active_members cached property and its usage pattern', 'test the OrganizationMemberMixin.has_permission method checks user active_organization_id', 'refactor the OrganizationMemberMixin.has_permission method to support additional permission checks', 'review the OrganizationMixin class and its cached_property pattern for Django models', 'add a user to an organization and create an OrganizationMember record', 'find the organization associated with a given user', 'soft delete an organization member by marking deleted_at and cleaning up user state', 'list projects belonging to an organization sorted by creation date with task counts', 'get an OrganizationMemberSerializer with annotations count and project contribution info', 'list OrganizationMemberSerializer entries with user and project data for an organization', 'serialize an OrganizationIdSerializer with id, title, contact_info, and created_at fields', 'handle an OrganizationInviteSerializer with token and invite_url fields', 'review the python function organization_people_list that renders the organizations people list HTML template', 'create the python view function simple_view that renders the organizations people list HTML template', 'test the python function organization_people_list renders the correct HTML template', 'refactor the python function simple_view to render a different template', 'summarize the python function organization_people_list that renders an HTML template for listing organization people']
```

Usage

```
{'create_organization': 'create an OrganizationSerializer to serialize organization data with all fields', 'get_organization_member_details': 'get an OrganizationMemberSerializer with annotations count and project contribution info', 'list_organization_members': 'list OrganizationMemberSerializer entries with user and project data for an organization', 'serialize_organization_id': 'serialize an OrganizationIdSerializer with id, title, contact_info, and created_at fields', 'handle_organization_invite': 'handle an OrganizationInviteSerializer with token and invite_url fields'}
```

## File: HumanSignal_label-studio/label_studio/organizations/views.py

Prompts

```
['build a Django REST API endpoint to list organizations the authenticated user has access to', 'create a paginated API endpoint to retrieve organization members with optional project contribution details', 'retrieve details for a specific organization member by user ID within a given organization', 'soft delete an organization member from the current active organization with permission checks', 'reset the invitation token and generate a new invite URL for an organization', 'create an organization with a title, created_by user, and optional legacy API token settings', 'destroy an organization by deleting its projects, SAML config, and the organization record', 'test the OrganizationMixin.active_members cached property returns self.members', 'review the OrganizationMixin.active_members cached property and its usage pattern', 'test the OrganizationMemberMixin.has_permission method checks user active_organization_id', 'refactor the OrganizationMemberMixin.has_permission method to support additional permission checks', 'review the OrganizationMixin class and its cached_property pattern for Django models', 'add a user to an organization and create an OrganizationMember record', 'find the organization associated with a given user', 'soft delete an organization member by marking deleted_at and cleaning up user state', 'list projects belonging to an organization sorted by creation date with task counts', 'get an OrganizationMemberSerializer with annotations count and project contribution info', 'list OrganizationMemberSerializer entries with user and project data for an organization', 'serialize an OrganizationIdSerializer with id, title, contact_info, and created_at fields', 'handle an OrganizationInviteSerializer with token and invite_url fields', 'review the python function organization_people_list that renders the organizations people list HTML template', 'create the python view function simple_view that renders the organizations people list HTML template', 'test the python function organization_people_list renders the correct HTML template', 'refactor the python function simple_view to render a different template', 'summarize the python function organization_people_list that renders an HTML template for listing organization people']
```

Usage

```
{'review_organization_people_list': 'review the python function organization_people_list that renders the organizations people list HTML template', 'create_simple_view': 'create the python view function simple_view that renders the organizations people list HTML template', 'test_organization_people_list': 'test the python function organization_people_list renders the correct HTML template', 'refactor_simple_view': 'refactor the python function simple_view to render a different template', 'summarize_organization_people_list': 'summarize the python function organization_people_list that renders an HTML template for listing organization people'}
```

