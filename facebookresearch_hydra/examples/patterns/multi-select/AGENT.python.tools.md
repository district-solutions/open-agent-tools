# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/patterns/multi-select/my_app.py

Prompts

```
['run the Hydra multi-select app that prints resolved config as YAML', 'run my_app with a config override like server=apache_https to switch server config', 'run my_app with site overrides like +server/site=amazon to add a site config', 'review the hydra.main decorator that configures version_base, config_path, and config_name', 'summarize how OmegaConf.to_yaml converts the DictConfig into a human-readable YAML string']
```

Usage

```
{'run_hydra_multi_select_app': 'run the Hydra multi-select app that prints resolved config as YAML', 'run_my_app_with_config_override': 'run my_app with a config override like server=apache_https to switch server config', 'run_my_app_with_site_override': 'run my_app with site overrides like +server/site=amazon to add a site config', 'review_hydra_main_decorator': 'review the hydra.main decorator that configures version_base, config_path, and config_name', 'summarize_omegaconf_to_yaml': 'summarize how OmegaConf.to_yaml converts the DictConfig into a human-readable YAML string'}
```

