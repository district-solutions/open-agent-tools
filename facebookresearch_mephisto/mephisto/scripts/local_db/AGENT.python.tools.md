# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/scripts/local_db/clear_worker_onboarding.py

Prompts

```
["run the script to clear a worker's onboarding qualification by their worker name", 'run the main function to prompt for a worker id and clear their onboarding', 'run clear_onboarding to revoke a specific qualification for a given Worker object', 'review the clear_onboarding function that uses OnboardingRequired.clear_onboarding to revoke qualifications', 'review the main function that finds workers by name and clears their onboarding qualification', 'run the interactive script to review and remove accepted tips from Mephisto task units', 'run the main function to iteratively remove accepted tips from agent states across task units', 'remove a specified tip row from the tips CSV file by tip ID and task run', 'review all accepted tips for a task and choose to remove or keep each one', 'refactor the TipsRemovalType enum to add new removal options beyond REMOVE and KEEP', 'run the review_tips_for_task script to interactively approve or reject tips from a Mephisto task', 'review the TipsReviewType enum with ACCEPTED, REJECTED, and SKIP values for tip review actions', 'refactor the get_index_of_value function to find the index of a property value in a list', 'summarize the _add_row_to_tips_file function that appends accepted tips to a CSV file', 'test the remove_tip_from_metadata function that deletes a rejected tip from the agent state metadata']
```

Usage

```
{'run_clear_worker_onboarding': "run the script to clear a worker's onboarding qualification by their worker name", 'run_main': 'run the main function to prompt for a worker id and clear their onboarding', 'run_clear_onboarding': 'run clear_onboarding to revoke a specific qualification for a given Worker object', 'review_clear_onboarding': 'review the clear_onboarding function that uses OnboardingRequired.clear_onboarding to revoke qualifications', 'review_main': 'review the main function that finds workers by name and clears their onboarding qualification'}
```

## File: facebookresearch_mephisto/mephisto/scripts/local_db/remove_accepted_tip.py

Prompts

```
["run the script to clear a worker's onboarding qualification by their worker name", 'run the main function to prompt for a worker id and clear their onboarding', 'run clear_onboarding to revoke a specific qualification for a given Worker object', 'review the clear_onboarding function that uses OnboardingRequired.clear_onboarding to revoke qualifications', 'review the main function that finds workers by name and clears their onboarding qualification', 'run the interactive script to review and remove accepted tips from Mephisto task units', 'run the main function to iteratively remove accepted tips from agent states across task units', 'remove a specified tip row from the tips CSV file by tip ID and task run', 'review all accepted tips for a task and choose to remove or keep each one', 'refactor the TipsRemovalType enum to add new removal options beyond REMOVE and KEEP', 'run the review_tips_for_task script to interactively approve or reject tips from a Mephisto task', 'review the TipsReviewType enum with ACCEPTED, REJECTED, and SKIP values for tip review actions', 'refactor the get_index_of_value function to find the index of a property value in a list', 'summarize the _add_row_to_tips_file function that appends accepted tips to a CSV file', 'test the remove_tip_from_metadata function that deletes a rejected tip from the agent state metadata']
```

Usage

```
{'run_remove_accepted_tips_script': 'run the interactive script to review and remove accepted tips from Mephisto task units', 'run_main_tips_removal': 'run the main function to iteratively remove accepted tips from agent states across task units', 'remove_tip_from_tips_file': 'remove a specified tip row from the tips CSV file by tip ID and task run', 'review_accepted_tips_interactive': 'review all accepted tips for a task and choose to remove or keep each one', 'refactor_TipsRemovalType_enum': 'refactor the TipsRemovalType enum to add new removal options beyond REMOVE and KEEP'}
```

## File: facebookresearch_mephisto/mephisto/scripts/local_db/review_tips_for_task.py

Prompts

```
["run the script to clear a worker's onboarding qualification by their worker name", 'run the main function to prompt for a worker id and clear their onboarding', 'run clear_onboarding to revoke a specific qualification for a given Worker object', 'review the clear_onboarding function that uses OnboardingRequired.clear_onboarding to revoke qualifications', 'review the main function that finds workers by name and clears their onboarding qualification', 'run the interactive script to review and remove accepted tips from Mephisto task units', 'run the main function to iteratively remove accepted tips from agent states across task units', 'remove a specified tip row from the tips CSV file by tip ID and task run', 'review all accepted tips for a task and choose to remove or keep each one', 'refactor the TipsRemovalType enum to add new removal options beyond REMOVE and KEEP', 'run the review_tips_for_task script to interactively approve or reject tips from a Mephisto task', 'review the TipsReviewType enum with ACCEPTED, REJECTED, and SKIP values for tip review actions', 'refactor the get_index_of_value function to find the index of a property value in a list', 'summarize the _add_row_to_tips_file function that appends accepted tips to a CSV file', 'test the remove_tip_from_metadata function that deletes a rejected tip from the agent state metadata']
```

Usage

```
{'run_review_tips_for_task': 'run the review_tips_for_task script to interactively approve or reject tips from a Mephisto task', 'review_TipsReviewType': 'review the TipsReviewType enum with ACCEPTED, REJECTED, and SKIP values for tip review actions', 'refactor_get_index_of_value': 'refactor the get_index_of_value function to find the index of a property value in a list', 'summarize_add_row_to_tips_file': 'summarize the _add_row_to_tips_file function that appends accepted tips to a CSV file', 'test_remove_tip_from_metadata': 'test the remove_tip_from_metadata function that deletes a rejected tip from the agent state metadata'}
```

