# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/static_react_task/static_react_blueprint.py

Prompts

```
['create a StaticReactBlueprint instance with a task_run, DictConfig args, and SharedStaticTaskState shared_state', 'configure StaticReactBlueprintArgs with task_source path to a prebuilt React JavaScript bundle file', 'enable link_task_source in StaticReactBlueprintArgs to symlink the task bundle for local development watch builds', 'call assert_task_args on StaticReactBlueprint to validate task_source exists and link_task_source is compatible with the architect type', 'review the StaticReactBlueprint __init__ method to understand how js_bundle is resolved and validated on startup', 'build a static React task by copying bundle.js into the server directory for deployment', 'copy additional task files from an extra source directory into the static resource directory', 'create a symlink to the task bundle.js file instead of copying it when link_task_source is enabled', 'write a done.built confirmation file to the build directory after task files are deployed', 'review the StaticReactTaskBuilder class and its build_in_dir method for static React task deployment']
```

Usage

```
{'create_static_react_blueprint': 'create a StaticReactBlueprint instance with a task_run, DictConfig args, and SharedStaticTaskState shared_state', 'configure_static_react_blueprint_args': 'configure StaticReactBlueprintArgs with task_source path to a prebuilt React JavaScript bundle file', 'enable_link_task_source': 'enable link_task_source in StaticReactBlueprintArgs to symlink the task bundle for local development watch builds', 'assert_static_react_task_args': 'call assert_task_args on StaticReactBlueprint to validate task_source exists and link_task_source is compatible with the architect type', 'review_static_react_blueprint_init': 'review the StaticReactBlueprint __init__ method to understand how js_bundle is resolved and validated on startup'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/static_react_task/static_react_task_builder.py

Prompts

```
['create a StaticReactBlueprint instance with a task_run, DictConfig args, and SharedStaticTaskState shared_state', 'configure StaticReactBlueprintArgs with task_source path to a prebuilt React JavaScript bundle file', 'enable link_task_source in StaticReactBlueprintArgs to symlink the task bundle for local development watch builds', 'call assert_task_args on StaticReactBlueprint to validate task_source exists and link_task_source is compatible with the architect type', 'review the StaticReactBlueprint __init__ method to understand how js_bundle is resolved and validated on startup', 'build a static React task by copying bundle.js into the server directory for deployment', 'copy additional task files from an extra source directory into the static resource directory', 'create a symlink to the task bundle.js file instead of copying it when link_task_source is enabled', 'write a done.built confirmation file to the build directory after task files are deployed', 'review the StaticReactTaskBuilder class and its build_in_dir method for static React task deployment']
```

Usage

```
{'build_static_react_task': 'build a static React task by copying bundle.js into the server directory for deployment', 'copy_extra_source_files': 'copy additional task files from an extra source directory into the static resource directory', 'symlink_task_bundle': 'create a symlink to the task bundle.js file instead of copying it when link_task_source is enabled', 'write_built_confirmation': 'write a done.built confirmation file to the build directory after task files are deployed', 'review_StaticReactTaskBuilder': 'review the StaticReactTaskBuilder class and its build_in_dir method for static React task deployment'}
```

