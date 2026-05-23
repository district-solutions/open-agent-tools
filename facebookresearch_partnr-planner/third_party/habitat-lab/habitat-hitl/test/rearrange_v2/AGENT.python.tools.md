# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/test/rearrange_v2/test_app_state_start_session.py

Prompts

```
['test the AppStateStartSession._try_get_episode_indices method with various connected user episode scenarios', 'test _try_get_episode_indices with a single connected user providing comma-separated episode strings', 'test _try_get_episode_indices with two connected users providing matching episode selections', 'test _try_get_episode_indices returns None for invalid input types like None, int, float, or dict', 'test _try_get_episode_indices returns None when episode indices are negative or exceed total episode count', 'test the generate_unique_session_id function with episode IDs and connection records to verify session ID formatting', 'test the make_s3_filename function to sanitize special characters and truncate long filenames for S3 uploads', 'test the validate_experiment_name function to check valid and invalid experiment name strings', 'review the generate_unique_session_id function logic for handling episode IDs and user connection records', 'refactor the make_s3_filename function to support additional filename sanitization rules for S3 storage']
```

Usage

```
{'test_try_get_episode_indices': 'test the AppStateStartSession._try_get_episode_indices method with various connected user episode scenarios', 'test_episode_indices_single_user': 'test _try_get_episode_indices with a single connected user providing comma-separated episode strings', 'test_episode_indices_multi_user_match': 'test _try_get_episode_indices with two connected users providing matching episode selections', 'test_episode_indices_invalid_input': 'test _try_get_episode_indices returns None for invalid input types like None, int, float, or dict', 'test_episode_indices_out_of_range': 'test _try_get_episode_indices returns None when episode indices are negative or exceed total episode count'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/test/rearrange_v2/test_s3_upload.py

Prompts

```
['test the AppStateStartSession._try_get_episode_indices method with various connected user episode scenarios', 'test _try_get_episode_indices with a single connected user providing comma-separated episode strings', 'test _try_get_episode_indices with two connected users providing matching episode selections', 'test _try_get_episode_indices returns None for invalid input types like None, int, float, or dict', 'test _try_get_episode_indices returns None when episode indices are negative or exceed total episode count', 'test the generate_unique_session_id function with episode IDs and connection records to verify session ID formatting', 'test the make_s3_filename function to sanitize special characters and truncate long filenames for S3 uploads', 'test the validate_experiment_name function to check valid and invalid experiment name strings', 'review the generate_unique_session_id function logic for handling episode IDs and user connection records', 'refactor the make_s3_filename function to support additional filename sanitization rules for S3 storage']
```

Usage

```
{'test_generate_unique_session_id': 'test the generate_unique_session_id function with episode IDs and connection records to verify session ID formatting', 'test_make_s3_filename': 'test the make_s3_filename function to sanitize special characters and truncate long filenames for S3 uploads', 'test_validate_experiment_name': 'test the validate_experiment_name function to check valid and invalid experiment name strings', 'review_generate_unique_session_id': 'review the generate_unique_session_id function logic for handling episode IDs and user connection records', 'refactor_make_s3_filename': 'refactor the make_s3_filename function to support additional filename sanitization rules for S3 storage'}
```

