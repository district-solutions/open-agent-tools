# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/tasks/management/commands/annotations_fill_updated_by.py

Prompts

```
['run the Django management command annotations_fill_updated_by to fill updated_by field for annotations', 'test the Command.handle method that invokes the annotation updated_by migration', 'test the Command.add_arguments method that configures the Django management command argument parser', 'run the _fill_annotations_updated_by function to populate updated_by from completed_by per project', 'review the Command class that implements a Django management command for filling annotation updated_by fields', 'recalculate project stats for an organization by passing the organization id to the calculate_stats management command', 'update task counters for all tasks in a project using the update_tasks_counters function from tasks.functions', 'run the calculate_stats django management command with an organization id argument to recalculate total_annotations', 'filter projects by organization id using Project.objects.filter(organization_id=org_id) before recalculating stats', 'start job async or sync for update_tasks_counters using start_job_async_or_sync from core.redis', 'run the Django management command to recalculate project stats for all organizations', 'run the Django management command with --from-scratch to recalculate project stats from scratch', 'run the Django management command with --redis to use rq workers for async background processing', 'build a Django management command that recalculates total_annotations and other project stats across all organizations', 'review the calculate_stats_all_orgs function imported from tasks.functions for recalculation logic']
```

Usage

```
{'run_command_fill_updated_by': 'run the Django management command annotations_fill_updated_by to fill updated_by field for annotations', 'test_handle_method': 'test the Command.handle method that invokes the annotation updated_by migration', 'test_add_arguments': 'test the Command.add_arguments method that configures the Django management command argument parser', 'run_migration_fill_annotations': 'run the _fill_annotations_updated_by function to populate updated_by from completed_by per project', 'review_command_class': 'review the Command class that implements a Django management command for filling annotation updated_by fields'}
```

## File: HumanSignal_label-studio/label_studio/tasks/management/commands/calculate_stats.py

Prompts

```
['run the Django management command annotations_fill_updated_by to fill updated_by field for annotations', 'test the Command.handle method that invokes the annotation updated_by migration', 'test the Command.add_arguments method that configures the Django management command argument parser', 'run the _fill_annotations_updated_by function to populate updated_by from completed_by per project', 'review the Command class that implements a Django management command for filling annotation updated_by fields', 'recalculate project stats for an organization by passing the organization id to the calculate_stats management command', 'update task counters for all tasks in a project using the update_tasks_counters function from tasks.functions', 'run the calculate_stats django management command with an organization id argument to recalculate total_annotations', 'filter projects by organization id using Project.objects.filter(organization_id=org_id) before recalculating stats', 'start job async or sync for update_tasks_counters using start_job_async_or_sync from core.redis', 'run the Django management command to recalculate project stats for all organizations', 'run the Django management command with --from-scratch to recalculate project stats from scratch', 'run the Django management command with --redis to use rq workers for async background processing', 'build a Django management command that recalculates total_annotations and other project stats across all organizations', 'review the calculate_stats_all_orgs function imported from tasks.functions for recalculation logic']
```

Usage

```
{'recalculate_organization_stats': 'recalculate project stats for an organization by passing the organization id to the calculate_stats management command', 'update_tasks_counters': 'update task counters for all tasks in a project using the update_tasks_counters function from tasks.functions', 'run_calculate_stats_command': 'run the calculate_stats django management command with an organization id argument to recalculate total_annotations', 'filter_projects_by_organization': 'filter projects by organization id using Project.objects.filter(organization_id=org_id) before recalculating stats', 'start_job_async_or_sync': 'start job async or sync for update_tasks_counters using start_job_async_or_sync from core.redis'}
```

## File: HumanSignal_label-studio/label_studio/tasks/management/commands/calculate_stats_all_orgs.py

Prompts

```
['run the Django management command annotations_fill_updated_by to fill updated_by field for annotations', 'test the Command.handle method that invokes the annotation updated_by migration', 'test the Command.add_arguments method that configures the Django management command argument parser', 'run the _fill_annotations_updated_by function to populate updated_by from completed_by per project', 'review the Command class that implements a Django management command for filling annotation updated_by fields', 'recalculate project stats for an organization by passing the organization id to the calculate_stats management command', 'update task counters for all tasks in a project using the update_tasks_counters function from tasks.functions', 'run the calculate_stats django management command with an organization id argument to recalculate total_annotations', 'filter projects by organization id using Project.objects.filter(organization_id=org_id) before recalculating stats', 'start job async or sync for update_tasks_counters using start_job_async_or_sync from core.redis', 'run the Django management command to recalculate project stats for all organizations', 'run the Django management command with --from-scratch to recalculate project stats from scratch', 'run the Django management command with --redis to use rq workers for async background processing', 'build a Django management command that recalculates total_annotations and other project stats across all organizations', 'review the calculate_stats_all_orgs function imported from tasks.functions for recalculation logic']
```

Usage

```
{'run_calculate_stats_all_orgs': 'run the Django management command to recalculate project stats for all organizations', 'run_calculate_stats_from_scratch': 'run the Django management command with --from-scratch to recalculate project stats from scratch', 'run_calculate_stats_redis': 'run the Django management command with --redis to use rq workers for async background processing', 'build_calculate_stats_command': 'build a Django management command that recalculates total_annotations and other project stats across all organizations', 'review_calculate_stats_all_orgs': 'review the calculate_stats_all_orgs function imported from tasks.functions for recalculation logic'}
```

