# Agent Python Tools

- repo: huggingface/ai-deadlines
- repo_uri: https://github.com/huggingface/ai-deadlines

## File: huggingface_ai-deadlines/agents/agent.py

Prompts

```
['run the 3-stage pipeline to find and update conference deadlines using retrieval, aggregation, and push agents', 'run multiple retrieval agents sequentially to search the web for conference deadline information', 'run an aggregation agent to perform majority vote over retrieval results and synthesize consensus', 'run a push agent to write updated YAML and commit changes directly to the main branch', 'run a single Claude agent query with structured output and automatic retries on silent exits', 'run the modal agent to process a single conference like neurips and push updates to main', 'run the modal agent to process all conferences sequentially and push each update to main', 'deploy the modal agent for weekly scheduled runs on Sunday midnight UTC', 'run the modal agent to process a limited subset of conferences for testing', 'get a sorted list of all conference names from the conferences directory yml files']
```

Usage

```
{'run_conference_deadline_pipeline': 'run the 3-stage pipeline to find and update conference deadlines using retrieval, aggregation, and push agents', 'run_retrieval_agents': 'run multiple retrieval agents sequentially to search the web for conference deadline information', 'run_aggregation_agent': 'run an aggregation agent to perform majority vote over retrieval results and synthesize consensus', 'run_push_agent': 'run a push agent to write updated YAML and commit changes directly to the main branch', 'run_agent_with_retry': 'run a single Claude agent query with structured output and automatic retries on silent exits'}
```

## File: huggingface_ai-deadlines/agents/modal_agent.py

Prompts

```
['run the 3-stage pipeline to find and update conference deadlines using retrieval, aggregation, and push agents', 'run multiple retrieval agents sequentially to search the web for conference deadline information', 'run an aggregation agent to perform majority vote over retrieval results and synthesize consensus', 'run a push agent to write updated YAML and commit changes directly to the main branch', 'run a single Claude agent query with structured output and automatic retries on silent exits', 'run the modal agent to process a single conference like neurips and push updates to main', 'run the modal agent to process all conferences sequentially and push each update to main', 'deploy the modal agent for weekly scheduled runs on Sunday midnight UTC', 'run the modal agent to process a limited subset of conferences for testing', 'get a sorted list of all conference names from the conferences directory yml files']
```

Usage

```
{'run_modal_agent_single_conference': 'run the modal agent to process a single conference like neurips and push updates to main', 'run_modal_agent_all_conferences': 'run the modal agent to process all conferences sequentially and push each update to main', 'run_modal_agent_scheduled': 'deploy the modal agent for weekly scheduled runs on Sunday midnight UTC', 'run_modal_agent_subset': 'run the modal agent to process a limited subset of conferences for testing', 'get_conferences_list': 'get a sorted list of all conference names from the conferences directory yml files'}
```

