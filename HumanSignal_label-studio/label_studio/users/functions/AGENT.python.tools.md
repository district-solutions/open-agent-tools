# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/users/functions/common.py

Prompts

```
['test the hash_upload function that generates a hashed filename with UUID prefix for avatar uploads', 'test the check_avatar function that validates image dimensions, extensions, content type, and file size', 'test the save_user function that saves a user to the database and assigns an organization', 'test the proceed_registration function that registers a new user via POST user_signup', 'test the login function that sets last_login session timestamp and authenticates a user', "set a user's last activity timestamp in Redis with optional custom timestamp and automatic TTL expiration", "retrieve a user's last activity timestamp from Redis by user ID, returning None if not found", 'synchronize batched user activity timestamps from Redis to the Django database with atomic bulk updates', 'schedule a background job to sync user activities from Redis to the database when a configurable threshold is reached', 'clean up Redis activity data including individual user keys and batch set entries for given user IDs']
```

Usage

```
{'test_hash_upload': 'test the hash_upload function that generates a hashed filename with UUID prefix for avatar uploads', 'test_check_avatar': 'test the check_avatar function that validates image dimensions, extensions, content type, and file size', 'test_save_user': 'test the save_user function that saves a user to the database and assigns an organization', 'test_proceed_registration': 'test the proceed_registration function that registers a new user via POST user_signup', 'test_login': 'test the login function that sets last_login session timestamp and authenticates a user'}
```

## File: HumanSignal_label-studio/label_studio/users/functions/last_activity.py

Prompts

```
['test the hash_upload function that generates a hashed filename with UUID prefix for avatar uploads', 'test the check_avatar function that validates image dimensions, extensions, content type, and file size', 'test the save_user function that saves a user to the database and assigns an organization', 'test the proceed_registration function that registers a new user via POST user_signup', 'test the login function that sets last_login session timestamp and authenticates a user', "set a user's last activity timestamp in Redis with optional custom timestamp and automatic TTL expiration", "retrieve a user's last activity timestamp from Redis by user ID, returning None if not found", 'synchronize batched user activity timestamps from Redis to the Django database with atomic bulk updates', 'schedule a background job to sync user activities from Redis to the database when a configurable threshold is reached', 'clean up Redis activity data including individual user keys and batch set entries for given user IDs']
```

Usage

```
{'create_set_user_activity': "set a user's last activity timestamp in Redis with optional custom timestamp and automatic TTL expiration", 'read_get_user_activity': "retrieve a user's last activity timestamp from Redis by user ID, returning None if not found", 'run_sync_user_activities': 'synchronize batched user activity timestamps from Redis to the Django database with atomic bulk updates', 'test_schedule_activity_sync': 'schedule a background job to sync user activities from Redis to the database when a configurable threshold is reached', 'refactor_cleanup_redis_data': 'clean up Redis activity data including individual user keys and batch set entries for given user IDs'}
```

