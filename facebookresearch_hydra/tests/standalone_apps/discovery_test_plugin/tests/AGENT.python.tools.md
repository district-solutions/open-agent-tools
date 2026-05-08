# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/standalone_apps/discovery_test_plugin/tests/test_discovery.py

Prompts

```
['test that DiscoveryTestPlugin is discoverable via Plugins.instance().discover(Plugin)', 'test that a plugin is imported exactly once by checking the import log file', 'test that modules starting with underscore are skipped during plugin discovery', 'test that NotHiddenTestPlugin is included in discovered plugins list', 'review the Plugins.instance().discover(Plugin) API for discovering Hydra plugins']
```

Usage

```
{'test_plugin_discovery': 'test that DiscoveryTestPlugin is discoverable via Plugins.instance().discover(Plugin)', 'test_import_count': 'test that a plugin is imported exactly once by checking the import log file', 'test_hidden_plugins_skipped': 'test that modules starting with underscore are skipped during plugin discovery', 'test_visible_plugins_included': 'test that NotHiddenTestPlugin is included in discovered plugins list', 'review_plugins_discover_api': 'review the Plugins.instance().discover(Plugin) API for discovering Hydra plugins'}
```

