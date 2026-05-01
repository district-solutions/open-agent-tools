# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/ci_cd/baseline_db.py

Prompts

```
['create a baseline database migration from a prisma schema using prisma migrate diff', 'run the baseline_db script to generate migration SQL from an empty database state', 'generate migration SQL by comparing an empty database against the prisma schema datamodel', 'create a timestamped migration directory with migration_lock.toml and migration.sql files', 'review the create_baseline function that generates prisma baseline migrations from schema.prisma', 'run a script that checks if files exceed a maximum line count and reports oversized files', 'create a function that checks multiple files against a max line threshold and returns oversized ones', 'test the check_file_length function with a list of filenames and a max line limit', 'refactor the check_file_length function to support recursive directory scanning for oversized files', 'review the check_file_length function that validates file line counts and exits with status code 1 on failure', 'run the script to compare model_prices_and_context_window.json against its backup and copy if they differ', 'run the main function to check if two JSON files match and auto-sync on mismatch', 'test the main function to verify it returns 0 when files match and 1 when they differ', 'test the copy_content function to verify it copies a source file to a destination path', 'review the main function to understand the file comparison and auto-copy logic', 'run the migration script to generate a new Prisma migration SQL file from schema changes', 'run the migration script with --allow-destructive to permit DROP COLUMN or DROP TABLE statements', 'run the migration script with --skip-freshness-check to bypass the branch freshness guard', 'call create_migration to generate a Prisma migration by diffing the temp database against schema.prisma', 'check if the current branch is up to date with the base branch before generating migrations']
```

Usage

```
{'create_baseline_migration': 'create a baseline database migration from a prisma schema using prisma migrate diff', 'run_baseline_script': 'run the baseline_db script to generate migration SQL from an empty database state', 'generate_migration_sql': 'generate migration SQL by comparing an empty database against the prisma schema datamodel', 'create_migration_directory': 'create a timestamped migration directory with migration_lock.toml and migration.sql files', 'review_create_baseline': 'review the create_baseline function that generates prisma baseline migrations from schema.prisma'}
```

## File: berriai_litellm/ci_cd/check_file_length.py

Prompts

```
['create a baseline database migration from a prisma schema using prisma migrate diff', 'run the baseline_db script to generate migration SQL from an empty database state', 'generate migration SQL by comparing an empty database against the prisma schema datamodel', 'create a timestamped migration directory with migration_lock.toml and migration.sql files', 'review the create_baseline function that generates prisma baseline migrations from schema.prisma', 'run a script that checks if files exceed a maximum line count and reports oversized files', 'create a function that checks multiple files against a max line threshold and returns oversized ones', 'test the check_file_length function with a list of filenames and a max line limit', 'refactor the check_file_length function to support recursive directory scanning for oversized files', 'review the check_file_length function that validates file line counts and exits with status code 1 on failure', 'run the script to compare model_prices_and_context_window.json against its backup and copy if they differ', 'run the main function to check if two JSON files match and auto-sync on mismatch', 'test the main function to verify it returns 0 when files match and 1 when they differ', 'test the copy_content function to verify it copies a source file to a destination path', 'review the main function to understand the file comparison and auto-copy logic', 'run the migration script to generate a new Prisma migration SQL file from schema changes', 'run the migration script with --allow-destructive to permit DROP COLUMN or DROP TABLE statements', 'run the migration script with --skip-freshness-check to bypass the branch freshness guard', 'call create_migration to generate a Prisma migration by diffing the temp database against schema.prisma', 'check if the current branch is up to date with the base branch before generating migrations']
```

Usage

```
{'run_check_file_length': 'run a script that checks if files exceed a maximum line count and reports oversized files', 'create_check_file_length': 'create a function that checks multiple files against a max line threshold and returns oversized ones', 'test_check_file_length': 'test the check_file_length function with a list of filenames and a max line limit', 'refactor_check_file_length': 'refactor the check_file_length function to support recursive directory scanning for oversized files', 'review_check_file_length': 'review the check_file_length function that validates file line counts and exits with status code 1 on failure'}
```

