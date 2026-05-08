# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tools/configen/example/my_app.py

Prompts

```
['run the my_app Hydra application that instantiates User and Admin objects from config', 'use hydra.utils.instantiate to create a User object from the cfg.user config node', 'use hydra.utils.instantiate to create an Admin object from the cfg.admin config node', 'store a config schema mapping UserConf and AdminConf dataclasses in the Hydra ConfigStore', 'review the hydra.main decorator that configures the app with config_path and config_name']
```

Usage

```
{'run_hydra_app': 'run the my_app Hydra application that instantiates User and Admin objects from config', 'instantiate_user_from_config': 'use hydra.utils.instantiate to create a User object from the cfg.user config node', 'instantiate_admin_from_config': 'use hydra.utils.instantiate to create an Admin object from the cfg.admin config node', 'register_config_schema': 'store a config schema mapping UserConf and AdminConf dataclasses in the Hydra ConfigStore', 'review_hydra_main_decorator': 'review the hydra.main decorator that configures the app with config_path and config_name'}
```

