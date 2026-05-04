# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-hitl/test/rearrange_v2/test_app_state_start_session.py

Prompts

```
['test AppStateStartSession._try_get_episode_indices to validate episode index parsing from connected user data', 'test _try_get_episode_indices with a single user requesting episodes as a comma-separated string', 'test _try_get_episode_indices with two users requesting the same episodes and verify consensus', 'test _try_get_episode_indices returns None when episodes field is None, int, float, or dict', 'test _try_get_episode_indices returns None when episode indices are negative or exceed total count', 'test the generate_unique_session_id function with episode IDs and connection records to verify session ID format', 'test the make_s3_filename function to verify it sanitizes special characters and truncates long filenames', 'test the validate_experiment_name function to verify it accepts valid names and rejects invalid ones', 'refactor the generate_unique_session_id function to support additional user identification fields beyond user_id', 'review the make_s3_filename function and its special character replacement and truncation logic']
```

Usage

```
{'test_try_get_episode_indices': 'test AppStateStartSession._try_get_episode_indices to validate episode index parsing from connected user data', 'test_episode_indices_single_user': 'test _try_get_episode_indices with a single user requesting episodes as a comma-separated string', 'test_episode_indices_multi_user_match': 'test _try_get_episode_indices with two users requesting the same episodes and verify consensus', 'test_episode_indices_invalid_format': 'test _try_get_episode_indices returns None when episodes field is None, int, float, or dict', 'test_episode_indices_out_of_range': 'test _try_get_episode_indices returns None when episode indices are negative or exceed total count'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/test/rearrange_v2/test_s3_upload.py

Prompts

```
['test AppStateStartSession._try_get_episode_indices to validate episode index parsing from connected user data', 'test _try_get_episode_indices with a single user requesting episodes as a comma-separated string', 'test _try_get_episode_indices with two users requesting the same episodes and verify consensus', 'test _try_get_episode_indices returns None when episodes field is None, int, float, or dict', 'test _try_get_episode_indices returns None when episode indices are negative or exceed total count', 'test the generate_unique_session_id function with episode IDs and connection records to verify session ID format', 'test the make_s3_filename function to verify it sanitizes special characters and truncates long filenames', 'test the validate_experiment_name function to verify it accepts valid names and rejects invalid ones', 'refactor the generate_unique_session_id function to support additional user identification fields beyond user_id', 'review the make_s3_filename function and its special character replacement and truncation logic']
```

Usage

```
{'test_generate_unique_session_id': 'test the generate_unique_session_id function with episode IDs and connection records to verify session ID format', 'test_make_s3_filename': 'test the make_s3_filename function to verify it sanitizes special characters and truncates long filenames', 'test_validate_experiment_name': 'test the validate_experiment_name function to verify it accepts valid names and rejects invalid ones', 'refactor_generate_unique_session_id': 'refactor the generate_unique_session_id function to support additional user identification fields beyond user_id', 'review_make_s3_filename': 'review the make_s3_filename function and its special character replacement and truncation logic'}
```

