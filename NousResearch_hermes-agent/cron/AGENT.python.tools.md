# Agent Python Tools

- repo: NousResearch/hermes-agent
- repo_uri: https://github.com/NousResearch/hermes-agent

## File: NousResearch_hermes-agent/cron/jobs.py

Prompts

```
['create a cron job with a prompt, schedule string, and optional skills, model, and delivery options', "parse a schedule string like 'every 30m', '0 9 * * *', or '2026-02-03T14:00' into a structured schedule dict", 'get all enabled cron jobs that are due to run now, handling stale missed runs with fast-forward logic', 'list all cron jobs, optionally including disabled ones, with normalized skill fields', 'save cron job output as a timestamped markdown file under ~/.hermes/cron/output/{job_id}/', 'run all due cron jobs and execute them with file-based locking to prevent concurrent ticks', 'execute a single cron job by id, building the prompt, running the agent, and returning success with output', 'deliver a cron job response to configured targets like telegram, discord, slack, or origin chat', "run a cron job's pre-check script and parse wakeAgent gate to decide whether to skip the agent run", 'build the effective prompt for a cron job by injecting script output, skills, and system guidance']
```

Usage

```
{'create_cron_job': 'create a cron job with a prompt, schedule string, and optional skills, model, and delivery options', 'parse_schedule_string': "parse a schedule string like 'every 30m', '0 9 * * *', or '2026-02-03T14:00' into a structured schedule dict", 'get_due_jobs': 'get all enabled cron jobs that are due to run now, handling stale missed runs with fast-forward logic', 'list_cron_jobs': 'list all cron jobs, optionally including disabled ones, with normalized skill fields', 'save_job_output': 'save cron job output as a timestamped markdown file under ~/.hermes/cron/output/{job_id}/'}
```

## File: NousResearch_hermes-agent/cron/scheduler.py

Prompts

```
['create a cron job with a prompt, schedule string, and optional skills, model, and delivery options', "parse a schedule string like 'every 30m', '0 9 * * *', or '2026-02-03T14:00' into a structured schedule dict", 'get all enabled cron jobs that are due to run now, handling stale missed runs with fast-forward logic', 'list all cron jobs, optionally including disabled ones, with normalized skill fields', 'save cron job output as a timestamped markdown file under ~/.hermes/cron/output/{job_id}/', 'run all due cron jobs and execute them with file-based locking to prevent concurrent ticks', 'execute a single cron job by id, building the prompt, running the agent, and returning success with output', 'deliver a cron job response to configured targets like telegram, discord, slack, or origin chat', "run a cron job's pre-check script and parse wakeAgent gate to decide whether to skip the agent run", 'build the effective prompt for a cron job by injecting script output, skills, and system guidance']
```

Usage

```
{'run_cron_jobs': 'run all due cron jobs and execute them with file-based locking to prevent concurrent ticks', 'execute_single_cron_job': 'execute a single cron job by id, building the prompt, running the agent, and returning success with output', 'deliver_cron_response': 'deliver a cron job response to configured targets like telegram, discord, slack, or origin chat', 'run_cron_precheck_script': "run a cron job's pre-check script and parse wakeAgent gate to decide whether to skip the agent run", 'build_cron_job_prompt': 'build the effective prompt for a cron job by injecting script output, skills, and system guidance'}
```

