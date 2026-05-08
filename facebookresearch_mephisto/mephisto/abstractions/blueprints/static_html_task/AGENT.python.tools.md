# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/static_html_task/static_html_blueprint.py

Prompts

```
['create a StaticHTMLBlueprint instance with a task run, args config, and shared static task state', 'configure StaticHTMLBlueprintArgs with a task source HTML file path and optional preview or onboarding source', 'assert task args for a StaticHTMLBlueprint validating data CSV, JSON, or JSONL file existence', 'validate that an onboarding HTML source file exists and pairs with an onboarding qualification', 'review the StaticHTMLBlueprint init method to understand HTML file resolution and initialization data setup', 'build a static HTML task frontend by running npm install and webpack dev build', 'rebuild the frontend core by running npm install and npm run dev in the source directory', 'copy the task HTML file, preview file, onboarding file, and bundle.js into a build directory', 'review the StaticHTMLTaskBuilder class and its build_in_dir method for static HTML task deployment', 'summarize the rebuild_core method that runs npm install and webpack to build the frontend']
```

Usage

```
{'create_static_html_blueprint': 'create a StaticHTMLBlueprint instance with a task run, args config, and shared static task state', 'configure_static_html_blueprint_args': 'configure StaticHTMLBlueprintArgs with a task source HTML file path and optional preview or onboarding source', 'assert_static_html_task_args': 'assert task args for a StaticHTMLBlueprint validating data CSV, JSON, or JSONL file existence', 'validate_onboarding_source': 'validate that an onboarding HTML source file exists and pairs with an onboarding qualification', 'review_static_html_blueprint_init': 'review the StaticHTMLBlueprint init method to understand HTML file resolution and initialization data setup'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/static_html_task/static_html_task_builder.py

Prompts

```
['create a StaticHTMLBlueprint instance with a task run, args config, and shared static task state', 'configure StaticHTMLBlueprintArgs with a task source HTML file path and optional preview or onboarding source', 'assert task args for a StaticHTMLBlueprint validating data CSV, JSON, or JSONL file existence', 'validate that an onboarding HTML source file exists and pairs with an onboarding qualification', 'review the StaticHTMLBlueprint init method to understand HTML file resolution and initialization data setup', 'build a static HTML task frontend by running npm install and webpack dev build', 'rebuild the frontend core by running npm install and npm run dev in the source directory', 'copy the task HTML file, preview file, onboarding file, and bundle.js into a build directory', 'review the StaticHTMLTaskBuilder class and its build_in_dir method for static HTML task deployment', 'summarize the rebuild_core method that runs npm install and webpack to build the frontend']
```

Usage

```
{'build_static_html_task': 'build a static HTML task frontend by running npm install and webpack dev build', 'rebuild_frontend_core': 'rebuild the frontend core by running npm install and npm run dev in the source directory', 'copy_task_files_to_dir': 'copy the task HTML file, preview file, onboarding file, and bundle.js into a build directory', 'review_StaticHTMLTaskBuilder': 'review the StaticHTMLTaskBuilder class and its build_in_dir method for static HTML task deployment', 'summarize_rebuild_core': 'summarize the rebuild_core method that runs npm install and webpack to build the frontend'}
```

