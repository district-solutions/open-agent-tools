# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/test/apps/webui/routers/test_auths.py

Prompts

```
['test the TestAuths class that integrates authentication API endpoints with a PostgreSQL test database', 'test the test_get_session_user method that retrieves the current session user details via GET /api/v1/auths', "test the test_update_profile method that updates a user's name and profile image URL via POST /api/v1/auths/update/profile", 'test the test_signin method that authenticates a user with email and password via POST /api/v1/auths/signin and returns a Bearer token', 'test the test_signup method that creates a new user account via POST /api/v1/auths/signup and returns user details with a Bearer token', 'test the test_add_user method that creates a new user with admin role via POST /api/v1/auths/add by an authenticated user', "test the test_update_password method that changes a user's password via POST /api/v1/auths/update/password", 'test the Model CRUD API endpoints for listing, adding, querying, and deleting models', 'test the GET /api/v1/models/list endpoint to retrieve paginated model listings with filters', 'test the POST /api/v1/models/add endpoint to create a new model with id, name, meta, and params', 'test the POST /api/v1/models/model/delete endpoint to remove a model by id', 'test the Models.search_models method to filter models by query, tag, and ordering', 'test the TestUsers class that verifies user CRUD operations via HTTP endpoints', 'test inserting new users with id, name, email, profile_image_url, and role fields', "test updating a user's role from user to admin via the update/role endpoint", 'test getting and updating user settings with ui and model_config attributes', 'test deleting a user by id and verifying the user list reflects the deletion']
```

Usage

```
{'test_auths_class': 'test the TestAuths class that integrates authentication API endpoints with a PostgreSQL test database', 'test_get_session_user': 'test the test_get_session_user method that retrieves the current session user details via GET /api/v1/auths', 'test_update_profile': "test the test_update_profile method that updates a user's name and profile image URL via POST /api/v1/auths/update/profile", 'test_signin': 'test the test_signin method that authenticates a user with email and password via POST /api/v1/auths/signin and returns a Bearer token', 'test_signup': 'test the test_signup method that creates a new user account via POST /api/v1/auths/signup and returns user details with a Bearer token', 'test_add_user': 'test the test_add_user method that creates a new user with admin role via POST /api/v1/auths/add by an authenticated user', 'test_update_password': "test the test_update_password method that changes a user's password via POST /api/v1/auths/update/password"}
```

## File: open-webui_open-webui/backend/open_webui/test/apps/webui/routers/test_models.py

Prompts

```
['test the TestAuths class that integrates authentication API endpoints with a PostgreSQL test database', 'test the test_get_session_user method that retrieves the current session user details via GET /api/v1/auths', "test the test_update_profile method that updates a user's name and profile image URL via POST /api/v1/auths/update/profile", 'test the test_signin method that authenticates a user with email and password via POST /api/v1/auths/signin and returns a Bearer token', 'test the test_signup method that creates a new user account via POST /api/v1/auths/signup and returns user details with a Bearer token', 'test the test_add_user method that creates a new user with admin role via POST /api/v1/auths/add by an authenticated user', "test the test_update_password method that changes a user's password via POST /api/v1/auths/update/password", 'test the Model CRUD API endpoints for listing, adding, querying, and deleting models', 'test the GET /api/v1/models/list endpoint to retrieve paginated model listings with filters', 'test the POST /api/v1/models/add endpoint to create a new model with id, name, meta, and params', 'test the POST /api/v1/models/model/delete endpoint to remove a model by id', 'test the Models.search_models method to filter models by query, tag, and ordering', 'test the TestUsers class that verifies user CRUD operations via HTTP endpoints', 'test inserting new users with id, name, email, profile_image_url, and role fields', "test updating a user's role from user to admin via the update/role endpoint", 'test getting and updating user settings with ui and model_config attributes', 'test deleting a user by id and verifying the user list reflects the deletion']
```

Usage

```
{'test_models_crud': 'test the Model CRUD API endpoints for listing, adding, querying, and deleting models', 'test_get_models_list': 'test the GET /api/v1/models/list endpoint to retrieve paginated model listings with filters', 'test_add_model': 'test the POST /api/v1/models/add endpoint to create a new model with id, name, meta, and params', 'test_delete_model': 'test the POST /api/v1/models/model/delete endpoint to remove a model by id', 'test_search_models': 'test the Models.search_models method to filter models by query, tag, and ordering'}
```

## File: open-webui_open-webui/backend/open_webui/test/apps/webui/routers/test_users.py

Prompts

```
['test the TestAuths class that integrates authentication API endpoints with a PostgreSQL test database', 'test the test_get_session_user method that retrieves the current session user details via GET /api/v1/auths', "test the test_update_profile method that updates a user's name and profile image URL via POST /api/v1/auths/update/profile", 'test the test_signin method that authenticates a user with email and password via POST /api/v1/auths/signin and returns a Bearer token', 'test the test_signup method that creates a new user account via POST /api/v1/auths/signup and returns user details with a Bearer token', 'test the test_add_user method that creates a new user with admin role via POST /api/v1/auths/add by an authenticated user', "test the test_update_password method that changes a user's password via POST /api/v1/auths/update/password", 'test the Model CRUD API endpoints for listing, adding, querying, and deleting models', 'test the GET /api/v1/models/list endpoint to retrieve paginated model listings with filters', 'test the POST /api/v1/models/add endpoint to create a new model with id, name, meta, and params', 'test the POST /api/v1/models/model/delete endpoint to remove a model by id', 'test the Models.search_models method to filter models by query, tag, and ordering', 'test the TestUsers class that verifies user CRUD operations via HTTP endpoints', 'test inserting new users with id, name, email, profile_image_url, and role fields', "test updating a user's role from user to admin via the update/role endpoint", 'test getting and updating user settings with ui and model_config attributes', 'test deleting a user by id and verifying the user list reflects the deletion']
```

Usage

```
{'test_TestUsers': 'test the TestUsers class that verifies user CRUD operations via HTTP endpoints', 'test_TestUsers_insert_new_user': 'test inserting new users with id, name, email, profile_image_url, and role fields', 'test_TestUsers_update_role': "test updating a user's role from user to admin via the update/role endpoint", 'test_TestUsers_user_settings': 'test getting and updating user settings with ui and model_config attributes', 'test_TestUsers_delete_user': 'test deleting a user by id and verifying the user list reflects the deletion'}
```

