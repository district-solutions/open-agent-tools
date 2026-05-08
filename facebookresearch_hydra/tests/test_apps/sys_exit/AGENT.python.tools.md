# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/sys_exit/my_app.py

Prompts

```
['run the hydra decorated my_app function that exits with sys.exit(42)', 'test that sys.exit(42) works correctly inside a hydra.main decorated function', 'review the hydra.main decorator usage with version_base set to None', 'summarize the my_app function that takes a DictConfig and calls sys.exit(42)', 'refactor the my_app function to change the sys.exit return code from 42']
```

Usage

```
{'run_hydra_app_sys_exit': 'run the hydra decorated my_app function that exits with sys.exit(42)', 'test_sys_exit_in_hydra': 'test that sys.exit(42) works correctly inside a hydra.main decorated function', 'review_hydra_main_decorator': 'review the hydra.main decorator usage with version_base set to None', 'summarize_my_app': 'summarize the my_app function that takes a DictConfig and calls sys.exit(42)', 'refactor_sys_exit_code': 'refactor the my_app function to change the sys.exit return code from 42'}
```