## File: berriai_litellm/ci_cd/check_files_match.py

Prompts

```
['create a baseline database migration from a prisma schema using prisma migrate diff', 'run the baseline_db script to generate migration SQL from an empty database state', 'generate migration SQL by comparing an empty database against the prisma schema datamodel', 'create a timestamped migration directory with migration_lock.toml and migration.sql files', 'review the create_baseline function that generates prisma baseline migrations from schema.prisma', 'run a script that checks if files exceed a maximum line count and reports oversized files', 'create a function that checks multiple files against a max line threshold and returns oversized ones', 'test the check_file_length function with a list of filenames and a max line limit', 'refactor the check_file_length function to support recursive directory scanning for oversized files', 'review the check_file_length function that validates file line counts and exits with status code 1 on failure', 'run the script to compare model_prices_and_context_window.json against its backup and copy if they differ', 'run the main function to check if two JSON files match and auto-sync on mismatch', 'test the main function to verify it returns 0 when files match and 1 when they differ', 'test the copy_content function to verify it copies a source file to a destination path', 'review the main function to understand the file comparison and auto-copy logic', 'run the migration script to generate a new Prisma migration SQL file from schema changes', 'run the migration script with --allow-destructive to permit DROP COLUMN or DROP TABLE statements', 'run the migration script with --skip-freshness-check to bypass the branch freshness guard', 'call create_migration to generate a Prisma migration by diffing the temp database against schema.prisma', 'check if the current branch is up to date with the base branch before generating migrations']
```

Usage

```
{'run_check_files_match': 'run the script to compare model_prices_and_context_window.json against its backup and copy if they differ', 'run_main': 'run the main function to check if two JSON files match and auto-sync on mismatch', 'test_main': 'test the main function to verify it returns 0 when files match and 1 when they differ', 'test_copy_content': 'test the copy_content function to verify it copies a source file to a destination path', 'review_main': 'review the main function to understand the file comparison and auto-copy logic'}
```

## File: berriai_litellm/ci_cd/run_migration.py

Prompts

```
['create a baseline database migration from a prisma schema using prisma migrate diff', 'run the baseline_db script to generate migration SQL from an empty database state', 'generate migration SQL by comparing an empty database against the prisma schema datamodel', 'create a timestamped migration directory with migration_lock.toml and migration.sql files', 'review the create_baseline function that generates prisma baseline migrations from schema.prisma', 'run a script that checks if files exceed a maximum line count and reports oversized files', 'create a function that checks multiple files against a max line threshold and returns oversized ones', 'test the check_file_length function with a list of filenames and a max line limit', 'refactor the check_file_length function to support recursive directory scanning for oversized files', 'review the check_file_length function that validates file line counts and exits with status code 1 on failure', 'run the script to compare model_prices_and_context_window.json against its backup and copy if they differ', 'run the main function to check if two JSON files match and auto-sync on mismatch', 'test the main function to verify it returns 0 when files match and 1 when they differ', 'test the copy_content function to verify it copies a source file to a destination path', 'review the main function to understand the file comparison and auto-copy logic', 'run the migration script to generate a new Prisma migration SQL file from schema changes', 'run the migration script with --allow-destructive to permit DROP COLUMN or DROP TABLE statements', 'run the migration script with --skip-freshness-check to bypass the branch freshness guard', 'call create_migration to generate a Prisma migration by diffing the temp database against schema.prisma', 'check if the current branch is up to date with the base branch before generating migrations']
```

Usage

```
{'run_migration': 'run the migration script to generate a new Prisma migration SQL file from schema changes', 'run_migration_destructive': 'run the migration script with --allow-destructive to permit DROP COLUMN or DROP TABLE statements', 'run_migration_skip_freshness': 'run the migration script with --skip-freshness-check to bypass the branch freshness guard', 'create_migration_programmatic': 'call create_migration to generate a Prisma migration by diffing the temp database against schema.prisma', 'check_branch_freshness': 'check if the current branch is up to date with the base branch before generating migrations'}
```

